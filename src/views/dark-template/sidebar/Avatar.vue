<template>
  <div class="text-md-center">
    <v-avatar
      size="200"
    >
      <img
        :src="publicPath('/img/avatar.jpg')"
        class="avatar-img"
        alt="Uladislau Shusterman"
      >
    </v-avatar>
  </div>
</template>

<script>
export default { name: 'Avatar' }
</script>

<style scoped>
.avatar-img {
  height: 200px;
  width: 140px;
  border-radius: 8%;
}
</style>
