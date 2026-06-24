---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 37 items, 21 important content pieces were selected

---

1. [FUTO Swipe: Open-Source Swipe Typing Model Released](#item-1) ⭐️ 8.0/10
2. [Rhombus Language 1.0 Released with Powerful `…` Macro Operator](#item-2) ⭐️ 8.0/10
3. [Open-Source WYSIWYG TikZ Editor Launched](#item-3) ⭐️ 8.0/10
4. [The Coming Loop: AI Shifts Software Development](#item-4) ⭐️ 8.0/10
5. [Vitamin D Benefits: Mostly for Severely Deficient People](#item-5) ⭐️ 8.0/10
6. [Prompt Injection as Role Confusion: Style Overrides Content](#item-6) ⭐️ 8.0/10
7. [Porting Moebius 0.2B Inpainting Model to Browser via WebGPU](#item-7) ⭐️ 8.0/10
8. [DeepSWE: New Open-Source Benchmark for Frontier Coding Agents](#item-8) ⭐️ 8.0/10
9. [Vulnerability reports are not special anymore](#item-9) ⭐️ 7.0/10
10. [Swift Package Index acquired by Apple](#item-10) ⭐️ 7.0/10
11. [Meta Halts Employee Monitoring After Data Leak](#item-11) ⭐️ 7.0/10
12. [Extreme Heat Conference Canceled Due to Heat Warning](#item-12) ⭐️ 7.0/10
13. [Are model security risks tested in production?](#item-13) ⭐️ 7.0/10
14. [Hugging Face Revives Papers with Code with New Features](#item-14) ⭐️ 7.0/10
15. [Seeking Literature on Syntax-Robust NLI for Imperfect Text](#item-15) ⭐️ 7.0/10
16. [LLM Vulnerability Detection Benchmark Obfuscates Juliet Test Cases](#item-16) ⭐️ 7.0/10
17. [uv 0.11.24 adds Python 3.15 beta, relocatable environments](#item-17) ⭐️ 6.0/10
18. [Remembering Tony Krueger, the man behind spell-check squiggles](#item-18) ⭐️ 6.0/10
19. [Datasette 1.0a35 Alpha Adds Create/Alter Table APIs](#item-19) ⭐️ 6.0/10
20. [Test harness for OPFS + Pyodide in Datasette Lite](#item-20) ⭐️ 6.0/10
21. [Potential Mistake Found in ICLR 2026 Blogpost](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [FUTO Swipe: Open-Source Swipe Typing Model Released](https://swipe.futo.tech/) ⭐️ 8.0/10

FUTO Swipe, a new open-source swipe typing model, has been released as part of the FUTO Keyboard app for Android, aiming to provide high accuracy and multi-language support. This project offers a potential open-source alternative to proprietary keyboards like Gboard, addressing user pain points in multi-language switching and accuracy for swipe typing. The model is fully offline on Android, and the trained models can be downloaded separately for building custom keyboards, though early users report issues with random capitalization and lack of contextual word suggestions.

hackernews · futohq · Jun 23, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48648619)

**Background**: Swipe typing (also known as gesture typing) allows users to input words by sliding a finger across the keyboard letters, with the system predicting the intended word. FUTO Swipe uses machine learning to decode these gestures; its open-source nature enables community improvements and customization.

<details><summary>References</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://swipe.futo.org/">FUTO Keyboard Swipe Training</a></li>

</ul>
</details>

**Discussion**: Community comments express strong interest in multi-language support (e.g., English+German simultaneously) and desire for a keyboard layout optimized for swipe typing. Some users have switched from Gboard, noting improvements but also issues like random capitalization and lack of context awareness.

**Tags**: `#typing`, `#mobile input`, `#open source`, `#keyboard`, `#machine learning`

---

<a id="item-2"></a>
## [Rhombus Language 1.0 Released with Powerful `…` Macro Operator](https://blog.racket-lang.org/2026/06/rhombus-v1.0.html) ⭐️ 8.0/10

Rhombus Language, a new language built on Racket, reached version 1.0 in June 2026. The release highlights a novel `…` operator that acts as a general macro for nested data structures and mapping, not just a splat operator. This release marks a significant milestone for a language that combines conventional syntax with Racket's powerful macro system. It may influence how programming languages integrate user-defined syntax extensions, especially with operators that replace common patterns like `map`. The `…` operator is not a built-in feature but is implemented as a macro, demonstrating Rhombus's macro-extensibility. The release is coordinated with the Rhombus package on Racket's package system, and the language uses Shrubbery syntax for conventional appearance.

hackernews · Decabytes · Jun 22, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48633473)

**Background**: Rhombus is a general-purpose programming language built on Racket, designed to be easy to use and uniquely customizable. It uses Shrubbery syntax, which provides a more conventional syntax while retaining the full power of Racket's macro system. The `…` operator in Rhombus is an example of how macros can create flexible, context-sensitive syntax.

<details><summary>References</summary>
<ul>
<li><a href="https://rhombus-lang.org/">Rhombus Programming Language</a></li>
<li><a href="https://github.com/racket/rhombus">GitHub - racket/rhombus: Rhombus programming language</a></li>
<li><a href="https://docs.racket-lang.org/rhombus/index.html">Rhombus - Racket</a></li>

</ul>
</details>

**Discussion**: Commenters expressed enthusiasm for the `…` operator and its generality, comparing it favorably to splat operators in other languages. Some discussed the challenges of macro design without s-expressions, referencing talks by Matthew Flatt. There was also interest in the Shrubbery syntax and future conference talks.

**Tags**: `#rhombus`, `#racket`, `#programming-languages`, `#macros`, `#release`

---

<a id="item-3"></a>
## [Open-Source WYSIWYG TikZ Editor Launched](https://tikz.dev/editor/) ⭐️ 8.0/10

A new open-source WYSIWYG TikZ editor has been released, allowing users to visually edit TikZ figures while the source code and rendered output stay synchronized in real time. The editor was built almost entirely using the AI coding agent Codex, with over 700 million tokens consumed. This tool addresses a major pain point for academics and LaTeX users who manually code TikZ figures, significantly lowering the barrier to creating high-quality diagrams. It also showcases the potential of AI-assisted development to tackle projects that would be too tedious for humans alone. The editor maintains a mapping between source code locations and rendered objects, enabling drag-and-resize edits that only modify the relevant coordinates without altering code structure. However, community feedback notes that generated code uses absolute coordinates, which is suboptimal compared to typical TikZ practices.

hackernews · DominikPeters · Jun 23, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48645437)

**Background**: TikZ is a powerful LaTeX package for creating vector graphics using commands like \draw and \node, widely used in academic papers. Traditionally, users write code and repeatedly recompile to adjust positions, a tedious process. This editor provides a visual interface that synchronizes with the source code, similar to GUI-based drawing tools but for LaTeX.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PGF/TikZ">PGF/TikZ - Wikipedia</a></li>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://tikz.dev/">PGF/TikZ Manual - Complete Online Documentation</a></li>

</ul>
</details>

**Discussion**: The community response is positive overall, with many users excited about the tool's potential, but some criticize the generated TikZ code for relying on absolute coordinates instead of more elegant relative positioning. One commenter, the developer, revealed the project cost about $500 in ChatGPT subscriptions despite consuming $15k worth of tokens at API rates, highlighting the efficiency of AI-assisted development.

**Tags**: `#LaTeX`, `#TikZ`, `#editor`, `#WYSIWYG`, `#open-source`

---

<a id="item-4"></a>
## [The Coming Loop: AI Shifts Software Development](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Armin Ronacher published an essay titled 'The Coming Loop' reflecting on the shift in software development towards AI-assisted loops, warning that this may lead to a loss of human craftsmanship and code maintainability. This essay sparks critical conversation about the impact of AI on software engineering practices, particularly the risk of skill atrophy and over-reliance on machines for code understanding and maintenance. With 362 points and 254 comments, the essay has high engagement in the developer community, and the author is a respected figure known for creating Flask. The topic touches on human understanding, code quality, and the potential loss of craftsmanship.

hackernews · ingve · Jun 23, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48643180)

**Background**: In AI-assisted development, 'loops' refer to iterative cycles where developers prompt AI models to generate or modify code, then review and refine. This approach can accelerate coding but risks creating code that is hard for humans to fully understand or maintain without machine help.

**Discussion**: Commenters like mccoyb and stillpointlab emphasize that AI loops require upfront clarity and spec writing, which cannot be shortcut. Others like gavinh and miki123211 worry about loss of human ability to create or discuss code without augmentation, and a degradation of aesthetic judgment in coding.

**Tags**: `#AI-assisted development`, `#software engineering`, `#code quality`, `#human-AI collaboration`, `#programming practices`

---

<a id="item-5"></a>
## [Vitamin D Benefits: Mostly for Severely Deficient People](https://dynomight.net/vitamin-d/) ⭐️ 8.0/10

A detailed analysis of vitamin D studies reveals that significant benefits are primarily observed in individuals with severe deficiency, challenging the broad health claims often made by influencers. This nuanced perspective helps clarify conflicting evidence on vitamin D supplementation and encourages more targeted use rather than universal supplementation. The analysis notes that NHANES survey data had methodological limitations, such as collecting data in northern latitudes only during summer, which may affect prevalence estimates of deficiency.

hackernews · surprisetalk · Jun 23, 16:30 · [Discussion](https://news.ycombinator.com/item?id=48647486)

**Background**: Vitamin D is essential for bone health and immune function, and deficiency is linked to various health issues. However, many studies on supplementation have shown mixed results, partly because baseline levels vary. Vitamin K2 is often recommended alongside D3 to support calcium absorption and prevent arterial calcification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vitamin_K2">Vitamin K2</a></li>
<li><a href="https://health.clevelandclinic.org/vitamin-k2">Vitamin K2: What It Is and Its Benefits - Cleveland Clinic Health ...</a></li>

</ul>
</details>

**Discussion**: Community comments critique the NHANES survey design for its seasonal-latitude bias and highlight the importance of co-supplementation with vitamin K2 for optimal absorption. Some users share personal experiences of needing higher doses (e.g., 5000 IU/day) to achieve adequate blood levels.

**Tags**: `#vitamin D`, `#nutrition science`, `#health`, `#evidence-based medicine`

---

<a id="item-6"></a>
## [Prompt Injection as Role Confusion: Style Overrides Content](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 8.0/10

Researchers found that LLMs judge text source based on style rather than role tags, enabling effective jailbreaks; destyling reduced attack success from 61% to 10%. This reveals a fundamental limitation of current LLMs: they cannot reliably distinguish trusted instructions from untrusted input, undermining AI safety and security in applications like chatbots and autonomous agents. The study involved role probes to measure internal role perception and found that style mimicry allowed attacks to succeed even when the untrusted text was wrapped in <user> tags.

rss · Simon Willison · Jun 22, 23:59

**Background**: Prompt injection is a vulnerability where adversarial input causes LLMs to behave unexpectedly, akin to command injection. Role confusion refers to the LLM's inability to perceive the intended role of text, leading it to follow instructions that sound like system directives regardless of their actual role tag.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.12277">[2603.12277] Prompt Injection as Role Confusion - arXiv.org Prompt Injection as Role Confusion Measuring and Understanding LLM Identity Confusion Prompt Injection as Role Confusion - simonwillison.net Prompt Injection as Role Confusion: Unmasking the Deeper Flaw ... Paper page - I'm Spartacus, No, I'm Spartacus: Measuring and ... Prompt Injection as Role Confusion | Hacker News</a></li>
<li><a href="https://role-confusion.github.io/">Prompt Injection as Role Confusion</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>

</ul>
</details>

**Tags**: `#prompt injection`, `#AI safety`, `#jailbreak`, `#LLM`, `#role confusion`

---

<a id="item-7"></a>
## [Porting Moebius 0.2B Inpainting Model to Browser via WebGPU](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 8.0/10

Simon Willison ported the lightweight Moebius 0.2B image inpainting model from PyTorch/CUDA to run in the browser using ONNX Runtime Web on WebGPU, with the help of Claude Code. A working demo is available at simonw.github.io/moebius-web/. This makes a high-performance inpainting model accessible without dedicated GPU hardware, enabling in-browser image editing directly. It also demonstrates the feasibility of porting specialized ML models to WebGPU using AI coding agents like Claude Code. The model weights are ~1.27 GB (UNet alone is 907 MB), downloaded from Hugging Face on first run. The port uses ONNX Runtime Web rather than higher-level libraries like Transformers.js, and the author intentionally avoided a known fast attention kernel to keep code simpler.

rss · Simon Willison · Jun 22, 23:43

**Background**: Image inpainting is a technique to fill or replace masked regions of an image with plausible content. Moebius is a lightweight framework with just 0.2B parameters that achieves quality comparable to much larger 10B-parameter models. WebGPU is a browser API providing low-level GPU access for high-performance computing, including machine learning inference. ONNX Runtime Web enables running ONNX models in the browser using WebGPU as the backend.

<details><summary>References</summary>
<ul>
<li><a href="https://simonw.github.io/moebius-web/">Moebius Inpainting — WebGPU</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>

</ul>
</details>

**Tags**: `#image inpainting`, `#WebGPU`, `#browser ML`, `#model porting`, `#AI deployment`

---

<a id="item-8"></a>
## [DeepSWE: New Open-Source Benchmark for Frontier Coding Agents](https://www.reddit.com/r/MachineLearning/comments/1ue0hlp/deepswe_new_benchmark_looking_at_how_well_todays/) ⭐️ 8.0/10

DeepSWE is a new open-source benchmark for evaluating AI coding agents, featuring contamination-free tasks, diverse real-world repositories, and hand-written verifiers. This benchmark addresses key flaws in existing coding benchmarks, such as data contamination and lack of real-world complexity, potentially setting a new standard for evaluating software engineering capabilities of frontier models. Tasks in DeepSWE require 5.5x more code and ~2x more output tokens than SWE-bench Pro, yet have shorter prompts, and verifiers test software behavior rather than implementation details.

reddit · r/MachineLearning · /u/we_are_mammals · Jun 24, 02:03

**Background**: Existing coding benchmarks like SWE-bench often suffer from data contamination because tasks are adapted from public repositories, inflating model scores. DeepSWE creates entirely new tasks to avoid this. The benchmark spans 91 repositories across 5 languages and uses hand-written verifiers for reliable assessment. It is designed to better reflect real-world software engineering challenges.

<details><summary>References</summary>
<ul>
<li><a href="https://deepswe.lol/">DeepSWE — Long-Horizon Software Engineering Benchmark</a></li>
<li><a href="https://www.emergentmind.com/topics/contamination-free-benchmarking">Contamination - Free Benchmarking</a></li>
<li><a href="https://www.swebench.com/">SWE - bench Leaderboards</a></li>

</ul>
</details>

**Tags**: `#benchmark`, `#code generation`, `#AI evaluation`, `#software engineering`, `#machine learning`

---

<a id="item-9"></a>
## [Vulnerability reports are not special anymore](https://words.filippo.io/vuln-reports/) ⭐️ 7.0/10

Security researcher Filippo Valsorda argues that vulnerability reports have become devalued due to an influx of spam and low-quality LLM-generated reports, fundamentally changing the dynamics between researchers and maintainers. This shift erodes trust in vulnerability reporting, making it harder for legitimate researchers to get serious attention and increasing the burden on open source maintainers, potentially leading to slower or missed fixes for real vulnerabilities. The author notes that half of the unsolicited reports come from LLMs finding trivial issues like bad CSS, while the other half appear to be extortion attempts. He suggests the situation may be temporary as LLMs also help fix bugs and improve code quality.

hackernews · goranmoomin · Jun 23, 23:42 · [Discussion](https://news.ycombinator.com/item?id=48653216)

**Background**: Vulnerability reporting is a process where security researchers privately disclose flaws to maintainers, historically seen as a serious responsibility. With the rise of LLMs that can automatically scan code for potential vulnerabilities, the volume of reports has surged, many of which are low severity or irrelevant. This overwhelms maintainers and devalues the signal of a genuine report.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2511.04538v1">From Model to Breach: Towards Actionable LLM-Generated Vulnerabilities ...</a></li>
<li><a href="https://arxiv.org/html/2505.01177v1">LLM Security: Vulnerabilities, Attacks, Defenses, and Countermeasures</a></li>

</ul>
</details>

**Discussion**: Community comments highlight frustration from both sides: maintainers receiving spam (e.g., 2-5 reports per week) and researchers feeling that reports are dismissed. Some believe the trend is temporary as LLMs both find and fix bugs, while others argue it incentivizes better practices like memory-safe languages. A commentator notes that vulnerability reporting exists for the project's benefit, not the researcher's.

**Tags**: `#security`, `#vulnerability reporting`, `#LLMs`, `#open source`, `#community discussion`

---

<a id="item-10"></a>
## [Swift Package Index acquired by Apple](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 7.0/10

Apple has acquired the Swift Package Index, a community-run package search engine and metadata index for Swift packages, as announced on the SPI blog. This acquisition signals Apple's increased investment in the Swift ecosystem and package management, potentially centralizing developer tools. The Swift Package Index will remain open source and available to the community, with Apple pledging no immediate changes to its operation.

hackernews · JDevlieghere · Jun 23, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48648779)

**Background**: The Swift Package Index (SPI) is a community-driven website that indexes Swift packages from GitHub, providing search, metadata, and package recommendations. It was founded by Dave Verwer and Sven A. Schmidt. Apple's own Swift Package Manager (SPM) integrates with packages, but SPI offered an independent search and discovery platform.

<details><summary>References</summary>
<ul>
<li><a href="https://9to5mac.com/2026/06/23/swift-package-index-joins-apple-pledges-to-remain-open-source/">Swift Package Index joins Apple, pledges to remain open ...</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some are optimistic for the creators, while others worry about Apple's track record with open source and developer services, especially regarding future plans for developer identity.

**Tags**: `#Swift`, `#Apple`, `#package management`, `#open source`

---

<a id="item-11"></a>
## [Meta Halts Employee Monitoring After Data Leak](https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/) ⭐️ 7.0/10

Meta paused its employee-tracking program after an internal data leak exposed private conversations and performance information of employees. This incident raises serious concerns about privacy and surveillance in the workplace, especially within a company that handles vast amounts of user data. The leaked data included plain-text screenshots of employee private conversations and performance information, suggesting the monitoring was thorough and not properly anonymized.

hackernews · 1vuio0pswjnm7 · Jun 24, 00:28 · [Discussion](https://news.ycombinator.com/item?id=48653575)

**Background**: Employee monitoring programs involve tracking activities like screen recording, keystrokes, or communication to assess productivity. Meta's program was reportedly used to evaluate performance but raised privacy issues. The leak underscores risks of such surveillance even within a company.

**Discussion**: Commenters expressed outrage and distrust, noting that if Meta monitors its own employees so invasively, users' data is even less safe. Some called the company 'shameless' and criticized its ethics, while others questioned the use of AI in securing the data.

**Tags**: `#privacy`, `#surveillance`, `#meta`, `#data leak`, `#employee monitoring`

---

<a id="item-12"></a>
## [Extreme Heat Conference Canceled Due to Heat Warning](https://www.lse.ac.uk/granthaminstitute/events/extreme-heat-improving-governance-and-strengthening-action-around-the-world/) ⭐️ 7.0/10

A conference on extreme heat governance, hosted by the Grantham Research Institute and the Zurich Climate Resilience Alliance, was canceled due to an extreme heat warning in London, with expected temperatures of 37–40°C. The cancellation underscores the irony and real-world gaps in climate adaptation, as even experts gather to discuss extreme heat while being vulnerable to it, highlighting the urgent need for better infrastructure and preparedness. The conference was scheduled for mid-July 2024 in London; the warning prompted the organizers to prioritize attendee safety. The event was meant to address governance and action for extreme heat globally.

hackernews · rendx · Jun 23, 23:26 · [Discussion](https://news.ycombinator.com/item?id=48653060)

**Background**: Extreme heat events are increasing in frequency and intensity due to climate change. Many regions, especially in Europe, lack widespread air conditioning and have buildings designed for cooler climates, making heatwaves particularly dangerous. The irony of a climate adaptation conference being disrupted by the very phenomenon it addresses highlights the challenge of adapting to rapidly changing conditions.

**Discussion**: Commenters pointed out the irony, with some noting the event included a 'fireside chat.' Others compared regional differences in heat preparedness, such as Australia's greater heat tolerance versus European infrastructure limitations. A few argued that Europeans are not sufficiently criticized for their resistance to air conditioning, citing higher heat-related death rates in Greece compared to US states.

**Tags**: `#climate change`, `#extreme weather`, `#irony`, `#adaptation`, `#conference`

---

<a id="item-13"></a>
## [Are model security risks tested in production?](https://www.reddit.com/r/MachineLearning/comments/1uddtws/are_model_security_risks_extraction_poisoning/) ⭐️ 7.0/10

A Reddit user highlighted that many ML teams skip adversarial testing for model extraction and poisoning before deploying models, raising concerns about security review gaps compared to traditional software. This oversight could expose deployed models to theft or manipulation, potentially leading to financial loss, biased outputs, or system compromise, especially as ML adoption grows in critical applications. Model extraction attacks duplicate a model through API queries, while model poisoning injects malicious data during training to alter behavior; both are well-documented threats that are often not tested in production environments.

reddit · r/MachineLearning · /u/Xorphian · Jun 23, 10:52

**Background**: Model security risks such as extraction and poisoning are distinct from traditional software vulnerabilities. Extraction allows attackers to steal intellectual property by querying a model's API, while poisoning can introduce backdoors or biases. Despite growing awareness, OWASP's ML Security Top 10 lists both as critical risks, yet security review practices lag behind those for conventional software.

<details><summary>References</summary>
<ul>
<li><a href="https://owasp.org/www-project-machine-learning-security-top-10/docs/ML10_2023-Model_Poisoning">OWASP Machine Learning Security Top Ten 2023 | ML10:2023 Model ...</a></li>
<li><a href="https://www.praetorian.com/blog/stealing-ai-models-through-the-api-a-practical-model-extraction-attack/">Stealing AI Models Through the API: A Practical Model Extraction Attack | Praetorian</a></li>
<li><a href="https://www.infoq.com/articles/understanding-ml-model-poisoning/">Understanding ML Model Poisoning: How It Happens and How to ... - InfoQ</a></li>

</ul>
</details>

**Tags**: `#ML security`, `#adversarial testing`, `#model extraction`, `#poisoning`, `#production deployment`

---

<a id="item-14"></a>
## [Hugging Face Revives Papers with Code with New Features](https://www.reddit.com/r/MachineLearning/comments/1ucm508/some_new_updates_to_papers_with_code_p/) ⭐️ 7.0/10

Hugging Face has added new features to Papers with Code, including SOTA badges that highlight papers in the top 3 for a benchmark, a trending score combining GitHub stars and Hugging Face artifact activity, support for external evaluations, and expanded benchmarks and tasks. These updates revive a key platform for machine learning research, making it easier to discover state-of-the-art results and track trending work, which fosters collaboration and building upon prior research. SOTA badges appear on any paper feed for benchmarks like PostTrainBench, and the trending score now also incorporates Hugging Face model, dataset, and Space popularity. External evals allow viewing third-party benchmark results not originally in the paper.

reddit · r/MachineLearning · /u/NielsRogge · Jun 22, 14:29

**Background**: Papers with Code is a platform that aggregates machine learning papers, code implementations, and benchmark results, helping researchers compare and build on each other's work. Hugging Face, a leading AI community hub, acquired Papers with Code and is now reviving it with new features to enhance research discovery.

<details><summary>References</summary>
<ul>
<li><a href="https://posttrainbench.com/?trk=public_post_comment-text">PostTrainBench</a></li>
<li><a href="https://llm-stats.com/benchmarks/posttrainbench">PostTrainBench Leaderboard | LLM Stats</a></li>
<li><a href="https://epoch.ai/benchmarks/post-train-bench">PostTrainBench | Epoch AI</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#research tools`, `#open source`, `#benchmarks`, `#papers with code`

---

<a id="item-15"></a>
## [Seeking Literature on Syntax-Robust NLI for Imperfect Text](https://www.reddit.com/r/MachineLearning/comments/1ucy7p3/syntactically_robust_nli_for_semantics_of/) ⭐️ 7.0/10

A Reddit user posted a question seeking literature on syntactically robust natural language inference (NLI) for evaluating semantically correct but syntactically noisy text generated by diffusion LLMs. This highlights a gap in current NLI methods, which are typically optimized for well-formed text, and could impact the evaluation and progress of diffusion-based language models that produce imperfect syntax. The user specifically mentions diffusion (D-) LLMs as opposed to autoregressive (AR) LLMs, and notes that aside from LLaDA, most current diffusion LLM outputs suffer from syntactic noise, complicating NLI usage.

reddit · r/MachineLearning · /u/RepresentativeBee600 · Jun 22, 21:51

**Background**: Natural language inference (NLI) determines the logical relationship (e.g., entailment, contradiction) between a premise and a hypothesis. Autoregressive LLMs generate text token-by-token, while diffusion LLMs iteratively denoise a sequence, often producing less syntactically fluent output. LLaDA is a notable diffusion LLM that achieves competitive performance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0950705124012425">Bridge to better understanding: Syntax extension with virtual linking-phrase for natural language inference - ScienceDirect</a></li>
<li><a href="https://people.cs.georgetown.edu/nschneid/p/amr4nli.pdf">AMR4NLI: Interpretable and robust NLI measures from semantic graphs Juri OpitzQ</a></li>
<li><a href="https://arxiv.org/abs/2502.09992">[2502.09992] Large Language Diffusion Models - arXiv.org</a></li>

</ul>
</details>

**Tags**: `#NLI`, `#diffusion LLMs`, `#syntax robustness`, `#natural language processing`, `#machine learning`

---

<a id="item-16"></a>
## [LLM Vulnerability Detection Benchmark Obfuscates Juliet Test Cases](https://www.reddit.com/r/MachineLearning/comments/1ud0rft/nondeterministic_vulnerability_detection/) ⭐️ 7.0/10

A new benchmark system, about 80% complete, obfuscates Juliet test cases to remove LLM advantages and injects comments (accurate, misleading, or neutral) to study their effect on vulnerability detection. This work addresses the known limitation of LLMs having an unfair advantage on standard CWE test cases, and introduces a novel dimension by manipulating comments to measure their impact on detection accuracy, which could lead to more realistic benchmarking of LLMs for security tasks. The benchmark includes hundreds of CWEs, uses LLM-injected comments in three sentiments, and still requires pruning of some CWEs that might be recognizable as Juliet code; remaining tasks include polishing presentation, benchmarking published LLMs, and final pruning.

reddit · r/MachineLearning · /u/Psychological_Meat_6 · Jun 22, 23:34

**Background**: The Juliet test suite is a widely-used collection of synthetic test cases for evaluating static analysis tools on known vulnerability types. The Common Weakness Enumeration (CWE) provides a standardized taxonomy for software weaknesses. LLMs have shown strong performance in detecting vulnerabilities in standard datasets, but concerns exist that they may rely on superficial patterns or dataset artifacts, motivating the need for more challenging and realistic benchmarks. This project attempts to address that by obfuscating the code structure and injecting comments that can either help or mislead the model.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Common_Weakness_Enumeration">Common Weakness Enumeration - Wikipedia</a></li>
<li><a href="https://elib.dlr.de/194605/1/2112.06623.pdf">Dataset for Exploring Juliet through the Lens of</a></li>
<li><a href="https://ieeexplore.ieee.org/document/9346306/">Fast Bug Detection Algorithm for Identifying Potential Vulnerabilities ...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#vulnerability detection`, `#benchmarking`, `#security`, `#AI`

---

<a id="item-17"></a>
## [uv 0.11.24 adds Python 3.15 beta, relocatable environments](https://github.com/astral-sh/uv/releases/tag/0.11.24) ⭐️ 6.0/10

uv 0.11.24 was released on June 23, 2026, adding support for CPython 3.15.0b3 and introducing preview support for relocatable project environments, along with performance improvements and bug fixes. This release allows Python developers to test the upcoming Python 3.15 beta with uv's fast dependency resolution, and the relocatable environments feature addresses a long-standing pain point of moving virtual environments between machines. It further solidifies uv's position as a modern, high-performance Python package manager. Relocatable environments are a preview feature that allows virtual environments to be moved or copied to different paths/machines by avoiding hardcoded paths in activation scripts and configuration. The release also uses a compact index for lazy version maps to improve package resolution performance.

github · github-actions[bot] · Jun 23, 21:16

**Background**: uv is a fast Python package manager written in Rust, designed as a replacement for pip and venv. Traditional Python virtual environments contain hardcoded absolute paths, making them difficult to relocate or share across machines. The relocatable feature, long requested by the community (e.g., issue #3587), aims to solve this by generating environments with relative paths. Python 3.15 is the next major version of Python, currently in beta, allowing early testing.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/astral-sh/uv/issues/3587">Add support for --relocatable · Issue #3587 · astral-sh/uv</a></li>
<li><a href="https://github.com/astral-sh/uv/issues/15751">Support portable mode: config lookup relative to uv binary & relocatable venv Python binaries · Issue #15751 · astral-sh/uv</a></li>

</ul>
</details>

**Tags**: `#python`, `#package-manager`, `#uv`, `#release`

---

<a id="item-18"></a>
## [Remembering Tony Krueger, the man behind spell-check squiggles](https://devblogs.microsoft.com/oldnewthing/20260622-00/?p=112451) ⭐️ 6.0/10

Raymond Chen's article pays tribute to Tony Krueger, the Microsoft engineer who pioneered the red and green squiggly underlines for real-time spell checking in word processors, a feature that became ubiquitous in software. This tribute highlights how a small user interface innovation can have a massive impact on how millions interact with text, changing the editing experience forever. It also serves as a reminder of the unsung engineers who shaped modern computing. Tony Krueger implemented the squiggly underlines in Microsoft Word to make spell checking unobtrusive, so it didn't interrupt the user's workflow. The red squiggles indicate potential spelling errors, while green squiggles indicate potential grammatical errors.

hackernews · saikatsg · Jun 23, 18:10 · [Discussion](https://news.ycombinator.com/item?id=48648959)

**Background**: Before real-time squiggly underlines, spell checkers required users to run a separate check that interrupted their typing. Tony Krueger's innovation at Microsoft made spell checking continuous and non-intrusive. The feature first appeared in Microsoft Word and later became a standard in word processors, browsers, and text editors.

<details><summary>References</summary>
<ul>
<li><a href="https://devblogs.microsoft.com/oldnewthing/20260622-00/?p=112451">In memory of the man who put red and green squiggles under ...</a></li>
<li><a href="https://learn.microsoft.com/en-us/answers/questions/5052879/can-you-shed-some-light-on-the-red-squiggly-lines">Can you shed some light on the red squiggly lines that ...</a></li>

</ul>
</details>

**Discussion**: Commenters shared mixed feelings: some appreciated the historical insight, while others criticized the squiggles' inaccuracy in multilingual contexts. One commenter wished such stories were shared before the person passed away, and another humorously suggested yellow squiggles for logic errors in code.

**Tags**: `#history`, `#spell check`, `#word processors`, `#computing history`, `#Raymond Chen`

---

<a id="item-19"></a>
## [Datasette 1.0a35 Alpha Adds Create/Alter Table APIs](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 6.0/10

Datasette 1.0a35 introduces a new Create table interface in the database actions menu, backed by a JSON API, and an Alter table interface for modifying existing tables, including add, rename, reorder, drop columns, change constraints, and rename table. This release significantly expands Datasette's capabilities, enabling users to modify database schemas directly from the web UI or via API, reducing the need for external tools. It positions Datasette as a more complete data management platform for SQLite databases. The Create table API supports defining columns, primary keys, custom column types, NOT NULL constraints, literal and expression defaults, and single-column foreign keys. The Alter table API includes a 'Drop table' button, also backed by an API. Additionally, the release includes new Template context documentation listing variables available for custom templates, treated as a stable API until Datasette 2.0.

rss · Simon Willison · Jun 23, 21:34

**Background**: Datasette is an open-source tool for exploring and publishing SQLite databases. It provides a web interface and a JSON API for querying data. Previously, creating or altering tables required using SQLite command-line tools or other SQL clients; now these operations are available directly through Datasette's UI and API.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Datasette">Datasette</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#database`, `#JSON API`, `#release`

---

<a id="item-20"></a>
## [Test harness for OPFS + Pyodide in Datasette Lite](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 6.0/10

Simon Willison built a test harness that combines Pyodide and the Origin Private File System (OPFS) to explore the possibility of editing persistent SQLite files from Datasette Lite running entirely in the browser. This experiment could enable full-featured data editing tools in the browser without server-side components, leveraging SQLite for local data persistence and Pyodide for running Python code. The test harness is a playground UI built with Claude Code for web, designed to test OPFS support across different browsers. Datasette Lite already runs the full Datasette application in the browser using Pyodide and WebAssembly.

rss · Simon Willison · Jun 23, 18:58

**Background**: Pyodide is a Python distribution for the browser and Node.js based on WebAssembly, allowing Python packages to run in browser environments. The Origin Private File System (OPFS) is a storage endpoint provided by the File System API that is private to the page's origin and optimized for performance. Datasette Lite is a version of the Datasette data exploration tool that runs entirely in the browser using Pyodide and WebAssembly.

<details><summary>References</summary>
<ul>
<li><a href="https://pyodide.org/">Pyodide — Version 314.0.0</a></li>
<li><a href="https://github.com/pyodide/pyodide">GitHub - pyodide/pyodide: Pyodide is a Python distribution for the ...</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://github.com/simonw/datasette-lite">GitHub - simonw/datasette-lite: Datasette running in your ...</a></li>

</ul>
</details>

**Tags**: `#pyodide`, `#opfs`, `#datasette-lite`, `#sqlite`, `#browsers`

---

<a id="item-21"></a>
## [Potential Mistake Found in ICLR 2026 Blogpost](https://www.reddit.com/r/MachineLearning/comments/1ud9i2g/found_a_potential_mistake_in_an_iclr_2026/) ⭐️ 6.0/10

A Reddit user reported a potential mistake in an ICLR 2026 blogpost and created a GitHub issue (#218) on the official blogpost track repository, but has received no response from authors or organizers for several weeks. This incident underscores the importance of open peer review for conference blogposts, as community verification can help catch errors before final publication. It also highlights potential gaps in responsiveness within the blogpost track's review process. The issue was filed at https://github.com/iclr-blogposts/2026/issues/218, but the original post lacks technical details about the alleged mistake. The user is seeking community feedback to confirm their understanding.

reddit · r/MachineLearning · /u/metalwhaledev · Jun 23, 06:39

**Background**: ICLR (International Conference on Learning Representations) runs a Blogposts Track where authors submit blog-style posts summarizing or critiquing ML research. These posts are hosted on a GitHub repository and are reviewed before acceptance. The track aims to make ML research more accessible and interactive.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/iclr-blogposts/2026">ICLR 2026 Blogposts Track - GitHub</a></li>
<li><a href="https://iclr-blog-track.github.io/submitting/">Submitting · The ICLR Blog Track</a></li>

</ul>
</details>

**Tags**: `#ICLR`, `#peer review`, `#blogpost`, `#mistake`, `#machine learning`

---