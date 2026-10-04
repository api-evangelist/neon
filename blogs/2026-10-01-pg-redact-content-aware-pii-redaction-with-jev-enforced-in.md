---
title: "pg_redact: Content-aware PII redaction with Jev, enforced in Postgres"
url: "https://neon.com/blog/pg-redact-content-aware-pii-redaction-with-jev-enforced-in-postgres"
date: "2026-10-01"
author: "Rishi Raj Jain"
feed_url: "https://neon.com/blog/rss.xml"
---
PII redaction in Postgres today works column by column. Its limitation is that it only works when each piece of personal data has its own column, which is rarely the case with free text.
