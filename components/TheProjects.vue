<template>
  <section class="common-section bg-gray">
    <div class="container">
      <vueper-slides
        class="no-shadow"
        :visible-slides="6"
        slide-multiple
        :gap="3"
        :dragging-distance="3"
        :bullets="false"
        :breakpoints="{ 800: { visibleSlides: 2, slideMultiple: 2 } }"
      >
        <vueper-slide
          v-for="slide in slides"
          :key="slide.id"
          :image="slide.image"
        />
      </vueper-slides>
    </div>
  </section>
</template>

<script>

import { VueperSlides, VueperSlide } from "vueperslides";
import "vueperslides/dist/vueperslides.css";

export default {
  name: "TheProjects",
  layout: "component",
  components: { VueperSlides, VueperSlide },

  data() {
    return {
      slides: [
        {
          image: require("~/assets/images/projects/project-1.png"),
        },
        {
          image: require("~/assets/images/projects/project-2.png"),
        },
        {
          image: require("~/assets/images/projects/project-3.png"),
        },
        {
          image: require("~/assets/images/projects/project-4.png"),
        },
        {
          image: require("~/assets/images/projects/project-5.png"),
        },
        {
          image: require("~/assets/images/projects/project-6.png"),
        },
        {
          image: require("~/assets/images/projects/project-7.png"),
        },
        {
          image: require("~/assets/images/projects/project-8.png"),
        },
        {
          image: require("~/assets/images/projects/project-9.png"),
        },

        {
          image: require("~/assets/images/projects/project-10.png"),
        },

        {
          image: require("~/assets/images/projects/project-11.png"),
        },

        {
          image: require("~/assets/images/projects/project-12.png"),
        },
        {
          image: require("~/assets/images/projects/project-13.png"),
        },
        {
          image: require("~/assets/images/projects/project-14.png"),
        },
        {
          image: require("~/assets/images/projects/project-15.png"),
        },
        {
          image: require("~/assets/images/projects/project-16.png"),
        },
        {
          image: require("~/assets/images/projects/project-17.png"),
        },
        {
          image: require("~/assets/images/projects/project-18.png"),
        },
      ],
    };
  },
};
</script>
<style>
.vueperslides__track,.vueperslides__inner {
height: 112px;
}
.vueperslides__arrow {
  top: -35px;
}
.vueperslides__arrow--prev{
  
left: auto !important;
right: 1.5em !important;
}

.vueperslide{
  background-size: contain !important;
  background-repeat: no-repeat;
}
.vueperslides__arrow svg {
  width: 30px;
}
button:focus{
  outline: none;
}





</style>
