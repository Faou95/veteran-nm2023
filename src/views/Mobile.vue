<template>
  <div class="mobile">
    <div class="header">
      <h1>VETERAN NM<br>2024</h1>
    </div>
    <div class="ril"></div>
    <div class="lia"></div>
    <div class="content">
      <div class="text-wrapper">

        <h1 style="margin-bottom: 25px">Randesund IL og Lia IL har den store gleden av å invitere til årets Norgesmesterskap for
          veteraner. <br>Stevnet spilles i Sukkevannhallen i Kristiansand
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
      </div>

      <v-divider
        style="margin: 50px 0"
        thickness="10"
        color="white"
      ></v-divider>

      <div class="text-wrapper">

        <h1 style="font-size: 25px; text-align: center; margin-bottom: 30px">VENUE</h1>

        <h2 style="color: white; font-size: 25px; text-align: center">Sukkevannhallen</h2>
        <p style="text-align: center; font-size: 15px">Dvergsnesveien 27, 4638 Kristiansand</p>
        <p style="margin-top: 25px; font-size: 18px">Sukkevannhallen er delt opp i 2 hovedhaller ved siden av hverandre med plass til 16 hager per hall. <br> <br>
          I hallen finner du også en bemannet kiosk med masse godsaker!<br><br>
          Det er rikelig med parkeringsplasser rundt hallen. Så det bør være god plass til alle
          som kommer med egen bil.</p>

        <img style="
            display: block;
            height: 200px;
            object-fit: cover;
            margin: 25px auto;
            width: 100%;
            "
             src="/src/assets/Sukkevannshallen.jpeg" alt="Sukkevannshallen" title="Sukkevannshallen"
        >
      </div>



    </div>
  </div>
</template>

<script>
export default {
  name: "Mobile"
}
</script>

<style lang="scss">
  .mobile {

    .header {
      height: 100px;
      background-image: url("/src/assets/tablet-header.png");
      background-position: center center;
      background-repeat: no-repeat;
      width: 100%;

      h1 {
        color: white;
        font-size: 30px;
        text-align: center;
        padding-top: 10px;
        line-height: 1;
        -webkit-text-stroke-width: 1px;
        -webkit-text-stroke-color: #000000;
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
      max-width: 100%;
      margin: auto;
      background-color: #192a66;
      padding-top: 20px;

      h1 {
        color: white;
        font-size: 20px;
      }

      .text-wrapper {
        margin: auto;
        width: 90%;
      }
    }
  }
</style>
