# ![joomla-spc](media/silverpclogo.png)

> Helping you build a better Joomla

# Generator-joomla-spcv2 [![Build Status](https://secure.travis-ci.org/pacav69/generator-joomla-spc.png?branch=master)](https://travis-ci.org/pacav69/generator-joomla-spc)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)


A component generator for [Yeoman](http://yeoman.io).

## What It Does
Using this generator, you can quickly and effortlessly *scaffold* out a new [joomla](http://joomla.org) extension, using recommended MVC design pattern and coding standards.  These include:


* Component
* Plug-in 
* Template Front End
* Template Admin
* Module
           
So rather than manually creating your own ``config.xml`` and other config files, you just need to use this generator, type in your options, and everything is set up for you.  If you want to add a new model, view, or controller, just use the sub-generators!

Stores user data in config.json in home directory for later usage with generators.

Makes use of gruntjs to do the following:


- zip files for deployment


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```
## Other requirements

Gruntjs-cli


### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

Copy from git repository

or

To install generator-joomla-spcv2 from npm, run:

```
$ npm install -g generator-joomla-spcv2
```

Finally, initiate the generator:

```
$ yo joomla-spcv2
```

## Subgenerators
There are currently **4** subgenerators planned; only ``controller`` is working right now:

1. *model*: ``yo joomla-spcv2:model "model-name"`` - *Not yet implemented*
2. *view*: ``yo joomla-spcv2:view "view-name"`` - *Not yet implemented*
3. *controller*: ``yo joomla-spcv2:controller "controller-name"`` 
4. *helper*: ``yo joomla-spcv2:helper "helper-name"`` - *Not yet implemented*

## Other generators

Select from list upon startup of *yo joomla-spc*

*component*

*module*:*Not yet implemented*

*plugin*: *Not yet implemented*

*template*: *Not yet implemented*

*templateadmin*: *Not yet implemented*



Each generator creates a new file with phpdocumentor and joomla standards, packaged and subpackaged as needed

## Usage

Create a working directory
open up a command prompt in the working directory

    yo joomla-spcv2


after running the generator files will be stored in app directory
modify files to your project requirements

from the command prompt in the working directory type 

    grunt 

this will zip (grunt's default task) up files located in app directory and place the zip file in dist directory.

## Reference
The components and starting logic are derived form the book [Learning Joomla 3 Extension Development Third Edition](http://www.amazon.com/Learning-Joomla-Extension-Development-Third-Edition/dp/1782168370) (you can also find this on *other* alternative locations on the internet [by googling](https://encrypted.google.com/search?{google:acceptedSuggestion}oq=learning+joomla+3+extension+development&sourceid=chrome&ie=UTF-8&q=learning+joomla+3+extension+development))

[joomla-platform-examples](https://github.com/joomla/joomla-platform-examples)

[sublime text 2 joomla snippets](https://github.com/joomlapro/joomla-bundle "sublime text 2 joomla snippets")

# To-do
read the todo.txt file

## Help
Information on how to use sub-generators can be found by using:

	yo  joomla-spcv2 --help

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)
