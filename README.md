# Hack4Impact Project Descriptions

This repository contains basic information about Hack4Impact projects that will
be displayed on the [organization website](http://hack4impact.org/projects).

Feel free to open a pull request to update your information at any time, but
please do not commit to `master` or merge the request without approval.


## Instructions

Copy the template below into a new file `projectname.md`. Each project description
is a Markdown file with a YAML header marked by `---`. The header contains some
metadata, and the document body should contain paragraphs about the project.

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
- `client_name`
- `client_description`: Usually from client, in 2-4 sentences. 

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

Links
N/A for app if not live (hopefully client has website :P)
Github repo *

Your answer
This is a required question
Client organization website *

Your answer
Live link! *

Your answer
Tags
2-3 words/phrases/categories about project
Social impact keywords *
ie microfinance, education, food rights, juvenile justice, law. These can be pulled directly from the description of the client organization and/or the description of the project.

Your answer
Tech keywords *
ie crowdsourcing, gamification, mobile, mapping, data analytics. These *should not* include specific technologies used (that will come later!)

Your answer
Project
If you have a RELATED LINK for description, put “[ ]” around phrase and include link in “()” right after (markdown)
1-3 sentences about the problem *
Why did the client approach us? What general product did they want? It might help to have statistics/description of general problem (22% of Philly county residents are food insecure; cost of a sentence has a huge impact on a judge's ruling)
Your answer

Bulleted list of features *
5-10 bullet points. Can mention languages/tech used, but try to avoid and also explain features in English
Your answer

2-3 sentences on a technical challenge that you faced during the project *
Your answer

Bulleted list of languages/technologies used, with purpose in parentheses *
ie “D3 (for data visualization)”
Your answer

1-3 sentences on how app will be/is being used, and its potential/actual impact *
feel free to elaborate on potential impact and future extensions of projects
Your answer

Are you allowed by client to send screenshots? *
If so, please email ANY USEFUL APP SCREENSHOTS to Yoni
Yes
No
Media mentions/other related links!
Thanks!!!


### Exec board members

In addition to the fields listed above, exec board members should include the
following (note that `role` is indented):

```
---
exec:
  role: External Relations Chair
---
```

### Alumni

In addition to the fields listed above, organization alumni should include the
following:

```
---
alum: true
---
```


## Template

```markdown
---
layout: profile

first_name:
last_name:
class_of:

email:
website:
github:
twitter:
linkedin:
---

Add your bio here.

Note that you _can_ use standard **Markdown** formatting here. Please don't
include any headers or non-paragraph elements, however.
```

## Example

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
