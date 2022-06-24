<template>
  <div id="app">
    <h1 class="title">Hi Seymur !</h1>
    <label class="search__label" for="search">
        <button class="search__icon fa-solid fa-magnifying-glass"></button>
      <input class="search__input" type="text" name="search" id="search" placeholder="Search City">
    </label>

  </div>
</template>

<style lang="sass">
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,600;1,500&display=swap')

*
  box-sizing: border-box
  margin: 0
  padding: 0
  outline: none

html, body
  font-family: 'Noto Sans', sans-serif
  background-color: #22252a
  font-size: 10px
  font-weight: 400
  font-style: normal
  letter-spacing: .4px
  overflow-x: hidden
  position: relative

ul, li
  display: block
  list-style: none
  margin: 0
  padding: 0

h1, h2, h3, h4, h5, h6, p, address, span, label, input, button, table, caption
  margin: 0
  padding: 0

h1, h2, h3, h4, h5
  font-weight: 500
  font-style: normal

p
  line-height: 1.7

b, strong
  font-weight: bold

#app
  padding: 2em

.title
  font-size: 2.4rem
  font-weight: 600
  color: #fdfdfd
  margin-bottom: .8em

.search
  &__label
    position: relative
  &__input
    font-weight: 500
    width: 100%
    background-color: transparent
    border: 1px solid #2f3237
    border-radius: 5em
    padding: 1em 1.5em 1em 3.5em
    color: #7d8085
  &__icon
    color: #7d8085
    font-size: 2rem
    position: absolute
    left: .8em
    top: -.2em
    background-color: transparent
    border: none
</style>