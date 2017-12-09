# Verge Scraper
 A Node.js & MongoDB webapp that web-scrapes news data from The Verge and allows users to comment about what they have read. Users can also delete unwanted comments.

## Functionality

On the backend, the app uses express to serve routes and mongoose to interact with a MongoDB database.

On the frontend, the app uses handlebars for templating each article and materialize as a styling framework. 
The app also uses jQuery and AJAX to help with making post requests.

And for webscraping, the app uses the request and cheerio node packages. All webscrapping code can be found in the controllers.js file.

## Technologies

* MongoDB
* Node Packages
* cheerio 
* Handlebars
* expresss
* JQuery
* Materialize

## See it live here [Verge Scrapper](https://tranquil-dawn-20997.herokuapp.com/articles)


