<template>
  <div>
    <header>
      <h1>Masahiro's Site</h1>
      <HeaderNav />
    </header>
  </div>
</template>

<script>
import HeaderNav from "@/components/headerNav.vue";
export default {
  components: {
    HeaderNav,
  },
};
</script>

<style scoped>
header {
  color: gray;
  padding-left: 50px;
  padding-right: 50px;
  font-size: 20px;
  background-color: white;
  box-shadow: 0px 10px 10px -5px rgba(0,0,0,0.5);
  margin-bottom: 30px;
}
</style>