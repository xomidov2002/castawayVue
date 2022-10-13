<template>
  <section class="tests">
    <Card />
  </section>
</template>

<script>
import Card from "../components/testimonialsCard.vue";
export default {
  components: {
    Card,
  },
  props: {
    item: {
      type: Object,
      required: true,
    },
  },
  data() {
    return {
      
    };
  },
  methods: {},
};
</script>

<style lang="scss">
.tests {
  margin-top: 200px;
  margin-bottom: 200px;
  .container{
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    
  }
}
</style>