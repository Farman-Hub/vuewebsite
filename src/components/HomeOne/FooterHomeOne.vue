<template>
  <!--====== APPIE FOOTER PART START ======-->

  <section class="appie-footer-area">
    <div class="container" id="Contact">
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="footer-about-widget">
            <div class="logo">
              <a href="#"><img src="@/assets/images/logo-7.png" alt="" /></a>
            </div>
            <!-- <a href="#">Read More <i class="fal fa-arrow-right"></i></a> -->
            <div class="social mt-30">
              <ul>
                <li>
                  <a href="https://www.facebook.com/excelgst"><i class="fab fa-facebook-f"></i></a>
                </li>
                <li>
                  <a href="https://www.linkedin.com/company/excel-security-solutions/"><i class="fab fa-linkedin-in"></i></a>
                </li>
                <li>
                  <a href="https://www.instagram.com/excelsecuritysolutions/"><i class="fab fa-instagram"></i></a>
                </li>
                <li>
                  <a href="https://wa.me/yourwhatsapplink"><i class="fab fa-whatsapp"></i></a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 mt-35 center">
          <p>We are a community-focused security initiative offering bespoke security solutions to residents in the Saanenland region.</p>
          <p>Our services are delivered in collaboration with <span class="highlight">Excel Security Solutions</span>, a recognised leader in private and corporate security.</p>

          

        </div>
        <!-- <div class="col-lg-6 col-md-6">
          <div class="footer-navigation">
            <h4 class="title">Company</h4>
            <ul>
              <li><router-link to="/about-us">About Us</router-link></li>
              <li><router-link to="/service-details">Service</router-link></li>
              <li><a href="#">Case Studies</a></li>
              <li><router-link to="/news">Blog</router-link></li>
              <li><router-link to="/contact">Contact</router-link></li>
            </ul>
          </div>
        </div> -->
        <!-- <div class="col-lg-3 col-md-6">
          <div class="footer-navigation">
            <h4 class="title">Support</h4>
            <ul>
              <li><a href="#">Community</a></li>
              <li><a href="#">Resources</a></li>
              <li><a href="#">Faqs</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Careers</a></li>
            </ul>
          </div>
        </div> -->
        <div class="col-lg-4 col-md-6">
          <div class="footer-widget-info text-center text-lg-right">
            <h4 class="title">Get In Touch</h4>
            <ul>
              <li>
                <a href="mailto:contact@chalert.com">
                  <i class="fal fa-envelope"></i> contact@chalert.ch
                </a>
              </li>

              <li>
                <a href="tel:+41764343113">
                  <i class="fal fa-phone"></i> +41 76 434 31 13
                </a>
              </li>
              <li>
                <a href="https://www.google.com/maps/place/Excel+Security+Solutions+AG/@46.4850781,7.2626024,15z/data=!4m6!3m5!1s0x478ef1af1633e61b:0x1c2a56d16165b7b5!8m2!3d46.4850781!4d7.2626024!16s%2Fg%2F11g6qk75pm?entry=ttu"
                  target="_blank">
                  <i class="fal fa-map-marker-alt"></i> Excel Security Solutions AG <br/> Rübeldorfstrasse 23 <br/> 3792 Saanen <br/>
                  Switzerland
                </a>
              </li>

            </ul>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">
          <div class="
              footer-copyright
              d-flex
              align-items-center
              justify-content-between
              pt-35
            ">
            <div class="apps-download-btn">
              <!-- <ul>
                <li>
                  <a href="#"><i class="fab fa-apple"></i> Download for iOS</a>
                </li>
                <li>
                  <a class="item-2" href="#"><i class="fab fa-google-play"></i> Download for Android</a>
                </li>
              </ul> -->
            </div>
            <div class="copyright-text">
              <p>Copyright © 2024 CHalert. All rights reserved.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!--====== APPIE FOOTER PART ENDS ======-->
</template>

<script>
export default {};
</script>

<style scoped>
.copyright-text {
  text-align: center;
  margin: 0 auto;
}

.highlight {
  color: #ed1f27;
  font-weight: 600;
}

.center {
  text-align: center;
}

@media (min-width: 992px) {
    .footer-widget-info ul,
    .title {
      text-align: right;
    }
  }

</style>