<template>
  <div class="header">
    <div class="header__logo">Inbranders</div>
    <div class="header__nav">
      <a href="/" class="header__nav__item">Home</a>
      <a href="/music" class="header__nav__item">Music</a>
      <a href="/events" class="header__nav__item">Events</a>
      <a href="/merch" class="header__nav__item">Merch</a>
      <a href="/contact" class="header__nav__item">Contact</a>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: $spacer * 2;
}

.header__logo {
  font-family: $font-logo;
  font-size: 3rem;
}

.header__nav {
  display: none;
}

.header__nav__item {
  +.header__nav__item {
    margin-left: 1rem;
  }
}
</style>
