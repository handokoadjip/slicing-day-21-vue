<template>
  <Content1Component />
  <Content2Component />
  <Content3Component />
  <AboutComponent />
</template>

<script>
import Content1Component from "@/components/Content1Component.vue";
import Content2Component from "@/components/Content2Component.vue";
import Content3Component from "@/components/Content3Component.vue";
import AboutComponent from "@/components/AboutComponent.vue";

export default {
  name: "HomePage",
  components: {
    Content1Component,
    Content2Component,
    Content3Component,
    AboutComponent,
  },
  mounted() {
    document.title = "Designspiration | Christina Michelaitsch"
  }
}
</script>
