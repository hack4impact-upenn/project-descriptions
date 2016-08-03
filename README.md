# Hack4Impact Project Descriptions

This repository contains basic information about Hack4Impact projects that will
be displayed on the [organization website](http://hack4impact.org/projects)
(or will be soon!).

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
- `project_name*`: Project's name.
- `project_tagline*`: "What is project?" in <15 words (Tweetable).
- `project_semesters*`: [fYY/sYY].

Client info:
- `client_name`: Client's name.
- `client_description`: Client description, usually from client, in 2-4 sentences. 

Project team:
- `pm*`: project manager's name
- `tl`: tech lead's name
- `devs`: [developers' names]

Project contact information (each of these fields are optional, so only include the ones
you want):
- `email`: An email address that can be used to contact you. Note that this
  address will be made public, so you may want to set up mail filters or use a
  different email than your primary one if you choose to include an email.
- `website`: The _URL_ of your personal website.
- `github`: Your GitHub _username_ (not URL).
- `twitter`: Your Twitter _handle_, without the leading `@`.
- `linkedin`: The _URL_ of your LinkedIn profile (their username conventions are
  somewhat inconsistent).

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
