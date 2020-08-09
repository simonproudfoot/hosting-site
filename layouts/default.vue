<template>
    <v-app>
        <v-app-bar :clipped-left="clipped" hide-on-scroll app>
             <nuxt-link to="/"><v-toolbar-title v-text="title" /></nuxt-link>
            <v-spacer />

            <nuxt-link class="mx-3" to="/webdesign">Web design</nuxt-link>
            <nuxt-link class="mx-3" to="/amends">Site amends</nuxt-link>
             <v-btn class="primary--border" outlined="" rounded>Sign in</v-btn>
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
            title: 'logo'
        }
    }
}
</script>
<style scopped>
  a{
    text-decoration: none;
  }
</style>
