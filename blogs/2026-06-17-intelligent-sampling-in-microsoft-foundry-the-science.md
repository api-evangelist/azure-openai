---
title: "Intelligent sampling in Microsoft Foundry: the science behind selecting better production traces"
url: "https://techcommunity.microsoft.com/t5/microsoft-foundry-blog/intelligent-sampling-in-microsoft-foundry-the-science-behind/ba-p/4523722"
date: "2026-06-17"
author: "imatiach"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=azure-ai-foundry-blog"
---
Authors: Ilya Matiach, Morteza Ziyadi, José Santos, Ali Mahmoudzadeh, Shuo Qiu, Salma Elshafey, April Kwong, Vivek Bhadauria TL;DR Microsoft Foundry's intelligent sampling feature (used when creating an evaluation or fine-tuning dataset from production agent traces) uses a MinHash farthest-first diversity sampler. On WildChat (the primary validation dataset, sampling 100 items from a 5,000-trace pool), diversity sampling produces +29.1% higher lexical diversity and +44.8% larger vocabularies than a uniform-random baseline; across five additional datasets (Dolly, No Robots, OASST2, ShareGPT-GPT4, UltraChat), vocabulary gains range from +5.7% to +86.3%. An LLM judge prefers diversity-sampled data 78% of the time for evaluation and 71% for training (268 paired judgments).
