<template>
  <div class="container">
    <div class="testimonials"
      v-for="item in array"
      :key="item.id"
    >
      <ul>
        <li v-for="i in item.star" :key="i"><i class="fas fa-star"></i></li>
      </ul>
      <p class="comment">
        {{ item.comment }}
      </p>
      <p class="name">{{ item.name }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      array: [
        {
          id: 1,
          star: 4,
          name: "Betty Lacey",
          comment: "I can’t recommend this podcast enough",
        },
        {
          id: 2,
          star: 5,
          name: "Adam Driver",
          comment: "Jacob is the best in the business",
        },
        {
          id: 3,
          star: 3,
          name: "Marcus Brown",
          comment: "A wealth of audio knowledge",
        },
        {
          id: 2,
          star: 4,
          name: "Jessica Knowl",
          comment: "Every episode is a gem!",
        },
        {
          id: 4,
          star: 5,
          name: "Scott Adams",
          comment: "Whoa whoa, let me take some notes!",
        },
        {
          id: 6,
          star: 3,
          name: "Steven Blast",
          comment: "I’ve upped my game considerably since I started listening",
        },
      ],
    };
  },
  methods: {},
};
</script>

<style lang="scss">
.container {
  .testimonials {
    width: 423px;
    height: 364px;
    background: #000;
    border-radius: 32px;
    padding: 54px 50px;
    ul {
      display: flex;
      gap: 6px;
      margin-bottom: 22px;
      background: #000;
      li {
        i {
          color: yellow;
          background: #000;
        }
      }
    }
    .comment {
      color: #fff;
      background: #000;
      max-width: 313px;
      font-weight: 400;
      font-size: 35px;
      line-height: 43.2px;
      margin-bottom: 19px;
      height: 173px;
      overflow-y: initial;
      overflow-x: hidden;
    }
    .name {
      color: rgb(255, 255, 255, 0.7);
      background: #000;
      font-weight: 400;
      font-size: 24px;
      line-height: 28.8px;
    }
  }
}
</style>