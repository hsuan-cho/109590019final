<template lang="pug">
.backImage
.NTUH__art {{ NTUH__art }}
.schoolIcon
.NTUH__art2 {{ NTUH__art2 }}
.news {{ news }}
.contact {{ contact }}
.tecnoart {{ tecnoart }}
.clas {{ clas }}
.clas2 {{ clas2 }}
.come {{ come }}
.HOME {{ HOME }}
.spring_rec
.spring_money {{ spring_money }}
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },

  data() {
    return {
      spring_money: '“春之清華”獎學金，鼓勵藝術卓越學生”第一志願”選讀清華(5名)!',
      HOME: 'HOME',
      come: '招生',
      clas: '學士班特色',
      clas2: '學士班簡介',
      tecnoart: '科藝賞析',
      contact: '聯絡',
      news: '最新消息',
      NTUH_art: '國立清華大學藝術學院',
      NTUH__art: '國立清華大學',
      NTUH__art2: '藝術學院',
    }
  }
}
</script>

<style lang="sass">
.spring_money
  position: absolute
  width: 650px
  height: 29px
  left: calc(50% - 604px/2 - 315px)
  top: calc(50% - 29px/2 + 155.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 20px
  line-height: 142.69%

  /* identical to box height, or 29px
  letter-spacing: 0.06em
  color: #000000

.spring_rec
  position: absolute
  width: 635px
  height: 58px
  left: calc(50% - 635px/2 - 291.5px)
  top: calc(50% - 58px/2 + 153px)
  background: rgba(255, 255, 255, 0.7)
  border-radius: 8px

.line
  position: absolute
  width: 1189px
  height: 0px
  left: calc(50% - 1189px/2 + 45.5px)
  top: calc(50% - 0px/2 - 390px)
  border: 1px solid #FFFFFF

.HOME
  position: absolute
  width: 86px
  height: 43px
  left: calc(50% - 86px/2 + 625px)
  top: calc(50% - 43px/2 - 220px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.come
  position: absolute
  width: 80px
  height: 43px
  left: calc(50% - 50px/2 + 640px)
  top: calc(50% - 43px/2 - 130px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.clas
  position: absolute
  width: 200px
  height: 43px
  left: calc(50% - 75px/2 + 535px)
  top: calc(50% - 43px/2 - 40px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.clas2
  position: absolute
  width: 200px
  height: 43px
  left: calc(50% - 75px/2 + 535px)
  top: calc(50% - 43px/2 + 55px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.teacher
  position: absolute
  width: 80px
  height: 43px
  left: calc(50% - 59px/2 + 332.5px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.tecnoart
  position: absolute
  width: 170px
  height: 43px
  left: calc(50% - 103px/2 + 580px)
  top: calc(50% - 43px/2 + 230px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.contact
  position: absolute
  width: 80px
  height: 43px
  left: calc(50% - 59px/2 + 640px)
  top: calc(50% - 43px/2 + 315px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.news
  position: absolute
  width: 170px
  height: 43px
  left: calc(50% - 103px/2 + 580px)
  top: calc(50% - 43px/2 + 140px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.NTUH_art
  position: absolute
  width: 390px
  height: 43px
  left: calc(50% - 269px/2 + 450px)
  top: calc(50% - 43px/2 - 240px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.schoolIcon
  position: absolute
  width: 101px
  height: 100px
  left: calc(50% - 101px/2 - 670px)
  top: calc(50% - 100px/2 - 230px)
  background: url(../assets/cropped-NTHU-logo.png)

.NTUH__art
  position: absolute
  width: 692px
  height: 249px
  left: calc(50% - 692px/2 - 327px)
  top: calc(50% - 249px/2 + 7px)
  font-family: Cairo
  font-style: normal
  font-weight: 600
  font-size: 80px
  line-height: 142.69%

  /* or 114px
  letter-spacing: 0.17em
  color: #FFFFFF

.NTUH__art2
  position: absolute
  width: 692px
  height: 249px
  left: calc(50% - 692px/2 - 420px)
  top: calc(50% - 249px/2 + 115px)
  font-family: Cairo
  font-style: normal
  font-weight: 600
  font-size: 80px
  line-height: 142.69%

  /* or 114px
  letter-spacing: 0.17em
  color: #FFFFFF

.backImage
  position: absolute
  width: 100vw
  height: 100vh
  background: url(../assets/4884841.jpg)
</style>
