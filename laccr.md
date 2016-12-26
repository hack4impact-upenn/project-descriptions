---
layout: project

summary:
    name: Juvenile Sentence Cost Calculator
    tagline: Simply calculates and compares different expenditures for juvenile sentences to help attorneys and advocates

team:
    - year: 2014
      semester: Fall
      pm: Cathy Chen
      developers:
          - Ali Altaf 
          - Rachel Hong

client:
    - name: Louisiana Center for Children’s Rights
      description: >
            The Louisiana Center for Children’s Rights is a non-profit that
            defends the right of every Louisiana child to fairness, dignity, and
            opportunity. It is the only specialized juvenile defense law office
            in the country and houses the Louisiana Children’s Advocacy Group
            that advocates for a more fair and compassionate juvenile justice
            system.
      website_url: http://www.laccr.org/

project:
    problem: >
            The cost of a sentence has a huge impact on a judge's ruling and is often
            used by the advocacy group to expose inefficiencies in the system. However
            calculating and comparing different expenditures is a tedious and arduous
            task that many attorneys and advocates simply do not have time for. The
            organization thus applied to Hack4Impact for help building a juvenile
            sentence cost calculator
    features:
        - Choose sentence type
        - Choose sentence duration in years, months, and days
        - Calculate a single sentence in dollars
        - Add different sentence choices
        - Visualize comparative sentence costs on scale
        - See dollar difference between sentence costs
    technologies:
        - jQuery (JavaScript library to simplify JavaScript programming) 
        - D3.js (JavaScript library for manipulating documents based on data)
        - Foundation (to make the web application mobile-responsive)
    technical_challenges:
        - The team spent most of the time in the first few weeks
            determining the features and designing the product. A majority of
            the planning process was spent discussing how to best display
            comparisons and make the web application extremely intuitive and
            quick to use. After a couple of design mockups the client selected
            the one they liked best and with a couple of modifications the
            coding started.
    impact: >
            Hopefully the product can make it easier for lawyers and advocates
            to calculate sentence costs used in defending the rights of children
            and improving the juvenile justice system.

code:
    github_repo_name: lcag

keywords:
    social_impact_keywords:
        - juvenile justice
        - sentencing costs
        - legal advocacy
    tech_keywords:
        - data visualization
        - mobile-responsive
        - user interface

media:
    screenshots:
        - screenshot_caption: Initial sentence choice comparison
          screenshot_url: https://raw.githubusercontent.com/hack4impact/lcag/master/ss01.png
        - screenshot_caption: Sentence choice calculation, with type and duration
          screenshot_url: https://raw.githubusercontent.com/hack4impact/lcag/master/ss02.png
        - screenshot_caption: Sentence choice 1, 2, 3 calculation
          screenshot_url: https://raw.githubusercontent.com/hack4impact/lcag/master/ss03.png
    articles:
        - article_name: Computer Science for a Cause
          article_url: https://mandtforlife.com/2015/02/04/computer-science-for-a-cause/
---
