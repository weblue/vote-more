<template>
  <div class="hello">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            ezVote - Virginia
          </h1>
          <h2 class="subtitle">
            We're here to make voting easy.
          </h2>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IntroBanner',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
