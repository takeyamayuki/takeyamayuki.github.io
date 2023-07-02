---
title: "Tech Projects"
date: 2021-06-20T20:13:34+09:00
draft: false
toc: false
images:
---


## 目次

- [ロボカップジュニアサッカー](#-ロボカップジュニアサッカー)
- [NonMouse](#-nonmouse)
- [RESTuino](#-restuino)
- [シューティングゲーム](#-シューティングゲーム)
- [Youtubeチャンネルの運営](#-youtubeチャンネルの運営)
- [GyroMouseBLE](#-gyromouseble)
- [スマートホーム](#-スマートホーム)
- [倒立振子](#-倒立振子)
- [競技プログラミング](#-競技プログラミング)
- [ChinaRemover](#-chinaremover)

&nbsp;

## ⚽ ロボカップジュニアサッカー

２台の完全自律型ロボット同士でサッカーの試合をする大会であるロボカップジュニアサッカーにおいて，高校２年生のときに全国５位入賞．チームは２人で運営し，私は主に123Ddesignでの機構設計，KiCad，bsch3vを用いた回路，基板の設計開発を担当．
[試合動画](https://www.youtube.com/playlist?list=PLkEBRGnKNUILFJv4zKvQkQi69NoT-_FYg)，[ロボットの詳細](https://note.com/spinach_egg/n/n5938fe6f424b)，[GitHub(基板データ)](https://github.com/takeyamayuki/RCJ_Japan_Soccer2017_Board)

- 試合の様子

<iframe width="560" height=auto style="display:block; margin:24px auto 0; width:70%; aspect-ratio:1.766;"  src="https://www.youtube.com/embed/YSenTVdDd-s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- 製作したロボット

{{< image src="/img/0894.JPG" position="center" style="width:70%; border-radius: 8px;" >}}


## 👆 NonMouse  

Webカメラを用いて手の骨格を認識することで実体のないマウスを開発．技育展2021にて開発スキル支援部門で優秀賞受賞．[GitHub](https://github.com/takeyamayuki/NonMouse2)，[Zenn](https://zenn.dev/ninzin/articles/94b05fdb9edf53)，[Youtube](https://youtu.be/ufvOJUTCF8M)

{{< image src="https://user-images.githubusercontent.com/22733958/135473409-9ddf2fc5-4722-4e55-8eef-64476635c10d.gif" position="center" style="width:70%; border-radius: 8px;" >}}  

## 📶 RESTuino

RESTuinoは，REST APIでArduinoを制御するためのESP32向けファームウェアで，このファームウェアを用いることで，IoT開発の効率化を行えたり，対話型組み込み開発ができるようになる．
[GitHub](https://github.com/takeyamayuki/RESTuino)，[Zenn](https://zenn.dev/ninzin/articles/5c859a0bfc1ee6)

{{< image src="https://user-images.githubusercontent.com/22733958/188927218-d310dea3-8fe5-4b1a-8fdd-ffdac5e5f4da.gif" position="center" style="width:70%; border-radius: 8px;" >}}


<!-- Arduinoを用いてWebアプリケーションを作成することができます．-->

## 🔫 シューティングゲーム      

高校の文化祭において，レーザーでCdSセンサーの的を撃つとパソコン上で点数がカウントされ順位表に表示するシステムを構築．３人で作っていて，自分は回路設計，はんだ付けを担当．

{{< image src="/img/02_013.JPG" position="center" style="width:70%; border-radius: 8px;" >}}


## 💻 Youtubeチャンネルの運営

[でんきにんじんチャンネル](https://www.youtube.com/channel/UC2Ijyce-DOkMKqagTPDZleg)で電子工作，プログラミング，商品レビューや音楽の動画を投稿．
[【電子工作】シンセサイザーを作る](https://youtu.be/jINfBOPpO74) というシンセサイザーの作り方の動画を投稿し，現在8000回再生．

## 🖱️ GyroMouseBLE

Youtubeの企画として，Wiiリモコンのようにジャイロセンサーを使ってマウスを操作するBLEデバイスの製作をした．[GitHub](https://github.com/takeyamayuki/GyroMouseBLE)，[Youtube](https://youtu.be/DzT40SCh3nI)

{{< image src="https://user-images.githubusercontent.com/22733958/130589777-bb9e9679-aeb6-43dd-bc9e-a26c03030525.gif" position="center" style="width:70%; border-radius: 8px;" >}} 


## 🏠 スマートホーム

Raspberry Pi，ESP32を用いて家のIoT化を行った．メイン処理部分にはHomekitエミュレータのHomebridgeをインストールしたRaspberry Piを使用し，リモコン操作も可能にした．壁付けスイッチの操作のために，Switchbotを模した[RESTful-servo-motor](https://github.com/takeyamayuki/RESTful-servo-motor)を開発した．(→現在は，それをarduinoGPIOに拡張した[RESTuino](#-restuino)があります．)

現時点では，エアコン操作とスイッチ操作を，家の中ならiphoneのホームアプリから，家の外ならVPN接続をしてブラウザから操作できる．[Youtube](https://youtu.be/n8qGnXRE8T8)   

- iPhoneからスイッチを操作する様子

{{< image src="https://user-images.githubusercontent.com/22733958/173193531-89778f00-82e1-46e1-8544-b0c455d07dfb.gif" position="center" style="width:70%; border-radius: 8px;" >}}  


## 🤖 倒立振子

ジャイロセンサを搭載した二輪ロボットの製作と，倒立振子のPD制御プログラムを開発した． [GitHub](https://github.com/takeyamayuki/Inverted-pendulum)

{{< image src="https://user-images.githubusercontent.com/22733958/174483055-81f5fcc1-4386-4e63-b027-0413a0957270.gif" position="center" style="width:70%; border-radius: 8px;" >}}  


## 💻 競技プログラミング

Python，C++を用いてAtcoderに出場．現在茶色(highet 404)．  
[リンク](https://atcoder.jp/users/takeyama)


## 🛒 ChinaRemover

Amazonの検索結果の中から，日本発送以外のものを排除した検索結果を表示するGoogle Chromeの拡張機能を製作．
[Chrome Store](https://chrome.google.com/webstore/detail/china-remover/koddfmmljnagafaapbegnjacfhlhiefg?hl=ja&gl=001)，[GitHub](https://github.com/takeyamayuki/ChinaRemover)


&nbsp;

※ 下線が引いてあるものはリンク先に飛べます．