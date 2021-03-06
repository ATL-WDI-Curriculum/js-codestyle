<!--
This file is auto-generated from a 'template.md'
file using the 'md-process' script.
Therefore *DO NOT* edit this file directly!
Instead edit the template file and then run 'md-process'.
-->

# JavaScript Code Style

## Table of Contents

* [What is Code Style?](#what-is-code-style)
* [Why is Good Code Style Important?](#why-is-good-code-style-important)
* [Tools: Linters, Beautifiers, and Editor Plugins](#tools-linters-beautifiers-and-editor-plugins)
  * [Linters](#linters)
  * [Editor Plugins](#editor-plugins)
* [Exercise](#exercise)
* [For Further Reading](#for-further-reading)

## What is Code Style?

A set of recommended conventions for styling your code. Styling includes:

* variable, function, and class naming
* indentation
* comments
* use of white space
* placement of opening and closing brackets
* many others...

![Tabs vs. Spaces](images/tabs-vs-spaces.png)

Often a specific Code Style is documented in a Style Guide. There are many style guides to choose from, such as:

* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
* [Google JavaScript Style Guide](https://google.github.io/styleguide/javascriptguide.xml)
* [W3 Schools JavaScript Conventions](http://www.w3schools.com/js/js_conventions.asp)
* [jQuery's JavaScript Style Guide](https://contribute.jquery.org/style-guide/js/)

## Why is Good Code Style Important?

* Readability (for others and your future self)
* Consistency - all of the code in a specific project is consistantly formatted
* Helps in identifying and removing careless mistakes (typos)
* Helps in identifying WET code - DRY it up!

## Tools: Linters, Beautifiers, and Editor Plugins

There are many tools that can help us write well-styled code.

### Linters

Linters are tools that analyze our source code looking for code style violations and potential bugs. Popular JavaScript code linters are:

* [JSLint](http://www.jslint.com/)
* [JSHint](http://jshint.com/)
* [JavaScript Code Style - JSCS](http://jscs.info/)
* [ESLint](http://eslint.org/)

Read [A Comparison of JavaScript Linting Tools](http://www.sitepoint.com/comparison-javascript-linting-tools/) for a detailed comparison of these linting tools.

### Editor Plugins

There are many packages for both Sublime and Atom that aid in checking your code for good coding style. Some of these packages will check your code as you type and some will wait for you to execute the check. These tools fall into one of the following categories:

* Linter - checks your code to ensure that it conforms to a selected coding style guide
* Beautifier - reformats your code, adding indentation, aligning braces, etc.

## Exercise

See [CodeStyle Exercise](https://github.com/ATL-WDI-Exercises/codestyle-and-linting) for instructions.

## For Further Reading

* [JavaScript Style Guides and Beautifiers](https://addyosmani.com/blog/javascript-style-guides-and-beautifiers/)
* [10 Best JavaScript Style Guides](http://noeticforce.com/best-javascript-style-guide-for-maintainable-code)
* [Online JavaScript Beautify](http://www.cleancss.com/javascript-beautify/)
