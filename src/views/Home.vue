<template>
  <div>
    <div class="desktop" v-if="deviceType === 'desktop'">
      <div class="wrapper">
        <div class="header"></div>
        <div class="ril"></div>
        <div class="lia"></div>
      </div>
      <div class="content">

        <h1 style="width: 80%; margin: auto">Randesund IL og Lia IL har den store gleden av å invitere til årets Norgesmesterskap for
          veteraner <br>Stevnet spilles i Sukkevannhallen i Kristiansand
        </h1>
        <p style="text-align: center">
          Påmelding innen fredag 26. april <br>
          <v-btn
            height="65px"
            width="200px"
            style="margin-top: 10px; font-size: 20px"
            variant="outlined"
            text="Påmelding her"
            href="https://ttadmin.webzenter.com/ext?function=Register&TournamentId=316">
          </v-btn>
        </p>

        <p style="text-align: center; margin-top: 100px">
          På resultatsiden finner du trekking og alle resultater for Veteran NM 2024<br>
          <v-btn
            height="65px"
            width="200px"
            style="margin-top: 10px; font-size: 20px"
            variant="outlined"
            text="Resultatside"
            href="https://resultat.ondata.se/001083/">
          </v-btn>
        </p>

        <v-divider
          style="margin: 50px 0"
          thickness="10"
          color="white"
        ></v-divider>

        <h1 class="heading-text">VENUE</h1>

        <div style="width: 90%; margin: auto">
          <div class="flex-container">
            <div style="flex: 1">
              <div style="flex: 1; margin-top: 25px">
                <div style="width: 90%; margin: auto">
                  <h2 style="color: white; font-size: 30px; text-align: center">Sukkevannhallen</h2>
                  <p style="text-align: center; font-size: 18px">Dvergsnesveien 27, 4638 Kristiansand</p>
                  <p style="margin-top: 50px; font-size: 20px">Sukkevannhallen er delt opp i 2 hovedhaller ved siden av hverandre med plass til 16 hager per hall. <br> <br>
                    I hallen finner du også en bemannet kiosk med masse godsaker!<br><br>
                    Det er rikelig med parkeringsplasser rundt hallen. Så det bør være god plass til alle
                    som kommer med egen bil.</p>
                </div>
              </div>
            </div>

            <div style="flex: 1.5">
              <img style="
            width: 100%;
            flex: 1;
            display: block;
            height: 450px;
            object-fit: cover;
            margin: auto;"
                   src="/src/assets/Sukkevannshallen.jpeg" alt="Sukkevannshallen" title="Sukkevannshallen"
              >
            </div>
          </div>


          <div class="flex-container" style="margin: 40px 0">
            <div style="flex: 1.5">
              <img style="
              width: 100%;
              display: block;
              height: 400px;
              object-fit: cover;
              margin: auto;"
                   src="/src/assets/hall2.jpg" alt="Hovedhall 2" title="Hovedhall 2"
              >
            </div>

            <div style="flex: 1">
              <div style="margin-top: 50px" >
                <div style="width: 90%; margin: auto">
                  <h2 style="color: white; font-size: 30px; text-align: center">Hovedhall 2</h2>
                  <p style="margin-top: 40px; font-size: 20px">Hovedhall 2 er den nyere av de 2 hallene. Hallen ligger vegg i vegg med Hovedhall 1.<br> <br>
                    Idrettshallen har parkettdekke på 20 x 40 meter og tribunekapasitet til 300 personer.</p>
                </div>
              </div>
            </div>



          </div>

          <div class="flex-container">

            <div style="flex: 1; margin-top: 50px" >
              <div style="width: 90%; margin: auto">
                <h2 style="color: white; font-size: 30px; text-align: center">Hovedhall 1</h2>
                <p style="margin-top: 40px; font-size: 20px">Hovedhall 1 er hallen som ligger nærmst inngangen. Du må gå gjennom hall 1 for å komme deg til hall 2.<br> <br>
                  Samme som hall 2 så har hall 1 også parkettdekke på 20 x 40 meter og tribunekapasitet til 300 personer.</p>
              </div>
            </div>
            <img style="
            flex: 1;
            display: block;
            height: 400px;
            object-fit: cover;
            margin: auto;"
                 src="/src/assets/hall1.jpg" alt="Hovedhall 1" title="Hovedhall 1"
            >
          </div>
        </div>


        <v-divider
          style="margin: 50px 0"
          thickness="10"
          color="white"
        ></v-divider>


        <h1 class="heading-text" style="padding: 0 0 20px 0">OVERNATTING</h1>
        <h2 style="text-align: center; color: white;">Scandic Kristiansand Bystranda</h2>
        <h3 style="text-align: center; color: white; padding-bottom: 25px; font-style: italic; font-size: 15px">Østre Strandgate 74, 4608 Kristiansand</h3>
        <img style="
          display: block;
          width: 80%;
          height: 500px;
          object-fit: cover;
          margin: auto;
        "
             src="/src/assets/scandic.jpg" alt="Bilde av: Tord-Erik Andersen" title="Bilde av: Tord-Erik Andersen"
        >

        <p style="width: 80%; margin: 50px auto 0 auto">Velkommen til Scandic Kristiansand Bystranda, hotellet som vant prisen for regionens beste hotellfrokost i 2023! Bo sentralt og familievennlig midt på populære Bystranda, nær sentrum, shopping og restauranter.
          Barnevennlig med lekerom og strand, vegg-i-vegg med Aquarama med treningssenter, badeland og Spa. Restaurant med utsikt over havet og egen barnebuffet om sommeren. Parkering i garasje (mot avgift) med direkte adkomst til resepsjonen via heis.</p>

        <h1 style="padding: 50px 0 25px 0">BANKETT</h1>
        <p style="width: 80%; margin: 0 auto 50px auto">Det blir bankett lørdag kveld på hotellet. Vi kommer tilbake senere med meny og program for
          banketten. Det blir velkomstdrink, forrett, hovedrett og dessert. <br>
          Pris: 795 kroner per person.
        </p>
        <p style="width: 80%; margin: auto">
          <span style="font-weight: bold; font-size: 25px">Priser per rom per natt inklusive frokost</span><br>
          Enkeltrom: kr 1190 per natt<br>
          Dobbelt rom: kr 1440 per natt
        </p>
        <p style="text-align: center; margin-top: 75px">Rombestilling og bankett påmelding sendes direkte til Randesund / Lia på e-post: <br>
          <span style="font-weight: bold; font-size: 27px">jens.salvesen2@gmail.com</span></p>


      </div>
    </div>

    <Tablet v-else-if="deviceType === 'tablet'"></Tablet>

    <Mobile v-else></Mobile>

  </div>
