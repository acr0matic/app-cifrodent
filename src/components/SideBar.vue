<template>
  <div class="sidebar">
    <div id="nav">
      <router-link to="/">Рабочий стол</router-link> |
      <router-link to="/history">История заказов</router-link> |
      <router-link to="/profile">Профиль</router-link> |
      <router-link to="/notification">Оповещения</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SideBar'
}
</script>

<style scoped lang="scss">

#nav {
  a {
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

</style>
