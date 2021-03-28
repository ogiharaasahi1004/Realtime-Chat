# Realtime-Chat

## サービス概要

![Web アルビレックス新潟 トップ](https://i.gyazo.com/33338cc4841856b1e2b6faca8e4d7096.png)

スポーツ好きほど熱狂的なファンはいません。私は自ら積極的に学んだ知識を使って、僕はその力を地方の盛り上げるために使いたいと思い、製作しました。

今も新潟を盛り上げている、新潟アルビレックスのサポーターがさらに交流し、意見交換や内容を共有することができるアプリです。

***
## 作る上で意識した事

一つ一つの機能自体はいたってシンプルなものばかりであり、画期的で面白みのある作品かどうかと問われればあまり自信はありません。

しかしながら、Rails最大の強みでもある「MVCアーキテクチャ」の概念にひたすら忠実に従い、何よりも基本を意識した構成を心掛けております。

## 制作したきっかけ
アルビレックス新潟サポーターが有料のファンクラブより、無料で気軽にサポーター同士がつながることができる場所が欲しかったからです。

僕も１２年間以上スポーツを続けているスポーツ好きなので気持ちがわかるのですが、スポーツが好きな人は、その日の試合のお話やチームの状況を、すぐ知りたいし、思いを共有したいし、ヒトと繋がりたい思いが非常に強いです。

だからこのようなアプリ（繋がれる場所）があれば、他のスポーツ好きの人が、簡単に気軽に、繋がれるようになりたいと考えたからです。

ユーザー間で情報共有する事でスポーツ好きにありがちな「承認欲求（スポーツ好きである事に対する誇り）」の実現を目指します。

*さらにスポーツ好きの盛り上がりが、地方を盛り上げることにも良い影響を与えると考えたからです。*
***
## 重視した点
- １番に、地方の課題解決をテーマの中心にしました。
- 僕も地方に住んでいるからわかりますが、顧客の悩みと市場のニーズを解決するために作りました。
- サービス自体は、なるべくシンプルに作り、基本に忠実に作り、動作が軽いことを大切にしました。
- フォロー機能でユーザー同士が繋がり合い、いいね機能でお互いの投稿を評価し合ったり、想いを共有するために考えを文字で投稿できるようにしました。
- 動作確認を、機能ごとと全体の動作確認も行う点をとても大切にしました。

　
## 技術内容
- フレームワーク:Ruby on Rails（ '5.2.2'）
- DB: 'mysql2', '>= 0.4.4', '< 0.6.0'
- DB：PostgreSQL (本番環境)
- バージョン管理:Git
- インフラ:Heroku
- Webサーバ:puma('3.11')
- スタイルシート:sass-rails', '~> 5.0'
- パスワードセキュリティ:'bcrypt', '~> 3.1.7'

***
## URL
https://web-albirex.herokuapp.com/

テストユーザーアカウント

メールアドレス：test@example.com
パスワード：test
***

# 開発環境
- Ruby  2.5.3
- Rails 5.2.2

***

# サイトマップ
![Web アルビレックス新潟 サイトマップ](https://i.gyazo.com/a7171d1378f57f0da9730798d73df744.png)
***

# ER図
![Web アルビレックス新潟 ER図](https://i.gyazo.com/e56bf80a5b864b25922db55d96f5d9c6.png)
***

# 実装した各種機能

『記事関連』
- 記事一覧表示機能
- 詳細表示機能
- 記事投稿機能
- 記事削除機能
- エラーメッセージ表示機能
- お気に入り機能（いいね機能）
- ヘージネーション機能（kaminari）

『ユーザー関連』
- ユーサー登録機能
- ロクイン/ログアウト機能
- ユーサーフォロー機能
- DBテーフルのリレーション機能
***

## トップページ（ログイン前）
![Web アルビレックス新潟 トップページ（ログイン前）](https://i.gyazo.com/c13b0e701cb2b78b1bb93f53026eae59.jpg)

## トップページ（ログイン後）
![Web アルビレックス新潟 トップページ（ログイン後）](https://i.gyazo.com/54cdebe369d29841ed3e68a8982fec0d.png)

## ユーザー登録ページ
![Web アルビレックス新潟 ユーザー登録ページ](https://i.gyazo.com/b6ff55c14a9fcb6e4183f13b5720e5d0.png)

## ログインページ
![Web アルビレックス新潟 ログインページ](https://i.gyazo.com/c04f16194b0ce83a348964968909f729.png)

## 投稿一覧ページ
![Web アルビレックス新潟 投稿一覧ページ](https://i.gyazo.com/ba9a21d2b6c80ebca27471c814174b29.png)

## フォロー一覧ページ
![Web アルビレックス新潟 フォロー一覧ページ](https://i.gyazo.com/71e5e8004b6f633bd6e0367a8ef545c9.png)

## フォロワー一覧ページ
![Web アルビレックス新潟 フォロワー一覧ページ](https://i.gyazo.com/824f8a823e279a6561af042bb726a51d.png)

## お気に入り一覧ページ
![Web アルビレックス新潟 お気に入り一覧ページ](https://i.gyazo.com/91e4d5e0ab0ff853fe60d6265d8a9873.png)

## ユーザー詳細ページ
![Web アルビレックス新潟 ユーザー詳細ページ](https://i.gyazo.com/ba9a21d2b6c80ebca27471c814174b29.png)


# 作成者の自己紹介

新潟大学工学部 新３年　荻原朝飛（２０歳）

*将来の夢 : 地方に全力で貢献する、ユーザーに喜んでもらえるエンジニアになること。*

- 得意な分野: 
チーム活動、コミュニケーション、プレゼンテーション
- スキルセット: 
HTML/CSS、Ruby、JavaScript、Firebase、MySQL、Git、GitHub
- やりたいこと: 
ヒトとヒトが繋がれる場所を作りたかった。
- Ruby選んだ理由: 
まず、Webアプリケーション開発の知見と動的型付け言語の知見をつける。
- Goをやる理由: 
今、最も価値の高い静的型付け言語は「Go」だと思うから。
- 目標: 
静的型付け言語の知見とマイクロサービス方式での開発手法に関する知見をつけて、お客さまを喜んでもらえるエンジニアになる。

『想いが伝わると非常に嬉しいです！ありがとうございました！』

***

