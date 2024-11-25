#### [GitHubの使い方はこちらの記事をご確認ください。](https://bit-trade-one.co.jp/h2gh/)
# ADUBRU-RelayControll

![](https://bit-trade-one.co.jp/wp/wp-content/uploads/2019/08/3b41b291e659768dc80db779f12b911e.jpg)  

USB接続する事でPC上のアプリからリレーを自在にコントロールできる、ADUBRUのサポートページです。  

### [製品HP](https://bit-trade-one.co.jp/adubru/) 

### [Q&A](FAQ.md) 

# PC制御アプリ

### [5回路版ダウンロードリンク](https://github.com/bit-trade-one/ADUBRU-RelayControll/raw/master/PC-Tool/USB_Relay_Controll_CT_5Relay.exe)  

### [9回路版ダウンロードリンク](https://github.com/bit-trade-one/ADUBRU-RelayControll/raw/master/PC-Tool/USB_Relay_Controll_CT_9Relay.exe)  

### [PC制御アプリ・ソース](https://github.com/bit-trade-one/ADUBRU-RelayControll/tree/master/PC-Tool)  

### 複数台を１台のパソコンに接続する場合は、ファームウェアを書き換える必要があります。  
ファームウェア書き換え手順のドキュメントに従い書き換えを行ってください。  
MultipleConnectionsファルダ内の、ドキュメントに従いファームウェアを書き換えて、PCアプリ、ライブラリを使用してください。  

---

## ライブラリ

### [C#ライブラリ](https://github.com/bit-trade-one/ADUBRU-RelayControll/tree/master/Library-Cs)

### [C++ライブラリ](https://github.com/bit-trade-one/ADUBRU-RelayControll/tree/master/Library-Cpp)

### [Visual Basicライブラリ](https://github.com/bit-trade-one/ADUBRU-RelayControll/tree/master/Library-VB)

---

## 回路図

### [5回路版回路図](https://github.com/bit-trade-one/ADUBRU-RelayControll/blob/master/Schematics/usbrelay_5_v11_20190711_sch.pdf)

### [9回路版回路図](https://github.com/bit-trade-one/ADUBRU-RelayControll/blob/master/Schematics/usbrelay_9_v12_20190819_sch.pdf)

---

## 寸法

### [5回路寸法](https://github.com/bit-trade-one/ADUBRU-RelayControll/blob/master/Documents/usbrelay_5_v11.1_20190711_brd.pdf)
### [9回路寸法](https://github.com/bit-trade-one/ADUBRU-RelayControll/blob/master/Documents/usbrelay_9_v11.1_20190711_brd.pdf)
---


## ファームウェア
### [ファームウェア・ソース](https://github.com/bit-trade-one/ADUBRU-RelayControll/tree/master/Firmware)

---
 
**ご注意！**  
本製品をお使いになるには電子工作や電子回路についての一般的な知識が必要です。  

## 製品仕様

基本仕様  
【アプリ対応OS】Windows7, Windows8.1, Windows10 搭載のDOS/Vパソコン  
　（サンプルアプリを動かすには .NET Framework4.0が必要）  
【対応機種】USBポートを標準で持ちパソコン本体メーカーが上記対応OS上でのUSBポートの動作を保証している機種。  
(一部対応しない機種があります）NEC PC-9800、PC-9821シリーズには対応しておりません。  
【インターフェース】・USB2.0 TypeB コネクタ  
【電源】・USB 5V  
リレー仕様：  
【出力端子】COM/NO/NC (1C)  
【定格電圧/電流】AC 250V/10A, DC30V/10A  
【寸法・質量】  
ADUBRU5  
　寸法：72.5×68×17mm（ハンダ面側の突起を含まず）  
　質量：約0.065kg  
ADUBRU9  
　寸法：92×86×17mm（ハンダ面側の突起を含まず）  
　質量：約0.11kg  
【使用温度】 0 ～ 40℃（結露なきこと）  
【生産国】Made in Japan  
