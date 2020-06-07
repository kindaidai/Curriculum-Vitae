## Markdown to PDF
```shell
$ git clone git@github.com:kindaidai/Curriculum-Vitae.git
$ cd Curriculum-Vitae
$ yarn
$ md-to-pdf CURRICULUM-VITAE.md
```

# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|金田一 大(Kindaichi Dai)|
|Blog|[kindai-dai](http://kindai-dai.hatenablog.com/)|
|Qiita|[kindaidai](https://qiita.com/kindaidai)|
|Twitter|[@kindai_dai](https://twitter.com/kindai_dai)|

- 1990/09/11 生まれ
- 青森県出身 八戸高専卒

## スキル
### 言語
- 実務経験有り
  - Ruby
  - JavaScript
  - TypeScript
  - Python
- 実務経験はないが趣味で触った程度
  - Golang
### フレームワーク
- Ruby on Rails
- React
### インフラ
0からの構築経験はないですが、負荷対応や開発する上で連携が必要になって利用したことがあるものです。
- AWS(EC2, ELB, RDS, ElasticCache, S3, CloudFront, Lambda, CloudWatch)
- heroku
### ミドルウェア
- RDB(MySQL, PostgreSQL)
- redis
- Nginx
### CI
- CircleCI
- Wercker
### Editor
- VSCode
- vim

## 強み
- 特に新規機能開発は、十分なヒアリングや周りの意見を聞いてから、設計に落とし込むことを常に心がげています
- 必要なテストコードを必ず書いて、ライブラリのアップデートやコード変更をしやすくなるような開発をすることができます
- チームのDXを常に意識しています

## 最近の趣味
フロントエンドの知識をアップデートするために、パーソナルサイトをNextjsを使って構築中(開発し始めたばかりです...)
できればブログの仕組みもヘッドレスCMSなどを使って構築してみる予定
https://github.com/kindaidai/kindaidaidev

## 職務経歴

### 2019/02 - 現在 : 株式会社キャタル

職務: ソフトウェアエンジニア

ソフトウェアエンジニアとして、2つのシステム開発に従事していました。フロントエンドはTypeScript、React、Redux、Apollo Clientなどを用いた開発、サーバーサイドはRuby、Ruby on Railsを用いて開発をしていました。また、２つのサービスを1つに統合する業務を半年かけて任せてもらいました。

#### 横断プロジェクト
- pull pandaを導入し、アサインされたPRのリマインダーとランダムアサインの仕組みを導入
- herokuのproduction環境のdumpデータとアセットを、staging、review-appsに適用できるコマンドを作成して、productionと同等の環境を用意できる仕組みを整備

#### 自社英語塾学習管理システム
生徒、親、先生、運営スタッフが教室で使用する、学習管理システムの新規開発、保守、運用
- COVID-19による緊急事態宣言の影響で一括処理バッチ作成
- Rubyのアップグレード対応
- SQL改善によるパフォーマンス改善

使用した技術
- React, Redux, TypeScript
- Ruby, Ruby on Rails

#### 英作文添削システム
バイリンガルの先生による英作文添削システムの新規開発、保守、運用
- 別々のサービスで稼働していた、バイリンガルの先生による英文添削システムを1つのシステムに統合
  - データ移行バッチ作成
  - 必要な機能移植
- 動画アップロードの仕組みをcarrierwaveからshrineへ移行
- ブラウザから動画を録画できるように整備
- GraphQL, Apollo Clientを使ったAPIの整備、開発
- rubocopの設定を横断的に使用できるようにgem化してrubygemsへアップロード
- Ruby, Railsのアップグレード対応

使用した技術
- React, Redux, TypeScript, apollo client
- Ruby, Ruby on Rails
  - GraphQL Ruby

### 2017/11 - 2018/12: エコーズ株式会社
### 2019/04 - 現在: エコーズ株式会社(業務委託)

職務: サーバーサイドエンジニア

サーバーサイドエンジニアとして、Ruby, Ruby on Railsを用いてAPIの開発、新規機能開発に従事していました。また、画像の動的変換のためにImageFluxを導入したり、画像の非同期投稿処理をできるようにしたりと根幹の機能を任せていただきました。
効率的なSQLの組み方やDBの正規化・ログテーブルの扱いなど、DB設計について多く学びました。

#### 自社サービス「マンガハック」の設計・開発

[マンガハック](https://mangahack.com/)の新機能設計・開発(API含む)・保守・緊急対応
- イラスト投稿機能
- 画像投稿非同期処理
- IP保有企業との協業施策
- iOS, Android向け内部API開発、Swagger UIによるAPIドキュメント整備
- SNSバズによるサーバー増築などのリクエストスパイク対応

使用した技術
- Ruby, Ruby on Rails
  - sidekiq, shrine, ImageFlux

### 2016/12 - 2017/10: 株式会社Miraie

職務: サーバーサイドエンジニア

サーバーサイドエンジニアとして、Ruby, Ruby on Rails を用いて新規機能開発に従事していました。ログイン機能やCSVダウンロード・アップロード、RSpceを用いたテストの記述など、Ruby on Railsの基本的な開発を学びました。

#### 社内向けマーケディングシステム開発
- 客先(デジタルマーケティング会社)常駐にて、社内システム開発
  - 自社メディア数値管理システム
  - Googleアナリティクスのデータをメディアごとに集積・可視化
  - 独自の計算式でデータ加工、可視化
