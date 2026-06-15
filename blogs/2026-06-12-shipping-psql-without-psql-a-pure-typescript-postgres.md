---
title: "Shipping psql without psql: a pure-TypeScript Postgres client in neonctl"
url: "https://neon.com/blog/shipping-psql-without-psql"
date: "2026-06-12"
author: "Vadim Kharitonov"
feed_url: "https://neon.com/blog/rss.xml"
---
neonctl psql used to fail with "command not found" whenever psql wasn't on your PATH — which is most macOS laptops, slim Linux containers, Windows boxes, CI runners, and sandboxes. So we did the uncomfortable thing: reimplemented the psql client in pure TypeScript, embedded it in the CLI, and built a byte-exact conformance harness against PostgreSQL's own regression suite to prove it actually behaves like psql...
