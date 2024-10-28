<script setup lang="ts">

import {green} from "vuetify/util/colors";
</script>

<template>
  <v-table>
    <thead>
    <tr>
      <th class="text-left">
        Name
      </th>
      <th class="text-left">
        Calories
      </th>
      <th>Status</th>
    </tr>
    </thead>
    <tbody>
    <tr

    >
      <td>abc</td>
      <td>xyz</td>
      <td><v-btn

          :color="green"

          size="small"


      ></v-btn></td>
    </tr>
    </tbody>
  </v-table>
</template>

<style scoped>

</style>