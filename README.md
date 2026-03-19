# Attacks and Defenses in Differentially Private Deep Learning: New Security Risks in New Era
<a href="https://www.preprints.org/manuscript/202603.1179" 
   target="_blank" 
   style="display: inline-block; padding: 10px 20px; background-color: #24292e; color: white; text-decoration: none; border-radius: 6px; font-weight: bold;">
   📥 Download Full Paper (PDF)
</a>

![structure_of_survey](assets/structure_of_survey.png)
With the rapid advancement of deep learning, differential privacy has become a key technique for protecting sensitive data with a formal guarantee of privacy. By injecting noise and enforcing privacy budgets, differentially private deep learning (DP-DL) systems are able to protect individual data points yet still maintain a model’s utility. However, recent studies reveal that DP-DL systems can be vulnerable to different types of attacks throughout their lifecycle. Naturally, this has attracted the attention of both academia and industry. Critically, these risks are not the same as those associated with traditional deep learning. This is because the differential privacy mechanism itself introduces new attack surfaces that adversaries can exploit. Our work focuses on the distinct vulnerabilities that can arise at the data, algorithm, and architecture levels. By analyzing representative attacks and corresponding defenses, this survey highlights emerging challenges and outlines promising research directions. Overall, our aim is to make differential privacy more robust and deployable in real-world deep learning systems.

**📍 This survey systematically examines attacks and defenses on DP-DL systems from three perspectives: data level, algorithm level, and architecture level.**


## Update Records
- 2026-03-16: The first version of our survey has been released on preprints.

