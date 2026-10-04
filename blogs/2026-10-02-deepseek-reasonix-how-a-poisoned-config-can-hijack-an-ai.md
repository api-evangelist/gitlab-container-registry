---
title: "DeepSeek-Reasonix: How a poisoned config can hijack an AI coding agent"
url: "https://about.gitlab.com/blog/deepseek-reasonix-vulnerability-discovered/"
date: "2026-10-02"
author: "Abisheik Magesh"
feed_url: "https://about.gitlab.com/atom.xml"
---
GitLab's Threat Research Group discovered a command execution vulnerability ( GHSA-grg2-7gc6-36m6 , CVE-2026-102437 ) in DeepSeek-Reasonix Studio, a desktop git client designed for developers pairing with AI coding assistants. The flaw, called ConfigPoisoning, could allow attacker-supplied code to execute when a developer views a file's diff. To address this vulnerability, you should update to DeepSeek-Reasonix Studio 2.21.0 or DeepSeek Reasonix npm 1.39.3.
