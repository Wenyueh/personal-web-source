---
title: 'Propagation and Pitfalls: Reasoning-based Assessment of Knowledge Editing through Counterfactual Tasks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jiang Guo
  - Mingwen Dong
  - Henghui Zhu
  - Patrick Ng
  - Zhiguo Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-31'
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
summary: Current approaches of knowledge editing struggle to effectively propagate updates to interconnected facts. In this work, we delve into the barriers that hinder the appropriate propagation of updated knowledge within these models for accurate reasoning. To support our analysis, we introduce a novel reasoning-based benchmark -- ReCoE (Reasoning-based Counterfactual Editing dataset) -- which covers six common reasoning schemes in real world. We conduct a thorough analysis of existing knowledge editing techniques, including input augmentation, finetuning, and locate-and-edit. We found that all model editing methods show notably low performance on this dataset, especially in certain reasoning schemes. Our analysis over the chain-of-thought generation of edited models further uncover key reasons behind the inadequacy of existing knowledge editing methods from a reasoning standpoint, involving aspects on fact-wise editing, fact recall ability, and coherence in generation. We will make our benchmark publicly available.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2401.17585'
#url_code: https://sunbelbd.github.io/Open-Information-eXpression/
#url_dataset: 'https://aclanthology.org/2020.emnlp-main.167.pdf'
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
  - LLM & NLP

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
Existing OIE (Open Information Extraction) algorithms are independent of each other such that there exist lots of redundant works; the featured strategies are not reusable and not adaptive to new tasks. This paper proposes a new pipeline to build OIE systems, where an Open-domain Information eXpression (OIX) task is proposed to provide a platform for all OIE strategies. The OIX is an OIE friendly expression of a sentence without information loss. The generation procedure of OIX contains shared works of OIE algorithms so that OIE strategies can be developed on the platform of OIX as inference operations focusing on more critical problems. Based on the same platform of OIX, the OIE strategies are reusable, and people can select a set of strategies to assemble their algorithm for a specific task so that the adaptability may be significantly increased. This paper focuses on the task of OIX and propose a solution–Open Information Annotation (OIA). OIA is a predicate-function-argument annotation for sentences. We label a data set of sentence-OIA pairs and propose a dependency-based rule system to generate OIA annotations from sentences. The evaluation results reveal that learning the OIA from a sentence is a challenge owing to the complexity of natural language sentences, and it is worthy of attracting more attention from the research community.