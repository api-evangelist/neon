---
title: "Improving Lakebase Postgres Compute Cache on Neon, Part 1"
url: "https://neon.com/blog/improving-lakebase-compute-cache-part-1"
date: "2026-09-09"
author: "Sunil Kamath"
feed_url: "https://neon.com/blog/rss.xml"
---
On large fixed-size Lakebase Postgres computes on Neon, we now put most of the machine's memory into Postgres shared buffers and back that cache with huge pages. Hot pages stay in DRAM instead of falling through to a local disk cache, so the same working set is served faster and with less CPU.
