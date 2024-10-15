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

Academic service
======
Reviewers of IEEE Transactions on Neural Networks and Learning Systems(TNNLS)

Selected Awards
======
National Scholarship (Twice)

<!-- Education/advised/hobby/dataset -->
