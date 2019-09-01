---
layout: project

summary:
    name: Philly Tenancy Tracker
    tagline: Helping low-income and at-risk tenants in Philly keep track of important information related to their tenancy in order to fight against unjust evictions

team:
    - year: 2018
      semester: Fall
      pm: Victor Chien
      developers:
          - Jediah Katz
          - Hana Pearlman
          - Andrew Shen
          - Jamie Wang
          - Annie Su
          - Roberta Nin Feliz
          - Moksh Jawa

client:
    - name: Community Legal Services of Philadelphia
      description: >
         Founded in 1966 by the Philadelphia Bar Association, Community Legal Services (CLS) has provided free civil legal assistance to more than one million low-income Philadelphians. Approximately 10,000 clients were represented by CLS in the past year.
      website_url: https://clsphila.org/

project:
    problem: >
         Thousands of at-risk and low-income tenants in Philadelphia have been victims of wrongful/unjust evictions. A primary reason for this is that many of these tenants have difficulty keeping track of critical pieces of information related to their tenancy (payments, repairs, complaints) that would be paramount in defending them against such evictions.
    features:
        - Management system for rent payments
        - Management system for issues (repair requests, complaints)
        - Ability to send any of the above information via email
        - Ability to view rent agreement
        - Checklist for items tenants need to prepare for court.
    technologies:
        - React
        - MongoDB
        - AWS
        - AWS S3
        - Heroku
    technical_challenges:
        - Learning and using a new stack (React, MongoDB, AWS, AWS S3)
        - Storing images on AWS S3
        - Backend authentication of various actions
    impact: >
       With easy access to important tenancy information through this application, tenants can better defend themselves against wrongful evictions in court and keep their homes. 

code:
    github_repo_name: cls-philly-tenant

keywords:
    social_impact_keywords:
        - justice
        - court
        - protect
    tech_keywords:
        - logging

media:
    screenshots:
        - screenshot_caption: CLS Philly Tenant 1
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/cls-philly-tenant/ss01.gif"
        - screenshot_caption: CLS Philly Tenant 2
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/cls-philly-tenant/ss02.png"
        - screenshot_caption: CLS Philly Tenant 3
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/cls-philly-tenant/ss03.gif"
        - screenshot_caption: CLS Philly Tenant 4
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/cls-philly-tenant/ss04.gif"
        - screenshot_caption: CLS Philly Tenant 5
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/cls-philly-tenant/ss05.png"
---