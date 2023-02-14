# JapaneseOpenPowerDataUsage 
&copy; S. Harada 2023/02/14 最終更新

電力自由化の進展に伴い多くの電力関連情報が公開され，誰でも利用できるようになっています。
このレポジトリにはそれら公開データを取り込んで利用するためのプログラムを掲載していく予定です。
データを取り込み自分で処理するための方法を学んでもらうことを目的としています。
可視化した結果だけを閲覧したい場合にはエクレトリカル・ジャパンをお勧めします。

2022.02.14 沖縄電力需給関連情報(需給実績)[https://www.okiden.co.jp/business-support/service/supply-and-demand/](https://www.okiden.co.jp/business-support/service/supply-and-demand/)
からダウンロードしたデータを読み込みプロットするJupyter Notebook [PythonOEPC.ipynb](https://github.com/S-Ha/JapaneseOpenPowerDataUsage/blob/main/PythonOEPC.ipynb)を公開しました。

Jupyter Notebookのファイルを利用するためにはいくつかの方法があります。
* pipで管理するpythonにjupyter環境を追加インストール
* anacondaのインストーラを用いてpythonやjupyter環境を同時にインストール
* Jupyter Lab Desktopをアプリケーションとしてインストール

最も簡単に利用する方法は最後のJupyter Lab Desktop[https://github.com/jupyterlab/jupyterlab-desktop](https://github.com/jupyterlab/jupyterlab-desktop)をインストールする方法です。pipやanacondaで管理するPythonを使っておらずPythonの利用目的がJupyter環境に限定される場合はこの方法を勧めます。なお，他の環境のPythonがインストールされていても，Jupyter Lab Desktop専用のPython環境を用いることもできます。
