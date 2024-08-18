Geo-FuB: A Method for Constructing an Operator-Function Knowledge Base for Geospatial Code Generation Tasks Using Large Language Models

Overview
Welcome to the Geo-FuB repository! This project introduces Geo-FuB, a comprehensive framework designed to build an operator-function knowledge base to enhance geospatial code generation using Large Language Models (LLMs). The goal of Geo-FuB is to tackle the challenge of coding hallucinations in LLMs when applied to geospatial tasks by leveraging a domain-specific knowledge base.

Core Components
Geo-FuB consists of three key components, each contributing to the construction of the operator-function knowledge base:

Function Semantic Framework Construction (Geo-FuSE):

Utilizes techniques like Chain-of-Thought (CoT), TF-IDF, t-SNE, and Gaussian Mixture Model.
Discovers and organizes semantic features from geospatial scripts.
Frequent Operator Combination Statistics (Geo-FuST):

Employs Abstract Syntax Trees (ASTs) and the APRIORI algorithm.
Identifies and analyzes frequent operator combinations in code structures.
Combination and Semantic Framework Mapping (Geo-FuM):

Combines LLMs with fuzzy matching algorithms.
Aligns operator combinations with the function semantic framework to construct the Geo-FuB knowledge base.

Repository Contents
This repository includes the following components of the Geo-FuB framework:

Geo-FuSE: Function Semantic Framework Construction
Geo-FuST: Frequent Operator Combination Statistics
Geo-FuM: Combination and Semantic Framework Mapping
Each directory contains code, documentation, and examples relevant to the respective component.

Dataset
The Geo-FuB knowledge base has been constructed using 154,075 Google Earth Engine scripts, which provide a rich source of geospatial functions and operator relationships. The dataset is available within this repository for further experimentation and development.

Evaluation
The Geo-FuB framework has undergone rigorous evaluation to ensure both structural integrity and semantic accuracy:

Overall Accuracy: 88.89%
Structural Accuracy: 92.03%
Semantic Accuracy: 86.79%
These metrics underscore the robustness and reliability of Geo-FuB in improving geospatial code generation tasks.

Applications
Geo-FuB is particularly useful for:

Enhancing geospatial code generation with LLMs, particularly in avoiding coding hallucinations.
Optimizing research workflows by providing an empirical resource for further fine-tuning and applying the Retrieval-Augmented Generation (RAG) paradigm.

How to Use
Clone the repository:
git clone https://github.com/whuhsy/Geo-FuB.git


Use the provided scripts and datasets to build and test your own operator-function knowledge base.

Citation
If you use Geo-FuB in your research, please cite our paper:
@article{your_paper,
  title={Geo-FuB: A Method for Constructing an Operator-Function Knowledge Base for Geospatial Code Generation Tasks Using Large Language Models},
  author={Shuyang Hou, Anqi Zhao, Jianyuan Liang, Zhangxiao Shen, Huayi Wu},
  journal={Your Journal Name},
  year={2024},
  volume={},
  pages={}
}

Contact
For questions or collaborations, please contact the corresponding author:

Huayi Wu
Email: wuhuayi@whu.edu.cn
