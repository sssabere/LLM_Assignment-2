## Trustworthiness Evaluation of Qwen/Qwen1.5-0.5B-Chat

This repository contains the code and analysis for evaluating the trustworthiness of the large language model **Qwen/Qwen1.5-0.5B-Chat** using the **DecodingTrust** benchmark.  
The study focuses on three trust dimensions: **Machine Ethics**, **Toxicity**, and **Stereotype Bias**.

---

### Main Notebooks

#### 1. `Assignment2_Preparation.ipynb`

This notebook includes:
- Loading and exploring subsets of the **DecodingTrust** dataset.  
- Feeding selected prompts (toxicity, machine ethics, and stereotype bias) to the **Qwen/Qwen1.5-0.5B-Chat** model.  
- Collecting and saving the model responses for later evaluation.  

#### 2. `Interpretation_Dataframes.ipynb`

This notebook includes:
- Evaluating model outputs using quantitative metrics such as **toxicity score**, **semantic similarity**, and **correlation**.  
- Generating visualizations (e.g., scatter plots of prompt vs. response toxicity).  
- Interpreting model behavior across the three trust dimensions.  
