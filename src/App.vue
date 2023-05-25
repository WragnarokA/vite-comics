<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppNavMain from './components/AppNavMain.vue'
import AppFooter from './components/AppFooter.vue'

import ComincsCards from './data/comincs'

export default {
  components: {
    AppHeader,
    AppMain,
    AppNavMain,
    AppFooter,

  },
  data() {
    return {
      listaFumetti: ComincsCards,
    }
  },
  mounted() {
    console.log("appvue", this.listaFumetti);
  }

}

</script>


<template>
  <AppHeader />
  <main>
    <AppMain :fumetti="listaFumetti" />
    <AppNavMain />

  </main>
  <AppFooter />

  <div>

  </div>
</template>

<style lang="scss" scoped>
@use './styles/partials/_variables' as *;
</style>
