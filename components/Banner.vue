<template>
  <section class="banner-one" id="home">
    <img
      src="/assets/images/banner/banner-shape-1-1.png"
      alt="Banner-Shape-1"
      class="banner-shape-1"
    />
    <img
      src="/assets/images/banner/banner-shape-1-2.png"
      alt="Banner-Shape-2"
      class="banner-shape-2"
    />
    <div
      class="banner-one__bg"
      style="background-image: url(assets/images/banner/banner-bg-1.png);"
    ></div>
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="banner-one__content">
            <h3>Psicóloga<br />Larissa Caroline<br />Benedito</h3>
            <h4>Usando uma abordagem Humanista</h4>
            <p>
              Eu te ajudarei a identificar os problemas que o aflingem e a
              melhorar seus relacionamentos em geral.
            </p>
            <a href="/#sobre-mim" class="thm-btn"><span>SOBRE MIM</span></a>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="banner-img wow fadeInUp" data-wow-duration="1500ms">
            <img
              src="/assets/images/shapes/banner-1-1.png"
              class="banner-image__curvs"
              alt=""
            />
            <div
              class="banner-bg"
              style="background-image: url(/assets/images/banner/banner-shape-1-4.png)"
            ></div>
            <img
              src="/assets/images/banner/insta-profile.png"
              alt="Banner-img"
            />
            <div class="banner-icon-1">
              <i class="piloz-lamp"></i>
            </div>
            <div class="banner-icon-2">
              <i class="piloz-linked"></i>
            </div>
            <div class="banner-icon-3">
              <i class="piloz-human-resources"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Banner"
};
</script>

<style scoped></style>
