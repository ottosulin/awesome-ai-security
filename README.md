# Awesome AI Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ottosulin/awesome-ai-security)

A curated list of awesome AI security related frameworks, standards, learning resources and open source tools.

If you want to contribute, create a PR or contact me [@ottosulin](https://mastodon.social/@ottosulin).

## Table of Contents

- [Learning resources](#learning-resources)
  - [General reading material](#general-reading-material)
  - [Technical material & labs](#technical-material--labs)
  - [Podcasts](#podcasts)
- [Governance](#governance)
  - [Frameworks and standards](#frameworks-and-standards)
  - [Standards](#standards)
  - [Taxonomies, terminology and risks](#taxonomies-terminology-and-risks)
  - [Other material](#other-material)
- [Offensive tools and frameworks](#offensive-tools-and-frameworks)
  - [Guides & frameworks](#guides--frameworks)
  - [ML](#ml)
  - [Attacking LLMs](#attacking-llms)
  - [AI for offensive cyber](#ai-for-offensive-cyber)
- [Defensive tools and frameworks](#defensive-tools-and-frameworks)
  - [Guides & frameworks](#guides--frameworks-1)
  - [AI for defensive cyber](#ai-for-defensive-cyber)
  - [Data security and governance](#data-security-and-governance)
  - [General AI / ML safety and robustness](#general-ai--ml-safety-and-robustness)
  - [MCP Security](#mcp-security)
  - [LLM Guardrails](#llm-guardrails)
  - [Security for agentic AI tools](#security-for-agentic-ai-tools)
  - [Detection & scanners](#detection--scanners)
  - [OpenClaw](#openclaw)
  - [Privacy and confidentiality](#privacy-and-confidentiality)
  - [Miscellaneous](#miscellaneous)
- [Agentic AI skills](#agentic-ai-skills)
- [Models for cyber security](#models-for-cyber-security)

## Learning resources

### General reading material
* [GenAI Security podcast](https://podcasts.apple.com/ph/podcast/the-genai-security-podcast/id1782916580)
* [OWASP ML TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/)
* [OWASP LLM TOP 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [OWASP AI Security and Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/)
* [NIST AIRC](https://airc.nist.gov/Home) - NIST Trustworthy & Responsible AI Resource Center
* [The MLSecOps Top 10 by Institute for Ethical AI & Machine Learning](https://ethical.institute/security.html)
* [OWASP Multi-Agentic System Threat Modeling](https://genai.owasp.org/resource/multi-agentic-system-threat-modeling-guide-v1-0/)
* [OWASP: CheatSheet – A Practical Guide for Securely Using Third-Party MCP Servers 1.0](https://genai.owasp.org/resource/cheatsheet-a-practical-guide-for-securely-using-third-party-mcp-servers-1-0/)

### Technical material & labs
* [Damn Vulnerable MCP Server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) - _A deliberately vulnerable implementation of the Model Context Protocol (MCP) for educational purposes._
* [OWASP WrongSecrets LLM exercise](https://wrongsecrets.herokuapp.com/challenge/32)
* [vulnerable-mcp-servers-lab](https://github.com/appsecco/vulnerable-mcp-servers-lab) - _A collection of servers which are deliberately vulnerable to learn Pentesting MCP Servers._
* [FinBot Agentic AI Capture The Flag (CTF) Application](https://genai.owasp.org/resource/finbot-agentic-ai-capture-the-flag-ctf-application/) - _FinBot is an Agentic Security Capture The Flag (CTF) interactive platform that simulates real-world vulnerabilities in agentic AI systems using a simulated Financial Services-focused application._

### Podcasts
* [MLSecOps podcast](https://mlsecops.com/podcast)
* [AI Security Podcast](https://www.aisecuritypodcast.com/)

## Governance

### Frameworks and standards
* [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base/AI_RMF)
* [ISO/IEC 42001 Artificial Intelligence Management System](https://www.iso.org/standard/81230.html)
* [ISO/IEC 23894:2023 Information technology — Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
* [Google Secure AI Framework](https://blog.google/technology/safety-security/introducing-googles-secure-ai-framework/)
* [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)
* [OWASP Artificial Intelligence Maturity Assessment](https://github.com/OWASP/www-project-ai-maturity-assessment)
* [Google Secure AI Framework](https://saif.google/)
* [CSA AI Model Risk Framework](https://cloudsecurityalliance.org/artifacts/ai-model-risk-management-framework)

### Standards
* [OWASP Agent Name Service](https://genai.owasp.org/resource/agent-name-service-ans-for-secure-al-agent-discovery-v1-0/)
* [OWASP AI Security Verification Standard](https://github.com/OWASP/AISVS)
* [OWASP Agent Observability Standard](https://aos.owasp.org/)

### Taxonomies, terminology and risks
* [NIST AI 100-2e2023](https://csrc.nist.gov/publications/detail/white-paper/2023/03/08/adversarial-machine-learning-taxonomy-and-terminology/draft)
* [AVIDML](https://avidml.org/taxonomy/)
* [MITRE ATLAS](https://atlas.mitre.org/)
* [ISO/IEC 22989:2022 Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://www.iso.org/standard/74296.html)
* [MIT AI Risk Repository](https://airisk.mit.edu/)
* [AI Incident Database](https://incidentdatabase.ai/)
* [NIST AI Glossary](https://airc.nist.gov/glossary/)
* [The Arcanum Prompt Injection Taxonomy](https://arcanum-sec.github.io/arc_pi_taxonomy) - _Comprehensive prompt injection attack classification system covering attack intents, techniques, evasions, and input vectors. Categorizes goals, methods, obfuscation techniques, and attack surfaces for prompt injection attacks._
* [CSA LLM Threats Taxonomy](https://cloudsecurityalliance.org/artifacts/csa-large-language-model-llm-threats-taxonomy)

### Technical resources for governance
[Trusera ai-bom](https://github.com/Trusera/ai-bom) - _AI Bill of Materials — discover every AI agent, model, and API in your infrastructure_

### Other material
* [OWASP LLM Applications Cybersecurity and Governance Checklist](https://genai.owasp.org/resource/llm-applications-cybersecurity-and-governance-checklist-english/)
* [OWASP AI Security and Privacy Guide](github.com/OWASP/www-project-ai-security-and-privacy-guide)

## Offensive tools and frameworks

### Guides & frameworks
* [OWASP GenAI Red Teaming Guide](https://genai.owasp.org/initiatives/#ai-redteaming)

### ML
* [Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware) - _makes it possible to write agents that learn to manipulate PE files (e.g., malware) to achieve some objective (e.g., bypass AV) based on a reward provided by taking specific manipulation actions_
* [Deep-pwning](https://github.com/cchio/deep-pwning) - _a lightweight framework for experimenting with machine learning models with the goal of evaluating their robustness against a motivated adversary_
* [Counterfit](https://github.com/Azure/counterfit) - _generic automation layer for assessing the security of machine learning systems_
* [DeepFool](https://github.com/lts4/deepfool) - _A simple and accurate method to fool deep neural networks_
* [Snaike-MLFlow](https://github.com/protectai/Snaike-MLflow) - _MLflow red team toolsuite_
* [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT.) - An automatic pentester (+ corresponding *[benchmark dataset](https://github.com/ipa
-lab/hacking-benchmark)*)
* [Charcuterie](https://github.com/moohax/Charcuterie) - _code execution techniques for ML or ML adjacent libraries_
* [OffsecML Playbook](https://wiki.offsecml.com) - _A collection of offensive and adversarial TTP's with proofs of concept_
* [BadDiffusion](https://github.com/IBM/BadDiffusion) - _Official repo to reproduce the paper "How to Backdoor Diffusion Models?" published at CVPR 2023_
* [Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)
* Adversarial Machine Learning Library(Ad-lib)](https://github.com/vu-aml/adlib) - _Game-theoretic adversarial machine learning library providing a set of learner and adversary modules_
* [Adversarial Robustness Toolkit](https://research.ibm.com/projects/adversarial-robustness-toolbox) - _ART focuses on the threats of Evasion (change the model behavior with input modifications), Poisoning (control a model with training data modifications), Extraction (steal a model through queries) and Inference (attack the privacy of the training data)_
* [cleverhans](https://github.com/cleverhans-lab/cleverhans) - _An adversarial example library for constructing attacks, building defenses, and benchmarking both_
* [foolbox](https://github.com/bethgelab/foolbox) - _A Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX_
* [TextAttack](https://github.com/QData/TextAttack) - _TextAttack 🐙 is a Python framework for adversarial attacks, data augmentation, and model training in NLP https://textattack.readthedocs.io/en/master/_

### Attacking LLMs
* [garak](https://github.com/leondz/garak/) - _security probing tool for LLMs_
* [agentic_security](https://github.com/msoedov/agentic_security/) - _Agentic LLM Vulnerability Scanner / AI red teaming kit_
* [Agentic Radar](https://github.com/splx-ai/agentic-radar) - _Open-source CLI security scanner for agentic workflows._
* [llamator](https://github.com/LLAMATOR-Core/llamator) - _Framework for testing vulnerabilities of large language models (LLM)._
* [whistleblower](https://github.com/Repello-AI/whistleblower) - _Whistleblower is a offensive security tool for testing against system prompt leakage and capability discovery of an AI application exposed through API_
* [LLMFuzzer](https://github.com/mnns/LLMFuzzer) - _🧠 LLMFuzzer - Fuzzing Framework for Large Language Models 🧠 LLMFuzzer is the first open-source fuzzing framework specifically designed for Large Language Models (LLMs), especially for their integrations in applications via LLM APIs. 🚀💥_
* [vigil-llm](https://github.com/deadbits/vigil-llm) - _⚡ Vigil ⚡ Detect prompt injections, jailbreaks, and other potentially risky Large Language Model (LLM) inputs_
* [FuzzyAI](https://github.com/cyberark/FuzzyAI) - _A powerful tool for automated LLM fuzzing. It is designed to help developers and security researchers identify and mitigate potential jailbreaks in their LLM APIs._
* [EasyJailbreak](https://github.com/EasyJailbreak/EasyJailbreak) - _An easy-to-use Python framework to generate adversarial jailbreak prompts._
* [promptmap](https://github.com/utkusen/promptmap) - _a prompt injection scanner for custom LLM applications_
* [PyRIT](https://github.com/Azure/PyRIT) - _The Python Risk Identification Tool for generative AI (PyRIT) is an open source framework built to empower security professionals and engineers to proactively identify risks in generative AI systems._
* [PurpleLlama](https://github.com/meta-llama/PurpleLlama) - _Set of tools to assess and improve LLM security._
* [Giskard-AI](https://github.com/Giskard-AI/giskard) - _🐢 Open-Source Evaluation & Testing for AI & LLM systems_
* [promptfoo](https://github.com/promptfoo/promptfoo) - _Test your prompts, agents, and RAGs. Red teaming, pentesting, and vulnerability scanning for LLMs. Compare performance of GPT, Claude, Gemini, Llama, and more. Simple declarative configs with command line and CI/CD integration._
* [HouYi](https://github.com/LLMSecurity/HouYi) - _The automated prompt injection framework for LLM-integrated applications._
* [llm-attacks](https://github.com/llm-attacks/llm-attacks) - _Universal and Transferable Attacks on Aligned Language Models_
* [Dropbox llm-security](https://github.com/dropbox/llm-security) - _Dropbox LLM Security research code and results_
* [llm-security](https://github.com/greshake/llm-security) - _New ways of breaking app-integrated LLMs_
* [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - _This repository provides a benchmark for prompt Injection attacks and defenses_
* [Plexiglass](https://github.com/safellama/plexiglass) - _A toolkit for detecting and protecting against vulnerabilities in Large Language Models (LLMs)._
* [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - _Make your GenAI Apps Safe & Secure 🚀 Test & harden your system prompt_
* [EasyEdit](https://github.com/zjunlp/EasyEdit) - _Modify an LLM's ground truths_
* [spikee](https://github.com/WithSecureLabs/spikee)) - _Simple Prompt Injection Kit for Evaluation and Exploitation_
* [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - _A list of curated resources for people interested in AI Red Teaming, Jailbreaking, and Prompt Injection_
* [mcp-injection-experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) - _Code snippets to reproduce MCP tool poisoning attacks._
* [gptfuzz](https://github.com/sherdencooper/GPTFuzz) - _Official repo for GPTFUZZER : Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts_
* [AgentDojo](https://github.com/ethz-spylab/agentdojo) - _A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents._
* [jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) - _JailbreakBench: An Open Robustness Benchmark for Jailbreaking Language Models [NeurIPS 2024 Datasets and Benchmarks Track]_
* [giskard](https://github.com/Giskard-AI/giskard) - _🐢 Open-Source Evaluation & Testing library for LLM Agents_
* [TrustGate](https://github.com/NeuralTrust/TrustGate) - _Generative Application Firewall (GAF) to detects, prevents and blocks attacks against GenAI Applications_
* [blackice](https://github.com/databricks/containers/tree/master/ubuntu/blackice) - _BlackIce is an open-source containerized toolkit designed for red teaming AI models, including Large Language Models (LLMs) and classical machine learning (ML) models. Inspired by the convenience and standardization of Kali Linux in traditional penetration testing, BlackIce simplifies AI security assessments by providing a reproducible container image preconfigured with specialized evaluation tools._
* [augustus](https://github.com/praetorian-inc/augustus) - _LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks. 190+ probes, 28 providers, single Go binary. Production-ready with concurrent scanning, rate limiting, and retry logic._

### AI for offensive cyber
* [guardian-cli](https://github.com/zakirkun/guardian-cli) - _AI-Powered Security Testing & Vulnerability Scanner. Guardian CLI is an intelligent security testing tool that leverages AI to automate penetration testing, vulnerability assessment, and security auditing._
* [AI-Red-Teaming-Playground-Labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) - _AI Red Teaming playground labs to run AI Red Teaming trainings including infrastructure._
* [HackGPT](https://github.com/NoDataFound/hackGPT) - _A tool using ChatGPT for hacking_
* [mcp-for-security](https://github.com/cyproxio/mcp-for-security) - _A collection of Model Context Protocol servers for popular security tools like SQLMap, FFUF, NMAP, Masscan and more. Integrate security testing and penetration testing into AI workflows._
* [cai](https://github.com/aliasrobotics/cai) - _Cybersecurity AI (CAI), an open Bug Bounty-ready Artificial Intelligence ([paper](https://arxiv.org/pdf/2504.06017))_
* [AIRTBench](https://github.com/dreadnode/AIRTBench-Code) - _Code Repository for: AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models_
* [PentestGPT](https://github.com/GreyDGL/PentestGPT) - _A GPT-empowered penetration testing tool_
* [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - _Helping Ethical Hackers use LLMs in 50 Lines of Code or less.._
* [HexStrikeAI](https://github.com/0x4m4/hexstrike-ai) - _HexStrike AI MCP Agents is an advanced MCP server that lets AI agents (Claude, GPT, Copilot, etc.) autonomously run 150+ cybersecurity tools for automated pentesting, vulnerability discovery, bug bounty automation, and security research. Seamlessly bridge LLMs with real-world offensive security capabilities._
* [Burp MCP Server](https://github.com/PortSwigger/mcp-server) - _MCP Server for Burp_
* [burpgpt](https://github.com/aress31/burpgpt) - _A Burp Suite extension that integrates OpenAI's GPT to perform an additional passive scan for discovering highly bespoke vulnerabilities and enables running traffic-based analysis of any type._
* [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard/) - _A comprehensive, intelligent, and easy-to-use AI Red Teaming platform developed by Tencent Zhuque Lab.It integrates modules for Infra Scan,MCP Scan,and Jailbreak Evaluation,providing a one-click web UI, REST APIs, and Docker-based deployment for comprehensive AI security evaluation._
* [strix](https://github.com/usestrix/strix) - _Strix are autonomous AI agents that act just like real hackers - they run your code dynamically, find vulnerabilities, and validate them through actual proof-of-concepts_
* [mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) - _A growing collection of MCP servers bringing offensive security tools to AI assistants. Nmap, Ghidra, Nuclei, SQLMap, Hashcat and more._
* [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - _AutoPentestX – Linux Automated Pentesting & Vulnerability Reporting Tool_
* [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - _AI-native security testing platform built in Go. Integrates 100+ security tools with an intelligent orchestration engine, role-based testing with predefined security roles, skills system, and comprehensive lifecycle management. Uses MCP protocol and AI agents for end-to-end automation from conversational commands to vulnerability discovery._
* [redamon](https://github.com/samugit83/redamon) - _AI-powered agentic red team framework that automates offensive security operations from reconnaissance to exploitation to post-exploitation with zero human intervention._

## Defensive tools and frameworks

### Guides & frameworks
* [OWASP LLM and Generative AI Security Center of Excellence Guide](https://genai.owasp.org/resource/llm-and-generative-ai-security-center-of-excellence-guide/)
* [OWASP Agentic AI – Threats and Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/)
* [OWASP AI Security Solutions Landscape](https://genai.owasp.org/ai-security-solutions-landscape/)
* [OWASP GenAI Incident Response Guide](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/)
* [OWASP LLM and GenAI Data Security Best Practices](https://genai.owasp.org/resource/llm-and-gen-ai-data-security-best-practices/)
* [OWASP Securing Agentic AI Applications](https://genai.owasp.org/resource/securing-agentic-applications-guide-1-0/)
* [CSA Maestro AI Threat Modeling Framework](https://cloudsecurityalliance.org/blog/2025/02/06/agentic-ai-threat-modeling-framework-maestro)

### AI for defensive cyber
* [Claude Code Security Review](https://github.com/anthropics/claude-code-security-review) - _An AI-powered security review GitHub Action using Claude to analyze code changes for security vulnerabilities._
* [GhidraGPT](https://github.com/ZeroDaysBroker/GhidraGPT) - _Integrates GPT models into Ghidra for automated code analysis, variable renaming, vulnerability detection, and explanation generation._
* [claude-grc-plugin](https://github.com/mlunato47/claude-grc-plugin) - _Claude Code plugin that turns Claude into a senior GRC analyst. 72+ reference files covering 15 frameworks (NIST 800-53, FedRAMP, ISO 27001, SOC 2, etc.), 24 slash commands, and deep domain knowledge for federal and commercial compliance work._

### Data security and governance
* [datasig](https://github.com/trailofbits/datasig) - _Dataset fingerprinting for AIBOM_
* [OWASP AIBOM](https://github.com/OWASP/www-project-aibom) - _AI Bill of Materials_

### General AI / ML safety and robustness
* [secml-torch](https://github.com/pralab/secml-torch) - _SecML-Torch: A Library for Robustness Evaluation of Deep Learning Models_
* [awesome-ai-safety](https://github.com/hari-sikchi/awesome-ai-safety)

### MCP Security
* [MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist) - _A comprehensive security checklist for MCP-based AI tools. Built by SlowMist to safeguard LLM plugin ecosystems._
* [Awesome-MCP-Security](https://github.com/Puliczek/awesome-mcp-security) - _Everything you need to know about Model Context Protocol (MCP) security._
* [secure-mcp-gateway](https://github.com/enkryptai/secure-mcp-gateway) - _This Secure MCP Gateway is built with authentication, automatic tool discovery, caching, and guardrail enforcement._
* [mcp-context-protector](https://github.com/trailofbits/mcp-context-protector) - _context-protector is a security wrapper for MCP servers that addresses risks associated with running untrusted MCP servers, including line jumping, unexpected server configuration changes, and other prompt injection attacks_
* [mcp-guardian](https://github.com/eqtylab/mcp-guardian/) - _MCP Guardian manages your LLM assistant's access to MCP servers, handing you realtime control of your LLM's activity._
* [MCP Audit VSCode Extension](https://github.com/Agentity-com/mcp-audit-extension) - _Audit and log all GitHub Copilot MCP tool calls in VSCode in centrally with ease._

### LLM Guardrails
* [Guardrail.ai](https://shreyar.github.io/guardrails/) - _Guardrails is a Python package that lets a user add structure, type and quality guarantees to the outputs of large language models (LLMs)_
* [CodeGate](https://codegate.ai) - _An open-source, privacy-focused project that acts as a layer of security within a developers Code Generation AI workflow_
* [LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall) - _LlamaFirewall is a framework designed to detect and mitigate AI centric security risks, supporting multiple layers of inputs and outputs, such as typical LLM chat and more advanced multi-step agentic operations._
* [ZenGuard AI](https://github.com/ZenGuard-AI/fast-llm-security-guardrails) - _The fastest Trust Layer for AI Agents_
* [llm-guard](https://github.com/protectai/llm-guard) - _LLM Guard by Protect AI is a comprehensive tool designed to fortify the security of Large Language Models (LLMs)._
* [vibraniumdome](https://github.com/genia-dev/vibraniumdome) - _Full blown, end to end LLM WAF for Agents, allowing security teams govenrance, auditing, policy driven control over Agents usage of language models._
* [LocalMod](https://github.com/KOKOSde/localmod) - _Self-hosted content moderation API with prompt injection detection, toxicity filtering, PII detection, and NSFW classification. Runs 100% offline._
* [NeMo-GuardRails](https://github.com/NVIDIA/NeMo-Guardrails) - _NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems._
* [DynaGuard](https://github.com/montehoover/DynaGuard) - _A Dynamic Guardrail Model With User-Defined Policies_
* [AprielGuard](https://huggingface.co/blog/ServiceNow-AI/aprielguard) - _8B parameter safety–security safeguard model_
* [Safe Zone](https://github.com/thyrisAI/safe-zone) - _Safe Zone is an open-source PII detection and guardrails engine that prevents sensitive data from leaking to LLMs and third-party APIs._
* [superagent](https://github.com/superagent-ai/superagent) - _Superagent provides purpose-trained guardrails that make AI-agents secure and compliant._

### Security for agentic AI tools
* [sidechannel](https://github.com/HackingDave/sidechannel) - _Signal messaging bot that integrates Claude AI for coding and development workflows from your phone. Features long-term memory, autonomous development tasks, and parallel execution with production-grade reliability._
* [mcp-context-protector](https://github.com/trailofbits/mcp-context-protector) - _mcp-context-protector is a security wrapper for MCP servers that addresses risks associated with running untrusted MCP servers_
* [vibekit](https://github.com/superagent-ai/vibekit) - _Run Claude Code, Gemini, Codex — or any coding agent — in a clean, isolated sandbox with sensitive data redaction and observability baked in._
* [claude-code-safety-net](https://github.com/kenryu42/claude-code-safety-net) - _A Claude Code plugin that acts as a safety net, catching destructive git and filesystem commands before they execute_
* [leash](https://github.com/strongdm/leash) - _Leash wraps AI coding agents in containers and monitors their activity._
* [skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) - _A security scanner for AI Agent Skills that detects prompt injection, data exfiltration, and malicious code patterns. Combines pattern-based detection (YAML + YARA), LLM-as-a-judge, and behavioral dataflow analysis for comprehensive threat detection._
* [Project CodeGuard](https://github.com/cosai-oasis/project-codeguard) - _CoSAI Open Source Project for securing AI-assisted development workflows. CodeGuard provides security controls and guardrails for AI coding assistants to prevent vulnerabilities from being introduced during AI-generated code development._
* [pipelock](https://github.com/luckyPipewrench/pipelock) - _Security harness for AI agents — egress proxy with DLP scanning, SSRF protection, MCP response scanning, and workspace integrity monitoring_
* [claude-code-devcontainer](https://github.com/trailofbits/claude-code-devcontainer) - _Sandboxed devcontainer for running Claude Code in bypass mode safely. Built for security audits and untrusted code review._

### Detection & scanners
* [modelscan](https://github.com/protectai/modelscan) - _ModelScan is an open source project from Protect AI that scans models to determine if they contain unsafe code._
* [rebuff](https://github.com/woop/rebuff) - _Prompt Injection Detector_
* [langkit](https://github.com/whylabs/langkit) - _LangKit is an open-source text metrics toolkit for monitoring language models. The toolkit various security related metrics that can be used to detect attacks_
* [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - _A security scanning tool for MCP servers_
* [picklescan](https://github.com/mmaitre314/picklescan) - _Security scanner detecting Python Pickle files performing suspicious actions_
* [fickling](https://github.com/trailofbits/fickling) - _A Python pickling decompiler and static analyzer_
* [a2a-scanner](https://github.com/cisco-ai-defense/a2a-scanner) - _Scan A2A agents for potential threats and security issues_
* [medusa](https://github.com/Pantheon-Security/medusa) - _AI-first security scanner with 74+ analyzers, 180+ AI agent security rules, intelligent false positive reduction. Supports all languages. CVE detection for React2Shell, mcp-remote RCE._
* [julius](https://github.com/praetorian-inc/julius) - _LLM service fingerprinting tool for security professionals. Detects 32+ AI services (Ollama, vLLM, LiteLLM, Hugging Face TGI, etc.) during penetration tests and attack surface discovery. Uses HTTP-based service fingerprinting to identify server infrastructure._

### OpenClaw
* [openclaw-shield](https://github.com/knostic/openclaw-shield) - _Security plugin for OpenClaw agents - prevents secret leaks, PII exposure, and destructive command execution_
* [clawsec](https://github.com/prompt-security/clawsec) - _Security scanner and hardening tool for OpenClaw deployments. Provides security assessments, configuration auditing, and vulnerability detection specifically for OpenClaw gateway and agent configurations._
* [nanoclaw](https://github.com/qwibitai/nanoclaw) - _Lightweight alternative to OpenClaw that runs in containers for security. Connects to WhatsApp, has memory, scheduled jobs, and runs directly on Anthropic's Agents SDK. First AI assistant to support Agent Swarms for collaborative agent teams._
* [secureclaw](https://github.com/adversa-ai/secureclaw) - _Automated security hardening for OpenClaw AI agents by Adversa AI. 51 audit checks, 12 behavioral rules, 9 scripts, 4 pattern databases. Full OWASP ASI Top 10 coverage. Protects against prompt injection, credential theft, supply chain attacks, and privacy leaks._

### Privacy and confidentiality
* [Python Differential Privacy Library](https://github.com/OpenMined/PyDP)
* [Diffprivlib](https://github.com/IBM/differential-privacy-library) - _The IBM Differential Privacy Library_
* [PLOT4ai](https://plot4.ai/) - _Privacy Library Of Threats 4 Artificial Intelligence A threat modeling library to help you build responsible AI_
* [TenSEAL](https://github.com/OpenMined/TenSEAL) - _A library for doing homomorphic encryption operations on tensors_
* [SyMPC](https://github.com/OpenMined/SyMPC) - _A Secure Multiparty Computation companion library for Syft_
* [PyVertical](https://github.com/OpenMined/PyVertical) - _Privacy Preserving Vertical Federated Learning_
* [Cloaked AI](https://ironcorelabs.com/products/cloaked-ai/) - _Open source property-preserving encryption for vector embeddings_
* [dstack](https://github.com/Dstack-TEE/dstack) - _Open-source confidential AI framework for secure ML/LLM deployment with hardware-enforced isolation and data privacy_
* [PrivacyRaven](https://github.com/trailofbits/PrivacyRaven) - _privacy testing library for deep learning systems_

### Miscellaneous
* [claude-secure-coding-rules](https://github.com/TikiTribe/claude-secure-coding-rules) - _Open-source security rules that guide Claude Code to generate secure code by default._

## Agentic AI skills
* [Ghost Security Skills](https://github.com/ghostsecurity/skills) - Agent application security (appsec) skills and tools for Claude Code
* [tm_skills](https://github.com/izar/tm_skills) - _Agent skills to help with Continuous Threat Modeling_
* [Trail of Bits Skills Marketplace](https://github.com/trailofbits/skills) - _Trail of Bits Claude Code skills for security research, vulnerability detection, and audit workflows_
* [Semgrep Skills](https://github.com/semgrep/skills) - _Official Semgrep skills for Claude Code and other AI coding assistants. Provides security scanning, code analysis, and vulnerability detection capabilities directly in your AI-assisted development workflow._

## Models for cyber security
* [VulnLLM-R-7B](https://huggingface.co/UCSB-SURFI/VulnLLM-R-7B) - _Specialized reasoning LLM for vulnerability detection. Uses Chain-of-Thought reasoning to analyze data flow, control flow, and security context. Outperforms Claude-3.7-Sonnet and CodeQL on vulnerability detection benchmarks. Only 7B parameters making it efficient and fast._
* [Foundation-Sec-8B-Reasoning](https://huggingface.co/fdtn-ai/Foundation-Sec-8B-Reasoning) - _Llama-3.1-FoundationAI-SecurityLLM-8B-Reasoning (Foundation-Sec-8B-Reasoning) is an open-weight, 8-billion parameter instruction-tuned language model specialized for cybersecurity applications. It extends the Foundation-Sec-8B base model with instruction-following and reasoning capabilities. It leverages prior training to understand security concepts, terminology, and practices across multiple security domains_
* [AgentDoG](https://github.com/AI45Lab/AgentDoG) - _AgentDoG is a risk-aware evaluation and guarding framework for autonomous agents. It focuses on trajectory-level risk assessment, aiming to determine whether an agent’s execution trajectory contains safety risks under diverse application scenarios._
