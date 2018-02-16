---
layout: project

summary:
    name: Application Processing Software
    tagline: A web app to quickly process an application by completing the needed calculations for that application. 

team:
    - year: 2017
      semester: Fall
      pm: Brandon Obas
      tl: Suzanne Knop
      developers:
          - Jasmine Lee
          - Hunter Lightman
          - Andrew Shen

client:
    - name: Habitat for Humanity Philadelphia
      description: >
        Habitat for Humanity is a non-profit whose mission is build and repair houses for families in need in the Philadelphia area. 
      website_url: https://www.habitatphiladelphia.org/

project:
    problem: >
        Habitat for Humanity currently has three programs Homeownership Program, Home Repair Program, and Individual Development Account Program. These are programs that require individuals to complete an application and submit financial/ supporting documentation in order to be considered for one of the programs. Currently, all applications are reviewed and audited manually. All calculations are done manually. Due to this there were many inefficiencies and errors.It takes a lot of time to process all of this applications manually. Furthermore some of the calculations would be incorrect and the volunteer would have to start the application all over again. Sometimes a volunteer would move an application towards the next step of the application process when they should not have. This is where we step in. By creating a web app that would allow volunteers to process applications online.  

    features:
        - "Create a new application "
        - "Search for specific applicants"
        - "Complete calculations based off information from application"
        - "Issue flags that stop applications from proceeding based off calculations"
        - "Ability to edit and create fields, calculations, flags and phases"
    technologies:
        - JavaScript
        - Python Libraries
        - HTML, CSS
    technical_challenges:
        - One of the most difficult aspects of this project was implementing the feature to process calculations. We had to figure out a way to do different operations such as addition and subtraction with multiple input parameters.   
        - Another technical challenge that we faced was dynamically generating phases and fields. 
    impact: >
        By creating this application, we saved Habitat for Humanity countless hours in processing applications manually. We minimized the amount of errors that would have occured when doing calculations manually for each application. We also made it easier for Habitat for Humanity to keep track of all the applications that they recieve. Not only will this application benefit Habitat for Humanity but it could also be used by any non-profit that would want to process their applications online. 

code:
    github_repo_name: habitat-for-humanity
    live_url: https://habitat-for-humanity.herokuapp.com/

keywords:
    social_impact_keywords:
        - Home Repair
        - affordable housing
        - families in need
    tech_keywords:
        - web app
        - data processing

media:
    screenshots:
        - screenshot_caption: View all Applications
          screenshot_url: https://imgur.com/szCRPS9
        - screenshot_caption: A Phase in application processing
          screenshot_url: https://imgur.com/6Zt1JS1
        - screenshot_caption: Creating a new Phase/Calculation
          screenshot_url: https://imgur.com/ZNkrr5w
---
