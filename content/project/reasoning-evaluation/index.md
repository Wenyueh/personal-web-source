---
title: 'Reasoning and Evaluation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

date: '2025-05-04'
doi: ''

# Summary. An optional shortened abstract.
summary: 'Benchmarks decide what progress looks like, so they should be hard to overfit and should measure something with structure. I build reasoning benchmarks organized by computational complexity, and study where LLM reasoning is genuine and where it reflects patterns already seen in pretraining.'
tags: []
weight: 4

# Display this page in the Featured widget?
featured: true

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Overview
Most reasoning benchmarks emphasize deduction, where the rules are given and the task is to apply them. Organizing tasks by complexity class instead gives a principled difficulty axis and a way to say precisely what a model can and cannot do, and refreshing the instances regularly keeps the benchmark from being absorbed into the next round of training data. Induction, where the rule itself has to be inferred from observations, is the more demanding direction and the one closer to scientific discovery, and current models struggle with even its simplest classes. Alongside benchmark construction, this line covers how context shapes apparent reasoning ability, how reasoning behaves under test-time scaling, and how to find the slices of data where a system quietly fails.
