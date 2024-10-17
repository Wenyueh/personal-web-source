---
title: "Agentless: Demystifying LLM-based Software Engineering Agent"
summary: 这篇文章讨论了一个问题，代码任务比如说SWE-bench这样的benchmark真的需要agent来做planning吗？
author: admin
tags:
  - research
date: '2024-07-04'
reading_time: true
# Optional external URL for project (replaces project detail page).
external_link: ''
share: false
image:
   focal_point:
   preview_only: true

# links:
#   - icon: paperclip
#     icon_pack: fab
#     name: 
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

这篇文章讨论了一个问题，代码任务比如说SWE-bench这样的benchmark真的需要agent来做planning吗？
	
[向右R] 背景
用agent解决代码问题是今年蛮火的一个话题
让agent做规划，使用外部工具，自动帮我们完成代码任务比如说debug
著名(或者说臭名昭著?)的Devin就是这样一个程序员agent
	
[向右R] 文章观点与做法
这篇文章与其说是一个技术文章不如说是一个position文章，它抛出问题之后设计了一套还蛮简单的方法解决SWE问题：
	
[一R] 先localize有问题的代码：把代码整理成树结构，然后让llm指出哪些文件哪些方程导致了bug
[二R] 然后让LLM提出一些可能的解决方案
[三R] 之后再过滤一遍llm提出的方案，比如说去掉有语法错误的方案，确定最终解决方法
	
总之，方法很简单 效果也还不错
	
[向右R] 问题
[一R] 这篇文章用一套manually designed或者说expert designed的workflow代替了agent的自主规划过程，但这是agentless？还是说这依然是agent只不过不是llm-based agent，而是llm+human-based agent？
	
Andrew Ng一直宣传的workflow大体就是这样吧[笑哭R]用人类的expertise去辅助llm的规划，只不过说这里的“辅助”已经多到全部“代替”
	
[二R] 一个更广泛的问题则是：我们什么时候、什么场景下真的需要agent？agent的规划多大程度需要人类expertise的辅助？归根结底还是一个使用场景问题
	
[三R] 这篇文章说自己是agentless，突出自己完全用manually designed workflow，不用llm planning然后获得一个超强agent，我感觉是一种倒退[doge]人类世界的任务五花八门，每一个都设计一个这种fully-manually-designed的expert workflow？还是说 as lecun said，auto-regressive LLM就完全不能也不该做planning？