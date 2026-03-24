# Awesome AI Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ottosulin/awesome-ai-security)

A curated list of awesome AI security related frameworks, standards, learning resources and open source tools.

If you want to contribute, create a PR or contact me [@ottosulin](https://mastodon.social/@ottosulin).

## Table of Contents

- [Learning Resources](#learning-resources)
  - [Reading & Guides](#reading--guides)
  - [Courses, Labs & CTFs](#courses-labs--ctfs)
  - [Podcasts](#podcasts)
- [Governance & Risk Management](#governance--risk-management)
  - [Frameworks](#frameworks)
  - [Standards & Verification](#standards--verification)
  - [Taxonomies, Terminology & Risk Databases](#taxonomies-terminology--risk-databases)
  - [Checklists & Practical Guidance](#checklists--practical-guidance)
- [Attack Techniques & Red Teaming](#attack-techniques--red-teaming)
  - [Adversarial ML & Classical Models](#adversarial-ml--classical-models)
  - [LLM & GenAI Red Teaming](#llm--genai-red-teaming)
  - [Agentic AI & MCP Attack Tools](#agentic-ai--mcp-attack-tools)
  - [AI-Assisted Offensive Security](#ai-assisted-offensive-security)
- [Benchmarks & Evaluations](#benchmarks--evaluations)
- [Defense & Security Controls](#defense--security-controls)
  - [Input/Output Guardrails](#inputoutput-guardrails)
  - [Agent Runtime Security & Sandboxing](#agent-runtime-security--sandboxing)
  - [MCP Security](#mcp-security)
  - [Model & Artifact Scanning](#model--artifact-scanning)
  - [AI-Assisted Defensive Security](#ai-assisted-defensive-security)
  - [Privacy & Confidential Computing](#privacy--confidential-computing)
  - [Data & Supply Chain Security](#data--supply-chain-security)
- [Agentic AI Security Skills](#agentic-ai-security-skills)
- [Security-Focused AI Models](#security-focused-ai-models)

## Learning Resources

### Reading & Guides
* [OWASP ML TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/)
* [OWASP LLM TOP 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [OWASP AI Security and Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/)
* [NIST AIRC](https://airc.nist.gov/Home) - NIST Trustworthy & Responsible AI Resource Center
* [The MLSecOps Top 10 by Institute for Ethical AI & Machine Learning](https://ethical.institute/security.html)
* [OWASP Multi-Agentic System Threat Modeling](https://genai.owasp.org/resource/multi-agentic-system-threat-modeling-guide-v1-0/)
* [OWASP: CheatSheet – A Practical Guide for Securely Using Third-Party MCP Servers 1.0](https://genai.owasp.org/resource/cheatsheet-a-practical-guide-for-securely-using-third-party-mcp-servers-1-0/)

### Courses, Labs & CTFs
* [Damn Vulnerable MCP Server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) - _A deliberately vulnerable implementation of the Model Context Protocol (MCP) for educational purposes._
* [OWASP WrongSecrets LLM exercise](https://wrongsecrets.herokuapp.com/challenge/32)
* [vulnerable-mcp-servers-lab](https://github.com/appsecco/vulnerable-mcp-servers-lab) - _A collection of servers which are deliberately vulnerable to learn Pentesting MCP Servers._
* [FinBot Agentic AI Capture The Flag (CTF) Application](https://genai.owasp.org/resource/finbot-agentic-ai-capture-the-flag-ctf-application/) - _FinBot is an Agentic Security Capture The Flag (CTF) interactive platform that simulates real-world vulnerabilities in agentic AI systems using a simulated Financial Services-focused application._
* [AI-Red-Teaming-Playground-Labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) - _AI Red Teaming playground labs to run AI Red Teaming trainings including infrastructure._

### Podcasts
* [MLSecOps podcast](https://mlsecops.com/podcast)
* [AI Security Podcast](https://www.aisecuritypodcast.com/)
* [AI Security Ops](https://aisecurityops.transistor.fm) - _Weekly podcasts from Black Hills Information Security exploring how AI transforms cybersecurity—covering emerging threats, tools, and trends with practical, actionable knowledge._
* [GenAI Security podcast](https://podcasts.apple.com/ph/podcast/the-genai-security-podcast/id1782916580)

## Governance & Risk Management

### Frameworks
* [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base/AI_RMF)
* [ISO/IEC 42001 Artificial Intelligence Management System](https://www.iso.org/standard/81230.html)
* [ISO/IEC 23894:2023 Information technology — Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
* [Google Secure AI Framework (SAIF)](https://saif.google/)
* [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)
* [OWASP Artificial Intelligence Maturity Assessment](https://github.com/OWASP/www-project-ai-maturity-assessment)
* [CSA AI Model Risk Framework](https://cloudsecurityalliance.org/artifacts/ai-model-risk-management-framework)
* [CSA Maestro AI Threat Modeling Framework](https://cloudsecurityalliance.org/blog/2025/02/06/agentic-ai-threat-modeling-framework-maestro)

### Standards & Verification
* [OWASP AI Security Verification Standard](https://github.com/OWASP/AISVS)
* [OWASP Agent Name Service](https://genai.owasp.org/resource/agent-name-service-ans-for-secure-al-agent-discovery-v1-0/)
* [OWASP Agent Observability Standard](https://aos.owasp.org/)

### Taxonomies, Terminology & Risk Databases
* [NIST AI 100-2e2023](https://csrc.nist.gov/publications/detail/white-paper/2023/03/08/adversarial-machine-learning-taxonomy-and-terminology/draft) - _Adversarial machine learning taxonomy and terminology_
* [MITRE ATLAS](https://atlas.mitre.org/)
* [AVIDML](https://avidml.org/taxonomy/)
* [MIT AI Risk Repository](https://airisk.mit.edu/)
* [AI Incident Database](https://incidentdatabase.ai/)
* [ISO/IEC 22989:2022 Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://www.iso.org/standard/74296.html)
* [NIST AI Glossary](https://airc.nist.gov/glossary/)
* [The Arcanum Prompt Injection Taxonomy](https://arcanum-sec.github.io/arc_pi_taxonomy) - _Comprehensive prompt injection attack classification system covering attack intents, techniques, evasions, and input vectors. Categorizes goals, methods, obfuscation techniques, and attack surfaces for prompt injection attacks._
* [CSA LLM Threats Taxonomy](https://cloudsecurityalliance.org/artifacts/csa-large-language-model-llm-threats-taxonomy)

### Checklists & Practical Guidance
* [OWASP LLM Applications Cybersecurity and Governance Checklist](https://genai.owasp.org/resource/llm-applications-cybersecurity-and-governance-checklist-english/)
* [OWASP AI Security and Privacy Guide](https://github.com/OWASP/www-project-ai-security-and-privacy-guide)
* [OWASP LLM and Generative AI Security Center of Excellence Guide](https://genai.owasp.org/resource/llm-and-generative-ai-security-center-of-excellence-guide/)
* [OWASP Agentic AI – Threats and Mitigations](https://genai.owsp.org/resource/agentic-ai-threats-and-mitigations/)
* [OWASP AI Security Solutions Landscape](https://genai.owasp.org/ai-security-solutions-landscape/)
* [OWASP GenAI Incident Response Guide](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/)
* [OWASP LLM and GenAI Data Security Best Practices](https://genai.owasp.org/resource/llm-and-gen-ai-data-security-best-practices/)
* [OWASP Securing Agentic AI Applications](https://genai.owasp.org/resource/securing-agentic-applications-guide-1-0/)
* [OWASP GenAI Red Teaming Guide](https://genai.owasp.org/initiatives/#ai-redteaming)

## Attack Techniques & Red Teaming

### Adversarial ML & Classical Models
* [Adversarial Robustness Toolkit](https://research.ibm.com/projects/adversarial-robustness-toolbox) - _ART focuses on the threats of Evasion (change the model behavior with input modifications), Poisoning (control a model with training data modifications), Extraction (steal a model through queries) and Inference (attack the privacy of the training data)_
* [cleverhans](https://github.com/cleverhans-lab/cleverhans) - _An adversarial example library for constructing attacks, building defenses, and benchmarking both_
* [foolbox](https://github.com/bethgelab/foolbox) - _A Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX_
* [TextAttack](https://github.com/QData/TextAttack) - _A Python framework for adversarial attacks, data augmentation, and model training in NLP_
* [DeepFool](https://github.com/lts4/deepfool) - _A simple and accurate method to fool deep neural networks_
* [Adversarial Machine Learning Library (Ad-lib)](https://github.com/vu-aml/adlib) - _Game-theoretic adversarial machine learning library providing a set of learner and adversary modules_
* [Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)
* [Deep-pwning](https://github.com/cchio/deep-pwning) - _a lightweight framework for experimenting with machine learning models with the goal of evaluating their robustness against a motivated adversary_
* [Counterfit](https://github.com/Azure/counterfit) - _generic automation layer for assessing the security of machine learning systems_
* [Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware) - _makes it possible to write agents that learn to manipulate PE files (e.g., malware) to achieve some objective (e.g., bypass AV) based on a reward provided by taking specific manipulation actions_
* [Charcuterie](https://github.com/moohax/Charcuterie) - _code execution techniques for ML or ML adjacent libraries_
* [OffsecML Playbook](https://wiki.offsecml.com) - _A collection of offensive and adversarial TTPs with proofs of concept_
* [BadDiffusion](https://github.com/IBM/BadDiffusion) - _Official repo to reproduce the paper "How to Backdoor Diffusion Models?" published at CVPR 2023_
* [Snaike-MLFlow](https://github.com/protectai/Snaike-MLflow) - _MLflow red team toolsuite_
* [secml-torch](https://github.com/pralab/secml-torch) - _SecML-Torch: A Library for Robustness Evaluation of Deep Learning Models_
* [awesome-ai-safety](https://github.com/hari-sikchi/awesome-ai-safety)

### LLM & GenAI Red Teaming
* [garak](https://github.com/leondz/garak/) - _security probing tool for LLMs_
* [ai-scanner](https://github.com/0din-ai/ai-scanner) - _Open-source web application for AI model security assessments, built on NVIDIA garak. Features 179 probes, multi-target scanning, scheduled scans, ASR scoring, and SIEM integration._
* [promptfoo](https://github.com/promptfoo/promptfoo) - _Test your prompts, agents, and RAGs. Red teaming, pentesting, and vulnerability scanning for LLMs. Compare performance of GPT, Claude, Gemini, Llama, and more. Simple declarative configs with command line and CI/CD integration._
* [PyRIT](https://github.com/Azure/PyRIT) - _The Python Risk Identification Tool for generative AI (PyRIT) is an open source framework built to empower security professionals and engineers to proactively identify risks in generative AI systems._
* [PurpleLlama](https://github.com/meta-llama/PurpleLlama) - _Set of tools to assess and improve LLM security._
* [augustus](https://github.com/praetorian-inc/augustus) - _LLM security testing framework for detecting prompt injection, jailbreaks, and adversarial attacks. 190+ probes, 28 providers, single Go binary. Production-ready with concurrent scanning, rate limiting, and retry logic._
* [FuzzyAI](https://github.com/cyberark/FuzzyAI) - _A powerful tool for automated LLM fuzzing. It is designed to help developers and security researchers identify and mitigate potential jailbreaks in their LLM APIs._
* [LLMFuzzer](https://github.com/mnns/LLMFuzzer) - _LLMFuzzer is the first open-source fuzzing framework specifically designed for Large Language Models (LLMs), especially for their integrations in applications via LLM APIs._
* [EasyJailbreak](https://github.com/EasyJailbreak/EasyJailbreak) - _An easy-to-use Python framework to generate adversarial jailbreak prompts._
* [gptfuzz](https://github.com/sherdencooper/GPTFuzz) - _Official repo for GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts_
* [llamator](https://github.com/LLAMATOR-Core/llamator) - _Framework for testing vulnerabilities of large language models (LLM)._
* [agentic_security](https://github.com/msoedov/agentic_security/) - _Agentic LLM Vulnerability Scanner / AI red teaming kit_
* [Agentic Radar](https://github.com/splx-ai/agentic-radar) - _Open-source CLI security scanner for agentic workflows._
* [whistleblower](https://github.com/Repello-AI/whistleblower) - _Offensive security tool for testing against system prompt leakage and capability discovery of an AI application exposed through API_
* [promptmap](https://github.com/utkusen/promptmap) - _a prompt injection scanner for custom LLM applications_
* [HouYi](https://github.com/LLMSecurity/HouYi) - _The automated prompt injection framework for LLM-integrated applications._
* [spikee](https://github.com/WithSecureLabs/spikee) - _Simple Prompt Injection Kit for Evaluation and Exploitation_
* [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - _Make your GenAI Apps Safe & Secure — Test & harden your system prompt_
* [EasyEdit](https://github.com/zjunlp/EasyEdit) - _Modify an LLM's ground truths_
* [llm-attacks](https://github.com/llm-attacks/llm-attacks) - _Universal and Transferable Attacks on Aligned Language Models_
* [Dropbox llm-security](https://github.com/dropbox/llm-security) - _Dropbox LLM Security research code and results_
* [llm-security](https://github.com/greshake/llm-security) - _New ways of breaking app-integrated LLMs_
* [Plexiglass](https://github.com/safellama/plexiglass) - _A toolkit for detecting and protecting against vulnerabilities in Large Language Models (LLMs)._
* [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - _A list of curated resources for people interested in AI Red Teaming, Jailbreaking, and Prompt Injection_
* [Giskard](https://github.com/Giskard-AI/giskard) - _Open-Source Evaluation & Testing for AI & LLM systems_
* [blackice](https://github.com/databricks/containers/tree/master/ubuntu/blackice) - _BlackIce is an open-source containerized toolkit designed for red teaming AI models, including Large Language Models (LLMs) and classical machine learning (ML) models. Inspired by the convenience and standardization of Kali Linux in traditional penetration testing, BlackIce simplifies AI security assessments by providing a reproducible container image preconfigured with specialized evaluation tools._
* [vigil-llm](https://github.com/deadbits/vigil-llm) - _Detect prompt injections, jailbreaks, and other potentially risky Large Language Model (LLM) inputs_
* [Vigil SOC](https://github.com/Vigil-SOC/vigil) - _A comprehensive open-source security operations platform for AI agents, enabling real-time monitoring, threat detection, and incident response for AI-powered environments._
* [ai-best-practices](https://github.com/semgrep/ai-best-practices) - _Semgrep Pro Rules to ensure code using LLMs is following best practices. 58 rules, 102 sub-rules covering 6 providers + MCP + Claude Code & Cursor hooks + LangChain. Detects hardcoded API keys, prompt injection risks, missing safety checks, and unhandled errors across 7 languages._
* [claude-secure-coding-rules](https://github.com/TikiTribe/claude-secure-coding-rules) - _Open-source security rules that guide Claude Code to generate secure code by default._

### Agentic AI & MCP Attack Tools
* [mcp-injection-experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) - _Code snippets to reproduce MCP tool poisoning attacks._
* [AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard/) - _A comprehensive, intelligent, and easy-to-use AI Red Teaming platform developed by Tencent Zhuque Lab. Integrates modules for Infra Scan, MCP Scan, and Jailbreak Evaluation, providing a one-click web UI, REST APIs, and Docker-based deployment for comprehensive AI security evaluation._
* [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - _A benchmark for prompt injection attacks and defenses_

### AI-Assisted Offensive Security
* [PentestGPT](https://github.com/GreyDGL/PentestGPT) - _A GPT-empowered penetration testing tool_
* [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) - _Helping Ethical Hackers use LLMs in 50 Lines of Code or less_
* [cai](https://github.com/aliasrobotics/cai) - _Cybersecurity AI (CAI), an open Bug Bounty-ready Artificial Intelligence ([paper](https://arxiv.org/pdf/2504.06017))_
* [shannon](https://github.com/KeygraphHQ/shannon) - _Fully autonomous AI pentester for web apps and APIs by Keygraph. White-box security testing that analyzes source code, identifies attack vectors, and executes real exploits. 96.15% success rate (100/104 exploits) on XBOW benchmark._
* [strix](https://github.com/usestrix/strix) - _Strix are autonomous AI agents that act just like real hackers - they run your code dynamically, find vulnerabilities, and validate them through actual proof-of-concepts_
* [redamon](https://github.com/samugit83/redamon) - _AI-powered agentic red team framework that automates offensive security operations from reconnaissance to exploitation to post-exploitation with zero human intervention._
* [CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI) - _AI-native security testing platform built in Go. Integrates 100+ security tools with an intelligent orchestration engine, role-based testing with predefined security roles, skills system, and comprehensive lifecycle management. Uses MCP protocol and AI agents for end-to-end automation from conversational commands to vulnerability discovery._
* [HexStrikeAI](https://github.com/0x4m4/hexstrike-ai) - _HexStrike AI MCP Agents is an advanced MCP server that lets AI agents (Claude, GPT, Copilot, etc.) autonomously run 150+ cybersecurity tools for automated pentesting, vulnerability discovery, bug bounty automation, and security research._
* [mcp-for-security](https://github.com/cyproxio/mcp-for-security) - _A collection of Model Context Protocol servers for popular security tools like SQLMap, FFUF, NMAP, Masscan and more. Integrate security testing and penetration testing into AI workflows._
* [mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) - _A growing collection of MCP servers bringing offensive security tools to AI assistants. Nmap, Ghidra, Nuclei, SQLMap, Hashcat and more._
* [Burp MCP Server](https://github.com/PortSwigger/mcp-server) - _MCP Server for Burp_
* [burpgpt](https://github.com/aress31/burpgpt) - _A Burp Suite extension that integrates OpenAI's GPT to perform an additional passive scan for discovering highly bespoke vulnerabilities and enables running traffic-based analysis of any type._
* [guardian-cli](https://github.com/zakirkun/guardian-cli) - _AI-Powered Security Testing & Vulnerability Scanner. Guardian CLI is an intelligent security testing tool that leverages AI to automate penetration testing, vulnerability assessment, and security auditing._
* [AutoPentestX](https://github.com/Gowtham-Darkseid/AutoPentestX) - _AutoPentestX – Linux Automated Pentesting & Vulnerability Reporting Tool_
* [HackGPT](https://github.com/NoDataFound/hackGPT) - _A tool using ChatGPT for hacking_

## Benchmarks & Evaluations

* [jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) - _JailbreakBench: An Open Robustness Benchmark for Jailbreaking Language Models [NeurIPS 2024 Datasets and Benchmarks Track]_
* [AgentDojo](https://github.com/ethz-spylab/agentdojo) - _A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents._
* [AIRTBench](https://github.com/dreadnode/AIRTBench-Code) - _Code Repository for: AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models_
* [HackingBuddyGPT benchmark dataset](https://github.com/ipa-lab/hacking-benchmark) - _Benchmark dataset for automated pentesting_
* [AgentDoG](https://github.com/AI45Lab/AgentDoG) - _AgentDoG is a risk-aware evaluation and guarding framework for autonomous agents. It focuses on trajectory-level risk assessment, aiming to determine whether an agent's execution trajectory contains safety risks under diverse application scenarios._

## Defense & Security Controls

### Input/Output Guardrails
* [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - _NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems._
* [LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall) - _LlamaFirewall is a framework designed to detect and mitigate AI centric security risks, supporting multiple layers of inputs and outputs, such as typical LLM chat and more advanced multi-step agentic operations._
* [llm-guard](https://github.com/protectai/llm-guard) - _LLM Guard by Protect AI is a comprehensive tool designed to fortify the security of Large Language Models (LLMs)._
* [Guardrails.ai](https://shreyar.github.io/guardrails/) - _Guardrails is a Python package that lets a user add structure, type and quality guarantees to the outputs of large language models (LLMs)_
* [TrustGate](https://github.com/NeuralTrust/TrustGate) - _Generative Application Firewall (GAF) to detect, prevent and block attacks against GenAI Applications_
* [ZenGuard AI](https://github.com/ZenGuard-AI/fast-llm-security-guardrails) - _The fastest Trust Layer for AI Agents_
* [vibraniumdome](https://github.com/genia-dev/vibraniumdome) - _Full blown, end to end LLM WAF for Agents, allowing security teams governance, auditing, policy driven control over Agents usage of language models._
* [LocalMod](https://github.com/KOKOSde/localmod) - _Self-hosted content moderation API with prompt injection detection, toxicity filtering, PII detection, and NSFW classification. Runs 100% offline._
* [DynaGuard](https://github.com/montehoover/DynaGuard) - _A Dynamic Guardrail Model With User-Defined Policies_
* [AprielGuard](https://huggingface.co/blog/ServiceNow-AI/aprielguard) - _8B parameter safety–security safeguard model_
* [Safe Zone](https://github.com/thyrisAI/safe-zone) - _Safe Zone is an open-source PII detection and guardrails engine that prevents sensitive data from leaking to LLMs and third-party APIs._
* [superagent](https://github.com/superagent-ai/superagent) - _Superagent provides purpose-trained guardrails that make AI-agents secure and compliant._
* [ShellWard](https://github.com/jnMetaCode/shellward) - _AI Agent Security Middleware with 8-layer defense against prompt injection, data exfiltration & dangerous commands. Zero dependencies._
* [rebuff](https://github.com/woop/rebuff) - _Prompt Injection Detector_
* [langkit](https://github.com/whylabs/langkit) - _LangKit is an open-source text metrics toolkit for monitoring language models. The toolkit provides various security related metrics that can be used to detect attacks_
* [CodeGate](https://codegate.ai) - _An open-source, privacy-focused project that acts as a layer of security within a developer's Code Generation AI workflow_

