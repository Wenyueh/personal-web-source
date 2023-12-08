---
title: 'A Predicate-Function-Argument Annotation of Natural Language for Open-Domain Information eXpression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mingming Sun
  - admin
  - Zoey Liu
  - Xin Wang
  - Kangjie Zheng
  - Ping Li

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-06-20'
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
summary: Existing OIE (Open Information Extraction) algorithms are independent of each other such that there exist lots of redundant works; the featured strategies are not reusable and not adaptive to new tasks. This paper proposes a new pipeline to build OIE systems, where an Open-domain Information eXpression (OIX) task is proposed to provide a platform for all OIE strategies. The OIX is an OIE friendly expression of a sentence without information loss. The generation procedure of OIX contains shared works of OIE algorithms so that OIE strategies can be developed on the platform of OIX as inference operations focusing on more critical problems. Based on the same platform of OIX, the OIE strategies are reusable, and people can select a set of strategies to assemble their algorithm for a specific task so that the adaptability may be significantly increased. This paper focuses on the task of OIX and propose a solution–Open Information Annotation (OIA). OIA is a predicate-function-argument annotation for sentences. We label a data set of sentence-OIA pairs and propose a dependency-based rule system to generate OIA annotations from sentences. The evaluation results reveal that learning the OIA from a sentence is a challenge owing to the complexity of natural language sentences, and it is worthy of attracting more attention from the research community.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: https://sunbelbd.github.io/Open-Information-eXpression/
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
Existing OIE (Open Information Extraction) algorithms are independent of each other such that there exist lots of redundant works; the featured strategies are not reusable and not adaptive to new tasks. This paper proposes a new pipeline to build OIE systems, where an Open-domain Information eXpression (OIX) task is proposed to provide a platform for all OIE strategies. The OIX is an OIE friendly expression of a sentence without information loss. The generation procedure of OIX contains shared works of OIE algorithms so that OIE strategies can be developed on the platform of OIX as inference operations focusing on more critical problems. Based on the same platform of OIX, the OIE strategies are reusable, and people can select a set of strategies to assemble their algorithm for a specific task so that the adaptability may be significantly increased. This paper focuses on the task of OIX and propose a solution–Open Information Annotation (OIA). OIA is a predicate-function-argument annotation for sentences. We label a data set of sentence-OIA pairs and propose a dependency-based rule system to generate OIA annotations from sentences. The evaluation results reveal that learning the OIA from a sentence is a challenge owing to the complexity of natural language sentences, and it is worthy of attracting more attention from the research community.