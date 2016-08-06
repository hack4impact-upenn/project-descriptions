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
- `tagline`: *15 words or less*. This should answer the question "What?" about
  the project. Examples: "Map-based web app to find local food resources",
"Report illegal vehicle idling in Philadelphia"

Team(s):

- `year`: The year that the project was worked on (e.g., `2015`, `2016`).
- `semester`: The semester that the project was worked on (`Spring` or `Fall`).
- `pm`: The first and last name of the project's PM.
- `tl` *(optional)*: The first and last name of the project's TL, if applicable
- `developers`: A list of the project's developers during this semester. Names
  should be written `FirstName LastName` and ordered *alphabetically by last
name*.

If this project has been worked on for multiple semesters, teams should be
ordered from *most recent* to *least recent*.

Client(s) *(optional, if the client is under NDA or the project has no
client)*:

- `name`: The name of the client organization.
- `description`: 2-3 sentences about the organization. This can probably be
  paraphrased from their website. E.g. "The Louisiana Center for
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

- `screenshot_urls`: A list of 3-5 links to screenshots of the project. The
  screenshots will be displayed on the website linearly in the order that the
links appear in the list.
- `article_urls` *(optional)*: A list of links to articles and other media
  about this project.

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
    screenshot:
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
    name: Philly Food Finder
    tagline: Map-based web app to find local food resources

team:
    - year: 2015
      semester: Fall
      pm: Paul McCartney
      tl: Theophilus London
      developers:
          - Ali Altaf
          - Abe Lincoln
          - Dhruv Maheshwari
          - Chris Murphy
          - Barack Obama
          - Swapneel Sheth

client:
      - name: The Louisiana Center for Children’s Rights (LACCR)
        description: >
            The Louisiana Center for Children’s Rights is a non-profit that
            defends the right of every Louisiana child to fairness, dignity,
            and opportunity. It is the only specialized juvenile defense law
            office in the country and houses the Louisiana Children’s Advocacy
            Group that advocates for a more fair and compassionate juvenile
            justice system.
        website_url: http://www.laccr.org/
code:
    github_repo_name: gpcah
    live_url: http://www.phillyfoodfinder.org/

keywords:
  social_impact_keywords:
    - microfinance
    - education
    - poverty
  tech_keyword_list:
    - crowdsourcing
    - data visualization

media:
  screenshot_url_list:
    - https://github.com/hack4impact/hack4impact.github.io/blob/master/projects/spring-2015/givology/ss01.png
    - https://github.com/hack4impact/hack4impact.github.io/blob/master/projects/spring-2015/givology/ss02.png
media:
  article_url_list: http://generocity.org/philly/2015/08/28/philly-food-finder-app-makes-finding-affordable-food-easier/
---
```
