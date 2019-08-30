# NPS-API-Assignment
#Assignment

Review The National Parks Services API documentation and create an API key. You'll add this key to your request as a query parameter (api_key=).
https://www.nps.gov/subjects/developer/get-started.htm
Review the /parks enpoint and data model to understand how it works.
https://www.nps.gov/subjects/developer/api-documentation.htm#/parks/getPark
https://www.nps.gov/subjects/developer/api-documentation.htm#/definitions/Park
Create a new app and push it to GitHub.
When you're done, submit the link to your GitHub repo at the bottom of the page.
#Requirements

The user must be able to search for parks in one or more states.
The user must be able to set the max number of results, with a default of 10.
The search must trigger a call to NPS's API.
The parks in the given state must be displayed on the page. Include at least:
Full name
Description
Website URL
The user must be able to make multiple searches and see only the results for the current search.

Example Results
https://api.nps.gov/api/v1/parks?stateCode=ga&limit=10&q=georgia
