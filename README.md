## Hi 👋

I am Ankit, a Machine Learning and Deep Learning Enthusiast. Currently, I am working as an AI Engineer at Indiana University.

- [Work Experience](#work-experience)
- [Other Works](#other-works)
- [Profile](#profile)
- [Contact](#contact)

### Work Experience

##### AI Engineer - Indiana University Indianapolis
> Aug 2025 - Present

- Implemented a weak supervision pipeline to expand a 270 example seed set [IU Press Release](https://github.com/anchauha/asset-deficit-miner/blob/main/process_with_llm/data/output/results_gemini-2.5-Instruct_semantic_extraction_prompt3_d689d527.json) into a 1350 example corpus of asset vs deficit language. Fine-tuned a [BERT uncased model](https://github.com/anchauha/asset-deficit-miner/blob/main/bert_finetuning/models/bert-v1/best_model/experiment_results.json) and conducted human-in-the-loop validation to ensure data quality.
- The fine-tuned BERT classifier reached a macro F1 score of 0.68 on span-level classification, establishing the first reliable and automated method for tracking asset-deficit based language in documents.
- Containerized and deployed the prototype web application using Flask. Achieved a p95 latency of 3.4 seconds on a V100 GPU under a load of 50 concurrent requests.

##### Research Assistant (AI) - Indiana University Indianapolis
> Aug 2023 - May 2025
- Led research and development of a culturally responsive GenAI system [CATpc (First Prototype)](https://github.com/anchauha/CATpc) for an [NSF funded research grant](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2334631) under the esteemed guidance of [Prof. Sunandan Chakraborty](https://luddy.indianapolis.iu.edu/contact/directory/sunandan-chakraborty.html) & [Dr. Jeremy Price](https://education.indianapolis.iu.edu/faculty-research/faculty-directory/price-jeremy.html). The final system demonstrated 14% higher pedagogical alignment scores, 8% reduced hallucinations, and 27% increased teacher satisfaction compared to GPT-3.5 baseline.
- Generated a large scale dataset for lung cancer coreference resolution using a multistage process, which included fine-tuning a BERT model on 1000 expert annotations to generate predictions for 7500 PubMed abstracts. Fine-tuned  6 LLMs on this dataset using PEFT with COT+FICL prompting, achieving 99% accuracy with Mixtral 8x7B.

##### Teaching Assistant - Indiana University Indianapolis
> Aug 2024 - Dec 2024 
- Supported over 30 students in the Fall 2024 H518 Deep Learning course through tutorials, labs, office hours, and lesson planning on topics: GANS, CNNS, LSTMs, Transformers, and Reinforcement Learning.

##### Cloud Consultant (Data & Machine Learning Platforms) - Capgemini
> Apr 2020 - Sep 2022

- Engineered a data ingestion pipeline using PySpark to load data into 100+ Hive tables, reducing data processing time by 40%.
- Built an XGBoost based predictive forecasting model that optimizes SKU selection for enterprise licensing needs. This benefited in 18% annual cost savings on underutilized license spend for 43,000+ users.
- Developed Cloud Functions to process and load over 10 GB of daily raw JSON data from GCS bucket into BigQuery and Cloud SQL.
- Led migration for legacy applications to Azure cloud environment during an enterprise split ensuring service continuity for over 23,000 users.

##### Cloud Consultant (Cloud Infrastructure & DevOps) - Wipro
> Jul 2018 - Mar 2020
- Developed federated workflows for Azure infrastructure provisioning, managing 250+ virtual machines with 99.9% uptime.
- Designed and maintained Azure DevOps pipelines for deployments to Azure App Services for 20+ business and operations applications, cutting deployment time by ~30%.
- Authored 20 knowledge base documents on routine administration tasks and contributed to regular knowledge sharing sessions on topics such as storage lifecycle, retention, and Azure CLI across EMEA, APAC, and NA teams.

### Other Works

##### Cultural Eval: Quantifying Cultural Bias in LLMs - Independent Study
> 2024
- Developed a quantitative framework to benchmark cultural bias in LLMs by applying PCA to extract 5 latent cultural dimensions from 97,000 records across 96 variables of [WVS Dataset](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp)
- Compared responses from Llama-2 13B, Gemma 3 12B, and Phi 4 across 5 extracted latent cultural dimensions using Tucker's Congruence Coefficient and Cohen's d, revealing consistent underestimation of Religious-Traditional values for non-Western demographic profiles (Cohen's d: -0.89 to -1.17) [Visualization](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/regional_bias_heatmap_all_models.png)
- Created Western Bias Index and Overall Cultural Bias Index metrics, finding Llama-2 demonstrated the strongest [Western bias (WBI = 1.34)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/western_bias_index.png) and Phi 4 the highest overall [cultural bias (OCBI = 0.78)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/overall_cultural_bias_index.png).

#### Mod-Guide: An LLM-based Content Moderation Feedback System
> 2024
- Prototyped a multimodal NLP workflow processing 200 community collected text, image and audio documents of hate speech against minority voices in Bangladesh. Augmented the data with custom chain-of-thought reasoning, grounded in external knowledge sources, to generate [contextual metadata](https://github.com/anchauha/BanglaRAG/blob/main/data/Structured_RAG.pdf)
- The final model's performance was evaluated on a 50 example held out set where our GPT-4 + RAG system achieved an F1 score of 87% at detecting culturally nuanced hate speech compared to an F1 score of 64% from the zero-shot GPT-4 baseline.

### Profile
* [LinkedIn](https://www.linkedin.com/in/chauhan-aankit/)

### Contact

* +1 317-491-7832 :phone:
* [Gmail](mailto:ankichau.1718@gmail.com)
