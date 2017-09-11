---
layout: project
type: project
image: images/Granatum_logo_square.png
title: Granatum
permalink: projects/granatum
date: 2016
labels:
  - R
  - Shiny
  - Web Development
summary: A scRNA-seq workflow app prototype I developed for a research lab.
---

<img class="ui image" src="{{ site.baseurl }}/images/Granatum_logo.png">

In my 1st summer in college and going into my 2nd year, I developed a prototype
for a web application that was meant to serve non-technical biologists to allow
them to create and run data processing workflows for single cell RNA sequencing
(scRNA-seq) data analysis.

Over the course of the project, I was exposed to my first experience in
software development and also got my first exposure to research.

The project was accomplished using the Shiny web application framework. It is a
reactive framework written in R that uses Node.js as a back-end. It is meant to
build smaller, reactive applications meant to serve only a few purposes, such
as displaying a geography data set.

Throughout the course of the internship, I touched on UI design, working with
Bioconductor (a biology research-focused package manager for R), graphing
with `ggplot2`, and data manipulation with `dplyr` and other functional
paradigms that are standard within R. I also learned more about how R handles
evaluation as I tried to create a work of "module" system for my application
without support from Shiny (as it had not been created yet when I started on
the project).

If you want to check out the non-prototype, finished application, see [here](http://ilab.hawaii.edu:8109/?_state_id_=5d8c45acabd6036d&tab=uep).
The code has significantly changed since the original prototype.

<img class="ui image" src="{{ site.baseurl }}/images/Granatum_screenshot.png">
