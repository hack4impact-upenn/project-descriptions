# Hack4Impact Project Descriptions

This repository contains basic information about Hack4Impact projects that will
be displayed on the [organization website](http://hack4impact.org/projects).

Feel free to open a pull request to update your information at any time, but
please do not commit to `master` or merge the request without approval.


## Instructions

Copy the template below into a new file `project-name.md`. Each project
description is a Markdown file with a YAML header marked by `---`. The header
contains some metadata, and the document body should contain paragraphs about
the project (described below). All header fields are **required** unless marked
otherwise.

### Header fields

- `layout`: **Don't change this.** This should always have the value `project`.
  It's used internally by the site generator ([Jekyll](https://jekyllrb.com/))
  to render the Markdown file into a webpage.

Summary:

- `name`: The name of the project.
- `tagline`: 15 words or less. This should answer the question "What?" about
  the project. Examples: "Map-based web app to find local food resources",
"Report illegal vehicle idling in Philadelphia."

Team(s):

- `year`: The year that the project was worked on (e.g., `2015`, `2016`).
- `semester`: The semester that the project was worked on (`Spring` or `Fall`).
- `pm`: The first and last name of the project's PM.
- `tl` *(optional)*: The first and last name of the project's TL, if applicable.
- `developers`: A list of the project's developers during this semester. Names
  should be written `FirstName LastName` and ordered alphabetically by last
name.

If this project has been worked on for multiple semesters, teams should be
ordered from *most recent* to *least recent*.

Client(s): *(optional, if the client is under NDA or the project has no
client)*

- `name`: The name of the client organization.
- `description`: 2-3 sentences about the organization. This can probably be
  paraphrased from their website. For example, "The Louisiana Center for
Children’s Rights is a non-profit that defends the right of every Louisiana
child to fairness, dignity, and opportunity. It is the only specialized
juvenile defense law office in the country and houses the Louisiana Children’s
Advocacy Group that advocates for a more fair and compassionate juvenile
justice system."
- `website_url` *(optional)*: The client's official website. If the client
  doesn't have a website, leave this field blank.

Project:

- `problem`: 1-3 sentences about the problem. Why did the client approach us?
  What general product did they want? It might help to have
statistics/description of general problem (22% of Philly county residents are
food insecure; cost of a sentence has a huge impact on a judge's ruling)
- `features`: List of 5-10 of the project's features. If you must, you can
  mention languages/tech used in the project, but also try to explain the
features in English.
- `technologies`: List of languages/technologies used, with the purpose for
  using the language/technology in this project in parentheses (e.g., `D3 (for
data visualization)`)
- `technical_challenges`: List of 2-to-3-sentence blurbs about technical
  challenges that you faced during the course of this project. There should be
at least 1 technical challenge included for each semester that this project has
occurred.
- `impact`: 1-3 sentences on how app will be/is being used, and its
  potential/actual impact. Feel free to elaborate on potential impact and
future extensions of the project.

Code:

- `github_repo_name`: The name of the github repo where the code for this
  project lives. (e.g., `maps4all` -- *not* the full URL
`https://github.com/hack4impact/maps4all`)
- `live_url` *(optional, if deployment is not complete)*: Where this project
  lives on the web.

Keywords:

- `social_impact_keywords`: A list of 2-4 social impact keywords that relate to
  this project. Keywords should be ordered *alphabetically* in the list.
- `tech_keywords`: A list of 2-4 tech keywords that relate to this project.
  Keywords should be ordered *alphabetically* in the list.

Media:

- `screenshots`: A list of 3-5 links to screenshots (`screenshot_url`) and
  captions (`screenshot_caption`) of the project. The screenshots will be
displayed on the website linearly in the order that the links appear in the
list.
- `article` *(optional)*: A list of article names (`article_name`) and links
  (`article_url`) about this project.

## Template

```markdown
---
layout: project

summary:
    name:
    tagline:

team:
    - year:
      semester:
      pm:
      tl:
      developers:
          -
          -
          -
    - year:
      semester:
      pm:
      tl:
      developers:
          -
          -
          -

client:
    - name:
      description:
      website_url:
    - name:
      description:
      website_url:

project:
    problem:
    features:
        -
        -
        -
        -
        -
    technologies:
        -
        -
        -
    technical_challenges:
        -
    impact:

code:
    github_repo_name:
    live_url:

keywords:
    social_impact_keywords:
        -
        -
        -
    tech_keywords:
        -
        -
        -

media:
    screenshots:
        - screenshot_caption:
          screenshot_url:
        - screenshot_caption:
          screenshot_url:
        - screenshot_caption:
          screenshot_url:
    articles:
        - article_name:
          article_url:
        - article_name:
          article_url:
---

```

## Example

Here's an example of the required formatting.

```markdown
---
layout: project

summary:
    name: Federalist Papers
    tagline: >
        A collection of 85 articles and essays promoting the ratification of
        the United States Constitution

team:
    - year: 1787
      semester: Fall
      pm: Alexander Hamilton
      tl: James Madison
      developers:
          - John Jay

client:
    - name: United States Constitution
      description: >
          The Constitution of the United States of America is the supreme law
          of the United States. Empowered with the sovereign authority of the
          people by the framers and the consent of the legislatures of the
          states, it is the source of all government powers, and also provides
          important limitations on the government that protect the fundamental
          rights of United States citizens.
      website_url: https://www.whitehouse.gov/1600/constitution

project:
    problem: >
        The process set out in the Constitution for its ratification provides
        for much popular debate in the states. The Constitution cannot take
        effect until it had been ratified by nine of the thirteen state
        legislatures -- unanimity is not required. The Federalists need to
        convince the country of the Constitution's merit.
    features:
        - Analysis of the groups opposing the proposed Constitution.
        - Warnings of the dangers of factions.
        - Advocacy for a large republic.
        - >
              Explanation of the structure of the Constitution, its checks and
              balances, and how it protects the rights of the people.
    technologies:
        - ink
        - quill pens
        - paper
    technical_challenges:
        - >
              Eighteenth century printing technology prevented the regular
              publishing of the Federalist papers outside New York state.
              Hamilton tirelessly worked to have the essays reprinted in
              newpapers outside of New York, and indeed they were published in
              several other states where the Constitution ratification debate
              was taking place; however, in other parts of the country they
              were often overshadowed by local writers.
    impact: >
        To this day, the Federalist Papers serve as an invaluable resource for
        understanding some of the framers' intentions for the Constitution.

code:
    github_repo_name: federalist-papers
    live_url: https://www.congress.gov/resources/display/content/The+Federalist+Papers

keywords:
    social_impact_keywords:
        - democracy
        - education
        - ratification
    tech_keywords:
        - crowdsourcing

media:
    screenshots:
        - screenshot_caption: The Federalist Papers
          screenshot_url: https://upload.wikimedia.org/wikipedia/commons/1/12/The_Federalist_(1st_ed,_1788,_vol_I,_title_page).jpg
        - screenshot_caption: Alexander Hamilton, author of 51 articles of the Federalist Papers
          screenshot_url: https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Alexander_Hamilton_portrait_by_John_Trumbull_1806.jpg/1280px-Alexander_Hamilton_portrait_by_John_Trumbull_1806.jpg
        - screenshot_caption: James Madison, author of 26 articles of the Federalist Papers
          screenshot_url: https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/James_Madison.jpg/1280px-James_Madison.jpg
        - screenshot_caption: John Jay, author of 5 articles of the Federalist Papers
          screenshot_url: https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/John_Jay_%28Gilbert_Stuart_portrait%29.jpg/440px-John_Jay_%28Gilbert_Stuart_portrait%29.jpg
    articles:
        - article_name: Better Than a 'Hamilton' Shout-Out? John Jay Manuscript Surfaces
          article_url: http://artsbeat.blogs.nytimes.com/2016/05/05/better-than-a-hamilton-shout-out-john-jay-manuscript-surfaces/?_r=0
        - article_name: Reviewing the Authors Of the Federalist Papers
          article_url: http://www.nytimes.com/1981/05/24/nyregion/l-reviewing-the-authors-of-the-federalist-papers-131051.html

---

```
