<template>
  <div class="upcoming-elections">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Upcoming Elections
          </h1>
          <div>
            <ul>
                <li> Date: Level - Election </li>
                <li> Date: Level - Election </li>
                <li> Date: Level - Election </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'UpcomingElections',
  props: {
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
  /* display: inline-block; */
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
