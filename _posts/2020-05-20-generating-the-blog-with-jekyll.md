---
title: Generating the blog with Jekyll
layout: post
featured-image: /assets/post-media/2020-04-27/kickin-back.jpg
featured-thumbnail: /assets/post-media/2020-04-27/kickin-back-sm.jpg
description: I took my sad excuse of a blog and fed it to Jekyll. It spat this out!
categories: jekyll coding
---

## Static Site Generator-generated!

We are now up and running with static site generator Jekyll!

![Jekyll logo](\assets\post-media\2020-04-27\jekyll.svg "Jekyll logo")

As I mentioned in [yesterday's post]({% post_url 2020-05-17-moving-beyond-wordpress %}), I wanted to start experimenting with some static website tools. A few hours research today and we're good (I think). This is what's been done:

- Decided to try out Jekyll as a static site generator (it has been round for long and the documentation is good)
- Research
- Install Ruby (Jekyll is written in Ruby). I'm on Windows so I used the installer package: [Ruby](https://www.ruby-lang.org/en/)
- With Ruby installed, proceeded to install Jekyll:

```
> gem install jekyll
```

- Created a new Jekyll site:

```
> jekyll new C:/my-path
```

- Followed the [official Jekyll guide on converting a site to Jekyll](https://jekyllrb.com/tutorials/convert-site-to-jekyll/)

And it seems smooth! I like being able to re-use footer and html head without any hassle, just by using layouts.
