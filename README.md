# SB_kakumei_simulator

ささみ氏により作成されたゲーム「しりとりバトル」での最善手を求めます。

今回は革命合戦編です。

# Features

* HP
* 攻撃力
* 防御力
* 乱数
* 言葉
* タイプ

を設定して革命合戦の勝敗を完全に予測します。

自身での単語の追加も可能です。

## play.txt
革命合戦で使用する単語集です。

単語を追加する際は以下のように追加してください。

```
単語 タイプ1 タイプ2
```

タイプは0,1個のみの入力でも可能です。遊びタイプを含まなくても問題ありません。

※辞書は逐次更新されます。

## typed.csv
使用される単語の最大打点を求めるためだけに使用しております。

万が一新たな単語が追加された場合や独自の単語を追加したい場合は修正してください。

# Note

### HPの設定可能範囲
HPは1から100まで設定可能です。

### 計算時間
* HPが多すぎる場合
* 攻撃力が低すぎる場合
* 防御力が高すぎる場合

以上のような場合では計算に最悪数時間かかります。

(終了時にはメッセージボックスにて通知が行きます。)

長すぎると感じる場合は処理を中断してください。

### エラー
エラーが発生した場合はエラーの内容を私に教えていただければ幸いです。


# Author


* 作成者:しりとり太郎


# License
本アプリケーションの二次配布・商用利用を固く禁止します。

* ささみ氏のTwitter: https://twitter.com/sasamijp
* しりとりバトル(ブラウザ版): http://siritoribattle.net
