<template>
  <section class="brand-one">
    <div class="container">
      <div class="brand-one__carousel">
        <client-only>
          <!-- important to add no-ssr-->
          <carousel
            :items="5"
            :autoplay="true"
            :nav="false"
            :dots="false"
            :margin="100"
            :responsive="{
              0: { items: 2 },
              640: { items: 3 },
              992: { items: 4 },
              1024: { items: 5 }
            }"
          >
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
            <div class="item">
              <img src="/assets/images/resources/brand-1-1.png" alt="" />
            </div>
            <!-- /.item -->
          </carousel>
        </client-only>
      </div>
      <!-- /.brand-one__carousel owl-carousel thm__owl-carousel owl-theme -->
    </div>
    <!-- /.container -->
  </section>
</template>

<script>
export default {
  name: "Brands"
};
</script>

<style scoped></style>
