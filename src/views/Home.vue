<template lang="pug">
.desk1
  .backImage
  .NTUH__art {{ NTUH__art }}
  .schoolIcon
  .NTUH_art {{ NTUH_art }}
  .NTUH__art2 {{ NTUH__art2 }}
  .news {{ news }}
  .contact {{ contact }}
  .tecnoart {{ tecnoart }}
  .teacher {{ teacher }}
  .clas {{ clas }}
  .come {{ come }}
  .HOME {{ HOME }}
  .line
  .spring_rec
  .spring_money {{ spring_money }}
  
.desk2
  .bottom
  .up_grid
  .bottomgrid
  .intro_rec
  .IPTA_feature
  .core
  .NTHUisNationalTop {{ NTHUisNationalTop }}
  .classgood {{ classgood }}
  .coreability {{ coreability }}
  .socialcare {{ socialcare }}
  .NTHU2018 {{ NTHU2018 }}
  .forFuture {{ forFuture }}
  .straightline
  .GOTOCircle
  .lecture {{ lecture }}
  .GOTO {{ GOTO }}

.desk3
  .backshining
  .backbig
  .schoolclassnews {{ schoolclassnews }}
  .rightright1Group
  .right1Group
  .leftleft1Group
  .middle1Group
  .left1Group
  .middle2Group
  .getprice_20200artgraybottom
  .getprice_2020spring_graybottom
  .getprice_first_white
  .firstNTUH__white
  .getprice_2020spring_ {{ getprice_2020spring_ }}
  .NTUH__white
  .NTUH_ {{ NTUH_ }}
  .annouce_spring_graybottom
  .annouce_spring_ {{ annouce_spring_ }}
  .firstNTUH_ {{ firstNTUH_ }}
  .getprice_first {{ getprice_first }}
  .getprice_2020IPTA_ {{ getprice_2020IPTA_ }}
  .leftup_rec
  .right_midgrayrec
  .right_up_rec
  .newsHere {{ newsHere }}

