# はじめの一歩

## もくじ
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [はじめの一歩](#一歩)
	- [もくじ](#)
	- [ドキュメントの目的](#目的)
	- [対象者](#対象者)
	- [注意](#注意)
	- [読む順番](#読順番)

<!-- /TOC -->

## ドキュメントの目的
ローカルの Windows PC に仮想化技術の一つである Docker を利用して Ubuntu 18.04 環境を構築し

- python3
- Jupyter notebook
- bash
- 各種統計、機械学習

を行えるようにします。
( 仮想化技術は大別すると VM / Docker に分けられますが、その違いは Web に公開されているドキュメントに譲ります。)

## 対象者
- Windows ユーザで Linux は使ったことがない方
- 非 IT エンジニアで、データの加工 / 可視化 / 分析 のいづれかを担当する方
- 業務上 Woindows PC を作業用として貸与されているが、それ以外の環境は自由に用意できない方
- python や jupyter といった言葉を知っているけど環境構築までできない方
- 自分でできることは自分でしたい方

## 注意
ここでは、非エンジニアが読み進められるよう、厳密ではない表現をする場合があります。
また、読み進めれば同じ環境を構築できることを目指しますが「コマンドプロンプトとは」「dockerとは」については記述しません。

## 読む順番
1. [Jupyter を構築する](./setup_jupyter_env/readme.md)
2. [データサイエンスに利用するライブラリをインストールする](./install_datascience_libs/readme.md)
3. [Spark をインストールして jupyter から触る](./install_apache_spark)
