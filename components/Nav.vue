<template>
  <div>
    <header
      :class="
        `site-header-one stricky site-header-one__fixed-top ${
          sticky ? 'stricked-menu stricky-fixed' : ''
        }`
      "
    >
      <div class="container-fluid">
        <div class="site-header-one__logo">
          <a href="/">
            <img src="/assets/images/logo-1-1.png" width="129" alt="" />
          </a>
          <span class="side-menu__toggler"><i class="fa fa-bars"></i></span
          ><!-- /.side-menu__toggler -->
        </div>
        <!-- /.site-header-one__logo -->
        <div class="main-nav__main-navigation">
          <ul class="main-nav__navigation-box one-page-scroll-menu">
            <li class="scrollToLink">
              <a href="/#home">Home</a>
            </li>
            <li class="scrollToLink"><a href="/#features">Features</a></li>
            <li class="scrollToLink"><a href="/#pricing">Pricing</a></li>
            <li class="scrollToLink">
              <a href="/#testimonials">Testimonials</a>
            </li>
            <li class="scrollToLink"><a href="/#screens">Screens</a></li>
            <li class="dropdown  scrollToLink">
              <a href="/#blog">News</a>
              <ul>
                <li><nuxt-link to="/blog">News</nuxt-link></li>
                <li><nuxt-link to="/blog-details">News Details</nuxt-link></li>
              </ul>
            </li>
          </ul>
          <!-- /.main-nav__navigation-box -->
        </div>
        <!-- /.main-nav__main-navigation -->
        <div class="main-nav__right">
          <a href="#" class="thm-btn"><span>Download App</span></a>
        </div>
        <!-- /.main-nav__right -->
      </div>
      <!-- /.container-fluid -->
    </header>

    <div class="side-menu__block">
      <div class="side-menu__block-overlay custom-cursor__overlay">
        <div class="cursor"></div>
        <div class="cursor-follower"></div>
      </div>
      <div class="side-menu__block-inner ">
        <div class="side-menu__top justify-content-end">
          <a href="#" class="side-menu__toggler side-menu__close-btn">
            <img src="assets/images/shapes/close-1-1.png" alt="" />
          </a>
        </div>
        <nav class="mobile-nav__container">
          <!-- content is loading via js -->
        </nav>
        <div class="side-menu__sep"></div>
        <!-- /.side-menu__sep -->
        <div class="side-menu__content">
          <p>
            Lorem Ipsum is simply dummy text the printing and setting industry.
            Lorm Ipsum has been the industry's stanard dummy text ever.
          </p>
          <p>
            <a href="mailto:needhelp@apton.com">needhelp@apton.com</a><br />
            <a href="tel:888-999-0000">888 9990000</a>
          </p>
          <div class="side-menu__social">
            <a href="#"><i class="fab fa-facebook-square"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-pinterest-p"></i></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
      sticky: false,
      mobileToggle: false
    };
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 70) {
        this.sticky = true;
      } else if (window.scrollY < 70) {
        this.sticky = false;
      }
    }
  }
};
</script>

<style scoped></style>
