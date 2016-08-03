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

Length/size:
- `tagline`: < 15 words
- `semesters/name`: `fYY` or `sYY`
- `keywords`: (lists of 2-4 keywords
- `description`: (2-4 sentences)

Optional:
- `tl`: (optional)
- `live_url`: (optional if not completed)
- `keywords`: (lists of 2-4 keywords, sorted alphabetically)
- `screenshot_url_list`: (sorted linearly like how you would navigate)
- `clients`: (optional if client under NDA or no client)

Sorting:
- `semesters`: (sorted from most to least recent)
- `devs`: (sorted alphabetically by first name)
- `article_url_list` (sorted by most to least recent)

## Template

```markdown
---
layout: project

project:
  summary:
    name:
    tagline:
    semesters:
      - 
      - 
      - 
  team:
    `pm`:
    `tl`: (optional)
    `devs`: (sorted alphabetically by first name)
      - Aa Dd
      - Cc Bb
  `code`:
    `github_repo_name`:
    `live_url`: (optional if not completed)
  `keywords`: (lists of 2-4 keywords, sorted alphabetically)
    `social_impact_keyword_list`:
      - a
      - b
      - c
    `tech_keyword_list`: (2-4 keywords)
      - d
      - e
      - f
  `screenshots`:
    `screenshot_url_list`: (sorted linearly like how you would navigate)
      - http://hack4impact.org/first
      - http://hack4impact.org/second
  `media`:
    `article_url_list` (sorted by most to least recent)
      - http://hack4impact.org/february16
      - http://hack4impact.org/january16
`clients`: (optional if client under NDA or no client)
  - `name`:
    `description`: (2-4 sentences)
    `website_url`
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
