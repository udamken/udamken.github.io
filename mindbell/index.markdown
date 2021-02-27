---
layout:   page
title:    MindBell
logourl:  /images/MindBell_128x128.png
summary:  Aims to give you a support for staying mindful in a busy life - for remembering what really counts
category: app
order:    1
---
> **_WANTED_** [New maintainer wanted!](/mindbell-maintainer)

**MindBell** rings periodically as a mindfulness bell during the day, to give you the opportunity to hold on for a moment and consider what you are currently doing, and in what state of mind you are while you are doing it. According to the Zen Buddhist teacher Thich Nhat Hanh, this is an effective means of developing mindfulness.

> **_HINWEIS:_** Nein, diese Seite gibt es nicht auf Deutsch - wie sie sich übersetzen lässt steht [hier](/translate-website).

Please take a look at this [introduction](/mindbell-intro) on how to use MindBell.

Download MindBell from [releases of MindBell](https://github.com/udamken/mindbell/releases) or [product subdirectory of MindBell in the code repository](https://github.com/udamken/mindbell/tree/master/product) or [Google Play](https://play.google.com/store/apps/details?id=com.googlecode.mindbell) or compile it on your own. If downloading, please be sure to use the latest version.

MindBell has been published under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

**Please be aware that I'm developing and supporting MindBell in my spare time.** So I'd like to save the time to answer questions repeatedly but to use the time for adding new features. Therefore I'd kindly ask you to check the following list of **frequently asked questions** for an answer first if you have questions or problems.

> **_HINT:_** If you miss reminders or meditation ending bells please check [power saving](/mindbell-notringing#power-saver).

---
<br/>

  <ul class="post-list">
    {% assign sorted_posts = site.posts | sort: 'title' %}
    {% for post in sorted_posts %}
      {% if post.category == "mindbell" %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </li>
      {% endif %}
    {% endfor %}
  </ul>
