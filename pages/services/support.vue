<template>
  <div>
    <NavDark />
    <ThePageHeader />
    <TheAbout />
    <TheQuestions />
    <TheTime />
    <TheSlogan />
    <TheCraft />
  </div>
</template>

<script>
import ThePageHeader from "../../components/support/ThePageHeader.vue";
import TheAbout from "../../components/support/TheAbout.vue";
import TheTime from "../../components/support/TheTime.vue";
import TheSlogan from "../../components/support/TheSlogan.vue";
import TheCraft from "../../components/support/TheCraft.vue";
import TheWorks from "../../components/TheWorks.vue";

export default {
  name: "Services",
  layout: "main",
  components: {
    ThePageHeader,
    TheAbout,
    TheTime,
    TheCraft,
    TheSlogan,
    TheWorks,
  },
};
</script>
