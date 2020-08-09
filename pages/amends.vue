<template>
    <main>
        <header class="py-16">
            <v-container>
                <v-row align="center" justify="center">
                   <v-col cols="12" md="6" class="ml-n16">
                        <v-img class="ml-md-16" src="wp.jpg" :aspect-ratio="$vuetify.breakpoint.xs ||  $vuetify.breakpoint.sm ? 1.4 : 1"> </v-img>
                    </v-col>
                    <v-col cols="10" md="6" style="z-index: 1">
                        <h3>Services</h3>
                        <h1 class="display-2 primary--text" style="text-transform: capitalize">Need amends?</h1>
                        <p class="ml-16 mt-3">Server companies don't usually make websites... But we're not your average server company. Our developers can make design and build you a website<br/><br/>
                            <h4 class="primary--text">From £500<br/><small>Per amend</small></h4>
                    </v-col>
                </v-row>
            </v-container>
        </header>
    </main>
</template>
