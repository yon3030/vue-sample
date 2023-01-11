<template>
  <section class="common-section bg-liner">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <div class="counter">
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
          <div class="counter">
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
          <div class="counter">
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
          <div class="counter">
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
</template>

<script>
import CountTo from "vue-count-to";
export default {
  name: "TheCounter",
  layout:'component',
  components: { CountTo },
  
  
};
</script>

<style></style>
