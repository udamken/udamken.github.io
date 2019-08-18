---
layout:   post
title:    (06) Why doesn't MindBell ring or remind (periodically)?
category: mindbell
permalink: mindbell-notringing
---

First of all I'm very sorry that MindBell does not ring or remind as you expect.

Due to targeting a newer Android version ([enforced by Google Play](https://android-developers.googleblog.com/2017/12/improving-app-security-and-performance.html?m=1)) with MindBell 3.5.0 Android seems to handle the app differently regarding power saving. So it's most likely about [power saving](#power-saver).

> **_HINT:_** If you miss reminders or meditation ending bells please check [power saving](/mindbell-notringing#power-saver).

Here is a checklist that I hope might help to get it going:

* Does it make a sound when you touch the bell?

  Follow every message that might give a hint.

* Which audio channel does the sound go to and which volume control is used?

  Please check the sound output section of the [settings](/mindbell-intro#settings).

* Is the volume too low?

  If the volume of the audio channel should be used please check the volume setting for this audio channel in your phone's volume control.

  If the MindBell' volume setting should be used please check the bell volume in the reminder actions section of the [settings](/mindbell-intro#settings).

* Did you activate reminders by the switch?

  See [intro](/mindbell-intro) how to activate it and turn the switch in its ON position.
  
  If the switch automatically goes back to OFF when leaving MindBell please clear app data via your phone's settings in the _Apps_ section. Weird, but some users reported it simply helps to wait one or two days.

* Have you specified which reminder actions should be taken?

  Ensure the action you are missing is enabled: bell display, sound or vibration.

* Is it possible that reminders were suppressed because of [these reasons](/upside-down) when you expected it to remind?

  If so the bell won't play a sound, vibrate or even display in that moment (depending on the corresponding option).
  
  That takes a new interval to try it again. With long intervals this might result in never getting a reminder.

* Is there a chance that you simply overheard the bell? While in flow or very busy?

  Choose another ringtone or enable vibration and/or enable notifications when the bell rings (needs version >= 3.1.0).
  
  Not forever, just to check.

* Is 'Pause audio on sound' enabled in the [settings](/mindbell-intro#settings)?

  Please disable that option. It doesn't work properly on devices of some vendors, e.g. Samsung or LG.

<a id="power-saver"></a>

* Are you using any sort of power saver app or power saver mechanism?

  Please exclude MindBell from any power saver app or power saver mechanism. This might be specific to your version, model and vendor of your phone or you might have installed some specials apps for this. E.g. on **Honor**, **Huawei** and **Xiaomi** phones reminder won't work without this.

  Please deactivate and activate reminders by the switch to test these settings after changing them.

  Please exclude MindBell from optimizing battery use following this [description](/mindbell-battery).
  The 'Battery settings' option under 'Problem solving' in MindBell's settings should take you there.

  Please check these faq of two other apps - completely independent of MindBell but root cause for the mentioned problems is the same as for missing reminders in MindBell. Be aware they have nothing at all to do with MindBell or dknapps.de neither am I responsible for the content - the links are added for your convenience only:
  
  * <a href="http://nine-faq.9folders.com/categories/2758-troubleshooting" target="_blank">foreign troubleshooting tips for an app called "Nine"</a>
  * <a href="https://threema.ch/en/faq/push_andr" target="_blank">foreign troubleshooting tips for an app called "Threema"</a>
  * <a href="https://threema.ch/de/faq/push_andr" target="_blank">fremde Hilfestellung für ein App namens "Threema" (deutsch/german)</a>
  
  <br/>You think MindBell should solve this for you? Sorry, it can't.
  
  Before <span style="color:red">**complaining or down-ranking**</span> please watch this <a href="https://youtu.be/nlmS8_Gz5QA" target="_blank">video</a> and read this <a href="https://www.reddit.com/r/Android/comments/8qjhx7/huawei_oneplus_and_xiaomis_overlyaggressive/" target="_blank">text</a>.

* Is there any mechanism that suspends apps when your device is locked?

  Please exclude MindBell from lock screen cleanup on **EMUI** phones (like Honor or Huawei) following this [description](/mindbell-battery-emui).

* Does your phone suppress notifications that are not of high importance?

  Please read this [comment](https://play.google.com/store/apps/details?id=com.googlecode.mindbell&reviewId=gp:AOqpTOF1-BqVtwU4o2Zj7AOjCgCnGEzP2szShVXADmaokxOEqK6z9-9z-z2wR9pk4X3DwA3ahzoO4LRxGKdYy-0) regarding **Samsung** Galaxy S7, maybe you have something similar on your device.
  
* These tips didn't help?

  Please take your favourite search engine and look for something like “vendor device battery optimization”, with replacing “vendor” and “device” according to your phone.

  
* Please try this reminder test scenario:

  Go to the active times and rhythm section of the [settings](/mindbell-intro#settings).

  Specify reminder times from 00:00 to 00:00, activate all weekdays, set interval to 1 minute and disable interval deviations.

  Go to the reminder actions section of the [settings](/mindbell-intro#settings).

  Enable show bell, play sound and vibrate. Select single bell as bell sound.

  Leave the settings, activate the bell.

  After at least 2 minutes you should see the bell, hear a sound and your phone should vibrate.

  **<span style="color:red">If reminders work for a short interval like a minute but not for a longer interval like an hour</span> then it's for sure about [power saving](#power-saver).**

* Please try this meditation test scenario:

  Start a meditation with enabling the option to keep the screen on. Choose the meditation length according to your wanted reminder interval - just to check whether your phone will be waken up to play the ending bells after that time.
  
  **<span style="color:red">If you hear the ending bells when the meditation is over</span> then it's for sure about [power saving](#power-saver).**

* Have you tried to uninstall MindBell and re-install it freshly?

  Clear data first (it might make a difference).

  On Marshmallow and higher please disable automatic restoring of app data after reinstallation.

  Then uninstall and reinstall MindBell.

* Have you re-booted your mobile to see whether that helps?

  Please try that one, too.

* You've found a solution that's not listed here?

  Please send me an e-mail. I'd be happy to add it to this list.

* All this did not help?

  Then it's once again time to say sorry - but I'm out of ideas.
  
  Probably MindBell became a victim of Google's and your vendor's efforts to decrease power consumption on your version of Android and type of phone.
