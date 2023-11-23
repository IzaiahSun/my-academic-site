---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
classes: wide

# toc: true
# toc_label: "Table of Contents"
# toc_icon: "cog"

title: "Who is the Real Hero? Measuring Developer Contribution via Multi-dimensional Data Integration"
date: 2023-09-03 

---

## Abstract

Proper incentives are important for motivating developers in open-source communities, which is crucial for maintaining the development of open-source software healthy. To provide such incentives, an accurate and objective developer contribution measurement method is needed. However, existing methods rely heavily on manual peer review, lacking objectivity and transparency. The metrics of some automated works about effort estimation use only syntax-level or even text-level information, such as changed lines of code, which lack robustness. Furthermore, some works about identifying core developers provide only a qualitative understanding without a quantitative score or have some project-specific parameters, which makes them not practical in real-world projects. To this end, we propose CValue, a multidimensional information fusion-based approach to measure developer contributions. CValue extracts both syntax and semantic information from the source code changes in four dimensions: modification amount, understandability, inter-function and intra-function impact of modification. It fuses the information to produce the contribution score for each of the commits in the projects. Experimental results show that CValue outperforms other approaches by 19.59% on 10 real-world projects with manually labeled ground truth. We validated and proved that the performance of CValue, which takes 83.39 seconds per commit, is acceptable to be applied in real-world projects. Furthermore, we performed a large-scale experiment on 174 projects and detected 2,282 developers having inflated commits. Of these, 2,050 developers did not make any syntax contribution; and 103 were identified as bots.

## Access
- arxiv: [https://arxiv.org/abs/2308.08991](https://arxiv.org/abs/2308.08991)
- IEEE Xplore: [https://ieeexplore.ieee.org/document/10298552/](https://ieeexplore.ieee.org/document/10298552/)
- ASE Conference Website: [https://conf.researchr.org/details/ase-2023/ase-2023-papers/17/Who-is-the-Real-Hero-Measuring-Developer-Contribution-via-Multi-dimensional-Data-Int](https://conf.researchr.org/details/ase-2023/ase-2023-papers/17/Who-is-the-Real-Hero-Measuring-Developer-Contribution-via-Multi-dimensional-Data-Int)
