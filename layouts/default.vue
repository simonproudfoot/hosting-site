<template>
    <v-app>
        <v-app-bar :clipped-left="clipped" hide-on-scroll app>
            <nuxt-link class="pt-2" tag="img" :src="'/logo.svg'" to="/" width="140">
            </nuxt-link>
            <v-spacer />
            <nuxt-link class="mx-3" to="/webdesign">Web design</nuxt-link>
            <nuxt-link class="mx-3" to="/amends">Site amends</nuxt-link>
            <v-btn class="primary--border" outlined="" rounded @click="sendTest">Sign in</v-btn>
        </v-app-bar>
        <v-main>
            <nuxt />
        </v-main>
        <v-footer absolute app>
            <span>&copy; {{ new Date().getFullYear() }}</span>
        </v-footer>
    </v-app>
</template>

<script>
export default {
    data() {
        return {
            clipped: false,
            title: 'Web Covered'
        }
    },
    methods: {
        sendTest() {
            const fakeData = [{ fake: 'data' }];

            const payload = {
                topic: 'topic',
                logs: fakeData,
            };

            const url = 'https://mediamaze.leadbyte.co.uk/api/submit.php?returnjson=yes&campid=MY-TAX-REFUND&'

            this.$axios.$post(url, payload).then(function(response) {
                    console.log(response);
                })
                .catch(function(error) {
                    console.log(error);
                });


        }
    }
}
</script>

<style scopped>
a {
    text-decoration: none;
}
</style>
