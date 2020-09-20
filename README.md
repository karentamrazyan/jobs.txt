# jobs.txt

jobs.txt specification

Separators: new line, pipe (|), ;.

## Fields / Properties

- [mandatory, default] Role: (alt: Title: ?) e.g. Solution Architect
- ID: 
- Description: *no line breaks allowed* *hacks: two blanks = new line, three blanks = new paragraph*
- Locations: (Location: ?) remote
- Contact: 
- Salary: -> Compensation: (includes salary, equity)
- Languages: 
- Travel: (can be in %)
- ? Keywords: -> Skills: 
- Employer: company name, e.g. Amazon
- Type: full-time; part-time; volunteer; internship; contract
- Released: (alt: Posted: ?)
- Updated: 

Vlad's suggestions: "Valid from: , Valid until: "

EXAMPLE:

Role: Solution Architect|ID: SL23454|Description: Bla-bla-bla|Location: remote, EU; Berlin, Germany; Paris, France|Contact: example.com/contact|Compensation: equity|Languages: English|Travel: 20%|Skills: aws; mongodb|Employer: Tesla Motors|Type: full-time|Released: 20-09-2020


## Challenges

- description and other texts in multiple languages for the same job position

## Alternatives

[JobPosting Structured Data](https://developers.google.com/search/docs/data-types/job-posting)

## Similar Concepts

- [robots.txt](https://www.robotstxt.org/)
- ads.txt

## TODOs

- create jobs.txt validator (/validator?)
- create jobs.txt generator (/generator?)
- write jobs.txt parser in JS, node
