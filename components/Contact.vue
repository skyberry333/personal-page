<template>
  <div :class="$style.contact">
    <p>Don't be shy, drop me a line!</p>
    <p>
      <a href="mailto:skyberry333@gmail.com">Email</a>
      <span>·</span>
      <a href="wechat.jpg" target="_blank">Wechat</a>
      <span>·</span>
      <a href="https://www.instagram.com/5.8ft/" target="_blank">Instagram</a>
    </p>
    <p><em>Site magic by <a href="https://github.com/skyberry333" target="_blank">@Nicholas</a></em></p>
  </div>
</template>

<style lang="stylus" module>
  @require '~assets/util'

  .contact
    text-small()
    span
      margin 0 1em
    +below(tablet)
      margin-top 24px
    +above(tablet)
      margin-top 48px
</style>
