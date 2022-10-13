<template>
  <section class="cards">
    <div class="container">
      <!-- CARD -->
      <div class="card">
        <img src="../assets/images/card-1.jpg" alt="" />
        <div class="title">
          <button class="name">Gear</button>
          <h3 class="epis">Episode 3</h3>
          <h1>Should you get outboard audio gear?</h1>
          <p class="text">
            Is hardware really worth it when it comes to podcasting? The answer
            is...it depends. Heres our reasons on why you might want to consider
            picking something up.
          </p>
          <button class="btn">View Episodes Details</button>
        </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <img src="../assets/images/card-2.jpg" alt="" />
        <div class="title">
          <button class="name">Tips & Tricks</button>
          <h3 class="epis">Episode 2</h3>
          <h1>Mic tricks to take you to the next level</h1>
          <p class="text">
            Stop rolling with those default settings on your mic. These small
            tweaks will take you from sounding good to great.
          </p>
          <button class="btn">View Episodes Details</button>
        </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <img src="../assets/images/card-3.jpg" alt="" />
        <div class="title">
          <button class="name">Gear</button>
          <h3 class="epis">Episode 1</h3>
          <h1>The best microphone under $200</h1>
          <p class="text">
            With so many microphones on the market, how are you supposed to know
            what’s the best? Take a look at our top picks.
          </p>
          <button class="btn">View Episodes Details</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss">
.cards {
  color: #fff;
  .container {
    .card {
      margin-bottom: 60px;
      background: #000;
      border-radius: 32px;
      padding: 40px;
      display: flex;
      gap: 53px;
      align-items: center;
      .title {
        background: none;
        .name {
          font-weight: 400;
          font-size: 18px;
          line-height: 27px;
          border-radius: 6px;
          padding: 0 16px;
          margin-bottom: 48px;
          color: #fff;
          border: none;
          cursor: pointer;
        }
        .epis {
          color: #118da8;
          background: none;
          font-weight: 400;
          font-size: 17px;
          line-height: 27px;
          margin-bottom: 18px;
        }
        h1 {
          max-width: 701px;
          font-weight: 400;
          font-size: 64px;
          line-height: 70px;
          letter-spacing: 2.56px;
          background: none;
          margin-bottom: 28px;
        }
        .text {
          max-width: 757px;
          background: none;
          font-weight: 400;
          font-size: 22px;
          line-height: 33px;
          opacity: 0.7;
          margin-bottom: 18px;
        }
        .btn {
          padding: 12px 20px;
          background: #118da8;
          color: white;
          border-radius: 6px;
          font-weight: 400;
          font-size: 18px;
          line-height: 27px;
        }
      }
    }
  }
}
</style>