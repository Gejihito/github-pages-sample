<template>
  <v-app>
    <v-content>
      <Template/>
    </v-content>
  </v-app>
</template>

<script>
import Template from './components/Template'

export default {
  name: 'App',
  components: {
    Template
  },
  data () {
    return {
      //
    }
  }
}
</script>
