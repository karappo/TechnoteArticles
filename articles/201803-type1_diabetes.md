# T1D（１型糖尿病）を取り巻くテック業界の今

<!-- MarkdownTOC -->

- 1型糖尿病\(T1D\)とは
- ペン型注射器
- FreeStyle Libre
	- iOSのHealth.appとの連携方法
	- 良かったところ
	- イマイチなところ
- CGM\(Continuous Glucose Monitoring\)
- SAP\(Sensor-Augmented Insulin Pumps\)
- 事例紹介
	- Dexcom G5
	- Tidepool
	- NightScout
	- Bigfoot Biomedical
		- Data Driven Disease
		- Bryan Mazlish
	- その他のアプリ
- 今後
	- 人口膵臓
	- YouTuber

<!-- /MarkdownTOC -->


## 1型糖尿病(T1D)とは

私は、2001年12月に1型糖尿病（T1D-Type1 Diabetes）を発症しました。T1Dの発症率は、10万人に1人（0.001%）とかなり珍しい病気です。因みに世間的に「糖尿病」というと、大抵生活習慣病の1種である「2型糖尿病」のことを指しています。名前は似ていますが、成り立ちからして全く別の病気なので、頭を切り替えて混同しないようにして下さい。

T1Dとは、遺伝や生活習慣とは関係なく突発的に誰にでも起こりうる膵臓疾患で、インスリン（Insulin）を体内で分泌できなくなる病気です。インスリンは、血液中の糖分（Glucose）をエネルギーに変える働きをしている大事なホルモンです。これが足りないと血糖値はどんどん上昇し、エネルギー供給もされなくなるので、様々な弊害が起こります。そのため、T1D患者は血糖値の高くなる毎食後、必要量のインスリンを自己注射によって補っています。また、食後たけでなく持続型と呼ばれる基礎分泌分を補う目的のもう1種類を1日1回別途注射することも多いです。私の場合も、基礎分泌量もほとんどないので、1日4回の自己注射が生命維持に不可欠な状況です。また、今のところ一度発症すると治りません。発症を知らされた当時、正直に言って絶望しました。毎日数時間おきに指を穿刺して血糖値を測定・記録し、測定値や状況に応じてインスリンの投与量を自分で判断し、自己注射しなくてはならないのです。数週間数ヶ月の話ではありません。一生その鎖に常につながれているのです、想像してみて下さい。

とはいえ、もっと重篤な病気のことを思えばかなり恵まれています。血糖値のコントロールさえきちんとできれば、健常者と同じように生活できるのですから。また、医療技術の発達によって少しづつ患者の負担は軽減されています。血糖測定器と注射器がメインのプロダクトですが、ここ数年でデジタル技術を使った便利なプロダクトも増えてきました。この記事では、そのあたりの話を紹介していきたいと思います。

また常に持ち歩くものなので、デザインも重要です。正直、昔はかっこ悪いものばかりで、ひと目に晒したくないという気持ちになり、患者の気持ちを後ろ向きにさせていました。最近は、その辺も段々ましになってきました。まだ、自慢できるようなものではないですが、少なくとも恥ずかしいレベルではなくなったのではないかと思います。

## ペン型注射器

例えば、昔はよく病院で使われているような注射器で針も使い捨てではなかったので、熱消毒の必要もありましたが、今は「ペン型」と呼ばれる携帯性の高いタイプの機材があり、針も使い捨てで消毒は不要です。


[Novo Pen Echo](https://www.novonordisk.com/patients/diabetes-care/pens--needles-and-injection-support/NovoPenEcho.html)


## FreeStyle Libre

この記事を書いている現在は、2018年3月です。2ヶ月前の2018年1月から、アメリカの[Abbot社](http://www.abbott.com/)の[FreeStyle Libre](https://www.freestylelibre.us/)を処方してもらえるようになりました。この機械は、500円玉サイズのセンサー（メモリー）を体に取り付けることで、常時血糖値をモニタリングすることができる機械です。



### iOSのHealth.appとの連携方法

- [ ] Health Kit？

### 良かったところ

### イマイチなところ

## CGM(Continuous Glucose Monitoring)

【他の機材の紹介。インスリンポンプについても触れる？】
10年前くらいから普及してきている？
https://www.youtube.com/watch?v=gj0mQ0x4PDY 9:15

※　LibreはFlash Glucose Monitorで、Continuousではない。

## SAP(Sensor-Augmented Insulin Pumps)

コミュニティに入ってから、CGMの次に頻繁に見かける様になった単語で、SAPと言うものがあります。・・・

## 事例紹介

### Dexcom G5

https://www.dexcom.com/g5-mobile-cgm
https://www.youtube.com/watch?v=4JjsOL81wdA

- 直接BluetoothでiPhoneにデータ転送される
- 高血糖低血糖アラート
- Health.appにももちろん対応
- データをリアルタイムに共有できるFollower機能

### Tidepool

FBグループで教えてもらいました。

### NightScout

Libre + iOSでは使えない。

- [ ] Androidでとりあえず体験してみる

### Bigfoot Biomedical



#### Data Driven Disease

“Data Driven Disease”この言葉は、後で触れるBigfoot社のCEO Jeffrey Brewer氏が下に貼り付けたプレゼンの中で使っていた言葉です。僕は、この言葉が非常に印象に残りました。

https://www.youtube.com/watch?v=uh_QmjkMQd8

- [ ] 色んな人が言ってるみたいだけどどうしよう
	https://medcitynews.com/2017/01/glooko-novo-nordisk-digital-diabetes/?utm_source=hs_email&utm_medium=email&utm_content=40272698&_hsenc=p2ANqtz--UEtSx0SxjYDdEc3-QT3widYfjJh58FoWDf-5WqI6-9YeKW7_COQfxJNR51af8mrAslGg5OxDLsmeNVGforuzBiYmU1g&_hsmi=40272698

#### Bryan Mazlish

Bigfoot Co-founder
家族のためにインスリンポンプをHACKして人口膵臓を自力で作った。（世界初の外来人口膵臓？）
- [ ] この辺の話をちゃんと調べてまとめる
- [ ] 夫々のプロフィールに目を通す
	https://www.bigfootbiomedical.com/leadership/

### その他のアプリ

https://spike-app.com/
元xDrip

## 今後

- 自分の興味
- 今後のトレンド
- 技術進歩によって予見できる未来

### 人口膵臓


### YouTuber

特に若い人が多い？機材の説明など動画で説明されると分かりやすい。

Diabetic Energetic
https://www.youtube.com/channel/UC_20PWJ0X0HAloRioVvb5-A
この人は、かなり情報通。

Michelle Lord
https://www.youtube.com/channel/UCAaImwzx0e7zPUaylejt3Tw

- [ ] もっといないか調べる
- [ ] それぞれの動画をもっと見て、感想をまとめる。
- [ ] お勧め回など

