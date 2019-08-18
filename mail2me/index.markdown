---
layout:   page
title:    mail2me
logourl:  /images/mail2me_128x128.png
summary:  Create an email to yourself with one click
category: app
order:    1
---
A link or widget - it's your choice - created by **mail2me** on the homescreen of your Android device allows you to open your favorite email client with one click. This opens up an empty email already addressed to the addressee you specified when creating the link or widget.

Download mail2me from [product subdirectory of mail2me in the code repository](https://github.com/udamken/mail2me/tree/master/product) or [Google Play](https://play.google.com/store/apps/details?id=de.dknapps.mail2me) or compile it on your own. If downloading, please be sure to use the latest version.

mail2me has been published under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

If you have questions or problems please check the following list of **frequently asked questions**. If that does not answer your question plesase send an e-mail to **maill2me [at] dknapps.de** (please replace [at] accordingly).

  <ul class="post-list">
    {% assign sorted_posts = site.posts | sort: 'title' %}
    {% for post in sorted_posts %}
      {% if post.category == "mail2me" %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </li>
      {% endif %}
    {% endfor %}
  </ul>
