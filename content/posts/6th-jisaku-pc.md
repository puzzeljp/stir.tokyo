---
title: 6年ぶりにPCを組み立てました
description: 6年ぶりに自作した記録
date: 2019-07-11T13:05:50.287Z
image: /images/uploads/6th-jisaku-pc.png
categories:
  - computer
tags:
  - 自作PC
  - computer
  - ガジェット
---
[初めてパソコンを作りました \- colopixie](https://colopixie.com/computer/%e5%88%9d%e3%82%81%e3%81%a6%e3%83%91%e3%82%bd%e3%82%b3%e3%83%b3%e3%82%92%e4%bd%9c%e3%82%8a%e3%81%be%e3%81%97%e3%81%9f/) に前回も組み立てたときに書きましたが、自分のメモとして書いておきます。

### 使い道
自宅メインPCの置き換えです。まだ移行しきれてないですが、MacPro 2013 6Core, 64GB, 1TB SSD, FirePro D700*2 を使ってました。買い替えきっかけは、**4Kビデオのレンダリング**の遅さと、**Lightroomの処理の遅さ**です。さすがに持ち運びに使っている、MacBook Pro 2018 13 Core i5, 16GB, 1TB よりはさすがに早いですが、会社で使っている、MacBook Pro 15 2018 Core i9, 32GB, 1TB, Radeon Pro 560X と同等のスピードなので、もう少し自宅では快適に行いたいというのが目的です。

### 予算
30万円です。
MacPro よりもなるべく表面上のスペックは下がらないように努力はしました。また、Thunderbolt のHDDなどがあるので、そこら辺も考えながら構成をしています。

### 条件
- CPU: 6コア/12スレッド
- メモリ: 64GB以上
- マザボ: M.2 NVMe 2つ以上/ Thunderbolt 3 あり
- GPU: RTX 2080 以上
- SSD: M.2 NVMe 1TB 以上

レアケースなのは、Thunderbolt 3 が付いたマザーボードだとおもいます。PCI 接続の Thunderbolt 3 カードを入れれば良いんですが、10Gbps LAN などのカードも増やしたいと思っていたので、マザーボードについているといいなぁと思って探していました。
目的は、LG 5K Display を接続するためです。

## 構成 (5/31当時)
- 【CPU】Core i9 9900K BOX \61,947 @Amazon.co.jp
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B005404P9I&linkId=5e8c16ecf7ffe53ef4fccc990c1ef371"></iframe>
- 【CPUクーラー】MasterLiquid ML240L RGB MLW-D24M-A20PC-R1 \9,073 @Amazon.co.jp
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B075YPG52N&linkId=17756ba0b43bef5e6d0d85b13fb0a38c"></iframe>
- 【メモリ】F4-3000C16Q-64GVRB [DDR4 PC4-24000 16GB 4枚組] \38,980 @PCSHOPアーク
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B07791TXY6&linkId=4d9c02151b4178d6df3904c679f19cb0"></iframe>
- 【マザーボード】Z390 DESIGNARE [Rev.1.0] \33,779 @ドスパラ
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B07K8RJZRG&linkId=c3a3f341ad15aeee7f8be1a1c81c5443"></iframe>
- 【ビデオカード】NE62080S20P2-180A (GeForce RTX2080 8GB) [PCIExp 8GB] ドスパラWeb限定モデル \79,800 @ドスパラ
  - [価格\.com \- Palit Microsystems NE62080S20P2\-180A \(GeForce RTX2080 8GB GamingProOC\) \[PCIExp 8GB\] ドスパラWeb限定モデル 価格比較](https://kakaku.com/item/K0001088741/)
- 【SSD】Force Series MP510 CSSD-F960GBMP510 \16,980 @最安
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B07HR78FQ5&linkId=c68423fe3e98e42248cc8cc4f7634bf8"></iframe>
- 【ケース】SST-KL07B \10,440 @最安
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B01LY422W8&linkId=80b0d821332a4e10ad92fcaf269abe32"></iframe>
- 【電源】NeoECO Gold NE750G \9,352 @TSUKUMO
  - <iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=maybexxx-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B078JBVTBV&linkId=c7c53b7246254c323ba371f2e7523824"></iframe>

**【合計】¥ 260,351**

[自作PC 構成見積もり てすと](http://niku.webcrow.jp/?M3EyztExSY8o1TFxyTHXMfFKidAxqUrN0dExcQpM1NHRMQ40cdQxycjI1tEz1IFBEAIz9PQMzZIt9PTKjAA=)

## 良くなったところ
### 確実にパフォーマンスが上がった
- Lightroom の部分修正や書き出し速度があがりました。α7RⅢ の高解像度の RAW ファイルでさえも快適に行えます。（その代わり CPU 率が 100％ になります）
- 動画の編集やエンコーディングに関しては、まだあまり試せてないですが、Looks を当てても元動画の FPS が出た状態で編集をすることが出来てます。
Windows に関しては、サブ機として使っていたので特に違和感はありません。Photoshop, Illustrator, Premiere, Figma が普通に動きます。Mac より安定しているかと言われると、Figma は Mac の方が安定して動きますね。
Adobe 製品は特に違和感なく動作しています。
- NASの接続に関しても、Windows にしてから安定して接続できています。コレについてはまたどこかで書きたいと思っているですが、Lightroom の写真データに関しては、NASに保管しています。

### もう少し考えても良かったこと
パーツの話にはなるのですが、もう少しCPUクーラーを考えても良いかもとは思っていました。CPU率が 100％ になることが多々あり、その際に結構な温度に達してしまうのでもう少し大きい物か、水冷でも評判の良い物にすれば良かったなと思ってます。

## まとめ
- 組み立てて良かった。30万以下でこのスペックは、Mac ではつくれない。
- Windows で動くエンコードのソフトなど結構役に立つ。
- ノートは、Mac の方が良いなと思う（トラックパッド問題は標準ドライバを当てれば結構行ける）、液晶ディスプレイの質や開発環境のことを考えると Mac である必要がある･･･。
- なので、自作PC(i9) 、持ち運びは MacBook Pro 13 2018 モデルでちょっとの間は行こうと思っています。ただ、昨日 VAIO SX12 を買ってしまったので、一旦持ち運びメイン機に昇格させる可能性はあります。

是非、家に高性能なパソコンが欲しいな〜という方はパソコン組み立ててはいかがでしょうか。Core i9 も安く、SSDもメモリもだいぶ下がってます。

