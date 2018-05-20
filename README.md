# pyhton-Environment
Ubuntu16.04でのpythonの環境構築の方法です（電子工学研究会用）<br>
<br>
今回はAnacondaというディストリビューションを使ってインストールを行います。<br>
<br>
https://www.anaconda.com/download/ <br>
まず↑のURLにアクセスしてください。<br>
<br>
![](https://github.com/AtsuyaKoike/pyhton-Environment/blob/master/anakonda.png)<br>
そして「Python 3.6 version」のDOWNLOADをクリックし、任意のディレクトリに保存します。<br>
<br>
![](https://github.com/AtsuyaKoike/pyhton-Environment/blob/master/anakonda2.png)<br>
<br>
そしてターミナルでダウンロードしたディレクトリまで移動してbashコマンドで実行します。<br>
<br>
![](https://github.com/AtsuyaKoike/pyhton-Environment/blob/master/anakonda3.png)<br>
<br>
指示に従っていきましょう。基本的にそのままで問題ありません。<br>
<br>
他にもインストール場所について聞かれることがありますが、yesで大丈夫です。<br>
<br>
最後にMicorsoft VScodeをインストールするか聞かれますが、どちらでも構いません。<br>
<br>
# バージョン確認
```
$ python --version
```
でpyhtonのバージョンを確認することができます。<br>
```
$ conda list
```
でAnacondaのバージョンを確認することができます。<br>
# 対話モード
インストールが完了するとpythonコマンドが使えるようになります。<br>
pythonインタプリタの対話モードで計算やprint関数を試してみましょう。<br>
![](https://github.com/AtsuyaKoike/pyhton-Environment/blob/master/anakonda4.png)<br>
<br>
これで設定は完了です。pythonのプログラムを書いていきましょう！<br>

# pythonスクリプトファイル
pythonインタプリタでは長いプログラムが書けないのでファイル実行できるようにししょう。<br>
今回は例えばpractice.pyというファイルをつくり（pythonのファイルは.pyで表されます）、その中にプログラムを書いていきます。<br>
実行は
```
$ pyhton practice.py
```
で行えます。
