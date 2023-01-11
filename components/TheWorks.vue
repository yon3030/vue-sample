<template>
  <section class="common-section">
    <header class="section-header">
      <div class="container">
        <span>Our Work</span>
        <h2>Popular Works</h2>
      </div>
    </header>
    <div class="container">
      <div class="row">
        <div class="col-md-4" v-for="work in works" :key="work.id">
          <div class="work-item js-tilt">
            <figure class="work-thumb">
              <img :src="getImgUrl(work.image)" alt="Work 1" />
            </figure>
          </div>
        </div>
      </div>
    </div>
    
  </section>
</template>

<script>
export default {
  name: "TheWorks",
  layout: "component",
  data() {
    return {
      works: [
        {
          id: 0,
          image: "works/work-01.png",
          title: "Bringero App",
        },
        {
          id: 1,
          image: "works/work-02.png",
          title: "Bringero App",
        },
        {
          id: 2,
          image: "works/work-03.png",
          title: "Bringero App",
        },
        {
          id: 3,
          image: "works/work-04.png",
          title: "Bringero App",
        },
        {
          id: 4,
          image: "works/work-05.png",
          title: "Bringero App",
        },
        {
          id: 5,
          image: "works/work-06.png",
          title: "Bringero App",
        },
      ],
    };
  },
  methods: {
    getImgUrl: function (imagePath) {
      return require("@/assets/images/" + imagePath);
    },
  },
};
</script>

<style></style>
