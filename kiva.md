---
layout: project

summary:
    name: Kiva Crowdsourced Due Diligence App
    tagline: Leverage volunteers to more quickly review loan applications from sustainable social organizations worldwide.

team:
    - year: 2014
      semester: Fall
      pm: Dhruv Maheshwari
      developers:
          - Alex Harelick
          - Yoni Nachmany
          - Rodrigo Ornelas
          - Arman Tokanov

client:
    - name: Kiva
      description: >
          Kiva is a non-profit organization with a mission to connect people through lending to alleviate poverty. Leveraging the internet and a worldwide network of microfinance institutions, Kiva lets individuals lend as little as $25 to help create opportunity around the world.
      website_url: https://www.kiva.org/

project:
    problem: >
        Kiva came to us with the goal of building an app that would allow them to more quickly approve loans to entrepreneurs around the world. With the recent addition of Kiva Zip, a new Kiva product that allows non-traditional lending institutions (such as churches and schools), Kiva was receiving thousands of loan applications and needed a process by which to crowd-source application reading.
    features:
        - Gamification to help incentivize volunteers to continue working
        - Document viewer so that each loan application could be viewed as the review was being completed
        - Dashboard for administrators to quickly see aggregated statistics per loan application 
        - Question upvote mechanisms for volunteers to determine what other information would be useful in evaluating the loan
        - Training/Resources for volunteers
    technologies:
        - HTML (for front-end)
        - CSS (for front-end)
        - JS/JQuery (for front-end) 
        - Node/Express (for web-app framework)
        - MongoDB (for database)
    technical_challenges:
        - Beyond just reviewing loan applications, the “Crowdsourced Due Diligence App” needed to be a useful tool for Kiva administrators and create an effective user experience for volunteers. We sat down with a few Kiva members who gave us a detailed spec of how to accomplish those two goals.
    impact: >
        At the end of the semester, we handed the project off to the engineering team of Kiva, who will integrate it with their systems and deploy it in the coming year. Kiva's https://github.com/kiva/crowdvet/ repository forked from Hack4Impact's repository.

code:
    github_repo_name: kiva
    live_url: http://www.crowdvet.org/

keywords:
    social_impact_keywords:
        - microfinance
        - poverty
        - volunteer-management
    tech_keywords:
        - crowdsourcing
        - gamification
        - upvoting

media:
    screenshots:
        - screenshot_caption: Dashboard for administrators to quickly see aggregated statistics per loan application 
          screenshot_url: https://raw.githubusercontent.com/hack4impact/Kiva/master/dashboard.png
        - screenshot_caption: Loan application review
          screenshot_url: https://raw.githubusercontent.com/hack4impact/Kiva/master/form.png
    articles:
        - article_name: Student organization connects non-profits with app development
          article_url: http://www.thedp.com/article/2015/02/hack-for-impact
        - article_name: Computer Science for a Cause
          article_url: https://mandtforlife.com/2015/02/04/computer-science-for-a-cause/
---
