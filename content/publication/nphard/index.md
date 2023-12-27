---
title: 'NPHardEval: Dynamic Benchmark on Reasoning Ability of Large Language Models via Complexity Classes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lizhou Fan
  - admin
  - Lingyao Li
  - Haoyang Ling
  - Yongfeng Zhang
  - Libby Hemphill

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-22'
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
summary: Complex reasoning ability is one of the most important features of current LLMs, which has also been leveraged to play an integral role in complex decision-making tasks. Therefore, the investigation into the reasoning capabilities of Large Language Models (LLMs) is critical -- numerous benchmarks have been established to assess the reasoning abilities of LLMs. However, current benchmarks are inadequate in offering a rigorous evaluation of the full extent of reasoning abilities that LLMs are capable of achieving. They are also prone to the risk of overfitting, as these benchmarks, being publicly accessible and static, allow models to potentially tailor their responses to specific benchmark metrics, thereby inflating their performance. Addressing these limitations, our research introduces a new benchmark, named NPHardEval. This benchmark is designed to evaluate the reasoning abilities of LLMs across a broad spectrum of 900 algorithmic questions, extending up to the NP-Hard complexity class. These questions are meticulously chosen to represent a wide range of complexity class below the NP-hard complexity class, offering a rigorous measure of the reasoning ability of LLMs. Through this study, we shed light on the current state of reasoning in LLMs, providing an objective and rigorous perspective through the comparison of LLMs' performance across complex classes. Moreover, this benchmark is designed with a dynamic update mechanism, where the datapoints are refreshed on a monthly basis. Such regular updates play a crucial role in mitigating the risk of LLMs overfitting to the benchmark, promoting a more accurate and reliable assessment of their reasoning capabilities. The benchmark dataset and code of NPHardEval are available at [this https URL](https://github.com/casmlab/NPHardEval).
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/casmlab/NPHardEval'
url_pdf: 'https://arxiv.org/pdf/2312.14890.pdf'
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
Complex reasoning ability is one of the most important features of current LLMs, which has also been leveraged to play an integral role in complex decision-making tasks. Therefore, the investigation into the reasoning capabilities of Large Language Models (LLMs) is critical -- numerous benchmarks have been established to assess the reasoning abilities of LLMs. However, current benchmarks are inadequate in offering a rigorous evaluation of the full extent of reasoning abilities that LLMs are capable of achieving. They are also prone to the risk of overfitting, as these benchmarks, being publicly accessible and static, allow models to potentially tailor their responses to specific benchmark metrics, thereby inflating their performance. Addressing these limitations, our research introduces a new benchmark, named NPHardEval. This benchmark is designed to evaluate the reasoning abilities of LLMs across a broad spectrum of 900 algorithmic questions, extending up to the NP-Hard complexity class. These questions are meticulously chosen to represent a wide range of complexity class below the NP-hard complexity class, offering a rigorous measure of the reasoning ability of LLMs. Through this study, we shed light on the current state of reasoning in LLMs, providing an objective and rigorous perspective through the comparison of LLMs' performance across complex classes. Moreover, this benchmark is designed with a dynamic update mechanism, where the datapoints are refreshed on a monthly basis. Such regular updates play a crucial role in mitigating the risk of LLMs overfitting to the benchmark, promoting a more accurate and reliable assessment of their reasoning capabilities. The benchmark dataset and code of NPHardEval are available at [this https URL](https://github.com/casmlab/NPHardEval).
