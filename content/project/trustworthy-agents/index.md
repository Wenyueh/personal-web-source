---
title: 'Trustworthy Agents: Safety, Risk, and Privacy'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

date: '2026-04-03'
doi: ''

# Summary. An optional shortened abstract.
summary: 'An agent that acts in the world can cause material harm, leak what its principal told it, or simply fail. I work on the mechanisms that make deployment defensible: safety constraints during planning, privacy-preserving communication, and risk standards that pay out when an agent gets it wrong.'
tags: []
weight: 2

# Display this page in the Featured widget?
featured: true

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Overview
Agent trustworthiness is not a single property. Safety can be built into the planning loop itself, through an agent constitution that injects safety knowledge before a plan is generated, constrains generation while it happens, and inspects the result afterwards. Privacy is a separate axis: cloud models see everything a user sends them, so prompts can be obfuscated generatively and still complete the task. Beyond the model, there is the question of what a user is owed when an agent fails. Treating that as a settlement problem rather than a purely technical one turns trust from an implicit expectation about model behavior into an explicit and enforceable guarantee.
