# CH552Xiao2

<img src="https://github.com/akita11/CH552Xiao2/blob/main/CH552Xiao2.png" width="240px">

[WCH(南京沁恒微电子股份有限公司)](http://wch-ic.com/)の8ビットマイコン[CH552](http://wch-ic.com/products/CH552.html)を使った、Seeeduino Xiao型のマイコンボードです。
主な特徴は以下のとおりです。

- Seeeduino Xiao型
- [ArduinoIDEなどでプログラム開発が可能](https://qiita.com/akita11/items/d7baed4ca3c06e292637)
- USBペリフェラル（キーボードやUSBメモリなど）として動作可能
- USB Type-Cコネクタ

またSeeeduino Xiaoとは、以下のような違いがあります。
- 一部ピンの機能が異なる
- +5V端子に、外部電源から+5Vを供給可能（内部にレギュレータはないので、+5Vを超える電圧は不可）
- +3.3V出力の電流供給能力は100mA程度（CH552内蔵レギュレータの性能）
- **現在のロットでは、Seeeduino Xiaoとは+3.3Vと+5Vのピン配置が逆**（Seeeduino Xiao用拡張ボードを利用する場合などは注意してください）

v1である[CH552Xiao](https://github.com/akita11/CH552Xiao)からピン配置が変更されています。

## ピン配置

<img src="https://github.com/akita11/CH552Xiao2/blob/main/CH552Xiao2_pin.png" width="720px">

<img src="https://github.com/akita11/CH552Xiao2/blob/main/CH552Xiao2_Back.png" width="240px">

基板上の"LED"（オレンジ）はP3.0で駆動できます。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
