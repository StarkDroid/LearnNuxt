<template>
  <div>
    <nuxt keep-alive />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "LearnNuxt",
      meta: [
        {
          hid: "description",
          name: "description",
          content:
            "Best place to find a curated list of implementation that NuxtJS has to offer",
        },
      ],
    };
  },
};
</script>
<style>
body {
  font-family: "Outfit";
}
</style>
