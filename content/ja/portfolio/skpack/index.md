---
title: SKPACK ホームページ
description: SKPACK 会社のホームページです。
date: "2024-04-04"
jobDate: 2023/01 - 2023/07
work: [Web Application]
techs: [TypeScript, Angular, NestJS, TypeORM, MySQL]
designs: []
thumbnail: images/skpack/main.png
projectUrl: https://skpack.co.kr
---

SKPACK 会社のホームページです。

プロジェクト人員構成は三人で、私はフロントエンド、バッグエンド開発を担当しました。

以前プロジェクトから設計、コードレビューを担当していただいたPMとサブリーダー兼コード作成を主に担当した私、二人のチームにデザイナーが合流して始めて三人で進行したプロジェクトです。

## アプリケーション

一般使用者用のホームページ画面と管理者用のホームページの内容を管理（内容の追加、修正、削除）ができるアドミンページで構成されています。
アドミンページにはngx-adminテンプレートが使用されました。

## 使用技術

フロントエンドは**TypeScript**で作成し、**Angular**フレームワークが使用されました。

バッグエンドは**TypeScript로**で作成し、**NestJS**フレームワークを使用したRestfulAPIとして開発されました。
**MySQL** DBMSに接続するため**TypeORM**を使用しました。

開発されたアプリケーションは**Docker**コンテナ化してサービスし、以後**AWS EKS**に移転しました。

### ホームページ画面

{{<figure src="/portfolio/images/skpack/main2.png" caption="メイン画面の一部">}}

{{<figure src="/portfolio/images/skpack/products.png" caption="製品紹介画面">}}

{{<figure src="/portfolio/images/skpack/media.png" caption="製品動画画面">}}

{{<figure src="/portfolio/images/skpack/notice.png" caption="お知らせ画面">}}

### アドミン画面

{{<figure src="/portfolio/images/skpack/admin_login.png" caption="ログイン画面">}}

{{<figure src="/portfolio/images/skpack/admin_nav.png" caption="メニュー画面">}}

{{<figure src="/portfolio/images/skpack/admin_product.png" caption="製品画面">}}