---
layout: project

summary:
    name: Madaktari Africa
    tagline: A volunteer management system for doctors educating physicians abroad

team:
    - year: 2017
      semester: Fall
      pm: Abhinav Suri
      tl: Santiago Buenahora
      developers:
          - Sanjay Subramaniam
          - Nishita Jain
          - Roberto Nin Feliz

client:
    - name: Madaktari Africa
      description: >
         Madaktari Africa is an organization that sends doctors from the United States to 3rd world countries to do more than just treat patients. Madaktari believes that it is crucial to teach surgeons and physicians in areas like Tanzania how to do specialized procedures so that it will not be necessary to request foreign aid in the future. Its mission is to enhance the existing healthcare system by using a "train forward" model, creating a local, sustainable, self-propagating system of healthcare, which empowers people and improves lives.
      website_url: https://www.madaktari.org

project:
    problem: >
         Madaktari Africa receives several emails from physicians who are interested in volunteering; however, the volume of people interested is far too large to keep track of on a spreadsheet. They needed a system that could allow physicians to apply to be part of a trip, coordinate teams of physicians and nurses, handle necessary paperwork, and follow up after the trip with a survey.
    features:
        - Customizable form complete with file upload (mini-google form)
        - Searchable database of members and  team creation functionality
        - Administrator functionality to oversee all steps of the process including accepting/rejecting clients and creating teams
        - Functionality for email notifications
        - Rating and testimonial system for teams and hosts
        - Scheduling function for scheduling trips in a team
    technologies:
        - Python
        - Flask
        - SQLite
        - AWS S3
        - Formbuilder (for frontend interface)
    technical_challenges:
        - Creating a means by which to customize a form and store it in the database (along with the responses in the correct format) proved to be quite challenging. However, a frontend solution called "Form Builder" allowed us to create a common format for form structure data to be represented and displayed. From there, we used a binary pickle type in SQLite to store the data for form responses and render them out on the frontend
        - Additionally, we needed a means by which to handle file uploads in the form. Using amazon S3, we were able to store files for access later on in the application process.
        - Creating teams was a central feature for the application which required more logic on the database end. Using a many-to-many model, we were able to successfully integrate teams into the application.
    impact: >
       To date, Madaktari Africa is in the process of integrating the project into their current system and are looking forward to deploying it for public use. This project will help them manage their flow of interested doctors and solve their logistics issues.

code:
    github_repo_name: madaktari

keywords:
    social_impact_keywords:
        - volunteering
    tech_keywords:
        - dynamic forms
        - databases

media:
    screenshots:
        - screenshot_caption: Madaktari 1
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss01.png"
        - screenshot_caption: Madaktari 2
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss02.png"
        - screenshot_caption: Madaktari 3
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss03.png"
        - screenshot_caption: Madaktari 4
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss04.png"
        - screenshot_caption: Madaktari 5
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss05.png"
        - screenshot_caption: Madaktari 6
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss06.png"
        - screenshot_caption: Madaktari 7
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss07.png"
        - screenshot_caption: Madaktari 8
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/madaktari/ss08.png"
---