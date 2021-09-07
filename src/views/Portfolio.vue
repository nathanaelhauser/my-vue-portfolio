<template>
  <div class="portfolio">
    <h1>This is the portfolio page</h1>

    <!-- Setup a loop of cards -->
    <div class="cards">
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
    </div>
  </div>
</template>

<script>
import Card from "@/components/Card.vue";

export default {
  components: { Card },
};
</script>

<style scoped>
.cards {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
</style>
