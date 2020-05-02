---
layout:    post
title:     (02) What has been changed recently?
category:  mindbell
permalink: mindbell-changelog
---

### 3.6.0

* SDK target level increased to 29
* Status notification removed
* Notification bound to a foreground service is now shown when MindBell is active or meditation is ongoing (this hopefully keeps MindBell alive and overcomes battery optimization issues)

### 3.5.0

* Minimum SDK level increased to 21 ... due to missing system sounds in emulator with lower levels and a bug in preferences handling in level 16
* Quick settings tile added for quick mute/unmute and to replace status notification as of Android Oreo ([issue #50](https://github.com/udamken/mindbell/issues/50))
* Spanish translations contributed on [Crowdin](https://crowdin.com/project/mindbell/) added
* Separate settings option to grant permission READ_PHONE_STATE
* Sometimes we have to let things go, golden status icon removed
* New option to suppress reminders if phone is in any (!) do-not-disturb mode ([issue #75](https://github.com/udamken/mindbell/issues/75))
* Schedule now gets only update when a relevant setting has been changed
* Internal statistics added to see whether scheduled actions occur on time
* Actions are now always associated with a notification and executed in foreground
* Reliably support sounds longer than 10s
* Code refactoring for better separation of concerns
* Moved from Java to Kotlin
* SDK target level increased to 26 because of [Google Play](https://android-developers.googleblog.com/2017/12/improving-app-security-and-performance.html?m=1) ([issue #66](https://github.com/udamken/mindbell/issues/66))

### 3.2.6

* New stick-bell sound added
* New sounds with bell, silence and stick-bell added
* Duration of system sounds now limited to a quarter of the interval but to fixed 13 s
* Improved wording due to calling it reminder but ring
* Status notification now also turns upside down during nighttime
* Nighttime intervals are now seen as completely active or not depending on the weekday of the beginning of the interval
* Option 'Mute with phone' replaced by 'Don't remind if ringtone is muted' plus 'Don't remind if audio is muted'

### 3.2.5

* New section 'Problem solving' added to settings
* New option to open FAQ under 'Problem solving'
* New option to check battery optimization settings under 'Problem solving'
* New option to enable a workaround for distorted sound on some devices under 'Problem solving'
* Option to send an e-mail with log moved to 'Problem solving'
* New section 'Sound output' added to settings
* New option to choose audio channel under 'Sound output'
* New option to use volume control of audio channel or MindBell's own volume settings under 'Sound output'
* Default changed to use audio channel volume instead of MindBell's own volume settings
* Request permission READ_EXTERNAL_STORAGE to allow user created system sounds to be chosen

### 3.2.4

* Tap (bell) to ring reintroduced

### 3.2.3

* New intro text ([issue #57](https://github.com/udamken/mindbell/issues/57))
* Tap to ring replaced by a play button
* Prohibit division by zero when choosing zero interval (which is invalid)
* Allow to ring on the minute for full hour intervals

### 3.2.2

* Hide bell also if sound was suppressed ([issue #47](https://github.com/udamken/mindbell/issues/47))
* Time to hide the bell without sound and to dismiss ring notification is now 10 s (instead of 15 s)

### 3.2.1

* Option to stop meditation mode automatically
* Zero bells setting replaced by button to start meditation directly
* Preferences reordered for a better overview
* When meditating show only button to stop meditation
* Back button when the bell shows up now returns to previous app ([issue #38](https://github.com/udamken/mindbell/issues/38))

### 3.2.0

* Optionally zero bells on meditation beginning
* Time picker for intervals
* Fixed period specification issue
* Optionally dismiss ring notification after a short while
* Meditation dialog redesigned for better clickability

### 3.1.4

* Pause Audio On Sound now defaults to off
* Keep Screen On now defaults to on
* Theme added to use colors of dknapps.de

### 3.1.3

* Icon with background
* Fixed landscape layout issues

### 3.1.2

* Separate volume setting for bells during meditation
* Improvements and bugfixes in meditation parameter settings

### 3.1.1

* Meditation dialog reorder to reflect calculation order
* Prophylactic change to address [issue #15](https://github.com/udamken/mindbell/issues/15)

### 3.1.0

* Meditation timer countdown continues below zero ([issue #28](https://github.com/udamken/mindbell/issues/28))
* New option to pause other audio sources while playing sound ([issue #3](https://github.com/udamken/mindbell/issues/3))
* New option to suppress sound while music is playing ([issue #3](https://github.com/udamken/mindbell/issues/3))
* New option to enable notification when bell rings to make wearables vibrate ([issue #25](https://github.com/udamken/mindbell/issues/25))
* New option to specify meditation periods of different lengths ([issue #29](https://github.com/udamken/mindbell/issues/29))

### 3.0.5

* Switch instead of buttons to activate or deactive the bell

### 3.0.4

* Use time pickers for start and end time of activity

### 3.0.3

* Fixed chopping off the playing sound after unloading the app (by Android or manually in recently used apps list)

### 3.0.2

* Fixed mute-till-feature (has muted effectively erroneously for minutes but for hours)

### 3.0.1

* Request needed permission directly on first app startup

### 3.0.0

* Meditation timer functionality added ([issue #8](https://github.com/udamken/mindbell/issues/8))
* Deprecated preference sharing avoided by removal of multi-process operation ([issue #24](https://github.com/udamken/mindbell/issues/24))
* MindBell can now be muted manually by a button in the status notification ([issue #26](https://github.com/udamken/mindbell/issues/26))
* Ringing comprises displaying the bell, playing sound and vibrating. Being muted in turn means nothing of all three. Following this logic the bell gets no longer displayed when muted.
* Status-Icon is now enabled by default, so insufficient permissions warning leads directly to the settings.
* Tapping the bell now always plays the sound - muted or not - but does not vibrate any more.
* Several internal refactoring measures

### 2.6.2

* Button added to go to battery optimization options
* Privacy Policy referenced in help dialog

### 2.6.1

* Correction of clarification for mute-with-phone option ([issue #17](https://github.com/udamken/mindbell/issues/17))

### 2.6.0

* Settings rearranged into groups
* New option to set timing to regular rather than randomized ([issue #1](https://github.com/udamken/mindbell/issues/1))
* New option to normalize timing to the minute ([issue #22](https://github.com/udamken/mindbell/issues/22))
* New option to "ring" the bell without playing a sound ([issue #4](https://github.com/udamken/mindbell/issues/4))
* New option to choose a notification ringtone (those are not played in a loop) ([issue #12](https://github.com/udamken/mindbell/issues/12))
* New otion to choose vibration pattern
* New menu entry to send information by e-mail ([issue #20](https://github.com/udamken/mindbell/issues/20))
* New intervals (1, 2, 3, 4 and 45 minutes) added ([issue #7](https://github.com/udamken/mindbell/issues/7), [issue #23](https://github.com/udamken/mindbell/issues/23))
* Vibration is now completely off when off was chosen ([issue #10](https://github.com/udamken/mindbell/issues/10))
* Bypass implemented for bell not [turning over]((/mindbell-intro#bell-is-muted)) (on some devices) when muting/demuting phone by volume keys or by switching do-not-disturb mode tabs ([issue #15](https://github.com/udamken/mindbell/issues/15))
* Status icon no longer disappears on updates of MindBell ([issue #21](https://github.com/udamken/mindbell/issues/21))
* Mute-with-phone option clarified or at least described more precisely ([issue #17](https://github.com/udamken/mindbell/issues/17))
* Settings chosen from a list are now removed and re-initialized if they contain invalid values
* New help dialog

### 2.5.14

* Fixed scheduling issues by using different AlarmManager methods for higher SDK levels

### 2.5.13

* Option to choose previous notification icon added to the settings (brings back golden bowl on some devices)

### 2.5.11/2.5.12

* Request permission as required for new permission model (SDK level 23)

### 2.5.8/2.5.9/2.5.10

* Reset alarm volume to it's original value after ringing the bell multiple times (concurrently)

### 2.5.7

* Update notification additionally on volume change action (needed for some devices)

### 2.5.6

* Added feedback message when clicking bell-on icon
* Hint added how to ring the bell which in turn shows how to activate the bell
* Brought weekday abbreviations in order according to locale
* Show text how to activate the bell longer because text is longer now

### 2.5.5

* Package renaming reverted to com.googlecode.mindbell (so MindBell keeps it's identity)
* SDK level increased to minimum 16 (and target 23) ... due to lack of a test environment

### 2.5.4

* Bell no longer rings immediately after leaving settings or after pressing bell button
* MindBell can now be activated/deactivated additionally by icon in action bar
* New icons following Material Design (white notification icons) or used from Material Icon Library
* SDK level increased to (minimum 11 and) target 23

### 2.5.3

* Preference added for Lollipop and higher to show notification texts on lock screen

### 2.5.2

* Copyright updated in source code

### 2.5.1

* IDE moved to Eclipse Mars.2 with Andmore

### 2.5.0

* Packages renamed to de.dknapps.mindbell
* About dialog redesigned to reflect upcoming maintainer change

### 2.4.3

* Promo popup reused as migration reminder (to de.dknapps.mindbell)

### 2.4.2

* Reset alarm volume to it's original value after ringing the bell

### 2.4.1

* MindBell activation can be restricted to selected weekdays
* SDK level increased to minimum 11 (and target 17)

### 2.4.0

* Hidden menu issues fixed
* SDK level increased to minimum 10 and target 17
