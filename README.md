# README

## ■ サービス概要

- 喫煙者がタバコを吸いながら心情や考えを投稿するサービスです。
- 非喫煙者も喫煙者の考えに触れ、異なる視点から世界観を広げることができます。

## ■ このサービスへの思い・作りたい理由

喫煙者がタバコを吸っているときに何を考えているか、周りの人にはあまり知られていません。家族や友人が煙草をふかしながら、ふと漏らす言葉に心を揺さぶられることがありました。このアプリを通じて、喫煙中のリラックスした瞬間に生まれる考えや思いを気軽に共有できる場を作りたいと思いました。

## ■ ユーザー層について

- **喫煙者**：自分の心情や考えを一服しながら気軽に共有したい方。
- **非喫煙者**：喫煙者の思考や気持ちを理解し、新たな視点を得たい方。

この2つの層を対象にしたのは、喫煙者には共感や安心感を、非喫煙者には新しい発見や他者理解の機会を提供できるからです。

## ■ サービスの利用イメージ

- 喫煙者はアプリを開き、タバコを吸いながらその瞬間に思ったことや感じたこと投稿します。掲示板内でユーザーが自由に心情を投稿できる機能を作ることで、交流を深められる環境を提供したいと考えております。
- 禁煙を考えているユーザーも、同じ目的で利用しているユーザーとコミュニティを通じて日々を分かち合い、前向きな気持ちで禁煙達成を目標に利用していただけたらと考えております。
- 非喫煙者は喫煙者の投稿を見て、どのようなことを考えているのかを知ることができます。これにより、喫煙の文化や思考の広がりを感じてもらうことができると思います。

## ■ ユーザーの獲得について

- **喫煙者**：Xにてシェア・ユーザー間での招待など
- **非喫煙者**：Xにてシェア・ユーザー間での招待など

## ■ サービスの差別化ポイント・推しポイント

**差別化ポイント:**

- 既存のSNSでは、喫煙者がタバコに関して自由に話す場が少ないですが、このアプリは喫煙中の瞬間に特化したサービスです。
- 禁煙だけのためのアプリはたくさん存在しますが、禁煙に失敗したらそこで一旦アプリの利用をやめてしまう方が多いかと思われます。このアプリは禁煙のためだけのアプリではないので、失敗してしまってもまた禁煙しようと踏み出すまでの期間、愛用していただけるのではと考えております。

**推しポイント:**

- 物思いに耽ったつぶやきが見れるだけではなく、喫煙後のすっきりとしたリフレッシュされた気持ちを言語化して呟いていただくことで、活気が溢れるかと思われます。
- ユーザー名の後ろに吸っているタバコの銘柄名を入れることで、新作のフレーバーが登場したりした際に似た味覚の方の意見を知ることができるので参考になりやすい。
- 非喫煙者が異なる文化を理解する場を得ることが大きな魅力です。

## ■ 機能候補

- **MVPリリース時**:
    - ユーザー登録（sorcery）
    - ログイン機能（ユーザー名とemailとパスワード）
    - 掲示板一覧
    - コメント投稿機能
    - 非喫煙者の閲覧モード
- **本リリースまで**:
  - ユーザー定着のため
  - いいね機能(turbo)
  - 銘柄ごとのランキングやバッジシステム（一例ですが、これまでに吸ってきた銘柄の数のランキングや、アプリ継続日数ランキング、いいね・ブクマランキング・バッジシステムなど）
  - コミュニティを探しやすくするため、銘柄ごとの絞り込み検索機能(Ransack)
- Googleログイン機能
- X共有機能

## ■ 機能の実装方針予定

| category | 技術 |
| --- | --- |
| フロントエンド | Rails 7.1.3.2 (Hotwire/Turbo), TailwindCSS, DaisyUI |
| バックエンド | Rails 7.1.3.2 (Ruby 3.2.2 ) |
| データベース | Mysql2 |
| 認証 | sorcery |
| 環境構築 | Docker |
| インフラ | heroku |
| Web API | 未定 |
