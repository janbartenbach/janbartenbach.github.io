<template>
  <q-page class="column justify-start items-center bg-white" style="width:100%">

    <!-- Kopfzeile -->
    <!-- <div class="row justify-around items-center bg-black text-white shadow-1" style="width:100%;height:45px">
      <div class="row justify-around items-center" style="border:soli">
        <div class="row justify-around items-center" style="border:soli"><q-img src="~assets/Logo_NoShadow_White.png" style="width:30px;"></q-img></div>
        <div class="row justify-start" style="font-weight:300; border:soli; padding-left:10px;">StraightUp</div>
      </div>
    </div> -->
    <div class="row justify-between items-center text-black" style="width:100%; height:80px; padding-left:20px; padding-right:20px; position:absolute; z-index: 1; border:soli">
      <div class="row">
          <q-btn flat color="primary" text-color="black" width>
          <div style="border:soli">Product</div>
        </q-btn>
        <q-btn flat color="primary" text-color="black" width>
          <div style="border:soli">Philosophy</div>
        </q-btn>
        <q-btn flat color="primary" text-color="black" width>
          <div style="border:soli">Team</div>
        </q-btn>
      </div>      
      <div class="row" style="">
        <!-- <q-img src="~assets/Logo_Shadow_NoText.png" style="width:50px;"></q-img> -->
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
    <video  style=";min-width:300px; width:80%; border:soli" autoplay loop muted playsInline>
      <source type="video/mp4" src="~assets/VideoLoop_weiß_v2.mp4">
    </video>
    <!-- <q-img src="~assets/gurt2.png" style="margin-top:100px; width:60%; border:soli;"></q-img> -->


    <div class="" style="width:100%; height:100px">
     
    </div>

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Product
      </div>
    </div>

    <!-- Separator -->
    <!-- <q-separator color="black" style="width:80%; margin:100px 0px"></q-separator> -->
    
    <!-- Produkt -->
    <div class="row justify-around items-center" style="margin-top:50px;width:90%; border:soli">
      <q-img style="width:60%; min-width:350px" src="~assets/GurtBeschriftet.png"></q-img>
      <div class="column justify around" style="width:35%;min-width:250px; border:soli;padding-top:30px">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The Wearable Component</div>
        <div>Our main goal is to design a barely noticeable product, which helps our customers to achieve a healthy posture throughout the day without being intrusive or visible. Using a novel sensor-technology we are able to measure the exact position of each shoulder, which is the main indicator for upper body posture. Whenever a bad posture is detected, our quietly vibrating haptic engine reminds the user to actively adjust their posture. This reminder is based on an intelligent algorithm (AI) which was developed hand in hand with one of Germanys leading Physiotherapists for back and shoulders, resulting in an effective training of the back muscles and establishing healthy habits. To ensure a smooth integration into the daily routine we designed the product to be as lightweight and flexible as possible. Additionally, we made it fully waterproof to be washed without any disassembly.
</div>
      </div>
    </div>

    <!-- Separator -->
    <q-separator style="width:80%; margin:50px 0px"></q-separator>

    <!-- App -->
    <div class="row justify-around items-center" style="width:90%;">
      <div class="column justify around" style="width:40%;min-width:250px; border:soli;">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The App</div>
        <div >Our app is the main interface for the user to track their progress, adjust the desired intensity of the posture training, and share their achievements with friends and the community. To match different situations throughout the day, the user can select and edit various profiles which differ in feedback frequency, movement threshold or vibration pattern. Over time our intelligent algorithms will recognize the overall health and daily patterns of the user and automatically adapt the training intensity and times accordingly. All data recorded while using our product is displayed comprehensibly to enable our users to break their bad habits and become the best versions of themselves.
      </div>
    </div>
      <!-- <q-img style="padding-top:30px;min-width:300px; width:30%;" src="~assets/AppDesgin.png"></q-img> -->
      <video  style="padding-top:30px;min-width:300px; width:30%;" autoplay loop muted playsInline>
        <source type="video/mp4" src="~assets/App_Bildschirmaufnahme.mp4">
      </video>
    </div>

    <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px; margin-top:50px">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Ecosystem
      </div>
    </div>

    <!-- Ecosystem -->
    <div class="row justify-around items-center" style="width:90%; margin: 50px 0px">
      <q-img style="width:55%; min-width:350px" src="~assets/Ecosystem.png"></q-img>
       
      <div style="width:30%;min-width:250px; border:soli;padding-top:30px">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The Ecosystem</div>
        Apart from the basic functionality, our app offers even more service: Exercises and online courses are available, well matched to the individual user’s state of health and fitness. Additionally, users can be linked to physiotherapists in case of necessary treatments. In this case, the expert will be granted access to the relevant data provided by the StraightUp system. Furthermore, we are planning to cooperate with company healthcare and health insurances to make healthy posture available to as many people as possible, thus reducing the long-term costs of back problems for everyone involved.</div>
    </div>

     <!-- ZwischenBlock Überschrift -->
    <div class="row justify-around items-center bg-primary" style="width:100%; height:100px;">
      <div class="text-white" style="font-size:30px; font-weight:200">
        The Team
      </div>
    </div>

    <!-- Team -->
    <div class="row justify-around items-center" style="width:90%; margin: 50px 0px">
       
      <div style="width:40%;min-width:250px; border:soli;">
        <div class="text-primary" style="margin-bottom:20px; font-size:20px;">The Team</div>
      Three of us - Erik, Marcus, Jan - started out as a team of 3 engineering students from KIT in Karlsruhe. Coming from different areas of expertise, we quickly grew as a well working, cooperative team that was able to develop first products for university related projects. As time passed, we got more and more engaged and motivated in product development and as the opportunity came by, working hand in hand with a physiotherapist to create an incredible, well needed product to prevent backpain, we instantly went for it. After the main steps in development of the novel technology were completed, we were super happy to have Jan G join us, as an expert on business development. Through this addition we are now able to take the first steps in building a business around our unique product.</div>
      <q-img class="shadow-10" style="width:50%; min-width:350px; margin-top:30px; border-radius:15px" src="~assets/Team_sharp.jpg"></q-img>
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
          Jan Grigarzik<br>
          <br>
          v.23
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
