<template>
    <div>
        <v-btn
            href="#"
            target="_blank"
            height="65"
            text
        >
            <span class="mr-2">Home</span>
        </v-btn>
        <v-btn
            href="#"
            target="_blank"
            text
            height="65"
        >
            <span class="mr-2">About</span>
        </v-btn>
        <v-btn
            href="#"
            target="_blank"
            text
            height="65"
        >
            <span class="mr-2">Schedule</span>
        </v-btn>
        <v-btn
            href="#"
            target="_blank"
            text
            height="65"
        >
            <span class="mr-2">Gallery</span>
        </v-btn>
        <v-btn
            href="#"
            target="_blank"
            text
            height="65"
        >
            <span class="mr-2">Contact</span>
        </v-btn>
    </div>
</template>
<script>
export default {
    name: 'navbar'
}
</script>
<style scoped>
.v-toolbar__content a {
  color: #FFF;
  border-radius: 0px;
  box-shadow: inset 0 0 0 0 #ffd600;
  -webkit-transition: ease-out 0.4s;
  -moz-transition: ease-out 0.4s;
  transition: ease-out 0.4s;
}

.v-toolbar__content a:hover {
  box-shadow: inset 0 100px 0 0 #ffd600;
}
</style>