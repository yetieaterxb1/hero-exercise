# The Assignment
## PROJECT ZIP: 
FIGMA: https://www.figma.com/file/RnVUQ2JobhBYSEjAfl0DQa/Hero-Exercise

## Requirements
* Based on the pdf/png that is included in the provided project zip file make the following changes.
  - Updated hero section
  - Menu fixed to the top of the page (this was already done)
  - UTM query parameters added to the newsletter menu form
* Must include the use of SCSS and JavaScript
* The end result must be responsive (desktop, tablet, and mobile)

## Nice to have
* Fixed menu transition on scroll
* Include additional build optimizations to assets
* Optimize page performance
* Include multiple git commits with comments to show progress
* Include testing


## How to submit the project
You have one week to complete this, but we don't expect you to spend more than a few hours on it.

When it's ready, please send your recruiter a link to the source code, preferably in a GitHub repo but it can be a compressed zip file.

Include a README in your project for local setup and execution (this was already included in the boilerplate). In this, provide a description of your design considerations, assumptions, and trade-offs made during the exercise.


## Notes
The boilerplate for this project used bootstrap but I chose to only use SCSS to follow the guidelines/requirements. 

Following the figma design lead to many "magic numbers" for pixel values. Using a design system would remove the need for these random values, however I wanted to match the figma design as closely as possible. In a bigger project I would also choose to use more sass variables. 

For optimizing page performance, implementing caching would help here but I didn't want to do that for local testing. 

Testing for this page could involve unit tests written in Jest to cover dom elements and javascript functionality. Cypress could also be used to test the entire page and its functionality.


