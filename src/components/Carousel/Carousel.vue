<template>
  <div>
    <v-carousel hide-delimiters>
      <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
        <v-container style="margin-top: 50px;" text-center>
          <v-layout wrap>
            <v-row class="justify-left">
              <v-col md="4" lg="4" class="text-center">
                <h3>dance</h3>
                <h3 style="color: #ffd600;">studio</h3>
                <span>
                    A Complete Dance Class
                </span>
                <v-btn color="#ffd600" rounded>
                    Join Now
                </v-btn>
              </v-col>
            </v-row>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>
<script>
export default {
  name: "carousel",
  data: () => ({
    items: [{ src: require("../../assets/banner-bg.png") }]
  })
};
</script>

<style scoped>
h3 {
  font-size: 86px;
  color: #ffffff;
  font-family: "Roboto";
  font-weight: 500;
  text-transform: uppercase;
  padding: 0;
}

span {
    color: #ffffff;
    font-size: 20px;
    display: block;
    margin-bottom: 15px;
}
</style>