# 「生物物理学」サポートサイト
[鳥谷部祥一著「生物物理学」（日本評論社 物理学アドバンストシリーズ）](https://www.nippyo.co.jp/shop/book/8854.html)

<b>[第2刷での修正](http://web.tohoku.ac.jp/bp/wp-content/uploads/生物物理学修正（第１刷）.pdf) (2023/6/28)</b>

本書に関連するPython用ソースコードを提供しています．Jupyter Notebook形式ファイルとなっています．
実行環境をお持ちでない方は，"Open in Colab"ボタンをクリックすると，Google Colabからファイルを開くことができ，実行することもできます．
ただし，修正を保存したい場合は，一度，Colabのメニューからファイルをご自身のフォルダーに保存してください． <br><br>

| ファイル  | 概要 | 対応する章 |
| ----| ----| ----|
|  [K_kinetics.ipynb](K_kinetics.ipynb)  <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/K_kinetics.ipynb) | K1 ミカエリス-メンテンモデル<br> K2 アロステリック効果  | 第3章 |
 | [D_dynamicalsystem.ipynb](https://github.com/stoyabe/biophys/blob/main/D_dynamicalsystem.ipynb) <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/D_dynamicalsystem.ipynb) | D1 固定点<br> D2 ファンデルポール型振動子 <br> D3 チューリングパターン<br> D4 SIRモデル | 第4章 |
  | [F_fluctuation.ipynb](https://github.com/stoyabe/biophys/blob/main/F_fluctuation.ipynb) <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/F_fluctuation.ipynb) | F1 マルコフジャンプ<br> F2 ギレスピーアルゴリズム <br> F3 中心極限定理 <br> F4 ランダムウォーク <br> F5 拡散方程式<br> F6 移流拡散方程式<br> F7 自己相関関数<br> F8 ランジュバン方程式 | 第5章，第6章 |
| [S_structure.ipynb](https://github.com/stoyabe/biophys/blob/main/S_structure.ipynb) <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/S_structure.ipynb)  | S1 エントロピー弾性<br> S2 枯渇力 | 第7章 |
| [M_motor.ipynb](https://github.com/stoyabe/biophys/blob/main/M_motor.ipynb) <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/M_motor.ipynb)  | M1 分子ポンプ<br>M2 パワーストロークと拡散整流<br> M3 フラッシングラチェット<br> M4 滞在時間分布 | 第9章，第10章  |
| [C_cell.ipynb](https://github.com/stoyabe/biophys/blob/main/C_cell.ipynb) <br><br> [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stoyabe/biophys/blob/main/C_cell.ipynb) | C1 相分離<br> C2 ビチェックモデル | 第13章，第14章 |

ソースコードは，理解しやすさや修正のしやすさを優先して作っており，高速化や美しさは追及していません．プログラムをいじって遊ぶことで現象の理解の助けになると期待しています．
