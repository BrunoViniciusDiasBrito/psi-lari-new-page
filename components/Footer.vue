<template>
  <div>
    <footer class="site-footer">
      <div class="site-footer-bg" style="background-image: url(/assets/images/resources/footer-bg-shape-1.png)">
      </div>
      <div class="container">
        <div class="row">
          <div class="col-xl-12">
            <div class="footer-upper text-center">
              <div class="footer-logo">
                <img src="/assets/images/resources/footer-logo.png" alt="Footer Logo">
              </div>
              <ul class="footer-widget__social">
                <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                <li><a href="#" class="color-1"><i class="fab fa-facebook"></i></a></li>
                <li><a href="#" class="color-2"><i class="fab fa-pinterest-p"></i></a></li>
                <li><a href="#" class="color-3"><i class="fab fa-instagram"></i></a></li>
              </ul>
              <div class="footer-menu">
                <ul>
                  <li><a href="#">Home</a></li>
                  <li><a href="#">Features</a></li>
                  <li><a href="#">Pricing</a></li>
                  <li><a href="#">Team</a></li>
                  <li><a href="#">Screens</a></li>
                  <li><a href="#">News</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="site-footer__bottom">
        <div class="container text-center">
          <p>© copyright 2021 by <a href="#">Layerdrops.com</a></p>
        </div><!-- /.container -->
      </div>
    </footer>

    <a @click="scrollTop" class="scroll-to-target scroll-to-top" :style="`display: ${scrollBtn ? 'inline' : 'none'}`" href="#"><i class="fa fa-angle-up"></i></a>

  </div>
</template>

<script>
  export default {
    name: "Footer",
    data(){
      return {
        scrollBtn: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },

    methods: {

      handleScroll () {

        if (window.scrollY > 70) {
          this.scrollBtn = true
        }
        else if (window.scrollY < 70) {
          this.scrollBtn = false
        }
      },

      scrollTop () {
        window.scrollTo(0, 0);
      }


    }
  }
</script>

<style scoped>

</style>
