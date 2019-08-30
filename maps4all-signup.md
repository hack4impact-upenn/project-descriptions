---
layout: project

summary:
    name: Maps4All Signup
    tagline: An integrated platform to launch Maps4All instances

team:
    - year: 2017
      semester: Spring
      pm: Abhinav Suri
      tl: Santiago Buenahora
      developers:
          - Ben Sandler
          - Hunter Lightman
          - Hana Pearlman

client:
    - name: Maps4All
      description: Maps4All is a open source project created by Hack4Impact for the purpose of allowing nonprofits to easily display resources on a map.

project:
    problem: >
       Nonprofits need a way to effectively communicate where resources exist and how to get access to them. To address this issue, Maps4All was created for the Juvenile Law Center and was later reappropriated to be a generalized solution for displaying resources on a map. The issue was that members of Hack4Impact would need to manually set up an instance of Maps4All each time another nonprofit wanted access to the platform. This project aimed to solve that.
    features:
        - Ability to launch instances using Heroku's API
        - Created a generalized version of Maps4All that could work on heroku without additional setup
        - Created a user payment process by which users could pay on a monthly basis for usage of the platform via Stripe
        - Administrator accounts could manage existing Maps4All instances
        - Each instance of Maps4All could get their own subdomain via namecheap's API
    technologies:
        - Heroku
        - Flask
        - Stripe
        - Namecheap
        - Docker
    technical_challenges:
        - Creating instances via Heroku was very involved and we needed to find a way to automate the process of launching an instance. After discovering the OAuth API, we were able to execute commands as a user and launch any instance of an application (and create addons for the user)
        - In order to create a means by which to allow users to pay for the project, we needed to find a payment platform that could integrate into our app. Fortunately, we came across the Stripe API which allowed us to automate this process on a monthly basis.
        - In order to avoid creating a URL that was nonsensical, we allowed users to create their own subdomain on the platform as opposed to heroku's randomly generated name. This involved a lot of backend work on our end, but we eventually found a way to create subdomains with namecheap so that each user could have their own maps4all domain name.
    impact: >
        This application formed the precursor to the official maps4all platform which is serving nonprofits to this day.

code:
    github_repo_name: maps4all-signup

keywords:
    social_impact_keywords:
        - maps4all
        - resources
    tech_keywords:
        - heroku
        - OAuth
        - stripe
        - flask
        - sqlite

media:
    screenshots:
        - screenshot_caption: Maps4All Signup 1
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/maps4all-signup/ss01.png"
        - screenshot_caption: Maps4All Signup 2
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/maps4all-signup/ss02.png"
        - screenshot_caption: Maps4All Signup 3
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/maps4all-signup/ss03.png"
        - screenshot_caption: Maps4All Signup 4
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/maps4all-signup/ss04.png"
---