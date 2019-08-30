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

client:
    - name: ProPublica
      description: >
        ProPublica is an American nonprofit organization based in New York City. It is a nonprofit newsroom that aims to produce investigative journalism in the public interest.
      website_url: https://www.propublica.org

project:
    problem: >
        Doctor disciplinary data is siloed across states. When a doctor is disciplined in one state, the action is only reported by the state's medical board. But if the doctor moves from one state to another, patients may not receive adequate information regarding their physician's prior disciplinary actions. Thus, it was the goal of our project to create a data pipeline that could tackle this issue.
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
        The desired effect is to help aggregate doctor disciplinary data in one central database that can be viewed and analyzed by the client.

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
---
