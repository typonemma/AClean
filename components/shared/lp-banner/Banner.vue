<template>
  <div class="banner-wrapper">
    <v-container>
      <!-- -----------------------------------------------
            Start Banner
        ----------------------------------------------- -->
      <v-row justify="center">
        <v-col cols="12" md="7" lg="6" class="d-flex align-center">
          <div class="text-center text-md-left">
            <h1 class="banner-title font-weight-bold white--text">
             AClean
            </h1>
            <h4 class="banner-subtitle white--text font-weight-regular">
              Pengalaman baru service AC
            </h4>
            <div class="mt-16 pt-2 ">
              <v-btn
                class=""
                nuxt
                color="primary"
                depressed
                to="/"
                elevation="0" >
                Download AClean
              </v-btn>
            </div>
          </div>
        </v-col>
        <v-col cols="8" md="4" lg="4">
          <v-img
            :src="require('@/assets/images/landingpage/appdownload.png')"
            alt="banner"
          />
        </v-col>
      </v-row>

      <!-- -----------------------------------------------
            End Banner
        ----------------------------------------------- -->
    </v-container>
  </div>
</template>
<script>
export default {
  name: "Banner",
  data() {
    return {};
  }
};
</script>
