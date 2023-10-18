# MSX0向け便利コマンド集
## MSX0GET
HTTP通信でファイルをダウンロードするコマンドです。<br>
ファイル名: MSX0GET.COM<br>
使い方: MSX0GET HOSTNAME PORT SOURCEPATH DEST [WAITTIME]<br>
WAITTIMEは1/60秒単位です。AUTOEXEC.BATに組み込む場合は300程度を設定しておくと良いでしょう。<br>
## MSX0DCAT
ディスクイメージファイルの一覧を表示するコマンドです。<br>
ファイル名: MSX0DCAT.COM<br>
使い方: MSX0DCAT<br>
表示されるのは32ファイルです。<br>
## MSX0DIN
ディスクイメージファイルを切り替えるコマンドです。<br>
ファイル名: MSX0DIN.COM<br>
使い方: MSX0DIN DSK_FILE_NAME<br>
実行した直後は切り替わっておらず、2度目にアクセスしたときに切り替わっています。<br>
とりあえず1回 DIR を打ってください。<br>
## 特記事項
- 作者は使用した事による損害について一切の責任を負うことは出来ません。使用者の責任において使用してください。
