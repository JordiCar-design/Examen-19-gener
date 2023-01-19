<template>
  <v-app>
    <v-main>
      <v-row class="menu">
        <v-col>

        </v-col>
      </v-row>

      <v-col>
        <div style="font-weight:100;font-size:40px;color:white">
          <p>Pàgina principal de l'empresa</p>
        </div>

        <nuxt-link :to="`/empresa/`">Empresa</nuxt-link>
        <br />

        <nuxt-link :to="`/productes/`">Productes</nuxt-link>
        <br />

        <nuxt-link :to="`/privacitat/`">Política de privacitat</nuxt-link>
        <br />

        <nuxt-link :to="`/contacte/`">Contacte</nuxt-link>
        <br />

      </v-col>

      <nuxt />

    </v-main>
  </v-app>
</template>

