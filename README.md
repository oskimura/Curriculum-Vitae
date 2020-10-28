# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|oskimura|
|email|oskimura@ gmail.com|

## スキル
### 言語
- C
- C++
- Java
- Scala
- Erlang
- Verilog
- JavaScript

### フレームワーク

- xitrum
- spring

### その他

 言語やフレームワークに限らないスキル。開発手法やプロセス、ツールなど
 
 - プログラミング言語処理系作成 (Yacc/Lex, BEAM)
 - HDLによるCPU作成
 - 関数型言語によるコード設計
 - git (git flowで開発)
 - AWS (EC2 S3 Rout53 ClowdWatch)
 - Atlas (MongoDB)
 - Linux 
 - メッセージパッシングによる並列システム設計
 - 
 
## 言語

- 日本語
  - ネイティブ

## 強み

## やったことはないが興味があるもの
Unityによるゲーム制作
OS作成

## 職務経歴

### 2018/1 - 現在 : モビルス株式会社

職務: サーバサイドエンジニア

#### Line配信ツール

https://mobilus.co.jp/cast

- 言語 Scala JavaScript
- フレームワーク Node.js React express xitrum
- DB MongoDB
- バックエンド AWS(EC2,S3)
お客様のキャンペーンなどで、アンケートを行い、LINEに登録していただきます。
そのお客様にLINEからお知らせを行うのが本製品となります。
- 電話通知機能
お客様に登録頂いだ電話番号からSMS通知を行います。
電話番号は暗号化しており個人情報には配慮しています。

- 電話番号暗号化実装
- LINE 通知APIとの通信実装

- ニックネーム表示機能
オペレーターが操作する時に名前が出ていたのをニックネーム表示するようにしました。

- リファクタリング
  - Lintでフォーマット
  - ユニットテストを追加
  - CI環境を構築
- Reactによるフロントエンド実装
- MongoDBのコレクション設計
- RESTに基づいたAPI設計

前の担当者から引き継ぐ形で、システムの担当を行うという感じでした。
その中でバグ修正や機能追加を行いました。
Lintでフォーマット調整をしたりユニットテストを追加しました。
結果リファクタリングがすすんで行きました。


### 2011/10 - 2017/12: ユミルリンク株式会社 

#### 社内ライブラリ

##### メール暗号化
ErlangでSMIME暗号化を行うためにOpen SSLのAPIをErlangにラッパした。
- 言語 Erlang
- フレームワーク ymirlib
- その他 OpenSSL
- C言語のコードをNIFでErlangにラッパする箇所を実装

##### サーバアラートシステム

自社システムで開発したサーバサイドプログラムにアラートメッセージを発するライブラリを埋め込みます。
このメッセージはSSLで暗号化しています。
この受け取ったメッセージをHTTPサーバから見れるようにしました。

- 言語 Erlang
- フレームワーク Yaws ymirlib
- DB MongoDB
- MonogoDBのコレクション設計
- Yawsによるバックエンド開発

社内サーバのアラート等を記録するシステムがなかったので開発するという状況でした。
コアエンジニアの方と相談しながらシステムを設計実装していきました。
結果無事リリースでき社内で運用しました。Mackerelに置き換わるまで運用されました。
大変だったところはファイルを大量に作る必要があったのですがExt3ではファイルの数の上限が決まっているために止まってしまう問題が発生しました。
インフラの方との協議の結果OS（というか仮想マシン）を入れ直すことにしました。

### 2010/1 - 2011/10: 株式会社Speee

#### Speee platform

Googleの集計したランキングや顧客情報を確認するプラットフォーム
APサーバはJettyと社内システムで作成

- 言語 Java
- フレームワーク Jetty
- DB MySQL

- JavaとJettyによるバックエンド開発

元々Perlで開発されたシステムがあったのですがリプレースするという型で引き継ぎました。
コアエンジニアの方と相談しながら設計実装していきました。
結果無事リリースできました。
大変だった所はDBが大規模だったので、ロックを長期間しないようにSQLやプログラムを工夫する必要がありました。

#### ランキングアラートメール

Googleで集計したランキングで大きな変動があったときに担当営業にメールで知らせる

- 言語 Clojure
- DB MySQL
- Clojureによるクローリング
- MySQLのDB設計


## 課外活動

### 社外プロジェクト
* [アルゴリズム勉強会](https://algorithm.connpass.com/)

### 過去の登壇資料
* [Clean概説](https://www.slideshare.net/oskimura/clean-8554744)

### 執筆歴
* [Erlangで言語処理系作成](https://www.amazon.co.jp/Erlang%E3%81%A7%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E7%B3%BB%E4%BD%9C%E6%88%90-oskimura/dp/4873100593/ref=sr_1_4?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=erlang&qid=1602397288&s=books&sr=1-4)
* [Qiita](https://qiita.com/oskimura)
* [FPGAで4bitCPUをつくる](https://booth.pm/ja/items/1860724)
