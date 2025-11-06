# Project:  RAGSmith: A Framework for Finding the Optimal Composition of Retrieval-Augmented Generation Methods Across Datasets

* Student: Aniket Anil Naik (SJSU ID: 019107114)
* Class: CMPE-255: Data Mining (Fall 2025)
* Instructor: Professor Vijay Eranti

## 🚀 Project Links:

* View Presentation Slides
* Read Medium Post
* Project Objective

## Project Objective
This project translates the core technical concepts from the RAGSmith research paper into a short story. The story personifies the paper's central problem (brittle, isolated RAG components) and its solution (an end-to-end genetic search framework) to make the findings more intuitive and memorable.

## 🧭 The Paper at a Glance
* Title: RAGSmith: A Framework for Finding the Optimal Composition of Retrieval-Augmented Generation Methods Across Datasets
* Authors: Muhammed Yusuf Kartal, Suha Kagan Kose, Korhan Sevinç, and Burak Aktas
* Key Takeaway: RAGSmith is a framework that uses a genetic search to automatically find the best combination of RAG components (retrieval, ranking, etc.) for a specific dataset, resulting in a much better "end-to-end" system than manually tuning parts in isolation.

## 🛠️ Core Findings & Insights
The paper's investigation led to several key conclusions:
*** The "Brittle" Problem:** Optimizing RAG modules one by one doesn't work well because the parts interact in complex ways. A good retriever might give data the generator can't use.
* **A "Genetic Search" Solution:** The RAGSmith framework tests and "breeds" RAG pipelines from 46,080 possible configurations, evolving the best-performing combination.
* **A "Scalar Objective" is Key:** The system judges success not just on retrieval (finding good documents) but also on generation (writing a good answer), forcing a balanced result.
* **It Works:** The final "evolved" RAGSmith models beat the standard "naive" RAG setup by an average of +3.8% across six different and complex domains.

## Real-World Impact
This research matters because it offers a way to automate the incredibly complex, expensive, and time-consuming process of building a high-quality RAG system. Instead of engineers manually guessing the right components, they can use RAGSmith to discover the optimal, custom-built pipeline for their specific data (e.g., a financial RAG, a medical RAG). It shifts the work from "tuning" to "architecture search."

## Boundaries & Future Work
The study's conclusions are based on data from six domains, but all were derived from Wikipedia. Performance on completely different data (like private company docs) might vary. The search is also limited to the 46,080 configurations defined by the authors; it doesn't invent brand-new techniques. Finally, the genetic search is a "one-time" but computationally heavy cost.

## Full Citation
#### Kartal, M. Y., Kose, S. K., Sevinç, K., and Aktas, B., 2025, RAGSmith: A Framework for Finding the Optimal Composition of Retrieval-Augmented Generation Methods Across Datasets, arXiv:2511.01386v1 [cs.CL].
---
