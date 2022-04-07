# confidence_ellipse

x座標, y座標のデータが記載されたファイルから信頼楕円の情報を計算し、描画する。

# Demo

![demo](/imgs/demo.png) 

# Requirements

* python 3.9
* pandas 1.3.4
* numpy 1.20.3
* matplotlib 3.4.3
* scipy 1.7.1

# Installation

```bash
$ pip install scipy numpy pandas matplotlib
```

# Usage
## 事前準備
- 複数のExcelファイルが1つのフォルダに入れておく。

## 使用方法
confidence ellipse_ver3.ipynbを実行。
- 上記のフォルダを`folder_path`に指定すると、各ファイルを読み込み、散布図に等確率楕円を描画したグラフを作成し、相関係数、楕円の面積、半径をまとめのExcelに記載。パスは相対パスでも絶対パスでも可。
- 出力は各ファイルの散布図+確率楕円の画像とまとめのExcelファイル1つ。出力先は`output_path`と`output_fname`で指定。
 
