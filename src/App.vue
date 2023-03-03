<template>
  <div>
    <Navbar />
    <router-view />
    <Footer />
  </div>
</template>
<script>
import Navbar from "@/layouts/Navbar.vue";
import Footer from "@/layouts/Footer.vue";
export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
*{
  font-family: 'Inter', sans-serif;
  width: 1240;
}

:root{
  --white: #fff;
  --green: #05A55A;
  --f6:#f6f6f6;
  --gray:#747474;
  --black:#000;
}
</style>

