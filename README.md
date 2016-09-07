# ISHOCON2
iikanji na showwin contest 2nd (like ISUCON)

![](https://github.com/showwin/ISHOCON2/blob/master/doc/images/top.png)

# 概要(仮)
* ネット選挙を受け付けるWebサービス
* 大量の投票リクエストが送られてくる
* 10秒ごとに中間発表を行う必要がある(ベンチマーカーは1分間動くので、終了までに5回中間発表がある)
* 中間発表では、各候補者の支持度(pointの平均?)と、なぜ指示されているのか(noteを分析した結果)を表示する
* 1分間でどれだけの投票を受け付けられたかで勝負する
* 投票内容(データ)
  * name: 候補者の名前
  * point: 1 ~ 5 の5段階で、どれぐらい指示しているかを表す
  * note: どういった点で支持しているかを記述する
