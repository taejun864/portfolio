---
title: 사내 비용 관리 프로그램
description: 사내에서 사용되는 비용 관리 프로그램입니다.
date: "2024-04-01T09:49:32+09:00"
jobDate: 2022/07 - 2022/12
work: [web application]
techs: [TypeScript, Ionic, NestJS, PrismaORM, Docker, PostgreSQL]
thumbnail: expense/expenses.png
---

사내에서 사용되는 비용 관리 프로그램입니다.

프로젝트 규모는 2명으로 제가 맡은 업무는 프론트엔드, 백엔드 개발이었습니다.

## 애플리케이션
사용자는 비용 관리자, 사원의 두 종류의 Role이 있습니다.
  - 사원

    - 출장비, 회의비 등 회사에 청구하는 비용을 등록
    - 월말에 작성 한 비용을 종합하여 리포트를 제출

  - 비용 관리자

    - 제출 된 리포트를 결재
    - 리포트 검토 및 재작성 요청
    - 비용 정보를 일본의 회계 관리 프로그램인 Yayoi에 임포트 할 수 있도록 CSV화

## 사용 기술
프론트엔드는 **TypeScript**로 작성하였으며 **Ionic** 프레임워크를 사용하였습니다.

백엔드도 **TypeScript**로 작성하였으며 **NestJS** 프레임워크를 사용한 Restful API로 개발하였습니다. DBMS는 PostgreSQL을 사용했으며 DB 접속 및 TypeScript의 객체와 매핑을 위해 **PrismaORM**이 사용되었습니다.

개발 된 애플리케이션은 **Docker** 컨테이너화 하여 서비스 했었고 **AWS EKS**로 이전하였습니다.

## 업적
기존 Excel로 작성하여 메일로 송부하는 비용 청구 방식에서 웹 애플리케이션화 하여 문서 작성 시간을 단축 시켰으며 비용 관리자 측에서도 제출 받은 비용 정보를 회계 관리 프로그램에 자동으로 임포트 하는 기능으로 작업 시간을 단축 시켰습니다.


{{<figure src="login.png" caption="로그인 화면">}}

{{<figure src="expenses.png" caption="비용 화면">}}

{{<figure src="reports.png" caption="리포트 화면">}}