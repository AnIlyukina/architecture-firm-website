<template>
  <header class="header">
    <img 
      src="../assets/images/header__logo.png"
      class="header__logo"
      />
      <div class="header__menu">
        <nav class="header__navigation">
          <ul class="header__navigation-links">
            <li><a class="header__navigation-link" href="#">Projects</a></li>
            <li><a class="header__navigation-link" href="#">About</a></li>
            <li><a class="header__navigation-link" href="#">News</a></li>
            <li><a class="header__navigation-link" href="#">Team</a></li>
            <li><a class="header__navigation-link" href="#">Contact</a></li>
          </ul>
        </nav>
        <button class="header__button">
          Get template
        </button>
      </div>
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
  align-items: center;
  justify-content: space-between;
  &__logo{
    max-width: 220px;
    margin-left: 12px;
    height: 19px;
  }
  &__menu{
    display: flex;
    align-items: center;
  }
  &__navigation-links{
    display:flex;
    margin: 0;
    padding: 0;
    list-style-type: none;
    font-size: 15px;
    line-height: 24px;
  }
  &__navigation-link{
    text-decoration: none;
    color: #1B1A1A;
    margin-right: 32px;
  }
  &__button{
    padding: 11px 20px;
    background-color: #1B1A1A;
    border: none;
    border-radius: 14px;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: white;
  }
}
</style>