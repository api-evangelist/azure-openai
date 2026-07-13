---
title: "Cross-Region Model Connectivity Options in Microsoft Foundry: Supported Patterns and Tradeoffs"
url: "https://techcommunity.microsoft.com/t5/microsoft-foundry-blog/cross-region-model-connectivity-options-in-microsoft-foundry/ba-p/4528620"
date: "2026-06-19"
author: "rayankhoury"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=azure-ai-foundry-blog"
---
Model availability in Microsoft Foundry is region-dependent. The region approved for your project may not be the one where the model or Foundry Agent Service support you need is available. That creates a common cross-region design choice: connect directly to another Foundry resource, or add a gateway layer for more control and governance.
