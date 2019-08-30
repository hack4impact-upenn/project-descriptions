---
layout: project

summary:
    name: "Core Scholars"
    tagline: Scholarship requirements management application for the CORE Scholars Foundation

team:
    - year: 2018
      semester: Spring
      pm: Aruna Prasad
      tl: Santiago Buenahora
      developers:
          - Sanjay Subramaniam
          - Andrew Shen

client:
    - name: CORE Scholars
      description: >
        College Opportunity Resources for Education (CORE) is dedicated to uniting communities around the goal of ensuring that postsecondary education is affordable and accessible for all.  CORE Scholars is the first scholarship of its kind to focus specifically on high school seniors whether from the public, private, charter, or parochial systems living below the poverty line for an Individual Development Account (IDA) savings program. Over the past nine years, CORE has awarded over 25,669 Philadelphia students a total of more than 30 million dollars. 
      website_url: https://corescholars.org

project:
    problem: >
        CORE understands the value of education in the lives of families living at the poverty level. We want to ensure every high school student in America has an opportunity to attend college—today and for years to come. Reaching Independence by Saving for Education (RISE) is part of a national effort to work with individuals to teach financial literacy in order to achieve personal goals. RISE is a need-based savings program, which offers students up to four thousand dollars in scholarship money after saving five hundred dollars of income. RISE participants also received invaluable financial literacy training throughout the duration of their six-month savings commitment. Hack4Impact created an application to help students manage the process of saving five hundred dollars and completing the necessary financial literacy modules.

    features:
        - Profile: Student registers and fills out extensive profile that can be updated over time
        - Savings: Student self-reports savings balance and application sends students SMS reminders with current savings balance and targets.
        - Financial Literacy: Student self-reports progress  in Financial Literacy modules and application sends students SMS reminders to complete modules.
        - Admin Capabilities: Admin can edit values for savings, financial literacy and indicate completion of requirements. 
        - Executive Admin Capabilities: Executive admin can access private student information such as social security number for bank account creation and scholarship check approval. 
    technologies:
        - Flask Boilerplate
        - Airtable (for easily editable forms)
        - Twilio (for SMS notifications)
        - Plaid (for bank account integration)
    technical_challenges:
        - Plaid Integration 
        - File Upload 
        - UI Design
    impact: >
        For CORE, this app would shift how students engage with our program and staff by giving the students the ability to set the pace of their progress and to share it with others. It allows students to keep up with program requirements efficiently and immediately by putting all of the information and tools they need in one place. Because we have a small staff, this app would have an incredible impact on how the staff is able to allot their time and energy and to tailor resources for each student. 

code:
    github_repo_name: core-scholars

keywords:
    social_impact_keywords:
        - scholarship
        - financial literacy
        - savings
    tech_keywords:
        - file upload
        - Airtable
        - Plaid
        - Twilio

media:
    screenshots:
        - screenshot_caption: CORE Scholars
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/core-scholars/ss01.png"
---
