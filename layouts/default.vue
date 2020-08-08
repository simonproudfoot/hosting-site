<template>
    <v-app>

        <v-app-bar :clipped-left="clipped" hide-on-scroll app>

              <v-toolbar-title v-text="title" />
            <v-spacer />
               <v-btn class="primary--border" outlined="" rounded >Sign in</v-btn>
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

            title: 'Hosting'
        }
    }
}
</script>
