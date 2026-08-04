---
title: "Debug your Postgres from the terminal: a tour of `neon inspect db`"
url: "https://neon.com/blog/neon-inspect-db"
date: "2026-07-22"
author: "Savannah Longoria"
feed_url: "https://neon.com/blog/rss.xml"
---
The Neon CLI now ships `neon inspect db`: read-only, high-signal Postgres diagnostics that answer "what is slow?" without leaving the terminal or writing a single catalog query. Each subcommand runs one known-good query against Postgres' own statistics and catalog views and prints a clean table (or JSON/YAML for scripting).
