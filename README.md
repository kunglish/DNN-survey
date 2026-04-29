<h1 align = "center">🧭 The Survey of DNN Testing
</h1>
<!-- <p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"></a>
  <a href="https://arxiv.org/abs/2405.01466"><img src="https://img.shields.io/badge/arXiv-2405.01466-blue.svg"></a>
  <img src="https://img.shields.io/github/stars/iSEngLab/AwesomeLLM4APR?color=yellow&label=Stars">
  <img src="https://img.shields.io/badge/PRs-Welcome-red">
  <img src="https://img.shields.io/github/last-commit/iSEngLab/AwesomeLLM4APR">
</p> -->

**We selected five authoritative databases (ACM Digital Library ([ACM](https://dl.acm.org/)), IEEE Xplore Digital Library ([IEEE](https://ieeexplore.ieee.org/Xplore/home.jsp)), Springer Online Library ([Springer](https://link.springer.com/)), Elsevier Science Direct ([Elsevier](https://www.sciencedirect.com/)), and Wiley Online Library ([Wiley](https://onlinelibrary.wiley.com/))) as data sources. A total of 347 papers related to deep neural network (DNN) testing published between 2017 and 2025 were selected.**



## 📖 Contents

<!-- - [⭐ Citation](#-citation) -->
- [🧩 Applications and Domains](#applications-and-domains)
  - [Image Classification System Testing](#image-classification-system-testing)
  - [Autonomous Driving System Testing](#autonomous-driving-system-testing)
  - [Large Language Model Testing](#large-language-model-testing)
  - [Text Classification System Testing](#text-classification-system-testing)
  - [Recommendation System Testing](#recommendation-system-testing)
  - [Object Detection System Tesing](#object-detection-system-tesing)
  - [Speech Recognition System Testing](#speech-recognition-system-testing)
  - [Code Detection System Testing](#code-detection-system-testing)
  - [Machine Translation System Testing](#machine-translation-system-testing)
  - [Dialogue System Testing](#dialogue-system-testing)
  - [Airborne Collision Avoidance System Testing](#airborne-collision-avoidance-system-testing)
  - [Semantic Segmentation System Testing](#semantic-segmentation-system-testing)
  - [Video Classification System Testing](#video-classification-system-testing)
  - [Video Detection System Testing](#video-detection-system-testing)
  - [Malware Detection System Testing](#malware-detection-system-testing)
  - [Smart Home System Testing](#smart-home-system-testing)
- [🔗 Related DNN Testing Surveys](#related-DNN-testing-surveys)

[//]: # (- [📌 Available Tools]&#40;#available-tools&#41;)


<!-- ## 👏 Citation

```bibtex
@article{zhang2024survey,
  title={A Systematic Literature Review on Large Language Models for Automated Program Repair},
  author={Zhang, Quanjun and Fang, Chunrong and Xie, Yang and Ma, Yuxiang and Sun, Weisong and Yang, Yun and Chen, Zhenyu},
  journal={arXiv preprint arXiv:2405.01466}
  year={2024}
}

``` -->


<!-- ## 🔥🔥 New Papers -->

## 🧩 Applications and Domains
**We categorized the DNN test papers we surveyed by domain (⚠️note that a paper may cover multiple domains, so you may find it in multiple categories), and the detailed categorization is as follows:**

### Image Classification System Testing
1. Navigating the Testing of Evolving Deep Learning Systems: An Exploratory Interview Study [2025-ICSE] [[paper](https://www.computer.org/csdl/proceedings-article/icse/2025/056900a643/251mGh4tJn2)]
2. Measuring Training Variability From Stochastic Optimization Using Robust Nonparametric Testing [2025-JSTSP] [[paper](https://ieeexplore.ieee.org/abstract/document/11053660)]
3. DeepKernel: 2D-kernels Clustering Based Mutant Reduction for Cost-effective Deep Learning Model Testing [2025-JSS] [[paper](https://www.sciencedirect.com/science/article/pii/S0164121224002917)]
4. Robust Testing for Deep Learning using Human Label Noise [2025-DeepTest] [[paper](https://ieeexplore.ieee.org/abstract/document/11026911)]
5. Selection of Test Samples to Improve DNN Test Efficiency Based on Neuron Clusters [2025-NCA] [[paper](https://link.springer.com/article/10.1007/s00521-024-10894-9)]
6. TestifAI: Probabilistic Context-Aware Testing For Safe Deep Learning Models [2025-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/11024417)]
7. Enhancing Mutation Testing for Deep Neural Networks: A Novel Approach to Generating High-quality Mutants [2025-ASE] [[paper](https://link.springer.com/article/10.1007/s10515-025-00581-x)]
8. DiffGAN: A Test Generation Approach for Differential Testing of Deep Neural Networks for Image Analysis [2025-TOSEM] [[paper](https://ieeexplore.ieee.org/abstract/document/11173835)]
9. Adversarial Generation of Deep Neural Network Image Test Cases Based on Multi-Conditional Constraints [2025-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/11173506)]
10. MetaPri: Test Input Prioritization Based on Metamorphic Testing [2025-CSECS] [[paper](https://ieeexplore.ieee.org/abstract/document/11009647)]
11. BDTest: A Diversity-Oriented Test Case Generation Framework for Deep Neural Networks in 6G-IOT [2025-IoT] [[paper](https://ieeexplore.ieee.org/abstract/document/11186810)]
12. DeepCNP: An Efficient White-Box Testing of Deep Neural Networks by Aligning Critical Neuron Paths [2025-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584924002453)]
13. CtrlFuzz: A Controllable Diffusion-Based Fuzz Testing for Deep Neural Networks via Coverage-Aware Manifold Guidance [2025-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584925001958)]
14. Markov Model Based Coverage Testing of Deep Learning Software Systems [2025-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584924002337)]
15. Lightweight Probabilistic Coverage Metrics for Efficient Testing of Deep Neural Networks [2025-INTERNETWARE] [[paper](https://dl.acm.org/doi/full/10.1145/3755881.3755915)]
16. Deep2Fuzz: Coverage-Guided Reinforcement Fuzzing towards Deep Neural Networks [2025-NaNA] [[paper](https://ieeexplore.ieee.org/abstract/document/11272548)]
17. CNF: An Automated Test Case Generation Method Based on Neuron Coverage Guidance in Key Network Layers[ 2025-IEEE Access] [[paper](https://ieeexplore.ieee.org/abstract/document/10982285)]
18. Targeted Deep Learning System Boundary Testing [2025-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3771557)]
19. A Diffusion-Based Neuron Coverage Feedback Fuzz Testing Method [2025-ICIC] [[paper](https://link.springer.com/chapter/10.1007/978-981-96-9911-7_24)]
20. TAEFuzz: Automatic Fuzzing for Image-Based Deep Learning Systems via Transferable Adversarial Examples [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3714463)]
21. Cluster-Based Multi-Objective Metamorphic Test Case Pair Selection for Deep Neural Networks [2025-INTERNETWARE] [[paper](https://dl.acm.org/doi/full/10.1145/3755881.3755885)]
22. White-Box Test Input Generation for Enhancing Deep Neural Network Models through Suspicious Neuron Awareness [2025-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3736305)]
23. DeFinder: Error-Sensitive Testing of Deep Neural Networks via Vulnerability Interpretation [2025-JNCA] [[paper](https://www.sciencedirect.com/science/article/pii/S1084804525001092)]
24. SETS: A Simple yet Effective DNN Test Selection Approach [2025-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3772084)]
25. Efficient Adaptive Test Case Selection for DNNs Robustness Enhancement [2025-JSS] [[paper](https://www.sciencedirect.com/science/article/pii/S0164121225001190)]
26. MetaDTS: Distribution Difference-Based Adaptive Test Input Selection for Deep Neural Networks [2025-JSA] [[paper](https://www.sciencedirect.com/science/article/pii/S1383762125003546)]
27. DANDI: Diffusion as Normative Distribution for Deep Neural Network Input [2025-DeepTest] [[paper](https://ieeexplore.ieee.org/abstract/document/11026894)]
28. MetaSel: A Test Selection Approach for Fine-tuned DNN Models [2025-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/11175088)]
29. Evaluating the Effectiveness of Neuron Coverage Metrics: A Metamorphic-testing Approach [2025-SQJ] [[paper](https://link.springer.com/article/10.1007/s11219-025-09716-5)]
30. Effective Search Space Pruning for Testing Deep Neural Networks [2025-APLAS] [[paper](https://link.springer.com/chapter/10.1007/978-981-97-8943-6_18)]
31. A Fine-grained Evaluation of Mutation Operators to Boost Mutation testing for Deep Learning Systems [2025-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-025-10613-5)]
32. ReEPM: A Reliability Estimation Framework for CNNs Based on Error Probability Matrix Modeling [2025-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584925003209)]
33. White-Box Test Input Generation for Enhancing Deaep Neural Network Models through Suspicious Neuron Awareness [2025-TSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3736305)]
34. PriCod: Prioritizing Test Inputs for Compressed Deep Neural Networks [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3730435)]
35. DeepVec: State-Vector Aware Test Case Selection for Enhancing Recurrent Neural Network [2025-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10979368)]
36. Generating Latent Space-Aware Test Cases for Neural Networks using Gradient-Based Search [2025-ICSTW] [[paper](https://ieeexplore.ieee.org/abstract/document/10962499/)]
37. Assessing the Robustness of Test Selection Methods for Deep Neural Networks [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3715693)]
38. Research on Deep Learning Network Sample Generation Method Based on Abnormal Examples [2025-CSECS] [[paper](https://ieeexplore.ieee.org/abstract/document/11010008)]
39. Adaptive Random Testing of Deep Learning Systems Using Image Hashing [2025-TR] [[paper](https://ieeexplore.ieee.org/abstract/document/11173952)]
40. BallPri: Test Cases Prioritization for Deep Neuron Networks via Tolerant Ball in Variable Space [2025-ASE] [[paper](https://link.springer.com/article/10.1007/s10515-025-00498-5)]
41. Py-holmes: Causal Testing for Deep Neural Networks in Python [2024-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3663529.3663807)]
42. DeepLogic: Priority Testing of Deep Learning Through Interpretable Logic Units [2024-CJE] [[paper](https://ieeexplore.ieee.org/abstract/document/10606210)]
43. EATS: Efficient Adaptive Test Case Selection for Deep Neural Networks [2024-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/10684627)]
44. DeepFinder: A New White-Box Testing Framework for Deep Neural Networks [2024-AINIT] [[paper](https://ieeexplore.ieee.org/abstract/document/10581637/)]
45. Enhancing Neuron Coverage of DNN Models for Adversarial Testing [2024-ISSRE Wksp] [[paper](https://ieeexplore.ieee.org/abstract/document/10771301)]
46. FATS: Feature Distribution Analysis-Based Test Selection for Deep Learning Enhancement [2024-TBD] [[paper](https://ieeexplore.ieee.org/abstract/document/10323141)]
47. TEASMA: A Practical Methodology for Test Adequacy Assessment of Deep Neural Networks [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10720834)]
48. DeepSI: A Sensitive-Driven Testing Samples Generation Method of WhiteBox CNN Model for Edge Computing [2024-TST] [[paper](https://ieeexplore.ieee.org/abstract/document/10339724)]
49. DeepDTS: Diverse Test Selection Method for Deep Neural Networks [2024-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/10726966)]
50. Generation of Black-Box Adversarial Attacks Using Many Independent Objective-Based Algorithm for Testing the Robustness of Deep Neural Networks [2024-ASC] [[paper](https://www.sciencedirect.com/science/article/pii/S1568494624007439)]
51. Generative Model-Based Test Case Generation and Operational Testing for Deep Learning [2024-ICBASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10762049)]
52. Deceiving Humans and Machines Alike: Search-Based Test Input Generation for DNNs Using Variational Autoencoders [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3635706)]
53. Metamorphic Testing of Image Processing Applications: A General Framework and Optimization Strategies [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3679006.3685070)]
54. GIST: Generated Inputs Sets Transferability in Deep Learning [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672457)]
55. Using Metamorphic Relations to Improve Accuracy and Robustness of Deep Neural Networks [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3679006.3685067)]
56. Neuron Semantic-Guided Test Generation for Deep Neural Networks Fuzzing [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3688835)]
57. CriticalFuzz: A Critical Neuron Coverage-guided Fuzz Testing Framework for Deep Neural Networks [2024-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584924000818)]
58. GGT: Graph-guided Testing for Adversarial Sample Detection of Deep Neural Network [2024-COMPUT SECUR] [[paper](https://www.sciencedirect.com/science/article/pii/S0167404824000117)]
59. Test Selection for Deep Neural Networks using Meta-Models with Uncertainty Metrics[2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680312)]
60. Neuron Sensitivity-Guided Test Case Selection [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672454)]
61. IATT: Interpretation Analysis Based Transferable Test Generation for Convolutional Neural Networks [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3705301)]
62. DeepSensitive: A Fuzzing Test for Deep Neural Networks with Sensitive Neurons [2024-ICAI] [[paper](https://link.springer.com/chapter/10.1007/978-981-97-0903-8_33)]
63. A DNN Fuzz Testing Method Based on Gradient-Weighted Class Activation Map [2024-APSEC] [[paper](https://ieeexplore.ieee.org/abstract/document/10967331)]
64. Context-Aware Fuzzing for Robustness Enhancement of Deep Learning Models [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3680464)]
65. Validity Matters: Uncertainty-Guided Testing of Deep Neural Networks [2024-SOFTW TEST VERIF REL] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/stvr.1894)]
66. DeepGD: A Multi-Objective Black-Box Test Selection Approach for Deep Neural Networks [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3644388)]
67. Improving Testing of Deep-Learning Systems [2024-CACM] [[paper](https://dl.acm.org/doi/abs/10.1145/3633311)]
68. Can Coverage Criteria Guide Failure Discovery for Image Classifiers? An Empirical Study [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672446)]
69. IATT: Interpretation Analysis-Based Transferable Test Generation for Convolutional Neural Networks [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3705301)]
70. Benchmarking Test-Time DNN Adaptation at Edge with Compute-In-Memory [2024-JATS] [[paper](https://dl.acm.org/doi/full/10.1145/3665898)]
71. Towards Stricter Black-Box Integrity Verification of Deep Neural Network Models [2024-MM] [[paper](https://dl.acm.org/doi/abs/10.1145/3664647.3681691)]
72.  See the Forest, not Trees: Unveiling and Escaping the Pitfalls of Error-Triggering Inputs in Neural Network Testing [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680385)]
73. DevMuT: Testing Deep Learning Framework via Developer Expertise-Based Mutation [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695523)]
74. Evaluating Deep Neural Networks in Deployment: A Comparative Study (Replicability Study) [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680401)]
75. Prioritizing Test Inputs for DNNs Using Training Dynamics [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695498)]
76. FAST: Boosting Uncertainty-Based Test Prioritization Methods for Neural Networks via Feature Selection [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695472)]
77. Distance-Aware Test Input Selection for Deep Neural Networks [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3652125)]
78. CertPri: Certifiable Prioritization for Deep Neural Networks via Movement Cost in Feature Space [2024-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298498)]
79. Keeper: Automated Testing and Fixing of Machine Learning Software [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672451)]
80. Spectral Analysis of the Relation between Deep Learning Faults and Neural Activation Values [2024-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10638589)]
81. Adaptive Key Neuron-Guided Fuzz Testing for Human Security in Deep Learning System [2024-iHumEnTech] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-97578-3_52)]
82. DeepSample: DNN Sampling-Based Testing for Operational Accuracy Assessment [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639584)]
83. Themis: Automatic and Efficient Deep Learning System Testing with Strong Fault Detection Capability [2024-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/10771474)]
84. Neuron Importance-Aware Coverage Analysis for Deep Neural Network Testing [2024-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-024-10524-x)]
85. CIT4DNN: Generating Diverse and Rare Inputs for Neural Networks Using Latent Space Combinatorial Testing [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639106)]
86. Enhancing Valid Test Input Generation with Distribution Awareness for Deep Neural Networks [2024-COMPSAC] [[paper](https://ieeexplore.ieee.org/abstract/document/10633581)]
87. Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10462634)]
88. Towards Exploring the Limitations of Test Selection Techniques on Graph Neural Networks: An Empirical Study [2024-ICTSS][[paper](https://link.springer.com/article/10.1007/s10664-024-10515-y)]
89. Deep Learning-Based Test Data Augmentation Technology [2023-CISP-BMEI] [[paper](https://ieeexplore.ieee.org/abstract/document/10373379)]
90. On the Importance of Severely Testing Deep Learning Models of Cognition [2023-CSR] [[paper](https://www.sciencedirect.com/science/article/pii/S138904172300092X)]
91. Evaluation of Deep Neural Network Quality by CleanAI Coverage Metrics Library [2023-INISTA] [[paper](https://ieeexplore.ieee.org/abstract/document/10310324)]
92. Test Data Selection Based on Applying Mutation Testing to Decision Tree Models [2023-SAST] [[paper](https://dl.acm.org/doi/abs/10.1145/3624032.3624038)]
93. BTM: Black-Box Testing for DNN Based on Meta-Learning [2023-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/10366660/)]
94. Efficient Generation of Valid Test Inputs for Deep Neural Networks via Gradient Search [2023-J SOFTW-EVOL PROC] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2550)]
95. DeepPerform: An Efficient Approach for Performance Testing of Resource-Constrained Neural Networks [2023-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3551349.3561158)]
96. Semantic Data Augmentation for Deep Learning Testing Using Generative AI [2023-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298450)]
97. GraphPrior: Mutation-Based Test Input Prioritization for Graph Neural Networks [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3607191)]
98. QuoTe: Quality-oriented Testing for Deep Learning Systems [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3582573)]
99. DeepIA: An Interpretability Analysis Based Test Data Generation Method for DNN [2023-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/10366669)]HashC: Making Deep Learning Coverage Testing Finer and Faster [2023-JSA] [[paper](https://www.sciencedirect.com/science/article/pii/S1383762123001789)]
100. Distribution Aware Testing Framework for Deep Neural Networks [2023-IEEE Access] [[paper](https://ieeexplore.ieee.org/abstract/document/10296901)]
101. A White-Box Testing for Deep Neural Networks Based on Neuron Coverage [2023-TNNLS] [[paper](https://ieeexplore.ieee.org/abstract/document/9737039/)]
102. Robust Test Selection for Deep Neural Networks [2023-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10319282/)]
103. Test Input Selection for Deep Neural Network Enhancement Based on Multiple-Objective Optimization [2023-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/10123539)]
104. DeepCatch: A New Testing Framework for Convolutional Neural Networks [2023-CEI] [[paper](https://ieeexplore.ieee.org/abstract/document/10527909)]
105. Multi-Objective White-Box Test Input Selection for Deep Neural Network Model Enhancement [2023-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/10301276/)]
106. Black-Box Testing of Deep Neural Networks through Test Case Diversity [2023-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10041782/)]
107. DVTest: Deep Neural Network Visualization Testing Framework [2023-DSA] [[paper](https://ieeexplore.ieee.org/abstract/document/10314261)]
108. Aries: Efficient Testing of Deep Neural Networks via Labeling-Free Accuracy Estimation [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172681)]
109. Improving Testing of Deep-learning Systems: A Combination of Differential and Mutation Testing Results in Netter Test Data [2023-QUEUE] [[paper](https://spawn-queue.acm.org/doi/full/10.1145/3631340)]
110. On the Cost-effectiveness of Composite Metamorphic Relations for Testing Deep Learning Systems [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3524846.3527335)]
111. A Probabilistic Framework for Mutation Testing in Deep Neural Networks [2023-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584922002385)]
112. Finding Deviated Behaviors of the Compressed DNN Models for Image Classifications [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3583564)]
113. Boosting the Revealing of Detected Violations in Deep Learning Testing: A Diversity-Guided Method [2023-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3551349.3556919)]
114. When and Why Test Generators for Deep Learning Produce Invalid Inputs: An Empirical Study [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172704)]
115. DistXplore: Distribution-Guided Testing for Evaluating and Enhancing Deep Learning Systems [2023-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3611643.3616266)]
116. DLRegion: Coverage-guided Fuzz Testing of Deep Neural Networks with Region-Based Neuron Selection Strategies [2023-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584923001209)]
117. Input Distribution Coverage: Measuring Feature Interaction Adequacy in Neural Network Testing [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3576040)]
118. Repairing Failure-inducing Inputs with Input Reflection [2023-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3551349.3556932)]
119. HeatC: A Variable-Grained Coverage Criterion for Deep Learning Systems [2023-SETTA] [[paper](https://link.springer.com/chapter/10.1007/978-981-99-8664-4_14)]
120. CC: Causality-Aware Coverage Criterion for Deep Neural Networks [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172609)]
121. An Overview of Structural Coverage Metrics for Testing Neural Networks [2023-STTT] [[paper](https://link.springer.com/article/10.1007/s10009-022-00683-x)]
122. Rule-Based Testing of Neural Networks [2023-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3617574.3622747)]
123. In Defense of Simple Techniques for Neural Network Test Case Selection [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598073)]
124. Hierarchical Distribution-Aware Testing of Deep Learning [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3625290)]
125. DeepRover: A Query-Efficient BlackBox Attack for Deep Neural Networks [2023-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3611643.3616370)]
126. A Geometrical Approach to Evaluate the Adversarial Robustness of Deep Neural Networks [2023-TOMM] [[paper](https://dl.acm.org/doi/full/10.1145/3587936)]
127. CoopHance: Cooperative Enhancement for Robustness of Deep Learning Systems [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598093)]
128. ActGraph: Prioritization of Test Cases Based on Deep Neural Network Activation Graph [2023-ASE] [[paper](https://link.springer.com/article/10.1007/s10515-023-00396-8)]
129. Sensitive Region-Based Metamorphic Testing Framework using Explainable AI [2023-MET] [[paper](https://ieeexplore.ieee.org/abstract/document/10190404)]
130. PatchCensor: Patch Robustness Certification for Transformers via Exhaustive Testing [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3591870)]
131. DeepTD: Diversity-Guided Deep Neural Network Test Generation [2023-SETTA] [[paper](https://link.springer.com/chapter/10.1007/978-981-99-8664-4_24)]
132. Seed Selection for Testing Deep Neural Networks [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3607190)]
133. Practical Accuracy Evaluation for Deep Learning Systems via Latent Representation Discrepancy [2023-INTERNETWARE] [[paper](https://dl.acm.org/doi/abs/10.1145/3609437.3609457)]
134. Automatic Test Pattern Generation and Compaction for Deep Neural Networks [2023-SPDAC] [[paper](https://dl.acm.org/doi/abs/10.1145/3566097.3567912)]
135. DeepAbstraction++: Enhancing Test Prioritization Performance via Combined Parameterized Boxes [2023-AISoLA] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-46002-9_5)]
136. DFuzzer: Diversity-Driven Seed Queue Construction of Fuzzing for Deep Learning Models [2023-TR] [[paper](https://ieeexplore.ieee.org/abstract/document/10288417)]
137. ATOM: Automated Black-Box Testing of Multi-Label Image Classification Systems [2023-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298557)]
138. A Fine-Grained Evaluation of Mutation Operators for Deep Learning Systems: A Selective Mutation Approach [2023-INTERNETWARE] [[paper](https://dl.acm.org/doi/abs/10.1145/3609437.3609453)]
139. Revisiting Neuron Coverage for DNN Testing: A Layer-Wise and Distribution-Aware Criterion [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172683)]
140. DeepAtash: Focused Test Generation for Deep Learning Systems [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598109)]
141. LaF: Labeling-free Model Selection for Automated Deep Neural Network Reusing [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3611666)]
142. DeepCrime: From Real Faults to Mutation Testing Tool for Deep Learning [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172493)]
143. Requirements-Driven Logic Testing for Deep Neural Networks [2023-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/10429957)]
144. Efficient and Effective Feature Space Exploration for Testing Deep Learning Systems [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3544792)]
145. Evaluating Surprise Adequacy for Deep Learning System Testing [2023-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3546947)]
146. Revisiting Deep Neural Network Test Coverage From the Test Effectiveness Perspective [2023-J SOFTW-EVOL PROC] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2561)]
147. HashC: Making Deep Learning Coverage Testing Finer and Faster [2023-JSA] [[paper](https://www.sciencedirect.com/science/article/pii/S1383762123001789)]
148. Test Suite Generation Based on Context-Adapted Structural Coverage for Testing DNN [2023-APNOMS] [[paper](https://ieeexplore.ieee.org/abstract/document/10258238)]
149. TSDTest: A Efficient Coverage Guided Two-Stage Testing for Deep Learning Systems [2022-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/10077070)]
150. How Higher Order Mutant Testing Performs for Deep Learning Models: a Fine-Grained Evaluation of Test Effectiveness and Efficiency Improved From Second-Order Mutant-Classification Tuples [2022-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584922000994)]
151. Test-Time Detection of Backdoor Triggers for Poisoned Deep Neural Networks [2022-ICASSP] [[paper](https://ieeexplore.ieee.org/abstract/document/9746573/)]
152. Unsupervised Test-Time Adaptation of Deep Neural Networks at the Edge: A Case Study [2022-DATE] [[paper](https://ieeexplore.ieee.org/abstract/document/9774580)]
153. FuzzGAN: A Generation-Based Fuzzing Framework for Testing Deep Neural Networks [2022-HPCC] [[paper](https://ieeexplore.ieee.org/abstract/document/10074689)]
154. DANCe: Dynamic Adaptive Neuron Coverage for Fuzzing Deep Neural Networks [2022-IJCNN] [[paper](https://ieeexplore.ieee.org/abstract/document/9892349/)]
155. Mutation Testing Based Safety Testing and Improving on DNNs [2022-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/10062379)]
156. DeepBoundary: A Coverage Testing Method of Deep Learning Software Based on Decision Boundary Representation [2022-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/10076975)]
157. Comparing Input Prioritization Techniques for Testing Deep Learning Algorithms [2022-SEAA] [[paper](https://ieeexplore.ieee.org/abstract/document/10011200)]
158. DeepAbstraction: 2-Level Prioritization for Unlabeled Test Inputs in Deep Neural Networks [2022-AITest] [[paper](https://ieeexplore.ieee.org/abstract/document/9898118)]
159. EREBA: Black-Box Energy Testing of Adaptive Neural Networks [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510088)]
160. A Method and Experiment to Evaluate Deep Neural Networks as Test Oracles for Scientific Software [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3524481.3527232)]
161. Adaptive Test Selection for Deep Neural Networks[ 2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510232)]
162. Multi-objective Metamorphic Follow-up Test Case Selection for Deep Learning Systems [2022-GECCO] [[paper](https://dl.acm.org/doi/abs/10.1145/3512290.3528697)]
163. One Step Further: Evaluating Interpreters Using Metamorphic Testing [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534225)]
164. CAGFuzz: Coverage-Guided Adversarial Generative Fuzzing Testing for Image-Based Deep Learning Systems [2022-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9599374)]
165. DeepMC: DNN Test Sample Optimization Method Jointly Guided by Misclassification and Coverage [2022-APIN] [[paper](https://link.springer.com/article/10.1007/s10489-022-04323-4)]
166. Revisiting Neuron Coverage Metrics and Quality of Deep Neural Networks [2022-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/9825775)]
167. NPC: Neuron Path Coverage via Characterizing Decision Logic of Deep Neural Networks [2022-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3490489)]
168. 𝜀-weakened Robustness of Deep Neural Networks [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534373)]
169. RGChaser: A RL-guided Fuzz and Mutation Testing Framework for Deep Learning Systems [2022-DSA] [[paper](https://ieeexplore.ieee.org/abstract/document/9914422)]
170. BET: Black-Box Efficient Testing for Convolutional Neural Networks [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534386)]
171. Towards Practical Robustness Analysis for DNNs Based on PAC-model Learning [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510143)]
172. An Empirical Study on Data Distribution-Aware Test Selection for Deep Learning Enhancement [2022-TOMSE] [[paper](https://dl.acm.org/doi/full/10.1145/3511598)]
173. Simple techniques work surprisingly well for Neural network test Prioritization and Active learning (replicability study) [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534375)]
174. DeepState: Selecting Test Suites to Enhance the Robustness of Recurrent Neural Networks [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510231)]
175. Can Test Input Selection Methods for Deep neural Network Guarantee Test Diversity? A large-scale Empirical Study [2022-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584922001185)]
176. DeepSuite: A Test Suite Optimizer for Autonomous Vehicles [2022-T-ITS] [[paper](https://ieeexplore.ieee.org/abstract/document/9646479)]
177. TPFL: Test Input Prioritization for Deep Neural Networks Based on Fault Localization [2022-ADMA] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-22064-7_27)]
178. What Are We Really Testing in Mutation Testing for Machine Learning? A Critical Reflection [2021-ICSE-NIER] [[paper](https://ieeexplore.ieee.org/abstract/document/9402251)]
179. DeepCon: Contribution Coverage Testing for Deep Learning Systems [2021-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/9425998)]
180. Evaluation of the Benchmark Datasets for Testing the Efficacy of Deep Convolutional Neural Networks [2021-VI] [[paper](https://www.sciencedirect.com/science/article/pii/S2468502X21000371)]
181. Exposing Numerical Bugs in Deep Learning via Gradient Back-propagation [2021-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3468264.3468612)]
182. Boundary Sampling to Boost Mutation Testing for Deep Learning Models [2021-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584920301737)]
183. DeepBackground: Metamorphic Testing for Deep-Learning-driven Image Recognition Systems Accompanied by Background-Relevance [2021-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584921001555)]
184. Follow-up Test Cases are Better Than Source Test Cases in Metamorphic Testing: A Preliminary Study [2021-MET] [[paper](https://ieeexplore.ieee.org/abstract/document/9477655)]
185. A Review and Refinement of Surprise Adequacy [2021-DeepTest] [[paper](https://ieeexplore.ieee.org/abstract/document/9476898)]
186. An Empirical Study on Test Case Prioritization Metrics for Deep Neural Networks [2021-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/9724736)]
187. RobOT: Robustness-Oriented Testing for Deep Learning Systems [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402039)]
188. Black-Box Testing of Deep Neural Networks [2021-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/9700360)]
189. Safety Testing of Neural Network for Image Classification [2021-AEMCSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9512978)]
190. Cats are not Fish: Deep Learning Testing Calls for Out-of-distribution Awareness [2021-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3324884.3416609)]
191. Exposing Previously Undetectable Faults in Deep Neural Networks [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464801)]
192. Distribution-Aware Testing of Neural Networks Using Generative Models [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402100)]
193. Test Selection for Deep Learning Systems [2021-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3417330)]
194. Orchid: Building Dynamic Test Oracles with Training Bias for Improving Deep Neural Network Models [2021-DSA] [[paper](https://ieeexplore.ieee.org/abstract/document/9623032)]
195. Scalable Quantitative Verification For Deep Neural Networks [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402111)]
196. Measuring Discrimination to Boost Comparative Testing for Multiple Deep Learning Models [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402140)]
197. Operation is the Hardest Teacher: Estimating DNN Accuracy Looking for Mispredictions [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402144)]
198. Audee: Automated Testing for Deep Learning Frameworks [2021-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3324884.3416571)]
199. Towards Exploring the Limitations of Active Learning: An Empirical Study [2021-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/9678672)]
200. DeepHyperion: Exploring the Feature Space of Deep Learning-Based Systems through Illumination Search [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464811)]
201. DeepCrime: Mutation Testing of Deep Learning Systems Based on Real Faults [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464825)]
202. Prioritizing Test Inputs for Deep Neural Networks via Mutation Analysis [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402064)]
203. Neuron Activation Frequency Based Test Case Prioritization [2020-TASE] [[paper](https://ieeexplore.ieee.org/abstract/document/9405318)]
204. An Efficient Metamorphic Testing Leveraging Disentangled Transformation and Decision Oracle [2020-PRAI] [[paper](https://ieeexplore.ieee.org/abstract/document/10332066)]
205. An Empirical Study on Correlation between Coverage and Robustness for Deep Neural Networks [2020-ICECCS] [[paper](https://ieeexplore.ieee.org/abstract/document/9376208)]
206. Correlations Between Deep Neural Network Model Coverage Criteria and Model Quality [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409671)]
207. Effective White-Box Testing of Deep Neural Networks with Adaptive Neuron-selection Strategy [2020-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3395363.3397346)]
208. DeepGini: Prioritizing Massive Tests to Enhance the Robustness of Deep Neural Networks [2020-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3395363.3397357)]
209. Testing DNN Umage Classifiers for Confusion & Bias Errors [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380400)]
210. Cost-effective Testing of A Deep Learning model Through Input Reduction [2020-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/9251075)]
211. Is Neuron Coverage A Meaningful Measure for Testing Deep Neural Networks [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409754)]
212. Multiple-Boundary Clustering and Prioritization to Promote Neural Network Retraining [2020-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3324884.3416621)]
213. Fuzz Testing Based Data Augmentation to Improve Robustness of Deep Neural Networks [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380415)]
214. Computing the Testing Error Without a Testing Set [2020-CVPR] [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Corneanu_Computing_the_Testing_Error_Without_a_Testing_Set_CVPR_2020_paper.html)]
215. ARTDL: Adaptive Random Testing for Deep Learning Systems [2020-IEEE Access] [[paper](https://ieeexplore.ieee.org/abstract/document/8944083)]
216. Model-Based Exploration of the Frontier of Behaviours for Deep learning System Testing [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409730)]
217. Is Neuron Coverage a Meaningful Measure for Testing Deep Neural Networks? [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409754)]
218. DeepBillboard: Systematic Physical-world Testing of Autonomous Driving Systems [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380422)]
219. Importance-Driven Deep Learning System Testing [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380391)]
220. An Empirical Evaluation of Mutation Operators for Deep Learning Systems [2020-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/9159089)]
221. Practical Accuracy Estimation for Efficient Deep Neural Network Testing [2020-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3394112)]
222. On the Investigation of Essential Diversities for Deep Learning Testing Criteria [2019-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/8854700)]
223. A Reliability Analysis of a Deep Neural Network [2019-LATW] [[paper](https://ieeexplore.ieee.org/abstract/document/8704548)]
224. DeepCT: Tomographic Combinatorial Testing for Deep Learning Systems [2019-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/8668044)]
225. DeepHunter: A Coverage-guided Fuzz Testing Framework for Deep Neural Networks [2019-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3293882.3330579)]
226. Adversarial Sample Detection for Deep Neural Network Through model Mutation Testing [2019-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/8812047)]
227. Structural Test Coverage Criteria for Deep Neural Networks [2019-TECS] [[paper](https://dl.acm.org/doi/abs/10.1145/3358233)]
228. Input Prioritization for Testing Neural Networks [2019-AITest] [[paper](https://ieeexplore.ieee.org/abstract/document/8718224)]
229. DeepEvolution: A Search-Based Testing Approach for Deep Neural Networks [2019-ICSM] [[paper](https://ieeexplore.ieee.org/abstract/document/8919189)]
230. Deepstellar: Model-Based Quantitative Analysis of stateful Deep Learning Systems [2019-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3338906.3338954)]
231. Test4Deep: an Effective White-Box Testing for Deep Neural Networks [2019-CSE] [[paper](https://ieeexplore.ieee.org/abstract/document/8919545)]
232. Guiding Deep Learning System Testing Using Surprise Adequacy [2019-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/8812069)]
233. Boosting Operational DNN Testing Efficiency Through Conditioning [2019-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3338906.3338930)]
234. Anomaly Detection of attacks (ADA) on DNN Classifiers at Test Time [2018-MLSP] [[paper](https://ieeexplore.ieee.org/abstract/document/8517069)]
235. DeepMutation: Mutation Testing of Deep Learning Systems [2018-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/8539073)]
236. DLFuzz: Differential Fuzzing Eesting of Deep Learning Systems [2018-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3236024.3264835)]
237. DeepGauge: Multi-Granularity Testing Criteria For Deep Learning Systems [2018-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3238147.3238202)]
238. Concolic Testing for Deep Neural Networks [2018-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3238147.3238172)]
239. Validating a Deep Learning Framework by Metamorphic Testing [2017-MET] [[paper](https://ieeexplore.ieee.org/abstract/document/7961649)]
240. DeepXplore: Automated WhiteBox Testing of Deep Learning Systems [2017-SOSP] [[paper](https://dl.acm.org/doi/abs/10.1145/3132747.3132785)]


### Autonomous Driving System Testing
1. Generating Latent Space-Aware Test Cases for Neural Networks using Gradient-Based Search [2025-ICSTW] [[paper](https://ieeexplore.ieee.org/abstract/document/10962499/)]
2. Assessing the Robustness of Test Selection Methods for Deep Neural Networks [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3715693)]
3. Research on Deep Learning Network Sample Generation Method Based on Abnormal Examples [2025-CSECS] [[paper](https://ieeexplore.ieee.org/abstract/document/11010008)]
4. Adaptive Random Testing of Deep Learning Systems Using Image Hashing [2025-IET] [[paper](https://ieeexplore.ieee.org/abstract/document/11173952)]
5. Efficient Domain Augmentation for Autonomous Driving Testing Using Diffusion Models [2025-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/11029946)]
6. Decictor: Towards Evaluating the Robustness of Decision-Making in Autonomous Driving Systems [2025-ICSE] [[paper](https://arxiv.org/abs/2402.18393)]
7. OpenCat: Improving Interoperability of ADS Testing [2025-DeepTest] [[paper](https://ieeexplore.ieee.org/abstract/document/11026887)]
8. Benchmarking Image Perturbations for Testing Automated Driving Assistance Systems [2025-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10988980)]
9. Bias Behind the Wheel: Fairness Testing of Autonomous Driving Systems [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3702989)]
10. Metamorphic Testing of Deep Neural Network-Based Autonomous Driving Systems Using Behavioural Domain Adequacy [2025-NCA] [[paper](https://link.springer.com/article/10.1007/s00521-024-10794-y)]
11. BallPri: Test Cases Prioritization for Deep Neuron Networks via Tolerant Ball in Variable Space [2025-ASE] [[paper](https://link.springer.com/article/10.1007/s10515-025-00498-5)]
12. ObjTest: Object-Level Mutation for Testing Object Detection Systems [2024-INTERNETWARE] [[paper](https://dl.acm.org/doi/abs/10.1145/3671016.3671400)]
13. Seeing the Invisible: Test Prioritization for Object Detection System [2024-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-024-10539-4)]
14. Spectral Analysis of the Relation between Deep Learning Faults and Neural Activation Values [2024-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10638589)]
15. Adaptive Key Neuron-Guided Fuzz Testing for Human Security in Deep Learning System [2024-iHumEnTech] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-97578-3_52)]
16. DeepSample: DNN Sampling-Based Testing for Operational Accuracy Assessment [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639584)]
17. Themis: Automatic and Efficient Deep Learning System Testing with Strong Fault Detection Capability [2024-ISSRE] [[paper](https://ieeexplore.ieee.org/abstract/document/10771474)]
18. Neuron importance-Aware Coverage Analysis for Deep Neural Network Testing [2024-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-024-10524-x)]
19. CIT4DNN: Generating Diverse and Rare Inputs for Neural Networks Using Latent Space Combinatorial Testing [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639106)]
20. Enhancing Valid Test Input Generation with Distribution Awareness for Deep Neural Networks [2024-COMPSAC] [[paper](https://ieeexplore.ieee.org/abstract/document/10633581)]
21. Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10462634)]
22. Mutation-Based White Box Testing of Deep Neural Networks [2024-IEEE Access] [[paper](https://ieeexplore.ieee.org/abstract/document/10720015)]
23. Bridging the Gap between Real-world and Synthetic Images for Testing Autonomous Driving Systems [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695067)]
24. Predicting Safety Misbehaviours in Autonomous Driving Systems Using Uncertainty Quantification [2024-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10638606)]
25. Empirical Test of Visual Recognition System of Autonomous Vehicle Based On Deep Learning [2024-ICSECE] [[paper](https://ieeexplore.ieee.org/abstract/document/10729404)]
26. Causality-driven Testing of Autonomous Driving Systems [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3635709)]
27. Towards Reliable AI: Adequacy Metrics for Ensuring the Quality of System-level Testing of Autonomous Vehicles [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3623314)]
28. Federated Repair of Deep Neural Networks [2024-DeepTest] [[paper](https://dl.acm.org/doi/pdf/10.1145/3643786#page=24)]
29. Test Input Prioritization for 3D Point Clouds [2024-DeepTest] [[paper](https://dl.acm.org/doi/full/10.1145/3643676)]
30. Curiosity-Driven Testing for Sequential Decision-Making Process [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639149)]
31. Datactive: Data Fault Localization for Object Detection Systems [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680329)]
32. ISTA+: Test Case Generation and Optimization for Intelligent systems Based on coverage analysis [2024-SCP] [[paper](https://www.sciencedirect.com/science/article/pii/S0167642324000017)]
33. An Empirical Study of Testing Machine Learning in the Wild [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3680463)]
34. Generative Model-Based Testing on Decision-Making Policies [2023-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298522)]
35. DeepCrime: From Real Faults to Mutation Testing Tool for Deep Learning [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172493)]
36. Requirements-Driven Logic Testing for Deep Neural Networks [2023-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/10429957)]
37. Efficient and Effective Feature Space Exploration for Testing Deep Learning Systems [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3544792)]
38. Evaluating Surprise Adequacy for Deep Learning System Testing [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3546947)]
39. Revisiting Deep Neural Network Test Coverage from the Test Effectiveness Perspective [2023-J SOFTW-EVOL PROC] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2561)]
40. How Do Deep Learning Faults Affect AI-Enabled Cyber-Physical Systems in Operation? A Preliminary Study Based on DeepCrime Mutation Operators [2023-ESEM] [[paper](https://ieeexplore.ieee.org/abstract/document/10304794)]
41. A Scenario-Based Functional Testing Approach to Improving DNN Performance [2023-SOSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10254777)]
42. DeepManeuver: Adversarial Test Generation for Trajectory Manipulation of Autonomous Vehicles [2023-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10213222/)]
43. BehAVExplor: Behavior Diversity Guided Testing for Autonomous Driving Systems [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598072)]
44. Research on an Acceleration Test Method of Automatic Driving Based on Deep Neural Network [2023-ICCCBDA] [[paper](https://ieeexplore.ieee.org/abstract/document/10154870)]
45. Many-Objective Reinforcement Learning for Online Testing of DNN-Enabled Systems [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172658)]
46. Parameter Coverage for Testing of Autonomous Driving Systems under Uncertainty [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3550270)]
47. ISTA: Automatic Test Case Generation and Optimization for Intelligent Systems Based on Coverage Analysis [2023-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/10123517)]
48. TPFL: Test Input Prioritization for Deep Neural Networks Based on Fault Localization [2022-ADMA] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-22064-7_27)]
49. DeepSuite: A Test Suite Optimizer for Autonomous Vehicles [2022-T-ITS] [[paper](https://ieeexplore.ieee.org/abstract/document/9646479)]
50. LiRTest: Augmenting LiDAR Point Clouds for Automated Testing of Autonomous Driving Systems [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534397)]
51. Efficient Online testing for DNN-enabled Systems Using Surrogate-assisted and Many-objective Optimization [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510188)]
52. MDPFuzz: Testing Models Solving Markov Decision Processes [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534388)]
53. DeepHyperion: Exploring the Feature Space of Deep Learning-Based Systems Through Illumination Search [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464811)]
54. Prioritizing Test Inputs for Deep Neural Networks via Mutation Analysis [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402064)]
55. DeepCrime: Mutation Testing of Deep Learning Systems Based on Real Faults [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464825)]
56. Can Offline Testing of Deep Neural Networks Replace Their Online Testing? [2021-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-021-09982-4)]
57. A Combinatorial Approach to Testing Deep Neural Network-Based Autonomous Driving Systems [2021-ICSTW] [[paper](https://ieeexplore.ieee.org/abstract/document/9440193)]
58. ARTDL: Adaptive Random Testing for Deep Learning Systems [2020-IEEE Access] [[paper](https://ieeexplore.ieee.org/abstract/document/8944083)]
59. Model-Based Exploration of the Frontier of Behaviours for Deep Learning System Testing [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409730)]
60. Is Neuron Coverage A Meaningful Measure for Testing Deep Neural Networks? [2020-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409754)]
61. DeepBillboard: Systematic Physical-world Testing of Autonomous Driving systems [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380422)]
62. Importance-Driven Deep Learning System Testing [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380391)]
63. An Empirical Evaluation of Mutation Operators for Deep Learning Systems [2020-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/9159089)]
64. Practical Accuracy Estimation for Efficient Deep Neural Network Testing [2020-TOMSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3394112)]
65. Testing DNN-Based Path Planning Algorithms by Metamorphic Testing [2020-DSA] [[paper](https://ieeexplore.ieee.org/abstract/document/9331244)]
66. Misbehaviour Prediction for Autonomous Driving Systems [2020-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3377811.3380353)]
67. A Deep Convolutional Neural Network Based Small Scale Test-bed for Autonomous Car [2020-ICCA] [[paper](https://dl.acm.org/doi/abs/10.1145/3377049.3377076)]
68. Comparing Offline and Online Testing of Deep Neural Networks: An Autonomous Car Case Study [2020-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/9159088)]
69. Test4Deep: an Effective White-Box Testing for Deep Neural Networks [2019-CSE] [[paper](https://ieeexplore.ieee.org/abstract/document/8919545)]
70. Guiding Deep Learning System Testing Using Surprise Adequacy [2019-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/8812069)]
71. Boosting Operational DNN Testing Efficiency Through Conditioning [2019-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3338906.3338930)]
72. DeepRoad: GAN-Based Metamorphic Testing and Input Validation Framework for Autonomous Driving Systems [2018-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3238147.3238187)]
73. DeepTest: Automated Testing of Deep-neural-network-driven Autonomous Cars [2018-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3180155.3180220)]
74. DeepXplore: Automated WhiteBox Testing of Deep Learning Systems [2017-SOSP] [[paper](https://dl.acm.org/doi/abs/10.1145/3132747.3132785)]


### Large Language Model Testing
1. VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation [2025-PACMSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3729343)]
2. Unlocking Language Barriers: Assessing Pre-trained Large Language Models Scross Multilingual Tasks and Unveiling the Black Box With Explainable Artificial Intelligence [2025-EAAI] [[paper](https://www.sciencedirect.com/science/article/pii/S0952197625001368)]
3. AcTracer: Active Testing of Large Language Model via Multi-Stage Sampling [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3744340)]
4. CityBench: Evaluating the Capabilities of Large Language Models for Urban Tasks [2025-KDD] [[paper](https://dl.acm.org/doi/abs/10.1145/3711896.3737375)]
5. TELEIA: A Spanish Language Dataset for Evaluating Artificial Intelligence Models [2025-DATA BRIEF] [[paper](https://www.sciencedirect.com/science/article/pii/S2352340925001696)]
6. Understanding the Effectiveness of Coverage Criteria for Large Language Models: A Special Angle from Jailbreak Attacks [2025-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/11029795)]
7. Evaluating Large Language Model Robustness using Combinatorial Testing [2025-ICSTW] [[paper](https://ieeexplore.ieee.org/abstract/document/10962520)]
8. Evaluating Large Language Models for Software Testing [2025-CSI] [[paper](https://www.sciencedirect.com/science/article/pii/S0920548924001119)]
9. Risk Assessment Framework for Code Llms Via Leveraging Internal States [2025-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3696630.3728566)]
10. Robustness Evaluation of Code Generation Systems Via Concretizing Instructions [2025-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584924002507)]
11. HiBenchLLM: Historical Inquiry Benchmarking for Large Language Models [2025-DKE] [[paper](https://www.sciencedirect.com/science/article/pii/S0169023X24001071)]
12. Evaluation and Improvement of Test Selection for Large Language Models [2025-J SOFTW-EVOL PROC] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.70057)]
13. An Ensemble-Based Transfer Testing Method for Large Language Models [2025-EAAI] [[paper](https://www.sciencedirect.com/science/article/pii/S0952197625019086)]
14. Evaluating Large Language Model Performance to Support the Diagnosis and Management of Patients with Primary Immune Disorders [2025-JACI] [[paper](https://www.sciencedirect.com/science/article/pii/S0091674925001666)]
15. Challenging the Validity of Personality Tests for Large Language Models [2025-EAAMO] [[paper](https://dl.acm.org/doi/full/10.1145/3757887.3763016)]
16. ASTRAL: A Tool for the Automated Safety Testing of Large Language Models [2025-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3713081.3731733)]
17. LeCov: Multi-level Testing Criteria for Large Language Models [2025-JSS] [[paper](https://www.sciencedirect.com/science/article/pii/S0164121225004327)]
18. Online Safety Analysis for LLMs: a Benchmark, an Assessment, and a Path Forward [2025-TAI] [[paper](https://ieeexplore.ieee.org/abstract/document/11145129)]
19. Benchmarking Vision Capabilities of Large Language Models in Surgical Examination Questions [2025-JSE] [[paper](https://www.sciencedirect.com/science/article/pii/S1931720425000236)]
20. Evaluation of Chat Generative Pre-trained Transformer and Microsoft Copilot Performance on the American Society of Surgery of the Hand Self-Assessment Examinations [2025-JHS GO] [[paper](https://www.sciencedirect.com/science/article/pii/S2589514124001907)]
21. Adaptive Testing for LLM-Based Applications: A Diversity-Based Approach [2025-ICSTW] [[paper](https://ieeexplore.ieee.org/abstract/document/10962467)]
22. LangBiTe: An Open-source Platform to Automate Bias Testing of Large Language Models [2025-SOFTWAREX] [[paper](https://www.sciencedirect.com/science/article/pii/S2352711025002158)]
23. ASTRAL: Automated Safety Testing of Large Language Models [2025-AST] [[paper](https://ieeexplore.ieee.org/abstract/document/11081717)]
24. Mutation-Based Consistency Testing for Evaluating the Code Understanding Capability of LLMs [2024-CAIN] [[paper](https://dl.acm.org/doi/abs/10.1145/3644815.3644946)]
25. Drowzee: Metamorphic Testing for Fact-Conflicting Hallucination Detection in Large Language Models [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3689776)]
26. MedExpQA: Multilingual benchmarking of Large Language Models for Medical Question Answering [2024-AIM] [[paper](https://www.sciencedirect.com/science/article/pii/S0933365724001805)]


### Text Classification System Testing
1. DT4LM: Differential Testing for Reliable Language Model Updates in Classification Tasks [2025-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/11205851)]
2. Effective Black Box Testing of Sentiment Analysis Classification Networks [2025-SWQD] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-89277-6_3)]
3. White-Box Test Input Generation for Enhancing Deaep Neural Network Models through Suspicious Neuron Awareness [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3736305)]
4. PriCod: Prioritizing Test Inputs for Compressed Deep Neural Networks [2025-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3730435)]
5. DeepVec: State-Vector Aware Test Case Selection for Enhancing Recurrent Neural Network [2025-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10979368)]
6. Automated Testing Linguistic Capabilities of NLP Models [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672455)]
7. ISTA+: Test Case Generation and Optimization for Intelligent Systems Based on Coverage Analysis [2024-SCP] [[paper](https://www.sciencedirect.com/science/article/pii/S0167642324000017)]
8. DevMuT: Testing Deep Learning Framework via Developer Expertise-Based Mutation [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695523)]
9. Prioritizing Test Inputs for DNNs Using Training Dynamics [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695498)]
10. FAST: Boosting Uncertainty-Based Test Prioritization Methods for Neural Networks via Feature Selection [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695472)]
11. Distance-Aware Test Input Selection for Deep Neural Networks [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3652125)]
12. CertPri: Certifiable Prioritization for Deep Neural Networks via Movement Cost in Feature Space [2024-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298498)]
13. Keeper: Automated Testing and Fixing of Machine Learning Software [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672451)]
14. LEAP: Efficient and Automated Test Method for NLP Software [2023-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298415/)]
15. Dynamic Data Fault Localization for Deep Neural Networks [2023-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3611643.3616345)]
16. Revisiting Neuron Coverage for DNN Testing: A Layer-Wise and Distribution-Aware Criterion [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172683)]
17. DeepAtash: Focused Test Generation for Deep Learning Systems [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172683)]
18. LaF: Labeling-free Model Selection for Automated Deep Neural Network Reusing [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3611666)]
19. Revisiting Deep Neural Network Test Coverage from the Test Effectiveness Perspective [2023-J SOFTW-EVOL PROC] [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2561)]
20. Simple Techniques Work Aurprisingly Well for Neural Network Test Prioritization and Active Learning (replicability study) [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534375)]
21. DeepState: Selecting Test Suites to Enhance the Robustness of Recurrent Neural Networks [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510231)]
22. A Distance-Based Dynamic Random Testing Strategy for Natural Language Processing DNN Models [2022-QRS] [[paper](https://ieeexplore.ieee.org/abstract/document/10062454)]
23. Audee: Automated Testing for Deep Learning Frameworks [2021-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3324884.3416571)]
23. Towards Exploring the Limitations of Active Learning: An Empirical Study [2021-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/9678672)]
24. Prioritizing Test Inputs for Deep Neural Networks via Mutation Analysis [2021-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9402064)]


### Recommendation System Testing
1. Causally Perturbed Fairness Testing [2025-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3773088)]
2. MAFT: Efficient Model-Agnostic Fairness Testing for Deep Neural Networks via Zero-Order Gradient Search [2024-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639181)]
3. An Empirical Study on Correlations Between Deep Neural Network Fairness and Neuron Coverage Criteria [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10384481)]
4. FIPSER: Improving Fairness Testing of DNN by Seed Prioritization [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695486)]
5. Contexts Matter: An Empirical Study on Contextual Influence in Fairness Testing for Deep Learning Systems [2024-ESEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3674805.3686673)]
6. CertPri: Certifiable Prioritization for Deep Neural Networks via Movement Cost in Feature Space [2024-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298498)]
7. Evaluating Deep Neural Networks in Deployment: A Comparative Study (Replicability Study) [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680401)]
8. An Empirical Study of Testing Machine Learning in the Wild [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3680463)]
9. Information-Theoretic Testing and Debugging of Fairness Defects in Deep Neural Networks [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172902)]
10. Latent Imitator: Generating Natural Individual Discriminatory Instances for Black-Box Fairness Testing [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598099)]
11. FairRec: Fairness Testing for Deep Recommender Systems [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598058)]
12. ISTA: Automatic Test Case Generation and Optimization for Intelligent Systems Based on Coverage Analysis [2023-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/10123517)]
13. DeepCrime: From Real Faults to Mutation Testing Tool for Deep Learning [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172493)]
14. NeuronFair: Interpretable White-Box Fairness Testing Through Biased Neuron Identification [2022-ICSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510123)]
15. An Empirical Study on Data Distribution-Aware Test Selection for Deep Learning Enhancement [2022-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3511598)]
16. Efficient White-Box Fairness Testing Through Gradient Search [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464820)]
17. DeepCrime: Mutation Testing of Deep Learning Systems Based on Real Faults [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464825)]


### Object Detection System Tesing
1. Search-Based DNN Testing and Retraining With GAN-Enhanced Simulations [2025-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10880098)]
2. In-Simulation Testing of Deep Learning Vision Models in Autonomous Robotic Manipulators [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695281)]
3. A Testing and Evaluation Framework for the Quality of DNN Models [2024-ISSSR] [[paper](https://ieeexplore.ieee.org/abstract/document/10562092)]
4. Prioritizing Testing Instances to Enhance the Robustness of Object Detection Systems [2024-INTERNETWARE] [[paper](https://dl.acm.org/doi/abs/10.1145/3609437.3609446)]
5. See the Forest, not Trees: Unveiling and Escaping the Pitfalls of Error-Triggering Inputs in Neural Network Testing [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680385)]
6. Automatic Test Suite Generation for Key-points Detection DNNs Using many-objective Search (experience paper) [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464802)]
7. DevMuT: Testing Deep Learning Framework via Developer Expertise-Based Mutation [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695523)]
8. Adaptive Test Case Selection for DNN-Based Perception Functions [2021-ISSE] [[paper](https://ieeexplore.ieee.org/abstract/document/9582499)]
9. Combinational Metamorphic Testing for Deep Learning Based Target Detection CPS Systems [2021-QRS-C] [[paper](https://ieeexplore.ieee.org/abstract/document/9742146)]
10. A Multimodality Fusion Deep Neural Network and Safety Test Strategy for Intelligent Vehicles [2021-TOSEM] [[paper](https://ieeexplore.ieee.org/abstract/document/9207961)]
11. Metamorphic Object Insertion for Testing Object Detection Systems [2021-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3324884.3416584)]
12. ObjTest: Object-Level Mutation for Testing Object Detection Systems [2021-INTERNETWARE] [[paper](https://dl.acm.org/doi/abs/10.1145/3671016.3671400)]
13. Seeing the Invisible: Test Prioritization For Object Detection System [2021-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-024-10539-4)]
14. Computing the Testing Error Without a Testing Set [2020-CVPR] [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Corneanu_Computing_the_Testing_Error_Without_a_Testing_Set_CVPR_2020_paper.html)]

### Speech Recognition System Testing
1. AudioTest: Prioritizing Audio Test Cases [2025-PACMSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3728907)]
2. BallPri: Test Cases Prioritization for Deep Neuron Networks via Tolerant Ball in Variable Space [2025-ASE] [[paper](https://link.springer.com/article/10.1007/s10515-025-00498-5)]
3. An Empirical Study of Testing Machine Learning in the Wild [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3680463)]
4. Keeper: Automated Testing and Fixing of Machine Learning Software [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3672451)]
5. Spectral Analysis of the Relation Between Deep Learning Faults and Neural Activation Values [2024-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10638589)]
6. Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10462634)]
7. Synthesizing Speech Test Cases with Text-to-Speech? An Empirical Study on the False Alarms in Automated Speech Recognition Testing [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3597926.3598126)]
8. DeepCrime: From Real Faults to Mutation Testing Tool for Deep Learning [2023-ICSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10172493)]
9. ASRTest: Automated Testing for Deep-neural-network-driven Speech Recognition Systems [2022-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534391)]
10. Can Test Input Selection Methods for Deep Neural Network Guarantee Test Diversity? A Large-scale Empirical Study [2022-IST] [[paper](https://www.sciencedirect.com/science/article/pii/S0950584922001185)]
11. Deep Neural Network Based Noised Asian Speech Enhancement and Its Implementation on a Hearing Aid App [2021-TALLIP] [[paper](https://dl.acm.org/doi/abs/10.1145/3439797)]
12. DeepCrime: Mutation Testing of Deep Learning Systems Based on Real Faults [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464825)]
13. Practical Accuracy Estimation for Efficient Deep Neural Network Testing [2020-TOSEM] [[paper](https://dl.acm.org/doi/abs/10.1145/3394112)]
14. Deepstellar: Model-Based Quantitative Analysis of Stateful Deep Learning Systems [2019-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3338906.3338954)]


### Code Detection System Testing
1. LaF: Labeling-free Model Selection for Automated Deep Neural Network Reusing [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695523)]
2. KAPE: kNN-Based Performance Testing for Deep Code Search [2023-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3624735)]
3. CoCoFuzzing: Testing Neural Code Models With Coverage-Guided Fuzzing [2023-TR] [[paper](https://ieeexplore.ieee.org/abstract/document/9916170)]
4. A Search-Based Testing Framework for Deep Neural Networks of Source Code Embedding [2021-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/9438605)]


### Machine Translation System Testing
1. Machine Translation Testing via Syntactic Tree Pruning [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3640329)]
2. Word Closure-Based Metamorphic Testing for Machine Translation [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3675396)]
3. Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing [2024-TSE] [[paper](https://ieeexplore.ieee.org/abstract/document/10462634)]
4. Mutation Testing of Deep Reinforcement Learning Based on Real Faults [2023-ICST] [[paper](https://ieeexplore.ieee.org/abstract/document/10132198)]


### Dialogue System Testing
1. Applying Pairwise Combinatorial Testing to Large Language Model Testing[2023-ICTSS] [[paper](https://link.springer.com/chapter/10.1007/978-3-031-43240-8_16)]
2. DialTest: Automated Testing for Recurrent-neural-network-driven Dialogue Systems [2021-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3460319.3464829)]


### Airborne Collision Avoidance System Testing
1. Synthesizing Boxes Preconditions for Deep Neural Networks [2024-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650212.3680393)]
2. Generative Model-Based Testing on Decision-Making Policies [2023-ASE] [[paper](https://ieeexplore.ieee.org/abstract/document/10298522)]


### Semantic Segmentation System Testing
1. DevMuT: Testing Deep Learning Framework via Developer Expertise-Based Mutation [2024-ASE] [[paper](https://dl.acm.org/doi/abs/10.1145/3691620.3695523)]
2. Computing the Testing Error Without a Testing Set [2020-CVPR] [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Corneanu_Computing_the_Testing_Error_Without_a_Testing_Set_CVPR_2020_paper.html)]


### Video Classification System Testing
1. Prioritizing Test Cases for Deep Learning-Based Video Classifiers [2024-ESE] [[paper](https://link.springer.com/article/10.1007/s10664-024-10520-1)]


### Video Detection System Testing
1. FairnessEvaluation in Deepfake Detection Models Using Metamorphic Testing [2023-ISSTA] [[paper](https://dl.acm.org/doi/abs/10.1145/3524846.3527337)]


### Malware Detection System Testing
1. Test Suite Generation Based on Context-Adapted Structural Coverage for Testing DNN [2023-APNOMS] [[paper](https://ieeexplore.ieee.org/abstract/document/10258238)]


### Smart Home System Testing
1. Environment-Aware Testing for DNN-Based Smart-home WiFi Sensing Systems [2023-SANER] [[paper](https://ieeexplore.ieee.org/abstract/document/10123673)]




## 🔗 Related DNN Testing Surveys

1. Coverage-Guided Testing for Deep Learning Models: a Comprehensive Survey [2025-arXiv] [[paper](https://arxiv.org/abs/2507.00496)]

2. Test Optimization in DNN Testing: a Survey [2024-TOSEM] [[paper](https://dl.acm.org/doi/full/10.1145/3643678)]

3. Testing Deep Learning-Based Visual Perception for Automated Driving [2024-TCPS] [[paper](https://dl.acm.org/doi/abs/10.1145/3450356)]

4. A survey of uncertainty in deep neural networks [2023-AIR] [[paper](https://link.springer.com/article/10.1007/s10462-023-10562-9)]

5. Research on Deep Neural Network Testing Techniques [2023-ICMLCA] [[paper](https://dl.acm.org/doi/abs/10.1145/3650215.3650237)]

6. Testing of Autonomous Driving Systems: Where are We and Where Whould We Go? [2022-FSE] [[paper](https://dl.acm.org/doi/abs/10.1145/3540250.3549111)]

7. Testing Deep Learning Models: a First Comparative Study of Multiple Testing Techniques [2022-arXiv] [[paper](https://arxiv.org/abs/2202.12139)]

8. Adversarial Robustness of Deep Neural Networks: a Survey From a Formal Verification Perspective [2022-TDSC] [[paper](https://ieeexplore.ieee.org/document/9785704)]

9. Survey on Testing of Deep Neural Networks [2020-JSW] [[paper](https://jos.org.cn/jos/article/abstract/5951)]

10. A Survey of Safety and Trustworthiness of Deep Neural Networks: Verification, Testing, Adversarial Attack and Defence, and Interpretability [2020-COMPUT SCI REV] [[paper](https://www.sciencedirect.com/science/article/pii/S1574013719302527)]

[//]: # (## 📌 Available Tools)
[//]: # (1. [**DeepAtash**]&#40;https://github.com/testingautomated-usi/deepatash&#41;: Focused test generation tool for DL systems.)
[//]: # (2. [**DeepHyperion**]&#40;https://github.com/testingautomated-usi/DeepHyperion&#41;: Search Based DL system testing tools.)
