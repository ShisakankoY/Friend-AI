# Friend-AI

// Japanese

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

`<script src="https://shisakankoy.github.io/Friend-AI/friend-ai.js">`;

// English

## Overview

Friend-AI is a JavaScript library for a single-layer perceptron.

Currently, it only supports two inputs.

It uses the Step function.

Please note that it uses the MIT license.


## Syntax

Data Acquisition

`const ai = new FriendAi();`

Dataset

`ai.dataSet(input, answer);`

* Please hardcode the training data as a two-dimensional array and assign it.

Training

`ai.train(epochTime, lr);`;

* epochTime = number of training loops, lr = learning rate

Inference

`const result = ai.inference(input1, input2);`

* `input` are the two inputs for inference.

* It is recommended to store the inference result in a variable to return it.


## Usage

Please add the following to your HTML file.


`<script src="https://shisakankoy.github.io/Friend-AI/friend-ai.js">`;
