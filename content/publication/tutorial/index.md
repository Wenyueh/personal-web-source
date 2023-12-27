---
title: 'Tutorial on Large Language Models for Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lei Li
  - Shuyuan Xu
  - Chen Li
  - Yongfeng Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-11'
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
summary: Foundation Models such as Large Language Models (LLMs) have significantly advanced many research areas. In particular, LLMs offer significant advantages for recommender systems, making them valuable tools for personalized recommendations. For example, by formulating various recommendation tasks such as rating prediction, sequential recommendation, straightforward recommendation, and explanation generation into language instructions, LLMs make it possible to build universal recommendation engines that can handle different recommendation tasks. Additionally, LLMs have a remarkable capacity for understanding natural language, enabling them to comprehend user preferences, item descriptions, and contextual information to generate more accurate and relevant recommendations, leading to improved user satisfaction and engagement. This tutorial introduces Foundation Models such as LLMs for recommendation. We will introduce how recommender system advanced from shallow models to deep models and to large models, how LLMs enable generative recommendation in contrast to traditional discriminative recommendation, and how to build LLM-based recommender systems. We will cover multiple perspectives of LLM-based recommendation, including data preparation, model design, model pre-training, fine-tuning and prompting, multi-modality and multi-task learning, as well as trustworthy perspectives of LLM-based recommender systems such as fairness and transparency.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://llmrecsys.github.io/'
url_dataset: 'https://www.yongfeng.me/attach/hua-recsys2023.pdf'
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
  - LLM4RS

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
Foundation Models such as Large Language Models (LLMs) have significantly advanced many research areas. In particular, LLMs offer significant advantages for recommender systems, making them valuable tools for personalized recommendations. For example, by formulating various recommendation tasks such as rating prediction, sequential recommendation, straightforward recommendation, and explanation generation into language instructions, LLMs make it possible to build universal recommendation engines that can handle different recommendation tasks. Additionally, LLMs have a remarkable capacity for understanding natural language, enabling them to comprehend user preferences, item descriptions, and contextual information to generate more accurate and relevant recommendations, leading to improved user satisfaction and engagement. This tutorial introduces Foundation Models such as LLMs for recommendation. We will introduce how recommender system advanced from shallow models to deep models and to large models, how LLMs enable generative recommendation in contrast to traditional discriminative recommendation, and how to build LLM-based recommender systems. We will cover multiple perspectives of LLM-based recommendation, including data preparation, model design, model pre-training, fine-tuning and prompting, multi-modality and multi-task learning, as well as trustworthy perspectives of LLM-based recommender systems such as fairness and transparency.