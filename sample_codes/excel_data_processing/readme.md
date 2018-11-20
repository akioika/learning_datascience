# Excel ファイルからデータを抽出して加工する

## 状況
Excel にデータが格納されているが、大量なので加工するのに時間が掛かってしまう。どうにかして短時間に、手間をかけずに作業を完了させたい。

## ゴール
- ビジネス的な面
  - データ加工を自動化することで工数削減を実現する
- 技術的な面
  - pandas を使ったデータ操作を覚える
    - データの読み込み
    - マスタと JOIN
    - GROPU BY / ORDER BY
    - CSV の出力

# 準備
1. %USERPROFILE%\Documents\docker\datascience 直下に excel_data_processing フォルダを作成する
2. 本ディレクトリに同梱されている excel_data_processing.ipynb を %USERPROFILE%\Documents\docker\datascience\excel_data_processing にコピーする
3. 本ディレクトリに同梱されている sample_data.xlsx を%USERPROFILE%\Documents\docker\datascience\excel_data_processing にコピーする
4. Jyputer で excel_data_processing.ipynb を開き、順に実行していく
