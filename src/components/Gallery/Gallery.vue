<template>
    <div>
        <v-container grid-list-md class="mt-6">
            <v-layout wrap>
                <v-row>
                    <v-col md="7" class="offset-lg-2 text-center">
                        <h3>Our Gallery</h3>
                        <span>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum 
                        </span>
                    </v-col>
                    <v-col class="mt-2 ml-6 offset-lg-2" md="12">
                        <div class="mb-3 ml-3 d-inline-block" v-for="(item, index) in items" :key="index">
                            <v-img class="img-fluid" :src="item.src" />
                        </div>
                    </v-col>
                </v-row>
            </v-layout>
        </v-container>
    </div>
</template>
<script>
export default {
    name: 'gallery',
    data: () => ({
        items: [
            { src: require('../../assets/1.png') },
            { src: require('../../assets/2.png') },
            { src: require('../../assets/3.png') },
            { src: require('../../assets/4.png') },
            { src: require('../../assets/5.png') },
            { src: require('../../assets/6.png') }
        ]
    })
}
</script>

<style scoped>
.v-application--is-ltr .offset-lg-2 {
    margin-left: 21%;
}
</style>