<template>
  <div class="search-page">
    <mt-header fixed title="搜索">
      <router-link to="/" slot="left">
        <mt-button icon="back"></mt-button>
      </router-link>
    </mt-header>
  </div>
</template>

<script>
export default {
  head: {
    title: "搜索"
  },
  data() {
    return {
      value: ""
    };
  }
};
</script>

<style lang="scss">
@import "../assets/styles/mixin";

.search-page {
  padding: px2rem(88px) 0 0 0;
}
</style>
