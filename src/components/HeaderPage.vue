<template>
  <header class="header">
    <img 
      src="../assets/images/header__logo.png"
      class="header__logo"
      />
      <nav class="header__menu">
         <ul class="header__menu-links">
          <li class="header__menu-item"><a class="header__menu-link" href="#">Projects</a></li>
          <li><a class="header__menu-link" href="#">About</a></li>
          <li><a class="header__menu-link" href="#">News</a></li>
           <li><a class="header__menu-link" href="#">Team</a></li>
            <li><a class="header__menu-link" href="#">Contact</a></li>
        </ul>
      </nav>
  </header>
</template>

<script>

export default {
    name: 'HeaderPage'

}
</script>

<style lang="scss">
.header{
  padding: 22px 140px;
  display: flex;
  justify-content: space-between;
  &__logo{
    max-width: 220px;
    margin-left: 12px;
    height: 19px;
  }
  &__menu-links{
    display:flex;
    margin: 0;
    padding: 0;
    list-style-type: none;
    font-size: 15px;
    line-height: 24px;
  }
  &__menu-link{
    text-decoration: none;
    color: #1B1A1A;
    margin-right: 32px;
  }
}
</style>