# Tomoya Ueda（上田 友也）

京都在住の Web エンジニア志望です。
PC のオンサイト修理・ヘルプデスク（約 1 年半）と、Zabbix を用いたネットワーク機器の 24 時間監視（約 8 ヶ月）を経験したあと、「守る側」から「作る側」へ移るため、2025 年から PHP / Laravel を中心に Web アプリ開発を学んでいます。

- 得意：バックエンド（Laravel）。フロントは React / Next.js も一通り触っています
- 資格：基本情報技術者、LinuC レベル1（101・102）、EA/J認定 情報セキュリティ技術認定 応用コース テクニカル編　取得
- 学習の進め方：エラーは自分で切り分けて原因を記録する。AI は「実装の代行」ではなく、実装前に方針と理由を出させて自分が理解してから書く使い方をしています。あくまでサポートとして使っています。

---

## 制作物

新しいものが上からとなります。

| # | プロジェクト | 概要 | 主な技術 | 時期 |
|---|---|---|---|---|
| 5 | 店舗紹介サイト（受託・**非公開**） | 知人のお店から依頼を受けて開発。Next.js の公開サイトと Laravel の API・管理画面を分けたヘッドレス構成。AWS S3 への画像アップロード、問い合わせ API のレート制限、年齢確認ゲートなど | PHP 8.4 / Laravel 13 / Next.js 16 / React 19 / TypeScript / MySQL 8.0 / Docker / AWS S3 | 2026/7〜 |
| 4 | [Salon-booing-system-app](https://github.com/taotomo/Salon-booing-system-app) | Hot Pepper Beauty のような美容室の検索・予約サイト。エリア・ジャンル検索、評価順ソート、4 ステップの予約フロー、お気に入り、レビュー、オーナー向け管理画面。他人のデータを操作できないことをテストで確認 | PHP 8.4 / Laravel 13 / React 18 / TypeScript / Inertia.js / MySQL 8.0 / Docker / PHPUnit / Vitest | 2026/4〜7 |
| 3 | [net_shop](https://github.com/taotomo/net_shop) | ショップ開設・商品出品・購入（在庫管理）ができるネットショップ。FormRequest への分離、認可、約 50 ケースの PHPUnit テスト | PHP 8.0 / Laravel 8 / MySQL 8.0 / Docker / PHPUnit | 2026/2〜3 |
| 2 | [time-card-app](https://github.com/taotomo/time-card-app) | 勤怠管理アプリ。出退勤・休憩の打刻、月次カレンダー、修正申請と承認、CSV 出力 | PHP 8.2 / Laravel 10 / MySQL 8.0 / Docker | 2026/1 |
| 1 | [flea-market-app](https://github.com/taotomo/flea-market-app) | フリマアプリ。出品・購入・お気に入り・コメント、Stripe API による決済、メール認証 | PHP 8.2 / Laravel 8 / MySQL 8.0 / Docker / Stripe | 2025/12〜2026/1 |
| 0 | [contact-form-app](https://github.com/taotomo/contact-form-app) | お問い合わせフォーム。Laravel を学び始めたころの最初のアプリ | PHP 8.2 / Laravel 8 / MySQL 8.0 / Docker | 2025/11〜12 |

### 5 の店舗紹介サイトが非公開である理由

実在する店舗からの受託案件で、コードに店舗の連絡先・スタッフ情報などが含まれるため、リポジトリは非公開にしています。

---

## 技術スタック

| 分類 | 使ったもの |
|---|---|
| バックエンド | PHP 8.0〜8.4、Laravel 8 / 10 / 13 |
| フロントエンド | React 18 / 19、TypeScript、Next.js 16（App Router）、Inertia.js、Tailwind CSS、Blade |
| データベース | MySQL 8.0 |
| インフラ・環境 | Docker Compose（Nginx / PHP-FPM / MySQL）、AWS S3、Linux |
| テスト | PHPUnit、Vitest |
| ツール | Git / GitHub、VS Code、GitHub Copilot、Claude Code |

---

## 連絡先

- Email: toatomo2913@gmail.com
