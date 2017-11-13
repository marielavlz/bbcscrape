# New York Times Article Scraper!

#### What is it?

A full stack app that scrapes articles from the New York Times and allows users to make and save comments on the articles.

#### How does it work?
Users will hit the _scrape articles_ button at the top, which will pull articles from the New York Times website onto the page. The user then has the option of hitting _save_ in order to save any article of their choosing. To view the saved article, one needs only to click on the saved articles link at the top. 

Once in the saved articles linked, a user may add a note, remove a note, or remove a saved article therefore returning it to the main page. The application utilizes a non-SQL Mongo database and Mongoose to pull the articles and save the notes. 

#### NPM Requirements
* express
* express-handlebars
* mongoose
* body-parser
* cheerio
* request

#### Screenshots

![Main Page View](/public/assets/images/front.png)

![Saved Page View](/public/assets/images/saved.png)

![Notes View](/public/assets/images/notes.png)
