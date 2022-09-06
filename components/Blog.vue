<template>
  <section class="blog-one" id="blog">
      <div class="blog-1-shape-1" style="background-image: url(/assets/images/blog/blog-1-shape-1.png)"></div>
      <div class="blog-1-shape-2" style="background-image: url(/assets/images/blog/blog-1-shape-2.png)"></div>
      <div class="blog-1-shape-3" style="background-image: url(/assets/images/blog/blog-1-shape-3.png)"></div>
      <div class="container">
        <div class="block-title text-center">
          <p>From the Blog Posts</p>
          <h3>News & Articles</h3>
        </div><!-- /.block-title text-center -->
        <div class="row">
        <div class="col-lg-4 ">
          <div class="blog-one__single">
            <div class="blog-one__image">
              <img src="/assets/images/blog/blog-1-1.jpg" alt="">
              <div class="blog-hover-box">
                <div class="box">
                  <div class="icon-box">
                    <a href="#"><i class="far fa-link"></i></a>
                  </div>
                </div>
              </div>
            </div><!-- /.blog-one__image -->
            <div class="blog-one__content">
              <div class="blog-one__meta">
                <a href="#"><i class="far fa-calendar-alt"></i> 20 May, 2020</a>
                <a href="#"><i class="far fa-comments"></i> 2 comments</a>
              </div><!-- /.blog-one__meta -->
              <h3><nuxt-link to="/blog-details">Capitalize on low hanging fruit to</nuxt-link></h3>
              <div class="blog-one__text">
                <p>There are many people variation of passages of lorem Ipsum available in the
                  majority sed do eius.</p>
              </div>
              <nuxt-link to="/blog-details" class="thm-btn blog-one__btn"><span>Read More</span></nuxt-link>
            </div>
          </div>
        </div>
        <div class="col-lg-4 ">
          <div class="blog-one__single">
            <div class="blog-one__image">
              <img src="/assets/images/blog/blog-1-2.jpg" alt="">
              <div class="blog-hover-box">
                <div class="box">
                  <div class="icon-box">
                    <nuxt-link to="#"><i class="far fa-link"></i></nuxt-link>
                  </div>
                </div>
              </div>
            </div><!-- /.blog-one__image -->
            <div class="blog-one__content">
              <div class="blog-one__meta">
                <a href="#"><i class="far fa-calendar-alt"></i> 20 May, 2020</a>
                <a href="#"><i class="far fa-comments"></i> 2 comments</a>
              </div><!-- /.blog-one__meta -->
              <h3><nuxt-link to="/blog-details">Collaboratively admin istrate via </nuxt-link></h3>
              <div class="blog-one__text">
                <p>There are many people variation of passages of lorem Ipsum available in the
                  majority sed do eius.</p>
              </div>
              <nuxt-link to="/blog-details" class="thm-btn blog-one__btn"><span>Read More</span></nuxt-link>
            </div>
          </div>
        </div>
        <div class="col-lg-4 ">
          <div class="blog-one__single">
            <div class="blog-one__image">
              <img src="/assets/images/blog/blog-1-3.jpg" alt="">
              <div class="blog-hover-box">
                <div class="box">
                  <div class="icon-box">
                    <a href="#"><i class="far fa-link"></i></a>
                  </div>
                </div>
              </div>
            </div><!-- /.blog-one__image -->
            <div class="blog-one__content">
              <div class="blog-one__meta">
                <a href="#"><i class="far fa-calendar-alt"></i> 20 May, 2020</a>
                <a href="#"><i class="far fa-comments"></i> 2 comments</a>
              </div><!-- /.blog-one__meta -->
              <h3><nuxt-link to="/blog-details">Efficiently unleash cross-media</nuxt-link></h3>
              <div class="blog-one__text">
                <p>There are many people variation of passages of lorem Ipsum available in the
                  majority sed do eius.</p>
              </div>
              <nuxt-link to="/blog-details" class="thm-btn blog-one__btn"><span>Read More</span></nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Blog"
    }
</script>

<style scoped>

</style>
