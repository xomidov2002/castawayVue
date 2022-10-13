<template>
  <section class="about">
    <div class="container">
      <div class="info-man">
        <div class="info">
          <button class="btn">
            <i class="fas fa-arrow-right"></i>
          </button>
          <a href="#">Meet your host</a>
          <h3 class="name">Jacob Paulaner</h3>
          <p class="first">
            Jacob has a background in audio engineering, and has been podcasting
            since the early days.
          </p>
          <p class="second">
            He’s here to help you level up your game by sharing everything he’s
            learned along the way.
          </p>
        </div>
        <div class="image">
          <img class="image" src="../assets/images/Frame.jpg" alt="" />
        </div>
      </div>
      <ContactForm />
    </div>
  </section>
</template>

<script>
import "../assets/media.css"
import ContactForm from "../components/contactForm.vue";
export default {
  components: {
    ContactForm,
  },
};
</script>

<style lang="scss">
.about {
  margin-top: 200px;
  .container {
    .info-man {
      display: flex;
      justify-content: space-between;
      align-items: center;

      .info {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        .btn {
          width: 112px;
          height: 112px;
          border: none;
          border-radius: 50%;
          background: #118da8;
          margin-bottom: 20px;
          i {
            background: #118da8;
            font-size: 40px;
            color: #fff;
          }
        }
        a {
          font-weight: 400;
          font-size: 18px;
          line-height: 27px;
          color: #118da8;
        }
        .name {
          font-weight: 400;
          font-size: 65px;
          line-height: 79.2px;
          letter-spacing: 2.88px;
          color: #fff;
          margin-bottom: 28px;
        }
        .first {
          max-width: 556px;
          font-weight: 400;
          font-size: 22px;
          line-height: 33px;
          color: rgb(255, 255, 255, 0.7);
          margin-bottom: 33px;
        }
        .second {
          max-width: 528px;
          font-weight: 400;
          font-size: 22px;
          line-height: 33px;
          color: rgb(255, 255, 255, 0.7);
        }
      }
      .image {
        border-radius: 13px;
        max-width: 650px;
        img {
          object-fit: cover;
        }
      }
    }
  }
}
</style>