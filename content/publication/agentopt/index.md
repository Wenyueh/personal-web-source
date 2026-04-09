---
title: 'AgentOpt v0.1 Technical Report: Client-Side Optimization for LLM-Based Agent'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sripad Karne
  - Qian Xie
  - Armaan Agrawal
  - Nikos Pagonas
  - Kostis Kaffes
  - Tianyi Peng

author_notes:
  - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Equal contribution'

date: '2026-04-07'
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
summary: AgentOpt is a framework-agnostic Python package addressing client-side optimization challenges in AI agents. Rather than focusing on server-side efficiency, it examines how developers should allocate resources—including model choices, local tools, and API budgets—across agent pipeline stages. The cost gap between the best and worst model combinations can reach 13--32x in our experiments. The framework implements eight search algorithms to efficiently navigate model assignment possibilities, with Arm Elimination achieving near-optimal accuracy while reducing evaluation budget by 24–67% compared to brute-force approaches.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2604.06296'
url_code: 'https://github.com/AgentOptimizer/agentopt'
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
  - MLSys

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

## Abstract
AI agents are increasingly deployed in real-world applications, including systems such as Manus, OpenClaw, and coding agents. Existing research has primarily focused on server-side efficiency, proposing methods such as caching, speculative execution, traffic scheduling, and load balancing to reduce the cost of serving agentic workloads. However, as users increasingly construct agents by composing local tools, remote APIs, and diverse models, an equally important optimization problem arises on the client side. Client-side optimization asks how developers should allocate the resources available to them, including model choice, local tools, and API budget across pipeline stages, subject to application-specific quality, cost, and latency constraints. Because these objectives depend on the task and deployment setting, they cannot be determined by server-side systems alone. We introduce AgentOpt, the first framework-agnostic Python package for client-side agent optimization. We first study model selection, a high-impact optimization lever in multi-step agent pipelines. Given a pipeline and a small evaluation set, the goal is to find the most cost-effective assignment of models to pipeline roles. This problem is consequential in practice: at matched accuracy, the cost gap between the best and worst model combinations can reach 13–32× in our experiments. To efficiently explore the exponentially growing combination space, AgentOpt implements eight search algorithms, including Arm Elimination, Epsilon-LUCB, Threshold Successive Elimination, and Bayesian Optimization. Across four benchmarks, Arm Elimination recovers near-optimal accuracy while reducing evaluation budget by 24–67% relative to brute-force search on three of four tasks.