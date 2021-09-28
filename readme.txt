
このスプリクトは自分のファイル名によって動作が変わります（シンボリックファイルでも可）
このスクリプトを適当な所に置いた上で
「sudo ./tars install」でインストール（/usr/local/bin/内に各シンボリックリンクを生成します）
「sudo tars remove」でアンイントール


解凍系は　tars ＜解凍したいファイル名＞
圧縮系は　tars.c ＜圧縮ファイル名＞ ＜対象フォルダ名＞

その他解凍系は　tars.gz tarz.bz2 tars.xz tars.unzip
その他圧縮系は　tars.gz.c tarz.bz2.c tars.xz.c tars.zip


