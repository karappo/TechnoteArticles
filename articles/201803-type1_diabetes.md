# T1Dとテクノロジーの現在

私は、1型糖尿病（Type1 Diabetes。以下T1D）という10万人に1〜2人のかなり珍しい病気を持っています。2001年の発症以来、この持病についてまとまった記事を書いたことは、今までなかったのですが、近年この分野でもデジタル技術の波を感じる様になってきました。患者として、エンジニアとして、ついでにデザイナーとしての視点も加えつつ、T1Dに関する今ホットな話題を紹介して行きたいと思います。

## 1型糖尿病(T1D)とは

日本人糖尿患者の約95％を占めるのは生活習慣病の2型糖尿病（Type2 Diabetes。以下T2D）です。T1DとT2Dとは全く違います。生活習慣や遺伝などとは無関係に、様々な理由[note]私の場合は風邪のウイルスが引き金だった可能性が高いのですが、厳密には不明です。ストレスなどが原因となる場合もあり、発症の可能性は誰にでもあります。[/note]から突然発症します。T1Dは、自己免疫が膵臓にあるβ細胞というインスリンを作る細胞を破壊してしまい、インスリンが欠乏する病気です。インスリンは、血液中の糖分（Glucose）を細胞に運びエネルギーに変える働きをしているホルモンです。インスリンが欠乏すると、血液中に糖があふれ高血糖になります。

## 血糖測定とインスリン注射

高血糖への唯一の対抗手段はインスリン製剤の注入です。その量が多すぎれば、昏睡から死をも招く低血糖になり、足りなければ高血糖となり<a href="https://ja.wikipedia.org/wiki/%E7%B3%96%E5%B0%BF%E7%97%85%E6%80%A7%E3%82%B1%E3%83%88%E3%82%A2%E3%82%B7%E3%83%89%E3%83%BC%E3%82%B7%E3%82%B9" target="_blank">ケトアシドーシス</a>の危険性や合併症リスクが高まります。そのため、インスリン療法は厳密に行う必要があります。患者は自分自身で、食事のたびに血糖値を測り、その値やこれから摂取する食事量に応じてインスリンの量を見積もり、自己注射します。

### ペン型注射器

![Novo Pen Echo](https://www.novonordisk.com/content/dam/Denmark/HQ/Patients/DiabetesCare/PensNeedlesInjection/NovopenEcho-v3.png)

インスリンの自己注射には、「ペン型」と呼ばれる携帯性に優れたタイプの機材があります。針は使い捨てで消毒は不要です。


[Novo Pen Echo](https://www.novonordisk.com/patients/diabetes-care/pens--needles-and-injection-support/NovoPenEcho.html)


昔はよく病院で使われているような注射器だったらしいです。針も使い捨てではなかったので、煮沸消毒の必要もありました。


### FreeStyle Libre

この記事を書いている現在は、2018年3月です。2ヶ月前の2018年1月から、アメリカの[Abbot社](http://www.abbott.com/)の[FreeStyle Libre](https://www.freestylelibre.us/)を処方してもらえるようになりました。この機械は、500円玉サイズのセンサー（メモリー）を体に取り付けることで、常時血糖値をモニタリングすることができる機械です。

![FreeStyle Libre](https://www.freestylelibre.us/sites/all/themes/freestyle_libre/images/libre-system-large.png)

### iOSのHealth.appとの連携方法

- [ ] Health Kit？

### 良かったところ

（以前までの機器から改善された点。Accucheckの説明もする？）

### イマイチなところ

タッチディスプレイの反応が悪い。

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

<a href="https://tidepool.org/" target="_blank">Tidepool</a>は、世界中の患者の糖尿病機器からのデータを取得し、患者およびそのケアチームにデータのビジュアライズを提供してくれます。更に、患者は任意で自身のデータを匿名で研究機関に提供することもでき、研究に役立ててもらうこともできるという、オープンソースの非営利企業です。
<iframe width="560" height="315" src="https://www.youtube.com/embed/hQAXerpH8Tc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<a href="https://www.youtube.com/embed/jPuCWgqCcR0?start=436" target="_blank">実際の先生と患者が出演して診断している時の様子を見せてくれてる動画</a>もあり面白いです。



<a href="http://www.jdrf.org/" target="_blank">JDRF（国際若年性糖尿病研究財団）</a>がサポートしている。FBグループ「iVOX (TYPE1 IDDM JAPAN)」で教えていただきました。このグループも、色々な情報が得られます。

ソースコードも公開されててすごい・・・（react+reduxみたい）
https://github.com/tidepool-org/blip

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

T1Dは一度発症すると治りません。再生医療分野の発達によって将来的に期待は持てますが、まだまだ先の話です。発症を知らされた当時、正直に言って絶望しました。毎日数時間おきに指を穿刺して血糖値を測定・記録し、測定値や状況に応じてインスリンの投与量を自分で判断し自分で注射する、そんな生活を一生続けなければいけないのですから。とはいえ、もっと重篤な病気のことを思えば恵まれています。血糖値のコントロールさえきちんとできれば、健常者と同じように生活できるのですから。また、医療技術の発達によって少しづつ患者の負担は軽減されています。

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

Githubで「diabetes」で検索すると結構出てくる
https://github.com/Flameeyes/glucometerutils

- [ ] もっといないか調べる
- [ ] それぞれの動画をもっと見て、感想をまとめる。
- [ ] お勧め回など

小児発症が多いため、かつては「小児糖尿病」と呼ばれていました。
参照：[インスリン療法を知る ｜ 糖尿病がよくわかるDM TOWN](https://www.dm-town.com/life/ryouhou03.html)