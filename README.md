# M5StackChan-with-tamiya-tank

タミヤのカムロボのキャタピラ部分を使って、M5StackのStackChan用のキャタピラを作る手順

<img width="577" height="694" alt="image" src="https://github.com/user-attachments/assets/39bd3ff2-5cda-4564-978a-9bb1e8bd642f" />

## 資材

- [M5StackChan AIデスクトップロボット](https://docs.m5stack.com/ja/StackChan)
- [カムプログラムロボット工作セット](https://www.tamiya.com/japan/products/70227/index.html)
- [AtomicMotion](https://www.switch-science.com/products/10489)
- [AtomLite（他のAtomシリーズでも構いません）](https://www.switch-science.com/products/6262)
- [自作3Pプリンターパーツ(MakerWorldで公開)](https://makerworld.com/ja/models/3384887-stackchan-camrobobase-kit#profileId-3851775)
  - A. キャタピラ固定用のサイドパネル（左右）
  - B. StackChan用の台座（オプションの超音波センサーも取り付け可能）
  - C. カムロボの腕をStackChanに取り付けるアダプタ
  <img width="600" height="343" alt="mw01" src="https://github.com/user-attachments/assets/c790ef24-de4b-4a09-a64b-1010e9735247" />
- レゴテクニックピン（12本）

### オプション
- [M5Stack用超音波測距ユニット I/O（RCWL-9620）](https://www.switch-science.com/products/7632)
  - こちらは POAT.B 用の製品です

## 作り方

### キャタピラ部

カムプログラムロボットの
作成手順のうち **２、４，５，９，１０、１１，１２** を実施してキャタピラ部分だけを作ります。

この時、以下の手順では「不要なパーツ」や「自作3Pプリンターパーツ」を使用します

- ２：キャタピラ固定用のサイドパネルを自作3PプリンターパーツＡに交換
- １１：ロボのアームに装着する丸い部品が不要
- １２：StackChan用の台座（自作3PプリンターパーツＢ）をキャタピラベースに固定
- １２：カムロボの腕をStackChanに取り付けるアダプタ（自作3PプリンターパーツＣ）を使ってStackChanに腕を装着
<img width="600" height="377" alt="01" src="https://github.com/user-attachments/assets/d94417c5-a918-4498-8445-1f39e13fceec" />

<img width="600" height="224" alt="02" src="https://github.com/user-attachments/assets/558ec2ea-cefd-4eb9-8004-caefd45739b4" />

<img width="600" height="465" alt="03" src="https://github.com/user-attachments/assets/5eeb8961-d9ac-47f3-83bb-7658c1cd9e18" />

### StackChan部

AtomicMotionをカムロボのモーターにつないで制御してください。

超音波センサーを使って自動的に壁をよける[サンプルプログラム](https://github.com/u-tanick/stackchan-idf-for-auto-driving-vehicle-use-sonic)を公開しています。
超音波センサーはAtomicMotionのPort.Bに接続します。
また、AtomicMotionに取り付けたAtomLteとStackChanもGroveケーブルでつないでください。

もしラジコンのように操作したい場合は、BluetoothやESPNowなどを使って改造してください。

## 本ページ紹介用QRコード
<img width="450" height="450" alt="qrcode_github com" src="https://github.com/user-attachments/assets/ff41609a-e335-4069-bda6-f27940aaed0b" />

