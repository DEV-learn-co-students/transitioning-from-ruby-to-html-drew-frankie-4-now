# Transitioning from Ruby to HTML

## Introduction

In this course, we will take a short break from Ruby and will focus on HTML.
You might wonder why we're changing from programming in Ruby, which feels like
"doing programming," to focusing on HTML which feels like "writing words." Let's
address that concern.

## The Web Platform

At some point, we will want to allow others to use our applications. Employers,
technologists, and customers will assume Web integration as a standard "first
option" for delivery.

The web is an open platform. Unlike the mobile application stores, there are no
gatekeepers. Everyone can publish applications on the web as long as they
adhere to a few [open standards][].  This takes us back to Ruby, how can our
Ruby application work on the web? It's relatively simple-ish. All we need to do
is adhere to the web standards. To be more specific our Ruby application needs
to output data that can be published on the web and understood by web browsers.
Our Ruby application needs to output HTML.

## Creating Web Applications Is the Art of Generating HTML

Whenever we are writing a web application, we will inevitably get to the point
where we need to generate HTML. It does not matter what programming language we
use (Ruby, Python, JavaScript). At some point, our code will output HTML, and
if we want to interact with our websites, our code will need to know how to
interpret HTML.

Now you know why knowing HTML is important. It's what will allow us to share
the applications we write with billions of people on the web.

[open standards]: https://www.w3.org/standards/
