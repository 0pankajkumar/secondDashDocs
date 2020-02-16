---
date: 2020-02-15T10:26:15Z
lastmod: 2020-02-15T10:26:15Z
publishdate: 2020-02-15T10:26:15Z

title: Last Updated Date
description: Deciding last updated date
images:
- home-cover.png
weight: 70
---

The last updated date is the date at which last Upload was feeded.

It is calculated from the unique ID used by MongoDB to store & distinguish records. 
They use current timestamp to arrive at a unique ID while storing. We are reversing the procedure to get the date back.