<template>
<!-- Why Us Section -->
  <section id="whyus" class="px-2 py-lg-5 bg-white">
    <b-container>
      <header>
        <h2 class="text-center mb-5 pt-3">
          <small class="text-muted"><strong v-html="this.$store.state.jsonData.sections.aboutus.subtitle"></strong></small><br />
          <span v-html="this.$store.state.jsonData.sections.aboutus.title"></span>
        </h2>
      </header>
      <b-container>
        <b-row class="my-2 my-lg-5 py-2 py-lg-5">
          <b-col v-for="about in this.$store.state.jsonData.sections.aboutus.content" v-bind:key="about.number" cols="12" lg="6" class="">
            <div class="icon">
              <span class="text-muted pr-3 d-none d-md-inline">{{ about.number }}</span>
              <b-img :src="about.icon" fluid height="54" alt="Responsive image"></b-img>
            </div>
            <h4 class="text-muted my-4"><strong>{{ about.title }}</strong></h4>
            <div class="">{{ about.text }}</div>
          </b-col>
          <div class="line"></div>
        </b-row>
        <div class="about-us-btn"><button><a href="/About">About Us</a></button></div>
      </b-container>
    </b-container>
  </section>  
</template>

<script>

export default {
  data() {
    return {
      publicPath: process.env.baseUrl,
    };
  },
};
</script>