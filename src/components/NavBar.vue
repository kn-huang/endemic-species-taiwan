<template>
  <div id="navbar">
    <nav class="navbar navbar-expand-md navbar-light bg-light sticky-top">
      <div class="container-fluid">
        <a href="#index" class="navbar-brand">特別有種</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a href="#story" class="active nav-link">動物故事</a>
            </li>
            <li class="nav-item">
              <a href="#issue" class="nav-link">動物議題</a>
            </li>
            <li class="nav-item">
              <a href="#about" class="nav-link">關於我們</a>
            </li>
            <li class="nav-item">
              <a href="#website" class="nav-link">相關網頁</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: 'NavBar'
}
</script>
<style scoped lang="scss">
  
</style>