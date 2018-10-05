---
layout: post
title:  "Starting a blog"
date:   2018-10-02 22:15:11 +0000
categories: Blogging
---
So I've decided to start a blog and was looking for options on where to host it and what platform to use. I had a choice
between CMS powered platforms and static site generators.

Here are the ones I looked at:

## Wordpress

  Wordpress is the most popular blogging platform. In fact, it's used not only for blogging but as more of a general
  purpose CMS.

  Their website says "WordPress powers 31% of the internet". I don't know how reliable that number is, but that is huge.  That's not 31% of blogs, but 31% of all websites on the internet.

  Wordpress.com offers a free plan but you don't get your own domain and it comes with ads. You'd have to pay PHP 200 (~4 USD) for their Personal plan to remove the ads and use a custom domain name. Wordpress is open-source though, so I could also get a VPS for 5 USD per month and self-host.

  Wordpress is pretty customizable, that's why it's being used to build all kinds of websites but the tradeoff is that
  the admin interface is too complex. It's definitely overkill for my needs. I just need a simple way to post entries.

## Ghost

  Ghost is similar to Wordpress in that it's open-source with the company building it offering hosted plans. They are
  focused on blogging though so the interface looks cleaner, simpler and is easier to use.

  It's pretty expensive compared to Wordpress though as their Basic plan is at 29 USD per month. Again I could get a VPS
  and self-host but it's too much of a hassle for me right now.

## GitHub Pages

  GitHub Pages is quite different from the first two because it is a static site hosting platform rather than a blogging
  platform. Blogging is made possible by using Jekyll - a static site generator.

  So instead of having a web interface to create posts, I just fire up a text editor and write in Markdown then push to
  the Git repository when done. It does require some technical knowledge so it's not for everyone.

  It's completely free and I don't see my blog hitting Github's usage limits.

## GitLab Pages

  This one does everything GitHub Pages does plus adds support for other static site generators. It's also a plus that
  GitLab is open-source.

----

In the end, I decided to go for GitHub Pages because it's free and I already have a GitHub account and repo setup but GitLab Pages looks really
interesting and I will definitely look into that in the future.
