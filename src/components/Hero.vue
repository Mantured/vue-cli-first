<template>
  <div class="jumbotron">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Hero",
  data() {
    return {
      msg: "sono un Jumbotron, che odia Prettier",
    };
  },
};
</script>
