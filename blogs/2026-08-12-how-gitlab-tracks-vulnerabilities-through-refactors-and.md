---
title: "How GitLab tracks vulnerabilities through refactors and reformatting"
url: "https://about.gitlab.com/blog/improved-scope-offset-fingerprinting/"
date: "2026-08-12"
author: "Julian Thome"
feed_url: "https://about.gitlab.com/atom.xml"
---
Every day, security scans face the same problem: an agent or a developer adds a comment, reformats a file, or moves a function, and a naive vulnerability tracker suddenly reports the same finding twice. Security teams end up re-triaging issues they already dismissed, which causes futile auditing effort and erodes trust in the scan results. In 2022, we introduced advanced vulnerability tracking to tackle exactly this problem of code volatility .
