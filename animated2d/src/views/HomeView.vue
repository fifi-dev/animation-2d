<template>
  <div class="home px-20">
   <!--  <img alt="Vue logo" src="../assets/logo.png"> -->
    <div class="">
      <h1 className="text-5xl font-bold ">
        La lettre de Noel
      </h1>
      <CountDown class="my-8"></CountDown>
    </div>
    <div class="grid grid-cols-3 pt-12 gap-6">
      <button>
        <div class=" h-64 bg-slate-500">

        </div>
        <p>Ecrire une lettre </p>
      </button>
      <button>
        <div class=" h-64 bg-slate-500">

        </div>
        <p>Créer ma wishlist </p>
      </button>
      <div colocr="">
        <div class=" h-64 bg-slate-500">

        </div>
        <button>Idée Cadeaux</button>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import CountDown from '@/components/CountDown.vue';

export default {
  name: 'HomeView',
  components: 
  {
    CountDown
  },
  methods: {
    
  }
}
</script>

