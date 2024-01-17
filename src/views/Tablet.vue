<template>

  <div class="tablet">
    <div class="header">
      <h1>VETERAN NM 2024</h1>
    </div>
    <div class="ril"></div>
    <div class="lia"></div>

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

      <v-divider
        style="margin: 50px 0"
        thickness="10"
        color="white"
      ></v-divider>

      <h1 class="heading-text" style="padding-bottom: 25px">VENUE</h1>
        <h2 style="color: white; font-size: 25px; text-align: center">Sukkevannhallen</h2>
        <p style="text-align: center; font-size: 18px; margin-bottom: 50px">Dvergsnesveien 27, 4638 Kristiansand</p>
        <p style="margin: 50px auto; width: 80%">Sukkevannhallen er delt opp i 2 hovedhaller ved siden av hverandre med plass til 16 hager per hall. <br>
          I hallen finner du også en bemannet kiosk med masse godsaker!<br>
          Det er rikelig med parkeringsplasser rundt hallen. Så det bør være god plass til alle
          som kommer med egen bil.</p>

        <img style="
          display: block;
          width: 80%;
          height: 500px;
          object-fit: cover;
          margin: auto;
            "
             src="/src/assets/Sukkevannshallen.jpeg" alt="Sukkevannshallen" title="Sukkevannshallen"
        >

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

</template>

<script>
export default {
  name: "Tablet"
}
</script>

<style lang="scss">
  .tablet {
    .header {
      height: 100px;
      background-image: url("/src/assets/tablet-header.png");
      background-position: center center;
      background-repeat: no-repeat;
      width: 100%;

      h1 {
        color: white;
        font-size: 50px;
        text-align: center;
        padding-top: 25px;
        -webkit-text-stroke-width: 2px;
        -webkit-text-stroke-color: black;
      }
    }

    .ril {
      height: 100px;
      background-image: url("/src/assets/ril-tablet.png");
      position: absolute;
      width: 170px;
      left: 0;
      top: 0;
    }

    .lia {
      height: 100px;
      background-image: url("/src/assets/lia-tablet.png");
      position: absolute;
      width: 170px;
      right: 0;
      top: 0;
    }

    .content {
           position: relative;
           height: 100%;
           max-width: 90%;
           margin: auto;
           background-color: #192a66;
           padding-top: 50px;

      h1 {
        color: white;
        text-align: center;
        max-width: 100%;
        padding-bottom: 50px;
      }

      p {
        color: white;
      }
    }
  }
</style>
