<template>
    <v-app>

        <v-app-bar :clipped-left="clipped" hide-on-scroll app>
            <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
            <v-toolbar-title v-text="title" />
            <v-spacer />
        </v-app-bar>
        <v-main>
            <v-container>
                <nuxt />
            </v-container>
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
