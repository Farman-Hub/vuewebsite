<template>
<!--====== APPIE HERO PART START ======-->
  <section class="appie-hero-area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="appie-hero-content">
                        <span>{{welcome_message}}</span>
                        <p class="appie-title">{{slogan}}</p>
                        <p>We are a pioneering security service at the heart of the Saanenland region, placing clients and their community at the heart of everything we do.</br>

                        </br>We work in collaboration with – Chalet owners, local businesses as well as the local authorities to ensure the neighbourhood is safe, informed and empowered with peace of mind.<br/>

                        </br>Join us in creating a safer, stronger community together.</p>
                        <!--<p>{{description}}</p>-->
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="appie-hero-thumb">
                        <div class="thumb wow animated fadeInUp" data-wow-duration="2000ms" data-wow-delay="200ms">
                            <img src="@/assets/images/hero-thumb-1.png" alt="">
                        </div>
                        <div class="appie-hero-content">
                        <ul>
                          <li>
                              <router-link to="/sign-placement">
                                  <i :class="first_button_icon"></i>{{first_button_content}}
                              </router-link>
                          </li>
                      </ul>
                    </div>
                        <!--<div class="thumb-2 wow animated fadeInRight" data-wow-duration="2000ms" data-wow-delay="600ms">
                            <img src="@/assets/images/hero-thumb-2.png" alt="">-->
                    </div>
                </div>
                </div>
            </div>
        </div>
    </section>
    <!--====== APPIE HERO PART end ======-->
</template>

<script>

export default {
    props:['welcome_message','slogan','description','thumb_one','thumb_two','first_button_content','first_button_icon'],
    methods: {
        toggleModal() {
        // Handle the modal toggle logic here
        this.visitModalVisible = !this.visitModalVisible;
    }
}
}

</script>

<style scoped>
/* Target the image within the .appie-hero-thumb .thumb class */
.appie-hero-thumb .thumb img {
  /* Ensure the image transitions smoothly */
  transition: transform 0.3s ease-in-out;
  /* Optional: Set an initial scale to make the zoom effect more noticeable */
  transform: scale(1);
}

/* When hovering over the image, scale it up slightly */
.appie-hero-thumb .thumb:hover img {
  transform: scale(1.1); /* Adjust the scale value as needed for the desired zoom effect */
}

/* Ensure the container doesn't grow with the image, which might cause layout shifts */
.appie-hero-thumb .thumb {
  overflow: hidden; /* This clips the parts of the image that zoom outside the container's bounds */
}

.appie-title {
    font-size: 70px;
    font-weight: 700;
    color: #0e1133;;
}

.consultation-button-wrapper {
  display: none;
}

@media (max-width: 768px) {
  .consultation-button-wrapper {
    display: block; 
  }
}

@media (min-width: 769px) and (max-width: 1220) {
    .appie-title {
        font-size: 35px !important;
    }
}
</style>
