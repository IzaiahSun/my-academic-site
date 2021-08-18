---
abstract: Attackers upload webshell into a web server to achieve the purpose of
  stealing data, launching a DDoS attack, modifying files with malicious
  intentions, etc. Once these objects are accomplished, it will bring huge
  losses to website managers. With the gradual development of encryption and
  confusion technology, the most common detection approach using taint analysis
  and feature matching might become less useful. Instead of applying source file
  codes, POST contents, or all received traffic, this paper demonstrated an
  intelligent and efficient framework that employs precise sessions derived from
  the web logs to detect webshell communication. Features were extracted from
  the raw sequence data in web logs while a statistical method based on time
  interval was proposed to identify sessions specifically. Besides, the paper
  leveraged long short-term memory and hidden Markov model to constitute the
  framework, respectively. Finally, the framework was evaluated with real data.
  The experiment shows that the LSTM-based model can achieve a higher accuracy
  rate of 95.97% with a recall rate of 96.15%, which has a much better
  performance than the HMM-based model. Moreover, the experiment demonstrated
  the high efficiency of the proposed approach in terms of the quick detection
  without source code, especially when it only considers detecting for a period
  of time, as it takes 98.5% less time than the cited related approach to get
  the result. As long as the webshell behavior is detected, we can pinpoint the
  anomaly session and utilize the statistical method to find the webshell file
  accurately.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Yixin Wu
  - Yuqiang Sun
  - Cheng Huang
  - Peng Jia
  - Luping Liu
author_notes: []
publication: Security and Communication Network
summary: ""
url_dataset: ""
url_project: ""
publication_short: SCN
url_source: ""
url_video: ""
title: Session-Based Webshell Detection Using Machine Learning in Web Logs
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: null
date: 2020-11-22T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
