

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components:{
    HelloWorld,
  },

  data() {
    return {
      nomeApplicazione: "esempioProva 0.1"
    }
  },
  methods:{

  },
  mounted(){
    console.log("app caricata con successo")
  }
}

</script>

<!-- ============================================ -->

<template>
  <h1>Benvenuto in {{nomeApplicazione}}</h1>
  <HelloWorld />
</template>
