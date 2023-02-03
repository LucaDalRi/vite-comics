<script>

export default {
  name: 'AppHeader',
}

</script>

<template>
  <div class="containerHeader">
    <div class="containerLogoHeader">
      <img src="../assets/img/dc-logo.png" alt="DC Logo Header">
    </div>
    <div class="containerLinksHeader">
      <ul>
        <li><a href="#">Character</a></li>
        <li><a class="active" href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.containerHeader {
  display: flex;
  align-items: center;
  height: 150px;
  text-align: center;
}

.containerLogoHeader {
  width: 40%;
}

.containerLinksHeader {
  width: 60%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;

  ul {
    display: flex;
    justify-content: center;
    list-style: none;

    li a {
      text-decoration: none;
      color: rgb(0, 0, 0);
      margin: 0 20px;

      .active {
        color: rgb(29, 79, 218);
      }
    }

  }

}
</style>