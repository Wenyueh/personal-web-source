---
title: 'Efficient Agent Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

date: '2026-04-07'
doi: ''

# Summary. An optional shortened abstract.
summary: 'Agent pipelines are slow and expensive because they generate long chains of intermediate thoughts through large models. I work on making them cheaper and faster without giving up the quality of the final output, and on giving developers and users control over that tradeoff.'
tags: []
weight: 3

# Display this page in the Featured widget?
featured: true

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Overview
Efficiency for agents is not the same problem as efficiency for a single model call. The structure of the agent, not just the size of the model, drives the cost. Speculative execution lets a small model run ahead while a large one verifies, which cuts planning latency, and co-designing it with an interface that treats human interruption as a normal event rather than an exception makes the speedup usable. Making the speculation policy adaptive turns the latency and dollar cost tradeoff into a single parameter a practitioner can set. A related question sits above the model call entirely: given a pipeline with several stages, which model should serve each one. The gap between the best and worst assignment is large enough to dominate other optimizations, and search methods find near-optimal assignments at a fraction of the evaluation budget.
