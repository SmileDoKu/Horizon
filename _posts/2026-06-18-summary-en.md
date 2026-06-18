---
layout: default
title: "Horizon Summary: 2026-06-18 (EN)"
date: 2026-06-18
lang: en
---

> From 40 items, 16 important content pieces were selected

---

1. [GLM-5.2: Top open-weights LLM with 753B params](#item-1) ⭐️ 9.0/10
2. [Next-Latent Prediction Improves Transformer Efficiency and World Models](#item-2) ⭐️ 9.0/10
3. [Lore: Open-source version control for game dev](#item-3) ⭐️ 8.0/10
4. [US delays blacklisting DeepSeek, targets 100+ Chinese firms](#item-4) ⭐️ 8.0/10
5. [Firecracker VMs in EC2 launch browsers under 1s](#item-5) ⭐️ 8.0/10
6. [RFC 10008: New HTTP QUERY Method for Idempotent Requests with Body](#item-6) ⭐️ 8.0/10
7. [Datasette 1.0a34 Adds CRUD Operations](#item-7) ⭐️ 8.0/10
8. [Mapping Causal Dependencies via Contrastive Targeted SFT](#item-8) ⭐️ 8.0/10
9. [Adam (YC W25) Launches Open-Source AI CAD Tool](#item-9) ⭐️ 7.0/10
10. [Charity Majors: AI Makes Code Generation Free and Instant](#item-10) ⭐️ 7.0/10
11. [Georgi Gerganov Endorses Qwen3.6-27B for Local Coding](#item-11) ⭐️ 7.0/10
12. [Speculative Decoding Accelerates LLM Inference](#item-12) ⭐️ 7.0/10
13. [Assessing probe strength in language model circuits](#item-13) ⭐️ 7.0/10
14. [Loreline: New Tools for Interactive Fiction Writing](#item-14) ⭐️ 6.0/10
15. [<click-to-play> Web Component lazy-loads GIFs](#item-15) ⭐️ 6.0/10
16. [GAN Deployed on Raspberry Pi for Physical NFT Minting](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM-5.2: Top open-weights LLM with 753B params](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a 753B parameter Mixture-of-Experts open-weights LLM with 1M token context, under MIT license on June 16, 2026. It ranks first among open-weights models on the Artificial Analysis Intelligence Index v4.1. This release marks a significant milestone for open-weights AI, as GLM-5.2 outperforms other leading open models like MiniMax-M3 and DeepSeek V4 Pro. Its strong performance, especially in coding tasks, could accelerate adoption of open models in production. GLM-5.2 uses 40 active parameters via MoE, has a 1.51TB model size, and is text-only. It consumes more output tokens per task (43k) compared to peers, and is available via OpenRouter at competitive pricing.

rss · Simon Willison · Jun 17, 23:58

**Background**: Open-weights models release the trained parameters for inference and fine-tuning, but not full training code or data. Mixture of Experts (MoE) architectures use multiple specialized subnetworks ('experts') activated per token, enabling large total parameters with lower inference cost.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/applying-mixture-of-experts-in-llm-architectures/">Applying Mixture of Experts in LLM Architectures | NVIDIA Technical...</a></li>
<li><a href="https://www.linkedin.com/pulse/open-weights-vs-source-llms-why-difference-matters-more-kapil-uthra-6kanf">Open Weights vs . Open Source in LLMs: Why the Difference Matters...</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights the model's impressive benchmark performance and high-quality SVG generation, but notes token inefficiency and poor performance on some creative tasks like the opossum SVG.

**Tags**: `#LLM`, `#open-source`, `#AI`, `#GLM-5.2`, `#Z.ai`

---

<a id="item-2"></a>
## [Next-Latent Prediction Improves Transformer Efficiency and World Models](https://www.reddit.com/r/MachineLearning/comments/1u84mio/nextlatent_prediction_transformers_r/) ⭐️ 9.0/10

Microsoft Research introduces Next-Latent Prediction (NextLat), a self-supervised method that trains transformers to predict their own next latent state, enabling up to 3.3x faster inference via self-speculative decoding and forming compact world models. This addresses a fundamental limitation of next-token prediction by providing denser supervision and enabling transformers to learn compact world models for reasoning and planning, potentially leading to more efficient and capable AI systems. NextLat trains the transformer to predict its next latent state given the current latent state and next token, theoretically proving convergence to belief states. The method achieves up to 3.3x faster inference via recursive multi-step lookahead and self-speculative decoding.

reddit · r/MachineLearning · /u/jayden_teoh_ · Jun 17, 08:44

**Background**: Traditional transformers predict the next token directly, which is myopic and provides sparse supervision. Self-supervised learning allows models to learn from unlabeled data by predicting parts of the input. Latent states are compressed representations of history that capture essential information. Self-speculative decoding uses a single model to draft and verify tokens for lossless acceleration.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2511.05963">[2511.05963] Next-Latent Prediction Transformers Learn Compact World Models</a></li>
<li><a href="https://arxiv.org/html/2511.05963v1">Next-Latent Prediction Transformers Learn Compact World Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>

</ul>
</details>

**Tags**: `#transformer`, `#self-supervised learning`, `#efficient inference`, `#representation learning`, `#world models`

---

<a id="item-3"></a>
## [Lore: Open-source version control for game dev](https://lore.org/) ⭐️ 8.0/10

Lore, an open-source version control system designed specifically for game development, has been announced. It aims to handle large binary files and exclusive file locking more effectively than Git, positioning itself as a competitor to Perforce. Game development teams often struggle with Git's limitations on large binary assets and exclusive locks, making Perforce the de facto standard despite its age and complexity. Lore offers a modern, open-source alternative that could reduce costs and improve workflows for game studios. Lore is still in early development, and details about its underlying architecture and performance are limited. It remains to be seen whether it can match Perforce's maturity, scalability, and ecosystem integration, particularly with Unreal Engine.

hackernews · regnerba · Jun 17, 14:30 · [Discussion](https://news.ycombinator.com/item?id=48571081)

**Background**: Game development involves large binary files like textures, 3D models, and audio, which Git handles poorly due to its text-based diff algorithm. Perforce has been the industry standard for game version control because it supports large files and exclusive file locks, but it is proprietary, expensive, and has a complex administration. Lore aims to fill this gap with an open-source solution that prioritizes these game-specific needs.

<details><summary>References</summary>
<ul>
<li><a href="https://saaslete.com/tools/code-management/perforce-helix">Perforce Helix Core | Code Management & Version Control | saaslete</a></li>
<li><a href="https://stackoverflow.com/questions/17955232/version-control-solution-that-can-handle-large-binary-files">Version Control Solution that Can Handle Large Binary Files</a></li>
<li><a href="https://eforce1.feld.cvut.cz/gitlab/help/user/project/file_lock.md">File lock · Project · User · Help · GitLab</a></li>

</ul>
</details>

**Discussion**: Community comments largely welcome Lore as a much-needed challenger to Perforce, noting that Git is unsuitable for game asset workflows. However, some point out that Perforce is deeply entrenched in game studios, especially with Unreal Engine, and that Lore will need to prove its reliability and ease of use to gain adoption.

**Tags**: `#version control`, `#game development`, `#open source`, `#perforce`, `#git`

---

<a id="item-4"></a>
## [US delays blacklisting DeepSeek, targets 100+ Chinese firms](https://www.reuters.com/world/china/us-holds-off-blacklisting-chinas-deepseek-more-than-100-firms-deemed-security-2026-06-17/) ⭐️ 8.0/10

The US government has decided not to immediately blacklist Chinese AI company DeepSeek, but has designated more than 100 other Chinese firms as national security risks on its Entity List. This decision reflects the US's nuanced approach to Chinese AI competition, balancing concerns over data security with the desire to maintain access to cost-effective AI models. The delayed blacklisting of DeepSeek, which has gained popularity for its affordable and competitive models, could impact global AI supply chains and pricing. DeepSeek is known for its open-weight models and significantly lower training costs compared to its US counterparts, such as GPT-4. The Entity List restricts US companies from selling goods and services to listed entities, but does not prohibit US individuals from buying from them.

hackernews · giuliomagnifico · Jun 17, 03:55 · [Discussion](https://news.ycombinator.com/item?id=48565498)

**Background**: The Entity List is a US trade blacklist that restricts exports to entities deemed a national security threat. DeepSeek, founded in 2023, is a Chinese AI company that gained attention in early 2025 for its R1 model, which rivals OpenAI's GPT-4 and o1 at a fraction of the training cost—only $6 million compared to $100 million for GPT-4. The company uses weaker AI chips due to export restrictions, yet achieved competitive performance, causing major market shifts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://en.wikipedia.org/wiki/Entity_List">Entity List - Wikipedia</a></li>
<li><a href="https://www.cnbc.com/2025/03/26/us-blacklists-50-chinese-companies-in-bid-to-curb-beijings-ai-chip-capabilities.html">U.S. blacklists over 50 Chinese companies in bid to curb Beijing's AI, chip capabilities</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed reactions: some defended DeepSeek's usefulness and affordability, with one user stating they use it daily via VSCode and find it slightly behind Claude but suits their workflow. Others criticized US policy as hypocritical, comparing it to China's own internet restrictions and questioning enforcement feasibility. A few noted that many Chinese AI firms are already on the Entity List, but the practical impact is limited as they rely on domestic chips.

**Tags**: `#AI regulation`, `#DeepSeek`, `#geopolitics`, `#US-China`, `#national security`

---

<a id="item-5"></a>
## [Firecracker VMs in EC2 launch browsers under 1s](https://browser-use.com/posts/firecracker-browser-infra) ⭐️ 8.0/10

Browser-Use describes an architecture that runs Firecracker microVMs on EC2 to launch browsers in under 1 second, achieving an 81–84.8% stealth rate against anti-bot measures. This enables highly undetectable browser automation for web scraping, testing, and other tasks, but raises ethical concerns about bypassing anti-bot protections. Nested virtualization on regular EC2 instances was only supported since February 2026, before which bare metal instances were required to run Firecracker. The setup uses Chromium with stealth modifications.

hackernews · gregpr07 · Jun 16, 15:15 · [Discussion](https://news.ycombinator.com/item?id=48556561)

**Background**: Firecracker is an open-source virtualization technology from AWS that creates lightweight microVMs, combining security and speed. Nested virtualization allows running a hypervisor inside a VM, enabling scenarios like running Firecracker on EC2 virtual instances.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Firecracker_(software)">Firecracker (software) - Wikipedia</a></li>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast microVMs for serverless computing. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nested_virtualization">Nested virtualization</a></li>

</ul>
</details>

**Discussion**: Commenters raised ethical concerns about bypassing anti-bot measures, with some questioning the legitimacy of the service. Technical discussions highlighted the recent availability of nested virtualization on EC2 and suggested alternatives like Lightpanda or containers for higher density.

**Tags**: `#Firecracker`, `#EC2`, `#browser automation`, `#anti-bot`, `#nested virtualization`

---

<a id="item-6"></a>
## [RFC 10008: New HTTP QUERY Method for Idempotent Requests with Body](https://www.rfc-editor.org/info/rfc10008/) ⭐️ 8.0/10

RFC 10008 defines a new HTTP QUERY method that allows clients to send idempotent and safe requests with a request body, filling a gap between GET (no body) and POST (non-idempotent). This standardized method provides a correct way to perform complex, side-effect-free queries without misusing GET or POST, improving API clarity, cache semantics, and interoperability. The QUERY method is safe and idempotent; its cache key includes the full request body. The IETF working group chose a new method over allowing GET with a body due to historical interoperability issues.

hackernews · schappim · Jun 17, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48568502)

**Background**: HTTP methods have specific properties: GET is safe and idempotent but cannot have a body; POST is neither safe nor idempotent. Developers often needed to send complex queries (e.g., large JSON filters) without side effects, leading to workarounds like using GET with a body or POST for read operations. RFC 10008 formalizes a new method to address these use cases.

<details><summary>References</summary>
<ul>
<li><a href="https://www.rfc-editor.org/info/rfc10008/">RFC 10008 : The HTTP QUERY Method | RFC Editor</a></li>
<li><a href="https://datatracker.ietf.org/doc/draft-ietf-httpbis-safe-method-w-body/">draft-ietf-httpbis-safe- method -w-body-14 - The HTTP QUERY Method</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods">HTTP request methods - HTTP | MDN</a></li>

</ul>
</details>

**Discussion**: Community comments question the motiving example and cache semantics, with one commenter suggesting a stronger use case would help. Another wonders if HTML forms will support the QUERY method to avoid re-submission warnings. A third notes they have been using GET with a body for years despite standards.

**Tags**: `#HTTP`, `#RFC`, `#web standards`, `#API design`

---

<a id="item-7"></a>
## [Datasette 1.0a34 Adds CRUD Operations](https://simonwillison.net/2026/Jun/16/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 1.0a34 introduces insert, edit, and delete row functionality directly in the web interface, as announced on June 16, 2026. This addresses a long-standing gap, making Datasette a more complete tool for data management without needing external tools or SQL expertise. The feature is available on table pages and row pages, and was inspired by Datasette Agent, an AI assistant that already supported SQL write operations.

rss · Simon Willison · Jun 16, 21:31

**Background**: Datasette is an open-source tool for exploring and publishing data, typically from SQLite databases. It provides a web interface for browsing and querying data. Prior to this release, data modification required direct SQL interaction or external tools, making this CRUD addition a significant enhancement.

<details><summary>References</summary>
<ul>
<li><a href="https://agent.datasette.io/">Datasette Agent : an AI assistant for Datasette to help explore and...</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#database`, `#release`, `#CRUD`, `#open-source`

---

<a id="item-8"></a>
## [Mapping Causal Dependencies via Contrastive Targeted SFT](https://www.reddit.com/r/MachineLearning/comments/1u8if6l/contrastive_targeted_sft_as_a_mechinterp_method/) ⭐️ 8.0/10

A Reddit user proposes using contrastive targeted supervised fine-tuning (SFT) to identify and ablate circuits for specific capabilities in a 31B model, aiming to build a causal dependency graph of model dimensions. This method could enable more systematic mechanistic interpretability, allowing researchers to understand how capabilities interact and optimize training order, potentially leading to better control and understanding of large language models. The author plans to train contrastive variants (deep vs shallow examples for a specific dimension), locate the circuit, ablate it, and measure which other dimensions degrade to build a causal graph. They seek feedback on distinguishing direct from indirect effects and combining steering with fine-tuning.

reddit · r/MachineLearning · /u/Substantial_Diver469 · Jun 17, 18:31

**Background**: Mechanistic interpretability aims to reverse-engineer neural networks into human-understandable circuits. Supervised fine-tuning (SFT) adapts pretrained models to follow instructions. Contrastive approaches use paired examples to isolate features. Circuit discovery identifies subgraphs responsible for specific behaviors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.emergentmind.com/topics/contrastive-neuron-steering-cns">Contrastive Neuron Steering (CNS)</a></li>
<li><a href="https://openreview.net/forum?id=KxEselcinr">Time-Resolved Circuit Discovery in RNNs via... | OpenReview</a></li>

</ul>
</details>

**Tags**: `#mechanistic interpretability`, `#supervised fine-tuning`, `#causal dependency`, `#neural network interpretability`, `#circuit discovery`

---

<a id="item-9"></a>
## [Adam (YC W25) Launches Open-Source AI CAD Tool](https://github.com/Adam-CAD/CADAM) ⭐️ 7.0/10

Adam, a YC W25 startup, launched CADAM, an open-source AI agent that generates parametric 3D mechanical CAD models from text prompts and image references. This tool democratizes mechanical design by allowing non-experts to create CAD models using natural language, significantly lowering the barrier to entry and accelerating prototyping. It also advances the code-as-CAD paradigm, potentially transforming how engineers iterate on designs. CADAM outputs OpenSCAD code with automatically extracted parameters displayed as interactive sliders for instant tweaking, and exports to formats like STL and OBJ. It runs entirely in-browser via WebAssembly and supports multiple LLM backends through the Vercel AI SDK, with Gemini 3.1 Pro performing best in internal evaluations.

hackernews · zachdive · Jun 17, 16:14 · [Discussion](https://news.ycombinator.com/item?id=48572553)

**Background**: CAD (Computer-Aided Design) is essential for mechanical engineering but traditionally requires specialized software and skills. OpenSCAD is a script-based CAD tool popular in the open-source community. CADAM leverages AI to generate such scripts from natural language, making CAD accessible to a broader audience. The tool is built with TanStack Start and Supabase, and relies on parametric modeling principles to allow easy modification.

<details><summary>References</summary>
<ul>
<li><a href="https://tanstack.com/start/latest">TanStack Start</a></li>
<li><a href="https://supabase.com/">Supabase | The Postgres Development Platform.</a></li>
<li><a href="https://www.autodesk.com/solutions/parametric-modeling">Parametric Modeling Software | Autodesk</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some engineers express skepticism about real-world time savings and accuracy, while others report successful generation of practical parts like grommets. Several commenters also mention competing projects or propose alternative use cases, indicating strong interest but also reservations.

**Tags**: `#AI`, `#CAD`, `#open-source`, `#YC`, `#mechanical-design`

---

<a id="item-10"></a>
## [Charity Majors: AI Makes Code Generation Free and Instant](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 7.0/10

Charity Majors observed that as of 2025, AI has made code generation effectively free and instant, turning code from a treasured asset into a disposable commodity. This shift fundamentally changes how software is designed, built, and maintained, placing greater emphasis on architecture and testing over code volume. It will impact the economics of software development and the skills valued in engineers. Majors made this observation in her article 'AI demands more engineering discipline. Not less,' noting that the change occurred 'practically overnight' after 2025. She emphasized that code is now disposable and regenerable, contrasting with the past when it was carefully curated.

rss · Simon Willison · Jun 17, 17:12

**Background**: Before AI-assisted programming, writing code was time-consuming and expensive, leading organizations to treat lines of code as valuable assets to be reused and maintained. The advent of large language models (LLMs) and generative AI now allows developers to generate code rapidly from natural language prompts, dramatically lowering the cost of production.

**Tags**: `#ai-assisted-programming`, `#generative-ai`, `#software-engineering`, `#economics`

---

<a id="item-11"></a>
## [Georgi Gerganov Endorses Qwen3.6-27B for Local Coding](https://simonwillison.net/2026/Jun/16/georgi-gerganov/#atom-everything) ⭐️ 7.0/10

Georgi Gerganov, creator of llama.cpp, publicly endorsed the Qwen3.6-27B model for local coding tasks on Hacker News, stating he uses it daily on his M2 Ultra and RTX 5090 systems. This endorsement from a key figure in local LLM development validates Qwen3.6-27B as a practical, high-capability tool for coding, potentially accelerating adoption of local models for developers seeking privacy and low latency. Gerganov uses a minimal wrapper called pi agent with the command `pi -nc --offline` and a custom system prompt, and he applies it to mundane tasks like small commits in the ggml-org organization.

rss · Simon Willison · Jun 16, 16:04

**Background**: Georgi Gerganov is the creator of llama.cpp, a popular C/C++ library for running large language models locally on consumer hardware. Qwen3.6-27B is a 27-billion-parameter dense model from Alibaba's Qwen team, designed for agentic coding and outperforming larger models on benchmarks like SWE-bench. Local LLMs run entirely on the user's device, offering privacy and offline capabilities, and tools like pi agent provide lightweight interfaces for such models.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.6-27B">Qwen/Qwen3.6-27B · Hugging Face</a></li>
<li><a href="https://qwen.ai/blog?id=qwen3.6-27b">Qwen3.6-27B: Flagship-Level Coding in a 27B Dense Model</a></li>
<li><a href="https://github.com/earendil-works/pi">GitHub - earendil-works/pi: AI agent toolkit: unified LLM API, agent loop, TUI, coding agent CLI · GitHub</a></li>

</ul>
</details>

**Discussion**: The Hacker News comment section reacted positively, with Gerganov's detailed usage report—including hardware specs and the minimal harness—reinforcing the model's real-world viability for everyday coding tasks.

**Tags**: `#qwen`, `#local-llm`, `#coding`, `#llama.cpp`, `#model-endorsement`

---

<a id="item-12"></a>
## [Speculative Decoding Accelerates LLM Inference](https://www.reddit.com/r/MachineLearning/comments/1u83kzt/what_is_speculative_decoding_trending_on/) ⭐️ 7.0/10

Speculative decoding, an inference optimization technique using a small draft model to propose tokens verified by a larger model, is trending on Papers with Code. SGLang recently achieved state-of-the-art inference latencies by integrating DFlash block diffusion models, as detailed in their blog post. Speculative decoding enables up to 2-3x speedups in LLM token generation without output quality loss, making it crucial for real-time applications. The SGLang framework's achievement sets a new benchmark for serving efficiency, benefiting developers deploying large models in production. The technique leverages a lightweight draft model like DFlash, which uses block diffusion to generate multiple tokens in a single parallel pass. SGLang combined this with Modal's serverless cloud platform to achieve low-latency serving, as described in their June 15, 2026 blog post.

reddit · r/MachineLearning · /u/NielsRogge · Jun 17, 07:41

**Background**: Speculative decoding is an inference optimization method for large language models (LLMs). It uses a fast, small 'draft' model to quickly generate several future tokens, which are then checked in parallel by the larger 'target' model; if accepted, multiple tokens are added per step, accelerating generation. SGLang is a high-performance serving framework for LLMs, and DFlash is a lightweight block diffusion model designed specifically for speculative decoding, achieving higher speedups than earlier autoregressive methods like EAGLE-3.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sgl-project/sglang">GitHub - sgl-project/sglang: SGLang is a high-performance serving framework for large language models and multimodal models. · GitHub</a></li>
<li><a href="https://github.com/z-lab/dflash">GitHub - z-lab/dflash: DFlash: Block Diffusion for Flash Speculative Decoding · GitHub</a></li>
<li><a href="https://modal.com/">Modal: High-performance AI infrastructure</a></li>

</ul>
</details>

**Tags**: `#speculative decoding`, `#LLM inference`, `#optimization`, `#SGLang`, `#language models`

---

<a id="item-13"></a>
## [Assessing probe strength in language model circuits](https://www.reddit.com/r/MachineLearning/comments/1u8lo60/how_do_you_analyze_the_relative_strength_of/) ⭐️ 7.0/10

A Reddit user raised a detailed question about the lack of theoretical guarantees for evaluating the relative strength of linear probes in circuit analysis of language models, questioning how to balance probe capacity against model capacity and avoid overfitting. 这个问题凸显了机械可解释性研究中的一个关键缺口：如果没有关于探针可靠性的严格理论，关于模型内部知识的结论（例如位置编码）可能不可靠，进而影响诸如事实性保证等下游应用。 The user references an earlier post claiming to train a logistic regression probe to detect token position in a Transformer, and points out potential confounders like small vocabulary size and model errors in letter counting (e.g., Gemini miscounting 'r's in 'Google').

reddit · r/MachineLearning · /u/RepresentativeBee600 · Jun 17, 20:29

**Background**: In mechanistic interpretability, linear probes are simple classifiers trained on a model's hidden representations to detect whether certain concepts are encoded. Researchers often use them to infer what a model 'knows' about features like token position. However, theoretical foundations for probe validity—such as Nyquist-type sampling guarantees or bounds on overfitting—remain underdeveloped, making it difficult to separate genuine model knowledge from probe artifacts.

<details><summary>References</summary>
<ul>
<li><a href="https://carpentries-incubator.github.io/fair-explainable-ml/5c-probes.html">Trustworthy AI: Validity, Fairness, Explainability, and Uncertainty Assessments: Explainability methods: Linear Probes</a></li>
<li><a href="https://arxiv.org/abs/2602.17229">[2602.17229] Mechanistic Interpretability of Cognitive Complexity in LLMs via Linear Probing using Bloom's Taxonomy</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#mechanistic interpretability`, `#probes`, `#circuit analysis`, `#theory`

---

<a id="item-14"></a>
## [Loreline: New Tools for Interactive Fiction Writing](https://loreline.app/en/) ⭐️ 6.0/10

Loreline is a newly released set of tools for writing interactive fiction, featuring highly readable scripts and potential for deployment, but currently lacks built-in export options. Loreline enters a niche but passionate community of interactive fiction authors and game developers, offering a fresh alternative to established platforms like Inform 7 and Ink. Its readability focus may lower the barrier for new writers, but the missing export functionality could limit its adoption. The tool emphasizes script readability, as noted by community members, and has potential for deployment, but lacks out-of-the-box export targets like Ink's web export. Users must handle middleware to deploy their stories.

hackernews · smartmic · Jun 17, 20:29 · [Discussion](https://news.ycombinator.com/item?id=48576395)

**Background**: Interactive fiction (IF) is a genre of text-based games where players make choices that affect the story. Established tools like Inform 7 and Ink provide languages and engines for writing IF, with features such as natural language syntax (Inform 7) or simple markup (Ink). Loreline aims to offer a similar but distinct toolset with readable scripts.

**Discussion**: Community comments compare Loreline to Inform 7 and Ink, praising its script readability but noting the lack of built-in export options. One commenter mentioned missing deploy targets, while another recalled their own IF system focusing on visuals and portability.

**Tags**: `#interactive fiction`, `#game development`, `#writing tools`, `#Hacker News`, `#software tools`

---

<a id="item-15"></a>
## [<click-to-play> Web Component lazy-loads GIFs](https://simonwillison.net/2026/Jun/17/click-to-play-component/#atom-everything) ⭐️ 6.0/10

Simon Willison released a new web component called <click-to-play> that transforms a static image link into a click-to-play GIF player, loading the GIF only on user interaction. This component improves page performance by lazy-loading heavy GIFs, reducing bandwidth and load time, especially useful for content-heavy sites and mobile users. The component is built with native Web Components and follows progressive enhancement, so it works even if JavaScript is disabled, showing a fallback link.

rss · Simon Willison · Jun 17, 03:56

**Background**: Web Components are a set of browser standards allowing developers to create reusable custom elements with encapsulated styles and logic. Progressive enhancement is a web design strategy that ensures core content is accessible to all users, with enhanced features available to browsers that support them. This component leverages both to provide a lightweight, accessible solution.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Web_Components">Web Components</a></li>
<li><a href="https://en.wikipedia.org/wiki/Progressive_enhancement">Progressive enhancement</a></li>

</ul>
</details>

**Tags**: `#web-components`, `#javascript`, `#progressive-enhancement`, `#performance`, `#gif`

---

<a id="item-16"></a>
## [GAN Deployed on Raspberry Pi for Physical NFT Minting](https://www.reddit.com/r/MachineLearning/comments/1u8cqan/i_deployed_a_gan_on_a_raspberry_pi_4_and_built_a/) ⭐️ 6.0/10

A user trained a 128×128 DCGAN on a Macbook M3, exported it to ONNX, and deployed it on a Raspberry Pi 4 to generate hallucinated face hybrids at the press of a button, creating a physical NFT minting device. This project demonstrates the feasibility of running generative AI models on low-cost edge devices, opening up possibilities for interactive art installations and decentralized NFT generation. The generator uses 6 convolutional-transpose blocks starting with 1024 feature maps, trained on 2480 images across 11 subjects with one dominant anchor class. Inference takes 3 seconds per face on a Raspberry Pi 4, with model size 53MB in float32 ONNX format.

reddit · r/MachineLearning · /u/Numerous-Dentist-882 · Jun 17, 15:05

**Background**: DCGAN (Deep Convolutional Generative Adversarial Network) is a class of GANs that uses convolutional layers for image generation, commonly used for face generation. ONNX (Open Neural Network Exchange) is an open standard format for representing machine learning models, enabling interoperability between frameworks like PyTorch and runtime environments on edge devices such as the Raspberry Pi.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html">DCGAN Tutorial — PyTorch Tutorials 2.12.0+cu130 documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/ONNX">ONNX</a></li>

</ul>
</details>

**Tags**: `#GAN`, `#Raspberry Pi`, `#Edge AI`, `#ONNX`, `#Art project`

---