<template>
  <div>
    <Nav />
    <Banner />
    <Features />
    <CallToAction />
    <Video />
    <CallToActionTwo />
    <Pricing />
    <Testimonial />
    <Screenshots />
    <Faq />
    <Blog />
    <Brands />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
  import Nav from "../components/Nav";
  import Banner from "../components/Banner";
  import Features from "../components/Features";
  import CallToAction from "../components/CallToAction";
  import Video from "../components/Video";
  import CallToActionTwo from "../components/CallToActionTwo";
  import Pricing from "../components/Pricing";
  import Testimonial from "../components/Testimonial";
  import Screenshots from "../components/Screenshots";
  import Faq from "../components/Faq";
  import Blog from "../components/Blog";
  import Brands from "../components/Brands";
  import Subscribe from "../components/Subscribe";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      Subscribe,
      Brands,
      Blog,
      Faq,
      Screenshots,
      Testimonial,
      Pricing,
      CallToActionTwo,
      Video,
      CallToAction,
      Features,
      Banner,
      Nav
    }
  }
</script>
