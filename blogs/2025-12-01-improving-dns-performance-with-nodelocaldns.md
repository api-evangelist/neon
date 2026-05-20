---
title: "Improving DNS performance with NodeLocalDNS"
url: "https://neon.com/blog/improving-dns-performance-with-nodelocaldns"
date: "Mon, 01 Dec 2025 16:36:27 GMT"
author: "Luca Cittadini"
feed_url: "https://neon.com/blog/rss.xml"
---
At Neon, we run hundreds of thousands of Postgres databases as ephemeral Kubernetes pods. Because of our scale-to-zero feature, every time a user connects to their database, there’s a chance that we need to spin up a new Postgres process to serve that connection. The newly spun P...
