# easy-nyaaan
卒論発表中にゃーんって呟きたくない?
呟きたいよね?

## デモ
[Demo Movie Tweet](https://twitter.com/gonmoec/status/834660172140158976)

## makeあれこれ
* C++11くらい
* libcurl,liboauth使ってる
* boostも使ってる

## 実行あれこれ
* ./easy-nyaaan startで開始
* ./easy-nyaaan keytestでデバイスからの入力をテストできる
* ./easy-nyaaan devicesでデバイス名検索  

(udevの設定を適切に行なっていない場合はrootで実行)

## 設定あれこれ
main.confに
1. TwitterAPIのいろいろを書く
2. 入力デバイス名を調べて書く
3. 入力テストをしてkey="呟きたい内容"って書く(同時に複数の信号が出る場合は他のボタンを押したときにはない特徴的なキーを選択する)

## 動作環境あれこれ
* Linux
