---
layout: page
title: Web App and Mobile Developer
tagline: Supporting tagline
---
{% include JB/setup %}

Atom Yard develops apps for mobile and web.

## Web Apps

+ [**Review Mailer**](/reviewmailer)

Find out what customers are saying about your App Store applications.

[ ![Review Mailer screenshot](assets/img/screen_preview.png "Review Mailer") ](http://www.reviewmailer.com)

[Find out more here](http://www.reviewmailer.com)

## Mobile Apps for iPhone®

+ [**Noted! for iPhone®**](/noted)

+ [**Health Help for iPhone®**](/healthhelp)

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Contact Us

If you have any questions or comments, contact us [here](mailto:support@atomyard.com).


