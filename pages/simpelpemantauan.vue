<template>
  <v-app>
    <v-app-bar app dark color="blue darken-4">
     <v-card-title class="justify-center">
       SIMPEL
      </v-card-title>
    </v-app-bar>

  <v-card color="white">
    <v-content>
      <v-card width="500" class="mx-auto mt-9">
        <v-card-title>SIMPEL Pemantauan Biofarmaka Tropika IPB</v-card-title>
        <v-card-text>
          <v-text-field label="Nama Pengguna"/>
          <v-text-field 
          label="Kata Sandi" 
          :type="showPassword ? 'text' : 'password'"
          :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
          @click:append="showPassword = !showPassword"/>
        </v-card-text>

        <v-divider></v-divider>
        <v-card-actions>
          <v-btn color="info">Masuk</v-btn>
        </v-card-actions>
      </v-card>
    </v-content>
  <br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br>
  </v-card>
  
    <template>
    <v-footer
      v-bind="localAttrs"
      padless
    >
      <v-card
        flat
        tile
        width="125%"
        class="blue darken-4 text-center"
      >
        <v-card-text class="white--text">
          <strong>Pusat Studi Biofarmaka Tropika IPB — {{ new Date().getFullYear() }}</strong>
        </v-card-text>
      </v-card>
    </v-footer>
</template>
  </v-app>
</template>
<script>
export default {
  name: 'SimpelpemantauanPage'
}
</script>
<script>
export default {
  data()
  {
    return{
      showPassword:false
    }
  }
}
</script>

