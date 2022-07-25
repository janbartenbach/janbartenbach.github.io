<template>
  <q-page class="column justify-start items-center bg-white" style="width:100%">

    <!-- Kopfzeile -->
    <div class="row justify-around items-center bg-black text-white shadow-1" style="width:100%;height:60px">
      <div style="width:0%"></div>
      <div class="row justify-end" style="width:48%; font-weight:300; border:soli; padding-right:10px">Welcome To Our Website!</div>
      <div class="row justify-around items-center" style="width:4%;border:soli"><q-img src="~assets/Logo_NoShadow_White.png" style="width:30px;"></q-img></div>
      <div class="row justify-start" style="width:48%; font-weight:300; border:soli; padding-left:10px">StraightUp-Startup </div>
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

   <!-- <q-carousel
      swipeable
      animated
      v-model="slide"
      infinite
      thumbnails
      transition-prev="slide-right"
      transition-next="slide-left"
      transition-duration="1000"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
      control-color="black"
      style=" height:max-content; margin:30px 0px; border:solid; overflow:auto"
      
    >
      <q-carousel-slide :name="1" img-src="~assets/gurt2.png"  style="border:solid;"/>
      <q-carousel-slide :name="2" img-src="~assets/gurt3.png" style="width:80%;margin-left:10%"/>
    </q-carousel> -->

    <q-img src="~assets/gurt2.png" style="margin-top:100px; width:60%; border:soli;"></q-img>

    <!-- Separator -->
    <q-separator color="black" style="width:80%; margin:100px 0px"></q-separator>
    
    <!-- Produkt -->
    <div class="row justify-around items-center" style="width:80%; border:soli">
      <q-img style="width:65%; min-width:350px" src="~assets/GurtBeschriftet.png"></q-img>
      <div class="column justify around" style="width:30%;min-width:250px; border:soli;padding-top:30px">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The Wearable Component</div>
        <div >Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
      </div>
    </div>

    <!-- Separator -->
    <q-separator style="width:80%; margin:50px 0px"></q-separator>

    <!-- App -->
    <div class="row justify-around items-center" style="width:80%;">
      <div class="column justify around" style="width:30%;min-width:250px; border:soli;">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The App</div>
        <div >Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
      </div>
      <!-- <q-img style="padding-top:30px;min-width:300px; width:30%;" src="~assets/AppDesgin.png"></q-img> -->
      <video  style="padding-top:30px;min-width:300px; width:30%;" autoplay loop muted>
        <source type="video/mp4" src="~assets/video_App.mp4">
      </video>
    </div>

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px; margin-top:50px">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Ecosystem
      </div>
    </div>

    <!-- Ecosystem -->
    <div class="row justify-around items-center" style="width:80%; margin: 50px 0px">
      <q-img style="width:65%; min-width:350px" src="~assets/Ecosystem.png"></q-img>
      <div style="width:30%;min-width:250px; border:soli;padding-top:30px">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
    </div>

     <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Team
      </div>
    </div>

    <!-- Ecosystem -->
    <div class="row justify-around items-center" style="width:80%; margin: 50px 0px">
      <div style="width:30%;min-width:250px; border:soli;">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</div>
      <q-img style="width:65%; min-width:350px; margin-top:30px" src="~assets/TeamDesign.jpg"></q-img>
    </div>

        <!-- <video height="440" poster="https://cdn.quasar.dev/img/polina.jpg" autoplay loop muted style="border:solid; border-radius:25px; border-width:5px">
          <source type="video/mp4" src="~assets/Medien1.mp4" >
        </video> -->

    <!-- EndDiv -->
    <div class="row justify-around items-center bg-black" style="height:300px; width:100%; border:soli">
      <div class="column justify-around items-center text-white" style="width:50%; border:soli; height:200px; font-size:12px; font-weight:400">
        Erik Vautrin <br>
        Marcus Hamann-Schrör<br>
        Jan Bartenbach<br>
        -<br>
        v.12
      </div>
      <video  style="width:50%; max-height:300px; padding:10px 0px" autoplay loop muted playsInline>
        <source type="video/mp4" src="~assets/Video_Rot.mp4">
      </video>
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
