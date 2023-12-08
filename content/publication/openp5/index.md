---
title: 'OpenP5: Benchmarking Foundation Models for Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shuyuan Xu
  - admin
  - Yongfeng Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-06-19'
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
summary: This paper presents OpenP5, an open-source library for benchmarking foundation models for recommendation under the Pre-train, Personalized Prompt and Predict Paradigm (P5). We consider the implementation of P5 on three dimensions -- 1) downstream task, 2) recommendation dataset, and 3) item indexing method. For 1), we provide implementation over two downstream tasks -- sequential recommendation and straightforward recommendation. For 2), we surveyed frequently used datasets in recommender system research in recent years and provide implementation on ten datasets. In particular, we provide both single-dataset implementation and the corresponding checkpoints (P5) and another Super P5 (SP5) implementation that is pre-trained on all of the datasets, which supports recommendation across various domains with one model. For 3), we provide implementation of three item indexing methods to create item IDs -- random indexing, sequential indexing, and collaborative indexing. We also provide comprehensive evaluation results of the library over the two downstream tasks, the ten datasets, and the three item indexing methods to facilitate reproducibility and future research. We open-source the code and the pre-trained checkpoints of the OpenP5 library at [this url](https://github.com/agiresearch/OpenP5).
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/agiresearch/OpenP5'
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
This paper presents OpenP5, an open-source library for benchmarking foundation models for recommendation under the Pre-train, Personalized Prompt and Predict Paradigm (P5). We consider the implementation of P5 on three dimensions -- 1) downstream task, 2) recommendation dataset, and 3) item indexing method. For 1), we provide implementation over two downstream tasks -- sequential recommendation and straightforward recommendation. For 2), we surveyed frequently used datasets in recommender system research in recent years and provide implementation on ten datasets. In particular, we provide both single-dataset implementation and the corresponding checkpoints (P5) and another Super P5 (SP5) implementation that is pre-trained on all of the datasets, which supports recommendation across various domains with one model. For 3), we provide implementation of three item indexing methods to create item IDs -- random indexing, sequential indexing, and collaborative indexing. We also provide comprehensive evaluation results of the library over the two downstream tasks, the ten datasets, and the three item indexing methods to facilitate reproducibility and future research. We open-source the code and the pre-trained checkpoints of the OpenP5 library at [this url](https://github.com/agiresearch/OpenP5).