# University_JavaScript
Web実験

## なぜ作ったのか
　このプロジェクトは
[A computational and neural model of momentary subjective well-being](https://www.pnas.org/content/111/33/12252)
を追試するため、作られました。

## なぜjsPsychを利用するか
>jsPsychとは，ウェブブラウザー（Microsoft Edge,Google Chrome,Safariなど）上で行動実験を行うためのJavaScriptライブラリーです。そもそもJavaScriptを上手く使えば，ウェブブラウザーで動作する行動実験課題は作成できます。しかし，全て一から作っていると大変です。そこで，jsPsychのライブラリーを活用することで，より楽に実験課題を作成することができます。
[from](https://kunisatolab.github.io/main/how-to-jspsych1.html)

## 出来上がりはどんな感じ
　画面の左と右に数字が出ます。安定な収入にするのか、不安定でチャレンジがある収入にするのか参加者に選択してもらう。
そして選択の途中で今の気持ちが聞かれる。
プログラムは参加者の選択と気持ちを記録する。

実験は150試行、そのうち２、３回ごとに「今の気持ちは」が聞かれる。
図表Aの部分は理想です。
![図表](https://www.pnas.org/content/pnas/111/33/12252/F1.large.jpg?width=800&height=600&carousel=1)



## 問題点/debug
　このweb実験に関する修正はここに書かれています。
このweb実験は現在完成していません。

### 4月16日
　教示が曖昧、口頭の説明がないと、参加者が何をするのか、収入がどれか分からない。
150試行をこなす必要があるかどうか、指導教授と検討中(試行を減らす)。
呈示時間の長さは参加者にとって適度かどうか検討中。

## 反省
　jsPsychを使う前に、プログラミングについてRの経験しかありません。
最初は[jspsych](https://www.jspsych.org/)と先生のレジュメを頼りにしてコツコツ作りました。
JavaScriptの経験がなく、OOP(object-orientedprogramming)は何なのかもわかりませんでした。
一年間Erroと戦って気づいたとき、修論に使えるものはほぼ完成しています。

## ありがとう
　このプログラムを作れるには、恩師の指導とある友人のアドバイスに欠かせません。
いつも問題解決ではなく、解決の方向を導いてくれます。
2人のおかけでプログラミングの面白さを味わえました。
いろいろありがとうございました。
