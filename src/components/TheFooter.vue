<template>
  <v-card height="400px" >
    
      
    <v-footer
      v-bind="localAttrs"
      :padless="padless"
      
    >
      <v-card
        flat
        tile
        width="100%"
        class="text-center"
        dark
               
      >
        <v-card-text>
          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4"
            icon
          >
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="white--text">
          {{ new Date().getFullYear() }} — <strong> Email - contactanos.tm@technomotion.com <br>
        Ciudades - Medellin / Bogotá <br>
        Celular - 3002381435 <br>
        Repositorio - <span> <a href="https://github.com/Grupo-42-Mision-TIC-2022/Semana-5-42-backend.git">Semana-5-42</a></span></strong>
        </v-card-text>
      </v-card>
    </v-footer>

    <v-row
      align="center"
      justify="center"
      class="ma-12"
    >
      
    </v-row>
  </v-card>
</template>

<script>

  export default {
    data: () => ({
      icons: [
        'mdi-home',
        'mdi-email',
        'mdi-calendar',
        'mdi-delete',
      ],
      items: [
        'default',
        'absolute',
        'fixed',
      ],
      padless: false,
      variant: 'default',
    }),
    computed: {
      localAttrs () {
        const attrs = {}
        if (this.variant === 'default') {
          attrs.absolute = false
          attrs.fixed = false
        } else {
          attrs[this.variant] = true
        }
        return attrs
      },
    },
  }
</script>