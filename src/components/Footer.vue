<template>
  <v-footer dark padless class="footer">
    <v-card
      flat
      tile
      class="black white--text py-3 px-5 text-center"
      width="100%"
    >
      <v-row>
        <v-col cols="12" class="text-center pt-2">
          <div>&copy; {{ new Date().getFullYear() }} Dhruv Arora <br> All rights reserved.</div>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data() {
    return {
      icons: ['mdi-facebook', 'mdi-twitter', 'mdi-linkedin', 'mdi-instagram']
    };
  },
};
</script>

<style>
.footer {
  border-top: 4px solid red; 
}
</style>
