---
title: 'WebLLM: A High-Performance In-Browser LLM Inference Engine'

authors:
  - Charlie F. Ruan
  - Yucheng Qin
  - Xun Zhou
  - Ruihang Lai
  - Hongyi Jin
  - Yixin Dong
  - Bohan Hou
  - Meng-Shiun Yu
  - Yiyan Zhai
  - Sudeep Agarwal
  - Hangrui Cao
  - Siyuan Feng
  - Tianqi Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2024-12-08'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-08'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: Advancements in large language models (LLMs) have unlocked remarkable capabilities across various domains. However, deploying these models typically requires server-level GPUs and cloud-based inference. The recent emergence of smaller open-source models and increasingly powerful consumer devices has made on-device deployment a viable alternative. Specifically, the web browser as a platform for on-device deployment is universally accessible, provides a natural agentic environment, and conveniently abstracts out the different backends from diverse device vendors. To address this opportunity, we introduce WebLLM, an open-source JavaScript framework that enables high-performance LLM inference entirely within web browsers. WebLLM provides an OpenAI-style API for seamless integration into web applications, and leverages WebGPU for efficient local GPU acceleration and WebAssembly for performant CPU computation. By utilizing machine learning compilers MLC-LLM and Apache TVM, WebLLM generates optimized WebGPU kernels, overcoming the absence of performant GPU libraries in browsers. Our architecture adapts to the browser's runtime environment through web workers, ensuring smooth and uninterrupted user interfaces. Evaluation results demonstrate that WebLLM can preserve up to 80% performance of native deployment on the same device, with the potential to further close the gap. This work paves the way for universally accessible, privacy-preserving, personalized, and locally powered LLM applications in web browsers.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://openreview.net/pdf?id=ISRyILhAyS'
# url_poster: 'https://docs.google.com/presentation/d/1t3zp4-4bu7gZcFs-gJL0okiSw_0hd01X/edit?usp=sharing'
url_code: 'https://github.com/mlc-ai/web-llm'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: CD-GraB Paper Figure 1'
#   focal_point: ''
#   preview_only: false

---