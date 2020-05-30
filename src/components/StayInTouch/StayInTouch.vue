<template>
    <div>
        <v-sheet color="primary" style="color: #fff; border-radius: 0;">
            <v-container>
                <v-row>
                    <v-col cols="12" md="12" lg="6" class="offset-lg-3 text-center">
                        <h3>Stay In Touch!</h3>
                        <span style="font-size: 15px;">
                            Sign-up with your email address to receive news and updates.
                        </span>
                    </v-col>
                    <v-col cols="12" md="12" lg="6" class="offset-lg-3 text-center">
                        <v-text-field style="max-width: 50%;" height="35" color="white">
                        </v-text-field>
                        <v-btn flat>
                            Subscribe
                        </v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </v-sheet>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
h3 {
    font-size: 25px;
    font-weight: 500;
}
</style>