---
templateKey: blog-post
title: Gatsby with Netlify
date: 2018-03-24T08:05:20.614Z
description: Static site generator with headless CMS
tags:
  - web dev
image: "img/gatsby.png"
---

## Gatsby

### A static site

Gatsby is static site generator using React and GraphQL. Static site refers to site where there is not user generated content only contents are by web developers. Developers eitehr use admin panel or other means to update and updates are not real-time or frequent. One of the example of static site can be a resturant where there is only content is by resturant owners or product page of a company.

Dynamic sites are site where page is updated frequently mainly by user data or something like that. These are not technical definition and if I give you technical definition then there is not meaning this blog as there are lots of sources for technical definition.

## React
 
React plays a major role in gatsby as it is front-end used by gatsby for producing static site. React is a frontend library by Facebook which means it is used to create client side of a website. If you don't know then let me make clear that mainly as website consist of 3 main ingredients Frontend, backend and a database.


## Netlify

A continuous deployment service directly from Github. It needs its own article to explain. This blog is on netlify and using NetlifyCMS.

### Why we need static site?

If we have frontend framework or library why don't we use it to create websites. Yes we can and most of the time it used directly but blogs and sites which don't need data from user and display is in real-time then these libraries and frameworks are slow. Before these Single Page Application - a website where there is only one HTML page and javascript is used to add and remove elements from DOM (Data Object Model) sites used multiple HTML pages for displaying different data and it was fast but as time passed we needed much more functionalities and for that reasom SPAs came to being but they are not suitiable for every task. Even then there features are awesome and due to this reason gatsby uses React to produce static HTML pages during build step.