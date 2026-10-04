---
title: "Inside branch-based restores in Lakebase Postgres"
url: "https://neon.com/blog/inside-branch-based-restores-in-lakebase-postgres"
date: "2026-09-28"
author: "Carlota Soto"
feed_url: "https://neon.com/blog/rss.xml"
---
Restores are broken in managed OLTP, and they have been broken for a long time. They are slow, and they get slower with scale. The databases that need recovery most, the large production ones, are the ones left waiting the longest.
