# Awesome AutoResearch [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![Awesome AutoResearch](preface.png)

> A curated list of AutoResearch tools and frameworks that can autonomously conduct research, design experiments, analyze data, write papers, and generate scientific discoveries.

[AutoResearch](https://edisonscientific.com/articles/announcing-kosmos) represents a new paradigm in scientific discovery where AI systems can perform the complete research lifecycle - from hypothesis generation to peer review - with minimal or no human intervention. These systems leverage large language models and multi-agent frameworks to accelerate scientific progress across multiple domains.

## Open-source Research Agents & Tools

Projects are grouped by their primary function in the research workflow. Ecosystem-specific repos such as OpenClaw tools are folded into the same functional taxonomy instead of being split into a separate section.

### Benchmarks & Evaluation

Benchmarks and evaluation suites for measuring capabilities of autonomous research agents across tasks.

- [AIRS-Bench](https://github.com/facebookresearch/airs-bench) ![](https://img.shields.io/github/stars/facebookresearch/airs-bench.svg?cacheSeconds=172800) - Benchmark by Meta FAIR for quantifying end-to-end AI research abilities of LLM agents.
- [BixBench](https://github.com/Future-House/BixBench) ![](https://img.shields.io/github/stars/Future-House/BixBench.svg?cacheSeconds=172800) - Benchmark for LLM-based agents on verifiable computational biology and bioinformatics tasks.
- [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) ![](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench.svg?cacheSeconds=172800) - Comprehensive benchmark and leaderboard for evaluating deep research agents.
- [MLGym](https://github.com/facebookresearch/MLGym) ![](https://img.shields.io/github/stars/facebookresearch/MLGym.svg?cacheSeconds=172800) - Unified framework and benchmark by Meta FAIR for developing and evaluating AI research agents across ML tasks.
- [ScholarEval](https://github.com/skai-research/ScholarEval) ![](https://img.shields.io/github/stars/skai-research/ScholarEval.svg?cacheSeconds=172800) - Literature-grounded framework for evaluating research ideas with multi-dimensional quality criteria.
- [scienceboard](https://github.com/Agni-bot/scienceboard) ![](https://img.shields.io/github/stars/Agni-bot/scienceboard.svg?cacheSeconds=172800) - VM-based benchmark for evaluating multimodal autonomous agents on realistic scientific workflows.

### Deep Research Agents

Research-focused agents for iterative retrieval, synthesis, and report generation on complex questions.

- [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) ![](https://img.shields.io/github/stars/HKUDS/Auto-Deep-Research.svg?cacheSeconds=172800) - Open-source, cost-efficient alternative to OpenAI's Deep Research with universal LLM compatibility and strong GAIA Benchmark results.
- [Caesar](https://github.com/jasonzliang/caesar-agent) ![](https://img.shields.io/github/stars/jasonzliang/caesar-agent.svg?cacheSeconds=172800) - Builds a knowledge graph during web exploration, then refines drafts through adversarial synthesis that targets gaps in the previous draft.
- [DeerFlow](https://github.com/bytedance/deer-flow) ![](https://img.shields.io/github/stars/bytedance/deer-flow.svg?cacheSeconds=172800) - ByteDance's deep research workflow agent combining web search, code execution, and multi-step reasoning for complex research tasks.
- [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) ![](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch.svg?cacheSeconds=172800) - Tongyi Deep Research — iterative retrieval-augmented research agent for complex multi-hop questions.
- [DeepResearchAgent](https://github.com/SkyworkAI/DeepResearchAgent) ![](https://img.shields.io/github/stars/SkyworkAI/DeepResearchAgent.svg?cacheSeconds=172800) - Skywork AI's deep research agent for thorough multi-source web research and report synthesis.
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) ![](https://img.shields.io/github/stars/assafelovic/gpt-researcher.svg?cacheSeconds=172800) - Autonomous agent that conducts deep online research on any topic, producing detailed, factual reports with citations.
- [local-deep-research](https://github.com/LearningCircuit/local-deep-research) ![](https://img.shields.io/github/stars/LearningCircuit/local-deep-research.svg?cacheSeconds=172800) - Local-first deep research agent reaching ~95% on SimpleQA with local LLMs, integrating arXiv, PubMed, Semantic Scholar, Wikipedia, and 10+ sources with encrypted storage.
- [Open Deep Research](https://github.com/langchain-ai/open_deep_research) ![](https://img.shields.io/github/stars/langchain-ai/open_deep_research.svg?cacheSeconds=172800) - Fully open-source deep research agent with multi-model support, multi-search API, MCP integration, and built-in report generation.
- [OpenResearcher](https://github.com/TIGER-AI-Lab/OpenResearcher) ![](https://img.shields.io/github/stars/TIGER-AI-Lab/OpenResearcher.svg?cacheSeconds=172800) - Fully open training and inference pipeline for long-horizon deep research, releasing a 30B-A3B model that surpasses GPT-4.1 and Claude Opus 4 on BrowseComp-Plus.

### Literature Synthesis & QA

Tools focused on grounded question answering and literature synthesis over scientific sources.

- [Lune Research](https://github.com/RetrogradeLabs/lune-mcp-server) ![](https://img.shields.io/github/stars/RetrogradeLabs/lune-mcp-server.svg?cacheSeconds=172800) - MCP server for full-text search over peer-reviewed computer-science papers, citation traversal, structured evidence extraction, and claim verification against verbatim quotes.
- [OpenScholar](https://github.com/AkariAsai/OpenScholar) ![](https://img.shields.io/github/stars/AkariAsai/OpenScholar.svg?cacheSeconds=172800) - Retrieval-augmented language model that synthesizes scientific literature by grounding responses in relevant paper evidence.
- [PaperQA2](https://github.com/Future-House/paper-qa) ![](https://img.shields.io/github/stars/Future-House/paper-qa.svg?cacheSeconds=172800) - High-accuracy retrieval-augmented QA over scientific PDFs, demonstrating superhuman synthesis of scientific knowledge.
- [STORM](https://github.com/stanford-oval/storm) ![](https://img.shields.io/github/stars/stanford-oval/storm.svg?cacheSeconds=172800) - Stanford system for synthesizing Wikipedia-style long-form articles through multi-perspective question asking and retrieval.

### Paper Discovery & Monitoring

Tools for surfacing, recommending, and tracking new papers.

- [daily-paper-reader](https://github.com/ziwenhahaha/daily-paper-reader) ![](https://img.shields.io/github/stars/ziwenhahaha/daily-paper-reader.svg?cacheSeconds=172800) - Daily arXiv/OpenReview paper recommendation and AI reading platform with GitHub Actions automation and GitHub Pages deployment.
- [PaperVault](https://github.com/youngfish42/PaperVault) ![](https://img.shields.io/github/stars/youngfish42/PaperVault.svg?cacheSeconds=172800) - Auto-updating paper metadata database and web search platform covering top venues across major computer science fields.
- [zotero-arxiv-daily](https://github.com/TideDra/zotero-arxiv-daily) ![](https://img.shields.io/github/stars/TideDra/zotero-arxiv-daily.svg?cacheSeconds=172800) - Daily arXiv recommender that matches new papers to your Zotero library and sends personalized recommendations.

### Paper Reading, Annotation & Review

Tools for paper summarization, grounded reading, annotation, and review workflows.

- [ChatPaper](https://github.com/kaixindelele/ChatPaper) ![](https://img.shields.io/github/stars/kaixindelele/ChatPaper.svg?cacheSeconds=172800) - Uses ChatGPT to summarize arXiv papers, with professional translation, paper polishing, peer review analysis, and reviewer response generation.
- [ChatReviewer](https://github.com/nishiwen1214/ChatReviewer) ![](https://img.shields.io/github/stars/nishiwen1214/ChatReviewer.svg?cacheSeconds=172800) - Uses ChatGPT to analyze paper strengths/weaknesses, provide improvement suggestions, and auto-generate reviewer responses.
- [FactReview](https://github.com/DEFENSE-SEU/FactReview) ![](https://img.shields.io/github/stars/DEFENSE-SEU/FactReview.svg?cacheSeconds=172800) - Evidence-grounded ML paper review system that tags claim verdicts, positions literature, and supports execution-based verification.
- [OpenAIReview](https://github.com/ChicagoHAI/OpenAIReview) ![](https://img.shields.io/github/stars/ChicagoHAI/OpenAIReview.svg?cacheSeconds=172800) - LLM-assisted paper review toolkit that generates detailed draft feedback with multi-engine PDF extraction.
- [openpaper](https://github.com/khoj-ai/openpaper) ![](https://img.shields.io/github/stars/khoj-ai/openpaper.svg?cacheSeconds=172800) - Research paper reading and annotation workspace with an AI copilot for grounded Q&A over personal libraries.
- [paper_online](https://github.com/KMnO4-zx/paper_online) ![](https://img.shields.io/github/stars/KMnO4-zx/paper_online.svg?cacheSeconds=172800) - AI-driven paper insight and intelligent analysis platform for quickly screening academic papers.

### End-to-End Autonomous Research Systems

Autonomous systems that cover the full research lifecycle from ideation through experimentation and synthesis.

- [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) ![](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory.svg?cacheSeconds=172800) - End-to-end autonomous research workflow using LLM agents to assist with literature reviews, experiments, and report writing.
- [Agon](https://github.com/AutoResearch-Factory/Agon) ![](https://img.shields.io/github/stars/AutoResearch-Factory/Agon.svg?cacheSeconds=172800) - Claude Code plugin for topic-to-idea-to-proposal-to-experiment research loops.
- [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ![](https://img.shields.io/github/stars/HKUDS/AI-Researcher.svg?cacheSeconds=172800) - Autonomous scientific innovation system with dedicated research and paper agents for idea generation, experiment execution, and paper writing.
- [AI-Scientist](https://github.com/SakanaAI/AI-Scientist) ![](https://img.shields.io/github/stars/SakanaAI/AI-Scientist.svg?cacheSeconds=172800) - First comprehensive system for fully automatic scientific discovery, enabling LLMs to autonomously generate ideas, run experiments, and write papers.
- [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) ![](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2.svg?cacheSeconds=172800) - An autonomous AI research agent that employs agentic tree search for workshop-level scientific discovery, extending AI-Scientist with stronger experimental control and iterative hypothesis refinement.
- [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ![](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep.svg?cacheSeconds=172800) - Lightweight Markdown-only research workflow with cross-model review loops, idea discovery, and experiment automation.
- [auto-research](https://github.com/openags/auto-research) ![](https://img.shields.io/github/stars/openags/auto-research.svg?cacheSeconds=172800) - Autonomous generalist scientist framework for fully automated research agents from literature reviews to experiments and writing.
- [autoresearch](https://github.com/karpathy/autoresearch) ![](https://img.shields.io/github/stars/karpathy/autoresearch.svg?cacheSeconds=172800) - Karpathy's autonomous overnight research loop where agents iteratively edit/train/evaluate a compact LLM setup under a fixed 5-minute experiment budget.
- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) ![](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw.svg?cacheSeconds=172800) - Fully autonomous & self-evolving research from idea to paper using a multi-agent debate pipeline with self-healing and citation verification.
- [Biomni](https://github.com/snap-stanford/Biomni) ![](https://img.shields.io/github/stars/snap-stanford/Biomni.svg?cacheSeconds=172800) - Stanford's general-purpose biomedical AI agent that autonomously executes research tasks across biology and medicine, combining LLM reasoning, retrieval, and tool/code use.
- [claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar) ![](https://img.shields.io/github/stars/Galaxy-Dawn/claude-scholar.svg?cacheSeconds=172800) - Semi-automated academic research assistant covering ideation → coding → experiments → writing → publication using Claude Code or Codex CLI.
- [Curie](https://github.com/Just-Curieous/Curie) ![](https://img.shields.io/github/stars/Just-Curieous/Curie.svg?cacheSeconds=172800) - AI-agent framework for automated and rigorous scientific experimentation with end-to-end automation from hypothesis formulation to result interpretation.
- [DATAGEN](https://github.com/starpig1129/DATAGEN) ![](https://img.shields.io/github/stars/starpig1129/DATAGEN.svg?cacheSeconds=172800) - AI-driven multi-agent research assistant automating hypothesis generation, data analysis, visualization, and report writing via LangChain and LangGraph.
- [DeepScientist](https://github.com/ResearAI/DeepScientist) ![](https://img.shields.io/github/stars/ResearAI/DeepScientist.svg?cacheSeconds=172800) - Local-first autonomous research studio with Findings Memory and Bayesian optimization orchestrating baseline reproduction → branched experiments → LaTeX paper drafts.
- [EvoScientist](https://github.com/EvoScientist/EvoScientist) ![](https://img.shields.io/github/stars/EvoScientist/EvoScientist.svg?cacheSeconds=172800) - Self-evolving AI Scientists with a six-agent team and persistent memory for autonomous iterative research exploration.
- [InternAgent](https://github.com/InternScience/InternAgent) ![](https://img.shields.io/github/stars/InternScience/InternAgent.svg?cacheSeconds=172800) - Shanghai AI Lab's unified agentic framework for long-horizon autonomous discovery across physics, biology, earth, and life sciences.
- [nano-scientist](https://github.com/AI4Scientist/nano-scientist) ![](https://img.shields.io/github/stars/AI4Scientist/nano-scientist.svg?cacheSeconds=172800) - Budget-driven autonomous research agent that turns a topic into a technical report with a plan-execute-review loop and PDF output pipeline.
- [NanoResearch](https://github.com/OpenRaiser/NanoResearch) ![](https://img.shields.io/github/stars/OpenRaiser/NanoResearch.svg?cacheSeconds=172800) - Lightweight end-to-end research automation agent with minimal setup requirements.
- [nanoresearch](https://github.com/saadmsft/nanoresearch) ![](https://img.shields.io/github/stars/saadmsft/nanoresearch.svg?cacheSeconds=172800) - Tri-level co-evolving multi-agent research automation system with chat-style interaction and field-agnostic workflows.
- [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) ![](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist.svg?cacheSeconds=172800) - AI Scientist ecosystem covering idea generation, experiment design, and paper writing as a holistic blueprint for autonomous research.
- [pi-autoresearch](https://github.com/davebcn87/pi-autoresearch) ![](https://img.shields.io/github/stars/davebcn87/pi-autoresearch.svg?cacheSeconds=172800) - Extension for the [pi](https://pi.dev) agent that enables autonomous experiment loops to benchmark ideas, keep improvements, and revert regressions.
- [QUIT](https://github.com/Mr-XcHan/QUIT) ![](https://img.shields.io/github/stars/Mr-XcHan/QUIT.svg?cacheSeconds=172800) - Human-in-the-loop research automation platform with an artifact-driven Query-Understand-Implement-Tell pipeline and optional end-to-end mode.
- [Researcher](https://github.com/zhu-minjun/Researcher) ![](https://img.shields.io/github/stars/zhu-minjun/Researcher.svg?cacheSeconds=172800) - AI-powered research assistant for automated research workflows.
- [Robin](https://github.com/Future-House/robin) ![](https://img.shields.io/github/stars/Future-House/robin.svg?cacheSeconds=172800) - Multi-agent system by FutureHouse for automating scientific discovery, demonstrated on real-world biomedical research tasks (Nature 2026).
- [Virtual Lab](https://github.com/zou-group/virtual-lab) ![](https://img.shields.io/github/stars/zou-group/virtual-lab.svg?cacheSeconds=172800) - AI agent team that autonomously designs novel SARS-CoV-2 nanobodies, demonstrating end-to-end wet-lab-integrated scientific discovery.
- [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) ![](https://img.shields.io/github/stars/InternScience/Virtual-Scientists.svg?cacheSeconds=172800) - ACL 2025 project featuring many-heads multi-agent scientific idea generation for diverse hypothesis exploration.
- [Writing-Driven Autoresearch](https://github.com/happyhappy-jun/writing-driven-autoresearch) ![](https://img.shields.io/github/stars/happyhappy-jun/writing-driven-autoresearch.svg?cacheSeconds=172800) - Multi-agent harness that keeps a submittable paper from minute zero and drives every experiment from the claims in that draft; 1st place at the [Ralphthon@ICML 2026](https://luma.com/hjuo7auc) autonomous-research hackathon.

### Research Platforms & IDEs

Integrated workspaces, research operating systems, and agent-native interfaces for day-to-day scientific workflows.

- [aiXiv](https://www.aixiv.co) ![](https://img.shields.io/github/stars/aixiv-org/aixiv-core.svg?cacheSeconds=172800) - Multi-agent preprint server for human, AI and robot scientists with dual-track review and auto-agents ecosystem.
- [AutoSci](https://github.com/skyllwt/AutoSci) ![](https://img.shields.io/github/stars/skyllwt/AutoSci.svg?cacheSeconds=172800) - Agentic AI research platform that automates the full pipeline from paper ingestion and knowledge management to manuscript drafting.
- [Dr. Claw](https://github.com/OpenLAIR/dr-claw) ![](https://img.shields.io/github/stars/OpenLAIR/dr-claw.svg?cacheSeconds=172800) - AI research IDE with 100+ skills, structured dashboard (Survey → Ideation → Experiment → Publication), auto-research one-click execution, and multi-agent support.
- [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) ![](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents.svg?cacheSeconds=172800) - One-command setup for 9 specialized research agents with Paper Pipeline, Brainstorm, Daily Digest, and Rebuttal workflows built in.
- [Prismer](https://github.com/Prismer-AI/Prismer) ![](https://img.shields.io/github/stars/Prismer-AI/Prismer.svg?cacheSeconds=172800) - End-to-end research platform with PDF reading, Jupyter, LaTeX, code execution, and citation verification.
- [Research Claw](https://github.com/nanoAgentTeam/research-claw) ![](https://img.shields.io/github/stars/nanoAgentTeam/research-claw.svg?cacheSeconds=172800) - Self-hosted academic assistant by nanoAgentTeam for paper management, literature search, deadline tracking, and LaTeX/Overleaf sync.
- [ResearchClaw (Noietch)](https://github.com/Noietch/ResearchClaw) ![](https://img.shields.io/github/stars/Noietch/ResearchClaw.svg?cacheSeconds=172800) - OpenClaw-based research assistant by Noietch with structured paper management and annotation workflows.
- [ResearchClaw (ymx10086)](https://github.com/ymx10086/ResearchClaw) ![](https://img.shields.io/github/stars/ymx10086/ResearchClaw.svg?cacheSeconds=172800) - Local-first Research OS with claims/evidence graph, experiment tracking, paper management, skills, and multi-channel access.
- [sciClaw](https://github.com/drpedapati/sciclaw) ![](https://img.shields.io/github/stars/drpedapati/sciclaw.svg?cacheSeconds=172800) - Paired-scientist agent (Go/PicoClaw runtime) with Telegram/Discord interface, PubMed integration, reproducible experiment logging, skill library, and multi-provider LLM support.
- [ScienceClaw](https://github.com/beita6969/ScienceClaw) ![](https://img.shields.io/github/stars/beita6969/ScienceClaw.svg?cacheSeconds=172800) - Science-focused OpenClaw variant for structured scientific research workflows.
- [Scientify](https://github.com/tsingyuai/scientify) ![](https://img.shields.io/github/stars/tsingyuai/scientify.svg?cacheSeconds=172800) - Continuous-metabolism research system that tracks papers, evolves hypotheses, runs validation experiments, and proactively pushes updates.

### Experiment, Coding & Workflow Automation

Tools that act as the execution layer for experiments, data workflows, and research engineering loops.

- [AIDE](https://github.com/WecoAI/aideml) ![](https://img.shields.io/github/stars/WecoAI/aideml.svg?cacheSeconds=172800) - An ML engineering agent that uses tree search to optimize training code against arbitrary evaluation metrics, achieving human-level performance on Kaggle and MLE-bench.
- [agentic-data-scientist](https://github.com/K-Dense-AI/agentic-data-scientist) ![](https://img.shields.io/github/stars/K-Dense-AI/agentic-data-scientist.svg?cacheSeconds=172800) - Multi-agent framework for data science workflows with separated planning and execution phases.
- [autora](https://github.com/autoresearch/autora) ![](https://img.shields.io/github/stars/autoresearch/autora.svg?cacheSeconds=172800) - Automated research assistant for closed-loop empirical research with autonomous experiment design and data analysis.
- [AutoNumerics](https://github.com/Daviddjddu/Autonumerics) ![](https://img.shields.io/github/stars/Daviddjddu/Autonumerics.svg?cacheSeconds=172800) - Multi-agent pipeline that turns natural-language PDE problems into executable numerical solvers with residual-based verification.
- [expflow](https://github.com/diamond2nv/expflow) ![](https://img.shields.io/github/stars/diamond2nv/expflow.svg?cacheSeconds=172800) - Experiment workflow orchestration toolkit with CLI-driven training, hyperparameter optimization, and observability integrations.
- [Kapso](https://github.com/Leeroo-AI/kapso) ![](https://img.shields.io/github/stars/Leeroo-AI/kapso.svg?cacheSeconds=172800) - A self-improving AI software factory (for measurable objectives). \#1 open-source on MLE-Bench; ALE-Bench; RelBench.
- [MLE-agent](https://github.com/MLSysOps/MLE-agent) ![](https://img.shields.io/github/stars/MLSysOps/MLE-agent.svg?cacheSeconds=172800) - Intelligent companion for ML engineering and research integrating arXiv and Papers with Code for automated planning and debugging.
- [RD-Agent](https://github.com/microsoft/RD-Agent) ![](https://img.shields.io/github/stars/microsoft/RD-Agent.svg?cacheSeconds=172800) - Microsoft's LLM-agent framework for autonomous R&D, covering data science, quant finance, and research-driven software development.
- [Simply](https://github.com/google-deepmind/simply) ![](https://img.shields.io/github/stars/google-deepmind/simply.svg?cacheSeconds=172800) - Minimal JAX research codebase by Google DeepMind designed for agents to read code, propose ideas, run experiments, and iterate.

### Figure, Visualization & Design Agents

Tools dedicated to creating publication-quality figures, diagrams, and visual assets.

- [happy-figure-skill](https://github.com/BAIKEMARK/happy-figure-skill) ![](https://img.shields.io/github/stars/BAIKEMARK/happy-figure-skill.svg?cacheSeconds=172800) - Claude Code skill for generating publication-quality research figures with automated chart creation and styling.
- [PaperBanana](https://github.com/dwzhu-pku/PaperBanana) ![](https://img.shields.io/github/stars/dwzhu-pku/PaperBanana.svg?cacheSeconds=172800) - Reference-driven multi-agent framework for automated academic illustration with 5 specialized agents producing publication-quality diagrams.

### Scientific Writing & Publication

Tools focused on manuscript drafting, paper assembly, and submission-ready scientific writing.

- [claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-writer.svg?cacheSeconds=172800) - AI-powered scientific writing assistant for automated research paper generation and technical documentation.
- [Idea2Paper](https://github.com/AgentAlphaAGI/Idea2Paper) ![](https://img.shields.io/github/stars/AgentAlphaAGI/Idea2Paper.svg?cacheSeconds=172800) - End-to-end pipeline that takes a research idea and autonomously generates a complete paper draft.
- [PaperOrchestra](https://github.com/google-research/paper-orchestra) ![](https://img.shields.io/github/stars/google-research/paper-orchestra.svg?cacheSeconds=172800) - Multi-agent framework for automated research paper writing from raw ideas and experiment logs to submission-ready LaTeX drafts.
- [ScholarCopilot](https://github.com/TIGER-AI-Lab/ScholarCopilot) ![](https://img.shields.io/github/stars/TIGER-AI-Lab/ScholarCopilot.svg?cacheSeconds=172800) - LLM trained for academic writing that generates text with retrieval-grounded, accurate citations.

### Skill Libraries & Extensions

Reusable skill packs, domain extensions, and capability libraries for research-focused agents.

- [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-research-SKILLs) ![](https://img.shields.io/github/stars/Orchestra-Research/AI-research-SKILLs.svg?cacheSeconds=172800) - 86 skills across 22 categories covering the full AI research lifecycle: literature review, idea generation, experimentation, and paper authoring.
- [autoresearch-skill](https://github.com/wjgoarxiv/autoresearch-skill) ![](https://img.shields.io/github/stars/wjgoarxiv/autoresearch-skill.svg?cacheSeconds=172800) - Cross-platform LLM skill set (Claude Code/Codex/Gemini) that runs experiment-evaluate-iterate autoresearch loops from natural-language goals.
- [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills.svg?cacheSeconds=172800) - Comprehensive collection of 140 ready-to-use scientific skills for Claude across biology, chemistry, medicine, and more.
- [distillation-skills](https://github.com/Dubaoxu/distillation-skills) ![](https://img.shields.io/github/stars/Dubaoxu/distillation-skills.svg?cacheSeconds=172800) - Claude Code academic research skill suite spanning deep research, paper writing, peer review, persona distillation, and domain knowledge frameworks.
- [Easy-AutoResearch for Deep Learning](https://github.com/wjc2830/Easy-AutoResearch-for-DeepLearning) ![](https://img.shields.io/github/stars/wjc2830/Easy-AutoResearch-for-DeepLearning.svg?cacheSeconds=172800) - Claude Code skill that orchestrates six roles for versioned deep-learning experiments, requires approval before training, and accepts completion only with current-version evidence.
- [LabClaw](https://github.com/wu-yc/LabClaw) ![](https://img.shields.io/github/stars/wu-yc/LabClaw.svg?cacheSeconds=172800) - 240 OpenClaw skills for biology, pharmacology, medicine, literature, and visualization.
- [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) ![](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills.svg?cacheSeconds=172800) - 869 medical/biomedical skills spanning clinical, genomics, and drug discovery domains.
- [PaperClaw](https://github.com/guhaohao0991/PaperClaw) ![](https://img.shields.io/github/stars/guhaohao0991/PaperClaw.svg?cacheSeconds=172800) - OpenClaw skill for generating topic-specific expert agents for paper search, review, and critique workflows.
- [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) ![](https://img.shields.io/github/stars/K-Dense-AI/scientific-agent-skills.svg?cacheSeconds=172800) - 133 ready-to-use scientific skills across bioinformatics, drug discovery, clinical research, medical imaging, and materials science.

### Agent Frameworks, Environments & Training

Core runtimes, training infrastructure, and agent-building environments for autoresearch systems.

- [aira-dojo](https://github.com/facebookresearch/aira-dojo) ![](https://img.shields.io/github/stars/facebookresearch/aira-dojo.svg?cacheSeconds=172800) - Meta FAIR's extensible AI research agent development and evaluation framework with isolated code execution.
- [aviary](https://github.com/Future-House/aviary) ![](https://img.shields.io/github/stars/Future-House/aviary.svg?cacheSeconds=172800) - Language-agent gym with challenging scientific tasks and research-oriented environments.
- [Gym](https://github.com/NVIDIA-NeMo/Gym) ![](https://img.shields.io/github/stars/NVIDIA-NeMo/Gym.svg?cacheSeconds=172800) - NVIDIA NeMo environment library for evaluating and improving models/agents with multiple backend support.
- [NVIDIA NeMo RL](https://github.com/NVIDIA-NeMo/RL) ![](https://img.shields.io/github/stars/NVIDIA-NeMo/RL.svg?cacheSeconds=172800) - Scalable RL toolkit for efficient model reinforcement, including GRPO and large-scale training workflows.
- [tiny-scientist](https://github.com/ulab-uiuc/tiny-scientist) ![](https://img.shields.io/github/stars/ulab-uiuc/tiny-scientist.svg?cacheSeconds=172800) - Lightweight modular framework for building research agents with tool integration and controllable execution.

### Surveys, Guides & Tutorials

Educational resources, surveys, and practical guides for learning autonomous research concepts and workflows.

- [Autonomous-Agents](https://github.com/tmgthb/Autonomous-Agents) ![](https://img.shields.io/github/stars/tmgthb/Autonomous-Agents.svg?cacheSeconds=172800) - Daily-updated curated collection of research papers on autonomous LLM agents covering multi-agent systems, scientific computing, robotics, and more.
- [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) ![](https://img.shields.io/github/stars/ai-boost/awesome-ai-for-science.svg?cacheSeconds=172800) - Curated list of AI tools, libraries, papers, datasets, and frameworks for scientific discovery across physics, chemistry, biology, and materials.
- [awesome-autoresearch](https://github.com/alvinreal/awesome-autoresearch) ![](https://img.shields.io/github/stars/alvinreal/awesome-autoresearch.svg?cacheSeconds=172800) - Curated index of autonomous improvement loops, research agents, and autoresearch-style systems inspired by Karpathy's autoresearch.
- [Awesome-Deep-Research](https://github.com/DavidZWZ/Awesome-Deep-Research) ![](https://img.shields.io/github/stars/DavidZWZ/Awesome-Deep-Research.svg?cacheSeconds=172800) - Curated collection of deep research agents - industry products, open-source implementations, 70+ recent papers, and benchmarks through early 2026.
- [learn-auto-research](https://github.com/AI4Scientist/learn-auto-research) ![](https://img.shields.io/github/stars/AI4Scientist/learn-auto-research.svg?cacheSeconds=172800) - Educational repository for learning and practicing autonomous research workflows.

## Commercial Platforms

### End-to-End Research Automation

Commercial systems focused on autonomous end-to-end scientific research execution and acceleration.

- [Analemma](https://analemma.ai/fars) - Fully autonomous research system for end-to-end scientific research automation.
- [Co-Scientist](https://research.google/blog/accelerating-scientific-discovery-with-co-scientist/) - Google's AI co-scientist system for hypothesis generation, experimental design, and literature synthesis, demonstrated across multiple biomedical domains (Nature 2026).
- [DeepScientist](http://deepscientist.cc) - AI platform for accelerating scientific research and discovery.
- [Edison Scientific](https://edisonscientific.com) - Autonomous AI scientist platform (Kosmos) for end-to-end research automation.
- [FutureHouse](https://www.futurehouse.org) - AI platform building autonomous systems to accelerate scientific discovery.
- [OpenResearch](https://openresearch.sh) - AI research platform for autonomous scientific research workflows.
- [Weco](https://weco.ai) - Autonomous AI research agent for end-to-end AI research, recognized as the top contributor in OpenAI's Parameter Golf competition.

### Literature Discovery & Synthesis

Commercial tools for discovering, searching, and synthesizing scientific literature at scale.

- [AI Researcher](https://ai-researcher.net) - AI-powered research assistant for literature review and research synthesis.
- [AiraXiv](https://airaxiv.com) - AI research platform for automated paper discovery and analysis.
- [Consensus](https://consensus.app) - AI search engine that finds and summarizes scientific research papers.
- [Elicit](https://elicit.org) - AI research assistant that automates literature review workflows.

### Paper Reading, Review & Knowledge Management

Commercial products for document understanding, paper review, and research knowledge workflows.

- [IBM Watson Discovery](https://www.ibm.com/cloud/watson-discovery) - Enterprise AI platform for intelligent document understanding and search.
- [paper2skills](https://paper2skills.com) - AI-powered platform that converts research papers into actionable skills.
- [PaperReview](https://paperreview.ai) - AI-powered platform for automated paper review and feedback.
- [SciSpace](https://scispace.com) - AI copilot for research paper reading, writing, and understanding.

### Self-driving Labs

Automated laboratory platforms and initiatives that integrate robotics, AI, and closed-loop experimentation.

- [Acceleration Consortium](https://acceleration.utoronto.ca) - University of Toronto-led initiative advancing self-driving labs for materials acceleration and autonomous experimentation.
- [Emerald Cloud Lab](https://www.emeraldcloudlab.com) - Cloud-based robotic laboratory platform for programmable and remotely executed experiments.
- [IBM RXN for Chemistry](https://rxn.res.ibm.com) - AI platform for chemistry synthesis planning and autonomous lab workflow integration.
- [Strateos](https://www.strateos.com) - Remote robotic lab platform for automated experiment execution and high-throughput biology workflows.

## Contributing

Contributions are welcome! Please feel free to submit a pull request to add more AutoResearch tools to this awesome list.
