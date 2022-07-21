<template>
  <q-page class="column justify-start items-center bg-white" style="width:100%">

    <!-- Kopfzeile -->
    <div class="row justify-around items-center bg-black text-white shadow-1" style="width:100%;height:60px">
      <div style="width:0%"></div>
      <div class="row justify-end" style="width:48%; font-weight:300; border:soli">Welcome To Our Website!</div>
      <div class="row justify-around items-center" style="width:4%;border:soli"><q-img src="~assets/Logo_NoShadow_White.png" style="width:30px;"></q-img></div>
      <div class="row justify-start" style="width:48%; font-weight:300; border:soli">A Soon To Be Medtech Startup </div>
      <div style="width:0%"></div>
    </div>


    <!-- White Logo div -->
    <div class="bg-white column items-center justify-around" style="width:100%; margin:20px 0px">
        <img
          alt="Quasar logo"
          src="~assets/test3.png"
          style="width: 60%; margin:60px 0px"
        >
    </div>

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Product
      </div>
    </div>

    <!-- BigProduct Image -->
    <!-- <div class="row justify-around items-center " style="width:80%">
      <q-img class="" style="width:50%; margin:30px 0px" src="~assets/gurt2.png"></q-img>
    </div> -->
   <q-carousel
      swipeable
      animated
      v-model="slide"
      infinite
      autoplay="true"
      thumbnails
      transition-prev="slide-right"
      transition-next="slide-left"
      transition-duration="1000"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
      control-color="black"
      style="height:700px; width:50%; margin:30px 0px; border:soli"
    >
      <q-carousel-slide :name="1" img-src="~assets/gurt2.png" style="width:80%;margin-left:10%"/>
      <q-carousel-slide :name="2" img-src="~assets/gurt3.png" style="width:80%;margin-left:10%"/>
    </q-carousel>

    <!-- Separator -->
    <q-separator color="black" style="width:80%; margin:200px 0px"></q-separator>
    
    <!-- Produkt -->
    <div class="row justify-around items-center" style="width:80%;">
      <q-img style="width:65%" src="~assets/GurtBeschriftet.png"></q-img>
      <div style="width:30%">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
    </div>

    <!-- Separator -->
    <q-separator style="width:80%; margin:200px 0px"></q-separator>

    <!-- App -->
    <div class="row justify-around items-center" style="width:80%;">
      <div style="width:30%">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
      <q-img style="width:30%;" src="~assets/AppDesgin.png"></q-img>
    </div>

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Ecosystem
      </div>
    </div>

    <!-- Ecosystem -->
    <div class="row justify-around items-center" style="width:80%; margin: 100px 0px">
      <q-img style="width:60%;" src="~assets/Ecosystem.png"></q-img>
      <div style="width:30%">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
    </div>

     <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Team
      </div>
    </div>

    <!-- Ecosystem -->
    <div class="row justify-around items-center" style="width:80%; margin: 100px 0px">
      <div style="width:30%">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
      <q-img style="width:50%;" src="~assets/TeamDesign.jpg"></q-img>
    </div>

        <!-- <video height="440" poster="https://cdn.quasar.dev/img/polina.jpg" autoplay loop muted style="border:solid; border-radius:25px; border-width:5px">
          <source type="video/mp4" src="~assets/Medien1.mp4" >
        </video> -->

    <!-- EndDiv -->
    <div class="row justify-around items-center bg-primary" style="height:300px; width:100%; border:soli">
      <div class="column justify-around text-black" style="width:25%; border:soli; height:200px; font-size:17px; font-weight:400">
        StraightUp
        <q-separator color="black" style="width:35%"></q-separator>
        Erik Vautrin <br>
        Marcus Hamann-Schrör<br>
        Jan Bartenbach
      </div>
      <div class="row justify-around items-center" style="width:25%; border:soli; height:200px">
        <q-img style="width:40%;" src="~assets/gurt3.png"></q-img>
      </div>
      <div class="row justify-center items-center" style="width:25%; border:soli; height:200px">
        <q-img style="width:25%;" src="~assets/Logo_NoShadow_Black.png"></q-img>
      </div>
    </div>

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
