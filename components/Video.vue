<template>
  <!-- Youtube Video Section -->
  <section id="video" class="py-2 py-xl-5">
    <b-row no-gutters>
      <b-col xl="3" offset-xl="1" class="p-2 p-xl-5 text-center text-xl-right">
        <header>

            <b-img :src="publicPath + '/assets/imgs/logo/greendivider.png'" alt="" height="90" class="pt-3 d-none d-lg-inline" ></b-img>

            <h2 class="insight2 text-dark mb-1 mb-lg-5 pb-2 pt-3">
              <small class="text-muted mt-5"><strong>{{ this.$store.state.jsonData.sections.video.subtitle }}</strong></small>
              
              <br />
              <span style="color: #343a40 !important" v-html="this.$store.state.jsonData.sections.video.title"></span>
            </h2>

            <a class="btn btn-success py-3 px-5 text-white border-0 font-weight-normal" href="https://www.youtube.com/channel/UCwx88crK6W9gZFxwcolU_dQ" target="_blank">View More On YOUTUBE</a>

        </header>
      </b-col>

      <b-col xl="8" class="youtube-video">
        <b-embed type="video" aspect="16by9" controls :poster=" publicPath + this.$store.state.jsonData.sections.video.content.poster ">
          <source :src="publicPath + this.$store.state.jsonData.sections.video.content.url " type="video/mp4">
        </b-embed>
      </b-col>
      
    </b-row>
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
