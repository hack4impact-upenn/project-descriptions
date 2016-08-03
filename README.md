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

### Header fields

Template metadata:
- `layout`: **Don't change this.** This should always have the value `project`.
  It's used internally by the site generator ([Jekyll](https://jekyllrb.com/))
  to render the Markdown file into a webpage.

Project info:
- `project_name*`
- `project_tagline*`: "What is project?" in < 15 words (Tweetable).
- `project_semesters*`: [fYY/sYY].

Client info:
- `client_name`: if NDA, leave out
- `client_description`: Usually from client, in 2-4 sentences. If NDA, describe VERY broadly.

Project team:
- `pm*`
- `tl`
- `developers*`: [names]
- `designers`: [names]

Links:
- `github*`: repo (not URL).
- `client*`: url
- `app`: url
- `articles`: [url]
- `screenshots*`: [url]

Keywords:
- `social_impact_keywords`: [2-4 keywords]
- `tech keywords`: [2-4 keywords]

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

What featuress did we build and how did we build them programatically (aimed at a general, non-necessarily-technical audience)?

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
