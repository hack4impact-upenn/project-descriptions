---
layout: project

summary:
    name: Nonprofit Overhead Analyzer
    tagline: Enables nonprofits instantly compare their expense rate to others' and find areas for savings

team:
    - year: 2015
      semester: Spring
      pm: Arman Tokanov
      developers:
          - Maya Ebsworth 
          - Thomas Lee
          - Yoni Nachmany
          - Nancy Wong	

client:
    - name: United Affairs Coalition
      description: >
          Urban Affairs Coalition is a coalition of 55+ partner organizations, large and small, working on diverse issues that immediately affect communities. They strengthen nonprofits through fiscal sponsorship, capacity building, and program evaluation.
      website_url: http://uac.org/

project:
    problem: >
        A lot of the nonprofits are not aware of the degree of their fiscal responsibility and potential areas of improvement. While UAC does substantial work in outreach, they would like to enable every nonprofit in the United States to be able to quickly self-analyze their expense rate. One benefit is that this will help make the initial conversation with UAC more substantial and productive.
    features:
        - Search page: the user, typically a nonprofit employee, enters keywords or a specific nonprofit [EIN](http://www.irs.gov/Businesses/Small-Businesses-&-Self-Employed/Employer-ID-Numbers-EINs) to find the nonprofit they are looking for, with results displayed in a paginated table underneath
        - Nonprofit page: underneath the PDF of the most recent [Form 990](http://www.irs.gov/uac/Form-990,-Return-of-Organization-Exempt-From-Income-Tax), there are URLs to the nonprofit's page in NCCS and GuideStar databases, and next to the PDF, there are form fields to enter expense values from the PDF.
        - Form for nonprofit category: under the expense form there are selectors for identification of nonprofit's peer group (state, size, [NTEE code](http://nccs.urban.org/classification/)). Under those there is an 'Analyze' button that a user clicks to see the ranking and potential savings results for this particular nonprofit.
        - Values for overhead rate & chart for ranking (by each expense) within peer group.
        - Values & chart for potential savings (by each expense) from partnership with UAC.
        - Form to save the results and send contact info to UAC.
        - Email notification for the UAC admin, with contact information and analysis results.
    technologies:
        - Django (for web app framework).
        - SQL (databases for nonprofit aggregate financial data)
        - Bootstrap (framework for consistent front-end layout)
        - D3 & Google Charts (for analysis charts)
        - ProPublica API (for nonprofit financials)
    technical_challenges:
        - There were initial meetings with the client where the main goal was to understand the problem and sketch out high level design. After that the first mockup was built and approved by the client. The app was built according to the mockup with slight improvements along the way.
    impact: >
        The app will be used by nonprofit executives to help them gauge the financial health of their entity --  this will hopefully make the issue of nonprofit finances more open and transparent. Potential improvements lie in making the user experience even smoother, which overlays with the overall theme of the app - making nonprofit financial analysis as easy as possible. When there is API access for expense values for each nonprofit, it will be possible to pre-fill those for the user to make the user flow seamless.

code:
    github_repo_name: uac

keywords:
    social_impact_keywords:
        - nonprofits
        - fiscal sponsorship
        - efficiency
    tech_keywords:
        - data analytics
        - data visualization
        - restful APIs

media:
    articles:
        - article_name:
          article_url: http://www.generocity.org/urban-affairs-coalition-building-web-app-to-help-nonprofits-understand-overhead-costs/
        - article_name:
          article_url:
---
