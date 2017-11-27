---
layout: project

summary:
    name: IdleFreePhilly
    tagline: Crowdsourcing Illegal Idling in Philadelphia

team:
    - year: 2015
      semester: Fall
      pm: Sally Kong
      tl: Ben Sandler
      developers:
        - Thomas Lee
        - Alex Piatski
        - Kyle Rosenbluth
        - Sanjay Subramanian
        - Riley Wong

client:
    - name: Clean Air Council
      description: >
          Established in 1967, Clean Air Council (CAC) is Philadelphia’s oldest environmental conservation organization. The Council is dedicated to protecting and defending everyone’s right to breathe clean air. The Council works through a broad array of related sustainability and public health initiatives, using public education, community action, government oversight, and enforcement of environmental laws.
      website_url: http://cleanair.org/


project:
    problem: >
    Idling happens when a vehicle’s engine is unnecessarily left running while it is stopped. In some cities (including Philadelphia), idling of large vehicles such as trucks and buses is illegal due to its economic, health, and climate costs. The purpose of IdleFreePhilly was to provide a web and SMS platform for reporting and visualizing illegal idling of large vehicles in Philadelphia. This helps Clean Air Council in identifying problematic city agencies and companies to help them self-correct and train their personnel.
    features: >
    - Public Map of All Reports of Illegal Idling Incidents (Mobile responsive)
      - Time slider for filtering reports by date range
      - Interactive markers for displaying details of the idling incidents
      - Form for submitting reports
    - Administrative Features for Clean Air Council Staff
      - Dashboard for searching, filtering, and managing reports
      - Ability to manage user and agency permissions and accounts
      - Ability to bulk download reports as a CSV file
    - SMS Reporting
    technologies:
      - Flask
      - SQL
      - Google Maps API
      - Twilio
      - Imgur API
    technical_challenges:
      - Implementing various levels of permissions for viewing and editing reports. (ex. anonymizing license plates for the public but not for the Clean Air Council staff and agencies who own the vehicle with the license plate number)
      - Generalizing report validation code to work with both our web and sms reports

    impact: >
    Clean Air Council said that through IdleFreePhilly, they were able to record more than a 1000 illegal idling incidents. This allowed Clean Air Council to target specific agencies which had high idling counts with concrete evidence and persuaded these agencies to retrain their employees to prevent future idling.


code:
    github_repo_name: idle-free-philly
    live_url: http://idlefreephilly.org/

keywords:
    social_impact_keywords:
        - environmental conservation
    tech_keywords:
        - crowdsourcing
        - mapping
        - web app
        - sms report


media:
    screenshots:
        - screenshot_caption: Map of Reported Illegal Idling Incidents
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/idle-free-philly/map.png
        - screenshot_caption: Example Illegal Idling Incident Report
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/idle-free-philly/report_details.png
        - screenshot_caption: Web Form for Reporting
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/idle-free-philly/report_form.png
        - screenshot_caption: FAQ
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/idle-free-philly/faq.png
---
