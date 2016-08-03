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
  name: PhillyFoodFinder
  tagline: Map-based web app to find local food resources", "Report illegal vehicle idling in Philadelphia
semesters:
  - year: 2015
    semester: Fall
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
      - name: The Louisiana Center for Children’s Rights (LACCR)
        description: The Louisiana Center for Children’s Rights is a non-profit that defends the right of every Louisiana child to fairness, dignity, and opportunity. It is the only specialized juvenile defense law office in the country and houses the Louisiana Children’s Advocacy Group that advocates for a more fair and compassionate juvenile justice system.
        website_url: http://www.laccr.org/
code:
  github_repo_name: gpcah
  live_url: http://www.phillyfoodfinder.org/
keywords:
  social_impact_keyword_list: 
    - microfinance
    - education
    - poverty
  tech_keyword_list:
    - crowdsourcing
    = data visualization
screenshots:
  screenshot_url_list:
    - https://github.com/hack4impact/hack4impact.github.io/blob/master/projects/spring-2015/givology/ss01.png
    - https://github.com/hack4impact/hack4impact.github.io/blob/master/projects/spring-2015/givology/ss02.png
media:
  article_url_list: http://generocity.org/philly/2015/08/28/philly-food-finder-app-makes-finding-affordable-food-easier/
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In id elit est. Ut eros tellus, suscipit in nisl in, facilisis commodo purus. Sed nec varius arcu. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Mauris molestie augue vel pharetra laoreet. In laoreet, est non elementum aliquam, metus ligula interdum lacus, non dapibus dolor eros sit amet turpis. Pellentesque dignissim mi vel ligula maximus, sed vestibulum lacus sagittis. Curabitur pulvinar lobortis pharetra.

Donec lobortis finibus arcu, ac aliquet diam. Sed vitae dui et tellus maximus egestas quis ut quam. Nullam a gravida ante. In quis efficitur risus, in congue tortor. Integer sed lobortis urna. Etiam porta varius odio, vel sagittis purus dignissim in. Integer scelerisque dui ut accumsan finibus. Fusce id lacus auctor, malesuada quam vitae, efficitur magna. In tempor, diam ut bibendum accumsan, ex leo porta odio, a blandit sem massa in urna. Proin eleifend malesuada consectetur. Donec turpis justo, faucibus vitae ullamcorper eget, vestibulum eget ipsum. Donec sed accumsan felis, ut aliquam magna. Nullam non felis lorem. Etiam ac elementum lectus, ac lobortis mi. Suspendisse euismod maximus leo.

Integer bibendum quam magna, nec fermentum mi faucibus a. Duis facilisis, nulla at finibus sollicitudin, lacus risus porttitor augue, et tristique ante mauris a velit. Nam ac tincidunt lorem. Nam nec ex quis metus suscipit sodales sed eu est. Cras convallis tristique felis, at ultricies lectus mattis ut. Nulla semper nulla eget sem ultricies, eu rutrum lacus vulputate. Donec finibus, felis at lobortis iaculis, dolor arcu finibus felis, ullamcorper sollicitudin urna magna at dolor. Ut orci elit, egestas ullamcorper semper nec, congue id dui.

Maecenas a lectus sapien. Aliquam quis laoreet enim. Nam malesuada metus velit, quis sodales sem mattis a. Duis dictum, purus ut lobortis pellentesque, tellus augue placerat eros, in ornare nulla massa sed lorem. Etiam rhoncus semper ipsum, eget fringilla velit pharetra quis. In ornare pellentesque nisi id porttitor. Aenean bibendum diam non commodo dapibus. Sed a mi dui. Integer et pretium ante. Pellentesque scelerisque tristique ex, at placerat sem consequat ac. Etiam luctus sagittis dolor, eget tristique dolor aliquet quis. Suspendisse rhoncus, augue fringilla hendrerit condimentum, est enim interdum odio, eu ullamcorper lacus tellus non metus. Fusce faucibus lacus libero. Phasellus laoreet aliquam odio, eu fermentum mauris.

Donec in molestie enim. Nam odio dui, accumsan at nulla in, feugiat eleifend libero. Aliquam pellentesque euismod consequat. Aenean mattis nec risus vehicula porttitor. Mauris efficitur leo eget nisi ultrices, sed venenatis sapien sodales. Donec ante nisl, ultrices non tincidunt in, accumsan vel quam. Aliquam varius imperdiet sem, molestie tincidunt metus semper ac. Fusce felis sapien, malesuada in velit eget, aliquet imperdiet dui. Maecenas suscipit ligula dui, at gravida lacus suscipit id. Curabitur vehicula porta dignissim. Vivamus viverra sed enim quis hendrerit. Mauris eros lacus, sodales non vestibulum vitae, vulputate bibendum erat.
```
