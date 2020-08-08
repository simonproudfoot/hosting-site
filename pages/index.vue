<template>
    <main>
        <header class="py-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="10" md="6">
                        <v-img class="rounded-circle" src="/headerpic.jpg" aspect-ratio="1.1"> </v-img>
                    </v-col>
                    <v-col cols="10" md="6" class="ml-n16" style="z-index: 1">
                        <h3>Got a new website?</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">Let us handle the boring stuff.</h1>
                        <p class="ml-16 mt-3">Managing your web hosting can be a hassle, Have a one of our engineers regularly update your software, check for security flaws, Alert you if your site goes down and offer 24/7 online support if you need any help or advice </p>
                        <v-btn x-large class="m mt-3 secondary">Sign up</v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </header>
        <section>
            <v-container>
                <v-row align="center" justify="center">
                   <v-col cols="10" md="4">
                      <h3 class="display-1 pb-5">Choose the package thats right for you</h3>
                      <p>something something something something something</p>
                   </v-col>

                    <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="0">
                          <div>ic</div>
                          <small class="primary--text d-inline">£</small>
                          <h2 class="primary--text d-inline display-2">30</h2>
                          <p class="primary--text -2">Per month</p>
                        </v-card>
                    </v-col>
                     <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="0">
                          <div>ic</div>
                          <small class="primary--text d-inline">£</small>
                          <h2 class="primary--text d-inline display-2">200</h2>
                          <p class="primary--text -2">Per year</p>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </section>
    </main>
</template>

<script>
export default {
    components: {

    }
}
</script>
