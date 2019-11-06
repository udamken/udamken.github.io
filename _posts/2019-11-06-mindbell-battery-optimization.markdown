---
layout:   post
title:    (07) How to exclude MindBell from optimizing battery use?
category: mindbell
permalink: mindbell-battery
---

On newer Android versions MindBell has to be excluded from battery optimization to work well. On standard Android implementations such as [Android One](https://www.android.com/intl/en_US/one/) it's sufficient to exclude MindBell from the standard mechanism of battery optimization as described below. For deviant Android implementations please take a look at <a href="https://dontkillmyapp.com/?app=MindBell&3" target="_blank">Don't kill my app!</a>

The idea of MindBell is to get a reminder from time to time throughout the day. Reminder means to wakeup the phone by the means of an alarm and play a sound, show a bell or vibrate. Waking up the phone and these actions consume battery, of course. Some energy saving mechanisms assume this to be a waste of energy and prohibit the wakeup for the sake of a longer lasting battery. Therefore it might be necessary to exclude MindBell from whatever mechanism exists on your phone.

This is a description following some screenshots on an Android 7 device (Moto G4 Plus, which BTW doesn't need MindBell to be excluded). **If this description does not fit to your phone, vendor, model or version please take your favourite search engine and look for something like "vendor device battery optimization", with replacing "vendor" and "device" according to your phone.**

## (1) Phone settings ##

In your phone settings open the battery settings in the device section:

![](/images/battery/Screenshot_battery_en_US_01.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_01.png){:height="40%" width="40%"}

## (2) Battery settings ##

Click on the three-dot-menu-button to open battery optimization settings (which are different from the battery saver mode):

![](/images/battery/Screenshot_battery_en_US_02.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_02.png){:height="40%" width="40%"}

![](/images/battery/Screenshot_battery_en_US_03.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_03.png){:height="40%" width="40%"}

## (3) Battery optimization settings ##

The 'Battery settings' option under 'Problem solving' in MindBell's settings should take you to this point.

From here on show all apps not only the "not optimized" ones:

![](/images/battery/Screenshot_battery_en_US_04.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_04.png){:height="40%" width="40%"}

![](/images/battery/Screenshot_battery_en_US_05.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_05.png){:height="40%" width="40%"}

## (4) Battery optimization for MindBell ##

Now exclude MindBell from optimizing battery use (optimization is enabled per default):

![](/images/battery/Screenshot_battery_en_US_06.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_06.png){:height="40%" width="40%"}

![](/images/battery/Screenshot_battery_en_US_07.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_07.png){:height="40%" width="40%"}


## (5) Do not optimize battery use for MindBell ##

This is how it should look like if you followed the previous steps:

![](/images/battery/Screenshot_battery_en_US_08.png){:height="40%" width="40%"}
![](/images/battery/Screenshot_battery_de_DE_08.png){:height="40%" width="40%"}

