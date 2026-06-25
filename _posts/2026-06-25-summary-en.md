---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 38 items, 22 important content pieces were selected

---

1. [OpenAI unveils first custom AI chip Jalapeno with Broadcom](#item-1) ⭐️ 9.0/10
2. [DeepSWE Benchmark Evaluates Frontier Coding Agents with Contamination-Free Tasks](#item-2) ⭐️ 9.0/10
3. [Anthropic Accuses Alibaba of Illicit Claude Model Extraction](#item-3) ⭐️ 8.0/10
4. [Qualcomm Acquires Modular, Makers of Mojo and MAX](#item-4) ⭐️ 8.0/10
5. [NVIDIA's 45°C Liquid Cooling Slashes Data Center Water Use](#item-5) ⭐️ 8.0/10
6. [AI-Generated Job Apps Make Candidates Invisible](#item-6) ⭐️ 8.0/10
7. [Curated open-source OCR models and benchmarks on Papers with Code](#item-7) ⭐️ 8.0/10
8. [Superhuman Generals.io Agent via Self-Play RL](#item-8) ⭐️ 8.0/10
9. [LLM Inference Pricing Compilation Reveals Surprising Caching Cost Differences](#item-9) ⭐️ 8.0/10
10. [LuaJIT 3.0 proposes C-like syntax extensions](#item-10) ⭐️ 7.0/10
11. [PR Spam Today: Echoes of Early 2000s Email Spam](#item-11) ⭐️ 7.0/10
12. [Google Introduces Computer Use in Gemini 3.5 Flash](#item-12) ⭐️ 7.0/10
13. [$500M Intercept Fund aims to end respiratory infections](#item-13) ⭐️ 7.0/10
14. [Datasette 1.0a35 adds table creation and alteration APIs](#item-14) ⭐️ 7.0/10
15. [Testing OPFS with Pyodide for Persistent SQLite in Browser](#item-15) ⭐️ 7.0/10
16. [MuJoFil: GPU-Accelerated Simulator for Vision RL](#item-16) ⭐️ 7.0/10
17. [HDD-RoPE: A Dynamic Rotary Positional Embedding](#item-17) ⭐️ 7.0/10
18. [uv 0.11.24 Adds CPython 3.15.0b3 and Relocatable Environments Preview](#item-18) ⭐️ 6.0/10
19. [Why stating the obvious is key to good blogging](#item-19) ⭐️ 6.0/10
20. [RubyLLM: Unified Ruby Framework for AI Providers](#item-20) ⭐️ 6.0/10
21. [Simon Willison Converts MDN Browser Data to SQLite](#item-21) ⭐️ 6.0/10
22. [Model security risks in production: are they tested?](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI unveils first custom AI chip Jalapeno with Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI, in partnership with Broadcom, unveiled its first custom AI inference chip named Jalapeno, built by TSMC and designed from scratch in nine months. The chip claims to reduce inference cost by approximately 50% compared to current Nvidia GPUs. This marks a major strategic shift for OpenAI as it reduces reliance on external GPU suppliers like Nvidia, potentially lowering operational costs and setting a precedent for AI companies designing their own silicon. The move could accelerate the trend toward specialized AI hardware, impacting the entire AI hardware ecosystem. Jalapeno is a purpose-built inference ASIC, not a repurposed training accelerator, and is optimized specifically for large language models. It was developed from design to production in a record nine months, leveraging OpenAI's own AI models to accelerate parts of the design process.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: Large language model inference is computationally intensive, typically running on powerful GPUs from Nvidia. However, as AI scales, companies seek more efficient custom chips (ASICs) that can outperform general-purpose GPUs for specific tasks, similar to how Google developed its TPU. Building such chips involves complex design and manufacturing, often with partners like Broadcom and TSMC.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/broadcom-and-openai-unveil-custom-built-jalapeno-inference-processor-openais-first-chip-is-a-massive-reticle-sized-asic-built-in-an-ultra-fast-nine-month-development-cycle">Broadcom and OpenAI unveil custom-built Jalapeño inference processor ...</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: some are skeptical about OpenAI's claim of using its own models to accelerate chip design, calling it 'meaningless marketing', while others confirm TSMC as the manufacturer and discuss the broader trend of custom AI chips. Some commenters share excitement about the potential efficiency gains and compare Jalapeno to other specialized chips like Google TPU and Taalas.

**Tags**: `#OpenAI`, `#AI hardware`, `#custom chip`, `#inference`, `#Broadcom`, `#TSMC`

---

<a id="item-2"></a>
## [DeepSWE Benchmark Evaluates Frontier Coding Agents with Contamination-Free Tasks](https://www.reddit.com/r/MachineLearning/comments/1ue0hlp/deepswe_new_benchmark_looking_at_how_well_todays/) ⭐️ 9.0/10

DeepSWE is a new open-source benchmark for evaluating coding agents, featuring contamination-free tasks written from scratch, diverse repositories across 5 languages, real-world complexity requiring 5.5x more code than SWE-bench Pro, and hand-written verifiers for reliable software behavior testing. This benchmark addresses key limitations in existing coding agent evaluations—contamination, diversity, complexity, and verification—making it a more reliable measure of actual software engineering capabilities. It will help researchers and developers better assess and improve frontier AI coding agents. DeepSWE tasks have prompts about half the length of SWE-bench Pro's, yet solutions require 5.5x more code and about 2x more output tokens. Tasks are contamination-free because they are written from scratch rather than adapted from existing commits or PRs.

reddit · r/MachineLearning · /u/we_are_mammals · Jun 24, 02:03

**Background**: Benchmark contamination occurs when models are trained on test data, inflating performance. SWE-bench is a popular benchmark that evaluates LLMs on real-world GitHub issues, but it may suffer from contamination. DeepSWE aims to provide a contamination-free alternative with higher task diversity and complexity. Coding agents are AI systems that autonomously write or modify code, often using large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2406.19314">[2406.19314] LiveBench: A Challenging, Contamination-Limited LLM Benchmark</a></li>
<li><a href="https://www.swebench.com/">SWE-bench</a></li>

</ul>
</details>

**Tags**: `#benchmark`, `#coding agents`, `#machine learning`, `#software engineering`, `#AI evaluation`

---

<a id="item-3"></a>
## [Anthropic Accuses Alibaba of Illicit Claude Model Extraction](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic has accused Alibaba of conducting a large-scale model distillation campaign, using nearly 25,000 fraudulent accounts to generate over 28.8 million exchanges with Claude between April 22 and June 5, 2026, to illicitly extract its AI model capabilities. This accusation highlights the growing tension over intellectual property in the AI industry and the use of distillation as a means to replicate proprietary model capabilities, potentially undermining the business models of AI companies like Anthropic. Alibaba is accused of using the extracted outputs to train its own competing models, and the campaign involved resellers offering Claude API tokens at 70-90% below official prices, often through payment fraud and pooled accounts.

hackernews · htrp · Jun 24, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48664814)

**Background**: Model distillation is a technique where a smaller 'student' model learns to replicate the behavior of a larger 'teacher' model by training on its outputs. This is commonly used to create efficient models, but when done without authorization against a proprietary model accessed via API, it may violate terms of service and intellectual property rights. The practice has become a point of contention in the AI industry.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://labelbox.com/guides/model-distillation/">What is Model Distillation?</a></li>
<li><a href="https://nebius.com/blog/posts/model-distillation-intro">Introduction to model distillation: Efficient knowledge transfer for AI applications</a></li>

</ul>
</details>

**Discussion**: Commenters noted two types of distillation: black-box reinforcement and more targeted fine-tuning using another model's outputs (RLAIF). Some questioned what makes the accounts fraudulent if payment was made, while others compared the situation to historical tech copying, such as Steve Jobs on the Mac GUI. The discussion also revealed that Chinese resellers subsidize access by selling reasoning traces as training data.

**Tags**: `#AI`, `#model theft`, `#distillation`, `#Anthropic`, `#Alibaba`

---

<a id="item-4"></a>
## [Qualcomm Acquires Modular, Makers of Mojo and MAX](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

Qualcomm announced its acquisition of Modular, the startup behind the Mojo programming language and the MAX compiler stack, on June 24, 2026. The deal is valued at approximately $4 billion. This acquisition strengthens Qualcomm's AI capabilities by giving it a cutting-edge compiler stack that can target multiple hardware backends, potentially challenging NVIDIA's CUDA dominance. It also raises questions about the future openness of Mojo, which was promised to be open-sourced in fall 2026. Modular's Mojo language builds on MLIR (Multi-Level Intermediate Representation), enabling high-performance compilation for CPUs, GPUs, TPUs, and ASICs. The MAX compiler stack provides an alternative to NVIDIA's CUDA, and the deal was first reported by Reuters a few days before the official announcement.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: Mojo is a programming language designed to combine Python's ease of use with the performance of system languages like C++ and Rust. It leverages the MLIR compiler framework, allowing code to run on diverse hardware including GPUs and custom accelerators. Modular was founded by Chris Lattner, the original architect of LLVM and Swift, and Tim Davis. The company had promised to open-source Mojo in fall 2026, but the acquisition may alter those plans.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed, with some expressing disappointment that Mojo may not become the cross-platform language they hoped for, while others see strategic value for Qualcomm in competing with NVIDIA. Commenters also noted the coincidence of a Chinese supercomputer using ARM v9 chips without GPUs topping the Top500 list the day before the announcement.

**Tags**: `#Qualcomm`, `#Modular`, `#Mojo`, `#AI compiler`, `#acquisition`

---

<a id="item-5"></a>
## [NVIDIA's 45°C Liquid Cooling Slashes Data Center Water Use](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 8.0/10

NVIDIA has introduced a 45°C liquid cooling architecture for AI data centers that reduces water consumption to near zero and cuts operational costs by over $4 million annually. This innovation addresses the massive water footprint of AI data centers, enabling more sustainable scaling of AI infrastructure and opening the door to waste heat reuse for district heating. The architecture uses direct-to-chip liquid cooling with coolant temperatures up to 45°C (113°F), which is 10-15°C higher than typical liquid-cooled systems, allowing for near-complete elimination of evaporative water cooling.

hackernews · nitin_flanker · Jun 24, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48660178)

**Background**: Traditional data centers rely on air conditioning or liquid cooling at lower temperatures (30-35°C) to keep chips cool, consuming vast amounts of water for evaporation. Higher coolant temperatures reduce or eliminate the need for water-based cooling towers and also produce waste heat hot enough for practical reuse. NVIDIA's 45°C threshold is a significant leap because it balances chip cooling requirements with energy efficiency and water conservation.

<details><summary>References</summary>
<ul>
<li><a href="https://techstory.in/the-45c-breakthrough-nvidias-liquid-cooling-architecture-solves-data-center-water-crisis/">NVIDIA Liquid Cooling Design Cuts Water to Near Zero</a></li>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45 ° C Liquid Cooling Design for AI Data Centers</a></li>
<li><a href="https://www.araner.com/blog/data-center-and-district-heating-an-outstanding-combination">Data center and district heating : an outstanding combination</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the potential for district heating synergy, noting that 45°C is workable for heating loops and could provide millions of dollars in value to communities. Some questioned what exactly is innovative, given existing higher-temperature liquid cooling at NASA. Others asked for clarification on 'favorable climates' and the dependency on outside temperatures.

**Tags**: `#data center cooling`, `#water conservation`, `#NVIDIA`, `#liquid cooling`, `#sustainability`

---

<a id="item-6"></a>
## [AI-Generated Job Apps Make Candidates Invisible](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 8.0/10

Tom MacWright notes that AI-written job applications and portfolios produce generic, impersonal candidates that reveal nothing about the person beyond tool usage. This trend undermines the purpose of hiring by obscuring candidates' authentic qualities, making it harder for employers to evaluate fit and potentially eroding trust in the application process. MacWright observes LLM-cowritten applications linking to LLM-generated portfolios and GitHub projects with purely AI-written commit messages, creating a layer of 'accidental anonymity.'

rss · Simon Willison · Jun 24, 18:13

**Tags**: `#ai`, `#ethics`, `#careers`, `#hiring`, `#authenticity`

---

<a id="item-7"></a>
## [Curated open-source OCR models and benchmarks on Papers with Code](https://www.reddit.com/r/MachineLearning/comments/1ueiam6/find_the_best_opensource_ocr_models_in_one_place/) ⭐️ 8.0/10

A new overview page on Papers with Code lists top open-source OCR models and benchmarks, including Baidu's Unlimited OCR (3B parameters with Reference Sliding Window Attention) and Mistral's OCR 4 API. This curated list simplifies model selection for practitioners building document digitization pipelines, especially for agentic RAG and AI agent use cases that require converting messy PDFs into structured Markdown. The page highlights key benchmarks like OlmOCRBench (by Ai2) and OmniDocBench (by Shanghai AI Lab), and recommends Chandra OCR 2 and Mistral OCR v4 as top performers; Chandra OCR 2 is openly available for self-hosting or serverless API.

reddit · r/MachineLearning · /u/NielsRogge · Jun 24, 16:26

**Background**: Optical Character Recognition (OCR) converts images of text into machine-readable data, a crucial step for digitizing documents. Baidu's Unlimited OCR introduces Reference Sliding Window Attention (R-SWA), an efficient attention mechanism that uses fixed reference tokens and a sliding window to handle long sequences scalably. DeepSeek OCR, mentioned as a base for Baidu's model, is an open-weight OCR tool from the Chinese AI company DeepSeek, known for its cost-effective LLMs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/reference-sliding-window-attention-r-swa">Reference Sliding Window Attention (R-SWA)</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>

</ul>
</details>

**Tags**: `#OCR`, `#open-source`, `#document digitization`, `#AI agents`, `#Papers with Code`

---

<a id="item-8"></a>
## [Superhuman Generals.io Agent via Self-Play RL](https://www.reddit.com/r/MachineLearning/comments/1uei2yg/i_made_a_superhuman_generalsio_agent_with/) ⭐️ 8.0/10

A developer created an open-source superhuman agent for the real-time strategy game Generals.io, trained using self-play reinforcement learning with JAX and a Vision Transformer, and it achieved the #1 rank on the human 1v1 leaderboard. This demonstrates that scaling transformers with self-play can outperform human-crafted heuristics in imperfect-information games, and the open-source release provides a high-quality baseline for further research in game AI and RL. The pipeline was reimplemented from NumPy/Torch to JAX for faster computation, and the architecture was switched from CNN to Vision Transformer to better handle the game's spatial observations. The agent's code, including a fast JAX-based simulator, is available on GitHub.

reddit · r/MachineLearning · /u/shrekofspeed · Jun 24, 16:18

**Background**: Generals.io is a real-time strategy game with imperfect information (fog of war). Self-play reinforcement learning involves an agent learning by playing against itself or past versions of itself, which has been successfully used in games like AlphaGo. JAX is a high-performance numerical computing library, and Vision Transformer (ViT) adapts the transformer architecture for image-like inputs by dividing the image into patches.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision_transformer">Vision transformer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Self-play_(reinforcement_learning_technique)">Self-play (reinforcement learning technique)</a></li>

</ul>
</details>

**Tags**: `#reinforcement learning`, `#self-play`, `#game AI`, `#JAX`, `#Vision Transformer`

---

<a id="item-9"></a>
## [LLM Inference Pricing Compilation Reveals Surprising Caching Cost Differences](https://www.reddit.com/r/MachineLearning/comments/1ueavxn/i_compiled_llm_inference_pricing_across_7/) ⭐️ 8.0/10

A Reddit user compiled and compared LLM inference pricing across seven providers (OpenRouter, DeepSeek, Together AI, Fireworks, Groq, etc.), finding that cached input token costs vary dramatically between providers, with some cache hits being tens of times cheaper than cache misses. This comparison is a valuable resource for developers optimizing LLM inference costs, as caching policies and pricing can significantly impact total spending, especially for applications with reusable context like agents, RAG pipelines, and multi-turn conversations. The spreadsheet currently tracks input/output token pricing, context windows, cached input pricing, and model availability. However, it does not include real throughput, cold-start times, quantization variants, or reliability metrics.

reddit · r/MachineLearning · /u/Technomadlyf · Jun 24, 11:28

**Background**: LLM inference costs are typically calculated per token (input and output). Prompt caching allows providers to reuse previously computed portions of a prompt, leading to lower cost and latency. However, caching policies and pricing vary widely, and some providers do not clearly document them.

<details><summary>References</summary>
<ul>
<li><a href="https://projectdiscovery.io/blog/how-we-cut-llm-cost-with-prompt-caching">How We Cut LLM Costs by 59% With Prompt Caching — ProjectDiscovery Blog</a></li>
<li><a href="https://aws.amazon.com/blogs/database/optimize-llm-response-costs-and-latency-with-effective-caching/">Optimize LLM response costs and latency with effective caching | Amazon Web Services</a></li>
<li><a href="https://www.gmicloud.ai/en/blog/llm-inference-cost-optimization-caching-batching-routing">Cutting LLM Inference Costs in 2026: Where Caching, Batching, and Smart Routing Actually Pay Off | GMI Cloud</a></li>

</ul>
</details>

**Discussion**: The Reddit post has sparked discussion around caching's importance, with users sharing tips on evaluating providers beyond token pricing. Some noted that throughput and cold-start times are also critical, and that caching documentation is often lacking.

**Tags**: `#LLM`, `#pricing`, `#caching`, `#inference`, `#cost optimization`

---

<a id="item-10"></a>
## [LuaJIT 3.0 proposes C-like syntax extensions](https://github.com/LuaJIT/LuaJIT/issues/1475) ⭐️ 7.0/10

LuaJIT 3.0 has proposed adding C-like operators (e.g., &&, ||, !=) and a ternary expression (x ? y : z) to the Lua language, diverging from traditional Lua syntax. These changes could make Lua more accessible to developers from C-like backgrounds, potentially broadening its user base, but risk fragmenting the language's identity and compatibility with existing Lua code. The proposal also includes an alternative ternary syntax using `if x then y else z`, similar to Luau, which has been suggested in community discussions as a more Lua-friendly approach.

hackernews · phreddypharkus · Jun 25, 00:41 · [Discussion](https://news.ycombinator.com/item?id=48667336)

**Background**: LuaJIT is a widely used just-in-time compiler for Lua, known for its performance. Lua traditionally lacks a ternary operator, relying on `and/or` idioms. Luau, a Lua derivative used by Roblox, already supports `if-then-else` expressions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LuaJIT">LuaJIT - Wikipedia</a></li>
<li><a href="https://luajit.org/">The LuaJIT Project</a></li>

</ul>
</details>

**Discussion**: Community comments are divided: some support incremental additions like `if-then-else` expressions, while others oppose C-like syntax as unnecessary and harmful to Lua's identity.

**Tags**: `#LuaJIT`, `#syntax`, `#programming languages`, `#JIT compilation`, `#Lua`

---

<a id="item-11"></a>
## [PR Spam Today: Echoes of Early 2000s Email Spam](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 7.0/10

A blog post draws an analogy between modern pull request (PR) spam on GitHub and email spam from the early 2000s, arguing that open source maintainers need reputation systems and better infrastructure to combat it. This perspective reframes PR spam as an infrastructure problem, suggesting that solutions like reputation metrics and automated filtering could reduce maintainer burnout and improve open source project health. The post is an advertisement for an AI tool called OpenClaw, which uses a multi-model approach to detect spam PRs, but the analogy and proposed solutions have drawn substantial community discussion.

hackernews · dakshgupta · Jun 24, 14:32 · [Discussion](https://news.ycombinator.com/item?id=48660579)

**Background**: Pull request spam occurs when contributors submit low-quality, automated, or irrelevant PRs to open source projects, often as part of hackathons or marketing campaigns, wasting maintainers' time. Early 2000s email spam was combated through SPF, DKIM, and reputation-based filtering, which reduced spam to manageable levels. The blog suggests similar reputation systems could be built for open source contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/shitoberfest/spam-pullrequests">GitHub - shitoberfest/ spam - pullrequests : Show the world how many...</a></li>
<li><a href="https://arxiv.org/pdf/2505.18760">ARMS: A Vision for Actor Reputation Metric Systems in the Open-Source ...</a></li>
<li><a href="https://garvitasood.medium.com/github-clean-up-spam-babc5e5b5ab0">GitHub Clean-up Spam . by Garvita Sood, Anuj Bansal, Garima | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters noted GitHub's recent addition of configurable PR limits, and discussed differences between email spam (server-based reputation) and PR spam (user-based reputation). Some expressed disappointment that the post was an ad for an AI tool, while others found the analogy useful and suggested infrastructure like uBlock-style unsubscribe lists.

**Tags**: `#open source`, `#spam`, `#pull requests`, `#GitHub`, `#maintenance`

---

<a id="item-12"></a>
## [Google Introduces Computer Use in Gemini 3.5 Flash](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 7.0/10

Google has announced the integration of computer use capabilities into the Gemini 3.5 Flash model, enabling the AI to directly interact with desktop environments through clicks, keystrokes, and other actions. However, early community reports highlight significant reliability issues and unfavorable comparisons to competing solutions. This move positions Gemini as a direct competitor in the emerging field of AI agents that can autonomously control computers, a space currently led by Anthropic's Claude and OpenAI's Codex. The community's critical feedback underscores the challenges Google faces in delivering production-ready agentic capabilities. The computer use feature is part of the Gemini 3.5 Flash model, which is optimized for rapid agentic loops and complex coding tasks. Despite Google's claims of frontier-level intelligence, community tests show the model giving up on simple tasks (e.g., table extraction) or executing destructive commands like `git reset --hard` without validation.

hackernews · swolpers · Jun 24, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48662999)

**Background**: Computer use in AI refers to autonomous agents that can perceive and interact with digital interfaces—clicking buttons, typing text, and running commands—much like a human user. Major AI labs like Anthropic and OpenAI have already released such capabilities with more reliable results. Google’s entry into this space with Gemini 3.5 Flash aims to compete on speed and cost, but initial feedback suggests the model lags in reliability and agentic robustness.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/">Gemini 3 . 5 : frontier intelligence with action</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3 . 5 Flash — Google DeepMind</a></li>
<li><a href="https://github.com/trycua/acu">ACU - Awesome Agents for Computer Use - GitHub</a></li>

</ul>
</details>

**Discussion**: Community sentiment is largely critical, with users reporting that Gemini 3.5 Flash often fails at simple agentic tasks, gives up after many iterations, or performs unsafe actions like resetting a Git repository. Comparisons to competitors like Opus 4.8 and GPT 5.5 show Gemini underperforming, and users express disappointment over the lack of a Codex/Claude Code equivalent.

**Tags**: `#AI`, `#Gemini`, `#Google`, `#LLM`, `#computer-use`

---

<a id="item-13"></a>
## [$500M Intercept Fund aims to end respiratory infections](https://blog.interceptfund.com/p/ending-respiratory-infections) ⭐️ 7.0/10

Intercept, a new $500 million philanthropic initiative, has launched with the goal of drastically reducing and eventually eliminating respiratory infections like the common cold and influenza through better air cleaning and prevention technologies. Respiratory infections cause billions of illnesses annually, leading to lost productivity, chronic conditions like long COVID, and deaths in vulnerable populations. This initiative could transform public health by making indoor air safer and developing new preventatives. The fund is backed by prominent philanthropists and focuses on scaling air cleaning technologies and advancing novel preventive treatments. It acknowledges that even mild infections impose a significant collective burden, with healthy people spending about 5% of their lives sick.

hackernews · EthanFantl · Jun 25, 01:14 · [Discussion](https://news.ycombinator.com/item?id=48667588)

**Background**: Respiratory infections, including the common cold, influenza, and COVID-19, are primarily transmitted through airborne particles. Current mitigation relies on vaccines, masks, and hand hygiene, but indoor air cleaning remains underutilized. Intercept aims to fund research and implementation of effective air filtration, UV disinfection, and other technologies to prevent transmission at scale.

<details><summary>References</summary>
<ul>
<li><a href="https://www.interceptfund.com/">Intercept</a></li>
<li><a href="https://time.com/article/2026/06/24/500-million-intercept-fund-eliminate-common-cold/">A New $500 Million Fund Is Trying to Eliminate the Common Cold</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0091743523003602">Effectiveness of filtering or decontaminating air to reduce or prevent ...</a></li>

</ul>
</details>

**Discussion**: Community members shared emotional personal stories, such as a user whose girlfriend died from human metapneumovirus. Some expressed skepticism about relying on philanthropy for a problem they believe should be government-funded, while others questioned the cited illness statistics. Many supporters, particularly those affected by long COVID, expressed excitement and hope for the initiative's potential.

**Tags**: `#health`, `#respiratory-infections`, `#philanthropy`, `#long-covid`, `#air-cleaning`

---

<a id="item-14"></a>
## [Datasette 1.0a35 adds table creation and alteration APIs](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 introduces new web interfaces and JSON APIs for creating and altering SQLite tables, including support for defining columns, primary keys, constraints, and foreign keys. This release significantly enhances Datasette's programmatic write and schema-modification capabilities, moving from a read-only tool to one that enables full CRUD operations on SQLite databases. It empowers users to manage database schemas without direct SQL access. The new features include a 'Create table' interface backed by the /<database>/-/create JSON API and an 'Alter table' interface with /<database>/<table>/-/alter JSON API, supporting column operations, constraints, and table renaming. Additionally, the release stabilizes template context documentation for custom templates until Datasette 2.0.

rss · Simon Willison · Jun 23, 21:34

**Background**: Datasette is an open-source tool for exploring and publishing SQLite databases, providing a web interface and JSON API. Previously, table creation and schema changes required direct SQL commands; this alpha release adds user-friendly interfaces and APIs for those operations. The template context documentation ensures that custom templates relying on specific variables remain compatible with future versions.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/23/datasette/">Release: datasette 1.0a35 - simonwillison.net</a></li>
<li><a href="https://docs.datasette.io/en/stable/json_api.html">JSON API - Datasette documentation</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#release`, `#SQLite`, `#database`, `#API`

---

<a id="item-15"></a>
## [Testing OPFS with Pyodide for Persistent SQLite in Browser](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 7.0/10

Simon Willison created a test harness using the Origin Private File System (OPFS) with Pyodide to explore enabling Datasette Lite to edit persistent SQLite files stored in the browser. This exploration could enable full-fledged Python database applications running entirely in the browser with persistent storage, expanding the capabilities of web-based tools like Datasette Lite. The test harness uses OPFS, which provides high-performance per-origin sandboxed file storage, combined with Pyodide (CPython compiled to WebAssembly) to run Python code in the browser.

rss · Simon Willison · Jun 23, 18:58

**Background**: The Origin Private File System (OPFS) is part of the File System API, offering a sandboxed, persistent file system private to a web origin. Pyodide brings CPython to browsers via WebAssembly, allowing Python packages like SQLite to run client-side. Datasette Lite is a browser-based version of the Datasette data exploration tool.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN - MDN Web Docs</a></li>
<li><a href="https://pyodide.org/">Pyodide</a></li>

</ul>
</details>

**Tags**: `#browsers`, `#pyodide`, `#datasette-lite`, `#OPFS`, `#file system`

---

<a id="item-16"></a>
## [MuJoFil: GPU-Accelerated Simulator for Vision RL](https://www.reddit.com/r/MachineLearning/comments/1uemrch/mujoco_derived_simulator_for_high_fidelity_vision/) ⭐️ 7.0/10

A developer released MuJoFil, an open-source simulator that combines Nvidia's GPU-accelerated Newton Physics Engine with Google's Filament renderer to enable high-fidelity vision-based reinforcement learning training on GPU. MuJoFil addresses the lack of an easily accessible, open-source, GPU-native simulator for vision RL, potentially democratizing robotics research by removing hardware and licensing barriers. MuJoFil uses Newton for physics (based on MuJoCo's engine but GPU-native via NVIDIA Warp) and heavily modified Filament to render multiple simulations in parallel on GPU, supporting PBR textures and standard 3D formats like GLB and OpenUSD.

reddit · r/MachineLearning · /u/MT1699 · Jun 24, 19:07

**Background**: MuJoCo is a popular physics simulator for robotics but is CPU-bound, limiting parallelization. Vision-based reinforcement learning requires rendering, which MuJoCo doesn't accelerate on GPU. MJX does GPU physics but lacks rendering. NVIDIA Isaac is GPU-accelerated but requires powerful GPUs and a license. MuJoFil aims to fill this gap with open-source components.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/newton-physics">Newton Physics Engine | NVIDIA Developer</a></li>
<li><a href="https://github.com/google/filament">google / filament : Filament is a real-time physically based rendering ...</a></li>

</ul>
</details>

**Tags**: `#simulation`, `#reinforcement learning`, `#GPU`, `#MuJoCo`, `#robotics`

---

<a id="item-17"></a>
## [HDD-RoPE: A Dynamic Rotary Positional Embedding](https://www.reddit.com/r/MachineLearning/comments/1uelcm9/high_dimensional_dynamic_rotary_positional/) ⭐️ 7.0/10

Researchers introduced HDD-RoPE, a high-dimensional dynamic rotary positional embedding that uses cumulative matrix products to model multidimensional positional information, and showed it converges faster than xPos on TinyStories. This advances positional encoding by enabling tokens to learn positions not just within a linear sequence but also within higher-level structures like paragraphs or sentences, potentially improving transformer performance on long-context tasks. HDD-RoPE breaks query and key chunks into groups of size 4 (instead of the standard 2), yielding 6 axes of rotation for a 6-dimensional position space, and makes rotation amounts data-dependent based on layer activations.

reddit · r/MachineLearning · /u/mikayahlevi · Jun 24, 18:16

**Background**: Rotary Positional Embeddings (RoPE) encode token positions by rotating pairs of dimensions at fixed rates, enabling attention models to capture relative positions. xPos extends RoPE with extrapolation capabilities. HDD-RoPE generalizes this by using higher-dimensional rotations and dynamic rates.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/jploski/RotaryEmbedding">jploski/RotaryEmbedding: Comparison of RoPE and xPos positional ...</a></li>
<li><a href="https://kaggle.curtischong.me/techniques/xpos-positional-encoding">xpos positional encoding</a></li>

</ul>
</details>

**Tags**: `#positional embedding`, `#transformer`, `#machine learning`, `#attention`, `#RoPE`

---

<a id="item-18"></a>
## [uv 0.11.24 Adds CPython 3.15.0b3 and Relocatable Environments Preview](https://github.com/astral-sh/uv/releases/tag/0.11.24) ⭐️ 6.0/10

uv 0.11.24 adds support for CPython 3.15.0b3 and introduces a preview feature that makes project environments relocatable. The release also includes performance improvements, such as a compact index for lazy version maps, and several bug fixes. The preview of relocatable environments addresses a long-standing community request (issue #3587) by allowing project virtual environments to be moved or copied across filesystem paths. This release also ensures compatibility with the latest CPython 3.15 beta, keeping uv aligned with Python's cutting-edge development. The relocatable environment feature is currently under preview and requires explicit opt-in. The compact index for lazy version maps improves performance by reducing memory overhead. Bug fixes include proper handling of `exclude-newer` disabling, archive ID collision avoidance, and fixes for Fish shell activation scripts.

github · github-actions[bot] · Jun 23, 21:16

**Background**: uv is a fast Python package and project manager written in Rust, developed by Astral Software. A relocatable virtual environment is one whose activation scripts and internal paths do not depend on the absolute installation directory, allowing the environment to be moved to another location or machine. This feature was previously available in the `virtualenv` tool as experimental, and uv's implementation responds to user demand for such capability.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/astral-sh/uv/issues/3587">Add support for -- relocatable · Issue #3587 · astral-sh/ uv · GitHub</a></li>

</ul>
</details>

**Tags**: `#uv`, `#Python`, `#package management`, `#release`, `#performance`

---

<a id="item-19"></a>
## [Why stating the obvious is key to good blogging](https://blog.jim-nielsen.com/2026/blogging-stating-the-obvious/) ⭐️ 6.0/10

A blog post argues that effective blogging often involves stating what seems obvious to the author but not to others, inspired by the 'curse of knowledge' bias. This insight encourages writers to overcome imposter syndrome and share fundamental knowledge, helping new audiences while fostering a richer, more accessible online community. The post references the 'curse of knowledge' and notes that every year brings a new cohort of learners who need to hear the basics. Commenters share personal experiences with audience targeting.

hackernews · Curiositry · Jun 24, 23:46 · [Discussion](https://news.ycombinator.com/item?id=48666927)

**Background**: The curse of knowledge is a cognitive bias where experts assume others have the same understanding they do, making it hard to explain basic concepts. Blogging about obvious topics can bridge this gap for newcomers.

**Discussion**: Commenters largely agree with the post, with some sharing how they've seen similar effects in math and programming. A few note that even comments on Hacker News often state the obvious, yet get upvoted.

**Tags**: `#blogging`, `#knowledge sharing`, `#writing`, `#community`, `#meta`

---

<a id="item-20"></a>
## [RubyLLM: Unified Ruby Framework for AI Providers](https://rubyllm.com/) ⭐️ 6.0/10

RubyLLM is an open-source Ruby gem that provides a unified API for interacting with major AI providers including OpenAI, Anthropic Claude, Google Gemini, xAI, and Ollama. It simplifies AI integration for Ruby developers, offering a consistent interface similar to Vercel's AI SDK but tailored for the Ruby ecosystem, potentially boosting productivity and adoption of LLMs in Ruby applications. The gem has only three dependencies: Faraday, Zeitwerk, and Marcel. However, users report cache issues with providers like xAI, difficulty in implementing observability, and concerns about maintainer responsiveness to pull requests.

hackernews · doener · Jun 24, 14:41 · [Discussion](https://news.ycombinator.com/item?id=48660711)

**Background**: RubyLLM is designed to fill a gap in the Ruby ecosystem for mature AI tooling, providing a single API abstraction over multiple LLM providers. It aims to be easy to use out of the box while offering flexibility for advanced use cases.

<details><summary>References</summary>
<ul>
<li><a href="https://rubyllm.com/">RubyLLM | One beautiful Ruby framework for all major AI providers.</a></li>
<li><a href="https://gtmtools.dev/tools/rubyllm/">RubyLLM Review & API Analysis | GTM Tools</a></li>

</ul>
</details>

**Discussion**: Community feedback is mixed: some users praise its usability and compare it favorably to Vercel's AI framework, while others cite persistent cache bugs, lack of native responses API support (though reportedly now added), and difficulty in tracking API call sequences. A maintainer concern is that some merged PRs appear 'vibe coded' and lack rigor.

**Tags**: `#Ruby`, `#AI framework`, `#LLM`, `#developer tools`, `#open source`

---

<a id="item-21"></a>
## [Simon Willison Converts MDN Browser Data to SQLite](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison created a SQLite database from MDN's browser-compat-data repository, using AI-generated scripts from Claude Code for web (Opus 4.8) and Codex Desktop (GPT-5.5). The resulting ~66MB database is hosted on GitHub with open CORS headers and can be explored via Datasette Lite. This tool makes MDN's comprehensive browser compatibility data easily queryable via SQL, enabling developers and AI coding agents to quickly check feature support across browsers. It also demonstrates a practical workflow for using AI to generate and deploy data conversion scripts. The database is built by a Python script generated by Claude Code (Opus 4.8) using sqlite-utils, and a GitHub Actions workflow generated by Codex Desktop (GPT-5.5) force-pushes the database to an orphan branch for CDN access. The database includes open CORS headers, allowing direct client-side queries from tools like Datasette Lite.

rss · Simon Willison · Jun 24, 23:59

**Background**: MDN's browser-compat-data is a large JSON repository detailing which web platform features are supported in which browser versions. SQLite is a lightweight, file-based relational database engine. CORS (Cross-Origin Resource Sharing) headers allow web pages from different origins to access resources. Datasette Lite is a web-based tool that lets users explore SQLite databases interactively in the browser.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server - MDN Web Docs</a></li>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 - Anthropic</a></li>

</ul>
</details>

**Tags**: `#browser compatibility`, `#SQLite`, `#data conversion`, `#MDN`

---

<a id="item-22"></a>
## [Model security risks in production: are they tested?](https://www.reddit.com/r/MachineLearning/comments/1uddtws/are_model_security_risks_extraction_poisoning/) ⭐️ 6.0/10

A Reddit user observes that many ML teams deploy models without adversarial testing for risks like model extraction and data poisoning, highlighting a gap compared to standard software security reviews. As ML models are increasingly deployed in critical applications, the absence of systematic adversarial testing exposes organizations to extraction and poisoning attacks, undermining trust and security. The post serves as a discussion starter with no technical details or comments. It contrasts the current state of ML security with that of conventional software, where security review is standard.

reddit · r/MachineLearning · /u/Xorphian · Jun 23, 10:52

**Background**: Model extraction attacks involve an adversary querying a deployed model to steal its behavior or internal parameters, potentially enabling copycat models or transfer attacks. Data poisoning attacks introduce corrupted data during training to manipulate the model's predictions. Adversarial testing systematically evaluates model robustness against such threats, but it is not yet standard practice in many production environments.

<details><summary>References</summary>
<ul>
<li><a href="https://secportal.io/vulnerabilities/model-extraction-attack">Model Extraction Attack Guide | SecPortal</a></li>
<li><a href="https://en.wikipedia.org/wiki/Data_poisoning_attack">Data poisoning attack</a></li>
<li><a href="https://en.wikipedia.org/wiki/Adversarial_machine_learning">Adversarial machine learning - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#model security`, `#adversarial testing`, `#ML production`, `#extraction`, `#poisoning`

---