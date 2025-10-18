---
title: "Adaptive Performance Regression Detection via Semi-Supervised Siamese Learning"
authors:
- Yongqian Sun
- Mengyao Li
- Xiao Xiong
- Lei Tao
- Yimin Zuo
- Wenwei Gu
- Shenglin Zhang
- Junhua Kuang
- admin
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

abstract: Timely detection of performance regression issues is critical to ensuring the stability and user experience of software systems. Traditional methods often rely on high-quality annotated data or data distribution assumptions, which cannot effectively adapt to performance changes in dynamic workload environments. To solve this problem, we propose DynamicRegress, a performance regression detection method based on Siamese network and semisupervised learning. DynamicRegress integrates multi-dimensional key performance indicators (KPIs) with workload context to accurately characterize system states and detect performance regressions in real-time. By employing a dual weight-shared LSTM network, DynamicRegress reduces training complexity while retaining strong feature extraction capabilities. Data augmentation and a weighted loss function are incorporated to enhance the learning of minority regression cases, mitigating the class imbalance issue. Additionally, a semi-supervised learning strategy generates high-quality pseudo-labels to expand the training dataset, effectively addressing the challenge of limited labeled data. Experiments on production data from a top-tier global cloud service provider demonstrate that DynamicRegress achieves a superior F1 Score of 0.958 (outperforming the best baseline method by 0.282) while maintaining a low detection latency of 0.006 seconds per KPI pair. DynamicRegress provides a robust adaptive solution for performance regression detection in dynamic and complex software systems, and we have made the code publicly available to facilitate further research.

# Summary. An optional shortened abstract.
# summary: TrioXpert is an end-to-end framework for incident management in microservice systems that leverages multimodal data and LLM-based collaborative reasoning to handle AD, FT, and RCL tasks with high interpretability. It significantly outperforms baselines across multiple benchmarks.

tags:
- Performance Regression Detection
- Siamese Network
- Semi-supervised Learning


featured: true

links:
- name: ''
  url: ''
url_pdf: https://nkcs.iops.ai/wp-content/uploads/2025/09/Mengyao__SiameseLSTM.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
