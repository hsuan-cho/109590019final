<template lang="pug">
.backimage
.Contact {{ Contact }}
.rec
.C {{ C }}
.address {{ address }}
.tel {{ tel }}
.mail {{ mail }}
</template>

<script>
export default {
  name: 'Four',
  data() {
    return {
      Contact: '聯絡資訊',
      C: '國立清華大學藝術學院學士班',
      address: '30014新竹市南大路521號（教學大樓3F）',
      tel: '+886-3-5715131 #78802 /',
      mail: 'ipta@my.nthu.edu.tw',
    }
  }
}
</script>

<style lang="sass">
.Contact
  position: absolute
  width: 200px
  height: 43px
  left: calc(50% - 1440px/2 + 635px)
  top: calc(50% - 1024px/2 + 290px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 36px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.C
  position: absolute
  width: 500px
  height: 43px
  left: calc(50% - 1440px/2 + 485px)
  top: calc(50% - 1024px/2 + 420px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 24px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.address
  position: absolute
  width: 500px
  height: 43px
  left: calc(50% - 1440px/2 + 485px)
  top: calc(50% - 1024px/2 + 490px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 24px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.tel
  position: absolute
  width: 500px
  height: 43px
  left: calc(50% - 1440px/2 + 485px)
  top: calc(50% - 1024px/2 + 560px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 24px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.mail
  position: absolute
  width: 500px
  height: 43px
  left: calc(50% - 1440px/2 + 485px)
  top: calc(50% - 1024px/2 + 630px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 24px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.rec
  position: absolute
  width: 530px
  height: 350px
  left: calc(50% - 500px/2 - 10px)
  top: calc(50% - 500px/2 + 100px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.backimage
  position: absolute
  width: 100vw
  height: 100vh
  background: url(../assets/4884841.jpg)
</style>
