---
title: "Translate - Channel Automatic"
permalink: /trans-auto/
excerpt: "Translate a Channel Automatically"
last_modified_at: 2019-09-10T14:00:00+01:00   #Please Update, The +00:00 is the Time Zone difference
redirect_from:
  - /theme-setup/
toc: true

# Date formatting & Date Parsing - Let formatting and parsing date expressed in ISO8601 format.
# Can be obtained from https://dencode.com/en/date
# ---- Defined ----
# YYYY-MM-DD'T'hh:mm:ssTZD (e.g. 2015-12-11T20:28:30+01:00)
# YYYY = four-digit year
# MM = two-digit month (01=January, etc.)
# DD = two-digit day of month (01 through 31)
# hh = two digits of hour (00 through 23) (am/pm NOT allowed)
# mm = two digits of minute (00 through 59)
# ss = two digits of second (00 through 59)
# TZD = time zone designator (Z or +hh:mm or -hh:mm)
---

**Important Note**

*The bot's default prefix is !t (or !translate) - All commands must start with this prefix for the bot to process them.
Bot must have proper permissions in all relevant channels for full functionality (**read**, **write**, **react**, **mention**, **attachments**, **embed**).*

----

Automatically translates any new messages in the current channel and forwards them to you. Admins/mods can set forwarding to same channel, other channels or other users in the server. Messages in forwarded channels will also be sent back to origin*.

# Command
```bash
!translate channel from '[lang]' to `[lang]` for [dest]
```

# Parameters
* for **`[dest]`** _(optional)_  
Forwarding destination where the translated messages will be sent, defaults to "me" - translations sent via direct/private messages between you and the bot. Admins/mods can use discord mentions as forward destination with possibility to set multiple destinations at once. See examples below.

* to **`[lang]`** _(optional)_  
The language to translate to, defaults to server default language.

* from **`[lang]`** _(optional)_  
The language to translate from.

# Examples  
Using full language names
```bash
!translate channel from **`english`** to **`spanish`**  
```

Using language short codes
```bash
!translate channel from **`en`** to **`es`**  
```

Assigning a user as the target for translations
```bash
!translate channel from **`english`** to **`spanish`** for **`me`**
```

## Server Admins/Mods
Send translations to same channel
```bash
!translate channel from **`english`** to **`spanish`** for **`#SameChannelMention`**
```

Send translations to another channel in server
```bash
!translate channel from **`english`** to **`spanish`** for **`#OtherChannelMention`**  
```

Send translations to another user in server
```bash
!translate channel from **`english`** to **`spanish`** for **`@UserMention`**
```

Send translations to multiple channels/users in server at once
```bash
!translate channel from **`english`** to **`spanish`** for **`#Channel1`**, **`#Channel2`**, **`@User1`**, **`@User2`**
```

## Stopping
To stop an automatic translation task, simply go the original channel and use the stop command:
```bash
!translate stop  
!translate stop for me
```

## Admins/Mods
Stop all automatic translations
```bash
!translate stop for all
```

Stop all automatic translations for specific channel in server
```bash
!translate stop for #ForwardChannelMention
```

Stop all automatic translations for specific user in server
```bash
!translate stop for @UserMention
```

*Help command for stop: `!translate help stop`*

## Notes
*Help command for automatic translation: !translate help auto.*

Values wrapped in brackets **`[ ]`** mean user input.
**`[lang]`** values can be language names in English, native language names or ISO 639-1 codes. For example, **`german`** **`de`** and **`deutsch`** will all work the same.

Messages by bots are ignored.

Command messages are also ignored.

If you have a lot of users speaking a different language then it is advised you create a special public channel for them as a destination instead of having each one receive translated messages in private.
