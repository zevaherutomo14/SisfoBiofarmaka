<template>
  <v-app>  
    <v-card color="white">
      <v-content justify="center">
      <center><img src="~/assets/logo-ipb.png" fit="cover" width="600" height="192.5" class="mx-auto"></center>
     </v-content>
    </v-card>
    <v-card color="#0D47A1">
      <v-card-title class="justify-center">
       Selamat datang di Pusat Studi Biofarmaka Tropika
      </v-card-title>
      <p style="text-align:center">Pusat Studi Biofarmaka Tropika adalah lembaga riset yang berada di bawah Institut Pertanian Bogor</p>
    </v-card>

    <v-divider></v-divider>
    <br></br>    
    <p style="text-align:center">SIMPEL</p>
      <v-row
      align="center"
      justify="space-around"
      >   
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt           
                to="/simpeladmin"
              >
              Admin
             </v-btn>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="/simpelpemantauan"
              >
              Pemantauan
             </v-btn>
             <v-btn
                rounded
                color="primary"
                dark
                href="/simpelpeneliti"
              >
              Peneliti
             </v-btn>               
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SIPELAKEU</p>
      <v-row
      align="center"
      justify="space-around"
      >           
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://sisfo.biofarmaka.ipb.ac.id/SIPELAKU/login"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SIM-UKHP</p>
      <v-row
      align="center"
      justify="space-around"
      >         
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://sim-ukhp.biofarmaka.ipb.ac.id/Login"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
      </v-row>
      
      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SISDM Trop BRC</p>
      <v-row
      align="center"
      justify="space-around"
      > 
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://sisfo.biofarmaka.ipb.ac.id/SIMSDM/login"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">LPSB</p>
      <v-row
      align="center"
      justify="space-around"
      >       
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://lpsb.biofarmaka.ipb.ac.id/admin/login"
              >
              Masuk Admin LPSB
             </v-btn>             
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SIMALUB</p>
      <v-row
      align="center"
      justify="space-around"
      > 
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://simalub.biofarmaka.ipb.ac.id/login"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SIM-SARPRAS</p>
      <v-row
      align="center"
      justify="space-around"
      >       
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://sisfo.biofarmaka.ipb.ac.id/sim-sarpras/login"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
      </v-row>

      <br></br>
      <v-divider></v-divider>
      <br></br>
      <p style="text-align:center">SISEKRET</p>
      <v-row
      align="center"
      justify="space-around"
      > 
          <v-card-actions>
            <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                to="/sisekret"
              >
              Masuk
             </v-btn>             
        </v-card-actions>
        </v-row>
      <br></br>
      <v-divider></v-divider> 
      <br></br> 
    <!--
    <v-row
      align="center"
      justify="space-around"
    >       
      <v-expansion-panels> 
      <v-expansion-panel
        v-for="(item,i) in 1"
        :key="i"
      >
        <v-expansion-panel-header color="#0D47A1">
          <h3 style="text-align:center">SIMPEL</h3>
        </v-expansion-panel-header>
        <v-expansion-panel-content color="#0D47A1">
        <v-row
        align="center"
        justify="space-around"
        >   
            <v-card-actions>
              <v-spacer/>
              <v-btn
                  rounded
                  color="primary"
                  nuxt           
                  href="http://simpel.biofarmaka.ipb.ac.id/Admin/"
                >
                Admin
              </v-btn>
              <v-btn
                  rounded
                  color="primary"
                  nuxt
                  href="http://simpel.biofarmaka.ipb.ac.id/Pemantauan/"
                >
                Pemantauan
              </v-btn>
              <v-btn
                  rounded
                  color="primary"
                  dark
                  href="http://simpel.biofarmaka.ipb.ac.id/Peneliti/login"
                >
                Peneliti
              </v-btn>               
            </v-card-actions>
           </v-row>              
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-row>
    <v-row
      align="center"
      justify="space-around"
    >       
      <v-expansion-panels> 
      <v-expansion-panel
        v-for="(item,i) in 1"
        :key="i"
      >
        <v-expansion-panel-header color="#0D47A1">
          <h3 style="text-align:center">SIM-UKHP</h3>
        </v-expansion-panel-header>
        <v-expansion-panel-content color="#0D47A1">
        <v-row
        align="center"
        justify="space-around"
        >   
            <v-card-actions>
             <v-spacer/>
             <v-btn
                rounded
                color="primary"
                nuxt
                href="http://sim-ukhp.biofarmaka.ipb.ac.id/Login"
              >
              Masuk
             </v-btn>               
            </v-card-actions>
           </v-row>              
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-row>     
    -->
        <p style="text-align:center">Terima kasih sudah bergabung bersama Pusat Studi Biofarmaka Tropika IPB.</p>
        </v-card-actions>
      </v-card>
    </v-content>
    <v-card height="400px">
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
   </v-card>
  </v-app>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style scoped>
.v-application {
  background-color:#0D47A1;
}
</style>