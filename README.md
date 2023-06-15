# Awesome AI Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ottosulin/awesome-ai-security)

A curated list of awesome AI security related frameworks, attacks, tools and papers. Inspired by `awesome-machine-learning`.

If you want to contribute, create a PR or contact me [@ottosulin](https://twitter.com/ottosulin).

## Related awesome lists
* [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)
* [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)

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

## Offensive tools
* [Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware) - _makes it possible to write agents that learn to manipulate PE files (e.g., malware) to achieve some objective (e.g., bypass AV) based on a reward provided by taking specific manipulation actions_
* [Deep-pwning](https://github.com/cchio/deep-pwning) - _a lightweight framework for experimenting with machine learning models with the goal of evaluating their robustness against a motivated adversary_
* [PrivacyRaven](https://github.com/trailofbits/PrivacyRaven) - _privacy testing library for deep learning systems_
* [StringSifter](https://github.com/fireeye/stringsifter) - _A machine learning tool that ranks strings based on their relevance for malware analysis_
* [Adversarial Machine Learning Library(Ad-lib)](https://github.com/vu-aml/adlib) - _Game-theoretic adversarial machine learning library providing a set of learner and adversary modules_
* [Counterfit](https://github.com/Azure/counterfit) - _generic automation layer for assessing the security of machine learning systems_
* [DeepFool](https://github.com/lts4/deepfool) - _A simple and accurate method to fool deep neural networks_
* [Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)
* [garak](https://github.com/leondz/garak/) - _security probing tool for LLMs_
* [Snaike-MLFlow](https://github.com/protectai/Snaike-MLflow) - _MLflow red team toolsuite_

## Defensive tools
* [PLOT4ai](https://plot4.ai/) - _Privacy Library Of Threats 4 Artificial Intelligence A threat modeling library to help you build responsible AI_
* [ProtectAI's model scanner](https://github.com/protectai/model-scanner) - _Security scanner detecting serialized ML Models performing suspicious actions_
* [rebuff](https://github.com/woop/rebuff) - _Prompt Injection Detector_

## Resources for learning
* [MLSecOps podcast](https://mlsecops.com/podcast)

## Uncategorized useful resources
* [OWASP ML TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/)
* [OWASP LLM TOP 10](https://owasp.org/www-project-machine-learning-security-top-10/ ) - still under development
* [NIST AIRC](https://airc.nist.gov/Home) - NIST Trustworthy & Responsible AI Resource Center
* [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)

## Reserach Papers
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

### Model extraction attacks
* [Stealing Machine Learning Models via Prediction APIs](https://arxiv.org/abs/1609.02943)
* [On the Risks of Stealing the Decoding Algorithms of Language Models](https://arxiv.org/abs/2303.04729)

### Evasion attacks
* [Adversarial Demonstration Attacks on Large Language Models](https://arxiv.org/abs/2305.14950)
* [Looking at the Bag is not Enough to Find the Bomb: An Evasion of Structural Methods for Malicious PDF Files Detection](https://pralab.diee.unica.it/sites/default/files/maiorca_ASIACCS13.pdf)
* [Adversarial Generative Nets: Neural Network Attacks on State-of-the-Art Face Recognition](https://arxiv.org/abs/1801.00349)
* [Query Strategies for Evading Convex-Inducing Classifiers](https://people.eecs.berkeley.edu/~adj/publications/paper-files/1007-0484v1.pdf)
* [Adversarial Prompting for Black Box Foundation Models](https://arxiv.org/abs/2302.04237)
* [Automatically Evading Classifiers A Case Study on PDF Malware Classifiers](http://evademl.org/docs/evademl.pdf)
* [Generic Black-Box End-to-End Attack against RNNs and Other API Calls Based Malware Classifiers](https://arxiv.org/abs/1707.05970)
* [Fast Feature Fool: A data independent approach to universal adversarial perturbations](https://arxiv.org/abs/1707.05572v1)

### Poisoning attacks
* [Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)
* [BadGPT: Exploring Security Vulnerabilities of ChatGPT via Backdoor Attacks to InstructGPT](https://arxiv.org/abs/2304.12298)
* [Towards Poisoning of Deep Learning Algorithms with Back-gradient Optimization](https://arxiv.org/abs/1708.08689)
* [Efficient Label Contamination Attacks Against Black-Box Learning Models](https://www.ijcai.org/proceedings/2017/0551.pdf)
* [Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning](https://arxiv.org/abs/2305.04175)
* [UOR: Universal Backdoor Attacks on Pre-trained Language Models](https://arxiv.org/abs/2305.09574)
* [Analyzing And Editing Inner Mechanisms of Backdoored Language Models](http://arxiv.org/abs/2302.12461)
* [Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)

### Privacy attacks
* [Extracting training data from diffusion models](https://arxiv.org/abs/2301.13188)
* [Prompt Stealing Attacks Against Text-to-Image Generation Models](https://arxiv.org/abs/2305.13873)
* [Are Diffusion Models Vulnerable to Membership Inference Attacks?](https://arxiv.org/abs/2302.01316)
* [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://www.cs.cmu.edu/~mfredrik/papers/fjr2015ccs.pdf)
* [Multi-step Jailbreaking Privacy Attacks on ChatGPT](http://arxiv.org/abs/2304.05197)

### Injection attacks
* [DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection](https://arxiv.org/abs/2101.06896) 
* [Black Box Adversarial Prompting for Foundation Models](https://arxiv.org/abs/2302.04237)

### Other attack related research papers
* [Summoning Demons: The Pursuit of Exploitable Bugs in Machine Learning](https://arxiv.org/abs/1701.04739)
* [Automatically Evading Classifiers A Case Study on PDF Malware Classifiers](http://evademl.org/docs/evademl.pdf)
