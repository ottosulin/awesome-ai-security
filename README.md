# Awesome AI Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ottosulin/awesome-ai-security)

A curated list of awesome AI security related frameworks, attacks, tools and papers. Inspired by `awesome-machine-learning`.

If you want to contribute, create a PR or contact me [@ottosulin](https://twitter.com/ottosulin).

## Related awesome lists
* [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)
* [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
* [awesome-ai-safety](https://github.com/hari-sikchi/awesome-ai-safety)
* [awesome-mlops](https://github.com/kelvins/awesome-mlops)

## Frameworks and standards
* [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base/AI_RMF)
* [ISO/IEC 42001 Artificial Intelligence Management System](https://www.iso.org/standard/81230.html) - still under development
* [ISO/IEC 23894:2023 Information technology — Artificial intelligence — Guidance on risk management](https://www.iso.org/standard/77304.html)
* [Google Secure AI Framework](https://blog.google/technology/safety-security/introducing-googles-secure-ai-framework/)

## Taxonomies and terminology
* [NIST AI 100-2e2023](https://csrc.nist.gov/publications/detail/white-paper/2023/03/08/adversarial-machine-learning-taxonomy-and-terminology/draft)
* [AVIDML](https://avidml.org/taxonomy/)
* [MITRE ATLAS](https://atlas.mitre.org/)
* [ISO/IEC 22989:2022 Information technology — Artificial intelligence — Artificial intelligence concepts and terminology](https://www.iso.org/standard/74296.html)

## Offensive tools and frameworks

### Generic
* [Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware) - _makes it possible to write agents that learn to manipulate PE files (e.g., malware) to achieve some objective (e.g., bypass AV) based on a reward provided by taking specific manipulation actions_
* [Deep-pwning](https://github.com/cchio/deep-pwning) - _a lightweight framework for experimenting with machine learning models with the goal of evaluating their robustness against a motivated adversary_
* [Counterfit](https://github.com/Azure/counterfit) - _generic automation layer for assessing the security of machine learning systems_
* [DeepFool](https://github.com/lts4/deepfool) - _A simple and accurate method to fool deep neural networks_
* [garak](https://github.com/leondz/garak/) - _security probing tool for LLMs_
* [Snaike-MLFlow](https://github.com/protectai/Snaike-MLflow) - _MLflow red team toolsuite_
* [HackGPT](https://github.com/NoDataFound/hackGPT) - _A tool using ChatGPT for hacking_
* [HackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT.) - An automatic pentester (+ corresponding *[benchmark dataset](https://github.com/ipa
-lab/hacking-benchmark)*)
* [Charcuterie](https://github.com/moohax/Charcuterie) - _code execution techniques for ML or ML adjacent libraries_
* [OffsecML Playbook](https://wiki.offsecml.com) - _A collection of offensive and adversarial TTP's with proofs of concept_

### Adversarial
* [Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)
* Adversarial Machine Learning Library(Ad-lib)](https://github.com/vu-aml/adlib) - _Game-theoretic adversarial machine learning library providing a set of learner and adversary modules_
* [EasyEdit](https://github.com/zjunlp/EasyEdit) - _Modify an LLM's ground truths_ 

### Poisoning
* [BadDiffusion](https://github.com/IBM/BadDiffusion) - _Official repo to reproduce the paper "How to Backdoor Diffusion Models?" published at CVPR 2023_

### Privacy
* [PrivacyRaven](https://github.com/trailofbits/PrivacyRaven) - _privacy testing library for deep learning systems_

## Defensive tools and frameworks

### Safety and prevention
* [Guardrail.ai](https://shreyar.github.io/guardrails/) - _Guardrails is a Python package that lets a user add structure, type and quality guarantees to the outputs of large language models (LLMs)_

### Detection
* [ProtectAI's model scanner](https://github.com/protectai/model-scanner) - _Security scanner detecting serialized ML Models performing suspicious actions_
* [rebuff](https://github.com/woop/rebuff) - _Prompt Injection Detector_
* [langkit](https://github.com/whylabs/langkit) - _LangKit is an open-source text metrics toolkit for monitoring language models. The toolkit various security related metrics that can be used to detect attacks_
* [StringSifter](https://github.com/fireeye/stringsifter) - _A machine learning tool that ranks strings based on their relevance for malware analysis_

### Privacy and confidentiality
* [Python Differential Privacy Library](https://github.com/OpenMined/PyDP)
* [Diffprivlib](https://github.com/IBM/differential-privacy-library) - _The IBM Differential Privacy Library_
* [PLOT4ai](https://plot4.ai/) - _Privacy Library Of Threats 4 Artificial Intelligence A threat modeling library to help you build responsible AI_
* [TenSEAL](https://github.com/OpenMined/TenSEAL) - _A library for doing homomorphic encryption operations on tensors_
* [SyMPC](https://github.com/OpenMined/SyMPC) - _A Secure Multiparty Computation companion library for Syft_
* [PyVertical](https://github.com/OpenMined/PyVertical) - _Privacy Preserving Vertical Federated Learning_

## Resources for learning
* [MLSecOps podcast](https://mlsecops.com/podcast)

## Uncategorized useful resources
* [OWASP ML TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/)
* [OWASP LLM TOP 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [OWASP AI Security and Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/)
* [OWASP WrongSecrets LLM exercise](https://wrongsecrets.herokuapp.com/challenge/32)
* [NIST AIRC](https://airc.nist.gov/Home) - NIST Trustworthy & Responsible AI Resource Center
* [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)
* [The MLSecOps Top 10 by Institute for Ethical AI & Machine Learning](https://ethical.institute/security.html)

  
## Research Papers
### Adversarial examples and attacks
* [High Dimensional Spaces, Deep Learning and Adversarial Examples](https://arxiv.org/abs/1801.00634)
* [Adversarial Task Allocation](https://arxiv.org/abs/1709.00358)
* [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945)
* [The Space of Transferable Adversarial Examples](https://arxiv.org/abs/1704.03453)
* [RHMD: Evasion-Resilient Hardware Malware Detectors](http://www.cs.ucr.edu/~kkhas001/pubs/micro17-rhmd.pdf)
* [Generic Black-Box End-to-End Attack against RNNs and Other API Calls Based Malware Classifiers](https://arxiv.org/abs/1707.05970)
* [Vulnerability of Deep Reinforcement Learning to Policy Induction Attacks](https://arxiv.org/abs/1701.04143)
* [Can you fool AI with adversarial examples on a visual Turing test?](https://arxiv.org/abs/1709.08693)
* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)
* [Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452)
* [Crafting Adversarial Input Sequences for Recurrent Neural Networks](https://arxiv.org/abs/1604.08275)
* [Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697)
* [Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN](https://arxiv.org/abs/1702.05983)
* [Data Driven Exploratory Attacks on Black Box Classifiers in Adversarial Domains](https://arxiv.org/abs/1703.07909)
* [Fast Feature Fool: A data independent approach to universal adversarial perturbations](https://arxiv.org/abs/1707.05572v1)
* [Simple Black-Box Adversarial Perturbations for Deep Networks](https://arxiv.org/abs/1612.06299)
* [Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)
* [One pixel attack for fooling deep neural networks](https://arxiv.org/abs/1710.08864v1)
* [FedMLSecurity: A Benchmark for Attacks and Defenses in Federated Learning and LLMs](https://arxiv.org/abs/2306.04959)
* [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483)
* [Bad Characters: Imperceptible NLP Attacks](https://arxiv.org/abs/2106.09898)
* [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)
* [Exploring the Vulnerability of Natural Language Processing Models via Universal Adversarial Texts](https://aclanthology.org/2021.alta-1.14/)
* [Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)
* [Adversarial Attacks on Tables with Entity Swap](https://ceur-ws.org/Vol-3462/TADA4.pdf)

### Model extraction
* [Stealing Machine Learning Models via Prediction APIs](https://arxiv.org/abs/1609.02943)
* [On the Risks of Stealing the Decoding Algorithms of Language Models](https://arxiv.org/abs/2303.04729)

### Evasion
* [Adversarial Demonstration Attacks on Large Language Models](https://arxiv.org/abs/2305.14950)
* [Looking at the Bag is not Enough to Find the Bomb: An Evasion of Structural Methods for Malicious PDF Files Detection](https://pralab.diee.unica.it/sites/default/files/maiorca_ASIACCS13.pdf)
* [Adversarial Generative Nets: Neural Network Attacks on State-of-the-Art Face Recognition](https://arxiv.org/abs/1801.00349)
* [Query Strategies for Evading Convex-Inducing Classifiers](https://people.eecs.berkeley.edu/~adj/publications/paper-files/1007-0484v1.pdf)
* [Adversarial Prompting for Black Box Foundation Models](https://arxiv.org/abs/2302.04237)
* [Automatically Evading Classifiers A Case Study on PDF Malware Classifiers](http://evademl.org/docs/evademl.pdf)
* [Generic Black-Box End-to-End Attack against RNNs and Other API Calls Based Malware Classifiers](https://arxiv.org/abs/1707.05970)
* [Fast Feature Fool: A data independent approach to universal adversarial perturbations](https://arxiv.org/abs/1707.05572v1)
* [GPTs Don’t Keep Secrets: Searching for Backdoor Watermark Triggers in Autoregressive Language Models](https://aclanthology.org/2023.trustnlp-1.21/)

### Poisoning
* [Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)
* [BadGPT: Exploring Security Vulnerabilities of ChatGPT via Backdoor Attacks to InstructGPT](https://arxiv.org/abs/2304.12298)
* [Towards Poisoning of Deep Learning Algorithms with Back-gradient Optimization](https://arxiv.org/abs/1708.08689)
* [Efficient Label Contamination Attacks Against Black-Box Learning Models](https://www.ijcai.org/proceedings/2017/0551.pdf)
* [Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning](https://arxiv.org/abs/2305.04175)
* [UOR: Universal Backdoor Attacks on Pre-trained Language Models](https://arxiv.org/abs/2305.09574)
* [Analyzing And Editing Inner Mechanisms of Backdoored Language Models](http://arxiv.org/abs/2302.12461)
* [Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)
* [How to Backdoor Diffusion Models?](https://arxiv.org/abs/2212.05400)
* [On the Exploitability of Instruction Tuning](https://arxiv.org/abs/2306.17194)
* [Defending against Insertion-based Textual Backdoor Attacks via Attribution](https://aclanthology.org/2023.findings-acl.561/)
* [A Gradient Control Method for Backdoor Attacks on Parameter-Efficient Tuning](https://aclanthology.org/2023.acl-long.194/)
* [BadNL: Backdoor Attacks against NLP Models with Semantic-preserving Improvements](https://arxiv.org/abs/2006.01043)
* [Be Careful about Poisoned Word Embeddings: Exploring the Vulnerability of the Embedding Layers in NLP Models](https://arxiv.org/abs/2103.15543)
* [BadPrompt: Backdoor Attacks on Continuous Prompts](https://arxiv.org/abs/2211.14719)

### Privacy
* [Extracting training data from diffusion models](https://arxiv.org/abs/2301.13188)
* [Prompt Stealing Attacks Against Text-to-Image Generation Models](https://arxiv.org/abs/2305.13873)
* [Are Diffusion Models Vulnerable to Membership Inference Attacks?](https://arxiv.org/abs/2302.01316)
* [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://www.cs.cmu.edu/~mfredrik/papers/fjr2015ccs.pdf)
* [Multi-step Jailbreaking Privacy Attacks on ChatGPT](http://arxiv.org/abs/2304.05197)
* [Flocks of Stochastic Parrots: Differentially Private Prompt Learning for Large Language Models](https://arxiv.org/abs/2305.15594)
* [ProPILE: Probing Privacy Leakage in Large Language Models](https://arxiv.org/abs/2307.01881)

### Injection
* [DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection](https://arxiv.org/abs/2101.06896) 
* [Black Box Adversarial Prompting for Foundation Models](https://arxiv.org/abs/2302.04237)
* [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)
* [Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output Robustness of Large Language Models](https://arxiv.org/abs/2307.08487)
* [Jailbreaker: Automated Jailbreak Across Multiple Large Language Model Chatbots](https://arxiv.org/abs/2307.08715)
* [(Ab)using Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)

### Other research papers
* [Summoning Demons: The Pursuit of Exploitable Bugs in Machine Learning](https://arxiv.org/abs/1701.04739)
* [Automatically Evading Classifiers A Case Study on PDF Malware Classifiers](http://evademl.org/docs/evademl.pdf)
* [capAI - A Procedure for Conducting Conformity Assessment of AI Systems in Line with the EU Artificial Intelligence Act](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4064091)
* [A Study on Robustness and Reliability of Large Language Model Code Generation](https://arxiv.org/abs/2308.10335)
