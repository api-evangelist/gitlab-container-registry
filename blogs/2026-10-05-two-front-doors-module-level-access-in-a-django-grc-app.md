---
title: "Two front doors: Module-level access in a Django GRC app"
url: "https://about.gitlab.com/blog/module-level-access-in-a-django-grc-app/"
date: "2026-10-05"
author: "Donovan Felton"
feed_url: "https://about.gitlab.com/atom.xml"
---
GitLab's engineering team builds a lot of our own internal tooling, but one platform in particular forced us to rethink how we handle authorization: our internal GRC tool that serves two very different customer bases under one roof — our Security Compliance team and our Internal Audit team. If you're building or maintaining an internal Django tool that's starting to serve more than one audience — different teams, different data classification levels, different data that shouldn't cross streams — this post walks through the problem we hit, how we solved it, and how you can apply the same patter
