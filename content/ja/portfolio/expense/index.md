---
title: 社内費用管理プログラム
description: 社内で使用する費用管理プログラムです。
date: "2024-04-03"
jobDate: 2022/07 - 2022/12
work: [web application]
techs: [TypeScript, Ionic, NestJS, PrismaORM, Docker, PostgreSQL]
thumbnail: images/expense/expenses.png
---

社内で使用する費用管理プログラムです。

プロジェクト人員構成は二人で、私はフロントエンド、バッグエンド開発を担当しました。

## アプリケーション
使用者は費用管理者、社員の二種類のROLEがあります。
  - 社員

    - 出張費、会議費など会社に請求する費用を登録
    - 月末に作成した費用をまとめてリポートを提出

  - 費用管理者

    - 提出されたリポートを決裁
    - リポート検討および再作成要請
    - 費用情報を会計ソフトの弥生会計にインポートできるようにCSV化

## 使用技術
フロントエンドは**TypeScript**で作成し、**Ionic**フレームワークを使用しました。

バッグエンドも**TypeScript**で作成し、**NestJS**フレームワークを使用したRestful APIとして開発しました。DBMSは**PostgreSQL**を使用し、DB接続に**PrismaORM**が使用されました。

開発されたアプリケーションは**Docker**コンテナ化してサービスし、以後**AWS EKS**に移転しました。

## 業績
既存Excelで作成してメールで送付する費用請求プロセスからウェブアプリケーション化して文書作成時間を短縮し、費用管理者側でも提出された費用情報を会計ソフトにインポートできるようCSVファイル化機能を実装して作業時間を短縮しました。


{{<figure src="/portfolio/images/expense/login.png" caption="ログイン画面">}}

{{<figure src="/portfolio/images/expense/expenses.png" caption="費用画面">}}

{{<figure src="/portfolio/images/expense/reports.png" caption="リポート画面">}}