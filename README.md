# Rails App

## 概要
Ruby on Railsで作成した簡易ツイートアプリ（CRUD処理を実装）  
参考にした記事：https://qiita.com/kazukimatsumoto/items/14bdff681ec5ddac26d1

## アプリ機能
- ログイン機能
  - メールアドレス・パスワードでのユーザー作成・ログイン
  - ログインしていない場合、ツイート等の閲覧のみに制限
  - ユーザーの一覧表示、詳細情報表示に対応
- ツイート機能
  - ツイートの投稿、編集、削除、一覧表示に対応
  - ツイート投稿では、画像ファイルの添付が可能
- お気に入り機能
  - ツイートのお気に入り登録/解除に対応
- コメント機能
  - ツイートに対するコメントの投稿、編集、削除、一覧表示に対応
- フォロー/フォロワー機能
  - ユーザーに対するフォロー登録/解除に対応
  - フォローされたユーザーにはフォロワー情報を付加

## AWSとの連携
- データベースはAmazon RDS for MySQLに接続
- 投稿画像はAmazon S3に保存

## 実行画面
- ログイン画面  
![ログイン画面](./screnshots/login.png)
- ツイート一覧画面  
![ツイート一覧画面](./screnshots/tweets.png)
- ツイート投稿画面  
![ツイート投稿画面](./screnshots/new_tweet.png)
- ツイート詳細画面  
![ツイート詳細画面](./screnshots/tweet.png)
- コメント一覧画面  
![コメント一覧画面](./screnshots/comments.png)
- コメント詳細画面  
![コメント詳細画面](./screnshots/comment.png)
- ユーザー一覧画面  
![ユーザー一覧画面](./screnshots/users.png)
- ユーザー詳細画面  
![ユーザー詳細画面](./screnshots/user.png)
