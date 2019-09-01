---
layout: project

summary:
    name: Giving Project Volunteer and Donation Management Tool
    tagline: Streamlining volunteer and donation management for the Bread and Roses Community Fund

team:
    - year: 2018
      semester: Spring
      pm: Victor Chien
      tl: Suzanne Knop
      developers:
          - Hunter Lightman
          - Jasmine Lee

client:
    - name: Bread and Roses Community Fund
      description: >
         The Bread and Roses Community Fund of Philadelphia recruits a diverse cohort of volunteers every semester to raise money through the volunteers' connections for their Giving Project. Using the collected funds, Bread and Roses sponsors socially impactful community events and initiatives.
      website_url: https://breadrosesfund.org/

project:
    problem: >
         Every semester, Bread and Roses has to source and manage hundreds of volunteers. This is not an easy task, given the fact that there are only a handful of people to handle this. Similarly, volunteers have to track multiple donors and donations, in addition to constantly updating Bread and Roses management on their own progress.
    features:
        - A volunteer dashboard displaying important metrics (ex. total number of donations received, total amount raised by the cohort, etc.)
        - A drag and drop interface for keeping track of donor/donation progress (similar to Asana or Trello)
        - A volunteer management and filtering tool (similar to excel but with built in filtering capabilities - ethnicity, gender, sexual orientation, cohort, etc.)
        - Ability to download volunteers into an external spreadsheet, the ability to view the demographic data of a cohort in graph form.
    technologies:
        - Flask
        - JavaScript
        - HTML
        - CSS
        - Heroku
    technical_challenges:
        - Creating graphs
        - Aggregating data for metrics
        - Creating a highly interactive drag and drop interface
        - Verification flow for a donation
        - Downloading data onto an external excel spreadsheet
    impact: >
       This applications helps streamline volunteer recruiting for Bread and Roses. It also makes it easier for volunteers to manage and track their donors/donations. By saving time on both sides, Bread and Roses can raise more money, recruit multiple cohorts per semester, and drive greater impact in the Philly community.

code:
    github_repo_name: bread-and-roses

keywords:
    social_impact_keywords:
        - volunteer
        - volunteering
        - donations
        - donation
        - donors
        - funding
        - community
    tech_keywords:
        - graphing
        - filtering
        - csv creation
        - api

media:
    screenshots:
        - screenshot_caption: Bread and Roses 1
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/bread-and-roses/ss01.png"
        - screenshot_caption: Bread and Roses 2
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/bread-and-roses/ss02.png"
        - screenshot_caption: Bread and Roses 3
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/bread-and-roses/ss03.png"
        - screenshot_caption: Bread and Roses 4
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/bread-and-roses/ss04.png"
---