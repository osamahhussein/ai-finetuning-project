# Parameter-Efficient Fine-Tuning of TinyLlama Using LoRA

This repository presents the final project for the **Generative Artificial Intelligence** course.  
The project explores the use of **parameter-efficient fine-tuning techniques (LoRA)** to adapt a pre-trained large language model (**TinyLlama 1.1B Chat**) to a custom question–answer dataset.

The goal is to demonstrate the complete workflow of:
- Dataset preparation  
- Model fine-tuning  
- Evaluation  
- Inference using the fine-tuned model  

---

## Project Objective

The primary objective of this project is to understand how large language models (LLMs) can be adapted to specific tasks using efficient fine-tuning approaches.  
Instead of fully retraining the model, the project applies **LoRA (Low-Rank Adaptation)** to reduce computational cost while maintaining performance.

Through this project, the following skills were practiced:
- Working with pre-trained transformer models  
- Preparing custom datasets  
- Applying LoRA using the PEFT library  
- Running experiments on GPU using Google Colab  
- Evaluating model behavior through inference examples  

---

## Model and Tools

- **Base Model:** TinyLlama (1.1B Chat)
- **Fine-Tuning Method:** LoRA (using PEFT)
- **Environment:** Google Colab (GPU: T4)
- **Libraries Used:**
  - PyTorch  
  - Transformers (Hugging Face)  
  - PEFT  
  - Datasets  

---

## Dataset

A small custom dataset was created in **instruction–response format**.  
Each sample follows a structured prompt style to simulate real instruction-following behavior.

The dataset focuses on conceptual topics related to:
- Generative AI  
- Machine learning fundamentals  
- Language models  
- Overfitting and generalization  

---

## Notebook

All implementation steps (installation, data processing, training, and inference) are fully documented in the notebook.

👉 Open directly in Google Colab:  
https://colab.research.google.com/github/osamahussein/ai-finetuning-project/blob/main/llm_finetuning_project.ipynb

---

## How to Run the Project

1. Open the notebook using the Colab link above.  
2. Make sure the runtime is set to **GPU** (Runtime → Change runtime type → GPU).  
3. Run all cells from top to bottom.  
4. The final cells demonstrate inference using the fine-tuned model.  

---

## Example Output

**Input:**  
What is the difference between generative and discriminative models?

**Model Output:**  
Generative models learn the joint distribution of data, while discriminative models focus on separating decision boundaries between classes.

---

## Results

The fine-tuned model demonstrates improved alignment with the custom dataset compared to the base model.  
Generated responses become more consistent, relevant, and structured when answering domain-related questions.

Despite the small dataset size, the model shows clear learning behavior after applying LoRA fine-tuning.

---

## Limitations

- The dataset is relatively small, which limits generalization ability.  
- Training was performed using limited computational resources (Google Colab T4 GPU).  
- The model is intended for educational and experimental purposes rather than production use.

---

## Author

**Osama Hussein**  
Generative Artificial Intelligence Course – Final Project  
2026
