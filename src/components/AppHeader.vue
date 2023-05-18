<script>
export default {

}
</script>

<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="">
    <nav>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header{
  margin-inline: auto;
  width: 80%;
  height: 130px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  img{
    height: 90px;
  } 

  ul{
    display: flex;
    gap: 1em;
    list-style: none;
    height: 100%;
    align-content: center;
  }

  
  li{
    height: 100%;
    display: flex;
    align-items: center;
    padding: .5em;
    font-size: 14px;
    
    &:hover{
      border-bottom: 3px solid rgba(2,130,249,255);
      background-color: lightgray;
      cursor: pointer;
    }
  }
  
  nav{
    height: 100%;
    display: flex;
    align-items: center;
  }
}
</style>
