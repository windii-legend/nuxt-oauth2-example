<template>
<v-app>
  <v-toolbar dark fixed app>
    <v-toolbar-title>Nuxt Oauth2 Auth</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat to="/mypage">マイページ</v-btn>
      <v-btn flat>ログアウト</v-btn>
      <v-btn flat to="/login">ログイン</v-btn>
    </v-toolbar-items>
  </v-toolbar>
  <v-content>
    <v-container fluid fill-height>
      <nuxt/>
    </v-container>
  </v-content>
</v-app>
</template>
