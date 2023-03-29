# URL_Shortner

URL Shortener Web Application 

What will our Web app do (Objectives)?
1. As the name suggests, it shortens URLs.
2. Users can also save URLS by coming to the web app.

Why do we need a URL Shortener?
Sometimes we need to share or send links and this can be tiresome and annoying to copy and paste long URLs. That is where URL shorteners come in. Not only it helps in shortening the URL but it also allows the user to copy the shortened URL with a click of a button.

The project consists of 2 parts:
1. Frontend (done with HTML, CSS, and Bootstrap)
2. Backend - Flask (Python)
3. Backend - Database ORM

Front-End Information
 The front end consists of 2 web pages:
1. Home Page - A page will be shown where the user can enter the URL he/she wants to shorten. After the ‘shorten’ button is clicked, the shortened URL is displayed in the text field which the user can copy using the copy button.
2. History Page - Containing all the Original URLs along with the Shortened URLs.

Project Workflow
1. Users can enter the URL they want to shorten. After entering a URL, click on the ‘Shorten’ URL button to display the shortened URL in the following text field which can be copied by clicking on the copy button.
2. After the ‘Shorten’ button is clicked, the URL that is entered is saved in our database with the shortened URL. It is saved in the database so that the user can look into the previous URLs he entered in our web app with their shortened URL.
3. Try to verify whether the URL entered by the user is correct or not.
