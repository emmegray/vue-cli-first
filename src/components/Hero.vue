<template>
  <div>
    <b-jumbotron class="pink d-flex flex-column align-items-center">
      <p>{{msg}}</p>
      <slot></slot>
      <b-button class="pink" href="#">{{mgsButton}}</b-button>
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: `Hero`,
  props: {
    msg: String,
    mgsButton: String,
  }
}
</script>

<style scoped lang="scss">
.pink {
  background: rgba(216, 112, 147, 0.589);
}

div {
  p {
    color: white;
    font-size: x-large;
  }
  .btn {
    font-size: x-large;
  }
}
</style>