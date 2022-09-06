<template>
  <div class="page-wrapper">
    <nuxt />
  </div>
</template>


<script>

  export default {
    components: {
    },
    head(){
      return {
        title: "Piloz - Nuxt.js App Landing Template"
      }
    },
    mounted(){
      this.$nextTick(() => {
        this.$nuxt.$loading.start()
        setTimeout(() => this.$nuxt.$loading.finish(), 500)
      })


      //Submenu Dropdown Toggle

      if ($('.main-nav__main-navigation li.dropdown ul').length) {
        $('.main-nav__main-navigation li.dropdown').children('a').append('<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button>');
      }

      function dynamicCurrentMenuClass(selector) {
        let FileName = window.location.href.split('/').reverse()[0];

        selector.find('li').each(function () {
          let anchor = $(this).find('a');
          if ($(anchor).attr('href') == FileName) {
            $(this).addClass('current');
          }
        });
        // if any li has .current elmnt add class
        selector.children('li').each(function () {
          if ($(this).find('.current').length) {
            $(this).addClass('current');
          }
        });
        // if no file name return
        if ('' == FileName) {
          selector.find('li').eq(0).addClass('current');
        }
      }

      // mobile menu

      if ($('.main-nav__main-navigation').length) {
        let mobileNavContainer = $('.mobile-nav__container');
        let mainNavContent = $('.main-nav__main-navigation').html();



        mobileNavContainer.append(function () {
          return mainNavContent;
        });



        //Dropdown Button
        mobileNavContainer.find('li.dropdown .dropdown-btn').on('click', function (e) {
          $(this).toggleClass('open');
          $(this).parent().parent().children('ul').slideToggle(500);
          e.preventDefault();
        });

        // dynamic current class
        let mainNavUL = $('.main-nav__main-navigation').find('.main-nav__navigation-box');
        let mobileNavUL = mobileNavContainer.find('.main-nav__navigation-box');

        dynamicCurrentMenuClass(mainNavUL);
        dynamicCurrentMenuClass(mobileNavUL);


      }

      if ($('.stricky').length) {
        $('.stricky').addClass('original').clone(true).insertAfter('.stricky').addClass('stricked-menu').removeClass('original');
      }


      if ($('.side-menu__toggler').length) {
        $('.side-menu__toggler').on('click', function (e) {
          $('.side-menu__block').toggleClass('active');
          e.preventDefault();
        });
      }

      if ($('.side-menu__block-overlay').length) {
        $('.side-menu__block-overlay').on('click', function (e) {
          $('.side-menu__block').removeClass('active');
          e.preventDefault();
        });
      }


    }
  }
</script>

<style>
</style>
