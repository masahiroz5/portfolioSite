<template>
  <div>
    <Header />
    <main>
      <Nuxt />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/header.vue";
import Footer from "@/components/footer.vue";
export default {
  components: {
    Header,
    Footer,
  },
};
</script>
<style>
	main {
		max-width: 1200px;
		width: 100%;
		min-height: 700px;
		margin: auto;
		background-color: #EEEEEE;
		text-align: center;
		padding: 60px;
		border-radius:99px;
	}
</style>
