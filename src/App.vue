<template>
  <asmrHeader />
  <asmrBody />
</template>

<script>
import asmrHeader from "@/components/asmrHeader.vue";
import asmrBody from "@/components/asmrBody.vue";

export default {
  name: "App",

  components: {
    asmrHeader,
    asmrBody,
  },
};
</script>

<style>
* {
  /* border: 1px solid red; */
}

html,
body,
#app {
  margin: 0;
  height: 100%;
}
</style>
