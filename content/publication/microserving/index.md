---
title: 'A System for Microserving of LLMs'

authors:
  - Hongyi Jin
  - Ruihang Lai
  - charlieruan
  - Yingcheng Wang
  - Todd Mowry
  - Xupeng Miao
  - Zhihao Jia
  - Tianqi Chen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-12-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-17'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: Under Submission
publication_short: Under Submission

abstract: The recent advances in LLMs bring a strong demand for efficient system support to improve overall serving efficiency. As LLM inference scales towards multiple GPUs and even multiple compute nodes, various coordination patterns, such as prefill-decode disaggregation and context migration, arise in serving systems. Most inference services today expose a coarse-grained request-level API with a pre-configured coordination strategy, limiting the ability to customize and dynamically reconfigure the coordination. In this paper, we propose LLM microserving, a multi-level architecture for structuring and programming LLM inference services. We introduces simple yet effective microserving APIs to support fine-grained sub-request level actions. A programmable router transforms user requests into sub-request calls, enabling the dynamic reconfiguration of serving patterns. To support diverse execution patterns, we develop a unified KV cache interface that handles various KV compute, transfer, and reuse scenarios. Our evaluation shows that LLM microserving can be reconfigured to support multiple disaggregation orchestration strategies in a few lines of Python code while maintaining state-of-the-art performance for LLM inference tasks. Additionally, it allows us to explore new strategy variants that reduce up to 47% of job completion time compared to the existing strategies.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2412.12488'
# url_poster: 'https://docs.google.com/presentation/d/1t3zp4-4bu7gZcFs-gJL0okiSw_0hd01X/edit?usp=sharing'
url_code: 'https://github.com/mlc-ai/mlc-llm'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: CD-GraB Paper Figure 1'
#   focal_point: ''
#   preview_only: false

---