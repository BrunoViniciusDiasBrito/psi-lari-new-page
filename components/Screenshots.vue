<template>
  <section class="app-shot-one" id="screens">
    <div class="container-fluid">
      <div class="block-title text-center">
        <p>Check Before Choosing</p>
        <h3>App Screenshots</h3>
      </div>
      <!-- /.block-title -->

      <div class="app-shot-one__carousel owl-dot-type1">
        <client-only>
          <!-- important to add no-ssr-->
          <carousel
            :items="5"
            :autoplay="true"
            :nav="false"
            :dots="true"
            :margin="30"
            :responsive="{
              0: { items: 1 },
              640: { items: 3 },
              992: { items: 4 },
              1024: { items: 5 }
            }"
          >
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-1.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-2.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-3.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-4.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-5.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->

            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-1.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-2.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-3.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-4.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-5.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-1.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-2.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-3.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-4.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
            <div class="item">
              <img
                src="/assets/images/app-shots/app-shot-n-1-5.png"
                alt="Awesome Image"
              />
            </div>
            <!-- /.item -->
          </carousel>
        </client-only>
      </div>
      <!-- /.app-shot-one__carousel owl-theme owl-carousel -->
    </div>
    <!-- /.container-fluid -->
  </section>
</template>

<script>
export default {
  name: "Screenshots"
};
</script>

<style scoped></style>
