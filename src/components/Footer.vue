<template>
  <v-footer class="d-flex flex-column">
    <div class="d-flex w-100 px-6 pb-10 pt-8">
      <v-row>
        <v-col cols="12" sm="3">
          <h4 class="mt-2">EXPLORE</h4>
          <span class="text-caption">
            continually productize<br />
            compelling dome packed with<br />all Elated utilize website and
            <br />creating supply next-generation
          </span>
          <br />
          <h4 class="mt-2">Fallow Us On</h4>
          <v-icon class="mr-1" icon="mdi mdi-facebook"></v-icon>
          <v-icon class="mr-1" icon="mdi mdi-twitter"></v-icon>
          <v-icon class="mr-1" icon="mdi mdi-instagram"></v-icon>
          <v-icon class="mr-1" icon="mdi mdi-whatsapp"></v-icon>
          <v-icon class="mr-1" icon="mdi mdi-linkedin"></v-icon>
        </v-col>
        <v-col cols="12" sm="3">
          <h4 class="mt-2">Tour Type</h4>
          <span class="text-caption">Adventure Tour</span><br />
          <span class="text-caption">Group Tour</span><br />
          <span class="text-caption">Seasonal Tours</span><br />
          <span class="text-caption">Relaxation Toure</span><br />
          <span class="text-caption">Family Friendly Toure</span><br />
        </v-col>
        <v-col cols="12" sm="3">
          <h4 class="mt-2">Contact Info</h4>
          <span class="text-caption">
            <v-icon class="mr-1" icon="mdi mdi-phone"></v-icon>
            88130-589-745-6987<br />+1655-456-523
          </span>
          <br />
          <span class="text-caption">
            <v-icon class="mr-1" icon="mdi mdi-clock-time-eight"></v-icon
            >Mon-fri 09:00-18:00<br />except Public Holidays
          </span>
          <br />
          <span class="text-caption">
            <v-icon class="mr-1" icon="mdi mdi-map-marker"></v-icon>25/2 vokte
            street<br />building Melborn City
          </span>
          <br />
        </v-col>
        <v-col cols="12" sm="3">
          <h4 class="mt-2 text-center">Gallery</h4>
          <v-row>
            <v-col cols="4" class="d-flex child-flex" v-for="n in 6" :key="n">
              <v-img
                :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
                :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                aspect-ratio="1"
                cover
                bg-grey-lighten-2
              ></v-img>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </div>
    <div class="px-4 py-8 bgTop text-center w-100 text-black">
        <v-icon class="mr-2" color="black">mdi mdi-copyright</v-icon>
        <strong>
            >copyright {{ new Date().getFullYear()}} all Rights Reserved by AmirHosien Porgoli
        </strong>
    </div>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
v-footer {
  padding: 0 0 !important;
}
.bgTop {
  background-color: #f4f6fa;
}
</style>