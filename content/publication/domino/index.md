---
title: 'Discover, Explanation, Improvement: Automatic Slice Detection Framework for Natural Language Processing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lifeng Jin
  - Lingfeng Song
  - Haitao Mi
  - Yongfeng Zhang
  - Dong Yu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-12-31'
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
summary: Current natural language processing (NLP) models such as BERT and RoBERTa have achieved high overall performance, but they often make systematic errors due to bias or certain difficult features to learn. Thus research on slice detection models (SDM) which automatically identifies underperforming groups of datapoints has gradually caught more attention, which aims at both understanding model behaviors and providing insights for future model training and designing. However, there is little systematic research on SDM and quantitative evaluation of its assessment for NLP models. Our paper fills this gap by proposing "Discover, Explanation, Improvement" framework that discovers coherent and underperforming groups of datapoints and unites datapoints of each slice under human-understandable concepts; it also provides comprehensive evaluation tasks and the corresponding quantitative metrics, which enable convenient comparison for future works. Results show that our framework can accurately select error-prone datapoints with informative semantic features that summarize error patterns, based on which it directly boosts model performance by an average of 2.85 points based on trained models without tuning any parameters across multiple datasets.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/Wenyueh/DEIM'
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
Current natural language processing (NLP) models such as BERT and RoBERTa have achieved high overall performance, but they often make systematic errors due to bias or certain difficult features to learn. Thus research on slice detection models (SDM) which automatically identifies underperforming groups of datapoints has gradually caught more attention, which aims at both understanding model behaviors and providing insights for future model training and designing. However, there is little systematic research on SDM and quantitative evaluation of its assessment for NLP models. Our paper fills this gap by proposing "Discover, Explanation, Improvement" framework that discovers coherent and underperforming groups of datapoints and unites datapoints of each slice under human-understandable concepts; it also provides comprehensive evaluation tasks and the corresponding quantitative metrics, which enable convenient comparison for future works. Results show that our framework can accurately select error-prone datapoints with informative semantic features that summarize error patterns, based on which it directly boosts model performance by an average of 2.85 points based on trained models without tuning any parameters across multiple datasets.