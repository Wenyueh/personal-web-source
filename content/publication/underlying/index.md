---
title: 'Learning Underlying Representations and Input-Strictly-Local Functions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Adam Jardine
  - Huteng Dai

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-11-20'
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
summary: The simultaneous inference of underlying representations (URs) and a phonological grammar from alternating surface representations (SRs) in a morphological paradigm is a core problem in phonological learning that only recently has seen progress (Tesar, 2014; Cotterell et al., 2015; Rasin et al., 2018). This paper proposes a learning algorithm that infers URs and phonological processes from SRs based on the hypothesis that phonological generalizations belong to restrictive subregular regions in the Chomsky Hierarchy (Heinz, 2018). We give a procedure that, given sequences of morphemes paired with SRs, learns URs and a phonological grammar that is an input strictly local (ISL; Chandlee, 2014; Chandlee & Heinz, 2018) function. ISL functions are exactly those which make changes in the output with respect to the local information in the input. For now, the procedure is restricted to simplex ISL processes; that is, those exhibiting a single change. However, this illustrates that restrictive computational principles, combined with major principles in phonological analysis, allow for significant progress in understanding how phonological grammars and URs are learned. The paper is organized as follows. Section 2 briefly introduces the paradigm of the learning algorithm. Section 3 discusses the computational structure encoded in the learner. Section 4 is a detailed explanation of the algorithm with a simple example as illustration. Section 5 compares this algorithm with other algorithms and presents its advantages. The last section concludes the paper.
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
  - linguistics

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
The simultaneous inference of underlying representations (URs) and a phonological grammar from alternating surface representations (SRs) in a morphological paradigm is a core problem in phonological learning that only recently has seen progress (Tesar, 2014; Cotterell et al., 2015; Rasin et al., 2018). This paper proposes a learning algorithm that infers URs and phonological processes from SRs based on the hypothesis that phonological generalizations belong to restrictive subregular regions in the Chomsky Hierarchy (Heinz, 2018). We give a procedure that, given sequences of morphemes paired with SRs, learns URs and a phonological grammar that is an input strictly local (ISL; Chandlee, 2014; Chandlee & Heinz, 2018) function. ISL functions are exactly those which make changes in the output with respect to the local information in the input. For now, the procedure is restricted to simplex ISL processes; that is, those exhibiting a single change. However, this illustrates that restrictive computational principles, combined with major principles in phonological analysis, allow for significant progress in understanding how phonological grammars and URs are learned.
The paper is organized as follows. Section 2 briefly introduces the paradigm of the learning algorithm. Section 3 discusses the computational structure encoded in the learner. Section 4 is a detailed explanation of the algorithm with a simple example as illustration. Section 5 compares this algorithm with other algorithms and presents its advantages. The last section concludes the paper.