---
layout: project

summary:
    name: iCAN Road to College
    tagline: connect mentors with high school students who had gotten into college to mitigate "summer melt"

team:
    - year: 2014
      semester: Fall
      pm: Ali Altaf
      developers:
          - Maya Ebsworth
          - Ayush Goyal
          - Max McCarthy
          - Annie Meng

client:
    - name: Interactive College Access Network
      description: >
          ICAN is an innovative new program targeted at recent high school graduates from Philadelphia who intend to matriculate at college. Using mentorship and mobile applications to support low-income students through the summer between high school and college, we hope to decrease the number of students who are accepted to college but never enroll: an issue the experts call ["summer melt"](http://www.ed.gov/blog/2013/07/summer-melt/).
      website_url: http://icanphiladelphia.org

project:
    problem: >
        According to the latest longitudinal data on college completion, only 10% of entering 9th graders to the School District of Philadelphia in 1999-2000 had graduated from college by 2009. Despite increasing college access and completion rates for low-income students, college completion is still troublingly low. A lack of college degree severely limits individual employability, diminishes earning potentials, and stifles economic development in Philadelphia -- however, as education scholars have begun to discover, a key junction for intervention lies in the summer after high school graduation.
    features:
        - Landing page with Login, Student Signup, Mentor Signup
        - Account page with Your Tasks, Your Mentor, Your Profile, and Your College 
        - Your Tasks page with completed tasks and upcoming tasks
        - Your Mentor page with contact information
        - Your College page to find out more about your college, contac the admissions office, and more.
    technologies:
        - Python
        - Flask (for web application microframework)
        - SQLAlchemy (for databases)
        - Bootstrap (for responsive, mobile first framework for HTML, CSS, and JS)
    technical_challenges:
        - iCAN needed us to build an app to link mentors with high school students who had gotten into college, but the key part was making the UI and overall experience good enough to incentivize students to use it. We began by sitting down with members from the iCAN team to get a thorough understanding of the application they wanted us to build and over several hours we refined this down to a list of well-defined features. Over the course of the semester we met with the iCAN team every two weeks to determine which features were most important to work on, and at these meetings we refined the work we had previously completed.
    impact: >
        The iCAN app will act as a social platform for the iCAN administrator and student to connect, with clickable links to relevant tasks such as enrolling for classes, reading a tuition bill, and selecting a dorm. Students will be able to respond to received messages to request help from the iCAN administrator if needed. The iCAN app will also provide a social network for other iCAN participants through FAQ forums and links to social media like Facebook.

code:
    github_repo_name: ican
    live_url: http://ican-app.herokuapp.com/

keywords:
    social_impact_keywords:
        - mentorship
        - low-income students
        - summer melt
    tech_keywords:
        - UI
        - Task management
        - Gamification

media:
    screenshots:
        - screenshot_caption: "iCAN Road to College: Login, Student Signup, Mentor Signup"
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/ican/ss01.png
        - screenshot_caption: Account page with Your Tasks, Your Mentor, Your Profile, and Your College
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/ican/ss03.png
        - screenshot_caption: Your Tasks page with completed tasks and upcoming tasks
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/ican/ss04.png
        - screenshot_caption: Your Mentor page with contact information
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/ican/ss05.png
    articles:
        - article_name: Student organization connects non-profits with app development
          article_url: http://www.thedp.com/article/2015/02/hack-for-impact
---
