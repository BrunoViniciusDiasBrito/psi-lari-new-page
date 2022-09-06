<template>
  <div>
    <Nav />
    <PageHeader title="News" />
    <BlogPage />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import BlogPage from "../components/BlogPage";
  import Footer from "../components/Footer";
  export default {
    components: {Footer, BlogPage, PageHeader, Nav},
    head(){
      return {
        title: "Piloz | Blog"
      }
    }
  }
</script>
