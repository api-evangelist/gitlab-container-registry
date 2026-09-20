---
title: "When to use SAST versus an LLM security scanner"
url: "https://about.gitlab.com/blog/sast-vs-llm-security-scanner/"
date: "2026-09-16"
author: "Meir Benayoun"
feed_url: "https://about.gitlab.com/atom.xml"
---
You're probably running some version of this experiment already: Point a frontier model at a merge request and ask it to double as a vulnerability scanner. On a single merge request, it often works well. The model reads the code, reasons about what it's supposed to do, and catches real issues, sometimes ones a pattern-based scanner misses entirely.
