<template>
  <div class="jumbotron">
    <h1>{{ myMsg }}</h1>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Hero",
  props: {
    myMsg: String,
  },
};
</script>
