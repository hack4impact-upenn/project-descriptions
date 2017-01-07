---
layout: project

summary:
    name: Youth Matters: Philly
    tagline: Helping foster youth find resources in the local Philadelphia area

team:
    - year: 2016
      semester: Fall
      pm: Rani Iyer
      tl: Annie Meng
      developers:
          - Ben Sandler
          - Brandon Obas
	  - Kyle Rosenbluth
	  - Sanjay Subramanian
	  - Stephanie Shi

project:
    problem: >
        "Each year, approximately 800 youth age out of the child welfare system in Philadelphia without being placed with a family. These youth face significant challenges finding housing, employment, getting health care, making ends meet, and navigating the foster care system itself.”
    features:
        - View both a map and list of all the resources
		- Ability to search location and search resources by name 
		- Ability to filter resources by multiple criteria 
		- Ability to suggest new resources and edits to existing resources
		- Ability to rate/review resources
		- Admin-editable static pages to display important non-mappable information to youth
		- Mobile-responsive interface
		- Admin console to add, delete or edit resources
		- Admin ability to bulk upload resources through CSV
    technologies:
        - Flask (main Python web application framework)
        - Handlebars (create JS templates for displaying resources)
        - Google Maps API (mapping resources)
	- Papaparse (parsing CSV files of resources)
    technical_challenges:
        - Allowing for bulk uploading of resources through CSV: accommodating potentially large files and flexibility in being able to handle both reseting all data as well as updating
	- Defining and then implementing ways for users to be able to do more detailed searches for resources by filtering
    impact: >
        The desired effect is to help increase the number of youth aging out of the child welfare system by using the app to locate necessary resources.

code:
    github_repo_name: maps4all-jlc-sp2

keywords:
    social_impact_keywords:
        - foster youth 
        - resources
        - accessibility
    tech_keywords:
        - mapping
        - csv parsing
        - search

media:
    screenshots:
        - screenshot_caption: Home page
          screenshot_url: https://raw.githubusercontent.com/hack4impact/maps4all-jlc-sp2/master/example/home.png
        - screenshot_caption: Select a resource
          screenshot_url: https://raw.githubusercontent.com/hack4impact/maps4all-jlc-sp2/master/example/one.png
	- screenshot_caption: Resource detailed view
          screenshot_url: https://raw.githubusercontent.com/hack4impact/maps4all-jlc-sp2/master/example/two.png
---
