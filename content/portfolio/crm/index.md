---
title: 사내 CRM
description: 사내에서 사용하는 CRM 웹 애플리케이션입니다.
date: "2024-04-05"
jobDate: 2021/11 - 2022/03, 2023/08 - 2024/01
work: [web application]
techs: [TypeScript, Go, Angular, Fiber, MySQL, PostgreSQL, GORM]
designs: []
thumbnail: portfolio/crm/dashboard.png
---

사내에서 사용하는 CRM 웹 애플리케이션입니다.

2022/03 개발을 완료하여 사용 하던 중 사용자의 의견을 받아 2023/08 부터 대규모로 수정을 진행 한 프로젝트입니다.

# 2021 프로젝트
프로젝트 규모는 2명으로 저는 프론트엔드, 백엔드 개발을 담당하였습니다.

## 애플리케이션
사용자(영업사원)가 안건 정보 및 안건에 관한 영업 문서를 등록, 관리하며 년, 월 매출 정보를 차트로 시각화 하는 것이 주 기능입니다.

## 사용 기술
프론트엔드는 **TypeScript**로 작성하였으며, **Angular** 프레임워크를 사용하였습니다.

백엔드는 **Go**로 작성하였으며, **Fiber** 프레임워크를 사용 한 Restful API로 개발되었습니다. **MySQL** DBMS와 **Go** 객체의 매핑을 위해 **GORM**이 사용되었습니다.

개발 된 애플리케이션은 **Docker** 컨테이너화 하여 서비스 했습니다.

---------

# 2023 프로젝트
프로젝트 규모는 6명으로 2명이 프론트엔드, 2명이 백엔드를 담당하였으며 저는 프로젝트 리더를 맡아 전체적인 프로젝트 진행을 담당하였습니다.

## 수정 사항
사용자의 의견을 받아 UI가 수정 되었으며, 안건 및 문서 등록의 프로세스가 수정 되었습니다. 수정 과정에서 퍼포먼스 향상을 위해 **GORM**을 이용해 **MySQL**과 **Go**의 객체를 매핑하는 방식에서 SQL문을 직접 사용하는 방식으로 수정하였습니다. 또한 JSON 형식 지원 등을 고려하여 DBMS를 **MySQL**에서 **PostgreSQL**로 변경하였습니다.

## 사용 기술
프론트엔드는 **TypeScript**로 작성 하였으며, **Angular** 프레임워크를 사용하였습니다.

백엔드는 **Go**로 작성 하였으며, **Fiber** 프레임워크를 사용 한 Restful API입니다. DBMS는 기존 **MySQL**의 데이터를 **PostgreSQL**로 마이그레이션 하여 사용하였습니다.

개발 된 애플리케이션은 **AWS EKS**에서 서비스 했습니다.

{{<figure src="login.png" caption="로그인 화면">}}

{{<figure src="dashboard.png" caption="대시보드 화면">}}

{{<figure src="deals.png" caption="안건 관리 화면">}}