---
title: 'Local deployment of large-scale music AI models on commodity hardware'

authors:
  - Xun Zhou
  - Charlie Ruan
  - Zihe Zhao
  - Tianqi Chen
  - Chris Donahue

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-11-14'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-14'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: 25th Conference of the International Society for Music Information Retrieval (ISMIR) Late-Breaking Demo Session
publication_short: ISMIR'24 LBD

abstract: We present the MIDInfinite, a web application capable of generating symbolic music using a large-scale generative AI model locally on commodity hardware. Creating this demo involved porting the Anticipatory Music Transformer, a large language model (LLM) pre-trained on the Lakh MIDI dataset, to the Machine Learning Compilation (MLC) framework. Once the model is ported, MLC facilitates inference on a variety of runtimes including C++, mobile, and the browser. We envision that MLC has the potential to bridge the gap between the landscape of increasingly capable music AI models and technology more familiar to music software developers. As a proof of concept, we build a web application that allows users to generate endless streams of multi-instrumental MIDI in the browser, either from scratch or conditioned on a prompt. On commodity hardware (an M3 Macbook Pro), our demo can generate 51 notes per second, which is faster than real-time playback for 72.9% of generations, and increases to 86.3% with 2 seconds of upfront buffering.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2411.09625'
# url_poster: 'https://docs.google.com/presentation/d/1t3zp4-4bu7gZcFs-gJL0okiSw_0hd01X/edit?usp=sharing'
# url_code: 'https://github.com/mlc-ai/xgrammar'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: CD-GraB Paper Figure 1'
#   focal_point: ''
#   preview_only: false

---