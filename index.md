---
layout: page
title: DCI in Ruby
tagline: A sample application illustrating the Data Context Interaction paradigm (in Ruby)
---
{% include JB/setup %}


## Why DCI?

DCI (Data Context Interaction) is a new way to look at object-oriented programming. Instead of focusing on individual objects, the DCI paradigm focuses on communication between objects and makes it explicit. It improves the readability of the code, which helps programmers to reason about their programs.

I'd been reading blogs posts and watching talks about DCI for a long time and I felt that it's time to try it out. I found that most material related to DCI is theoretical. There were a few books, a dozen of blog posts, and several presentations that could give you a good picture of what DCI is. However, I could not find any "real world" examples of actually using it. That's why I decided to write a simple application showing how to implement DCI in Ruby.

## Like what?

Like the following projects:

* [DDDSample](http://dddsample.sourceforge.net/). This is a how-to example of implementing a typical DDD application.

* [The Silverlight Cookbook](http://silverlightcookbook.codeplex.com/). A reference application for Silverlight 5 LOB apps.
 
## Ruby/Rails

The application is a Rails project. There are a few reasons for it:

* All the DCI concepts can be implemented in Ruby. It doesn’t feel clunky or alien.
* Ruby is concise and readable. Even if you are a C# programmer, you should be able to understand what is going on.
* There is more interest in DCI in the Ruby community than in any other community. 

## This is not a book

Just to make it clear; this is a practical application of the DCI pattern, not a book. If you want to read up on DCI check out the following links:

* [Data Context Interaction: The Evolution of the Object Oriented Paradigm](http://rubysource.com/dci-the-evolution-of-the-object-oriented-paradigm/)

* [Lean Architecture](http://www.leansoftwarearchitecture.com/)

* [Clean Ruby](http://clean-ruby.com/)

<a href="resources.html">More talks, books, papers, and blog posts on DCI.</a>

## Purpose

The purpose of this project is to show a typical DCI application. There are many ways to implement any design pattern, and DCI is not an exception. Hence, the application isn't meant to show the way to use DCI, but just to illustrate one of many possible approaches.

## Application

* [Read more on what the application actually does.](/overview.html)

* [Read the technical overview of the application.](/technical_overview.html)


## More on DCI and Domain Design

I blog about DCI and domain design fairly regularly at [Victor Savkin's Blog](http://victorsavkin.com) and tweet about it at [@VictorSavkin](http://twitter.com/victorsavkin).
 