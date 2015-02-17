# backbone-views

## Description
Welcome to MV* Frameworks!  Now that we know a little backbone, we are going to build an Imdb act-alike, except we're going to crud movies.

## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand single responsibility principle
* Basic understanding of Backbone.Model, Backbone.Collection, Backbone.View constructors
* Understand difference between a Model View and Collection View.

### Performance Objectives

After completing this assignment, you be able to effectively use

* Use Backbone.Model, Backbone.Collection, Backbone.View
* Use the events object in views to effectively crud models
* Use Collection Views to render information into DOM


## Details

### Deliverables

* A repo containing at least:
  * `bower.json`
  * `main.js`
  * `index.html`
  * `views.js`
  * `collections.js`
  * `models.js`

### Requirements

* Create a backbone application that showcases movies.
* You must be able to Create, Read, Update, and Delete Movies
* Movies, as a collection should be rendered on the page.
* You must use the events object to create events to CRUD movies.
* Model must have a default Movie photo, and at minimum include the following Properties:
  - Title
  - Release Date
  - Synopsis

## Normal Mode

Create an IMDB like application with Backbone.js that allows you to add, remove, and list movies to the page.

## Hard Mode

In addition to Normal Mode, your application will also have routing, so that when you click on a movie you are taken to a separate view that has more details about the movie as well as reviews.  You will also need to CRUD reviews and have them associated with the specific movie.

## Nightmare Mode

Complete Normal and Hard Mode, but create the application using [Marionette.js](http://marionettejs.com/) 

## Additional Resources


* [Backbone Fundamentals Book by Addy Osmani](http://addyosmani.github.io/backbone-fundamentals/)
* Read [Single Responsibility Principle](http://code.tutsplus.com/tutorials/solid-part-1-the-single-responsibility-principle--net-36074)
