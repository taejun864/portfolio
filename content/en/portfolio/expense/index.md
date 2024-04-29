---
title: In-house expense system
description: Expense system used in-house.
date: "2024-04-03"
jobDate: 2022/07 - 2022/12
work: [web application]
techs: [TypeScript, Ionic, NestJS, PrismaORM, Docker, PostgreSQL]
thumbnail: images/expense/expenses.png
---

This is expense system used in-house.

The project consisted of two people, and I was in charge of front-end and back-end development.

## Application
There is two user Roles; Cost manager and User.

  - User

    - Register expenses charged to the company, such as business trip expenses and meeting expenses
    - Submit a report by compiling the expenses prepared at the end of the month

  - Cost manager

    - Approve the submitted report
    - Request for report review and rewriting
    - Convert cost information to CSV so it can be imported into Yayoi, a Japanese accounting management program

## Used skills
Front-end is written in **TypeScript**, and **Ionic** framework is used.

Back-end also written in **TypeScript**, and developed as Restful API used **NestJS** framework. 
The DBMS used was **PostgreSQL**, and **PrismaORM** was used for DB connection and object mapping in **TypeScript**.

The developed application was serviced as a **Docker** container and was transferred to **AWS EKS**.

## Achievements
The document creation time has been shortened by converting the existing expense billing method of writing in Excel and sending it by email into a web application, and providing export to csv file function so that the cost manager can import the submitted cost information into the accounting management program, thereby reducing work time.


{{<figure src="/portfolio/images/expense/login.png" caption="Login page">}}

{{<figure src="/portfolio/images/expense/expenses.png" caption="Expenses page">}}

{{<figure src="/portfolio/images/expense/reports.png" caption="Reports page">}}