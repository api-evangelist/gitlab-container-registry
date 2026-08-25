---
title: "Avoid the massive end-to-end tax of default full history clones"
url: "https://about.gitlab.com/blog/git-clone-override-policy/"
date: "2026-08-18"
author: "Darwin Sanoy"
feed_url: "https://about.gitlab.com/atom.xml"
---
It's easy to think of git clone as a client-side operation, but the settings of this operation impact the server side and all networks in between. When you run a default full history clone, the server has to walk the entire history, build a pack file for it (that's what "counting objects" is actually doing), and ship it over the wire. The client then unpacks all of it and checks out a full working tree.
