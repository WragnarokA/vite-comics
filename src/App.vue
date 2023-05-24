<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppNavMain from './components/AppNavMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppNavMain,
    AppFooter,
  },
  data() {
    return {
      helo: "ciao",


    }
  },
  methods: {
    metodo() {

    },

  },
  mounted() {

  }

}



</script>


<template>
  <AppHeader />
  <AppMain />
  <AppNavMain />
  <AppFooter />

  <div>

  </div>
</template>

<style lang="scss" >
@use './styles/generic.scss' as *;
</style>
