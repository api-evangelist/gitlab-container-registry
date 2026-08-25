---
title: "Critical remote code execution in Serena, a popular MCP coding agent"
url: "https://about.gitlab.com/blog/critical-rce-in-serena/"
date: "2026-08-17"
author: "Daniel Abeles"
feed_url: "https://about.gitlab.com/atom.xml"
---
Serena, one of the most widely used AI coding agents, ran attacker-supplied code the moment a developer opened a project. GitLab's Threat Research Group found a critical server-side template injection ( GHSA-pp25-4cg4-qcr9 , CVE pending) that executes arbitrary code in the Serena process. Anyone on serena-agent 1.6.1 or earlier should update to 1.7.0 now.
