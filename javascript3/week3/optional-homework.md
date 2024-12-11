> [!WARNING]
> These are optional homework exercises that you can complete on top of your [homework project](/homework-projects/readme.md), if you wish. There is no requirement for these to be reviewed, but feel free to ask a mentor if you wish for some feedback.

# Optional Homework

For this weeks homework we will create a web applications that generates a screenshot of a website based on a url. We will combine two API's one to generate the screenshot and one to allow the user to save the screenshot.

API to generate screenshot: https://rapidapi.com/apishub/api/website-screenshot6/?utm_source=RapidAPI.com%2Fguides&utm_medium=DevRel&utm_campaign=DevRel

API to save screenshot: https://crudcrud.com/

Technical spesifications.
1. User can enter a URL for a website and it will send back a screenshot of the website using the website-screenshot API
2. User can hit a button to save the screenshot. It will then save the screenshot and the URL as a resource on crudcrud
3. User can get a list of all screenshots he has saved
4. User can delete a screenshot he has saved

Extra
1. Create another resource called users which takes in an email and password. Create one user.
2. Get back a list of users
3. First show a login form
4. If the email and password matches the one user we created we show the applications else we show an error message.

Extra Extra
1. Create another user
2. When saving a screenshot also save the user email(or another unique identifer)
3. Make sure we are only showing screenshots that the user that is logged in has uploaded

Keep in mind the API key for the website-screenshot and the uuid for crudcrud should be in a secret.js file which is not comitted to git