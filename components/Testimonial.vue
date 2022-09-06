<template>
  <section id="testimonials" class="testimonials-one">
    <div class="testimonials-1-shape-3"
         style="background-image: url(/assets/images/testimonials/testimonials-1-shape-3.png)"></div>
    <div class="testimonials-1-shape-4"
         style="background-image: url(/assets/images/testimonials/testimonials-1-shape-4.png)"></div>
    <div class="testimonials-1-shape-5"
         style="background-image: url(/assets/images/testimonials/testimonials-1-shape-5.png)"></div>
    <div class="container">
      <div class="block-title text-center">
        <p>Our Testimonials</p>
        <h3>What They Says</h3>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <div class="testmonials__carousel owl-dot-type1">
            <client-only> <!-- important to add no-ssr-->
              <carousel :items="2" :autoplay="true" :nav= "false" :margin="30" :responsive="{0: {items: 1},640: {items: 1},992: {items: 2},1024: {items: 2}}">


              <div class="item">
              <div class="testimonials-one__single">
                <p class="testimonials-one__text">This is due to their excellent service,
                  competitive pricing and customer support. It’s throughly refresing to get such a
                  personal touch.</p>
                <div class="testimonials-one__icon">
                  <i class="fa fa-quote-left"></i>
                </div>
                <div class="testimonial-one-shape-1">
                  <img src="/assets/images/testimonials/testimonials-1-shape-1.png"
                       alt="Testimonial Shape1 Image">
                </div>
              </div>
              <div class="testimonials-one-client-info">
                <div class="testimonials-one__image">
                  <img src="/assets/images/testimonials/testimonials-1-img-1.png"
                       alt="Testimonials Image">
                </div>
                <div class="text">
                  <h3>Christine Rose</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="testimonials-one__single color-2">
                <p class="testimonials-one__text">This is due to their excellent service,
                  competitive pricing and customer support. It’s throughly refresing to get such a
                  personal touch.</p>
                <div class="testimonials-one__icon">
                  <i class="fa fa-quote-left"></i>
                </div>
                <div class="testimonial-one-shape-1">
                  <img src="/assets/images/testimonials/testimonials-1-shape-2.png"
                       alt="Testimonial Shape1 Image">
                </div>
              </div>
              <div class="testimonials-one-client-info">
                <div class="testimonials-one__image">
                  <img src="/assets/images/testimonials/testimonials-1-img-2.png"
                       alt="Testimonials Image">
                </div>
                <div class="text">
                  <h3>David Cooper</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="testimonials-one__single">
                <p class="testimonials-one__text">This is due to their excellent service,
                  competitive pricing and customer support. It’s throughly refresing to get such a
                  personal touch.</p>
                <div class="testimonials-one__icon">
                  <i class="fa fa-quote-left"></i>
                </div>
                <div class="testimonial-one-shape-1">
                  <img src="/assets/images/testimonials/testimonials-1-shape-1.png"
                       alt="Testimonial Shape1 Image">
                </div>
              </div>
              <div class="testimonials-one-client-info">
                <div class="testimonials-one__image">
                  <img src="/assets/images/testimonials/testimonials-1-img-1.png"
                       alt="Testimonials Image">
                </div>
                <div class="text">
                  <h3>Christine Rose</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="testimonials-one__single color-2">
                <p class="testimonials-one__text">This is due to their excellent service,
                  competitive pricing and customer support. It’s throughly refresing to get such a
                  personal touch.</p>
                <div class="testimonials-one__icon">
                  <i class="fa fa-quote-left"></i>
                </div>
                <div class="testimonial-one-shape-1">
                  <img src="/assets/images/testimonials/testimonials-1-shape-2.png"
                       alt="Testimonial Shape1 Image">
                </div>
              </div>
              <div class="testimonials-one-client-info">
                <div class="testimonials-one__image">
                  <img src="/assets/images/testimonials/testimonials-1-img-2.png"
                       alt="Testimonials Image">
                </div>
                <div class="text">
                  <h3>David Cooper</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
              </carousel>
            </client-only>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Testimonial"
    }
</script>

<style scoped>

</style>
