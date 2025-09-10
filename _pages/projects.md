---
layout: archive
title: Data Science Projects
permalink: /projects/
author_profile: true
---

Below are selected projects designed to demonstrate my technical skills and applied experience in data science, natural language processing, and statistical modeling. Each project highlights a specific set of tools and methods, and links to a live demo or interactive report where available.

---

## Building on Cresta's FECT paper: A QUD-based approach to factuality evaluation with conversational transcripts

I extended the 3D paradigm proposed in [Cresta's KDD paper](https://kdd-eval-workshop.github.io/genai-evaluation-kdd2025/assets/papers/Submission%2022.pdf) by Hagyeong Shin and her colleagues. Instead of the compositional semantics approach that drives the 3D paradigm, I direct the LLM to parse the conversational transcript through the lens of the Question Under Discussion framework. Initial results suggest that the challenge of evaluating the factuality of analytical claims about conversational data does benefit from a QUD-based transformation of the transcript, with performance roughly matching that from the 3D paradigm proposed in the original paper.

**Key highlights:**
- Use of OpenAI API in LLM-as-judge framework
- Application of linguistic theory to LLM prompt optimization
- POC reporting

📄 [View the live project website](https://tpoppels.github.io/cresta-fect-qud){:target="_blank"}

📂 [GitHub repository](https://github.com/tpoppels/cresta-fect-qud){:target="_blank"}

🛠 **Tools:** Python, OpenAI API, ipynb reports, matplotlib/seaborn, LLM prompt engineering

---

## Gender Bias in Language Prediction: Humans vs. Large Language Models

This multi-part portfolio project investigates how humans and large language models (LLMs) respond to gendered pronouns in political contexts, particularly when interpreting role nouns like *"the next president... she."*

The project extends a large-scale psycholinguistic experiment I conducted during my PhD, comparing human response patterns to model behavior and exploring whether predictive biases can be modified through targeted fine-tuning.

**Key highlights:**
- Statistical modeling using `brms` and reaction time data from 2,000+ human participants
- LLM surprisal analysis using HuggingFace models in Python
- Interactive dashboards built with Shiny (R) and Streamlit (Python)
- Strong focus on reproducibility, transparency, and structured reasoning

📄 [View the live project website](https://tpoppels.github.io/gender-bias-humans-vs-llms){:target="_blank"}

📂 [GitHub repository](https://github.com/tpoppels/gender-bias-humans-vs-llms){:target="_blank"}

🛠 **Tools:** R, brms, ggplot2, tidyverse, Python, HuggingFace, Streamlit, Shiny, Quarto, GitHub Pages

---


