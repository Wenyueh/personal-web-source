---
title: 'Quantifying Trust: Financial Risk Management for Trustworthy AI Agents'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tianyi Peng
  - Chi Wang
  - Ian Kaufman
  - Bryan Lim
  - Chandler Fang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-04-03'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ['3']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

# Summary. An optional shortened abstract.
summary: This paper shifts focus from internal model properties to end-to-end outcomes in trustworthy AI systems. Rather than relying solely on technical safeguards, we propose the Agentic Risk Standard (ARS) as a payment settlement standard for AI-mediated transactions. This framework integrates risk assessment, underwriting, and compensation into a single transaction framework to protect users. Under ARS, users receive enforceable compensation when agents fail to complete tasks, misalign with user intent, or produce unintended outcomes.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2604.03976'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Agent

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

## Abstract
Prior work on trustworthy AI emphasizes model-internal properties such as bias mitigation, adversarial robustness, and interpretability. As AI systems evolve into autonomous agents deployed in open environments and increasingly connected to payments or assets, the operational meaning of trust shifts to end-to-end outcomes: whether an agent completes tasks, follows user intent, and avoids failures that cause material or psychological harm. These risks are fundamentally product-level and cannot be eliminated by technical safeguards alone because agent behavior is inherently stochastic. To address this gap between model-level reliability and user-facing assurance, we propose a complementary framework based on risk management. Drawing inspiration from financial underwriting, we introduce the Agentic Risk Standard (ARS), a payment settlement standard for AI-mediated transactions. ARS integrates risk assessment, underwriting, and compensation into a single transaction framework that protects users when interacting with agents. Under ARS, users receive predefined and contractually enforceable compensation in cases of execution failure, misalignment, or unintended outcomes. This shifts trust from an implicit expectation about model behavior to an explicit, measurable, and enforceable product guarantee. We also present a simulation study analyzing the social benefits of applying ARS to agentic transactions.