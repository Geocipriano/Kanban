<template>
<v-app>
  <navbar/>
  <sidebar/>
</v-app>
</template>

<script>
import navbar from './components/navbar'
import sidebar from './components/sidebar'

export default {
  name: 'App',
  components : {
    navbar,
    sidebar
  },
  data() {
    return {
    }
  }
}
</script>

<style >

</style>