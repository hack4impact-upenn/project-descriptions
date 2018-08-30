---
layout: project

summary:
    name: Philly Food Finder
    tagline: Map-based web app to find local food resources

team:
    - year: 2014
      semester: Fall
      pm: Veronica Wharton
      developers:
          - Natasha Narang
          - Ben Sandler
          - Nancy Wong

client:
    - name: Greater Philadelphia Coalition Against Hunger
      description: >
        Founded in 1996, the Greater Philadelphia Coalition Against Hunger strives to build a community where all people have the food they need to lead healthy lives. The Coalition connects people with food assistance programs and nutrition education; provides resources to a network of food pantries; and educates the public and policymakers about responsible solutions that prevent people from going hungry. 
      website_url: http://hungercoalition.org
    - name: Philadelphia Food Policy Advisory Council 
      description: >
        The Philadelphia Food Policy Advisory Council (FPAC) facilitates the development of responsible policies that improve access for Philadelphia residents to culturally appropriate, nutritionally sound, and affordable food that is grown locally through environmentally sustainable practices.
      website_url: http://phillyfpac.org

project:
    problem: >
        In Philadelphia county, 22% of residents are food-insecure. While there are food assistance programs -- including food pantries, soup kitchens, and senior meal sites -- available to Philadelphians, such resources may be difficult for those in need to learn about or find.
    features:
        - intuitive map-based interface that visitors use to search for food resources by zip code
        - visitors can also search by types of resources
        - visitors can also search by advanced options
        - suite of administrative functions that will allow the FPAC to easily add and update food resources and other content on the website
        - managers of food resources within Philadelphia can submit their food resource’s information for inclusion in the website’s database
    technologies:
        - Flask (for web appl framework)
        - Foundation (for front-end)
        - SQLAlchemy (for database)
        - jQuery (for writing easier JavaScript)
        - gmaps.js (for map)
        - CKEditor.js (for web-based HTML text editor) 
        - Dropzone.js (for drag'n'drop file uploads)
        - Remodal (for pop-up modals)
    technical_challenges:
        - Our client, the Philadelphia Food Policy Advisory Council (FPAC), tackled this problem by creating the Food Resources Toolkit, a comprehensive guide to food resources in Philadelphia. Our task was to adapt the Food Resources Toolkit for the web -- to develop a central web-based tool where individuals can find all food resources that are available within their zip code. Our client also emphasized the need for the website to be easily updatable with new or updated food resources and information.
    impact: >
        We hope that Philly Food Finder will be a great asset to FPAC and the greater Philadelphia community. PhillyFoodFinder was a "2016 Outstanding Nominee" for the "Mayor's Award for Distinguished Group Service Project" during the 4th Annual Mayor and County Recognition Day for National Service.

code:
    github_repo_name: gpcah
    live_url: http://phillyfoodfinder.org/

keywords:
    social_impact_keywords:
        - food assistance
        - food insecurity
        - resource mapping
    tech_keywords:
        - mapping
        - search
        - administrative functions

media:
    screenshots:
        - screenshot_caption: Zip code search
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/gpcah/ss01.png
        - screenshot_caption: Add new food resource
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/gpcah/ss02.png
        - screenshot_caption: Approved Food Resources
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/gpcah/ss03.png
        - screenshot_caption: Approved Farmers Markets list
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/gpcah/ss04.png
    articles:
        - article_name: Philly Food Finder app makes finding affordable food easier
          article_url: http://generocity.org/philly/2015/08/28/philly-food-finder-app-makes-finding-affordable-food-easier/
        - article_name: Student organization connects non-profits with app development
          article_url: http://www.thedp.com/article/2015/02/hack-for-impact
---
