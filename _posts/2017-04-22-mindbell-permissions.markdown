---
layout:   post
title:    (13) Why does MindBell need permission "read phone status and identity"?
category: mindbell
---

At first let me tell you that MindBell doesn't want to sniff anything out. Neither does MindBell send any information anywhere over the internet or whatsoever. BTW it does not have the permission to access the internet. In _Settings > Apps_ you can see or show all permissions that an app requests.

READ_PHONE_STATE (read phone status and identity) is needed to modify the bell in the notification bar when phone status changes (phone call, flight mode, muted), if requested in the settings. That means the bell in the notification is [turned over](/mindbell-intro#bell-is-muted) during incoming or outgoing calls, flight mode or when the phone muted. Just to signal that you won't be disturbed by a ring while on the phone or asleep or meditating or whatever.

To be precise READ_PHONE_STATE is only needed to detect incoming or outgoing calls. Flight mode and muting the phone are signalled to MindBell without this permission. But IMHO [turning over](/mindbell-intro#bell-is-muted) the bell when it is muted only makes sense when it's [turned over](/mindbell-intro#bell-is-muted) in all those situations. It's a question of reliability of the notification.
