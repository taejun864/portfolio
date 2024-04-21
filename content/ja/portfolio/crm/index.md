---
title: 社内 CRM
description: 社内で使用するCRMウェブアプリケーションです。
date: "2024-04-05"
jobDate: 2021/11 - 2022/03, 2023/08 - 2024/01
work: [web application]
techs: [TypeScript, Go, Angular, Fiber, MySQL, PostgreSQL, GORM]
designs: []
thumbnail: images/crm/dashboard.png
---

社内で使用するCRMウェブアプリケーションです。

2022/03 개발을 완료하여 사용 하던 중 사용자의 의견을 받아 2023/08 부터 대규모로 수정을 진행 한 프로젝트입니다.
2022/03開発を完了して使用中、使用者の意見を聞いて、2023/08から修正を行ったプロジェクトです。

# 2021 プロジェクト
プロジェクト人員構成は二人で、私はフロントエンド、バッグエンド開発を担当しました。

## アプリケーション
使用者（営業社員）が案件情報および案件に関する営業文書を登録、管理して年、月別売り上げ情報をチャートで視覚化するのが主な機能です。

## 使用技術
フロントエンドは**TypeScript**で作成して、**Angular**フレームワークを使用しました。

バッグエンドは**Go**で作成して、**Fiber**フレームワークを使用したRestful APIとして開発しました。**MySQL** DBMSと **Go** オブジェクトとのマッピングをするため**GORM**を使用しました。

開発したアプリケーションは**Docker**コンテナ化してサービスしました。

---------

# 2023 プロジェクト
プロジェクト人員構成は６人で、二人がフロントエンド、二人がバッグエンドを担当し、私はプロジェクトリーダーとして全体的プロジェクト進行を担当しました。

## 修正事項
使用者の意見を聞き、UIの修正、案件および文書登録のプロセスが修正されました。修正作業中、パフォーマンス向上のため**GORM**を使用して**MySQL**と**Go**のオブジェクトをマッピングする方法からSQLステートメントを直接使用する方法に変更しました。なお、JSON形式の使用などのため、DBMSを**MySQL**から**PostgreSQL**に変更しました。

## 使用技術
フロントエンドは**TypeScript**で作成して、**Angular**フレームワークを使用しました。

バッグエンドは**Go**で作成されまして、**Fiber**フレームワークを使用したRestful APIです。DBMSは既存**MySQL**のデータを**PostgreSQL**にマイグレーションして使用しました。

開発されたアプリケーションは**AWS EKS**でサービスしました。

{{<figure src="/portfolio/images/crm/login.png" caption="ログイン画面">}}

{{<figure src="/portfolio/images/crm/dashboard.png" caption="ダッシュボード画面">}}

{{<figure src="/portfolio/images/crm/deals.png" caption="案件管理画面">}}