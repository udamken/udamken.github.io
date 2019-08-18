---
layout:   page
title:    PswGen
logourl:  /images/PswGen_128x128.png
summary:  Manages your websites and repeatably generates passwords for them on your desktop and mobile
category: app
order:    2
---
PswGen consists of two applications to manage your websites and to repeatably generate your passwords:

**PswGenDesktop manages login information** such as account, name and address of websites you are using. Furthermore **PswGenDesktop repeatably generates passwords** depending on the login information, generation parameters (length etc.) and a master passphrase each time you want login to a website. Just in case a website doesn't allow to change your password, PswGenDesktop can store that password for you, too, encrypted of course.

Download PswGenDesktop from [product subdirectory of PswGenDesktop in the code repository](https://github.com/udamken/PswGen/tree/master/PswGenDesktop/product) or compile it on your own. If downloading, please be sure to use the latest version.

**PswGenDroid** is used to access your login information on your mobile phone.

Download PswGenDroid from [product subdirectory of PswGenDroid in the code repository](https://github.com/udamken/PswGen/tree/master/PswGenDroid/product) or compile it on your own. If downloading, please be sure to use the latest version.

PswGen has been published under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

If you have questions or problems please check the following list of **frequently asked questions**. If that does not answer your question plesase send an e-mail to **pswgen [at] dknapps.de** (please replace [at] accordingly).

  <ul class="post-list">
    {% assign sorted_posts = site.posts | sort: 'title' %}
    {% for post in sorted_posts %}
      {% if post.category == "pswgen" %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </li>
      {% endif %}
    {% endfor %}
  </ul>
