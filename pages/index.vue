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
import Brands from "../components/Brands";
import Subscribe from "../components/Subscribe";
import Footer from "../components/Footer";
export default {
  head: {
    title: "Larissa Caroline Benedito"
  },
  components: {
    Footer,
    Subscribe,
    Brands,
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
};
</script>
