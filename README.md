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
- Type: full time; part time; volunteer; 
- Released: (alt: Posted: ?)
- Updated: 

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
