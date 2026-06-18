# Friend-AI

## 概要

Friend-AIは、単層パーセプトロンのJavaScriptライブラリです。
現在、入力２個にのみ対応しております。
Step関数を使用しております。
MITライセンス使用、ご注意ください。

## 構文

取得

`const ai = new FriendAi();`

データセット

`ai.dataSet(input, answer);`

* 教師データは、二次元配列として、直書きの上、代入してください。

学習

`ai.train(epochTime, lr);`;

* epochTime = 学習ループ数, lr = 学習率

推論

`const result = ai.inference(input1, input2);`

* inputは、推論する際の入力２つです。
* 推論結果をreturnするため、変数に入れることをおすすめします。

## 使い方

htmlファイルに以下を記入してください。

`
