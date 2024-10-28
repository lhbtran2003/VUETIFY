<script setup lang="ts">

import {CaUserAvatarFilledAlt} from "@kalimahapps/vue-icons";
</script>

<template>
  <v-row>
    <v-col>
      <form @submit.prevent="submit">
        <v-text-field
            label="Name"
        ></v-text-field>

        <v-text-field
            label="Phone Number"
        ></v-text-field>

        <v-text-field

            label="E-mail"
        ></v-text-field>

        <v-btn
            class="me-4"
            type="submit"
        >
          submit
        </v-btn>

      </form>
    </v-col>
    <v-col>
      <form @submit.prevent="submit">
        <v-text-field
            label="Name"
        >
          <CaUserAvatarFilledAlt/>
        </v-text-field>

        <v-text-field
            label="Phone Number"
        ></v-text-field>

        <v-text-field

            label="E-mail"
        ></v-text-field>

        <v-btn
            class="me-4"
            type="submit"
        >
          submit
        </v-btn>

      </form>

    </v-col>
  </v-row>
</template>


<style scoped>

</style>