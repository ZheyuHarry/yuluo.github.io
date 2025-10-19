---
title: "TrioXpert: An Automated Incident Management Framework for Microservice System"
authors:
- Yongqian Sun
- admin
- Xidao Wen
- et al.
date: "2025-09-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/ACM ASE*
publication_short: In *ASE*

abstract: Automated incident management plays a pivotal role in large-scale microservice systems. However, many existing methods rely solely on single-modal data (e.g., metrics, logs, and traces) and struggle to simultaneously address multiple downstream tasks, including anomaly detection (AD), failure triage (FT), and root cause localization (RCL). Moreover, the lack of clear reasoning evidence in current techniques often leads to insufficient interpretability. To address these limitations, we propose TrioXpert, an end-to-end incident management framework capable of fully leveraging multimodal data. TrioXpert designs three independent data processing pipelines based on the inherent characteristics of different modalities, comprehensively characterizing the operational status of microservice systems from both numerical and textual dimensions. It employs a collaborative reasoning mechanism using large language models (LLMs) to simultaneously handle multiple tasks while providing clear reasoning evidence to ensure strong interpretability. We conducted extensive evaluations on two popular microservice system datasets, and the experimental results demonstrate that TrioXpert achieves outstanding performance in AD (improving by 4.7% to 57.7%), FT (improving by 2.1% to 40.6%), and RCL (improving by 1.6% to 163.1%) tasks. TrioXpert has also been deployed in Lenovo's production environment, demonstrating substantial gains in diagnostic efficiency and accuracy.

# Summary. An optional shortened abstract.
summary: TrioXpert is an end-to-end framework for incident management in microservice systems that leverages multimodal data and LLM-based collaborative reasoning to handle AD, FT, and RCL tasks with high interpretability. It significantly outperforms baselines across multiple benchmarks.

tags:
- Large Language Models
- Anomaly Detection
- Failure Triage
- Root Cause Localization

featured: true

links:
- name: ''
  url: ''
url_pdf: https://nkcs.iops.ai/wp-content/uploads/2025/10/TrioXpert1.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://zheyuharry.github.io/yuluo.github.io/slides/TrioXpert-slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overview'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
