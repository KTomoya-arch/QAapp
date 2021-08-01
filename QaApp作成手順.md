## Railsアプリの初0⇨１実装
Railsアプリの雛形を作成 

rails new QaApp --d postgresql 


データベースを作成

bin/rails db:create


ここまででアプリケーション作成の下準備が完了

### テーブル/モデル開発手順
- 全体的な設計・下準備⇨機能に関連するモデルを用意する
- 今回作成するテーブルは以下の３つ

1、 ユーザー(テーブル名：users)

2、質問(テーブル名：posts)

3、 回答(テーブル名：answers)

モデルの雛形を作成する(マイグレーションファイルを作成する)

DBへ反映させる(rails db:migrate)

### コントローラとビューを作成
bin/rails g controller コントローラ名　アクション名

今回作成するコントローラは

1、usercontroller

２、sessioncontroller

３、questioncontroller

４、answercontroller

５、admin/usercontroller

６、admin/questioncontroller

