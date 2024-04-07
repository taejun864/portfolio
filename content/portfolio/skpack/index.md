---
title: SKPACK 홈페이지
description: SKPACK 홈페이지입니다.
date: "2024-04-02T20:02:28+09:00"
jobDate: 2023/01 - 2023/07
work: [Web Application]
techs: [TypeScript, Angular, NestJS, TypeORM, MySQL]
designs: []
thumbnail: skpack/main.png
projectUrl: https://skpack.co.jp
---

SKPACK의 홈페이지입니다.

프로젝트 규모는 3인으로 저는 프론트엔드, 백엔드 개발을 담당했습니다.

이전 프로젝트부터 설계, 코드 리뷰를 담당해 주신 PM과 서브 리더 겸 코드 작성을 주로 한 저 2명의 팀에 디자이너가 합류 해 처음으로 3인으로 진행한 프로젝트입니다.

## 애플리케이션

일반 사용자가 보는 홈페이지 화면과 관리자가 홈페이지의 내용을 관리(내용 추가, 수정, 삭제) 할 수 있는 어드민 페이지로 이루어져 있습니다.
어드민 페이지에는 ngx-admin 템플릿이 사용 되었습니다.

## 사용 기술

프론트엔드는 **TypeScript**로 작성되었으며, **Angular** 프레임워크가 사용 되었습니다.

백엔드는 **TypeScript로** 작성되었으며, **NestJS** 프레임워크를 사용 한 RestfulAPI로 개발되었습니다. 
**MySQL** DBMS에 접속 및 TypeScript 객체와 매핑을 위해 **TypeORM**을 사용하였습니다.

개발 된 애플리케이션은 **Docker** 컨테이너화 하여 서비스 했었고 **AWS EKS**로 이전하였습니다.