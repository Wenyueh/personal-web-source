---
title: 'Generative Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

date: '2023-05-11'
doi: ''

# Summary. An optional shortened abstract.
summary: 'Recommendation foundation models turn recommendation into a language task, generating the item to recommend instead of scoring every candidate. I work on what has to be true for that to function, starting with how items are named.'
tags: []
weight: 5

# Display this page in the Featured widget?
featured: true

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Overview
Collapsing a multi-stage retrieval and ranking pipeline into single-stage generation is appealing, but it creates a problem that does not exist in traditional recommenders: the model has to produce an identifier that refers to exactly one real item. How those identifiers are constructed turns out to drive performance substantially, and indexing schemes that carry sequential, collaborative, or semantic structure behave very differently from arbitrary ones. This line also covers fairness in recommendation foundation models and open benchmarks for comparing them, and it connects recent language modeling back to long-standing information retrieval principles about what an index is for.
