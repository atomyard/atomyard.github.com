---
layout: post
title: Blogging with Jekyll
---
When you think about it most companies only need a basic website - static pages with maybe a blog. Free options like Google Sites or WordPress are fine for many situations. I started out using Google Sites which was ok until I wanted to add some basic CSS and JavaScript but Google Sites was too inflexible to do this.

So I looked around for and found a great alternative - [GitHub Pages](http://pages.github.com/). It's is not for everyone but for developers its easy and best of all free!

Just create a GitHub repository called `your_github_username.github.com` and add a file called `index.html`	. Push the repository to GitHub and your website will then be available at [http://your_github_username.github.com](http://your_github_username.github.com). You also get the added benefit of Git revision control for your site. For detailed instructions including using your own domain name, GitHub Pages has an easy to follow guide [here](http://pages.github.com/).

The next step for my site was adding a blog. [Jekyll](https://github.com/mojombo/jekyll) is a simple static site generator which allows you to write your blog posts in distraction free markdown. Jekyll then takes care of generating the website based on your templates. Jekyll is built into GitHub so each time you push your repository, your site is automatically regenerated. I found [this](http://www.ksornberger.com/blog/blogging-with-jekyll-and-github/) tutorial helpful when setting up Jekyll for my site.