## Table of Contents
- [Risks in DP-DL](#Risks-in-DP-DL)
- [Attacks on DP-DL systems](#Attacks-on-DP-DL-systems)
- [Defenses for DP-DL systems](#Defenses-for-DP-DL-systems)
- [Defenses](#defenses)
- [Update Records](#update-records)
- [Paper List](#paper-list)
  - [Risks in DP-DL](#Risks-in-DP-DL)
  - [Attacks on DP-DL systems](#Attacks-on-DP-DL-systems)
  - [Defenses for DP-DL systems](#Defenses-for-DP-DL-systems)
  - [Defenses against External Interaction Attacks](#defenses-against-external-interaction-attacks)
  - [Defenses against Internal Cognitive Attacks](#defenses-against-internal-cognitive-attacks)
  - [Defenses against Multi-Agent Collaboration Attacks](#defenses-against-multi-agent-collaboration-attacks)
  - [Security Frameworks](#security-frameworks)
  - [Security Benchmarks](#security-benchmarks)
- [Citation](#citation)
- [Acknowledgement](#acknowledgement)
- [Contact Us](#contact-us)

## Risks in DP-DL
Focus: attacks on the agent-environment interface, including tool metadata manipulation and environment/data injection.

![Risks in DP-DL](assets/Risk_Analysis_Framework.png)

## Attacks on DP-DL systems
Focus: attacks on planning, reasoning, memory, and model internals, with persistent and covert effects.

![Internal Cognitive Attacks](assets/survey-4.png)

## Defenses for DP-DL systems
Focus: attacks on communication, coordination logic, and role trust in multi-agent systems.

![Multi-Agent Collaboration Attacks](assets/survey-5.png)

## Defenses
Focus: defense design space for external interaction attacks, internal cognitive attacks, and multi-agent collaboration attacks.

![Defenses](assets/survey-6.png)




## Paper List

### Risks in DP-DL
- Resisting structural re-identification in anonymized social networks, VLDB J 2010.12, [[paper](https://doi.org/10.1007/s00778-010-0210-x)]
- Applications of Differential Privacy in Social Network Analysis: A Survey, IEEE Trans. Knowl. Data Eng. 2023.01 [[paper](https://doi.org/10.1109/TKDE.2021.3073062)]
- Applications of deep learning for the analysis of medical data, Archives of pharmacal research 2019.06 [[paper](https://link.springer.com/article/10.1007/s12272-019-01162-9)]
- Dataset correlation inference attacks against machine learning models, arXiv 2021.12 [[paper](https://arxiv.org/abs/2112.08806)]
- Exploiting attribute correlation for reconstruction attacks on differentially private multi-attributed data, Journal of Information Security and Applications 2025.11 [[paper](https://www.sciencedirect.com/science/article/pii/S2214212625002613?via%3Dihub)]
- Large Language Models Can Be Strong Differentially Private Learners, arXiv 2021.10 [[paper](https://arxiv.org/abs/2110.05679)]
- Differentially Private Fine-tuning of Language Models, In The Tenth International Conference on Learning Representations 2022.01 [[paper](https://openreview.net/forum?id=Q42f0dfjECO)]
- Synthetic Text Generation with Differential Privacy: A Simple and Practical Recipe, In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics 2023.07 [[paper](https://aclanthology.org/2023.acl-long.74/)]
- Privacy-Preserving In-Context Learning with Differentially Private Few-Shot Generation, In The Twelfth International Conference on Learning Representations 2024.01 [[paper](https://openreview.net/forum?id=oZtt0pRnOl)]
- Mind the Privacy Unit! User-Level Differential Privacy for Language Model Fine-Tuning, arXiv 2024.06 [[paper](https://arxiv.org/abs/2406.14322)]
- In Differential Privacy, There is Truth: on Vote-Histogram Leakage in Ensemble Private Learning, arXiv 2022.09 [[paper](https://arxiv.org/abs/2209.10732)]
- Implicit Bias in Noisy-SGD: With Applications to Differentially Private Training. In International Conference on Artificial Intelligence and Statistics 2024.05 [[paper](https://proceedings.mlr.press/v238/sander24a.html)]
- Differentially Private Learning with Small Public Data. In The Thirty-Fourth AAAI Conference on Artificial Intelligence 2020.02  [[paper](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/aaai20ppsgd.pdf)]
- Learning Model-Based Privacy Protection under Budget Constraints. In Thirty-Fifth AAAI Conference on Artificial Intelligence 2021.02 [[paper](https://www.semanticscholar.org/paper/Learning-Model-Based-Privacy-Protection-under-Hong-Wang/c398f8a81d10c0d582dfae6d7896870d0acd6d82)]
- Private non-smooth erm and sco in subquadratic steps. Advances in Neural Information Processing Systems 2021 [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/file/211c1e0b83b9c69fa9c4bdede203c1e3-Paper.pdf)]
- On significance of the least significant bits for differential privacy. In the ACM Conference on Computer and Communications Security 2012.10 [[paper](https://dl.acm.org/doi/10.1145/2382196.2382264)]
- Are We There Yet? Timing and Floating-Point Attacks on Differential Privacy Systems. In 43rd IEEE Symposium on Security and Privacy 2022.05 [[paper](https://ieeexplore.ieee.org/document/9833672)]
- Precision-based attacks and interval refining: how to break, then fix, differential privacy on finite computers. arXiv 2022.07 [[paper](https://arxiv.org/abs/2207.13793)]
- Auditing privacy budget of differentially private neural network models, Neurocomputing 2025.01, [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231224015273?via%3Dihub)]
- Tighter Privacy Auditing of DP-SGD in the Hidden State Threat Model. arXiv 2024.05 [[paper](https://arxiv.org/abs/2405.14457)]
- Evaluating Differentially Private Machine Learning in Practice, USENIX Security 2019.08, [[paper](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman)]
- Nearly Tight Black-Box Auditing of Differentially Private Machine Learning, NeurIPS 2024.12, [[paper](http://papers.nips.cc/paper_files/paper/2024/hash/ed93b2b5722acc2341d421b8916404a1-Abstract-Conference.html)]
- Auditing Privacy Defenses in Federated Learning via Generative Gradient Leakage, CVPR 2022.06, [[paper](https://doi.org/10.1109/CVPR52688.2022.00989)]
- Gradient Obfuscation Gives a False Sense of Security in Federated Learning, USENIX Security 2023.08, [[paper](https://www.usenix.org/conference/usenixsecurity23/presentation/yue)]
- Local Differential Privacy Is Not Enough: A Sample Reconstruction Attack Against Federated Learning With Local Differential Privacy, IEEE TIFS 2025, [[paper](https://doi.org/10.1109/TIFS.2024.3515793)]
- Does Differential Privacy Really Protect Federated Learning From Gradient Leakage Attacks?, IEEE TMC 2024, [[paper](https://doi.org/10.1109/TMC.2024.3417930)]
- Reconstructing Individual Data Points in Federated Learning Hardened with Differential Privacy and Secure Aggregation, EuroS&P 2023.07, [[paper](https://doi.org/10.1109/EUROSP57164.2023.00023)]
- Auditing differentially private machine learning: how private is private SGD?. In Proceedings of the 34th International Conference on Neural Information Processing Systems 2020 [[paper](https://proceedings.neurips.cc/paper/2020/file/fc4ddc15f9f4b4b06ef7844d6bb53abf-Paper.pdf)]
- Threats to Training: A Survey of Poisoning Attacks and Defenses on Machine Learning Systems, ACM Computing Surveys 2023.12, [[paper](https://doi.org/10.1145/3538707)]

### Attacks on DP-DL systems
- Are Attribute Inference Attacks Just Imputation?, CCS 2022.11, [[paper](https://doi.org/10.1145/3548606.3560663)]
- Dataset Correlation Inference Attacks Against Machine Learning Models, arXiv 2021.12, [[paper](https://arxiv.org/abs/2112.08806)]
- User Inference Attacks on Large Language Models, EMNLP 2024.11, [[paper](https://doi.org/10.18653/V1/2024.EMNLP-MAIN.1014)]
- Averaging Attacks on Bounded Noise-based Disclosure Control Algorithms, PoPETs 2020, [[paper](https://doi.org/10.2478/popets-2020-0031)]
- In Differential Privacy, There is Truth: On Vote-Histogram Leakage in Ensemble Private Learning, NeurIPS 2022, [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/ba8d1b46292c5e82cbfb3b3dc3b968af-Paper-Conference.pdf)]
- Monitoring-Based Differential Privacy Mechanism Against Query Flooding-Based Model Extraction Attack, IEEE TDSC 2022, [[paper](https://doi.org/10.1109/TDSC.2021.3069258)]
- Are We There Yet? Timing and Floating-Point Attacks on Differential Privacy Systems, IEEE S&P 2022.05, [[paper](https://doi.org/10.1109/SP46214.2022.9833672)]
- On Significance of the Least Significant Bits for Differential Privacy, CCS 2012.10, [[paper](https://doi.org/10.1145/2382196.2382264)]
- Membership Inference Attack against Differentially Private Deep Learning Model, Transactions on Data Privacy 2018, [[paper](http://www.tdp.cat/issues16/tdp.a289a17.pdf)]
- Evaluating Differentially Private Machine Learning in Practice, USENIX Security 2019.08, [[paper](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman)]
- Membership Inference Attacks Against Machine Learning Models, IEEE S&P 2017.05, [[paper](https://doi.org/10.1109/SP.2017.41)]
- Membership Inference Attack on Differentially Private Block Coordinate Descent, PeerJ Computer Science 2023, [[paper](https://doi.org/10.7717/peerj-cs.1616)]
- Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting, IEEE CSF 2018.07, [[paper](https://doi.org/10.1109/CSF.2018.00027)]
- Deep Leakage from Gradients, NeurIPS 2019.12, [[paper](https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html)]
- Inverting Gradients – How Easy Is It to Break Privacy in Federated Learning?, NeurIPS 2020.12, [[paper](https://proceedings.neurips.cc/paper/2020/hash/c4ede56bbd98819ae6112b20ac6bf145-Abstract.html)]
- See Through Gradients: Image Batch Recovery via GradInversion, CVPR 2021.06, [[paper](https://doi.org/10.1109/CVPR46437.2021.01607)]
- Does Differential Privacy Really Protect Federated Learning From Gradient Leakage Attacks?, IEEE TMC 2024, [[paper](https://doi.org/10.1109/TMC.2024.3417930)]
- Local Differential Privacy Is Not Enough: A Sample Reconstruction Attack Against Federated Learning With Local Differential Privacy, IEEE TIFS 2025, [[paper](https://doi.org/10.1109/TIFS.2024.3515793)]
- Does Differential Privacy Really Protect Federated Learning From Gradient Leakage Attacks?, IEEE TMC 2024, [[paper](https://doi.org/10.1109/TMC.2024.3417930)]
- GI-NAS: Boosting Gradient Inversion Attacks Through Adaptive Neural Architecture Search, IEEE TIFS 2025, [[paper](https://doi.org/10.1109/TIFS.2025.3589127)]
- Evaluating Privacy Loss in Differential Privacy Based Federated Learning, Future Generation Computer Systems 2025, [[paper](https://doi.org/10.1016/j.future.2025.107848)]
- Auditing differentially private machine learning: how private is private SGD?. In Proceedings of the 34th International Conference on Neural Information Processing Systems 2020 [[paper](https://proceedings.neurips.cc/paper/2020/file/fc4ddc15f9f4b4b06ef7844d6bb53abf-Paper.pdf)]
- - Mean Aggregator Is More Robust than Robust Aggregators under Label Poisoning Attacks on Distributed Heterogeneous Data, JMLR 2025, [[paper](http://jmlr.org/papers/v26/27.html)]
- Manipulation Attacks in Local Differential Privacy, IEEE S&P 2021.05, [[paper](https://doi.org/10.1109/SP40001.2021.00001)]
- On Evaluating the Poisoning Robustness of Federated Learning under Local Differential Privacy, arXiv 2025.09, [[paper](https://arxiv.org/abs/2509.05265)]
- DP-Poison: Poisoning Federated Learning under the Cover of Differential Privacy, ACM Transactions on Privacy and Security 2025, [[paper](https://doi.org/10.1145/3702325)]
- Model Poisoning Attack in Differential Privacy-Based Federated Learning, Information Sciences 2023, [[paper](https://doi.org/10.1016/j.ins.2023.02.025)]

### Defenses for DP-DL systems
- Principal Component Analysis in the Local Differential Privacy Model, IJCAI 2019.08, [[paper](https://doi.org/10.24963/IJCAI.2019/666)]
- Stochastic Algorithms with Descent Guarantees for ICA, AISTATS 2019.04, [[paper](http://proceedings.mlr.press/v89/ablin19a.html)]
- Causal Feature Selection for Algorithmic Fairness, SIGMOD 2022.06, [[paper](https://doi.org/10.1145/3514221.3517909)]
- Automated Feature Engineering for Algorithmic Fairness, VLDB 2021, [[paper](https://doi.org/10.14778/3461535.3463474)]
- DP-GAN: Differentially Private Consecutive Data Publishing Using Generative Adversarial Nets, Journal of Network and Computer Applications 2021, [[paper](https://doi.org/10.1016/j.jnca.2021.103066)]
- DP-VAE: Human-Readable Text Anonymization for Online Reviews with Differentially Private Variational Autoencoders, WWW 2022.04, [[paper](https://doi.org/10.1145/3485447.3512232)]
- PrivDiffuser: Privacy-Guided Diffusion Model for Data Obfuscation in Sensor Networks, PoPETs 2025, [[paper](https://doi.org/10.56553/popets-2025-0118)]
- Learning with User-Level Privacy, NeurIPS 2021.12, [[paper](https://proceedings.neurips.cc/paper/2021/hash/67e235e7f2fa8800d8375409b566e6b6-Abstract.html)]
- User-Level Differential Privacy With Few Examples Per User, NeurIPS 2023.12, [[paper](http://papers.nips.cc/paper_files/paper/2023/hash/3d57795f0e263aa69577f1bbceade46b-Abstract-Conference.html)]
- Fine-Tuning Large Language Models with User-Level Differential Privacy, arXiv 2024.07, [[paper](https://arxiv.org/abs/2407.07737)]
- Monitoring-Based Differential Privacy Mechanism Against Query Flooding-Based Model Extraction Attack, IEEE TDSC 2022, [[paper](https://doi.org/10.1109/TDSC.2021.3069258)]
- The Optimal Upper Bound of the Number of Queries for Laplace Mechanism under Differential Privacy, Information Sciences 2019, [[paper](https://doi.org/10.1016/j.ins.2019.07.001)]
- Privacy Odometers and Filters: Pay-as-you-Go Composition, NeurIPS 2016.12, [[paper](https://proceedings.neurips.cc/paper/2016/hash/58c54802a9fb9526cd0923353a34a7ae-Abstract.html)]
- Are We There Yet? Timing and Floating-Point Attacks on Differential Privacy Systems, IEEE S&P 2022.05, [[paper](https://doi.org/10.1109/SP46214.2022.9833672)]
- Precision-Based Attacks and Interval Refining: How to Break, Then Fix, Differential Privacy on Finite Computers, arXiv 2022.07, [[paper](https://arxiv.org/abs/2207.13793)]
- On Significance of the Least Significant Bits for Differential Privacy, CCS 2012.10, [[paper](https://doi.org/10.1145/2382196.2382264)]
- Securing Floating-Point Arithmetic for Noise Addition. In Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security 2024.09 [[paper](https://dl.acm.org/doi/10.1145/3658644.3690347)]
- DP-SGD Without Clipping: The Lipschitz Neural Network Way. In The Twelfth International Conference on Learning Representations, ICLR 2024.05 [[paper](https://openreview.net/forum?id=BEyEziZ4R6)]
- Dpnas: Neural architecture search for deep learning with differential privacy. In Proceedings ofthe AAAIconference on artificial intelligence 2022.06 [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/20586)]
- Tempered sigmoid activations for deep learning with differential privacy, In Proceedings ofthe AAAI conference on artificial intelligence 2021.05 [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17123)]
- Losing Less: A Loss for Differentially Private Deep Learning, PoPETs 2023, [[paper](https://doi.org/10.56553/popets-2023-0083)]
- Auditing Privacy Budget of Differentially Private Neural Network Models, Neurocomputing 2025, [[paper](https://doi.org/10.1016/j.neucom.2024.128756)]
- Tighter Privacy Auditing of DP-SGD in the Hidden State Threat Model, arXiv 2024.05, [[paper](https://arxiv.org/abs/2405.14457)]
- Nearly tight black-box auditing of differentially private machine learning, Advances in Neural Information Processing Systems 2024, [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ed93b2b5722acc2341d421b8916404a1-Abstract-Conference.html)]
- Exploring the Privacy-Accuracy Trade-Off Using Adaptive Gradient Clipping in Federated Learning, IEEE TNSE 2025, [[paper](https://doi.org/10.1109/TNSE.2025.3546777)]
- Adap DP-FL: Differentially Private Federated Learning with Adaptive Noise, TrustCom 2022.12, [[paper](https://doi.org/10.1109/TRUSTCOM56396.2022.00094)]
- ADPFL: Adaptive Differential Privacy-Enhanced Federated Learning, IEEE Internet of Things Journal 2025, [[paper](https://doi.org/10.1109/JIOT.2025.3611410)]
- Securing Distributed SGD Against Gradient Leakage Threats, IEEE TPDS 2023, [[paper](https://doi.org/10.1109/TPDS.2023.3273490)]
- Staged Noise Perturbation for Privacy-Preserving Federated Learning, IEEE TSUSC 2024, [[paper](https://doi.org/10.1109/TSUSC.2024.3381812)]
- Towards Adaptive Privacy Protection for Interpretable Federated Learning, IEEE TMC 2024, [[paper](https://doi.org/10.1109/TMC.2024.3443862)]
- More Than Enough Is Too Much: Adaptive Defenses Against Gradient Leakage in Production Federated Learning, IEEE/ACM TON 2024, [[paper](https://doi.org/10.1109/TNET.2024.3377655)]

#### Defenses against External Interaction Attacks 
- Promptarmor: Simple yet effective prompt injection defenses, arXiv 2025.07 [[paper](https://arxiv.org/abs/2507.15219)]
- To Protect the LLM Agent Against the Prompt Injection Attack with Polymorphic Prompt, 2025 55th Annual IEEE/IFIP International Conference on Dependable Systems and Networks - Supplemental Volume (DSN-S) 2025.01 [[paper](https://scholar.google.com/scholar?q=To%20Protect%20the%20LLM%20Agent%20Against%20the%20Prompt%20Injection%20Attack%20with%20Polymorphic%20Prompt)]
- IsolateGPT: An Execution Isolation Architecture for LLM-Based Agentic Systems, NDSS 2025.01 [[paper](https://scholar.google.com/scholar?q=IsolateGPT%3A%20An%20Execution%20Isolation%20Architecture%20for%20LLM-Based%20Agentic%20Systems)]
- AirGapAgent: Protecting Privacy-Conscious Conversational Agents, Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security 2024.01 [[paper](https://scholar.google.com/scholar?q=AirGapAgent%3A%20Protecting%20Privacy-Conscious%20Conversational%20Agents)]
- CaMeLs Can Use Computers Too: System-level Security for Computer Use Agents, arXiv 2026.01 [[paper](https://arxiv.org/abs/2601.09923)]
- The task shield: Enforcing task alignment to defend against indirect prompt injection in llm agents, Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) 2025.01 [[paper](https://scholar.google.com/scholar?q=The%20task%20shield%3A%20Enforcing%20task%20alignment%20to%20defend%20against%20indirect%20prompt%20injection%20in%20llm%20agents)]
- MELON: Provable Defense Against Indirect Prompt Injection Attacks in AI Agents, Proceedings of the 42nd International Conference on Machine Learning (ICML) 2025.01 [[paper](https://scholar.google.com/scholar?q=MELON%3A%20Provable%20Defense%20Against%20Indirect%20Prompt%20Injection%20Attacks%20in%20AI%20Agents)]
- ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning, Forty-second International Conference on Machine Learning 2025.01 [[paper](https://scholar.google.com/scholar?q=ShieldAgent%3A%20Shielding%20Agents%20via%20Verifiable%20Safety%20Policy%20Reasoning)]
- Ipiguard: A novel tool dependency graph-based defense against indirect prompt injection in llm agents, Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing 2025.01 [[paper](https://scholar.google.com/scholar?q=Ipiguard%3A%20A%20novel%20tool%20dependency%20graph-based%20defense%20against%20indirect%20prompt%20injection%20in%20llm%20agents)]
- DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents, arXiv 2025.06 [[paper](https://arxiv.org/abs/2506.12104)]
- ALRPHFS: Adversarially Learned Risk Patterns with Hierarchical Fast& Slow Reasoning for Robust Agent Defense, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.19260)]

#### Defenses against Internal Cognitive Attacks
- Your Agent Can Defend Itself against Backdoor Attacks, arXiv 2025.06 [[paper](https://arxiv.org/abs/2506.08336)]
- A Survey on Autonomy-Induced Security Risks in Large Model-Based Agents, arXiv 2025.06 [[paper](https://arxiv.org/abs/2506.23844)]
- Get Experience from Practice: LLM Agents with Record & Replay, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.17716)]
- Check Yourself Before You Wreck Yourself: Selectively Quitting Improves LLM Agent Safety, arXiv 2025.10 [[paper](https://arxiv.org/abs/2510.16492)]
- A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory, arXiv 2025.10 [[paper](https://arxiv.org/abs/2510.02373)]
- Agentsafe: Safeguarding large language model-based multi-agent systems via hierarchical data management, arXiv 2025.03 [[paper](https://arxiv.org/abs/2503.04392)]
- Memory Poisoning Attack and Defense on Memory Based LLM-Agents, arXiv 2026.01 [[paper](https://arxiv.org/abs/2601.05504)]
- AdvEvo-MARL: Shaping Internalized Safety through Adversarial Co-Evolution in Multi-Agent Reinforcement Learning, arXiv 2025.10 [[paper](https://arxiv.org/abs/2510.01586)]
- Real ai agents with fake memories: Fatal context manipulation attacks on web3 agents, arXiv 2025.03 [[paper](https://arxiv.org/abs/2503.16248)]

#### Defenses against Multi-Agent Collaboration Attacks
- G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems, Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) 2025.01 [[paper](https://scholar.google.com/scholar?q=G-Safeguard%3A%20A%20Topology-Guided%20Security%20Lens%20and%20Treatment%20on%20LLM-based%20Multi-agent%20Systems)]
- GUARDIAN: Safeguarding LLM Multi-Agent Collaborations with Temporal Graph Modeling, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.19234)]
- Blindguard: Safeguarding llm-based multi-agent systems under unknown attacks, arXiv 2025.08 [[paper](https://arxiv.org/abs/2508.08127)]
- INFA-Guard: Mitigating Malicious Propagation via Infection-Aware Safeguarding in LLM-Based Multi-Agent Systems, arXiv 2026.01 [[paper](https://arxiv.org/abs/2601.14667)]
- Who's the Mole? Modeling and Detecting Intention-Hiding Malicious Agents in LLM-Based Multi-Agent Systems, arXiv 2025.07 [[paper](https://arxiv.org/abs/2507.04724)]
- MedSentry: Understanding and Mitigating Safety Risks in Medical LLM Multi-Agent Systems, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.20824)]
- 2025 IEEE International Conference on Information Reuse and Integration and Data Science (IRI), 2025 IEEE International Conference on Information Reuse and Integration and Data Science (IRI) 2025.01 [[paper](https://scholar.google.com/scholar?q=2025%20IEEE%20International%20Conference%20on%20Information%20Reuse%20and%20Integration%20and%20Data%20Science%20%28IRI%29)]
- On the Resilience of LLM-Based Multi-Agent Collaboration with Faulty Agents, Forty-second International Conference on Machine Learning 2025.01 [[paper](https://scholar.google.com/scholar?q=On%20the%20Resilience%20of%20LLM-Based%20Multi-Agent%20Collaboration%20with%20Faulty%20Agents)]
- Enhancing robustness of LLM-driven multi-agent systems through randomized smoothing, Chinese Journal of Aeronautics 2025.01 [[paper](https://scholar.google.com/scholar?q=Enhancing%20robustness%20of%20LLM-driven%20multi-agent%20systems%20through%20randomized%20smoothing)]
- CoTGuard: Using Chain-of-Thought Triggering for Copyright Protection in Multi-Agent LLM Systems, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.19405)]

#### Security Frameworks
- Aios: Llm agent operating system, arXiv 2024.03 [[paper](https://arxiv.org/abs/2403.16971)]
- IsolateGPT: An Execution Isolation Architecture for LLM-Based Agentic Systems, NDSS 2025.01 [[paper](https://scholar.google.com/scholar?q=IsolateGPT%3A%20An%20Execution%20Isolation%20Architecture%20for%20LLM-Based%20Agentic%20Systems)]
- Airgapagent: Protecting privacy-conscious conversational agents, Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security 2024.01 [[paper](https://scholar.google.com/scholar?q=Airgapagent%3A%20Protecting%20privacy-conscious%20conversational%20agents)]
- Security of ai agents, 2025 IEEE/ACM International Workshop on Responsible AI Engineering (RAIE) 2025.01 [[paper](https://scholar.google.com/scholar?q=Security%20of%20ai%20agents)]
- TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution, Trustworthy Multi-modal Foundation Models and AI Agents (TiFA) 2024.01 [[paper](https://scholar.google.com/scholar?q=TrustAgent%3A%20Towards%20Safe%20and%20Trustworthy%20LLM-based%20Agents%20through%20Agent%20Constitution)]
- ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning, Forty-second International Conference on Machine Learning 2025.01 [[paper](https://scholar.google.com/scholar?q=ShieldAgent%3A%20Shielding%20Agents%20via%20Verifiable%20Safety%20Policy%20Reasoning)]
- Position: Trustworthy AI Agents Require the Integration of Large Language Models and Formal Methods, Forty-second International Conference on Machine Learning Position Paper Track 2025.01 [[paper](https://scholar.google.com/scholar?q=Position%3A%20Trustworthy%20AI%20Agents%20Require%20the%20Integration%20of%20Large%20Language%20Models%20and%20Formal%20Methods)]
- AgentBreeder: Mitigating the AI Safety Impact of Multi-Agent Scaffolds via Self-Improvement, Scaling Self-Improving Foundation Models without Human Supervision 2025.01 [[paper](https://scholar.google.com/scholar?q=AgentBreeder%3A%20Mitigating%20the%20AI%20Safety%20Impact%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement)]
- Shapley-Coop: Credit Assignment for Emergent Cooperation in Self-Interested LLM Agents, arXiv 2025.06 [[paper](https://arxiv.org/abs/2506.07388)]
- Securing agentic ai: A comprehensive threat model and mitigation framework for generative ai agents, arXiv 2025.04 [[paper](https://arxiv.org/abs/2504.19956)]
- Sentinel Agents for Secure and Trustworthy Agentic AI in Multi-Agent Systems, arXiv 2025.09 [[paper](https://arxiv.org/abs/2509.14956)]
- Llamafirewall: An open source guardrail system for building secure ai agents, arXiv 2025.05 [[paper](https://arxiv.org/abs/2505.03574)]

#### Security Benchmarks
- AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents, The Thirteenth International Conference on Learning Representations 2025.01 [[paper](https://scholar.google.com/scholar?q=AgentHarm%3A%20A%20Benchmark%20for%20Measuring%20Harmfulness%20of%20LLM%20Agents)]
- OpenAgentSafety: A Comprehensive Framework for Evaluating Real-World AI Agent Safety, arXiv 2025.07 [[paper](https://arxiv.org/abs/2507.06134)]
- Agentauditor: Human-level safety and security evaluation for llm agents, arXiv 2025.06 [[paper](https://arxiv.org/abs/2506.00641)]
- Ali-agent: Assessing llms' alignment with human values via agent-based evaluation, Advances in Neural Information Processing Systems 2024.01 [[paper](https://scholar.google.com/scholar?q=Ali-agent%3A%20Assessing%20llms%27%20alignment%20with%20human%20values%20via%20agent-based%20evaluation)]
- Identifying the Risks of LM Agents with an LM-Emulated Sandbox, The Twelfth International Conference on Learning Representations 2024.01 [[paper](https://scholar.google.com/scholar?q=Identifying%20the%20Risks%20of%20LM%20Agents%20with%20an%20LM-Emulated%20Sandbox)]
- Agentdojo: A dynamic environment to evaluate prompt injection attacks and defenses for llm agents, Advances in Neural Information Processing Systems 2024.01 [[paper](https://scholar.google.com/scholar?q=Agentdojo%3A%20A%20dynamic%20environment%20to%20evaluate%20prompt%20injection%20attacks%20and%20defenses%20for%20llm%20agents)]
- ToolFuzz--Automated Agent Tool Testing, arXiv 2025.03 [[paper](https://arxiv.org/abs/2503.04479)]
- Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents, The Thirteenth International Conference on Learning Representations 2025.01 [[paper](https://scholar.google.com/scholar?q=Agent%20Security%20Bench%20%28ASB%29%3A%20Formalizing%20and%20Benchmarking%20Attacks%20and%20Defenses%20in%20LLM-based%20Agents)]
- Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools, The Thirty-ninth Annual Conference on Neural Information Processing Systems 2025.01 [[paper](https://scholar.google.com/scholar?q=Attractive%20Metadata%20Attack%3A%20Inducing%20LLM%20Agents%20to%20Invoke%20Malicious%20Tools)]
- WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks, ICML 2025 Workshop on Computer Use Agents 2025.01 [[paper](https://scholar.google.com/scholar?q=WASP%3A%20Benchmarking%20Web%20Agent%20Security%20Against%20Prompt%20Injection%20Attacks)]
- Dissecting Adversarial Robustness of Multimodal LM Agents, The Thirteenth International Conference on Learning Representations 2025.01 [[paper](https://scholar.google.com/scholar?q=Dissecting%20Adversarial%20Robustness%20of%20Multimodal%20LM%20Agents)]
- ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning, Forty-second International Conference on Machine Learning 2025.01 [[paper](https://scholar.google.com/scholar?q=ShieldAgent%3A%20Shielding%20Agents%20via%20Verifiable%20Safety%20Policy%20Reasoning)]
- Redcode: Risky code execution and generation benchmark for code agents, Advances in Neural Information Processing Systems 2024.01 [[paper](https://scholar.google.com/scholar?q=Redcode%3A%20Risky%20code%20execution%20and%20generation%20benchmark%20for%20code%20agents)]
- Breaking the code: Security assessment of ai code agents through systematic jailbreaking attacks, arXiv 2025.10 [[paper](https://arxiv.org/abs/2510.01359)]
- CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Web Application Vulnerabilities, Proceedings of the 42nd International Conference on Machine Learning (ICML) 2025.01 [[paper](https://scholar.google.com/scholar?q=CVE-Bench%3A%20A%20Benchmark%20for%20AI%20Agents%27%20Ability%20to%20Exploit%20Real-World%20Web%20Application%20Vulnerabilities)]
- SafeArena: Evaluating the Safety of Autonomous Web Agents, Forty-second International Conference on Machine Learning 2025.01 [[paper](https://scholar.google.com/scholar?q=SafeArena%3A%20Evaluating%20the%20Safety%20of%20Autonomous%20Web%20Agents)]
- AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents, Proceedings of the 39th Annual Conference on Neural Information Processing Systems (NeurIPS 2025) Datasets and Benchmarks Track 2025.01 [[paper](https://scholar.google.com/scholar?q=AgentDAM%3A%20Privacy%20Leakage%20Evaluation%20for%20Autonomous%20Web%20Agents)]

## Citation
If you find this survey useful, please cite:
```bibtex
@article{202603.1179,
	doi = {10.20944/preprints202603.1179.v1},
	url = {https://doi.org/10.20944/preprints202603.1179.v1},
	year = 2026,
	month = {March},
	publisher = {Preprints},
	author = {Kaiyan Zhao and Zhe Sun and Lihua Yin and Tianqing Zhu},
	title = {Attacks and Defenses in Differentially Private Deep Learning: New Security Risks in New Era},
	journal = {Preprints}
}
```

## Acknowledgement
Thanks to all collaborators and the open-source research community whose work is summarized in this repository.

## Contact Us
For suggestions or corrections, please contact:
- syg15688708938@163.com
