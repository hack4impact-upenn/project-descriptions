---
layout: project

summary:
    name: "ProPublica"
    tagline: A data pipeline to aggregate doctor disciplinary actions across the United States

team:
    - year: 2018
      semester: Fall
      pm: Kasra Khadem
      tl: Santiago Buenahora
      developers:
          - Charles Zhang
          - Jasmine Lee
          - Amit Lohe
          - Aruna Prasad
          - Alex Xu
project:
    problem: >
        Doctor disciplinary data is siloed across states. When a doctor moves from one state to another, patients may not receive adequate information regarding their physician's prior disciplinary actions.
    features:
        - Ability to web scrape doctor disciplinary actions in a state
        - Ability to aggregate actions in one central database
        - Ability to store PDFs of disciplinary action information
        - Ability to run scripts periodicly
    technologies:
        - Python
        - Selenium (for web scraping)
        - EC2
        - S3
        - SQLite
    technical_challenges:
        - Building scripts for states with very different days of recording and showing disciplinary actions
        - Removing duplicate data after the script is run each time
    impact: >
        The desired effect is to help aggregate doctor disciplinary data in one central database that can be viewed and analyzed

code:
    github_repo_name: doctor-data-scraper

keywords:
    social_impact_keywords:
        - doctor
        - healthcare
        - physician
        - disciplinary
    tech_keywords:
        - data
        - pipeline
        - scraping

media:
    screenshots:
        - screenshot_caption: Home page
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/m4a/ss01.png"
---
