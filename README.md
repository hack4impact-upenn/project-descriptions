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

`project`:
  `summary`:
    `name`:
    `tagline`: < 15 words
    `semesters`:
      - s16
      - f15
      - s15
  `members`:
    `pm`:
    `tl`: optional
    `devs`*:
      - Aa Bb
      - Cc Dd
  `code`:
    `github_repo_name`:
    `live_url`:
  `keyword_lists`:
    `social_impact_keyword_list`: 2-4 keywords
    `tech_keyword_list`: 2-4 keywords
  `screenshots`:
    `screenshot_url_list`:
      - first url
      - second url
    
  `media`:
    
- `article_url_list`

`clients`:
  - `name`: if NDA, leave blank
    `description`: usually comes from client, 2-4 sentences. If NDA, broad!
    `website_url`

## Template

```markdown
---
layout: project

project_name:
project_tagline:
project_semesters:

client_name:
client_description:

pm:
tl:
developers:
designers:

github:
client:
app:
articles:
screenshots:

social_impact_keywords:
tech keywords:
---

Add your project description here, answering each question in 2-4 sentences.

Why did client approach us?

Why was our project technically challenging?

Why was our project socially impactful?

What features did we build and how technologically (for general audience)?

Note that you _can_ use standard **Markdown** formatting here. Please don't
include any headers or non-paragraph elements, however.

```

## Example - TODO

Here's an example of the required formatting.

```markdown
---
layout: profile
first_name: Benjamin
last_name: Franklin
class_of: 1744
alum: true

email: benf@seas.upenn.edu
twitter: benfranklin
github: bfranklin
linkedin: https://linkedin.com/in/benjamin.franklin
---

Benjamin Franklin was one of the Founding Fathers of the United States. A
renowned polymath, Franklin was a leading author, printer, political theorist,
politician, freemason, postmaster, scientist, inventor, civic activist,
statesman, and diplomat. As a scientist, he was a major figure in the American
Enlightenment and the history of physics for his discoveries and theories
regarding electricity.
```
