# Code First Girls: Week 5 (Using Bootstrap)

This is an example of how we can structure our website, as well as how we import and use bootstrap.

## Getting Started

You can use this project as a quick way of getting started with your own projects. Just download, fork or clone this repo.

It contains two pages `index.html` and `about.html`, both of which have the `css/style.css` and `js/main.js` files linked already. It also includes CSS and JS from Bootstrap.

## About this project

This project contains the following:

```
- index.html
- about.html
- css
-- style.css
- js
-- main.js
```

## About Bootstrap

More information on Bootstrap 3.3.7 can be found here:

* https://getbootstrap.com/docs/3.3/

## Lesson 5

### What is hard about CSS?

* Different browsers will render CSS with subtle differences
* Different size screens mean websites will look different (mobile vs. desktop)

### What are the problems we need to solve?

* We need CSS fallbacks for differences in browser rendering
* We need to make sure our websites work on any device shown, regardless of screen size
* We need to become more efficient at writing code

### So what could the solution be?

* We can use a framework! It's a skeleton of code that provides generic functionality
* We can use it to extend our own code
* We can override the framework with our own code

### Introducing... Bootstrap! 👩🏻‍🎨

* It's a framework, originally made and maintained by a team at Twitter
* It's a set of ready-made CSS & JavaScript files for a whole bunch of popular components
* It's cross browser AND responsive 💪

### So how do I use Bootstrap?

* First you need to link it to the head of your HTML page
* You can either download Bootstrap.min.css locally and put it in your `css` folder, or you can use a link to the Bootstrap CDN
* Locally: `<link rel="stylesheet" href="css/bootstrap.min.css">`
* CDN: `<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">`
* If you use the CDN link, you'll need to make sure you're connected to the internet for it to work
* Then you can use bootstrap classes in your code e.g. `<div class="container">...</div>` and it will adopt the Bootstrap CSS!

### What if I want to use my own css?

* You still can! Just make sure the link to your css is included *AFTER* the Bootstrap css
* For example:

```
	<link rel="stylesheet" href="css/bootstrap.min.css" crossorigin="anonymous">
	<link rel="stylesheet" href="css/style.css">

```

* This means your css will override the Bootstrap css.

### What kind of things can I do with Bootstrap?

* You can read all about the Bootstrap CSS here: https://getbootstrap.com/docs/3.3/css/
* But let's look at a few examples...

#### Tables

Bootstrap tables look pretty cool! 
You can see some here: https://getbootstrap.com/docs/3.3/css/#tables

```
<table class="table">
	<tr>
		<td>Item</td>
		<td>Cost</td>
	</td>
	<tr>
		<td>Bananas</td>
		<td>50p</td>
	</tr>
	<tr>
		<td>Apples</td>
		<td>45p</td>
	</tr>
</table>
```

And then you can add additional classes, to change the styling...

For example:

* Striped: `<table class="table table-striped">...</table>`
* With a border: `<table class="table table-bordered">...</table>`

#### Buttons

If you want to add buttons to your website, Bootstrap has a whole bunch already styled for you!
You can read all about them here: https://getbootstrap.com/docs/3.3/css/#buttons

But here are a few examples for you to try out:

* `<button type="button" class="btn btn-default">Default</button>`
* `<button type="button" class="btn btn-primary">Primary</button>`
* `<button type="button" class="btn btn-success">Success</button>`
* `<button type="button" class="btn btn-info">Info</button>`
* `<button type="button" class="btn btn-warning">Warning</button>`
* `<button type="button" class="btn btn-danger">Danger</button>`

