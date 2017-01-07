---
layout: project

summary:
    name: Donor Engagement Dashboard
    tagline: Helping increase donor engagement and repeat donations

team:
    - year: 2015
      semester: Spring
      pm: Cathy Chen
      developers:
          - Alex Harelick
          - Natasha Narang
          - Rodrigo Ornelas
          - Veronica Wharton

client:
    - name: Givology
      description: >
          Givology is an online giving marketplace where people can browse and sponsor students and education projects in the developing world. A 100% volunteer-run organization, it partners with grassroots education organizations that lack marketing resources and are unfamiliar with using the Internet for fundraising and building awareness.
      website_url: http://givology.org/

project:
    problem: >
        Givology's dashboard for donors was not serving its purpose. The dashboard provided little feedback to donors of their overall impact. Also, the dashboard did not actively encourage donors to return or give repeated donations.
    features:
        - "Impact wheel: donors are able to see all their donations visualized in one space"
        - "Trending and recent donations - donors are encouraged to give further donations through suggestions on the dashboard"
        - "Goal setting: donors can set personal donation goals or compare their activities against a Givology Challenge"
        - "Impact ticker: a banner with pictures of all the organizations the donor has donated too"
        - Volunteer hours log
    technologies:
        - Django (for web application framework)
        - Python (for web application backend)
        - jQuery (for writing JavaScript more easily)
        - D3 (for data visualization)
    technical_challenges:
        - Initially the exact scope of the project was unclear but after 2 weeks of talking with the clients and brainstorming features that would really add to an engaging donor dashboard a detailed specification was drawn up and mockups created. The entire team contributed to the brainstorming of features and provided feedback for the mockups before they were sent to the client to be approved.
    impact: >
        "Givology's dashboard now provides feedback to donors of their overall impact and actively encourages donors to return or give repeated donations."

code:
    github_repo_name: givology

keywords:
    social_impact_keywords:
        - microfinance
        - education
        - poverty
    tech_keywords:
        - crowdsourcing
        - data representation
        - gamification?

media:
    screenshots:
        - screenshot_caption: Dashboard with impact wheel, trending/recent donations, and goal setting
          screenshot_url: https://raw.githubusercontent.com/hack4impact/Givology/master/ss01.png
        - screenshot_caption: Dashboard with impact ticker and volunteer hours log
          screenshot_url: https://raw.githubusercontent.com/hack4impact/Givology/master/ss02.png
---
