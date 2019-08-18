---
title: Navigating through the sea of GNSS hardware manufacturers
subtitle: 
summary: 
authors:
- admin
tags: []
categories: []
date: "2016-02-05T00:00:00Z" 
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

With an exponentially growing GNSS market, it can quickly become overwhelming when trying to decide on the ideal receiver that would meet a client's specifications. Because of this, I began collecting information on different GNSS receivers with the aim of developing a web utility that would allow the user to enter their specifications and the utility recommend suitable receivers. Over the pass couple months, I’ve been collecting publicly available information on different types of GNSS receivers.

Currently, the database consists of ~150 engineering grade GNSS receivers and information collected consider signal tracking capabilities, solution quality, data and memory, communications, physical characteristics, power and environmental conditions. The web utility is currently in an early stage of development with a few options still to be implemented and some additional data verification required.
Depending on user feedback, I am considering:
1.  Expanding the database from engineering grade receivers to lower accuracy receivers
2.  Creating a form which would allow users to submit receivers directly to the database

{{< gnss_hardware >}}
