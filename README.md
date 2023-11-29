# robosys2023
ロボットシステム学2023の授業にて作成したリポジトリです. このリポジトリ内のコードplusでは, 1から指定した数までの連続番号を合計した結果を標準出力することができます. 

# plusコマンド
[![test](https://github.com/SsamXI27/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/SsamXI27/robosys2023/actions/workflows/test.yml)

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu 20.04

## インストール手順
```
$ git clone https://github.com/SsamXI27/robosys2023.git
```

## このコードの使用方法
* robosys2023へ移動
```
$ cd robosys2023
```
  * seq (数字を入力)　| ./plus　と入力することで実行します. 例として下記のように入力すると1~10までを足した結果が出力されます. 
```
$ seq 10 | ./plus
```
  * 出力結果は下記のようになります
```
55
```
* numsを使用する場合の手順です. 
  * numsの中身は下記を入力することで確認できます. 
```
$ cat nums
```
  * 下記のように入力するとnums内に保存されている数を足した結果が標準出力されます. 
```
$ ./plus < nums
```
  * 出力結果は下記のようになります. 
```
55
```

## 著作権とライセンス
* このソフトウェアパッケージは, 3条項BSDライセンスの下, 再頒布および使用が許可されます.  
* このパッケージは, Ryuichi Ueda氏のコード(©2023 Ryuichi Ueda)を基に作られています. 
* このパッケージのコードは, 下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda)のものを, 本人の許可を得て自身の著者としたものです. 
  * [ryuichiueda/my_slides/robosys_2022](https://ryuichiueda.github.io/my_slides/robosys_2022/lesson3.html#/12)
* © 2023 Syousei Samitu