</template>

<script>
import Tablet from "@/views/Tablet.vue";
import Mobile from "@/views/Mobile.vue";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Home',
  components: {Mobile, Tablet},
  created() {
    window.addEventListener("resize", this.myEventHandler);
  },
  data() {
    return {
      deviceType: ""
    }
  },
  methods: {
    myEventHandler() {
      if(screen.availWidth <= 750) {
        this.deviceType = 'mobile'
      } else if(screen.availWidth > 750 && screen.width <= 1250) {
        this.deviceType = 'tablet'
      } else {
        this.deviceType = 'desktop'
      }

    }
  },
  mounted() {
    if(screen.availWidth <= 750) {
      this.deviceType = 'mobile'
    } else if(screen.availWidth > 750 && screen.width <= 1250) {
      this.deviceType = 'tablet'
    } else {
      this.deviceType = 'desktop'
    }
  }
}
</script>


<style lang="scss">


  html {
    height: 100%;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    min-height: 100%;
    background: linear-gradient(90deg, #00582c, #00582c, #d33139, #d33139);
  }

  p {
    color: white;
    font-size: 22px;
  }

  .desktop {
    height: 100%;

    .wrapper {
      position: relative;
      max-width: 1920px;
      width: 100%;
      margin: auto;
      height: 100%;

      .header {
        height: 275px;
        background-image: url("/src/assets/header-image.png");
        background-position: center center;
        background-repeat: no-repeat;
        width: 100%;
      }

      .ril {
        height: 275px;
        background-image: url("/src/assets/ril-logo.png");
        position: absolute;
        width: 441px;
        left: 0;
        top: 0;
      }

      .lia {
        height: 275px;
        background-image: url("/src/assets/lia-logo.png");
        position: absolute;
        width: 430px;
        right: 0;
        top: 0;
      }
    }

    .content {
      position: relative;
      height: 100%;
      max-width: 75%;
      margin: auto;
      background-color: #192a66;
      padding-top: 50px;

      h1 {
        color: white;
        text-align: center;
        max-width: 100%;
        padding-bottom: 50px;
      }

      .heading-text {
        font-size: 40px;
      }

      p {
        color: white;
      }

      .flex-container {
        border: 2px solid #838383;
        width: 100%;
        height: 100%;
        margin: auto;
        display: flex;
        flex-wrap: wrap;
        grid-area: e;
      }
    }
  }
</style>
