---
layout: post
title:  "Rolling a new Jekyll site"
date:   2015-12-13 20:00:00 -0600
blogimage: /assets/images/blog/jekyll.jpg
---

It's been over three years since my last website redesign, so it's time. Well, past time.

The site you're seeing now is my first build using [Jekyll](https://jekyllrb.com/ "Jekyll").

Quick observations from my first day in Jekyll:

* Getting set up was relatively simple, and less time-consuming than rolling a new site in something like Ruby on Rails or Drupal. It still took a while, since things like command line installations still give me pause, but it came together well with no frustration.

* Markdown feels really limiting. I quickly encountered a blocker when I wanted to run a large, styled quote across a page and struggled to style the quote and the attribution as I designed it. This is unresolved at the moment. It's really tempting to just use HTML on it, and I may have to.

* I need to style HTML headings (h2, h3, etc.) completely different on my resume page than on my blog posts. I'm still unsure about the best way to do this. My current solution is to create a new layout for the resume page (cloning `page.html`), and simply change the `article` class to essentially namespace the page content. Seems like overkill. Maybe I can add logic to `page.html` to change out classes. I'll explore that later.

* Once I adapt to the new way of doing things, I feel like this will be easy to maintain, update and grow. In the past, I'd roll a new site and not revisit it for months (or -cough-  years). When I needed to update it, it was awkward to refamiliarize myself with how I'd built it and how to best update or add to it. And of course, there was the *what-the-hell-was-I-thinking-when-I-did-it-like-this* remorse, which was immediately followed by *I-should-just-redesign-this-instead*.
