---
title: VeriTrade
summary: Using Machine Learning to automate trade finance verification. The solution involves extracting critical information across various documents like Bill of lading, Letter of credit, etc, and making sure those documents comply with ICC UCP & ISBP rules.
tags:
- Industry Projects
- Machine Learning
- NLP
- Computer Vision
date: "2019-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Veritrade is a solution to automate trade finance verification. The solution uses state of the art deep learning to first identify the type of documents from 23 different categories like Bill of Lading, Letter of Credit, Invoice, etc. Once a document is classified the solution extracts critical information like issue date, type of commodity, billing address, etc from each of those 23 documents using a hybrid approach comprising of both machine learning and heuristics. The information extraction approach is robust enough to handle different variations across the same documents.
The solution then runs around 4000 consistency checks and rules specified by UCP and ISBP. The rules and consistency checks can be intra and inter documents. 

Advantages of Veritrade:
* Massive efficiency gains of ~80%
* Drastically reduces the operational risk
* Brings objectivity to the UCP/ISBP rules
* Flexible to quickly adapt to any UCP/ISBP rules
* Eliminates training cost