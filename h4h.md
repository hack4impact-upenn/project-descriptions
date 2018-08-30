---
layout: project

summary:
    name: Application Processing Software
    tagline: A web app to quickly process an application by completing the needed calculations to screen that application. 

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
        Habitat for Humanity is a non-profit whose mission is to build and repair houses for families in need in the Philadelphia area. 
      website_url: https://www.habitatphiladelphia.org/

project:
    problem: >
        Habitat for Humanity currently has three programs: the Homeownership Program, the Home Repair Program, and the Individual Development Account Program. These are programs that require individuals to complete an application and submit financial/ supporting documentation in order to be considered for one of the programs. Currently, all applications are reviewed and audited manually, and all the calculations are done manually. Due to this, there were many inefficiencies and errors, and applications took a long time to process. Errors could lead to having to redo the backend calculations, or moving an application toward the next step of the application process when it should not have. This is where we step in: we created a web app that allows volunteers to process applications online.  

    features:
        - "Create a new application, and be able to go back and edit it"
        - "Search for specific applicants by name, status, program, and date applied"
        - "Complete custom calculations based off information from application"
        - "Issue flags that stop applications from proceeding based off calculations"
        - "Edit and create fields, calculations, flags, and phases (groups of fields)"
        - "Upload and save files"
    technologies:
        - Flask 
        - SQLAlchemy
        - JavaScript
        - WTForms
        - HTML
        - CSS
    technical_challenges:
        - Processing calculations. We had to figure out a way to do mathematical (+, -, *, /) and logical (&& and ||) operations with multiple input parameters. We solved this problem by creating a custom Field model and using the Python library py_expression_eval
        - Customizable forms. We tackled this challenge by creating models that represented the many-to-many relationship between Applications and Fields, and Phases that represented groupings of calculations done on fields. 
        - Dynamically generating forms from completely custom fields. We implemented this by populating our form purely with the custom fields on the frontend. None of the "phase" forms in our application are hard-coded!
    impact: >
        By creating this application, we saved Habitat for Humanity countless hours in processing applications manually, shortening the processing time from a few days to 15 minutes. We minimized the amount of errors that would have occured when doing calculations manually for each application. We also made it easier for Habitat for Humanity to keep track of all the applications that they recieve. Not only will this application benefit Habitat for Humanity but it could also be generalized and used by any non-profit that would want to process their applications online. 

code:
    github_repo_name: habitat-for-humanity
    live_url: https://habitat-for-humanity.herokuapp.com/

keywords:
    social_impact_keywords:
        - home repair
        - affordable housing
        - families in need
    tech_keywords:
        - web app
        - flask
        - sqlalchemy

media:
    screenshots:
        - screenshot_caption: View all Applications
          screenshot_url: https://imgur.com/szCRPS9
        - screenshot_caption: A Phase in application processing
          screenshot_url: https://imgur.com/6Zt1JS1
        - screenshot_caption: Creating a new Phase/Calculation
          screenshot_url: https://imgur.com/ZNkrr5w
---
