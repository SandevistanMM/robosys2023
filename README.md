# robosys2023
ロボットシステム学2023

# plusコマンド
[![test](https://github.com/SsamXI27/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/SsamXI27/robosys2023/actions/workflows/test.yml)

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu20.04

## インストール手順
```
$ git clone https://github.com/SsamXI27/robosys2023.git
```

## このコードの使用方法
* このコードでは順数を合計した結果が標準出力されます
* robosys2023へ移動
```
$ cd robosys2023
```
* seq (数字を入力)　| ./plus　と入力することで実行します.例として下記のように入力すると1~10までを足した結果が出力されます.
```
$ seq 10 | ./plus
```
* 下記のように入力するとnums内に保存されている数を足した結果が標準出力されます.
```
$ ./plus < nums
```

## 著作権とライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージは,Ryuichi Ueda氏のコード(©2023 Ryuichi Ueda)を基に作られています．
* このパッケージのコードは，下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda)のものを，本人の許可を得て自身の著者としたものです．
　　　　 * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Syousei Samitu