.desk4
  .backshining2
  .back
  .rightright2Group
  .right2Group
  .rightright3Group
  .leftleft2Group
  .left2Group
  .NTUH_IPTA_public_white
  .tec_objectAndimage_class_white
  .NTUH_IPTA_public {{ NTUH_IPTA_public }}
  .middle3Group
  .NTUH_art2 {{ NTUH_art2 }}
  .news2 {{ news2 }}
  .contact2 {{ contact2 }}
  .tecnoart2 {{ tecnoart2 }}
  .teacher2 {{ teacher2 }}
  .class2 {{ class2 }}
  .come2 {{ come2 }}
  .HOME2 {{ HOME2 }}
  .bottomline
  .bottomschoolicon
  .midleftgray
  .middowngrayrec
  .downleftyellowrec
  .middownleftgrayrec
  .middownredrec
  .midbottombluerec
  .greenrec
  .speech0528_white
  .class0526_white
  .classVRart_white
  .class0526 {{ class0526 }}
  .classVRart {{ classVRart }}
  .tec_object526 {{ tec_object526 }}
  .tec_object526_white
  .tec_objectAndimage_class {{ tec_objectAndimage_class }}
  .speech05 {{ speech05 }}
  .five {{ five }}
  .fb {{ fb }}
  .c2020 {{ c2020 }}
  .QuestionA {{ QuestionA }}
  .introduce {{ introduce }}
  .classes {{ classes }}
  .change {{ change }}
  .build {{ build }}
  .artte {{ artte }}
  .drawte {{ drawte }}
  .musicte {{ musicte }}
  .elete {{ elete }}
  .ath {{ ath }}
  .interact {{ interact }}
  .energy {{ energy }}
  .sound {{ sound }}
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
      clas: '學士班',
      teacher: '師資',
      tecnoart: '科藝賞析',
      contact: '聯絡',
      news: '最新消息',
      NTUH_art: '國立清華大學藝術學院',
      NTUH__art: '國立清華大學',
      NTUH__art2: '藝術學院',

      GOTO: 'GO TO',
      lecture: '學士班課程',
      forFuture: '因應未來產業的發展趨勢，創新科技與當代藝術結合之創作如雨後春筍。清華大學的是國內科學與科技的頂尖學府，對藝術學院發展「科技藝術」具有得天獨厚的優勢。本班師資除來自清華校內藝術學院、電資學院、工學院、生命科學院、人文社會等跨域教師外，我們也將聘進一群來自美國、歐洲與日本跨國與跨域的專業教師。也廣邀在臺灣在科技藝術創作領域最頂尖的業界團隊與藝術家加入我們的教學團隊，讓同學得到專業與多元的指導，並在共享學習、共享創意的環境裡，開創未來的產業，盡情發揮自己的潛能。',
      NTHU2018: '清華大學2018年成立藝術學院〝科技藝術〞跨域「學士班」。「科技藝術（TechArt）」是當代藝術的新形式創作也是國際藝術發展的重要趨勢，包含虛擬藝術、互動藝術、電腦動畫、電腦音樂、聲音藝術、科技性表演藝術、混合藝術、網路社群、創客藝術、仿生藝術、生物藝術、人工生命…等。在當代數位美學與數位藝術的基礎下，我們結合創新科技，如各種互動感測技術、虛擬實境、物聯網、人工智慧、大數據分析、基因工程…，把「科技」與「藝術」結合視為「未來文化學」，培養前瞻性、跨域研究與創作人才。',
      socialcare: '社會關懷與品格實踐能力\
        美感認知與經典欣賞能力\
        自然感知與創新發想能力\
        邏輯思辨與語文溝通能力\
        國際觀點與在地行動能力\
        資訊掌握與科技應用能力',
      coreability: '核心能力',
      classgood: '學士班特色',
      NTHUisNationalTop: '清華是國際頂尖科技大學，加上合校後的藝術學院，具備發展「科技藝術」的卓越條件。我們號召臺灣年輕一代的科技藝術學者專家，我們規劃有科技藝術跨域特別課程，並與業界合作推出創意跨域專題。你，不需猶豫，歡迎你的加入！',

      schoolclassnews: '院學士班最新消息',
      newsHere: '新消息，看這裡！',
      getprice_2020IPTA_: '【獲獎】2020藝術學院學士班春之清華獎學金\
        獲獎名單\
        109學年度藝術學院學士班【春之清華獎學金】\
        獲獎…\
        Read more',
      getprice_first: '【獲獎】《那顆Ｇ1咻！》國立清華大學\
        藝術學院學士班 第一屆系展 得獎名單\
        國立清華大學藝術學院學士班第一屆系展\
        獲獎名單…\
        Read more',
      firstNTUH_: '《那顆Ｇ1咻！》國立清華大學藝術學院學士班\
        第一屆系展\
        《那顆Ｇ1咻！》國立清華大學藝術學院學士班\
        第一屆系展 「當…\
        Read more',
      annouce_spring_: '【徵件公告】春之清華—藝術卓越獎科技藝術類\
        甄選辦法\
        春之清華 – 藝術卓越獎 科技藝術類 甄選辦…\
        Read more',
      NTUH_: '國立清華大學 藝術學院學士班\
        徵聘【助理教授級以上】專任教師1名\
        一、職稱：助理教授（含）以上教師 \
        二、聘任條件： 1.具國內…\
        Read more',
      getprice_2020spring_: '【獲獎】2020春之清華 – 藝術卓越獎\
        科技藝術類 得獎名單\
        2020春之清華 – 藝術卓越獎 科技藝術類…\
        Read more',
      speech05: '【演講】05/28 從腦科學看藝術 (Art and the\
        Brain: A Glimpse of Neuroaesthetics)\
        講題：從腦科學看藝術 Art and the Brain: …\
        Read more',
      tec_objectAndimage_class: '《 科技物件與人類幻象講座VII&VII》\
        5/26 & 6/2 Tue\
        《科技物件與人類幻象》講座與工作坊\
        第七&八場 …\
        Read more',
      tec_object526: '《 科技物件與人類幻象講座 Ⅸ》6/16 Tue\
        《科技物件與人類幻象》講座   第九場\
        時間2020/…\
        Read more',
      classVRart: '【講座】虛擬藝術美學思維與創作實踐\
        【虛擬藝術美學思維與創作實踐 講座】 時…\
        Read more',
      class0526: '【講座】05/26 當代劇場展演實務\
        華山藝文林璞總監\
        當代劇場展演實務 講座\
        時間：5月26日 (二) 9:00—…\
        Read more',
      HOME2: 'HOME',
      come2: '招生',
      class2: '學士班',
      teacher2: '師資',
      tecnoart2: '科藝賞析',
      contact2: '聯絡',
      news2: '最新消息',
      NTUH_art2: '國立清華大學藝術學院',
      NTUH_IPTA_public: '國立清華大學藝術學院學士班公開徵求\
        班主任候選人啓事\
        國立清華大學藝術學院學士班公開徵求\
        班主任候選人啓事 一、依據…\
        Read more',
      five: '“春之清華”卓越獎學金(5名)',
      fb: '學士班FB粉絲頁(new)',
      c2020: '2020招生',
      QuestionA: '招生Q&A',
      introduce: '學士班簡介',
      classes: '學士班課程',
      change: '國際交換',
      build: '藝術學院大樓(new)',
      artte: '學士班師資',
      drawte: '藝設系師資',
      musicte: '音樂系師資',
      elete: '電資學院師資',
      ath: '數位文創作品',
      interact: '互動藝術作品',
      energy: '動力藝術作品',
      sound: '聲音藝術作品',
    }
  }
}
</script>

