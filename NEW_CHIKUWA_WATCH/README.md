# New ちくわウォッチ (CHIKUWA WATCH New Version)

![IMAGE](https://user-images.githubusercontent.com/124578804/226565462-5594be7d-b806-428d-805c-d4ab445bead2.png)
![DARKMODE](https://user-images.githubusercontent.com/124578804/227699733-b330165f-dfb6-4db2-ac91-360efc8ac0d0.png)
![PEDOMETER](https://user-images.githubusercontent.com/124578804/227699650-107f2705-3bc0-4a3b-8168-94c906b90525.png)
![MSX0](https://user-images.githubusercontent.com/124578804/226571467-dda6f54b-9c6d-4235-a34c-07c213b7c64d.jpeg)

<p>デモ映像はこちら→https://youtu.be/2u2w_yfRsHE</p>
<p>アップデート版のデモ映像はこちら→https://youtu.be/MZQ6vv2_dfg</p>
<p>歩数計とマルチタスクのデモ映像はこちら→https://youtu.be/slLnVOB-MY0</p>

## 概要
MSX0をウェアラブルに使うために作ったスタイリッシュな時計です。<br>
機能の追加・入れ替えをしやすいように構造を見直しました。<br>
MSX0 stack単体でひととおりの操作ができるようになりました。

## 操作方法
#### 画面左上タップ、〇ボタン(左)、カーソルキー(左)
モードを選択します。
#### 画面中央下タップ、〇ボタン(中央)、カーソルキー(右)
時計モード：なし<br>
タイマーモード：時間設定→桁移動→元に戻る<br>
ストップウォッチモード：リセット<br>
歩数計モード：リセット
#### 画面右上タップ、〇ボタン(右)、スペースキー
時計モード：なし<br>
タイマーモード：カウントダウン開始・終了、時間設定時の数字変更<br>
ストップウォッチモード：計測開始・終了<br>
歩数計モード：計測開始・終了
#### 画面左下タップ、カーソルキー(下)
ダークモードの切り替え
#### ゲームパッドでも操作できます

## 起動方法
#### MSX-DOSで起動する（Release 05から）
[NCWTCD05.COM](https://github.com/chikuwa-empire/msx0-iot/raw/main/NEW_CHIKUWA_WATCH/NCWTCD05.COM)をMSX-DOSから実行してください。<br>
ちくわウォッチ専用ディスクにする場合は[AUTOEXEC.BAT](https://github.com/chikuwa-empire/msx0-iot/raw/main/NEW_CHIKUWA_WATCH/AUTOEXEC.BAT)をいっしょに入れておくと自動起動します。
#### ROMイメージをWebMSXで起動する
こちらのリンクから直接起動することができます。<br>
https://webmsx.org/?MACHINE=MSX2J&ROM=https://github.com/chikuwa-empire/msx0-iot/raw/main/NEW_CHIKUWA_WATCH/NCWTCH05.ROM

#### DISKイメージをMSX0で起動する（Release 04）
[NCWTCH04.DSK](https://github.com/chikuwa-empire/msx0-iot/raw/main/NEW_CHIKUWA_WATCH/NCWTCH04.DSK)をMSX0のマイクロSDカードに格納してください。
#### DISKイメージをWebMSXで起動する（Release 04）
こちらのリンクから直接起動することができます。<br>
https://webmsx.org/?MACHINE=MSX2J&DISK=https://github.com/chikuwa-empire/msx0-iot/raw/main/NEW_CHIKUWA_WATCH/NCWTCH04.DSK

## 補足事項
* 曜日が機種依存のためWebMSXでは異なる表示をする場合があります

## 変更履歴
### Release 05 - 2023.03.25
* MSX-DOS用アプリケーションにしました。
* 歩数計モードを追加しました。
* タイマー、ストップウォッチ、万歩計はマルチタスクで動きます。モードを切り替えても動きつづけます。
### Release 04 - 2023.03.23
* 加速度センサーのデバイス名が誤っていました。Bottom2が入手できたので修正して動作確認済みです。
### Release 03 - 2023.03.23
* 最上部のメニュー表示がおかしくなっていたので修正しました。動作には変更ありません。
### Release 02 - 2023.03.22
* 液晶表示面のタッチ操作に対応しました。
* ダークモードを追加しました。
* デバイス情報表示モードを追加しました。
### Release 01 - 2023.03.21
* MSX0で動作確認できましたので改めてリリースします。
