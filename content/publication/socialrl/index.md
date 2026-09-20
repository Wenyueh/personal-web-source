---
title: 'From Passive Delegates to Strategic Negotiators: Reinforcing Social Reasoning in Small Language Models with SocialRL'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zachary Huang
  - Tyler Payne
  - Safoora Yousefi
  - Saleema Amershi
  - Asli Celikyilmaz

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-08-13'
doi: '10.48550/arXiv.2608.13787'

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
summary: AI agents increasingly act on their users' behalf, but the dispositions that make an assistant pleasant can make it a poor delegate. A friendly frontier model may disclose its principal's private information unprompted and concede at the first sign of resistance. We present SocialRL, a general recipe that trains social reasoning directly, and apply it to a 4B model across six negotiation and persuasion domains. In-domain training reaches the frontier, with the 4B model matching or exceeding the GPT-5 family per domain on held-out scenarios. Cross-domain transfer follows game structure, and cascade RL and multi-teacher on-policy distillation consolidate the per-domain specialists into a single unified 4B model.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2608.13787'
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
AI agents increasingly act on their users' behalf, handling tasks such as scheduling meetings, comparing offers, and haggling over prices. These principal-driven tasks routinely place the agent across from a counterpart (another user's agent, a seller, a recruiter) whose goals may conflict with its principal's. Yet the dispositions that make an assistant pleasant can make it a poor delegate: a friendly, helpful frontier model may disclose its principal's private information unprompted and concede at the first sign of resistance. We present SocialRL, a general recipe that trains social reasoning directly, and apply it to a 4B model across six domains: Deal-or-No-Deal, CaSiNo, Craigslist, Job Interview, Calendar, and Marketplace. Every domain is trained in-domain under the same recipe, and every policy is evaluated on all six. We find that (1) in-domain training reaches the frontier: on held-out scenarios the 4B matches or exceeds the GPT-5 family per domain, closing 73-122% of the baseline-to-frontier gap on the negotiation games, with 78% of buyer openings anchoring below target versus 3% untrained; (2) cross-domain transfer follows game structure: structurally paired games lift each other, a broad multi-issue donor lifts nearly all domains, and structurally isolated games transfer nothing; (3) guided by this transfer structure, two strategies, cascade RL and multi-teacher on-policy distillation (OPD), consolidate the per-domain specialists into a single unified 4B that reaches 0.627 average utility across all six environments, matching or exceeding GPT-4.1 (0.625), GPT-5.1 (0.619), and GPT-5.2 (0.613); (4) an explicit theory-of-mind scaffold helps only through training: distilling the ToM trace, rather than actions alone, lifts utility on every environment and generalizes better across them, and of the two ToM skills, only next-action prediction predicts negotiation outcomes.
