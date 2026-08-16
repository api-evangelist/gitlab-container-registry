---
title: "A sandbox is only as closed as what an AI agent can reach"
url: "https://about.gitlab.com/blog/ai-agent-sandbox/"
date: "2026-08-12"
author: "Daniel Abeles"
feed_url: "https://about.gitlab.com/atom.xml"
---
In July, OpenAI and Hugging Face responsibly disclosed an OpenAI model under internal evaluation escaped its sandbox, reached the open internet, and accessed Hugging Face’s internal production infrastructure. The agent took datasets, cluster details, and cloud keys during the intrusion. The most critical part of the external phase of this incident was the first hour, when the agent escaped its sandbox by using a vulnerability within a package proxy on its sandbox’s allowlist to access the internet.
