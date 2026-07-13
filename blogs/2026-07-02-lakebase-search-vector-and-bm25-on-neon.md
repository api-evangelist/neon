---
title: "Lakebase Search: vector and BM25 on Neon"
url: "https://neon.com/blog/lakebase-search-on-neon"
date: "2026-07-02"
author: "Savannah Longoria"
feed_url: "https://neon.com/blog/rss.xml"
---
Neon launched the beta of Lakebase Search, combining hybrid vector and full-text retrieval through two Postgres extensions. It uses IVF plus RaBitQ indexing instead of HNSW, and BM25 search with top-K pushdown optimization, with indexes stored on object storage so they persist through scale-to-zero and branch instantly.
