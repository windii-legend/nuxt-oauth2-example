<template>
<v-container>
  <v-avatar :tile="tile" :size="100" color="grey lighten-4">
    <img :src="$auth.$state.user.avatar_url" alt="avatar">
  </v-avatar>
  <h1>こんにちは、{{$auth.$state.user.name}}さん!</h1>
</v-container>
</template>

<script>
export default {
  middleware: 'auth',
}
</script>
