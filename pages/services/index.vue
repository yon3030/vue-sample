<template>
  <div>
    <NavDark />
    <ThePageHeader />

    <section class="common-section services services-00">
      <div class="container">
        <header class="section-title">
          <h3>Services We Provide</h3>
          <p>
            Build leading brands, professional websites, unique mobile apps, and
            many more. We are an integrated corporation that leads you toward
            the future. We are your guide to success.
          </p>
        </header>
        <div class="row">
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-01.png"
                  alt="Branding"
                />
              </figure>
              <h2>Branding</h2>
              <p>
                We have a unique team that master everything about branding from
                naming and strategy to the logo design and brand guide.
              </p>
              <NuxtLink to="/services/branding"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-02.png"
                  alt="Mobile Apps"
                />
              </figure>
              <h2>Mobile Apps</h2>
              <p>
                We deal with each mobile initiative with a completely unique
                approach. Backed through local software program technology and
                our skilled team.
              </p>
              <NuxtLink to="/services/mobile"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-03.png"
                  alt="UX&UI Design"
                />
              </figure>
              <h2>UI&UX Design</h2>
              <p>
                Our team constantly works on making your website or mobile
                application experience clearer, shorter, extremely pleasant, and
                more humane .
              </p>
              <NuxtLink to="/services/uxui"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-04.png"
                  alt="Web Apps"
                />
              </figure>
              <h2>Web Developmet</h2>
              <p>
                We are a highly observant professional team that analyzes all
                your ideas and turn them into a user-friendly website that
                expresses you perfectly.
              </p>
              <NuxtLink to="/services/web"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-06.png"
                  alt="Support & Development"
                />
              </figure>
              <h2>Support & Development</h2>
              <p>
                We will help you to find the best solution for your business, as
                well as to keep up with all world trends.
              </p>
              <NuxtLink to="/services/support"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
          <div class="col-md-4">
            <div class="service-item">
              <figure class="service-icon">
                <img
                  src="~/assets/images/services/service-05.png"
                  alt="Digital Marketing"
                />
              </figure>
              <h2>Digital Marketing</h2>
              <p>
                our team works day and night to develop your marketing plan by
                following up on your customer behavior and the results of
                advertising.
              </p>
              <NuxtLink to="/services/marketing"
                >Read More <i class="fas fa-long-arrow-alt-right"></i
              ></NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="common-section bg-gray">
      <div class="container">
        <div class="row center">
          <div class="col-md-7">
            <div class="about-text">
              <h3>We deliver success</h3>
            </div>
            <ul class="items-list mb-60">
              <li>
                <span class="number-marker"> 1</span>
                <p>Focused on getting the best solution</p>
              </li>
              <li>
                <span class="number-marker"> 2</span>
                <p>Outstanding Customer Service and excellent communication</p>
              </li>
              <li>
                <span class="number-marker"> 3</span>
                <p>
                  Long-term partnerships we create it and we grow with our
                  clients
                </p>
              </li>
              <li>
                <span class="number-marker"> 4</span>
                <p>Honest and transparent process from start to finish</p>
              </li>
              <li>
                <span class="number-marker"> 5</span>
                <p>Assured quality on delivery and continuous support</p>
              </li>
              <li>
                <span class="number-marker"> 6</span>
                <p>100+ successful projects from different industries</p>
              </li>
            </ul>
          </div>
          <div class="col-md-5">
            <figure class="about-thumb offset-md-2">
              <img src="~/assets/images/company-mision.png" alt="Work 1" />
            </figure>
          </div>
        </div>
        <div class="row">
          <div class="col-md-3">
            <div class="counter counter-box">
              <count-to
                :start-val="0"
                :end-val="50"
                :suffix="'+'"
                :duration="2000"
              ></count-to>

              <p>Project Done</p>
            </div>
          </div>
          <div class="col-md-3">
            <div class="counter counter-box">
              <count-to
                :start-val="0"
                :end-val="12"
                :suffix="'+'"
                :duration="2000"
              ></count-to>

              <p>Global Parterns</p>
            </div>
          </div>
          <div class="col-md-3">
            <div class="counter counter-box">
              <count-to
                :start-val="0"
                :end-val="6"
                :suffix="'+'"
                :duration="2000"
              ></count-to>

              <p>Awards Winning</p>
            </div>
          </div>
          <div class="col-md-3">
            <div class="counter counter-box">
              <count-to
                :start-val="0"
                :end-val="15"
                :suffix="'+'"
                :duration="2000"
              ></count-to>

              <p>Creative Teams</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <TheSlogan />

    <TheLastPosts />
    <TheProjects />
    <TheFooter />
  </div>
</template>

<script>
import ThePageHeader from "../../components/ThePageHeader.vue";
import TheWorks from "../../components/TheWorks.vue";
import ChooseUs from "../../components/company/ChooseUs.vue";
import TheSlogan from "../../components/services/TheSlogan.vue";
import CountTo from "vue-count-to";

export default {
  name: "Services",
  layout: "page",
  components: { ThePageHeader, TheWorks, ChooseUs, CountTo, TheSlogan },
};
</script>
