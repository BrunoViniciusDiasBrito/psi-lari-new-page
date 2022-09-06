<template>
  <section id="pricing" class="pricing-one">
    <div class="pricing-one-shape-1" style="background-image: url(/assets/images/shapes/pricing-1-shape-1.png)">
    </div>
    <div class="container">
      <div class="block-title text-center">
        <p>Choose Our Pricing</p>
        <h3>Our Pricing Plans</h3>
      </div><!-- /.block-title text-center -->
      <ul class="list-inline text-center switch-toggler-list" role="tablist" id="switch-toggle-tab">
        <li class="month active"><a href="#">Monthly</a></li>
        <li>
          <!-- Rounded switch -->
          <label class="switch on">
            <span class="slider round"></span>
          </label>
        </li>
        <li class="year"><a href="#">Annualy</a></li>
      </ul><!-- /.list-inline -->

      <div class="tabed-content">
        <div id="month">
          <div class="row">
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle">
                  <div class="count">
                    <h4>01</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$20.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check"></i>Extra features</li>
                  <li><i class="fa fa-check"></i>Lifetime free support</li>
                  <li><i class="fa fa-check"></i>Upgrate options</li>
                  <li><i class="fa fa-check"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle circle-color-2">
                  <div class="count count-color-2">
                    <h4>02</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$30.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check icon-color-2"></i>Extra features</li>
                  <li><i class="fa fa-check icon-color-2"></i>Lifetime free support</li>
                  <li><i class="fa fa-check icon-color-2"></i>Upgrate options</li>
                  <li><i class="fa fa-check icon-color-2"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle circle-color-3">
                  <div class="count count-color-3">
                    <h4>03</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$60.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check icon-color-3"></i>Extra features</li>
                  <li><i class="fa fa-check icon-color-3"></i>Lifetime free support</li>
                  <li><i class="fa fa-check icon-color-3"></i>Upgrate options</li>
                  <li><i class="fa fa-check icon-color-3"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
          </div>
        </div>
        <div id="year">
          <div class="row">
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle">
                  <div class="count">
                    <h4>01</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$20.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check"></i>Extra features</li>
                  <li><i class="fa fa-check"></i>Lifetime free support</li>
                  <li><i class="fa fa-check"></i>Upgrate options</li>
                  <li><i class="fa fa-check"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle circle-color-2">
                  <div class="count count-color-2">
                    <h4>02</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$30.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check icon-color-2"></i>Extra features</li>
                  <li><i class="fa fa-check icon-color-2"></i>Lifetime free support</li>
                  <li><i class="fa fa-check icon-color-2"></i>Upgrate options</li>
                  <li><i class="fa fa-check icon-color-2"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
            <div class="col-xl-4 animated fadeInLeft">
              <div class="pricing-one__single">
                <div class="circle circle-color-3">
                  <div class="count count-color-3">
                    <h4>03</h4>
                  </div>
                </div>
                <div class="price">
                  <h2>$60.00</h2>
                  <p>Basic Pack</p>
                </div>
                <ul class="list-unstyled pricing-one__list">
                  <li><i class="fa fa-check icon-color-3"></i>Extra features</li>
                  <li><i class="fa fa-check icon-color-3"></i>Lifetime free support</li>
                  <li><i class="fa fa-check icon-color-3"></i>Upgrate options</li>
                  <li><i class="fa fa-check icon-color-3"></i>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"><span>Choose Plan</span></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "Pricing",
      mounted() {

        function toggleTabWithSwitch() {
          var toggleSwitch = $('#switch-toggle-tab label.switch');
          var monthTabTitle = $('#switch-toggle-tab li.month');
          var yearTabTitle = $('#switch-toggle-tab li.year');
          var monthTabContent = $('#month');
          var yearTabContent = $('#year');
          // hidden show deafult;
          monthTabContent.fadeIn();
          yearTabContent.fadeOut();

          function toggleHandle() {
            if (toggleSwitch.hasClass('on')) {
              yearTabContent.fadeOut();
              monthTabContent.fadeIn();
              monthTabTitle.addClass('active');
              yearTabTitle.removeClass('active');
            } else {
              monthTabContent.fadeOut();
              yearTabContent.fadeIn();
              yearTabTitle.addClass('active');
              monthTabTitle.removeClass('active');
            }
          };
          monthTabTitle.on('click', function() {
            toggleSwitch.addClass('on').removeClass('off');
            toggleHandle();
            return false;
          });
          yearTabTitle.on('click', function() {
            toggleSwitch.addClass('off').removeClass('on');
            toggleHandle();
            return false;
          });
          toggleSwitch.on('click', function() {
            toggleSwitch.toggleClass('on off');
            toggleHandle();
          });

        }
        toggleTabWithSwitch();
      }
    }
</script>

<style scoped>

</style>
