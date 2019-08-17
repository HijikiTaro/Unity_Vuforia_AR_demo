
- [注意](#%e6%b3%a8%e6%84%8f)
- [開発環境](#%e9%96%8b%e7%99%ba%e7%92%b0%e5%a2%83)
- [手順](#%e6%89%8b%e9%a0%86)
  - [事前準備：ARマーカー用に画像を準備](#%e4%ba%8b%e5%89%8d%e6%ba%96%e5%82%99ar%e3%83%9e%e3%83%bc%e3%82%ab%e3%83%bc%e7%94%a8%e3%81%ab%e7%94%bb%e5%83%8f%e3%82%92%e6%ba%96%e5%82%99)
  - [Vuforia：ユーザ登録](#vuforia%e3%83%a6%e3%83%bc%e3%82%b6%e7%99%bb%e9%8c%b2)
  - [Vuforia：マーカー登録とライセンスキー作成](#vuforia%e3%83%9e%e3%83%bc%e3%82%ab%e3%83%bc%e7%99%bb%e9%8c%b2%e3%81%a8%e3%83%a9%e3%82%a4%e3%82%bb%e3%83%b3%e3%82%b9%e3%82%ad%e3%83%bc%e4%bd%9c%e6%88%90)
  - [Unity：ダウンロードしたパッケージをインポート](#unity%e3%83%80%e3%82%a6%e3%83%b3%e3%83%ad%e3%83%bc%e3%83%89%e3%81%97%e3%81%9f%e3%83%91%e3%83%83%e3%82%b1%e3%83%bc%e3%82%b8%e3%82%92%e3%82%a4%e3%83%b3%e3%83%9d%e3%83%bc%e3%83%88)
  - [Unity：Vuforiaを有効](#unityvuforia%e3%82%92%e6%9c%89%e5%8a%b9)
  - [Unity：メインカメラを削除](#unity%e3%83%a1%e3%82%a4%e3%83%b3%e3%82%ab%e3%83%a1%e3%83%a9%e3%82%92%e5%89%8a%e9%99%a4)
  - [Unity：ARカメラ追加しライセンスキー登録](#unityar%e3%82%ab%e3%83%a1%e3%83%a9%e8%bf%bd%e5%8a%a0%e3%81%97%e3%83%a9%e3%82%a4%e3%82%bb%e3%83%b3%e3%82%b9%e3%82%ad%e3%83%bc%e7%99%bb%e9%8c%b2)
  - [オブジェクトを作ろう](#%e3%82%aa%e3%83%96%e3%82%b8%e3%82%a7%e3%82%af%e3%83%88%e3%82%92%e4%bd%9c%e3%82%8d%e3%81%86)
  - [ARで表示する3Dオブジェクトを追加](#ar%e3%81%a7%e8%a1%a8%e7%a4%ba%e3%81%99%e3%82%8b3d%e3%82%aa%e3%83%96%e3%82%b8%e3%82%a7%e3%82%af%e3%83%88%e3%82%92%e8%bf%bd%e5%8a%a0)
  - [動作テストを実施](#%e5%8b%95%e4%bd%9c%e3%83%86%e3%82%b9%e3%83%88%e3%82%92%e5%ae%9f%e6%96%bd)
- [参考](#%e5%8f%82%e8%80%83)

# 注意
このReadmeは下記参考をほぼそのまま引用している。

# 開発環境
- Window Home 10
- Unity 2019.1.11
- Vuforia

# 手順
## 事前準備：ARマーカー用に画像を準備
なんでもよいのでとりあえず、GANの時のようにスライムの画像を準備してみた。
![image](./Readme/demo_image.jpg)
## Vuforia：ユーザ登録
[Vuforia](https://developer.vuforia.com/)
## Vuforia：マーカー登録とライセンスキー作成
Target Managerにマーカーとしたい画像を登録する
![image](./Readme/image/1.PNG)
![image](./Readme/image/2.PNG)
![image](./Readme/image/3.PNG)
![image](./Readme/image/4.PNG)
![image](./Readme/image/5.PNG)
※Ratingの☆が高いほどよいらしい
![image](./Readme/image/6.PNG)
![image](./Readme/image/7.PNG)
ダウンロードしたパッケージは「demo1.unitypackage」
![image](./Readme/image/8.PNG)
![image](./Readme/image/9.PNG)
![image](./Readme/image/10.PNG)
## Unity：ダウンロードしたパッケージをインポート
![image](./Readme/image/11.PNG)
![image](./Readme/image/12.PNG)
![image](./Readme/image/13.PNG)
## Unity：Vuforiaを有効
![image](./Readme/image/14.PNG)
![image](./Readme/image/15.PNG)
VuforiaライブラリをUnnityにインストール
![image](./Readme/image/16.PNG)
![image](./Readme/image/17.PNG)
![image](./Readme/image/18.PNG)
![image](./Readme/image/19.PNG)
![image](./Readme/image/20.PNG)
![image](./Readme/image/21.PNG)
![image](./Readme/image/22.PNG)
Vuforiaライブラリをチェック
![image](./Readme/image/23.PNG)
## Unity：メインカメラを削除
## Unity：ARカメラ追加しライセンスキー登録
![image](./Readme/image/24.PNG)
![image](./Readme/image/25.PNG)
![image](./Readme/image/26.PNG)
![image](./Readme/image/27.PNG)
## オブジェクトを作ろう
![image](./Readme/image/28.PNG)
![image](./Readme/image/29.PNG)
## ARで表示する3Dオブジェクトを追加
![image](./Readme/image/30.PNG)
![image](./Readme/image/31.PNG)
## 動作テストを実施
![image](./Readme/image/32.PNG)
![image](./Readme/image/33.PNG)

# 参考
- [Vuforia](https://developer.vuforia.com/)
- [Unity+VuforiaでAR(拡張現実)しよう](https://note.mu/agw/n/n526010605270)
- [【Unity】Vuforiaを使ってARを表示する手順（2019年版）](http://nn-hokuson.hatenablog.com/entry/2018/08/28/192028)
- [XR](https://unity3d.com/jp/learn/tutorials/s/xr)

