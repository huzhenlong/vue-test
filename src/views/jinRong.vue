<template>
  <div>
    <van-nav-bar>
      <template #title>
        <span class="tle">金融</span>
      </template>
      <template #left>
        <van-icon name="arrow-left" size="18" color="#000"/>
      </template>
      <template #right>
        <van-icon name="arrow-left" size="18" color="#000"/>
      </template>
    </van-nav-bar>
  </div>
</template>

<script>
export default {
  name: "jinRong"
}
</script>

<style scoped>
.tle {
  font-size: 18px;
  font-weight: bold;
  letter-spacing: 1px;
}
</style>