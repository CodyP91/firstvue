<template>
  <div id="app">
    <PageHeader title="My Page" subtitle="This is a subtitle" />
    ...
  </div>
</template>

<script>
import PageHeader from "./components/PageHeader.vue";

export default {
  name: "App",
  components: {
    PageHeader,
  },
};
</script>
