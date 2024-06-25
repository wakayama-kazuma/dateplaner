# DatePlaner
## ■サービス概要
オススメのデートスポットや知っている穴場スポットから1日デートプランを作成し共有するサービスです。
もちろんデートだけでなく観光にオススメな穴場スポットやランチスポットなどオススメスポットであれば、どんなコンセプトでも投稿できます！

## ■ このサービスへの思い・作りたい理由
元々一人暮らしだったため、おうちデートが多くあまり気になりませんでしたが、実家に帰ると外でのデートが多くなり１日のデートプランを考えるのが割と大変だと感じました。
そのため投稿されたデートプランをもとに計画を練ったり穴場スポットを知れたら便利だと思いました。


## ■ ユーザー層について
* デートプランを考えるのが面倒な人
* 穴場スポットを知りたい人

## ■ サービスの利用イメージ
気になる投稿をもとに計画を練り実行。
その後そのプラン投稿することで自分のストックとして扱うことができ他の人も参考にすることができる。

## ■ ユーザーの獲得について
SNSを活用する：twitterで投稿できるようにする

## ■ サービスの差別化ポイント・推しポイント
デートや穴場スポットを紹介する場はあるがデートプランそのものを投稿する場は見かけない

## ■技術スタック
 バックエンド
* Ruby on Rails
* Node.js

フロントエンド
* CSS tailwind

デプロイ
* Heroku

データベース
* PostgreSQL
* AWS

API
* Google Maps API


## ■ 機能候補
### MVPリリース
* ユーザー登録機能
* 簡易ログイン・ログアウト機能
* ログイン・ログアウト機能
* Googleアカウントログイン・ログアウト機能
* デート、穴場スポット新規登録・編集機能
* キーワード検索機能
* モデルコース新規作成・編集機能
* スポットごとの滞在時間・移動手段設定機能
* プロフィール表示・編集機能
* いいね機能
* お気に入り機能・お気に入り一覧
* 自分の投稿履歴機能
* Twitter共有機能
* * 一日のスケジュールをタイムライン形式で表示

### 本リリース
* オートコンプリート検索・絞り込み検索機能
* 観光地・My穴場スポットの詳細ページにGoogleMap表示機能



■データ
・穴場スポットのデータに関しては自身や周りの情報をもとに30ほど入れておく

■プラン
・ユーザーフロー
1. ユーザーにログイン（登録）してもらう、
2. ユーザーが訪れたいスポットを検索・選択
3. スポットの訪問順序と滞在時間を設定(移動手段)
5. スポット間のルートがGoogle Maps上に表示
6. 各ルートの移動時間、距離を確認

## ■画面遷移図
https://www.figma.com/design/0jCGjADTj2QiUFyaaNINRh/%E7%84%A1%E9%A1%8C?node-id=0-1&t=BiA9G6MfDHHlv07R-0

### READMEに記載した機能
- [ ] ユーザー登録機能
- [ ] ログイン機能
- [ ] 検索機能
- [ ] デートプラン作成機能
- [ ] プロフィール機能 

