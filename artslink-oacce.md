---
layout: project

summary:
    name: "ArtsLink"
    tagline: ArtsLink is a free web tool to help Philadelphians find quality arts experiences in neighborhoods across the city.

team:
    - year: 2018
      semester: Spring
      pm: Steven Bursztyn
      tl: Rani Iyer
      developers:
          - Abhinav Suri
          - Brandon Obas
          - Nishita Jain

client:
    - name: Office of Arts, Culture and the Creative Economy
      description: >
        The Office of Arts, Culture and the Creative Economy (OACCE) connects Philadelphia's children, youth, and adults to enriching, arts-infused experiences: closes the gap in access to quality arts education, creative opportunities and cultural activities; and preserves the City's public art assets.
      website_url: https://creativephl.org

project:
    problem: >
        In an effort to get students, teachers, and philadelphians more engaged with the arts community in the city, OACCE reached out to us to create an online searchable database of art experience opportunities called ArtsLink. ArtsLink is a free resource for Philadelphians to discover arts programs from local organizations that best fit their needs or the needs of their community. Users can find programs that best fit their schedule and artists can create opportunities for public viewing on the website itself.

    features:
        - Individual art organization profile pages which are editable and available for public display. 
        - Search function to allow users to find art experience opportunities by art type, activity, availability time, target age group, and accessibility compliance.
        - Administrator functionality to edit user pages
        - Full user registration system for art experience providers
        - Gallery option to allow for multiple image uploads on an individual profile.
    technologies:
        - Python
        - SQLite
        - AWS S3
        - SendGrid
    technical_challenges:
        - Creating a stable image uploading service that was maintainable was a key feature to be implemented in this project. Due to the restrictions of Heroku, we needed to find a way to do this. Ultimately, we chose to use AWS S3 for its reliability and ease of integration.
        - Creating individual organization pages was a key feature as well. We eventually created an organization page system that allowed for there to be shared tags across the system that organizations can hold in common, allowing for an optimized search & filter experience.
    impact: >
        ArtsLink is part of OACCE's initiative to integrate artistic experiences into the classroom. Since working with us, OACCE has launched this tool publicly and it is currently in use across Philadelphia school districts, allowing for students to engage with the local arts community.


code:
    github_repo_name: ArtsLink-OACCE
    live_url: http://www.ArtsLinkPHL.org

keywords:
    social_impact_keywords:
        - arts
        - resources
    tech_keywords:
        - sqlite
        - aws
        - search

media:
    screenshots:
        - screenshot_caption: Home page
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/artslink-oacce/ss01.png"
        - screenshot_caption: Search page
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/artslink-oacce/ss02.png"
        - screenshot_caption: Example page 1
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/artslink-oacce/ss03.png"
        - screenshot_caption: Organization dashboard
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/artslink-oacce/ss04.png"
        - screenshot_caption: Example page 2
          screenshot_url: "https://raw.githubusercontent.com/hack4impact/project-screenshots/master/artslink-oacce/ss05.png"
---
