---
title: "Dependency Firewall: Block risky packages before the build"
url: "https://about.gitlab.com/blog/transcend-dependency-firewall/"
date: "2026-10-06"
author: "Alisa Ho"
feed_url: "https://about.gitlab.com/atom.xml"
---
Attackers disguise malicious packages as ones you trust. In June 2026, GitLab researchers found five malicious PyPI packages , four of them typosquats of Flask, Requests, and NumPy, that run at install time and steal CI/CD credentials. Additionally, AI coding agents now add open source dependencies on their own, often unreviewed, so developers don't have oversight into what packages may contaminate your build.
