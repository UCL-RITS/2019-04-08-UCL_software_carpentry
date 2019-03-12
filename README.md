# Software Carpentry @ UCL

This repository holds the website as a common place to link future and old
workshops (gh-pages branch,
[site](http://rits.github-pages.ucl.ac.uk/software-carpentry)). That page is
generated automatically from the content in `master` using [Travis](https://travis-ci.com)

You can see how it's built in:
[![Build Status](https://travis-ci.com/UCL-RITS/software-carpentry.svg?token=tpqYy2kGKwjiyqQSznFy&branch=master)](https://travis-ci.com/UCL-RITS/software-carpentry)

## Create a new workshop

If you are organising a workshop, copy the last file in `_posts` with a new date
and update the content in the yaml header.

## What else is in here?

The wiki is also a repository, and it contains the (internal) information about
the different workshops (i.e., steps to organise workshop, comments from the
students, ...).

When organising a new
[issue](https://github.com/UCL-RITS/software-carpentry/issues/new) you will get
a list of steps to organise a new workshop - if there's something missing update
it in the [issue template](.github/ISSUE_TEMPLATE.md).
The issues also hold all the software carpentry related issues, requests from
external participants, etc.

-------------

The template used for the generation of the pages comes from
[Evento](https://github.com/boyney123/evento).
