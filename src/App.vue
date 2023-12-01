<template>
  <div class="home">
    <NumberList />
  </div>
</template>

<script>
import NumberList from "@/components/NumberList.vue";

export default {
  name: "HomeView",
  components: {
    NumberList,
  },
};
</script>
