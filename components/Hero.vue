/* eslint-disable max-len */
<template>
  <!-- HERO Section -->
  <section id="hero" class="p-2 py-5 py-lg-5 bg-white overflow-hidden">
    <Navbar />
    <div class="layer layer_1" :style="{ backgroundImage: 'url(' + publicPath + '/assets/imgs/hero/layer_1.jpg)' }"></div>
    <div class="layer layer_2" :style="{ backgroundImage: 'url(' + publicPath + '/assets/imgs/hero/layer_2.png)' }"></div>
    <div class="layer layer_3" :style="{ backgroundImage: 'url(' + publicPath + '/assets/imgs/hero/layer_3.png)' }"></div>
    <div class="layer layer_4" :style="{ backgroundImage: 'url(' + publicPath + '/assets/imgs/hero/layer_4.jpg)' }"></div>
    <div class="layer layer_5 animate__animated animate__shakeX animate__infinite" :style="{ backgroundImage: 'url(' + publicPath + '/assets/imgs/hero/layer_5.png)' }"></div>
    <h1 v-html="this.$store.state.jsonData.general.slogan" class="text-center mt-5" style="z-index: 6; position: relative">
    </h1>
  </section>
</template>

<script>

export default {
  data() {
    return {
      publicPath: process.env.baseUrl,
    }
  },
};
</script>