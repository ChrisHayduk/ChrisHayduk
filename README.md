# Hi there, I'm Chris 👋

I'm currently the Lead ML Engineer for Drug Discovery at Deloitte, where I work to develop, orchestrate, and deploy deep learning models to accelerate pharmaceutical research and development.

In my free time, I build large language model (LLM) powered tools, develop open source LLM models and datasets, and contribute to LLM research projects.

## 💻 Github Projects 

I've worked on several drug discovery & LLM-focused projects featured on GitHub:

- [Optimized AlphaFold Multimer Vertex AI Pipeline](https://github.com/ChrisHayduk/Optimized-AlphaFold-Multimer-Vertex-AI-Pipeline) - Improved the open source Vertex AI AlphaFold pipeline for multimer input. Improvements include:
  1. Separating MSA and predict steps into different components
  2. Parallelizing MSAs, offering a >50% speedup
  3. Allowing for caching of MSAs (both at the individual chain and full protein level)
  4. Allowing using MSAs for some chains will skipping the MSA step for others (very useful for peptide optimization)
- [JANUS Peptide](https://github.com/ChrisHayduk/JANUS-Peptide) - Updates the JANUS molecular optimization approach to generate peptide binders using AlphaFold. Leverages a genetic algorithm running on top of AlphaFold to produce the optimized binders.
- [QLoRA for Masked Language Modeling](https://github.com/ChrisHayduk/QLoRA-for-MLM) - Updated QLoRA for use with the masked language modeling objective, enabling efficient finetuning of BERT-family models
- [Multi-GPU QLoRA](https://github.com/ChrisHayduk/qlora-multi-gpu) - Updated QLoRA to allow for distributed data parallel finetuning, significantly accelerating finetuning workloads

## 🤗 HuggingFace Projects 

I have also open sourced some of my LLM models and data on HuggingFace: 

### 📈 Datasets

- [ChrisHayduk/Llama-2-SQL-and-Code-Dataset](https://huggingface.co/datasets/ChrisHayduk/Llama-2-SQL-and-Code-Dataset) - Curated a SQL-focused code instruction set for LLaMA 2. The eval set includes dummy tables so that the trained model can be evaluated for SQL execution accuracy rather than token prediction accuracy. The dataset was processed in a number of ways, including introducing curriculum learning, fixing table inputs, and instruction filtering.

### 🚀 Models

- [ChrisHayduk/OpenGuanaco-13B](https://huggingface.co/ChrisHayduk/OpenGuanaco-13B) - Created an open source recreation of Guanaco using OpenLLaMA.

## 📫 How to Reach Me

* Twitter: https://twitter.com/chris_hayduk1
* LinkedIn: https://www.linkedin.com/in/chrishayduk/
* Substack: https://www.chrishayduk.com/

<!--
**ChrisHayduk/ChrisHayduk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
