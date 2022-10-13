<template>
  <section class="navbar" :class="{ active: add_active === true }">
    <div class="container">
      <img src="../assets/images/logo.png" alt="logo" />
      <ul class="menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">Episodes</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <div class="burger">
        <i class="fas fa-bars" @click="add_active = true"></i>
        <i class="fas fa-times" @click="add_active = false"></i>
      </div>
    </div>
  </section>
</template>

<script>
import "../assets/mainStyle.css";
import "../assets/media.css";
export default {
  data() {
    return{
      add_active: false
    }
  }
};
</script>

<style lang="scss">
.navbar {
  background: #191919;
  .container {
    width: 1300px;
    margin: 0 auto;
    padding: 43px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    .menu {
      display: flex;
      gap: 40px;
      li a {
        color: #fff;
        font-weight: 400;
        font-size: 17px;
        line-height: 27px;
        &:hover {
          color: #118da8;
        }
      }
    }
    .burger {
      position: relative;
      z-index: 3;
      display: none;
      color: #fff;
      width: 40px;
      height: 40px;
      justify-content: center;
      align-items: center;
      border: 1px solid #fff;
      border-radius: 6px;
      font-size: 20px;
      transition: 0.5s;
      
      .fa-times{
        display: none;
        transition: 0.3s;
      }
      .fa-bars{
        display: block;
        transition: 0.3s;
      }
    }
  }
  &.active{
    .burger{
      .fa-times{
        display: block;
      }
      .fa-bars{
        display: none;
      }
    }
  }
}
</style>