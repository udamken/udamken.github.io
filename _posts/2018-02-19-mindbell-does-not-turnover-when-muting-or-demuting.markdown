---
layout:   post
title:    (16) Why doesn't the notification bell turn over every time when muting/demuting?
category: mindbell
---

The notification icon shows a stylized bowl upside down when reminders are suppressed. Otherwise the notification icon shows a stylized bowl opened to the top. MindBell switches the notification icon when muting/demuting, that is meant by the bell is [turned over](/mindbell-intro#bell-is-muted).

Due to a [bug](https://issuetracker.google.com/issues/37127718) (in Android) MindBell doesn't get informed in time about muting/demuting when enabling/disabling the new do-not-disturb modes (introduced in Lollipop and Marshmallow) by switching from tab to tab between total-silence, alarms-only and priority-only - along the arrows in these screenshots:

![](https://github.com/udamken/mindbell/raw/master/misc/Screenshot_DnD_en_US.png){:height="40%" width="40%"}
![](https://github.com/udamken/mindbell/raw/master/misc/Screenshot_DnD_de_DE.png){:height="40%" width="40%"}


The only "solution" is a bypass with three ways to update the notification status which turns over the bell correctly: (1) Manually use status refresh button in notification. (2) Manually open and close [settings](/mindbell-intro#settings). (3) Automatically when the bell rings.
