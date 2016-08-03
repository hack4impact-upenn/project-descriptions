# Hack4Impact Project Descriptions

This repository contains basic information about Hack4Impact projects that will
be displayed on the [organization website](http://hack4impact.org/projects).

Feel free to open a pull request to update your information at any time, but
please do not commit to `master` or merge the request without approval.


## Instructions

Copy the template below into a new file `project-name.md`. Each project description
is a Markdown file with a YAML header marked by `---`. The header contains some
metadata, and the document body should contain paragraphs about the project
(described below).

Template metadata:
- `layout`: **Don't change this.** This should always have the value `project`.
  It's used internally by the site generator ([Jekyll](https://jekyllrb.com/))
  to render the Markdown file into a webpage.

### Data information
Formatting:
- `semesters/name`: title

Length/size:
- `tagline`: < 140 characters
- `keywords/*`: lists of 2-4 keywords
- `description`: 2-4 sentences
- `screenshot_urs`: 3-5 urls

Optional:
- `tl`: optional if position did not exist
- `live_url`: optional if deployment not completed
- `clients`: (optional if client under NDA or no client)

Sorting:
- `semesters`: sorted from most to least recent
- `devs`: sorted alphabetically by first name
- `article_url_list` sorted by most to least recent
- `keywords` lists: sorted alphabetically
- `screenshot` lists`: sorted linearly, like how you would navigate

## Template

```markdown
---
layout: project

summary:
  name:
  tagline:
semesters:
  - year:
    semester:
    team:
      pm:
      tl:
      developers:
      -
      -
      -
      -
      -
      -
    clients:
      - name:
        description:
        website_url:
      - name:
        description:
        website_url:
code:
  github_repo_name:
  live_url:
keywords:
  social_impact_keyword_list:
    -
    -
    -
    -
  tech_keyword_list:
    -
    -
    -
    -
screenshots:
  screenshot_url_list:
    -
    - 
    -
    -
    -
media:
  article_url_list
    -
    -
    -
---

Add your project description here, answering each question in 2-4 sentences.

Why did client approach us?

Why was project technically challenging?

Why was project socially impactful?

What features did we build and how did we build them technologically
(for a general audience)?

Note that you _can_ use standard **Markdown** formatting here. Please don't
include any headers or non-paragraph elements, however.

```

## Example - TODO

Here's an example of the required formatting.

```markdown
---
layout: project

summary:
  name: Project Name
  tagline: An app that connects nonprofits in need of high-tech solutions with students passionate about building technology for good.
semesters:
  - year: 2015
    semester: fall
    team:
      pm: Paul McCartney
      tl: Theophilus London
      developers:
      - Abe Lincoln
      - Ali Altaf
      - Barack Obama
      - Chris Murphy
      - Dhruv Maheshwari
      - Swapneel Sheth
    clients:
      - name: Philly Food Finder
        description:
        website_url:
      - name:
        description:
        website_url:
code:
  github_repo_name:
  live_url:
keywords:
  social_impact_keyword_list:
    -
    -
    -
    -
  tech_keyword_list:
    -
    -
    -
    -
screenshots:
  screenshot_url_list:
    -
    - 
    -
    -
    -
media:
  article_url_list
    -
    -
    -
---
