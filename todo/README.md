# todo

This is a project built for the Austin Haskell Meetup. It is the first end-to-end project we will be doing. It illustrates how to do some useful things in Haskell: query SQL databases, parse command line arguments, and assemble those into a working application. We're using the libraries `optparse-applicative` and `postgresql-simple` for this project.

## Prerequisites

To get the most out of this project, it's helpful if:

 - you are comfortable with Haskell syntax;  
 - you have a solid understanding of types and typeclasses;
 - you've been introduced to the `Alternative` typeclass;
 - you understand the idea of parsing.

 Things this project aims to demonstrate:  

 - how to set up Haskell projects;  
 - how to use Haskell libraries;
 - how to separate concerns appropriately (e.g., "pure" functions from `IO`);
 - how to parse command line arguments and query SQL databases using Haskell.  


## Overview

 The command-line argument parsing and the parts of the program the user interacts with are in app/Main.hs. The database stuff is mostly in src/Lib.hs. 

## Using this project

## Reading

[optparse docs](https://github.com/pcapriotti/optparse-applicative)

[24 Days of Hackage: optparse](https://ocharles.org.uk/blog/posts/2012-12-17-24-days-of-hackage-optparse-applicative.html)

[Brisbin optparse](https://robots.thoughtbot.com/applicative-options-parsing-in-haskell)

[optparse quickstart](https://ro-che.info/articles/2016-12-30-optparse-applicative-quick-start)
