---
title: In-house CRM
description: This is CRM web application for in-house.
date: "2024-04-05"
jobDate: 2021/11 - 2022/03, 2023/08 - 2024/01
work: [web application]
techs: [TypeScript, Go, Angular, Fiber, MySQL, PostgreSQL, GORM]
designs: []
thumbnail: images/crm/dashboard.png
---

This is CRM web application for in-house.

This project was completed in development in 2022/03 and major modifications starting from 2023/08 for reflect user feedback.

# 2021 project
The project consisted of two people, and I was in charge of front-end and back-end development.

## Application
The main function is for users (salespeople) to register and manage case information and sales documents related to the case, and to visualize annual and monthly sales information in charts.

## Used skills
Front-end is written in **TypeScript**, and **Angular** framework is used.

Back-end is written in **Go**, and developed as Restful API used **Fiber** framework. 
The DBMS used was **MySQL**, and **GORM** was used for DB connection and object mapping in **Go**.

The developed application was serviced as a **Docker** container.

---------

# 2023 project
The project consisted of six people, 2 people was in charge of frone-end 2 people was in charge of back-end, and I was in charge of overall proejct progress as the project leader.

## Fixes
The UI has been modified for reflect user feedback, and the process for case and document registration has been modified. In order to improve performance during the modification process, we changed from mapping objects in **MySQL** and **Go** using **GORM** to using SQL statements directly. Additionally, considering JSON format support, etc., the DBMS was changed from **MySQL** to **PostgreSQL**.

## Used skills
Front-end is written in **TypeScript**, and **Angular** framework is used.

Back-end is written in **Go**, and developed as Restful API used **fiber** framework. The DBMS used was **PostgreSQL**, migrating the existing **MySQL** data to **PostgreSQL**.

The developed application was serviced in **AWS EKS**.

{{<figure src="/portfolio/images/crm/login.png" caption="Login page">}}

{{<figure src="/portfolio/images/crm/dashboard.png" caption="Dashboard page">}}

{{<figure src="/portfolio/images/crm/deals.png" caption="Case management page">}}