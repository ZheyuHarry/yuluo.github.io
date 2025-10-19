---
title: "Predicting the Impact of Parameter Adjustments on Cellular Networks"
authors:
- Yongqian Sun
- Qingliang Zhang
- admin
- et al.
date: "2025-08-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE ISSRE*
publication_short: In *ISSRE*

abstract: Cellular networks are critical infrastructure for user equipment to access the Internet. Given the spatio-temporal dynamics of user distribution and traffic demand, operators adjust parameters such as transmission power (TP) and cell individual offset (CIO) to enhance network stability and service quality, However, predicting the impact of such adjustments is challenging due to limited historical adjustment data and complex metric dependencies. We propose PIPCell, a two-phase predictive framework. In phase one, PIPCell uses a closed-form multiplier from TP and CIO domain knowledge to calibrate adjustment free Workload predictions from pre-trained Transformers. In phase two, a causal graphical model organizes multiple pretrained Transformers to capture inter-metric dependencies and propagate adjustment effects. Experiments on real-world dataset from China Mobile show that PIPCell outperforms the best baseline by up to 25.8% in RMSE and 59.0% in sMAPE, demonstrating PIPCell’s potential for proactive and data-efficient cellular network optimization.

# Summary. An optional shortened abstract.
# summary: TrioXpert is an end-to-end framework for incident management in microservice systems that leverages multimodal data and LLM-based collaborative reasoning to handle AD, FT, and RCL tasks with high interpretability. It significantly outperforms baselines across multiple benchmarks.

tags:
- Cellular network
- parameter adjustment
- time series forecasting
- causal inference

featured: false

links:
- name: ''
  url: ''
url_pdf: https://nkcs.iops.ai/wp-content/uploads/2025/08/PIPCell_ISSRE_CameraReady_v5.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://zheyuharry.github.io/yuluo.github.io/slides/PIPCell_v2.pdf'
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
