---
title: "When a file is uploaded, run the job on Neon"
url: "https://neon.com/blog/when-a-file-is-uploaded-run-the-job-on-neon"
date: "2026-09-22"
author: "Mike Jerome"
feed_url: "https://neon.com/blog/rss.xml"
---
A file in a bucket is just bytes; when you upload it, there is often a job to do next with that file, and that job usually involves Postgres - a `files` row, a status, a thumbnail key. That is a perfect Neon Functions job; the missing piece was something to start the Function when the object appeared, without extra application code watching the bucket.
