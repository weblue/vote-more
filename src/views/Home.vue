<template>
  <div class="home">
    <div class="columns">
      <div class="column is-one-third">
        <UpcomingElections/>
      </div>
      <div class="divider"></div>
      <div class="column">
        <IntroBanner/>
      </div>
    </div>
    <div id="buttons">
      <div class="">
        <router-link to="/apply">
          <div class="button is-danger is-fullwidth" >
            <b>Register to Mail-in Vote!</b>
          </div>
        </router-link>
      </div>
      <div class="mt-1">
        <router-link class="mt-1" to="/notify">
          <div class="button is-danger is-fullwidth" >
            <b>Get notified about upcoming elections!</b>
          </div>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import IntroBanner from '@/components/IntroBanner.vue'
import UpcomingElections from '@/components/UpcomingElections.vue'

export default {
  name: 'Home',
  components: {
    IntroBanner,
    UpcomingElections
  }
}
</script>

<style>
#buttons {
  text-align: center;
  display: block;
  width: 75%;
  margin-left: auto;
  margin-right: auto;
}

.divider {
  width: 1px;
  margin: 3em 0;
  background: black;
}
</style>