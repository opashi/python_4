python 学習 4章
pythonの基本について

【for文の使い方】

■構文
for 変数 in 範囲(もしくはリスト) :
	処理


■例文
for i in renge(30) :
	print(i)


※Listの要素番号とデータを出力できる
List = [1,2,3]
for i,j in enumerate(List) :
	print(i,j)

出力：左がListのインデックス、右が値
0 1
1 2
2 3


【if文の使い方】

■構文

if 条件 :
	処理
elif 条件 :
	処理
else :
	処理

■例文

if a < b :
	print(a)
elif a > b :
	print(b)
else :
	print(a + b)


【便利機能：format】

出力する変数や数値などを{}で置き換え、見やすくすることができる

name = "opashi"
print("こんにちは。{}です。年齢は{}歳です。".format(name,25))

出力：こんにちは。opashiです。年齢は25歳です。



【Listについて】

■宣言

List名 = [データ]

■リストへの追加

List名.append(データ)

■リストの要素数を取得

len(List名)


【ライブラリの使い方】

■ライブラリのインストール

!pip install ライブラリ名

■ライブラリのインポート

import ライブラリ名

#変数のように略称を設定して、以降の指定ではライブラリ名を記載しなくてもよい
#ライブラリ名が長い場合などに使用
import ライブラリ名 as 略称
