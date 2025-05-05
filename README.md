# Awesome AI Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ottosulin/awesome-ai-security)

A curated list of awesome AI security related frameworks, standards, learning resources and tools.

If you want to contribute, create a PR or contact me [@ottosulin](https://twitter.com/ottosulin) / [@ottosulin](https://mastodon.social/@ottosulin).

## Learning resources
* [Damn Vulnerable MCP Server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) - _A deliberately vulnerable implementation of the Model Context Protocol (MCP) for educational purposes._
* [MLSecOps podcast](https://mlsecops.com/podcast)
* [GenAI Security podcast](https://podcasts.apple.com/ph/podcast/the-genai-security-podcast/id1782916580)
* [OWASP ML TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/)
* [OWASP LLM TOP 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [OWASP AI Security and Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/)
* [OWASP WrongSecrets LLM exercise](https://wrongsecrets.herokuapp.com/challenge/32)
* [NIST AIRC](https://airc.nist.gov/Home) - NIST Trustworthy & Responsible AI Resource Center
* [The MLSecOps Top 10 by Institute for Ethical AI & Machine Learning](https://ethical.institute/security.html)

## Governance

### Frameworks and standards
* [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base/AI_RMF)
* [ISO/IEC 42001 Artificial Intelligence Management System](https://www.iso.org/standard/81230.html) - still under development
* [ISO/IEC 23894:2023 Information technology — Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
* [Google Secure AI Framework](https://blog.google/technology/safety-security/introducing-googles-secure-ai-framework/)
* [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)
* [OWASP LLM Applications Cybersecurity and Governance Checklist](https://genai.owasp.org/resource/llm-applications-cybersecurity-and-governance-checklist-english/)

### Taxonomies and terminology
* [NIST AI 100-2e2023](https://csrc.nist.gov/publications/detail/white-paper/2023/03/08/adversarial-machine-learning-taxonomy-and-terminology/draft)
* [AVIDML](https://avidml.org/taxonomy/)
* [MITRE ATLAS](https://atlas.mitre.org/)
* [ISO/IEC 22989:2022 Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://www.iso.org/standard/74296.html)

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

### LLM
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
* [OpenPromptInjection](https://github.com/liu00222/Open-Prompt-Injection) - _This repository provides a benchmark for prompt Injection attacks and defenses_
* [Plexiglass](https://github.com/safellama/plexiglass) - _A toolkit for detecting and protecting against vulnerabilities in Large Language Models (LLMs)._
* [ps-fuzz](https://github.com/prompt-security/ps-fuzz) - _Make your GenAI Apps Safe & Secure 🚀 Test & harden your system prompt_

### Adversarial
* [Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)
* Adversarial Machine Learning Library(Ad-lib)](https://github.com/vu-aml/adlib) - _Game-theoretic adversarial machine learning library providing a set of learner and adversary modules_
* [EasyEdit](https://github.com/zjunlp/EasyEdit) - _Modify an LLM's ground truths_ 

### Poisoning and Injection
* [BadDiffusion](https://github.com/IBM/BadDiffusion) - _Official repo to reproduce the paper "How to Backdoor Diffusion Models?" published at CVPR 2023_
* [spikee](https://github.com/WithSecureLabs/spikee)) - _Simple Prompt Injection Kit for Evaluation and Exploitation_
* [Prompt Hacking Resources](https://github.com/PromptLabs/Prompt-Hacking-Resources) - _A list of curated resources for people interested in AI Red Teaming, Jailbreaking, and Prompt Injection_

### Other
* [HackGPT](https://github.com/NoDataFound/hackGPT) - _A tool using ChatGPT for hacking_


## Defensive tools and frameworks

### Guides & frameworks
* [OWASP LLM and Generative AI Security Center of Excellence Guide](https://genai.owasp.org/resource/llm-and-generative-ai-security-center-of-excellence-guide/)
* [OWASP Agentic AI – Threats and Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/)
* [OWASP AI Security Solutions Landscape](https://genai.owasp.org/ai-security-solutions-landscape/)

### Data security and governance
* [datasig](https://github.com/trailofbits/datasig) - _Dataset fingerprinting for AIBOM_ 

### Safety and prevention
* [Guardrail.ai](https://shreyar.github.io/guardrails/) - _Guardrails is a Python package that lets a user add structure, type and quality guarantees to the outputs of large language models (LLMs)_
* [CodeGate](https://codegate.ai) - _An open-source, privacy-focused project that acts as a layer of security within a developers Code Generation AI workflow_
* [MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist) - _A comprehensive security checklist for MCP-based AI tools. Built by SlowMist to safeguard LLM plugin ecosystems._
* [Awesome-MCP-Security](https://github.com/Puliczek/awesome-mcp-security) - _Everything you need to know about Model Context Protocol (MCP) security._
* [LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall) - _LlamaFirewall is a framework designed to detect and mitigate AI centric security risks, supporting multiple layers of inputs and outputs, such as typical LLM chat and more advanced multi-step agentic operations._
* [awesome-ai-safety](https://github.com/hari-sikchi/awesome-ai-safety)
* [ZenGuard AI](https://github.com/ZenGuard-AI/fast-llm-security-guardrails) - _The fastest Trust Layer for AI Agents_
* [llm-guard](https://github.com/protectai/llm-guard) - _LLM Guard by Protect AI is a comprehensive tool designed to fortify the security of Large Language Models (LLMs)._

### Detection & scanners
* [modelscan](https://github.com/protectai/modelscan) - _ModelScan is an open source project from Protect AI that scans models to determine if they contain unsafe code._
* [rebuff](https://github.com/woop/rebuff) - _Prompt Injection Detector_
* [langkit](https://github.com/whylabs/langkit) - _LangKit is an open-source text metrics toolkit for monitoring language models. The toolkit various security related metrics that can be used to detect attacks_
* [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - _A security scanning tool for MCP servers_

### Privacy and confidentiality
* [Python Differential Privacy Library](https://github.com/OpenMined/PyDP)
* [Diffprivlib](https://github.com/IBM/differential-privacy-library) - _The IBM Differential Privacy Library_
* [PLOT4ai](https://plot4.ai/) - _Privacy Library Of Threats 4 Artificial Intelligence A threat modeling library to help you build responsible AI_
* [TenSEAL](https://github.com/OpenMined/TenSEAL) - _A library for doing homomorphic encryption operations on tensors_
* [SyMPC](https://github.com/OpenMined/SyMPC) - _A Secure Multiparty Computation companion library for Syft_
* [PyVertical](https://github.com/OpenMined/PyVertical) - _Privacy Preserving Vertical Federated Learning_
* [Cloaked AI](https://ironcorelabs.com/products/cloaked-ai/) - _Open source property-preserving encryption for vector embeddings_
* [PrivacyRaven](https://github.com/trailofbits/PrivacyRaven) - _privacy testing library for deep learning systems_

