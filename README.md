# Making Headlines
## Review Express

### Background


<img src="daily_planet.jpg">

Weclome to the daily planet, we need your superhuman developer skills to help us share news with the world. We've seen that you have some express knowledge and need you to make us a mock website as soon as possible.

You'll need to use a database of articles to complete this assignment.

## Routes

You'll need the following `article` routes:

* `get`  `/articles` to display a summary  each article.
* `get` `/articles/new` to get a form to save a new article
* `post` `/articles` to save an article
* `get` `/articles/:id` to find an article by id in the array of `articles` and display it.
* `delete` `/articles/:id` to delete a particular article

You'll need the following `site` related routes:

* `get` `/` serve the homepage of your site.
* `get` `/about` serve a static about daily planet page.
* `get` `/contact` serve a static `contact` page.

## Structure

All your article related views should be in an `views/articles` folder. Each article should utilize `ejs` to render the page. Your `site` related views `index`, `about`, and `contact` should also have a folder `views/site`. 

## Styling

Your application must be styled, so be sure to include the following:

```
app.use(express.static(__dirname + '/public'))
```
and a `public/` folder with your stylesheets.


## Bonus

Include some navigation links to help the user navigate the site.