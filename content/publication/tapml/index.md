---
title: 'Emerging Platforms Meet Emerging LLMs: A Year-Long Journey of Top-Down Development'

authors:
  - Siyuan Feng
  - Jiawei Liu
  - Ruihang Lai
  - Charlie F. Ruan
  - Yong Yu
  - Lingming Zhang
  - Tianqi Chen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-04-16'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-16'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: Under Submission
publication_short: Under Submission

abstract: Deploying machine learning (ML) on diverse computing platforms is crucial to accelerate and broaden their applications. However, it presents significant software engineering challenges due to the fast evolution of models, especially the recent Large Language Models (LLMs), and the emergence of new computing platforms. Current ML frameworks are primarily engineered for CPU and CUDA platforms, leaving a big gap in enabling emerging ones like Metal, Vulkan, and WebGPU. While a traditional bottom-up development pipeline fails to close the gap timely, we introduce TapML, a top-down approach and tooling designed to streamline the deployment of ML systems on diverse platforms, optimized for developer productivity. Unlike traditional bottom-up methods, which involve extensive manual testing and debugging, TapML automates unit testing through test carving and adopts a migration-based strategy for gradually offloading model computations from mature source platforms to emerging target platforms. By leveraging realistic inputs and remote connections for gradual target offloading, TapML accelerates the validation and minimizes debugging scopes, significantly optimizing development efforts. TapML was developed and applied through a year-long, real-world effort that successfully deployed significant emerging models and platforms. Through serious deployments of 82 emerging models in 17 distinct architectures across 5 emerging platforms, we showcase the effectiveness of TapML in enhancing developer productivity while ensuring model reliability and efficiency. Furthermore, we summarize comprehensive case studies from our real-world development, offering best practices for developing emerging ML systems.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2404.09151'
# url_poster: 'https://docs.google.com/presentation/d/1t3zp4-4bu7gZcFs-gJL0okiSw_0hd01X/edit?usp=sharing'
# url_code: 'https://github.com/mlc-ai/xgrammar'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: CD-GraB Paper Figure 1'
#   focal_point: ''
#   preview_only: false

---