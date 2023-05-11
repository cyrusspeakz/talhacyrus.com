---
CUID: {{ .Date }}

type: newsletter
layout: issue
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

growth: true
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
summary: ""
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
authorsNoteCustom: ""

localNotificationDisplay: true
localNotificationText: ""

tocDisplay: true
socialShareDisplay: true

characterCountDisplay: true
wordCountDisplay: true
readTimeDisplay: true
---
