<template>
    <main>
        <header class="py-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="10" md="6">
                        <v-img :style="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 'opacity: 0.5' : null" class="ml-16 rounded-circle" src="headerpic.jpg" aspect-ratio="1"> </v-img>
                    </v-col>
                    <v-col cols="10" md="6" class="headerNudge ml-n16" style="z-index: 1" :style="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 'marginTop:-200px' : null">
                        <h3>Got a new website?</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">Let us handle the boring stuff.</h1>
                        <p class="ml-16 mt-3">Managing your web hosting can be a hassle, Have a one of our engineers regularly update your software, check for security flaws, Alert you if your site goes down and offer 24/7 online support if you need any help or advice </p>
                        <v-btn x-large rounded class="m mt-3 secondary">Sign up</v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </header>
        <section class="primary py-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="10" md="4">
                        <h3 class="display-1 white--text pb-5">Choose the package thats right for you</h3>
                        <p>something something something something something</p>
                    </v-col>
                    <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="0">
                            <div>ic</div>
                            <small class="primary--text d-inline">£</small>
                            <h2 class="primary--text d-inline display-2">30</h2>
                            <p class="primary--text -2">Per month</p>
                            <v-btn class="secondary my-5" rounded>Sign up</v-btn>
                        </v-card>
                    </v-col>
                    <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="0">
                            <div>ic</div>
                            <small class="primary--text d-inline">£</small>
                            <h2 class="primary--text d-inline display-2">200</h2>
                            <p class="primary--text -2">Per year</p>
                            <v-btn class="secondary my-5" rounded>Sign up</v-btn>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </section>
        <section>
            <v-parallax class="p-relative " src="office.jpg"  height="500">

                <v-row relative z-index="3" align="center" justify="center">
                    <v-col class="text-center" cols="10" md="7">
                        <h1 class="display-1 font-weight-thin mb-4">Limited Spaces</h1>
                        <h4 class="subheading">We're a small boutique business that keeps our client base small so that we can give each of or clients our attention (needs work). Due to this, we have limited space for new clients. <br/><v-btn class="primary my-5" rounded>Sign up today</v-btn> <br/>to guarantee your place.</h4>
                    </v-col>
                </v-row>
                 <v-overlay absolute z-index="-1"></v-overlay>
            </v-parallax>
        </section>
    </main>
</template>

<script>
export default {
    components: {

    }
}
</script>


