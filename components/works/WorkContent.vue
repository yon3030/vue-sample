<template>
  <section class="common-section">
    <div class="page-works">
      <div class="container">
        <div class="row">
          <div class="col-md-6" v-for="work in works" :key="work.id">
            <div class="work-item js-tilt">
              <figure class="work-thumb">
                <img :src="getImgUrl(work.image)" alt="Work 1" />
              </figure>

              <h5>{{ work.title }}</h5>
              <p>{{ work.desc }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  name: "WorksContent",
  layout:'component',


  data() {
    return {
      works: [
        {
          id: 0,
          image: "works/work-01.png",
          title: " Food App",
          desc: "Food Delivery App",
        },
        {
          id: 1,
          image: "works/work-02.png",
          title: " Food App",
          desc: "Food Delivery App",

        },
        {
          id: 2,
          image: "works/work-03.png",
          title: " Food App",
          desc: "Food Delivery App",

        },
        {
          id: 3,
          image: "works/work-05.png",
          title: " Food App",
          desc: "Food Delivery App",

        },
        {
          id: 4,
          image: "works/work-05.png",
          title: " Food App",
          desc: "Food Delivery App",

        },
        {
          id: 5,
          image: "works/work-06.png",
          title: " Food App",
          desc: "Food Delivery App",

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
