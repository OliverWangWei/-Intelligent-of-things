# 智慧家電

## 簡介

現在許多冷氣電扇都是全自動的感應當下的環境來決定是否要開還是關，在這裡我們簡單的製作一台可以自動感應溫濕度的電風扇，當你覺得熱之前他就已經為你自動打開而無需你懶洋洋地從舒服的沙發站起來跑去按才可以吹到陣陣涼風。不僅如此，還可以透過網頁即時監控現在的溫度和濕度。

## 功能
1. 自動偵測溫濕度，在溫溼度到達某種程度時自動開啟家電。

2. 擁有網頁介面，即時監控監理的溫濕度。

## 材料
樹莓派*1、杜邦線數條、馬達*1、風扇葉片*1、溫濕度感測器*1。


## 專案結構

├─ AdafruitDHT.py

├─ README.md

├─ engine.py

└─ server.py

- `AdafruitDHT.py` 即時監控問濕度
- `engine.py` 透過溫濕度決定是否開啟電風扇
- `server.py` 可以即時查看溫濕度的網頁 

## Demo

使用者可以透過網頁按下 `Get Info` 按鈕即可得到現在的溫濕度

![](https://i.imgur.com/rFVg0qo.png)

後段監控的溫濕度資料

![](https://i.imgur.com/N5keyui.png)

硬體裝置

![](https://i.imgur.com/2u6enmQ.jpg)

## 分工

- 丁翊軒 : 硬體配置
- 陳于真 : 專題發想 原型設計
- 王 威 : 程式串接
