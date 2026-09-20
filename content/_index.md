---
# Leave the homepage title empty to use the site title
title:
date: 2025-12-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      background:
        image:
          filename: wallpaper.jpg
          filters:
            brightness: 0.3
        text_color_light: true
  - block: markdown
    id: selected-works
    content:
      title: Selected Works
      subtitle: 'Papers I led as first, co-first, or senior author. Full list on the [Publications page](/en/publication/).'
      text: |-
        #### Strategic and social decision-making (main line)

        **[SocialRL: From Passive Delegates to Strategic Negotiators](/en/publication/socialrl/)** (2026, arXiv 2608.13787). A general RL recipe that trains social reasoning directly. A 4B model matches or exceeds the GPT-5 family in-domain across six negotiation domains. [PDF](https://arxiv.org/pdf/2608.13787)

        **[Game-theoretic LLM: Agent Workflow for Negotiation Games](/en/publication/gametheory/)** (2024, arXiv 2411.05990). Shows where LLMs depart from rational play in complete- and incomplete-information games, and designs game-theoretic workflows that steer them toward equilibrium and better negotiation outcomes. [PDF](https://arxiv.org/pdf/2411.05990)

        **[WarAgent](/en/publication/WarAgent/)** (2023, arXiv 2311.17227). LLM multi-agent simulation of WWI, WWII, and the Warring States period, used to study the triggers and conditions that lead to war. [PDF](https://arxiv.org/pdf/2311.17227.pdf)

        #### Trustworthy agents

        **[TrustAgent](/en/publication/trustagent/)** (2024, Findings of EMNLP). An agent-constitution framework with pre-planning, in-planning, and post-planning safety strategies. [PDF](https://github.com/agiresearch/TrustAgent/blob/main/TrustAgent.pdf)

        **[Quantifying Trust: the Agentic Risk Standard](/en/publication/quantifyingtrust/)** (2026, arXiv 2604.03976). A settlement-layer standard that integrates risk assessment, underwriting, and compensation for AI-mediated transactions. *Spotlighted in Fortune.* [PDF](https://arxiv.org/pdf/2604.03976)

        **[EmojiPrompt](/en/publication/emoji/)** (2025, NAACL). Generative prompt obfuscation so cloud LLMs can complete tasks without seeing raw private content. *Co-first author.* [PDF](https://aclanthology.org/2025.naacl-long.614.pdf)

        #### Efficient agent systems

        **[Interactive Speculative Planning](/en/publication/interactive_sp/)** (2025, ICLR). Speculative execution for agent planning, co-designed with a user interface that treats human interruption as a first-class part of the system rather than an exception. [PDF](https://arxiv.org/pdf/2410.00079)

        **[Dynamic Speculative Agent Planning](/en/publication/dynamicspec/)** (2026, ICLR). An asynchronous online RL framework for lossless acceleration of agent planning, exposing a single parameter that trades latency against dollar cost and cutting total cost by 30%. *Senior author.* [PDF](https://arxiv.org/abs/2509.01920)

        **[AgentOpt](/en/publication/agentopt/)** (2026, technical report, arXiv 2604.06296). Client-side model selection for agent pipelines. The cost gap between the best and worst model combinations reaches 13&ndash;32x, and Arm Elimination cuts evaluation budget by 24&ndash;67% at near-optimal accuracy. *Open-source package.* [PDF](https://arxiv.org/pdf/2604.06296) &middot; [Code](https://github.com/AgentOptimizer/agentopt)

        #### Foundations: generative recommendation and reasoning evaluation

        **[How to Index Item IDs for Recommendation Foundation Models](/en/publication/indexing/)** (2023, SIGIR-AP). Systematic study of item ID construction for LLM-based generative recommendation, with sequential, collaborative, semantic, and hybrid indexing. [PDF](https://arxiv.org/pdf/2305.06569.pdf)

        **[NPHardEval](/en/publication/nphard/)** (2024, ACL). A dynamic reasoning benchmark organized by computational complexity class and refreshed regularly to resist overfitting. *Co-first author.* [PDF](https://arxiv.org/pdf/2312.14890.pdf)
    design:
      columns: '2'
  - block: collection
    content:
      title: News
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: list
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
  - block: markdown
    id: honors
    content:
      title: Honors, Press, and Invited Talks
      subtitle: ''
      text: |-
        **Honors**

        - KAUST AI Rising Star, 2025 ([news](/en/talk/Selected-as-KAUST-AI-Rising-Star-in-2025/))
        - National Science Foundation SBIR research funding ($50,000), 2021
        - Phi Beta Kappa, UCLA College and Departmental Honors, 2018

        **Press**

        - "Quantifying Trust" spotlighted in Fortune, April 2026, with commentary on systemic financial risk from AI agents ([news](/en/talk/Our-paper-on-Quantifying-Trust-is-spotlighted-in-Fortune/))

        **Invited talks**

        - *From Philosophy of Language to AI Agents*: Fermilab (March 2026), MBZUAI and UC Santa Barbara (June 2026) ([news](/en/talk/Very-honored-to-be-able-to-give-an-invited-talk-at-Fermilab-From-Philosophy-of-Language-to-AI-Agent./))
        - *Agentic Risk Standard*: Columbia University (May 2026), Carnegie Mellon University (May 2026), UC Santa Barbara (April 2026)
        - *Magentic Marketplace*: Columbia Agent Workshop (October 2025), RecSys 2025 EARL Workshop (September 2025)

        **Service**

        - Co-organizer, ICLR 2026 Workshop on Memory for LLM-Based Agentic Systems (MemAgents) and the 2nd COLM 2026 Workshop on Lifelong Agents
        - Area Chair, ACL, EMNLP, NAACL, EACL, COLM (2025 to 2026)
    design:
      columns: '2'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Researcher
          company: Microsoft Research, AI Frontiers
          company_url: 'https://www.microsoft.com/en-us/research/lab/microsoft-research-new-york'
          company_logo: microsoft
          location: New York, USA
          date_start: '2025-06-09'
          date_end: ''
        - title: Postdoctoral Researcher in Computer Science
          company: Computer Science Department, University of California, Santa Barbara
          company_url: 'http://nlp.cs.ucsb.edu/'
          company_logo: ucsb
          location: California, USA
          date_start: '2024-10-01'
          date_end: '2025-06-07'
          description: |2-
              * Advisor: Prof. William Yang Wang
        - title: Ph.D. in Computer Science
          company: Computer Science Department, Rutgers University, New Brunswick
          company_url: 'https://cs.rutgers.edu'
          company_logo: Rutgers
          location: New Jersey, USA
          date_start: '2020-09-01'
          date_end: '2024-10-01'
          description: |2-
              * Dissertation: Trustworthy Large Language Model
              * Advisor: Prof. Yongfeng Zhang
        - title: Master of Arts (Ph.D. track transfer out) in Linguistics
          company: Department of Linguistics, Rutgers University
          company_url: 'https://ling.rutgers.edu/'
          company_logo: Rutgers
          location: New Jersey, USA
          date_start: '2018-09-01'
          date_end: '2020-06-30'
          description: |2-
              * Thesis: Learning Underlying Representations and Input-Strictly-Local Functions
              * Advisor: Prof. Adam Jardine
        - title: B.S. in Mathematics, General & B.A. in Linguistics&Philosophy with Specialization in Computing
          company: UCLA
          company_url: 'https://www.ucla.edu/'
          company_logo: UCLA
          location: California, USA
          date_start: '2014-10-01'
          date_end: '2018-06-30'
          description: |2-
              * Thesis: Boolean-Algebraic Representation of Possible Worlds
              * Advisor: Prof. Edward Keenan
    design:
      columns: '2'
---
