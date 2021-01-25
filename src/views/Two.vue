<template lang="pug">
.desk2
	.intro {{ intro }}
	.up_grid
	.bottomgrid
	.intro_rec
	.IPTA_feature
	.core
	.NTHU {{ NTHU }}
	.p2 {{ p2 }}
	.p3 {{ p3 }}
	.p4 {{ p4 }}
	.p5 {{ p5 }}
	.p6 {{ p6 }}
	.p7 {{ p7 }}
	.P {{ P }}
	.PP {{ PP }}
	.PPP {{ PPP }}
	.PPPP {{ PPPP }}
</template>

<script>
// @ is an alias to /src

export default {
	name: 'Two',
	data() {
		return {
			intro: '學士班簡介',
			NTHU: '國立清華大學在2016年11月與國立新竹教育大學合校後，增設了以培養優秀美術設計與音樂人才為宗旨的「藝術學院」，前為「國立新竹教育大學 人文社會與藝術學院」。目前藝術學院設有藝術與設計學系（創作組、設計組、碩士班及在職專班）、音樂學系（學士班、碩士班及在職專班），專任教師25位（藝術與設計學系14位、音樂學系11位），院以培養優秀美術設計與音樂人才為宗旨，在多元的師資培育激盪下，培育出許多優秀的藝術家和設計新銳，並屢獲國內外大獎，展現出令人矚目的創作能量，受相關產業矚目與青睞。',
			p2: '除此，本學院106學年度成立藝術學院【〝科技藝術〞跨域學士班】， 由許素朱(小牛）院長率領藝術學院教師以及臺灣一群科技藝術特種部隊擔任教師與顧問指導，特別聘請陶亞倫老師擔任學士班班主任，希望培養一群臺灣科技藝術的尖兵。106學年度也會開始籌設【科技藝術研究所】，含新媒體藝術組、創新科技組等兩組。數位時代來臨，新形式的科技與藝術結合之創作如雨後春筍，清華大學的是國內科學與科技頂尖學府，這對藝術學院發展「科技藝術」具有得天獨厚的優勢。期望為清華創造新的「科技藝術跨域 DNA」、以及「科技藝術跨域的新文化」，讓清華成為臺灣藝術界的跨域先鋒！',
			P: '科技藝術，當代藝術的 newtype !',
			p3: '「科技藝術（TechArt）」是當代藝術的新形式創作也是國際藝術發展的重要趨勢，包含互動藝術、電腦動畫、電腦音樂與聲音藝術、數位表演、混合藝術、數位社群、創客藝術…等。在當代數位美學與數位藝術的基礎下，我們結合創新科技，如各種互動感測技術、虛擬/擴增/混合實境、物聯網、人工智慧、大數據分析…，把「科技藝術」結合視為「專業領域」在清華做跨域研究創作人才培育。在清華強大的科技研發環境下，科技與藝術充滿著難以預期的實驗性與挑戰性，期締造臺灣TechArt 2.0新契機與新氣象！',
			PP: '在共享學習、共享創意環境裡發揮創意美學！',
			p4: '我們師資群除來自清華校內藝術學院、電資學院、工學院、人文社會等跨域教師外，我們也將聘進一群來自美國、歐洲與日本跨國與跨域的教師。我們也聘請臺灣在科技藝術活躍且經驗豐富的知名業界團隊或藝術家（豪華朗機工、帝凱科技、何理互動設計…）加入我們的教師群。我們師資每個人本身都是跨領域背景，所開的每一門課也都是已跨域融合後的課。同學可在跨域多元指導與跨域共享學習環境裡，發揮自我與創意美學！',
			PPP: '培養車庫創客精神，發揮數位自造無限能力',
			p5: '同學進來需自己make自己的學習環境。自己動手做自己的創客桌子，自己動手make數位機具。在自己make的創客空間，用自己make的數位機具，繼續創造更多科技藝術碰撞的研究與創作。',
			PPPP: '數位藝術跨域轉繹，數位文創跨域激發！',
			p6: '我們結合智慧科技與創新藝術，讓科技謙和無形的融入數位藝術的創作，讓藝術展現當代的無限可能性；而在數位文創應用方面，期盼科技能讓生活空間充滿智慧與互動，隨時隨地提供資訊讓所有數據導入城市社會，讓整個社會形成一個大的智慧城市實驗室，並最終期盼促成創意人才育成及數位文創經濟之發展。',
			p7: '我們歡迎喜歡科技與藝術的夥伴，來報考清大藝術學院科技藝術跨域學士班，讓我們一起來締造清大「科技藝術跨域的新DNA」、以及「科技藝術跨域的新文化」！',
		}
	}
}
</script>

<style lang="sass">
.desk3
	position: relative
	width: 100vw
	height: 100vh
	top: calc(50% - 1024px/2 - 600px)
	background: #FFFFFF

.intro
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 200px)
	font-family: Merienda
	font-style: normal
	font-weight: bold
	font-size: 36px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #3c096c

.NTHU
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 300px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p2
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 530px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p3
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 860px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p4
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1130px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p5
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1380px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p6
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1570px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.p7
	position: absolute
	width: 1050px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1750px)
	font-family: Merienda
	font-style: normal
	font-weight: normal
	font-size: 20px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #000000

.P
	position: absolute
	width: 801px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 810px)
	font-family: Merienda
	font-style: normal
	font-weight: bold
	font-size: 24px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #7209b7

.PP
	position: absolute
	width: 801px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1080px)
	font-family: Merienda
	font-style: normal
	font-weight: bold
	font-size: 24px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #7209b7

.PPP
	position: absolute
	width: 801px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1335px)
	font-family: Merienda
	font-style: normal
	font-weight: bold
	font-size: 24px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #7209b7

.PPPP
	position: absolute
	width: 801px
	height: 480px
	left: calc(50% - 1440px/2 + 200px)
	top: calc(50% - 1024px/2 + 1520px)
	font-family: Merienda
	font-style: normal
	font-weight: bold
	font-size: 24px
	line-height: 156.69%

	/* or 31px
	text-align: justify
	letter-spacing: 0.28em
	color: #7209b7

.intro_rec
	position: absolute
	width: 1200px
	height: 1580px
	left: calc(50% - 1200px/2 + 0px)
	top: calc(50% - 674px/2 + 98px)
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
	top: calc(50% - 244px/2 - 325px)
	background: url(../assets/8331.jpg)

.bottom
	position: absolute
	width: 1440px
	height: 1024px
	bottom: 0px
	background: #FFFFFF
</style>
