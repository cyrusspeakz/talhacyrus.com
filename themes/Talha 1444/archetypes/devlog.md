---
CUID: {{ .Date }}

type: devlog
layout:
status:
  - Next Up
  - In Progress
  - Archived
  - Cancelled

draft: true
feature: false
private: false
headless: false
highlight: false

growth: false
growthStage:
  - Seedling
  - Sprout
  - Evergreen
growthStart: ""
growthEnd: ""
growthUpdate: ""

date: {{ .Date }}
publishDate:
expiryDate:
lastmod:

url: ""
slug: ""
aliases: []
linkTitle: ""

series: []
title: {{ replace .Name "-" " " | title }}
subtitle: ""
summary:
description: ""

collections: []
categories: []
subjects: []
topics: []
tags: []

cover: ""
coverAltText: ""
coverCaptionText: ""
coverThumbnail: ""
coverURL: ""

authors:
  - {{ .Site.Params.defaultAuthor }}
authorsNoteType:
  - 
authorsNoteCustom:

localNotificationDisplay: true
localNotificationText: ""

tocDisplay: false
socialShareDisplay: false

characterCountDisplay: false
wordCountDisplay: false
readTimeDisplay: false
---

New features
Enhancements
Bugs and their fixes
Deprecated, soon-to-be-removed features
Removed, no-longer-available features
Security vulnerabilities