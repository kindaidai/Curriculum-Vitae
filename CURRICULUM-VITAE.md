---
stylesheet: https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.10.0/github-markdown.min.css
body_class: markdown-body
css: |-
  .markdown-body { font-size: 16px; }
  .markdown-body pre > code { white-space: pre-wrap; }
---

# 職務経歴書

## 基本情報

| key     | value                                         |
| :------ | :-------------------------------------------- |
| Name    | 金田一 大(Kindaichi Dai)                      |
| github  | [kindaidai](https://github.com/kindaidai)     |
| Twitter | [@kindai_dai](https://twitter.com/kindai_dai) |
| zenn    | [kindaidai](https://zenn.dev/kindaidai)       |
| Qiita   | [kindaidai](https://qiita.com/kindaidai)      |
| note    | [kindai0911](https://note.com/kindai0911)     |

- 1990/09/11 生まれ
- 青森県出身 国立八戸工業高等専門学校 卒業

## スキル

### 言語

- Ruby
- JavaScript, TypeScript

### フレームワーク

- Ruby on Rails
- React
- Next.js

## 強み

### 技術面

- Ruby on Rails, React, Next.js をベースにした開発の設計からテストを含む実装までリードできること
- EC サービスの経験を活かし、エンジニア以外のメンバーのシステム運用を考慮した開発ができること
- チームの DX を常に意識し、同じような作業の自動化、便利になるような SaaS 導入の提案や slack 拡張ができること

### 開発全般

- 敬意を持ってコミュニケーションができ、建設的な意見を言えること
- 機能開発において、十分なヒアリングや時には現場に赴き、ユーザー体験を意識しながら設計、開発ができること

## やったことはないが興味があるもの

- Ruby on Rails 以外のフレームワークを用いたバックエンド開発

<div class="page-break"></div>

## 職務経歴

### 2022/03 - 2025/04 : 株式会社ビビッドガーデン

職務: ソフトウェアエンジニア

[産直EC食べチョク](https://www.tabechoku.com/)の開発に従事し、社員向けの管理画面や生産者向けの管理画面も同時に開発していました。
<br />
食べチョク上でふるさと納税をするために外部連携、自治体向けに新しく管理画面を作りふるさと納税できるようにしました。
<br />
また、新規事業開発で新しいECサービスの立ち上げを担当し、0 -> 1 の開発を経験しました。

<details>
<summary>---詳細---</summary>

#### 食べチョク
[産直EC食べチョク](https://www.tabechoku.com/) の新機能設計・開発(API 含む)・保守・緊急対応
- 友だち招待機能
- SEO対応
- 注文時にプロモーションコード割引をできるようにする
- 生成AIを使って、Zendeskのチケットに優先順位ラベルを自動付与
- dependabotのPRをauto mergeするactions追加
- ギフトカード注文、メッセージ付き注文のソーシャル機能実装
- 同一生産者の別商品を組み合わせた買い切り定期便の実装
- クレジットカード3Dセキュア対応
- etc...

使用した技術
- React, MobX, jotai
- Ruby, Ruby on Rails

#### ふるさと納税
- ふるさと納税注文画面
- 管理画面を用いいた自治体とふるさと納税商品の運用管理
- 外部連携システム
  - 各自治体が利用しているシステムと食べチョクの繋ぎこみ
- 自治体向け管理画面(別システム)

使用した技術
- React, Next.js

#### 新規事業(ECサイト)
- EC、社員向け管理画面、ショップ向け管理画面の実装

使用した技術
- Ruby on Rails, Next.js


</details>


### 2019/02 - 2022/02 : 株式会社キャタル

職務: ソフトウェアエンジニア

ソフトウェアエンジニアとして、2 つのシステム開発に従事していました。フロントエンドは TypeScript、React、Redux、Apollo Client などを用いた開発、サーバーサイドは Ruby、Ruby on Rails を用いて開発をしています。
通常の新規開発・保守の他に、２つのサービスを 1 つに統合する業務を半年かけて行ったり、graphql-ruby を使用してフロントエンドとバックエンドのやりとりを REST から GraphQL API へ移行し、スケールしやすいように整備したりしました。

<details>
<summary>---詳細---</summary>

#### 横断プロジェクト

- pull panda を導入し、アサインされた PR のリマインダーとランダムアサインの仕組みを導入(今は、GitHub cheduled reminders)
- heroku の production 環境の dump データとアセットを、staging、review-apps に適用できるコマンドを作成して、production と同等の環境を用意できる仕組みを整備

#### 自社英語塾学習管理システム

生徒、親、先生、運営スタッフが教室で使用する、学習管理システムの新規開発、保守、運用

- COVID-19 による緊急事態宣言の影響で一括処理バッチ作成
- Ruby のアップグレード対応
- SQL 改善によるパフォーマンス改善

使用した技術

- React, Redux, TypeScript
- Ruby, Ruby on Rails

#### 英作文添削システム

バイリンガルの先生による英作文添削システムの新規開発、保守、運用

- 別々のサービスで稼働していた、バイリンガルの先生による英文添削システムを 1 つのシステムに統合
  - データ移行バッチ作成
  - 必要な機能移植
- 動画アップロードの仕組みを carrierwave から shrine へ移行
- ブラウザから動画を録画できるように整備
- GraphQL, Apollo Client を使った API の整備、開発
- rubocop の設定を横断的に使用できるように gem 化して rubygems へアップロード
- Ruby, Rails のアップグレード対応

使用した技術

- React, Redux, TypeScript, apollo client
- Ruby, Ruby on Rails
  - GraphQL Ruby

</details>

<div class="page-break"></div>

### 2017/11 - 2018/12: エコーズ株式会社

### 2019/04 - 現在: エコーズ株式会社(業務委託)

職務: ソフトウェアエンジニア

サーバーサイドエンジニアとして、Ruby, Ruby on Rails を用いて API の開発、新規機能開発に従事していました。また、画像の動的変換のために ImageFlux を導入したり、画像の非同期投稿処理をできるようにしたりと根幹の機能を任せていただきました。
効率的な SQL の組み方や DB の正規化・ログテーブルの扱いなど、DB 設計について多く学びました。

<details>
<summary>---詳細---</summary>

#### 自社サービス「マンガハック」の設計・開発

[マンガハック](https://mangahack.com/)の新機能設計・開発(API 含む)・保守・緊急対応

- イラスト投稿機能
- 画像投稿非同期処理
- IP 保有企業との協業施策
- iOS, Android 向け内部 API 開発、Swagger UI による API ドキュメント整備
- SNS バズによるサーバー増築などのリクエストスパイク対応

使用した技術

- Ruby, Ruby on Rails
  - sidekiq, shrine, ImageFlux
  </details>

### 2016/12 - 2017/10: 株式会社 Miraie

職務: ソフトウェアエンジニア

サーバーサイドエンジニアとして、Ruby, Ruby on Rails を用いて新規機能開発に従事していました。ログイン機能や CSV ダウンロード・アップロード、RSpce を用いたテストの記述など、Ruby on Rails の基本的な開発を学びました。

<details>
<summary>---詳細---</summary>

#### 社内向けマーケディングシステム開発

- 客先(デジタルマーケティング会社)常駐にて、社内システム開発
  - 自社メディア数値管理システム
  - Google アナリティクスのデータをメディアごとに集積・可視化
  - 独自の計算式でデータ加工、可視化

</details>
