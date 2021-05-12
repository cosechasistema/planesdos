<template>
  <v-container>

  <v-card
    class="mx-auto"
    max-width="344"
    :elevation= 10
  >


    <v-img
      contain
      src="../assets/Credencial-Integral-A.png"
      height="300px"
    ></v-img>

    <v-card-title>
      <p>Plan Integral</p>
    </v-card-title>

    <v-card-subtitle>
      <p>Consultas médicas ambulatorias 100%</p>
<p>Prácticas médicas, bioquímicas, radiológicas 100% (con autorización y con coseguro)</p>
<p>Prácticas Kinesiológicas 100% (con autorización y con coseguro)</p>
<p>Medicamentos ambulatorios VADEMECUM LIBRE</p>
<p>En farmacia propia descuentos de 30% + hasta un 20%</p>
<p>Farmacias adheridas descuentos 30%</p>
<p>Odontología 100% (excluido prótesis y ortodoncia) (con autorización)</p>
<p>Internaciones clínicas y/o quirúrgicas ( con autorización y sin coseguro)</p>
<p>Medicamentos y descartables en internaciones 100%</p>
<p>Cirugías y prácticas de alta complejidad nomecladas ( con autorización y con coseguro)</p>
<p>Cirugía y prácticas de alta complejidad NO nomecladas ( con autorización y con coseguro)</p>
<p>Ordenes con cargo</p>
    </v-card-subtitle>


    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to Vuetify
        </h1>

        <p class="subheading font-weight-regular">
          For help and collaboration with other Vuetify developers,
          <br>please join our online
          <a
            href="https://community.vuetifyjs.com"
            target="_blank"
          >Discord Community</a>
        </p>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          What's next?
        </h2>

        <v-row justify="center">
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Important Links
        </h2>

        <v-row justify="center">
          <a
            v-for="(link, i) in importantLinks"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ link.text }}
          </a>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Ecosystem
        </h2>

        <v-row justify="center">
          <a
            v-for="(eco, i) in ecosystem"
            :key="i"
            :href="eco.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ eco.text }}
          </a>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {

}
</script>
