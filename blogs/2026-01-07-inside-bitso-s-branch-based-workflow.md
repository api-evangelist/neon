---
title: "Inside Bitso’s Branch-Based Workflow"
url: "https://neon.com/blog/bitso-branching-workflow"
date: "Wed, 07 Jan 2026 17:01:55 GMT"
author: "Carlota Soto"
feed_url: "https://neon.com/blog/rss.xml"
---
“Neon’s branching gave us the last missing piece in our RISE (Robust Isolated Staging Environment): true database isolation. The services that touched schema changes or write-heavy paths could never share a database safely. Now every sandbox gets its own isolated Postgres DB when...
