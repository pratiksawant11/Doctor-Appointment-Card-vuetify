<template>
  <v-card max-width="400" class="mx-auto my-10">
    <v-img width="400" height="400" src="../assets/ddd.jpg" />
    <v-card-title>Dr.XI</v-card-title>
    <v-card-text>
      <v-row align="center" class="mx-0">
        <v-rating :value="4.5" color="indigo" size="14" dense half-increments />
        <div class="grey--text ml-4">4.5</div>
      </v-row>

      <div class="my-4 subtitle-1 black--text">Full Stack</div>
      <div class="subtitle-1">11, XI Hospital,opp Inox Mall, Ghatkopar (E)</div>
    </v-card-text>
    <v-divder></v-divder>
    <hr />
    <v-card-title>Todays Availability</v-card-title>
    <v-card-text>
      <v-chip-group active-class="light-blue accent-4 white--text">
        <v-chip>9.30AM</v-chip>
        <v-chip>1.00PM</v-chip>
        <v-chip>5.00PM</v-chip>
        <v-chip>8.00PM</v-chip>
      </v-chip-group>
    </v-card-text>
    <v-card-actions>
      <v-btn class="indigo accent-4">BOOK APPOINTENT</v-btn>
    </v-card-actions>
  </v-card>
</template>
  <script>
export default {};
</script>