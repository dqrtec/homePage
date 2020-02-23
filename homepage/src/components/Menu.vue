<template>
  <div class="menu-leteral">
    <div class="card container" style="width:360px;">
      <img class="card-img-top" src="https://avatars0.githubusercontent.com/u/20565933?s=460&amp;v=4" style="width:260px;height=260px" alt="Card image">
      <div class="card-body">
        <h4 class="card-title">Dqrtec</h4>
        <p class="card-text">Learn in UFC</p>
        <a href="#" class="btn btn-primary">See GitHub</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Menu',
  props: {
  }
}
</script>

<style scoped>
.menu-leteral{
  padding: 0%;
  width: 30%;
  height: 100%;
  position:fixed;
  background-color: #c1c1c1;
}
.card{
  align-self: center
}
</style>
