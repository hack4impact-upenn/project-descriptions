---
layout: project

summary:
    name: BusyBooth
    tagline: Help voters figure out when to cast their ballots using crowd-sourced polling place wait times

team:
    - year: 2016
      semester: Spring
      pm: Krishna Bharathala
      developers:
          - Cathy Chen
          - Hunter Lightman
          - Ben Sandler
          - Sanjay Subramanian

client:
    - name: OSET Foundation
      description: >
        The OSET Institute is all about making elections software technology publicly available in order to increase verification, accuracy, security, and transparency (in process), and ensure that ballots are counted as cast.  The work is all about integrity in election
      website_url: http://www.osetfoundation.org/

project:
    problem: >
        The January 2014 Presidential Commission on Election Administration (PCEA) report, triggered by the extraordinarily long lines witnessed in the 2012 Presidential election, includes several recommendations whose goal is to improve the voter experience. One way to address the polling place wait time and reduce line length is providing better and faster information to the voters who make up those lines, which could allow them to determine the best time to go, thus smoothing the traffic spikes that typically occur at certain times of the day. BusyBooth directly addresses that problem with an open source, mobile App that informs voters of the expected wait time at their assigned polling place based on self-reported information from others already in line and/or casting their ballots.
    features:
        - Typically, a voter will “check-in” when first launching BusyBooth on their mobile device.
        - The “check-in” process will authenticate the user to their jurisdiction’s clerk and verify that the individual is properly registered to vote. Of course, the system will verify that an Election Day is occurring and this individual is eligible to cast a ballot for the precinct they are registered to vote in. 
        - Once verified and checked in, the user will establish their current location (i.e., similar to pin dropping in ride share Apps such as Uber or Lyft).  With their starting location established, the App ( using the Google Maps API) will assist the user in determining first, the amount of time required to reach their assigned polling place. 
        - Next the App will provide an estimate of time to wait in line to cast a ballot based on others who have self-reported their current time to wait for that precinct.  By way of crowd sourcing wait time data, a composite wait time estimate is created. 
        - The user can monitor their BusyBooth, or be notified when the wait time reaches a tolerable amount of time as pre-set by the user. 
        - When a user arrives at their polling place they simply tap an "Arrival" button. It is possible the App could notice their arrival based on GPS proximity data and verify with the user that they intend to mark themselves as “arrived” for purposes of adding to the crowd-sourced wait time data set. 
        - The voter can then tap a "Casting" button once they’re checked-in with the Clerk and have received their ballot prior to putting their phone away ( as required in many polling places today.) 
        - Once finished casting their ballot, the user finally taps a “Done” button to end their total time at the polling place.  Here again, it is possible the App could notice their departure based on GPS proximity data and verify with the user that they intend to mark themselves as “Done” for purposes of adding to the crowd-sourced wait time data set. 
    technologies:
        - Objective-C
        - Python
        - Shell
    technical_challenges:
        - 
    impact: >
        The 1st successful outcome, well within 12 months of starting, would be the development, and preliminary usability testing for BusyBooth for an Election. A 2nd successful outcome would be the use of BusyBooth technology to support our collaboration with the Bipartisan Policy Center to improve their tools for studying long lines at polling places. A 3rd and important successful outcome over a 6-12 month timeframe after introduction of BusyBooth would be widespread adoption of the required API support of election jurisdictions to enable broader usage of the App, which would in turn, provide more data useful for elections officials seeking solutions to polling place operational efficiency issues.

code:
    github_repo_name: busy-booth
    live_url: https://itunes.apple.com/us/app/busybooth/id1161142855?mt=8

keywords:
    social_impact_keywords:
        - polling place wait time
        - elections
        - civic engagement
    tech_keywords:
        - crowdsourcing
        - open data
        - real-time data

media:
    screenshots:
        - screenshot_caption: Directions with time in minutes
          screenshot_url: https://raw.githubusercontent.com/hack4impact/busy-booth/master/screen696x696.jpeg
        - screenshot_caption: My Polling Place with address and buttons to View Wait Time and Get Driving Directions
          screenshot_url: https://raw.githubusercontent.com/hack4impact/busy-booth/master/screen696x696%20(1).jpeg
        - screenshot_caption: Past Poll Times, with the approximate wait time and past wait times every hour 
          screenshot_url: https://raw.githubusercontent.com/hack4impact/busy-booth/master/screen696x696%20(2).jpeg
        - screenshot_caption: Menu with My Polling Place, Directions, and Past Poll Times
          screenshot_url: https://raw.githubusercontent.com/hack4impact/busy-booth/master/screen696x696%20(3).jpeg
    articles:
        - article_name: This UPenn app could be an Election Day game-changer
          article_url: http://www.metro.us/philadelphia/this-upenn-app-could-be-an-election-day-game-changer/zsJpjb---VtPLDYDwg787E/
        - article_name: Penn students work to keep polling lines short
          article_url: http://www.philly.com/philly/blogs/real-time/UPenn-students-work-to-shorten-polling-lines.html
        - article_name: This app will help you avoid long lines at the voting booth on Election Day
          article_url: http://www.thedp.com/article/2016/09/hack4impact-strives-to-increase-voter-turnout
        - article_name: Siri, How Busy is my Polling Place?
          article_url: http://www.osetfoundation.org/blog/2014/9/3/siri-how-busy-is-my-polling-place
        - article_name: BusyBooth: a Crowd-Sourced Polling Place Wait Time Monitor to Determine the Best Time to Cast Your Ballot.
          article_url: https://www.newschallenge.org/challenge/elections/entries/use-busybooth-a-crowd-sourced-polling-place-wait-time-monitor-to-determine-the-best-time-to-cast-your-ballot
---
