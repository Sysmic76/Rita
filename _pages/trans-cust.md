---
title: "Translate - Custom Message"
permalink: /trans-cust/
excerpt: "Translate a Custom Message"
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

*Users who wish to receive automatic translations in private must **enable DMs** via **server privacy settings**.*

----

Translates a custom message entered by user.

# Command
```c++
> !t this: [msg]  
> !t this to [lang] from [lang]: [msg]
```

# Parameters
* to **`[lang]`** - defaults to server default language

* to **`[lang, lang, ...]`** - translates to multiple languages

* from [lang] - defaults to automatic detection

# Examples
```c++
> !t this: bonjour  
> !t this to spanish: hello world  
> !t this to arabic, hebrew: I love you  
> !t this to de from en: how are you?
```
