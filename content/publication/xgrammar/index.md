---
title: 'XGrammar: Flexible and Efficient Structured Generation Engine for Large Language Models'

authors:
  - Yixin Dong
  - Charlie F Ruan
  - Yaxing Cai
  - Ruihang Lai
  - Ziyi Xu
  - Yilong Zhao
  - Tianqi Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution, alphabetical order'
#   - 'Equal contribution, alphabetical order'
#   - 'Equal contribution, alphabetical order'
#   - 'Equal contribution, alphabetical order'

date: '2024-11-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-22'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under Submission
publication_short: Under Submission

abstract: The applications of LLM Agents are becoming increasingly complex and diverse, leading to a high demand for structured outputs that can be parsed into code, structured function calls, and embodied agent commands. These developments bring significant demands for structured generation in LLM inference. Context-free grammar is a flexible approach to enable structured generation via constrained decoding. However, executing context-free grammar requires going through several stack states over all tokens in vocabulary during runtime, bringing non-negligible overhead for structured generation. In this paper, we propose XGrammar, a flexible and efficient structure generation engine for large language models. XGrammar accelerates context-free grammar execution by dividing the vocabulary into context-independent tokens that can be prechecked and context-dependent tokens that need to be interpreted during runtime. We further build transformations to expand the grammar context and reduce the number of context-independent tokens. Additionally, we build an efficient persistent stack to accelerate the context-dependent token checks. Finally, we co-design the grammar engine with LLM inference engine to overlap grammar computation with GPU executions. Evaluation results show that XGrammar can achieve up to 100x speedup over existing solutions. Combined with an LLM inference engine, it can generate near-zero overhead structure generation in end-to-end low-LLM serving.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2411.15100'
# url_poster: 'https://docs.google.com/presentation/d/1t3zp4-4bu7gZcFs-gJL0okiSw_0hd01X/edit?usp=sharing'
url_code: 'https://github.com/mlc-ai/xgrammar'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: CD-GraB Paper Figure 1'
#   focal_point: ''
#   preview_only: false

---