<style lang="sass">
.desk1
  position: relative
  width: 1440px
  height: 1024px
  left: calc(50% - 1440px/2)
  top: calc(50% - 1024px/2 - 1536px)
  background: #FFFFFF

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
  left: calc(50% - 86px/2 - 235px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.come
  position: absolute
  width: 50px
  height: 43px
  left: calc(50% - 50px/2 + 65px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.clas
  position: absolute
  width: 75px
  height: 43px
  left: calc(50% - 75px/2 + 195.5px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.teacher
  position: absolute
  width: 59px
  height: 43px
  left: calc(50% - 59px/2 + 332.5px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.tecnoart
  position: absolute
  width: 103px
  height: 43px
  left: calc(50% - 103px/2 + 479.5px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.contact
  position: absolute
  width: 59px
  height: 43px
  left: calc(50% - 59px/2 + 622px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.news
  position: absolute
  width: 103px
  height: 43px
  left: calc(50% - 103px/2 - 78px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.NTUH_art
  position: absolute
  width: 269px
  height: 43px
  left: calc(50% - 269px/2 - 450px)
  top: calc(50% - 43px/2 - 406.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #FFFFFF

.schoolIcon
  position: absolute
  width: 101px
  height: 100px
  left: calc(50% - 101px/2 - 623.5px)
  top: calc(50% - 100px/2 - 419px)
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
  width: 1440px
  height: 1024px
  left: 0px
  top: 0px
  background: url(../assets/pexels-fotografierende-1213447.jpg)

.desk2
  position: relative
  width: 1440px
  height: 1024px
  left: calc(50% - 1440px/2)
  top: calc(50% - 1024px/2 - 512px)
  background: #FFFFFF

.GOTO
  position: absolute
  width: 162px
  height: 60px
  left: calc(50% - 164px/2 - 524px)
  top: calc(50% - 82px/2 + 374px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 24px
  line-height: 161.19%

  /* or 39px
  text-align: center
  letter-spacing: 0.35em
  color: #FFFFFF

.lecture
  position: absolute
  width: 162px
  height: 60px
  left: calc(50% - 164px/2 - 525px)
  top: calc(50% - 82px/2 + 420px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 24px
  line-height: 161.19%

  /* or 39px
  text-align: center
  letter-spacing: 0.35em
  color: #FFFFFF

.GOTOCircle
  position: absolute
  width: 167px
  height: 167px
  left: calc(50% - 167px/2 - 530.5px)
  top: calc(50% - 167px/2 + 378.5px)
  background: #000000
  border-radius: 100%

.straightline
  position: absolute
  width: 0px
  height: 541px
  left: calc(50% - 0px/2 + 218px)
  top: calc(50% - 541px/2 + 110.5px)
  border: 1px solid #000000

.forFuture
  position: absolute
  width: 330px
  height: 744px
  left: calc(50% - 330px/2 + 445px)
  top: calc(50% - 744px/2 + 210px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 170.7%

  /* or 31px
  text-align: justify
  letter-spacing: 0.35em
  color: #000000

.NTHU2018
  position: absolute
  width: 376px
  height: 527px
  left: calc(50% - 376px/2 - 25px)
  top: calc(50% - 527px/2 + 160px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 170.69%

  /* or 31px
  text-align: justify
  letter-spacing: 0.35em
  color: #000000

.socialcare
  position: absolute
  width: 310px
  height: 327px
  left: calc(50% - 352px/2 - 441px)
  top: calc(50% - 327px/2 + 144.5px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 22px
  line-height: 219.19%

  /* or 48px
  text-align: justify
  letter-spacing: 0.28em
  color: #000000

.coreability
  position: absolute
  width: 180px
  height: 65px
  left: calc(50% - 236px/2 - 499px)
  top: calc(50% - 65px/2 - 48.5px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 32px
  line-height: 142.69%

  /* or 46px
  letter-spacing: 0.35em
  color: #000000

.classgood
  position: absolute
  width: 220px
  height: 58px
  left: calc(50% - 279px/2 - 483.5px)
  top: calc(50% - 58px/2 - 380px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 32px
  line-height: 142.69%

  /* or 46px
  letter-spacing: 0.35em
  color: #000000

.NTHUisNationalTop
  position: absolute
  width: 801px
  height: 480px
  left: calc(50% - 801px/2 - 222.5px)
  top: calc(50% - 480px/2 - 110px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 20px
  line-height: 156.69%

  /* or 31px
  text-align: justify
  letter-spacing: 0.28em
  color: #000000

.coreabilityrec
  position: absolute
  width: 393px
  height: 436px
  left: calc(50% - 393px/2 - 461.5px)
  top: calc(50% - 436px/2 + 98px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.classgoodrec
  position: absolute
  width: 871px
  height: 266px
  left: calc(50% - 871px/2 - 222.5px)
  top: calc(50% - 266px/2 - 316px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.intro_rec
  position: absolute
  width: 949px
  height: 674px
  left: calc(50% - 949px/2 + 182.5px)
  top: calc(50% - 674px/2 + 98px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.IPTA_feature
  position: absolute
  width: 871px
  height: 266px
  left: calc(50% - 871px/2 - 222.5px)
  top: calc(50% - 266px/2 - 316px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.core
  position: absolute
  width: 393px
  height: 436px
  left: calc(50% - 393px/2 - 461.5px)
  top: calc(50% - 436px/2 + 98px)
  background: #FFFFFF
  border: 3px solid #000000
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
  border-radius: 19px

.bottomgrid
  position: absolute
  width: 916px
  height: 196px
  left: calc(50% - 916px/2 - 268px)
  top: calc(50% - 196px/2 + 414px)
  background: url(../assets/19273.jpg)

.up_grid
  position: absolute
  width: 685px
  height: 244px
  left: calc(50% - 685px/2 + 377.5px)
  top: calc(50% - 244px/2 - 390px)
  background: url(../assets/8331.jpg)

.bottom
  position: absolute
  width: 1440px
  height: 1024px
  left: calc(50% - 1440px/2)
  top: calc(50% - 1024px/2)
  background: #FFFFFF

.desk3
  position: relative
  width: 1440px
  height: 1023px
  left: calc(50% - 1440px/2)
  top: calc(50% - 1023px/2 + 511.5px)
  background: #FFFFFF

.newsHere
  position: absolute
  width: 300px
  height: 33px
  left: calc(50% - 176px/2 - 603px)
  top: calc(50% - 33px/2 - 355px)
  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 26px
  line-height: 142.69%

  /* or 29px
  letter-spacing: 0.06em
  color: #000000

.right_up_rec
  position: absolute
  width: 209.52px
  height: 209.52px
  left: calc(50% - 209.52px/2 + 490px)
  top: calc(50% - 209.52px/2 - 175px)
  background: #CCB88F
  transform: rotate(-45deg)

.right_midgrayrec
  position: absolute
  width: 143.65px
  height: 143.65px
  left: calc(50% - 143.65px/2 + 245px)
  top: calc(50% - 143.65px/2 + 360px)
  background: #A8A5A5
  transform: rotate(-45deg)

.leftup_rec
  position: absolute
  width: 156px
  height: 156px
  left: calc(50% - 156px/2 - 470px)
  top: calc(50% - 156px/2 - 200px)
  background: #C4C4C4
  transform: rotate(-45deg)

.getprice_2020IPTA_
  position: absolute
  width: 375px
  height: 120px
  left: calc(50% - 448px/2 - 215.5px)
  top: calc(50% - 114px/2 + 12px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #FFFFFF

.getprice_first
  position: absolute
  width: 331px
  height: 103px
  left: calc(50% - 331px/2 - 5px)
  top: calc(50% - 103px/2 - 247px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.firstNTUH_
  position: absolute
  width: 380px
  height: 93px
  left: calc(50% - 380px/2 - 4px)
  top: calc(50% - 93px/2 + 245px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.annouce_spring_
  position: absolute
  width: 381px
  height: 88px
  left: calc(50% - 381px/2 - 500px)
  top: calc(50% - 88px/2 + 242.5px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #FFFFFF

.annouce_spring_graybottom
  position: absolute
  width: 375px
  height: 82px
  left: calc(50% - 375px/2 - 498.5px)
  top: calc(50% - 82px/2 + 227px)
  background: rgba(95, 95, 95, 0.6)

.NTUH_
  position: absolute
  width: 315px
  height: 88px
  left: calc(50% - 315px/2 + 493px)
  top: calc(50% - 88px/2 + 231px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.NTUH__white
  position: absolute
  width: 375px
  height: 103px
  left: calc(50% - 375px/2 + 495px)
  top: calc(50% - 103px/2 + 225px)
  background: rgba(255, 255, 255, 0.3)

.getprice_2020spring_
  position: absolute
  width: 370px
  height: 70px
  left: calc(50% - 378.04px/2 + 240px)
  top: calc(50% - 88.46px/2)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #FFFFFF

.firstNTUH__white
  position: absolute
  width: 383px
  height: 80px
  left: calc(50% - 383px/2 - 15px)
  top: calc(50% - 103px/2 + 237px)
  background: rgba(255, 255, 255, 0.6)

.getprice_first_white
  position: absolute
  width: 338px
  height: 103px
  left: calc(50% - 338px/2 - 6px)
  top: calc(50% - 103px/2 - 262px)
  background: rgba(255, 255, 255, 0.6)

.getprice_2020spring_graybottom
  position: absolute
  width: 375px
  height: 90px
  left: calc(50% - 375px/2 + 236.5px)
  top: calc(50% - 95px/2 - 15px)
  background: rgba(95, 95, 95, 0.6)

.getprice_20200artgraybottom
  position: absolute
  width: 375px
  height: 90px
  left: calc(50% - 375px/2 - 255px)
  top: calc(50% - 104px/2 - 10px)
  background: rgba(95, 95, 95, 0.5)

.middle2Group
  position: absolute
  width: 342px
  height: 342px
  left: 542.5px
  top: 565px
  background: url(../assets/banner.png)
  transform: rotate(-45deg)
  opacity: 0.9

.left1Group
  position: absolute
  width: 342px
  height: 342px
  left: 293px
  top: 320px
  background: url(../assets/board-2303325_1920.jpg)
  transform: rotate(45deg)
  opacity: 0.8

.middle1Group
  position: absolute
  width: 342px
  height: 342px
  left: 541px
  top: 75px
  background: url(../assets/banner.png)
  transform: rotate(-45deg)

.leftleft1Group
  position: absolute
  width: 342px
  height: 342px
  left: 45px
  top: 565px
  background: url(../assets/light2-01-768x340.jpg)
  transform: rotate(-45deg)
  opacity: 0.9

.right1Group
  position: absolute
  width: 342px
  height: 342px
  left: 793px
  top: 320px
  background: url(../assets/light2-01-768x340.jpg)
  transform: rotate(-45deg)
  opacity: 0.9

.rightright1Group
  position: absolute
  width: 342px
  height: 342px
  left: 1040px
  top: 565px
  background: url(../assets/NEWS.jpg)
  transform: rotate(-45deg)

.schoolclassnews
  position: absolute
  width: 510px
  height: 60px
  left: calc(50% - 510px/2 - 420px)
  top: calc(50% - 60px/2 - 420px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 45px
  line-height: 142.69%

  /* or 68px
  text-align: center
  letter-spacing: 0.295em
  color: #000000

.backbig
  position: absolute
  width: 1402px
  height: 1008px
  left: calc(50% - 1402px/2 - 5px)
  top: calc(50% - 1008px/2 + 3px)
  background: #ECECEC

.backshining
  position: absolute
  width: 1440px
  height: 1024px
  left: calc(50% - 1921px/2 + 235px)
  top: calc(50% - 1081px/2 + 11px)
  background: url(../assets/pexels-pixabay-220067.jpg)

.desk4
  position: relative
  width: 1440px
  height: 1460px
  left: calc(50% - 1440px/2)
  top: calc(50% - 1460px/2 + 1534.5px)
  background: #FFFFFF

.speech05
  position: absolute
  width: 393px
  height: 90px
  left: calc(50% - 393px/2 - 5px)
  top: calc(50% - 90px/2 - 516px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.tec_objectAndimage_class
  position: absolute
  width: 365px
  height: 99px
  left: calc(50% - 365px/2 + 250px)
  top: calc(50% - 99px/2 - 255px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.tec_object526_white
  position: absolute
  width: 360px
  height: 101px
  left: calc(50% - 330px/2 + 230px)
  top: calc(50% - 101px/2 - 275px)
  background: rgba(255, 255, 255, 0.6)

.tec_object526
  position: absolute
  width: 375px
  height: 64px
  left: calc(50% - 375px/2 - 505px)
  top: calc(50% - 64px/2 - 515px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.classVRart
  position: absolute
  width: 362px
  height: 61px
  left: calc(50% - 362px/2 - 253px)
  top: calc(50% - 61px/2 - 275px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #FFFFFF

.class0526
  position: absolute
  width: 296px
  height: 98px
  left: calc(50% - 296px/2 + 491px)
  top: calc(50% - 98px/2 - 509px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #FFFFFF

.classVRart_white
  position: absolute
  width: 353px
  height: 72px
  left: calc(50% - 353px/2 - 250px)
  top: calc(50% - 72px/2 - 275px)
  background: rgba(255, 255, 255, 0.2)

.class0526_white
  position: absolute
  width: 300px
  height: 117px
  left: calc(50% - 300px/2 + 490px)
  top: calc(50% - 117px/2 - 520px)
  background: rgba(255, 255, 255, 0.2)

.speech0528_white
  position: absolute
  width: 397px
  height: 84px
  left: calc(50% - 397px/2 - 5px)
  top: calc(50% - 84px/2 - 523px)
  background: rgba(255, 255, 255, 0.6)

.midbottombluerec
  position: absolute
  width: 73.63px
  height: 73.63px
  left: calc(50% - 73.63px/2 - 5px)
  top: calc(50% - 73.63px/2 + 90px)
  background: #5CA7CC
  transform: rotate(-45deg)

.middownredrec
  position: absolute
  width: 52.69px
  height: 52.69px
  left: calc(50% - 52.69px/2 + 150px)
  top: calc(50% - 52.69px/2 - 75px)
  background: #E76A6A
  transform: rotate(-45deg)

.greenrec
  position: absolute
  width: 170px
  height: 170px
  left: calc(50% - 170px/2 - 400px)
  top: calc(50% - 170px/2 + 135px)

  background: #6DF390
  transform: rotate(-45deg)

.middownleftgrayrec
  position: absolute
  width: 74.26px
  height: 74.26px
  left: calc(50% - 74.26px/2 - 320px)
  top: calc(50% - 74.26px/2 - 20px)
  background: rgba(168, 165, 165, 0.4)
  transform: rotate(-45deg)

.downleftyellowrec
  position: absolute
  width: 161.21px
  height: 161.21px
  left: calc(50% - 161.21px/2 - 510px)
  top: calc(50% - 161.21px/2 - 150px)
  background: #FFF9B9
  transform: rotate(-45deg)

.middowngrayrec
  position: absolute
  width: 215.02px
  height: 215.02px
  left: calc(50% - 215.02px/2 - 5px)
  top: calc(50% - 215.02px/2 - 120px)
  background: #A8A5A5
  transform: rotate(-45deg)

.midleftgray
  position: absolute
  width: 157.63px
  height: 157.63px
  left: calc(50% - 157.63px/2 - 258px)
  top: calc(50% - 157.63px/2 - 660px)
  background: #D9D6D6
  transform: rotate(-45deg)

.bottomschoolicon
  position: absolute
  width: 101px
  height: 100px
  left: calc(50% - 101px/2 + 615px)
  top: calc(50% - 100px/2 + 420px)
  background: url(../assets/cropped-NTHU-logo.png)

.bottomline
  position: absolute
  width: 1189px
  height: 0px
  left: calc(50% - 1189px/2 - 78.5px)
  top: calc(50% - 0px/2 + 267.5px)
  border: 1px solid #000000

.HOME2
  position: absolute
  width: 86px
  height: 43px
  left: calc(50% - 86px/2 - 622px)
  top: calc(50% - 43px/2 + 373px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.come2
  position: absolute
  width: 50px
  height: 43px
  left: calc(50% - 50px/2 - 360px)
  top: calc(50% - 43px/2 + 327px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.class2
  position: absolute
  width: 75px
  height: 43px
  left: calc(50% - 75px/2 - 40px)
  top: calc(50% - 43px/2 + 325px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.teacher2
  position: absolute
  width: 59px
  height: 43px
  left: calc(50% - 59px/2 + 200px)
  top: calc(50% - 43px/2 + 325px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.tecnoart2
  position: absolute
  width: 103px
  height: 43px
  left: calc(50% - 103px/2 + 420px)
  top: calc(50% - 43px/2 + 326px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.contact2
  position: absolute
  width: 59px
  height: 43px
  left: calc(50% - 59px/2 - 636px)
  top: calc(50% - 43px/2 + 465px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.news2
  position: absolute
  width: 103px
  height: 43px
  left: calc(50% - 103px/2 - 617px)
  top: calc(50% - 43px/2 + 422px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.NTUH_art2
  position: absolute
  width: 269px
  height: 43px
  left: calc(50% - 269px/2 - 560px)
  top: calc(50% - 43px/2 + 325px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 18px
  line-height: 142.69%

  /* or 26px
  letter-spacing: 0.06em
  color: #000000

.middle3Group
  position: absolute
  width: 342px
  height: 342px
  left: 542.5px
  top: 36px
  background: url(../assets/200528.jpg)
  transform: rotate(-45deg)

.NTUH_IPTA_public
  position: absolute
  width: 322px
  height: 93px
  left: calc(50% - 322px/2 + 497px)
  top: calc(50% - 93px/2 - 17px)
  font-family: Merienda
  font-style: normal
  font-weight: bold
  font-size: 14px
  line-height: 142.69%

  /* or 20px
  letter-spacing: 0.295em
  color: #000000

.tec_objectAndimage_class_white
  position: absolute
  width: 375px
  height: 84px
  left: calc(50% - 375px/2 - 502.5px)
  top: calc(50% - 84px/2 - 520px)
  background: rgba(255, 255, 255, 0.6)

.NTUH_IPTA_public_white
  position: absolute
  width: 336px
  height: 101px
  left: calc(50% - 336px/2 + 490px)
  top: calc(50% - 101px/2 - 30px)
  background: rgba(255, 255, 255, 0.6)

.left2Group
  position: absolute
  width: 342px
  height: 342px
  left: 295px
  top: 284.5px
  background: url(../assets/5e7987.jpg)
  transform: rotate(-45deg)

.leftleft2Group
  position: absolute
  width: 342px
  height: 342px
  left: 45px
  top: 39px
  background: url(../assets/tfho.jpg)
  transform: rotate(-45deg)
  opacity: 0.9

.rightright3Group
  position: absolute
  width: 342px
  height: 342px
  left: 1040px
  top: 530px
  transform: rotate(-45deg)
  background: url(../assets/NEWS.jpg)

.right2Group
  position: absolute
  width: 342px
  height: 342px
  left: 790px
  top: 284.5px
  background: url(../assets/tfho.jpg)
  transform: rotate(-45deg)
  opacity: 0.9

.rightright2Group
  position: absolute
  width: 342px
  height: 342px
  left: 1040px
  top: 39px
  background: url(../assets/5e7987.jpg)
  transform: rotate(-45deg)

.five
  position: absolute
  width: 239px
  height: 28px
  left: calc(50% - 239px/2 - 259px)
  top: calc(50% - 28px/2 + 355px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.fb
  position: absolute
  width: 198px
  height: 28px
  left: calc(50% - 198px/2 - 282px)
  top: calc(50% - 28px/2 + 389px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.c2020
  position: absolute
  width: 93px
  height: 28px
  left: calc(50% - 93px/2 - 334.5px)
  top: calc(50% - 28px/2 + 425px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.QuestionA
  position: absolute
  width: 93px
  height: 28px
  left: calc(50% - 93px/2 - 334.5px)
  top: calc(50% - 28px/2 + 458px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.introduce
  position: absolute
  width: 105px
  height: 28px
  left: calc(50% - 105px/2 - 21px)
  top: calc(50% - 28px/2 + 355px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.classes
  position: absolute
  width: 105px
  height: 34px
  left: calc(50% - 105px/2 - 21px)
  top: calc(50% - 34px/2 + 393px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.change
  position: absolute
  width: 105px
  height: 28px
  left: calc(50% - 105px/2 - 31px)
  top: calc(50% - 28px/2 + 425px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.build
  position: absolute
  width: 174px
  height: 28px
  left: calc(50% - 174px/2 + 12px)
  top: calc(50% - 28px/2 + 459px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.artte
  position: absolute
  width: 105px
  height: 28px
  left: calc(50% - 105px/2 + 228px)
  top: calc(50% - 28px/2 + 355px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.drawte
  position: absolute
  width: 105px
  height: 28px
  left: calc(50% - 105px/2 + 228px)
  top: calc(50% - 28px/2 + 390px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.musicte
  position: absolute
  width: 105px
  height: 28px
  left: calc(50% - 105px/2 + 228px)
  top: calc(50% - 28px/2 + 425px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.elete
  position: absolute
  width: 118px
  height: 28px
  left: calc(50% - 118px/2 + 238px)
  top: calc(50% - 28px/2 + 459px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.ath
  position: absolute
  width: 121px
  height: 35px
  left: calc(50% - 121px/2 + 439.5px)
  top: calc(50% - 35px/2 + 359px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.interact
  position: absolute
  width: 121px
  height: 35px
  left: calc(50% - 121px/2 + 439.5px)
  top: calc(50% - 35px/2 + 393px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.energy
  position: absolute
  width: 130px
  height: 26px
  left: calc(50% - 114px/2 + 432px)
  top: calc(50% - 26px/2 + 423px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* identical to box height, or 26px */
  letter-spacing: 0.06em
  color: #000000

.sound
  position: absolute
  width: 121px
  height: 35px
  left: calc(50% - 121px/2 + 440px)
  top: calc(50% - 35px/2 + 463px)

  font-family: Merienda
  font-style: normal
  font-weight: normal
  font-size: 18px
  line-height: 142.69%
  /* or 26px */
  letter-spacing: 0.06em
  color: #000000

.back
  position: absolute
  width: 1402px
  height: 1280px
  left: calc(50% - 1402px/2 - 5px)
  top: calc(50% - 1190px/2 - 175px)
  background: #ECECEC

.backshining2
  position: absolute
  width: 1440px
  height: 1300px
  left: calc(50% - 1902px/2 + 226px)
  top: calc(50% - 1200px/2 - 170px)
  background: url(../assets/pexels-pixabay-220067.jpg)

.frame
  position: relative
  width: 1440px
  height: 4200px
  background: #FFFFFF
  opacity: 0
</style>
