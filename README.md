# robosys2023

# Plus プログラム

## 概要
このプログラムは、標準入力から数値を読み取り、それらの合計を計算して標準出力に出力する Python スクリプトです。

## 実行方法

1.  GitHub からリポジトリをクローンします
```
　git clone https://github.com/ryutarou1/robosys2022.git
```
2. 標準入力から数値データを入力します。

3. ./plusでスクリプトを実行します。

4. 実行結果が表示されます。

## 実行例
```

$ seq 3 | ./plus   # 正常な入力
```

```

6

```

```

$ echo $?

```

```

0

```

```

$ echo あ | ./plus  # ひらがなを入力してエラーを起こさせる

```

```

'あ' にアクセスできません: そのようなファイルやディレクトリはありません

```

```

$ echo $?

```

1


## 実行環境

Python 3

## テスト環境
Ubuntu 20.04.6 LTS (GNU/Linux 5.10.102.1-microsoft-standard-WSL2 x86_64)

## 必要なソフトウェア
Python 3.7~3.10

## ライセンス表示
*このソフトウェアパッケージは三条項BSDライセンスのもと、再頒布および使用が許可されています。

*このパッケージのコードは、下記のスライド（CC-BY-SA 4.0by Ryuich Ueda)のものを、本人の許可を得て自身の著作したものです。
  　　*[ryuichiueda/my_slides robosys_2022/lesson5.md] (https://github.com/ryuichueda/my_slides/tree/master/robosys_2022)
　 　 *[ryuichiueda/my_slides robosys_2022/lesson7.md] (https://github.com/ryuichueda/my_slides/tree/master/robosys_2022)

*This Softwere Package allowed Redistribution and Use by GPL 3.0
©2023 kanno ryutaro





