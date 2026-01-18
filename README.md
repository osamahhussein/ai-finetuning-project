# Parameter-Efficient Fine-Tuning of TinyLlama Using LoRA


This repository contains my final project for the **Generative Artificial Intelligence** course.  
The project focuses on fine-tuning the **TinyLlama** language model using a small custom question–answer dataset.

---

## Project Objective

The main objective of this project is to understand how large language models (LLMs) can be adapted to specific tasks using parameter-efficient fine-tuning techniques, especially **LoRA (Low-Rank Adaptation)**.  
Through this project, I explored the full pipeline of dataset preparation, model fine-tuning, and inference.

---

## Dataset

A small custom dataset was created in **instruction–response format**.

Each example follows this structure:
- **Instruction:** A question related to generative AI  
- **Response:** A short and clear answer  

The dataset covers topics such as:
- What is generative AI  
- Differences between generative and discriminative models  
- Applications of generative AI  
- Overfitting and generalization  
- Language models  

---

## Model and Tools

- **Base model:** TinyLlama (1.1B Chat)
- **Fine-tuning method:** LoRA (using PEFT)
- **Environment:** Google Colab (GPU: T4)
- **Libraries used:**
  - PyTorch  
  - Transformers (Hugging Face)  
  - PEFT  
  - Datasets  

---

Open directly in Colab:
https://colab.research.google.com/github/osamahussein/llm-finetuning-project/blob/main/llm_finetuning_project.ipynb


## Notebook

All implementation steps are available in the notebook:

## How to Run the Project

1. Open the notebook using the Colab link above.  
2. Make sure the runtime is set to GPU.  
3. Run all cells from top to bottom.  
4. The final cells demonstrate inference using the fine-tuned model.


## Example Output

**Input:** What is the difference between generative and discriminative models?  
**Model Output:** Generative models learn the joint distribution of data, while discriminative models focus on separating decision boundaries between classes.

