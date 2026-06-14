---
layout: default
title: "Horizon Summary: 2026-06-14 (EN)"
date: 2026-06-14
lang: en
---

> From 26 items, 14 important content pieces were selected

---

1. [Pyodide 314.0 Enables WASM Wheels on PyPI](#item-1) ⭐️ 9.0/10
2. [US Government Suspends Access to Anthropic's Fable 5 and Mythos 5](#item-2) ⭐️ 9.0/10
3. [2014 Talk Predicted JavaScript's Evolution into Compilation Target](#item-3) ⭐️ 8.0/10
4. [Honda Civic Infotainment Flaw Allows Code Execution via USB](#item-4) ⭐️ 8.0/10
5. [Mapping SQLite Result Columns to Source Tables](#item-5) ⭐️ 8.0/10
6. [Verifier Tax: Safety-Success Tradeoff in Tool-Using LLM Agents](#item-6) ⭐️ 8.0/10
7. [AI adoption is not universal despite hype](#item-7) ⭐️ 7.0/10
8. [Paul Graham on Earning a Billion Dollars](#item-8) ⭐️ 7.0/10
9. [Free SQL-to-ER diagram tool is browser-based and privacy-first](#item-9) ⭐️ 7.0/10
10. [OpenAI WebRTC audio playground updated with GPT-Realtime-2](#item-10) ⭐️ 7.0/10
11. [MDP Derivative-Free Optimization Outperforms Adam on MNIST](#item-11) ⭐️ 7.0/10
12. [Satirical Quote Mocks AI Startup Economics](#item-12) ⭐️ 6.0/10
13. [Bilingual ML Notebook Course Seeks Feedback](#item-13) ⭐️ 6.0/10
14. [PaddleOCR C++ Implementation with ncnn](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pyodide 314.0 Enables WASM Wheels on PyPI](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 9.0/10

Pyodide 314.0 allows Python package maintainers to publish WebAssembly (WASM) wheels directly to PyPI using the PyEmscripten platform tag defined in PEP 783. Previously, Pyodide core developers had to build and host over 300 packages themselves, creating a maintenance bottleneck. This change significantly reduces the maintenance burden on Pyodide developers and opens the door for community contributions, as any package author can now distribute WASM-compatible wheels. It strengthens the WebAssembly Python ecosystem, making Python in the browser more viable for a broader range of applications. The new platform tag is `pyemscripten_2026_0_wasm32`, and wheels built for it can be installed via `micropip` in Pyodide. The PyPI pull request enabling this support was merged on April 21, and tools like `cibuildwheel` now support building for this target.

rss · Simon Willison · Jun 13, 23:55

**Background**: Pyodide is a Python runtime for the browser, powered by WebAssembly. Previously, distributing Python packages with C or Rust extensions for Pyodide required manual compilation and hosting by the Pyodide team. PEP 783 formalized the PyEmscripten platform, allowing standard Python packaging tools to target WebAssembly, similar to how they target Linux, macOS, or Windows.

<details><summary>References</summary>
<ul>
<li><a href="https://pyodide.org/en/latest/development/abi.html">The PyEmscripten Platform — Version 314.0.0a2 - Pyodide</a></li>
<li><a href="https://peps.python.org/pep-0783/">PEP 783 – Emscripten Packaging - Python Enhancement Proposals</a></li>
<li><a href="https://pyodide.org/en/stable/development/abi/314.html">pyemscripten_2026_0 (under development) — Version 314.0.0</a></li>

</ul>
</details>

**Tags**: `#Pyodide`, `#WebAssembly`, `#PyPI`, `#Python packaging`, `#WASM`

---

<a id="item-2"></a>
## [US Government Suspends Access to Anthropic's Fable 5 and Mythos 5](https://simonwillison.net/2026/Jun/13/us-government-directive-to-suspend-access/#atom-everything) ⭐️ 9.0/10

The US government issued an export control directive suspending all access to Anthropic's Fable 5 and Mythos 5 AI models, citing national security concerns over a potential jailbreak method. Access was abruptly disabled for all customers on June 12, 2026. This is the first time a government has used export controls to halt access to a frontier AI model, setting a notable precedent for AI regulation. It raises concerns about government overreach and the potential impact on AI development, competition, and international tech policy. The directive targets all foreign nationals, including Anthropic employees, and the company had to disable the models for all customers to comply. Anthropic disputes the severity, stating the vulnerabilities are minor and also present in other publicly available models like GPT-5.5.

rss · Simon Willison · Jun 13, 01:01

**Background**: AI jailbreaks are techniques that bypass the safety guardrails of AI systems, potentially allowing malicious use. Fable 5 is Anthropic's most advanced model, part of the 'Mythos-class' tier, and was released just days before the directive. The US government has been tightening AI-related export controls, but this action marks the first time access to a model itself has been restricted rather than hardware or software exports.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.ibm.com/think/insights/ai-jailbreak">AI Jailbreak - IBM</a></li>
<li><a href="https://www.whitehouse.gov/presidential-actions/2025/07/promoting-the-export-of-the-american-ai-technology-stack/">Promoting The Export of the American AI Technology Stack</a></li>

</ul>
</details>

**Tags**: `#AI`, `#government regulation`, `#national security`, `#export control`, `#Anthropic`

---

<a id="item-3"></a>
## [2014 Talk Predicted JavaScript's Evolution into Compilation Target](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) ⭐️ 8.0/10

A 2014 talk titled 'The Birth and Death of JavaScript' accurately predicted that JavaScript would evolve into a compilation target for other languages, a vision now realized with WebAssembly. This prediction highlights the shift from JavaScript as a primary web language to a low-level compilation target, enabling near-native performance in browsers. The talk's accuracy underscores the prescience of early web technology thinkers and validates the trajectory of modern web development. The talk specifically foresaw asm.js, a strict subset of JavaScript, as the first step, which was later succeeded by WebAssembly. However, asm.js has since been deprecated in modern browsers, and WebAssembly still lacks direct DOM manipulation, requiring JavaScript as glue code.

hackernews · subset · Jun 14, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48526661)

**Background**: Asm.js is a low-level subset of JavaScript designed as a compilation target for languages like C and C++, enabling near-native performance in browsers via ahead-of-time optimization. Emscripten, an LLVM/Clang-based compiler, compiles C/C++ code to asm.js or WebAssembly. WebAssembly (Wasm) is a binary instruction format that superseded asm.js, now supported natively in all major browsers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">Asm.js</a></li>
<li><a href="https://en.wikipedia.org/wiki/Emscripten">Emscripten</a></li>

</ul>
</details>

**Discussion**: Community comments largely agree that the talk's core prediction was accurate, noting that asm.js and later WebAssembly fulfilled it. Some users point out that WebAssembly still needs JavaScript for DOM manipulation and is not evolving as fast as hoped. Others highlight that the talk also jokingly predicted a global disaster between 2020-2025, which resonated due to recent events.

**Tags**: `#JavaScript`, `#WebAssembly`, `#programming languages`, `#web development`, `#future of computing`

---

<a id="item-4"></a>
## [Honda Civic Infotainment Flaw Allows Code Execution via USB](https://juniperspring.org/posts/honda-evil-valet/) ⭐️ 8.0/10

A security researcher reverse-engineered the update process for 10th-generation Honda Civic infotainment systems and found that Honda uses publicly known AOSP test keys to sign firmware updates, enabling arbitrary code execution from a specially crafted USB drive. This vulnerability could allow an attacker with physical access to the car's USB port to install malicious software, potentially compromising the infotainment system and its connected components like microphones and GPS. It highlights broader security concerns in automotive infotainment systems. The update packages are essentially Android 4.2.2 recovery images with Honda-specific version checks that can be spoofed. The use of default AOSP test keys means anyone can sign their own package without needing to exploit a root vulnerability.

hackernews · librick · Jun 14, 00:49 · [Discussion](https://news.ycombinator.com/item?id=48523080)

**Background**: AOSP (Android Open Source Project) provides default test keys for development purposes, which are not meant for production use. Many manufacturers use Android-based infotainment systems, and if they do not replace these test keys with their own secure keys, the update mechanism becomes insecure against physical access attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/wfairclough/android_aosp_keys">GitHub - wfairclough/android_ aosp _ keys : The platform keys that are...</a></li>

</ul>
</details>

**Discussion**: Commenters debated the practical risk, noting that an attacker with physical access could just hide a listening device instead. Others appreciated the openness, arguing that it allows users to modify their own infotainment systems long-term, and that security concerns should be balanced against user freedom.

**Tags**: `#reverse-engineering`, `#automotive security`, `#infotainment`, `#Honda`, `#Android`

---

<a id="item-5"></a>
## [Mapping SQLite Result Columns to Source Tables](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 8.0/10

Simon Willison explored methods to programmatically map SQL query result columns back to their source table.column, using Claude Code to identify solutions including apsw, ctypes access to sqlite3_column_table_name(), and EXPLAIN analysis. This research could enable tools like Datasette to enrich query results with column provenance information, improving data exploration and debugging. The novel use of AI-assisted programming (Claude Code) to tackle a tricky database problem showcases a new approach to technical problem-solving. Claude Code (Opus 4.8) was used because Fable was banned by the US government at the time. The three identified methods are: using the apsw library, calling the C function sqlite3_column_table_name() via ctypes, and parsing EXPLAIN output.

rss · Simon Willison · Jun 13, 23:05

**Background**: SQL column provenance refers to the ability to determine which table and column a result value originates from. This is not directly exposed in Python's sqlite3 module. Datasette is an open-source tool for exploring and publishing relational databases, and Simon Willison is its creator.

<details><summary>References</summary>
<ul>
<li><a href="https://sqlite.org/c3ref/table_column_metadata.html">Extract Metadata About A Column Of A Table</a></li>
<li><a href="https://code.claude.com/docs/en/overview">Overview - Claude Code Docs</a></li>

</ul>
</details>

**Tags**: `#SQL`, `#Datasette`, `#column provenance`, `#AI-assisted programming`, `#database`

---

<a id="item-6"></a>
## [Verifier Tax: Safety-Success Tradeoff in Tool-Using LLM Agents](https://www.reddit.com/r/MachineLearning/comments/1u58mkq/the_verifier_tax_horizondependent_safetysuccess/) ⭐️ 8.0/10

The paper introduces the Verifier Tax, a horizon-dependent safety-success tradeoff in tool-using LLM agents, and proposes a two-tier verification architecture combining deterministic policy checks with an LLM-based verifier. This research reveals a fundamental tension in AI agent safety: verification can reduce unsafe success but also lowers task completion, especially as task horizon increases, forcing a tradeoff that must be considered in agent evaluation. The study uses τ-bench tool-use scenarios, categorizing agent outcomes into safe success, unsafe success, and failure, and finds that verification reduces unsafe success but imposes a 'tax' on task completion that grows with horizon.

reddit · r/MachineLearning · /u/AccomplishedLeg1508 · Jun 14, 02:09

**Background**: Tool-using LLM agents can complete tasks while violating safety policies, a scenario called 'unsafe success'. The τ-bench benchmark evaluates agents in dynamic tool-use environments requiring both task completion and policy adherence. The Verifier Tax concept emerges from the observation that verification systems, while reducing unsafe success, can also inadvertently hinder task completion over long horizons.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2603.19328">The Verifier Tax : Horizon Dependent Safety Success Tradeoffs in...</a></li>
<li><a href="https://www.linkedin.com/posts/tanmay-sah_the-verifier-tax-horizon-dependent-safetysuccess-activity-7462840811387256834-LAdv">The Verifier Tax : Horizon Dependent Safety – Success Tradeoffs in...</a></li>
<li><a href="https://github.com/sierra-research/tau-bench">GitHub - sierra-research/ tau - bench : Code and Data for Tau - Bench</a></li>

</ul>
</details>

**Tags**: `#LLM agents`, `#AI safety`, `#verification`, `#tool use`

---

<a id="item-7"></a>
## [AI adoption is not universal despite hype](https://gabrielweinberg.com/p/people-are-consuming-ai-like-they) ⭐️ 7.0/10

The article argues that contrary to the perception that everyone is using AI, adoption varies widely, with many people and companies either limiting or avoiding AI entirely. This matters because it challenges the dominant AI hype narrative, reminding product builders and job seekers that not everyone is onboard, which affects product strategy, interview responses, and system design decisions. The article highlights specific situations like job interviews where candidates feel pressured to hedge their AI usage, and companies replacing deterministic systems with slower, less reliable LLM versions.

hackernews · yegg · Jun 14, 14:44 · [Discussion](https://news.ycombinator.com/item?id=48527700)

**Background**: AI has been aggressively marketed and covered in media, leading to a perception that it is universally adopted. However, real-world adoption is uneven, with many professionals and companies cautious due to concerns about reliability, cost, and integration challenges.

**Discussion**: Commenters shared mixed experiences: some noted the difficulty of answering LLM usage questions in job interviews, while others observed companies replacing deterministic systems with inferior AI solutions. The meat consumption analogy was also discussed, highlighting that even with drawbacks, adoption can grow over time.

**Tags**: `#AI adoption`, `#technology hype`, `#software engineering`, `#HackerNews discussion`

---

<a id="item-8"></a>
## [Paul Graham on Earning a Billion Dollars](https://paulgraham.com/earn.html) ⭐️ 7.0/10

Paul Graham's essay argues that earning a billion dollars is achievable through rapid business growth and innovation, countering the claim that one cannot earn such wealth through work alone. He emphasizes that creating something worth a billion dollars and then selling it is a realistic path. This essay sparks debate on the limits of wealth acquisition and the moral hazards of billion-dollar enterprises, challenging assumptions about exploitation and externalities. It is significant for entrepreneurs, investors, and economists discussing wealth creation and inequality. Graham counters the view that billion-dollar fortunes require exploitation, focusing instead on growth, efficiency, and market creation. Community comments point out that such wealth often involves structures that generate externalities not borne by the founder, and that moral hazard may justify limits on wealth accumulation.

hackernews · kingstoned · Jun 14, 11:50 · [Discussion](https://news.ycombinator.com/item?id=48526360)

**Background**: Paul Graham is a well-known essayist, venture capitalist, and co-founder of Y Combinator. His essays often explore startup culture, wealth creation, and technology. The term 'billion dollars' in business usually refers to company valuation or exit value, not liquid cash earned from salary.

**Discussion**: Comments criticize Graham for dodging the moral hazard and externalities of billion-dollar enterprises, arguing that such wealth is typically extracted through structures that impose costs on society. Some agree that creative destruction is net positive but acknowledge moral entanglement with destruction, such as Uber displacing taxi drivers.

**Tags**: `#wealth`, `#entrepreneurship`, `#Paul Graham`, `#economics`, `#moral hazard`

---

<a id="item-9"></a>
## [Free SQL-to-ER diagram tool is browser-based and privacy-first](https://sqltoerdiagram.com/) ⭐️ 7.0/10

A new free tool, sqltoerdiagram.com, converts SQL CREATE TABLE statements into entity-relationship diagrams entirely in the browser with no server upload. This tool addresses a common pain point for developers who need to visualize database schemas but want to avoid paywalls, signups, or data privacy risks. Its client-side architecture ensures sensitive SQL never leaves the user's machine. The diagram is rendered using <canvas> with rasterized table bitmaps and viewport culling for performance. Unlike traditional ER diagrams, this tool generates a table-relationship diagram rather than a true entity-relationship diagram, as noted by a commenter.

hackernews · robhati · Jun 14, 03:43 · [Discussion](https://news.ycombinator.com/item?id=48523992)

**Background**: An entity-relationship diagram (ERD) is a visual representation of database entities and their relationships. Traditional ER diagrams distinguish between entities and tables, but many tools blur this line. This tool prioritizes ease-of-use and privacy by running all processing in the browser without any backend.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Entity–relationship_model">Entity–relationship model - Wikipedia</a></li>
<li><a href="https://www.lucidchart.com/pages/er-diagrams">What is an Entity Relationship Diagram (ERD)? - Lucidchart</a></li>

</ul>
</details>

**Discussion**: Commenters praised the tool's mobile usability and smooth pan/zoom experience. One user noted it's analogous to a query plan visualizer, while another requested options for straight lines and 90-degree angles. A pedantic comment pointed out that the output is a table-relationship diagram rather than a true ER diagram.

**Tags**: `#SQL`, `#database`, `#ER-diagram`, `#visualization`, `#privacy`

---

<a id="item-10"></a>
## [OpenAI WebRTC audio playground updated with GPT-Realtime-2](https://simonwillison.net/2026/Jun/12/openai-webrtc/#atom-everything) ⭐️ 7.0/10

Simon Willison updated his OpenAI WebRTC audio session playground to support the new GPT-Realtime-2 model and document context, enabling voice conversations about user-provided text. This demonstrates practical use of OpenAI's latest voice model with GPT-5-class reasoning, and shows how developers can build more interactive voice applications with document context. The model used is GPT-Realtime-2, which has a knowledge cutoff of September 30, 2024. The playground allows users to select the model, voice, and paste document context before starting a session.

rss · Simon Willison · Jun 12, 23:53

**Background**: WebRTC (Web Real-Time Communication) is a technology for low-latency audio/video communication in browsers. OpenAI's Realtime API enables voice interactions with AI models using WebRTC. GPT-Realtime-2 is OpenAI's most advanced voice model, offering GPT-5-class reasoning.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.openai.com/api/docs/models/gpt-realtime-2">GPT-Realtime-2 Model | OpenAI API</a></li>
<li><a href="https://developers.openai.com/api/docs/guides/realtime-webrtc">Realtime API with WebRTC | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#WebRTC`, `#audio`, `#API`, `#development`

---

<a id="item-11"></a>
## [MDP Derivative-Free Optimization Outperforms Adam on MNIST](https://www.reddit.com/r/MachineLearning/comments/1u4fc16/derivativefree_neural_network_optimization_mnist/) ⭐️ 7.0/10

A derivative-free optimization method called MDP achieved 93.4% test accuracy on MNIST classification, outperforming Adam's 91.7% using the same 784-32-10 network architecture. This result demonstrates that derivative-free optimization can compete with gradient-based methods on small-scale neural network tasks, potentially offering a viable alternative when gradients are unavailable or expensive to compute. The network had 25,450 parameters trained on 5,000 images; MDP achieved a cross-entropy loss of 0.0004083 versus Adam's 0.002945 after 1 million function evaluations without gradients.

reddit · r/MachineLearning · /u/Mis4318 · Jun 13, 02:51

**Background**: Derivative-free optimization (DFO) is a class of optimization methods that do not use gradient information, making them suitable for black-box functions. MNIST is a standard benchmark dataset for handwritten digit recognition. Adam is a widely used gradient-based optimizer for training neural networks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Derivative-free_optimization">Derivative-free optimization - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Neural Networks`, `#Optimization`, `#Derivative-Free`, `#MNIST`, `#Machine Learning`

---

<a id="item-12"></a>
## [Satirical Quote Mocks AI Startup Economics](https://simonwillison.net/2026/Jun/12/andrew-singleton/#atom-everything) ⭐️ 6.0/10

Andrew Singleton published a satirical piece on McSweeney's titled 'AI Economics for Dummies,' using a fictional story about a crematorium and a propane company to parody the circular investments and inflated valuations common in AI startups. This satire highlights the absurdity of money-losing AI startups achieving massive valuations through circular transactions, reflecting growing skepticism about the sustainability of AI investment hype. The story involves Jenny's crematorium receiving a $20 billion investment from John's propane company for 5% equity, then burning $10 billion cash and buying $10 billion propane to burn the money—generating $10 billion in reported revenue and a $100 billion valuation.

rss · Simon Willison · Jun 12, 18:09

**Background**: AI startup funding has seen a surge, with companies raising billions despite lacking clear revenue models. Critics argue that investments often flow in circular ways, where one startup buys services from another, inflating reported revenues and valuations without real economic value creation.

**Tags**: `#AI`, `#economics`, `#satire`, `#criticism`, `#startup culture`

---

<a id="item-13"></a>
## [Bilingual ML Notebook Course Seeks Feedback](https://www.reddit.com/r/MachineLearning/comments/1u4zbld/im_building_a_free_bilingual_machinelearning/) ⭐️ 6.0/10

The creator of the open-source repository 'Machine_Learning_Tutorials' is requesting community feedback on a free bilingual (English and Persian) Jupyter notebook machine learning course covering topics from foundations to MLOps. This project lowers the barrier for Persian-speaking learners to access high-quality ML education, and the community feedback approach helps tailor the curriculum to actual needs. It also serves as a model for creating inclusive, multilingual open-source educational resources. The repository currently includes notebooks organized by topic, with parallel English and Persian versions. Key areas cover ML foundations, data cleaning, regression/classification, ensembles, clustering, dimensionality reduction, evaluation, time series, anomaly detection, responsible ML, and MLOps. The creator specifically asks for feedback on chapter order, missing classical ML topics, practical notebook design, and bilingual usefulness.

reddit · r/MachineLearning · /u/abolfazl1363 · Jun 13, 19:07

**Background**: MLOps (Machine Learning Operations) is a paradigm that applies DevOps principles to the ML lifecycle, aiming to automate and streamline model deployment, monitoring, and governance. Responsible ML focuses on ensuring fairness, accountability, transparency, and privacy in machine learning systems. These topics have become increasingly important as ML moves from research to production, and including them in an introductory course helps learners understand the full lifecycle and ethical considerations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MLOps">MLOps</a></li>
<li><a href="https://aws.amazon.com/what-is/mlops/">What is MLOps? - Machine Learning Operations Explained - AWS</a></li>
<li><a href="https://www.oreilly.com/library/view/responsible-machine-learning/9781492090878/">Responsible Machine Learning [Book]</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#education`, `#open source`, `#jupyter notebooks`, `#bilingual`

---

<a id="item-14"></a>
## [PaddleOCR C++ Implementation with ncnn](https://www.reddit.com/r/MachineLearning/comments/1u4hy2x/paddleocr_v3v4v5v6_implemented_in_c_with_ncnn_p/) ⭐️ 6.0/10

A developer has updated their open-source PaddleOCR implementation in C++ to support PP-OCR models from version 3 to the latest version 6, using the lightweight ncnn inference framework instead of the official Paddle C++ runtime. This reduces deployment complexity significantly, as the official Paddle C++ runtime has many dependencies and is hard to integrate. Using ncnn makes OCR inference lightweight and faster on resource-constrained devices like mobile phones and embedded systems. The implementation now covers PP-OCR models v3, v4, v5, and v6. The author reports that ncnn is lighter and faster for their specific task compared to the official runtime.

reddit · r/MachineLearning · /u/Knok0932 · Jun 13, 05:06

**Background**: PaddleOCR is an OCR toolkit based on PaddlePaddle, supporting text detection and recognition. The official C++ inference runtime requires many dependencies, making deployment cumbersome, especially on edge devices. ncnn is a high-performance neural network inference framework optimized for mobile and embedded platforms, designed to be lightweight and dependency-free.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.gopenai.com/yolo-models-on-ncnn-faster-or-slower-a-technical-breakdown-03d36612c921">YOLO on NCNN : Optimize Performance for Faster Inference | GoPenAI</a></li>
<li><a href="https://github.com/leeroopedia/workflow-tencent-ncnn-image-classification-inference">leeroopedia/workflow-tencent- ncnn -image-classification- inference ...</a></li>

</ul>
</details>

**Tags**: `#OCR`, `#C++`, `#ncnn`, `#PaddleOCR`, `#deployment`

---