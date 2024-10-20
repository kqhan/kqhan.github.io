---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a first-year Ph.D. student at UCLA advised by Prof. Yizhou Sun. My research interests include LLM, AI for Science, and Graph.

I received my CS bachelor degree at Zhejiang University, advised by Prof. Yang Yang at AINet Lab. Fortunately, I also receive guidance from Prof. Carl Yang at Emory Graph Mining Lab.

I am excited to discuss and collaborate with individuals from diverse backgrounds. Please feel free to email me at: kqhan@cs.ucla.edu 

Recent Research
======

LLM reasoning
=======
The goal is to improve the reasoning ability of LLMs in multiple domains. 
Reasoning is the key foundation for ensuring the efficacy and reliability of language models.
While Large Language Models (LLMs) have demonstrated remarkable proficiency in certain reasoning tasks.
LLMs often experience hallucinations and unreliable reasoning, especially when they lack external knowledge.
I am working on evaluating and improving LLM reasoning by tackling challenges in robustness, structure, and efficiency.

To evaluate the robustness reasoning ability of LLMs, we propose the Concept-Reversed Winograd Schema Challenge Dataset (CR-WSC). 
In addition to avoiding simple semantic associations of words, it is  an adversarial dataset tailored specifically for LLMs, which is \textit{non-LLM-proof}: challenging to solve with LLMs. 
In CR-WSC, I expose vulnerabilities in LLMs' reasoning through adversarial evaluation, showing how subtle concept changes can lead to errors.
We propose a robust prompting method, called Abstraction-of-Thought (AoT), to first abstract the adversarial question to a normalized reasoning question, thus facilitating robust reasoning. 
Recognizing the gap in LLMs' ability to handle graph reasoning tasks, we developed GraphLLM, an approach that integrates graph learning models with LLMs to better interpret and reason on graph data.
We also tackled the efficiency challenges posed by large-scale LLMs in the context of TAGs. GraphAdapter, employs a graph neural network (GNN) as a lightweight, efficient adapter for LLMs, reducing computational costs and improving accuracy in various TAG-related tasks.

AI for science
========
I am also exploring how AI could be applied in science. AI can analyze vast amounts of data quickly, identify patterns, and automate complex processes, which accelerates discoveries and enhances precision in research.

We developed BrainODE to address data challenges in brain analysis derived from fMRI. This approach leverages Neural ODEs to enable continuous modeling of dynamic brain signals. It addresses three critical challenges associated with a unified framework, thereby significantly improving downstream brain network analysis.

Graph
========
Graph data is essential for modeling complex relationships among entities in various domains, such as social networks, transportation, and biology. It enables enhanced data analysis, allowing organizations to uncover patterns and insights. I have worked on developing how to utilize graph data efficiently and how to apply graph data in diverse domains.

To provide a fresh understanding of graph self-supervised learning based on task correlations, we propose GraphTCM to illustrate the task correlations and utilize it to enhance graph self-supervised training. In BrainODE, we utilize spatial graph and temporal graph to improve the performance of Neuarl ODEs. 


Publications
=======
Please refer to my Google Scholar profile for the latest publications and preprints.
\begin{enumerate}
    \item \textbf{Concept-Reversed Winograd Schema Challenge: Evaluating and Improving Robust Reasoning in Large Language Models via Abstraction} \\
    \textit{\textbf{Kaiqiao Han*}, Tianqing Fang*, Zhaowei Wang, Yangqiu Song, Mark Steedman} \\

    \item \textbf{Can GNN be Good Adapter for LLMs? } (WWW 24)\\
    \textit{Xuanwen Huang, \textbf{Kaiqiao Han}, Yang Yang, Dezheng Bao, Quanjin Tao, Ziwei Chai, Qi Zhu} \\

    \item \textbf{GraphLLM: Boosting Graph Reasoning Ability of Large Language Model} \\
    \textit{Ziwei Chai, Tianjie Zhang, Liang Wu, \textbf{Kaiqiao Han}, Xiaohai Hu, Xuanwen Huang, Yang Yang} \\

    \item \textbf{BrainODE: Dynamic Brain Network Analysis via Graph-Aided Neural Ordinary Differential Equations} (BHI 24)\\
    \textit{\textbf{Kaiqiao Han}, Yi Yang, Zijie Huang, Xuan Kan, Yang Yang, Ying Guo, Lifang He, Liang Zhan, Yizhou Sun, Wei Wang, Carl Yang} \\

    \item \textbf{Prompt-based node feature extractor for few-shot learning on text-attributed graphs} \\
    \textit{Xuanwen Huang, \textbf{Kaiqiao Han}, Dezheng Bao, Quanjin Tao, Zhisheng Zhang, Yang Yang, Qi Zhu} \\

    \item \textbf{Exploring Correlations of Self-supervised Tasks for Graphs} (ICML 24)\\
    \textit{Taoran Fang, Wei Zhou, Yifei Sun, \textbf{Kaiqiao Han}, Lvbin Ma, Yang Yang} \\

    \item \textbf{\textbf{A Neural Dynamics Driven Diffusion Method for
Learning Representations of Brain Signals}} \\
    \textit{Fanze Fu, Yang Yang, Junru Chen, \textbf{Kaiqiao Han}, Carl Yang} \\
    
    % \item \textbf{Title of the paper} \\
    % \textit{Author(s)} \\
\end{enumerate}
Other Projects
======
\textbf{Behavior Modeling and Recommender System in Influencer Economy}

We study the system for recommending proper influencers to businesses by modeling the influencers and network.


\textbf{AI Model Security Assessment and Hardening Platform}

National Innovation and Entrepreneurship Program for College Students, leader, advised by \href{https://nesa.zju.edu.cn/webpage/crew/jsl.html}{{Shouling Ji}}

Academic Service
======
Reviewers of IEEE Transactions on Neural Networks and Learning Systems(TNNLS)

Selected Awards
======
National Scholarship (Twice, Top 1\%) 

Outstanding Graduates of Zhejiang University

First-prize of Zhejiang Provincial Mathematics Competition

<!-- Education/advised/hobby/dataset -->
