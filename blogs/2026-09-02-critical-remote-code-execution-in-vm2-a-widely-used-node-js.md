---
title: "Critical remote code execution in vm2, a widely used Node.js sandbox library"
url: "https://about.gitlab.com/blog/critical-remote-code-execution-in-vm2/"
date: "2026-09-02"
author: "Abisheik Magesh"
feed_url: "https://about.gitlab.com/atom.xml"
---
GitLab's Threat Research Group found a critical sandbox escape vulnerability in vm2, one of the most widely adopted Node.js sandboxing libraries. The vulnerability uses a configuration copied straight from vm2's own README. We found the flaw, rated CVSS 3.1: 10.0, critical, using our own AI automated tools.
