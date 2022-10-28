<template>
  <div class="logo">
    <NLink to="/">
      <v-img
        :src="require('@/assets/images/logos/aclean-logo.png')"
        alt="logo"
      />
    </NLink>
  </div>
</template>

<script>
export default {
  name: "Logo",

  data() {
    return {};
  },
};
</script>

<style lang="scss">
.logo a {
  display: flex;
  width: 40px;
  height: 40px;
}
</style>