<template lang="pug">
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
</template>

<script>
// @ is an alias to /src

export default {
	name: 'One',
	data() {
		return {
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
		}
	}
}
</script>

<style lang="sass">
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
</style>
