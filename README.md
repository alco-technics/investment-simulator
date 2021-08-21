# investment-simulator

## 使い方

本リポジトリのファイルは、ブラウザ上で実行可能なGoogle Colaboratory上で動作する形式で実装します。

ここでは、Google DriveにGit クローンする方法を記載します。
（通常通り、ソースコードをダウンロード・クローンしてブラウザ上で使用することもできます。）

1. Google Colaboratoryを開きます。

 URL : https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja

2. 画面上部の「+コード」をクリックします。コーディングするテキストボックスが表示されます。

以下を入力し、実行します。
（実行にはテキストボックス左の再生ボタン「▶」をクリックします。）

※Googleアカウントへのログインが必要となります。

``` Python
from google.colab import drive
drive.mount('/content/drive')
```

次に、以下を入力し、実行します。

``` Python
%%bash
cd '/content/drive/My Drive/Colab Notebooks'
git clone https://github.com/alco-technics/investment-simulator
```

これにより、Google Drive上に「Colab Notebooks」というフォルダが作成され、「Colab Notebooks」内に今回クローンした「investment-simulator」が作成されます。
 
フォルダ内の「.ipynb」という拡張子のファイルをダブルクリックすると、Google Colaboratoryで開かれ、ソースコードを表示・実行することが可能となります。

---

### Google Colaboratory上でのプログラムの実行方法

Google Colaboratory上で、プログラムを実行するには、
画面上部のタブ「ランタイム」をクリックし、「全てのセルを実行する」とクリックします。


