# Welcome to Spresense libs for Arduino compatible project

本家のReadmeは、こちら。  
https://github.com/sonydevworld/spresense-arduino-compatible/blob/master/README.md  


# Spresense Arduino/SDK のαリリースについて  

こちらでは、本線のリリースの先駆けて、トライアル用にα版として、以下の2つのパッケージをリリースしています。  

・楽器用のプロジェクト向け（シンセサイザ機能版）  
・超高速ADCのプロジェクト向け（512kHz High Speed ADC版）  

注) 現時点で評価ができているものではありません。バグ等に関しての責任は負いかねます。  
注) 現在提供のAPIは、暫定版です。正式版で変更される可能性があります。  

これらをお試し頂いて、フィードバックをもらうことを目的としています。  


## 楽器用のプロジェクト向け  

楽器作成などを行うために、以下の機能を入れ込んでパッケージを作成しています。  
   - レコグナイザー機能 ※ライブラリ別。（契約メンバのみ）  
   - シンセサイザ機能  
   がArduinoで呼べるようになります。  


α版のinstallは、  

Arduinoのファイル / 環境設定 の中の <br>
追加ボードマネージャのURLに、 <br>

https://github.com/TomonobuHayakawa/spresense-arduino-compatible/releases/download/common/package_spresense_instrument_index.json <br>

を追加してください。  
これを追加すると、ボードマネージャの中に、  
Spresense Instrument  
というボードが新たに選択できます。  

楽器用のスケッチは、  

https://github.com/TomonobuHayakawa/Spresense-Playground/tree/master/sketches/Instruments  

こちらにあります。

## 超高速ADCのプロジェクト向け

AEセンシングなどのセンサ用ADCを超高速動作させるためのSDKになります。
*低速・超低消費電力モードでのSCU動作はできなくなります。*  


α版のinstallは、  

Arduinoのファイル / 環境設定 の中の <br>
追加ボードマネージャのURLに、 <br>

https://github.com/TomonobuHayakawa/spresense-arduino-compatible/releases/download/common/package_spresense_HighSpeedADC_index.json <br>

を追加してください。  
これを追加すると、ボードマネージャの中に、  
Spresense HighSpeedADC  
というボードが新たに選択できます。  

サンプルスケッチは、  スケッチ例 -> Spresense HighSpeedADC用のスケッチ例の中の Sensingの中にある

application / capture_hpadc

になります。



