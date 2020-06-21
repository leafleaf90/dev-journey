---
title: Moving beyond WordPress
layout: post
featured-image: /assets/post-media/2020-04-26/coffee-journal.jpg
featured-thumbnail: /assets/post-media/2020-04-26/coffee-journal-sm.jpg
description: In search for something lighter.
categories: coding
---

## The Starting Point

I have lots of websites running WordPress installations with some theme/sitebuilder, usually Divi with Slider Revolution for some added flair. Divi is good for clients that do not want to deal with markdown and have to update content several times per month or even daily. But performance-wise the site gets bogged down with all the extra fluff and slows down the user experience, both for visitors but also in the admin area. Also, for many clients it doesn't make sense to run a website with a database. A static website, consisting only of HTML, CSS and some JavaScript is often enough and brings huge performance advantages.

## Options

Right now I'm writing this straight into my index.html in VS Code.

![VS Code editor](/assets/post-media/2020-04-26/html-edit.png "VS Code editor")

I'm considering a headless CMS such as
[Ghost](https://ghost.org/) and some static site generator magic
such as [11ty](https://www.11ty.dev/) for the blog going forward. Gatsby from the React side seems easy to work with as well.
