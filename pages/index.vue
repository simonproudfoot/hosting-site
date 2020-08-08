<template>
    <main>
        <header class="py-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="10" md="6">
                        <v-img :style="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 'opacity: 0.5' : null" class="ml-16 roundd-circle" src="headerpic.jpg" aspect-ratio="1"> </v-img>
                    </v-col>
                    <v-col cols="10" md="6" class="headerNudge ml-n16" style="z-index: 1" :style="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 'marginTop:-200px' : null">
                        <h3 class="ml-16">Got a new website?</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">Let us handle the boring stuff.</h1>
                        <p class="ml-16 mt-3">Managing your web hosting can be a hassle, Have a one of our engineers regularly update your software, check for security flaws, Alert you if your site goes down and offer 24/7 online support if you need any help or advice </p>
                        <v-btn x-large rounded elevation="0" class="mt-3 secondary">Sign up</v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </header>
        <section class="primary py-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="10" md="4">
                        <h3 class="display-1 white--text pb-5">Choose the package thats right for you</h3>
                        <p class="white--text">something something something something something</p>
                    </v-col>
                    <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="20">
                            <div>ic</div>
                            <small class="primary--text d-inline">£</small>
                            <h2 class="primary--text d-inline display-2">30</h2>
                            <p class="primary--text -2">Per month</p>
                            <v-btn class="secondary my-5" elevation="0" rounded>Sign up</v-btn>
                        </v-card>
                    </v-col>
                    <v-col cols="10" md="4">
                        <v-card rounded class="text-center py-16" elevation="20">
                            <div>ic</div>
                            <small class="primary--text d-inline">£</small>
                            <h2 class="primary--text d-inline display-2">200</h2>
                            <p class="primary--text -2">Per year</p>
                            <v-btn class="secondary my-5" elevation="0" rounded>Sign up</v-btn>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </section>
        <section>
            <v-parallax class="p-relative " src="office.jpg" height="500">
                <v-row relative z-index="3" align="center" justify="center">
                    <v-col class="text-center" cols="10" md="7">
                        <h1 class="display-1 font-weight-thin mb-4">Limited Spaces</h1>
                        <h4 class="subheading">We're a small boutique business that keeps our client base small so that we can give each of or clients our attention (needs work). Due to this, we have limited space for new clients. <br/>
                            <v-btn class="primary my-5" rounded>Sign up today</v-btn> <br/>to guarantee your place.</h4>
                    </v-col>
                </v-row>
                <v-overlay absolute z-index="-1"></v-overlay>
            </v-parallax>
        </section>

        <section class="pt-16">
            <v-container>
                <v-row align="center" justify="center">

                    <v-col cols="10" md="6" style="z-index: 1">
                        <h3>With you from the start</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">We can make you a website</h1>
                        <p class="ml-16 mt-3">Server companies don't usually make websites... But we're not your average server company. Our developers can make design and build you a website<br/><br/>
                            <h4 class="primary--text">From £500<br/><small>Per amend</small></h4>
                    </v-col>
                    <v-col cols="12" md="6" class="ml-n16">
                        <v-img class="ml-md-16" src="office2.jpg" :aspect-ratio="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 1.4 : 1"> </v-img>
                    </v-col>
                </v-row>
            </v-container>
        </section>
        <section class="pt-16">
            <v-container>
                <v-row align="center" justify="center">
                    <v-col cols="12" md="6" class="ml-n16">
                        <v-img class="ml-md-16" src="wp.jpg" :aspect-ratio="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 1.4 : 1"> </v-img>
                    </v-col>
                    <v-col cols="10" md="6" style="z-index: 1">
                        <h3>Web developers on hand</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">Need website amends?</h1>
                        <p class="ml-16 mt-3">Server companies don't can't usually make amends to your website... But we're not your average server company. Wordpress makes it easy for users to amend their content. However, there may be elements of the site that need a profesional
                            to update.<br/><br/>
                            <h4 class="primary--text">From £50<br/><small>Per amend</small></h4>


                    </v-col>

                </v-row>
            </v-container>
        </section>

        <section class="py-16">
            <v-row relative z-index="3" align="center" justify="center">
                <v-col cols="12" class="text-center">
                    <h2 class="display-1 mb-5">Questions???</h2>
                </v-col>
                <v-col class="text-" cols="10" md="7">
                    <v-expansion-panels accordion>
                        <v-expansion-panel>
                            <v-expansion-panel-header>
                                <h3 class="primary--text">How long does it take?</h3>
                            </v-expansion-panel-header>
                            <v-expansion-panel-content>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                            </v-expansion-panel-content>
                        </v-expansion-panel>
                        <v-expansion-panel>
                            <v-expansion-panel-header>
                                <h3 class="primary--text">Can I cancel at any time?</h3>
                            </v-expansion-panel-header>
                            <v-expansion-panel-content>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                            </v-expansion-panel-content>
                        </v-expansion-panel>
                        <v-expansion-panel>
                            <v-expansion-panel-header>
                                <h3 class="primary--text">Is my data secure?</h3>
                            </v-expansion-panel-header>
                            <v-expansion-panel-content>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                            </v-expansion-panel-content>
                        </v-expansion-panel>
                    </v-expansion-panels>
                </v-col>
            </v-row>
        </section>
    </main>
</template>

<script>
export default {
    components: {

    }
}
</script>


