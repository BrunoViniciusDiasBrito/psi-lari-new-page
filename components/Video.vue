<template>
  <section class="video-one">
    <div
      class="container"
      style="background-image: url(/assets/images/resources/video-bg-1-1.jpg);"
    >
      <a
        href="https://www.instagram.com/tv/CbXnr9klr3O/?utm_source=ig_web_copy_link"
        class="video-one__btn video-popup"
        ><i class="fa fa-play"></i
      ></a>
      <div class="video-title">
        <h2>Watch Our Video</h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Video",
  mounted() {
    new GLightbox({
      selector: ".video-popup",
      touchNavigation: true,
      loop: true,
      autoplayVideos: true
    });
  }
};
</script>

<style scoped></style>
