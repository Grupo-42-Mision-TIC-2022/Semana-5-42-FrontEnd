<template>
  <div class="d-flex justify-content-center p-2">
    <v-card class="mx-auto" max-width="344">
      <v-img
        src="https://media.giphy.com/media/PiuL0MyzhlQv9fkNrY/giphy.gif"
        height="200px"
      ></v-img>

      <v-card-title> Servicios locales y remotos </v-card-title>

      <v-card-subtitle>
        Data y Analytics: la mejor respuesta para enfrentar la crisis Un negocio
        al cual se puede acceder en cualquier momento y lugar. No te compliques,
        si tus clientes o tus colaboradores requieren una herramienta por la
        cual puedan realizar todas sus tareas no solo de forma segura, eficiente
        e intuitiva sino que además con disponibilidad 24/7, entonces es hora de
        contratar un desarrollo web. <br />
      </v-card-subtitle>

      <v-card-actions>
        <v-btn color="blue" text> Explore </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>

          <v-card-text>
            Recopilación de datos data managment <br />
            Cloud computing <br />
            Erp managment <br />
            Gestión documental <br />
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <!-- segunda  tarjeta -->
    <v-card class="mx-auto" max-width="344">
      <v-img
        src="https://media.giphy.com/media/uH3ka2LMTxFxS/giphy.gif"
        height="200px"
      ></v-img>

      <v-card-title>
        Diseño visual y experiencia <br />
        de usuario
      </v-card-title>

      <v-card-subtitle>
        Desarrollamos las mejores interfaces de aplicaciones, paginas web <br />
        Son todas las tecnologías de diseño y desarrollo web que corren en el
        navegador y que se encargan de la interactividad con los usuarios.
        Podrás gestionar tu negocio en internet, pasarelas d epago, gestión de
        contenidos, etc.
      </v-card-subtitle>

      <v-card-actions>
        <v-btn color="green" text> Explore </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>

          <v-card-text>
            Frontend visual <br />
            Soluciones a su medida (aplicativos, APIS, bases de datos) <br />
            Gestión humana y financiera <br />
            Servicios de comunicación interna: noticias, información de eventos
            ejm muro de facebook pero interno
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>
    <!-- tercera tarjeta -->
    <v-card class="mx-auto" max-width="344">
      <v-img
        src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif"
        height="200px"
      ></v-img>

      <v-card-title>
        Desarrollo de <br />
        la programación
      </v-card-title>

      <v-card-subtitle>
        Consiste en un servidor, una aplicación y una base de datos <br />
        ASP.NET , PHP, Python, Ruby, Node.js, Java, MySQL, SQL Server,
        PostgreSQL, Oracle, MongoDB
      </v-card-subtitle>

      <v-card-actions>
        <br /><br /><br /><br />
        <v-btn color="blue" text> Explore </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>

          <v-card-text>
            Soluciones a su medida (aplicativos, APIS, bases de datos) <br />
            Gestión humana y financiera <br />
            Servicios de comunicación interna: noticias, información de eventos
            ejm muro de facebook pero interno
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>
  </div>
</template>

<script>
export default {
  data: () => ({
    show: false,
  }),
};
</script>