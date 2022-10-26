<template>
  <div class="home">
    <div class="home__header">
      <h1>Site building in progress :)</h1>
      <button>Dashboard</button>
    </div>
    <div>
      <img
        class="temp-illustration"
        src="../assets/Illustrations/Sample-38.svg"
      />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    // HelloWorld,
  },
};
</script>

<style lang="scss" scoped>
.home__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.temp-illustration {
  height: 100%;
  width: 100%;
}
</style>
