---
title: 'System 1+ System 2= Better World: Neural-Symbolic Chain of Logic Reasoning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yongfeng Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-28'
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

# abstract: Can we avoid wars at the crossroads of history? This question has been pursued by individuals, scholars, policymakers, and organizations throughout human history. In this research, we attempt to answer the question based on the recent advances of Artificial Intelligence (AI) and Large Language Models (LLMs). We propose \textbf{WarAgent}, an LLM-powered multi-agent AI system, to simulate the participating countries, their decisions, and the consequences, in historical international conflicts, including the World War I (WWI), the World War II (WWII), and the Warring States Period (WSP) in Ancient China. By evaluating the simulation effectiveness, we examine the advancements and limitations of cutting-edge AI systems' abilities in studying complex collective human behaviors such as international conflicts under diverse settings. In these simulations, the emergent interactions among agents also offer a novel perspective for examining the triggers and conditions that lead to war. Our findings offer data-driven and AI-augmented insights that can redefine how we approach conflict resolution and peacekeeping strategies. The implications stretch beyond historical analysis, offering a blueprint for using AI to understand human history and possibly prevent future international conflicts. Code and data are available at [this url](https://github.com/agiresearch/WarAgent). 

# Summary. An optional shortened abstract.
summary: Logical reasoning is a challenge for many current NLP neural network models since it requires more than the ability of learning informative representations from data. Inspired by the Dual Process Theory in cognitive science—which proposes that human cognition process involves two stages -- an intuitive, unconscious and fast process relying on perception calledSystem 1, and a logical, conscious and slow process performing complex reasoning called System 2—we leverage neural logic reasoning (System 2) on top of the representation learning models (System 1), which conducts explicit neural-based differentiable logical reasoning on top of the representations learned by the base neural models. Based on experiments on the commonsense knowledge graph completion task, we show that the two-system architecture always improves from its System 1 model alone. Experiments also show that both the rule-driven logical regularizer and the data-driven value regularizer are important and the performance improvement is marginal without the two regularizers, which indicates that learning from both logical prior and training data is important for reasoning tasks.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

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
  - pre-LLM NLP

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

## Abstract
Logical reasoning is a challenge for many current NLP neural network models since it requires more than the ability of learning informative representations from data. Inspired by the Dual Process Theory in cognitive science—which proposes that human cognition process involves two stages: an intuitive, unconscious and fast process relying on perception calledSystem 1, and a logical, conscious and slow process performing complex reasoning called System 2—we leverage neural logic reasoning (System 2) on top of the representation learning models (System 1), which conducts explicit neural-based differentiable logical reasoning on top of the representations learned by the base neural models. Based on experiments on the commonsense knowledge graph completion task, we show that the two-system architecture always improves from its System 1 model alone. Experiments also show that both the rule-driven logical regularizer and the data-driven value regularizer are important and the performance improvement is marginal without the two regularizers, which indicates that learning from both logical prior and training data is important for reasoning tasks.