---
layout: project

summary:
    name: Location History Analyzer
    tagline: An open source tool to quickly organize millions of Google location history points by bounding box into a single spreadsheet with weekly summaries.

team:
    - year: 2016
      semester: Fall
      pm: Krishna Bharathala
      tl: Abhinav Suri
      developers:
          - Santiago Buenahora
          - Daniel Zhang
          - Rachel Hong
          - Katie Jiang

client:
    - name: Community Legal Services
      description: >
        Community Legal Services of Philadelphia (CLS) is the first pro-bono legal clinic in the greater Philadelphia area, serving thousands of individuals since its inception.
      website_url: http://www.clsphila.org/

project:
    problem: >
        Community Legal Services routinely deals with issues regarding wage theft from employers. In most cases, employers withhold payment for overtime hours and, as a result, employees must sue for their rightful wages. To prepare for these cases, CLS goes through an extensive interview process with employees to construct a detailed sequence of events regarding their whereabouts for the times in question. However, this process is very time and cost intensive. However, for employees who have android smartphones with location history tracking enabled, this process can be streamlined by analyzing their entire location history data. That is where we stepped in. We created a way to analyze years of location history for relevant data all without uploading data to a server, guaranteeing data security and privacy.

    features:
        - "Upload Location History .json file of any size"
        - "Process all data within the client's web browser without need for external servers"
        - "Allow clients to select area of work and isolate data time points within those areas"
        - "Generate a CSV file with entry and exit times from areas of work"
        - "Preview all location data points on a map and cluster on the client end to enable seamless viewing"
        - "Tutorial for all new users to the platform"
    technologies:
        - JavaScript
        - Oboe.js for efficient chunking and streaming of files
        - HTML, CSS
        - Leaflet JS
    technical_challenges:
        - The most difficult portion of the project was loading all the data points into memory considering that some location history files contain upwards of 500 MB of data. We had to figure out a way to chunk and stream the file efficiently while making sure to display all points on the frontend and void crashing the user's browser.
        - We also had to make sure that the resulting timesheet and data points were output in a format easily usable by CLS lawyers. This final step was among the more difficult tasks as we had to make sure that the CSV output file could be submitted for court evidence.
    impact: >
        By creating this application, we saved CLS lawyers countless hours in interviewing victims of wage theft. Additionally, this product allowed cases to proceed to legal proceedings with an objective source of legal evidence for many clients. CLS is releasing this product to other pro-bono legal clinics in order to help them with the process of combating wage theft across the nation.

code:
    github_repo_name: cls
    live_url: http://hack4impact.github.io/cls

keywords:
    social_impact_keywords:
        - anti wage-theft
        - pro-bono
    tech_keywords:
        - web app
        - privacy
        - data processing

media:
    screenshots:
        - screenshot_caption: Tutorial
          screenshot_url: https://raw.githubusercontent.com/hack4impact/cls/master/media/tutorial.gif
        - screenshot_caption: Uploading location data
          screenshot_url: https://raw.githubusercontent.com/hack4impact/cls/master/media/upload.gif
        - screenshot_caption: Creating bounding boxes
          screenshot_url: https://raw.githubusercontent.com/hack4impact/cls/master/media/bounding_box.gif
        - screenshot_caption: Creation of CSV
          screenshot_url: https://raw.githubusercontent.com/hack4impact/cls/master/media/submit_csv.gif
---
