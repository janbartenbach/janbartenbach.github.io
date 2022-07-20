<template>
  <q-page class="column justify-center items-center bg-blue-1">
    <div class="bg-white column items-center justify-around" style="width:100%">
      <div style="height:100px"></div>
        <img
          alt="Quasar logo"
          src="~assets/test3.png"
          style="width: 60%"
        >
        <!-- <div class="q-mt-sm" style="font-size:80px">StraightUp</div>
        <div style="font-size:25px">A Novel Approach To Posture Control</div> -->

        <div style="height:100px"></div>
    </div>
    
<!-- 
    <q-separator color="black" style="width:90%"/> -->

    <div style="height:100px"></div>

    <img
      alt="Quasar logo"
      src="~assets/test1.png"
      style="width: 1280px; height: 720"
    >

    <div style="height:100px"></div>

    <q-separator class="" color="black" style="width:60%"/>

    <div style="height:100px"></div>

    <img
      alt="Quasar logo"
      src="~assets/test2.png"
      style="width: 1280px; height: 720"
    >

     <div style="height:100px"></div>

    <q-separator class="" color="black" style="width:60%"/>

    <div style="height:100px"></div>
    
    <img
      alt="Quasar logo"
      src="~assets/TeamDesign.jpg"
      style="width: 640; height: 360;border-radius:30px"
    >

     <div class="q-mt-md" style="height:200px; font-size:20px">Erik Vautrin (KIT) - Jan Bartenbach (KIT) - Marcus Hamann-Schroer (KIT)</div>

    
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import { ref } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  setup () {
    return {
      slide: ref(1)
    }
  }
})
</script>
