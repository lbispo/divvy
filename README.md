# Sessile Lite

## Introduction

Sessile Lite is a CSS3 layout library that allows easy implementation of grid layouts, single-row layouts, wrapping layouts, and navigation positioning. It is designed as a tool for rapid prototyping, or as a full-fledged layout solution for small websites and web apps. Sessile Lite is:

* Easy to use;
* Fully responsive;
* Mobile-first;
* Less invasive of your markup;
* **Not** opinionated about your breakpoint widths;
* **Not** based on a 12-column grid skeleton;
* Small!

## Implementation

Download the .zip or clone the repository. Included are:

- a sample HTML page;
- a CSS subdirectory containing three CSS files &ndash; narrow.css, medium.css, and wide.css &ndash; plus minified versions of same (narrow.min.css, medium.min.css, and wide.min.css).

Copy the CSS folder to your working directory, and link the separate CSS files into your document and choose your own breakpoints:

	<link rel="stylesheet" href="css/narrow.css">
	<link rel="stylesheet" href="css/medium.css" media="screen and (min-width: 40em)">
	<link rel="stylesheet" href="css/wide.css" media="screen and (min-width: 60em)">

Add classes to your markup to implement the layout rules. Layouts are accomplished by adding classes to a *parent* element, rather than having to add classes to each and every layout item &ndash; keeping markup generally cleaner. Examples:

	<main class="one fourth left"></main>
	<article class="thirds"></article>
	<header class="row three right"></header>
	<ul class="wrap"></ul>

By default, layouts applied to sub-module elements (text elements, etc.) render in narrow view; module elements (`header`, `footer`, `aside`, or any direct child of `article`) in medium view; and architectural elements (`main`, `body > div`) in wide view. Several mechanisms for overrides are provided.

Add your own design on top of the library by including a fourth CSS file of your own, perhaps named *theme.css.*

The sample HTML page included in the project contains many examples and an extensive explanation of features.

## Versions

This project is currently in beta. Beta testers welcome!

## Licence terms

This project is completely free and open source. Do what ye will!

## Related resources

There will be a tutorial on [sessile.net](http://www.sessile.net/sessilite/tutorial.html) shortly. For now, message me here at GitHub with any questions or suggestions!	