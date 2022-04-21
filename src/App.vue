<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";
import Header from "@/components/Header.vue";
export default {
  components: { MenuLateral, Main, Header, Footer },
};
</script>
<template>
  <MenuLateral />
  <Header />
  <Main />  
  <Footer />
</template>
<style></style>
