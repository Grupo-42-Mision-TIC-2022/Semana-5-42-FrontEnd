<template>
  <div class="d-flex justify-content-center p-2">
    <div id="app">
      <v-app id="inspire">
        <v-card
          class="mx-auto"
          color="deep-purple darken-1"
          dark
          max-width="450"
           max-height="390"
        >
          <v-card-title>
            <v-icon large left> mdi-twitter </v-icon>
            <span class="title font-weight-light">Twitter</span>
          </v-card-title>

          <v-card-text class="headline font-weight-bold">
            "Nos ayudaron a aprovechar las nuevas tecnologías para hacer crecer
            nuestro negocio. Soluciones escalables capaces de soportar el
            crecimiento de recursos con el uso intensivo de todo tipo de
            contenido, almacenamiento y procesos."
          </v-card-text>

          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="grey darken-3">
                <v-img
                  class="elevation-6"
                  alt=""
                  src="https://pbs.twimg.com/profile_images/628570533064507392/o46Pj8L3.png"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>HomeCenter</v-list-item-title>
              </v-list-item-content>

              
                <v-icon class="mr-1"> mdi-heart </v-icon>
                <span class="subheading mr-2">436</span>
                <span class="mr-1"></span>
                <v-icon class="mr-1"> mdi-share-variant </v-icon>
                <span class="subheading">45</span>
              
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-app>
    </div>

    <!-- 2 tarjeta -->
    <div id="app">
      <v-app id="inspire"
        ><v-card
          class="mx-auto"
          color="deep-purple darken-1"
          dark
          max-width="450"
           max-height="390"
        >
          <v-card-title>
            <v-icon large left> mdi-twitter </v-icon>
            <span class="title font-weight-light">Twitter</span>
          </v-card-title>

          <v-card-text class="headline font-weight-bold">
            "Los empleados ahora pueden conectarse, interactuar en equipo,
            comunicarse mejor, compartir conocimientos y mejorar sus
            habilidades. Un equipo bien coordinado brinda mayor seguridad,
            motivación y mejores resultados"
          </v-card-text>

          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="deep-purple darken-3">
                <v-img
                  class="elevation-6"
                  alt=""
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAilBMVEXE0wD////B0QDq76vd5ob8/fDG1AD+/vj///3d5YP9/vXp76n6++X7/On7/OzT3lTl7Jr099Pr8LTR3UbQ3D/x9MvJ1yfn7aLa43DX4mre5n/I1hvO20z1+NzO2zfw9MTa5GfT317f54/b5Hfw9MXu8rri66zm7sXf6JPp78jk7Lv1+NLi6Zrz9tfwPhfqAAAECElEQVR4nO2dWXMiMQyEbQHDfQQGSBiukINsjv//9xYYyVWBsLu1lSmXO/09kjyoy4estgzOEUIIIYQQQgghhBBCCCGEEEIIIYQQQgghhJCEEFcsl8PhchI7kIqQbDHt+SOr2KFUgqw3fd+YDjMRiR1LFUj2cRi75hpS3BGpd1oHhXewAt2247EF3jUP+gb3sALlJNCPcAXWTxmiX8QOpDJm05PCLu4Q1k4Cm8PYgVTGpFFO0ix2IJVRzlHcfUaGpUDgXDgqBTZmsQOpilm/VHiDugxloZMUNlfIkyqEPbEVDVWIOkndsqnLMHYgVSG6k/ox6iSVjSrcoSp0Okk9qrnmcg++0Whl6H0PdZLKGD3fuxtV+ICqMFOBHfiNpgG70TyowinqJA35Hra+P11VQNf3Vv3ibjRm0axQvWDZqcIb1EkaTjSwhUXWU4WwbvdaHYwG6jJ0961S4UfsQKoibDRPqMtQHtELi+Bg5LEDqYqZKYwdSFX8gMLiHd3BwLdKRZdhC7awMI+mGTuQqgi327j5vobuYFgLhr+FVbjSwgLmRCNnrM3BuPhLomMqo9onunZ/35jXzpinaQ8X/p9J9Do439WPtJ/b8/1Lff/6y/SsXl/3u/bz/vjH/bh9+I9l7Fj/k7O1Ztmwl4Eswwu2qhC3FWqX9qL7O8Eqhc33mbVCrWNHUhV5B72waOsQPsaOpCpkrgprqMswWKWLLxRiiLYTzcWNhWT3uxxA40QFDs61FN2e963NMHWNcqsKLxwMOwiknkRCvn85U5hrWezrqQ/iW6mjdff549DW7leJH1fNSDx/YxFaFZN/6Wyl0+Dsc7kzhZsocX0bYaguCotiAHIgNyPxIt/LojyRj6KE9X0UumM2L/0KyecN//ac+Ai6tRYWva8fc2XJn9vCfoLbg2GFxTz1sbqKHVxwey4tJcC+qbTHXD3UZq+Q73EdDCsskq8frmEdCrg9l6EVKvEC6Sqy1Z7LFewktXyPe2NhRuI7rELN97itUHbd3YTdaMxIfISdpNaDAdtzaUbilzcWENi3ROC0Qp1jNxY92I3GXO0P1EmK/5grOBiwhcVEjcQ+qoPxA4xE+zoa3BMNfOtzaIXCzfcddAfDHnO9xY6kKqSrCpO/PruGhMfbqAqtQwH4xkIF4n6HAn7rs72phL04dGokdlLvWrtKDj9Jrb6HNaHMZoOtDV2h+b6NOoR2KMUdQqeH0nbsOCpDv28H9xcQ9Ga0BXvodkUT+0hqVnCib3z/AXkpf2cFV+Ds5HUn3r39B2R2rCpWW9Q1KNnu2EIzAq0o8uVw12/5QQ31KkZOSX68mKFOUOeyLHM4b+wJIYQQQgghhBBCCCGEEEIIIYQQQgghhBBCCEmN31AtJjoofYNhAAAAAElFTkSuQmCC"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>Falabella</v-list-item-title>
              </v-list-item-content>

              
                <v-icon class="mr-1"> mdi-heart </v-icon>
                <span class="subheading mr-2">4326</span>
                <span class="mr-1"></span>
                <v-icon class="mr-1"> mdi-share-variant </v-icon>
                <span class="subheading">425</span>
             
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-app>
    </div>
    <!-- 3 tarjeta -->
    <div id="app">
      <v-app id="inspire">
        <v-card
          class="mx-auto"
          color="deep-purple darken-1"
          dark
          max-width="450"
          max-height="380"
        >
          <v-card-title>
            <v-icon large left> mdi-twitter </v-icon>
            <span class="title font-weight-light">Twitter</span>
          </v-card-title>

          <v-card-text class="headline font-weight-bold">
            "Excelentes resultados por el servicio ofrecido por esta 
            compañia, logramos trabajar de forma remota o en la 
            oficina, con múltiples dispositivos y sistemas 
            de operaciones de datos claves."
          </v-card-text>
          <br /><br />
          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="deep-purple darken-3">
                <v-img
                  class="elevation-6"
                  alt=""
                  src="data:image/png;base64,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"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>Totto</v-list-item-title>
              </v-list-item-content>

              
                <v-icon class="mr-1"> mdi-heart </v-icon>
                <span class="subheading mr-2">2126</span>
                <span class="mr-1"></span>
                <v-icon class="mr-1"> mdi-share-variant </v-icon>
                <span class="subheading">358</span>
              
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-app>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    //
  }),
};
</script>