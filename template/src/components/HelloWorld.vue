<template lang="html">
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-list>
        <v-card v-for="item in items">
          <v-card-title>
            HelloWorld
          </v-card-title>
        </v-card>
      </v-list>
    </v-slide-y-transition>
  </v-container>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style{{#sass}} lang="scss"{{/sass}}>
</style>
