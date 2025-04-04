# AI Research Summaries  

This repository contains a collection of AI research papers, with links to the original sources and concise summaries of their main topics and key takeaways. I will be updating this page regularly as I review more papers.  
Feel free to explore, contribute, or suggest papers for review!

## Research Papers  

| Title | Source | Summary | Key Takeaways |
|-------|--------|---------|--------------|
| Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | https://arxiv.org/abs/2005.11401 | Introduces **RAG**, a model that combines parametric (LLM-stored) and non-parametric (retrieved) knowledge to improve factual accuracy and dynamic updating in language generation. It compares two retrieval approaches: **RAG-Sequence** (fixed document for response) and **RAG-Token** (different documents per token). The study demonstrates improved QA and text generation performance over traditional seq2seq models. | <ul><li>**Hybrid Memory System**: Enhances LLMs with real-time document retrieval.</li><li>**Better QA & Generation**: Produces more factual and diverse responses.</li><li>**Retrieval Mechanism**: Uses a **dense vector index** for improved accuracy.</li><li>**Non-Parametric Memory**: Allows easy knowledge updates without retraining.</li><li>**Document Splitting**: Uses 100-word chunks for optimal retrieval.</li> |
