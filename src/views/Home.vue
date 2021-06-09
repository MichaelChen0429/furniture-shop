<template lang="pug">
.container--xxl.header
  .row.header__wrap
    .col-xxl-4.logo
      img.logo__photo(src='@/assets/Jevelin_logo.png')
    .col-xxl-4.justify-content-center.category
      a.category__noun Home
      a.category__noun Shop
      a.category__noun Decor
      a.category__noun Plant
      a.category__noun Light
      a.category__noun Chair
    .col-xxl-4.justify-content-end.action
        a
          i.bi.bi-facebook.action__button
        a
          i.bi.bi-twitter.action__button
        a
          i.bi.bi-instagram.action__button
        a
          i.bi.bi-search.action__button
        a
          i.bi.bi-cart.action__button
.container--xxl.content
  .row.banner
    .col-xxl-6.banner__title
      .info
        button.info__tag New collection
        .info__title Fill your home with uniqueness
        .info__subtitle Huge variety with modern glamour!
        .info__action
          .action__name Explore
          i.bi.bi-chevron-down.action__button(style="zoom: 1")
    img.col-xxl-6.align-self-start.banner__photo(src = "@/assets/banner.jpg")
  .row.note
    a.col.note__title    
      | &quot;! Use discount code: FIRSTIME to get&quot;
      span.highlight 10% off
      |     &quot;your first order !&quot;
.footer
</template>
<style lang="sass">
@media (max-width: 425px)
  .banner
    margin: 0
    padding: 0
@media (min-width: 768px)
  .banner
    margin: 0
    padding: 0 56px
.action__button
  position: relative
  margin-left: 16.8px
  zoom: 1.25

.header
  height: 130px
  display: flex
  justify-content: center
  .header__wrap
    display: flex
    align-items: center
    width: 90vw
    .logo
      .logo__photo
        height: 24px
    .category
      display: flex
      .category__noun
        padding: 0 16.8px
        font-size: 14px
        font-weight: 700
        color: rgb(0, 0, 0)
        text-decoration: none
    .action
      display: flex

.content
  .banner
    .banner__title
      background: rgb(246, 246, 246)
      padding: 0
      .info
        padding: 16vw 15px 0px 15px
        margin: 0px 26.75px
        .info__tag
          margin-bottom: 40px
          background-color: #171717
          border: none
          border-radius: 15px
          color: #ffffff
          height: 30px
          padding: 0 14px 0 14px
          line-height: 30px
          font-size: 12px
          font-weight: 800
        .info__title
          margin-bottom: 38px
          font-size: 4.16vw
          line-height: 5vw
          font-weight: 600
          color: rgb(15, 15, 15)
        .info__subtitle
          margin-bottom: 13.2vw
          font-size: 1.39vw
          font-weight: 600
          color: rgb(108, 108, 108)
        .info__action
          margin-bottom: 50px
          display: flex
          align-items: center
          .action__name
            font-size: 14px
            font-weight: 700
            color: rgb(0, 0, 0)
    .banner__photo
      padding: 0
      height: auto
  .note
    text-align: center
    .note__title
      margin: 0 4vw
      padding: 2.08vw 0
      border-bottom: solid 1px
      border-bottom-color: #efefef;
      font-size: 1.25vw
      font-weight: 600
      color: rgb(90, 90, 90)
      text-decoration: none
      .highlight
        color: rgb(255, 112, 18)
        margin: 0 4px


</style>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'Home',
  components: {
    HelloWorld,
  }
}
</script>
