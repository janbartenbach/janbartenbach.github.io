<template>
  <q-page class="column justify-start items-center bg-white" style="width:100%">

    <!-- Kopfzeile -->
    <div class="row justify-around items-center bg-black text-white shadow-1" style="width:100%;height:45px">
      <div class="row justify-around items-center" style="border:soli">
        <div class="row justify-around items-center" style="border:soli"><q-img src="~assets/Logo_NoShadow_White.png" style="width:30px;"></q-img></div>
        <div class="row justify-start" style="font-weight:300; border:soli; padding-left:10px;">StraightUp</div>
      </div>
    </div>


    <!-- White Logo div -->
    <!-- <div class="bg-white column items-center justify-around" style="width:100%; margin:20px 0px">
        <img
          alt="Quasar logo"
          src="~assets/test3.png"
          style="width: 60%; margin:60px 0px"
        >
    </div> -->

    <!-- Intro Video of Product -->
    <video  style="margin:50px 0px;min-width:300px; width:75%" autoplay loop muted playsInline>
      <source type="video/mp4" src="~assets/VideoLoop_weiß.mp4">
    </video>
    <!-- <q-img src="~assets/gurt2.png" style="margin-top:100px; width:60%; border:soli;"></q-img> -->

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Product
      </div>
    </div>

    <!-- Separator -->
    <!-- <q-separator color="black" style="width:80%; margin:100px 0px"></q-separator> -->
    
    <!-- Produkt -->
    <div class="row justify-around items-center" style="margin-top:50px;width:80%; border:soli">
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
      <video  style="padding-top:30px;min-width:300px; width:30%;" autoplay loop muted playsInline>
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
    <div class="row justify-around items-center bg-black" style="height:200px; width:100%; border:soli">
        <div class="column justify-around text-white" style="width:25%; height:80%; margin-right:20px; border:soli">
          Erik Vautrin <br>
          Marcus Hamann-Schroer<br>
          Jan Bartenbach<br>
          <br>
          v.15
        </div>
        <div class="column justify-around text-white" style="width:25%; height:80%; margin-right:20px; border:soli">
          Impressum: <br>
          StraightUp<br>
          Karlsruhe<br>
          ---<br>
          ---
        </div>
      <div class="bg-white row items-center justify-around" style="width:30%; height:80%; border-radius:15px; margin-right:20px; border:soli">
        <img
            alt="Quasar logo"
            src="~assets/test3.png"
            style="width:80%; border:soli"
          >
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
