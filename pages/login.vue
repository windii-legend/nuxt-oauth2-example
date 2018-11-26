<template>
<v-container>
<v-form>
  <v-card>
    <v-card-title>ログイン</v-card-title>
    <v-btn dark @click="loginWithGitHub">GitHubでログイン</v-btn>
  </v-card>
</v-form>
</v-container>
</template>

<script>
export default {
  methods: {
    loginWithGitHub: function () {
      this.$auth.loginWith('github')
    }
  }
}
</script>
