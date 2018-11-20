# ワードクラウドを作る

## 事前準備
[web_crawler](../web_crawler) で取得したニュースからワードクラウドを作成します。
事前に一度 web_crawler.ipynb の内容を一通り実行しておいてください。

## ハマりどころ
基本的には MeCab して wordcloud する例は web にたくさん記事がありますが、
実際に実行してみないと分からない点があります。例えば…

- Python3 で MeCab の parseToNode にバグがある
- Jupyter で MeCab を扱う関数を宣言して実行したとき、上記の事象が起こってもエラー出力されない
- parseToNode のバグ回避をしても私の環境だけか surface がうまく取得できない
