# object-literals

## Description
In the world of programming, we are often faced with many complex functions and methods, and if we didnt have an efficient way to lookup or organize our code, it would become really time consuming.  Fortunately, and over time, programmers find ways to make things more efficient and offer up common solutions to repeating problems.

One of those problems is:

<blockquote>
My code is all over the place, and as the code grows and I add more to my application, how do I write my code so that everything is more easily organized and simple to use.  Also, I want to make sure that I am not writing functions/methods that could potentially be overridden?
</blockquote>

We will be practicing the object literal pattern in this assignment.

## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand the utility of using object literals to organize your code.
* Start to understand separation of concerns
* Reinforcement of iteration over an array of objects.

### Performance Objectives

After completing this assignment, you be able to effectively use

* Object literals to break out methods and operations to consume data and put it on a web page.
* Iterating over data so that you can combine it with HTML markup.


## Details

### Deliverables

* A repo containing at least:
  * `data.js`
  * `bower.json` (that contains yoru dependencies)
  * `main.js`
  * `.gitignore`
  * `index.html`

### Requirements

* Create a separate `data.js` file that will hold your product data in the form of an array of objects.
* This `data.js` should define a global variable `var products` to the array and each product is an object iwth properties with a length of 6.
* Product should have the following properties:
  - Name of product
  - Description of product
  - Price of product
  - Image of product.
* Create a `main.js` file that contains an object literal that holds the methods used to put the data on the page.
* `main.js` should also have a Document Ready portion where the object is initialized.
* There should be no HTML markup in your data.js file, only data.
* You can make products for anything.

## Normal Mode

Create a single page products listing that includes the name, description, image, and price of at least 6 products.  Markup cannot exist on the page for each individual product, but should be inserted using jQuery/javascript in your main.js file.  Your data file also should not contain any html markup.

## Hard Mode

In addition to Normal Mode, use underscore for iteration and for templates.



## Additional Resources

* [Read Rebecca Murphy's awesome blog post on using object literals](http://rmurphey.com/blog/2009/10/15/using-objects-to-organize-your-code/)
