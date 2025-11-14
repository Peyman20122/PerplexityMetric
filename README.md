# PerplexityCalculator

<img width="852" height="496" alt="image" src="https://github.com/user-attachments/assets/3ed304a3-5bad-4659-985f-a1e0a259c5f1" />

**PerplexityCalculator** is a simple and professional Python class for calculating **Perplexity** and evaluating the quality of language models. This tool is suitable for NLP projects, chatbots and content generation models.

---

##  Download and install

### 1. Download the file directly
You can download the `perplexity_calculator.py` file from GitHub:

[Download perplexity_calculator.py](https://github.com/USERNAME/REPO_NAME/raw/main/perplexity_calculator.py)

### 2. Install the required libraries

```bash
pip install torch transformers
```
### How to use :

**Load model and tokenizer :**

<img width="482" height="60" alt="image" src="https://github.com/user-attachments/assets/6447a610-699c-4627-b797-44348f235c6c" />

**Input text which can be Persian or English :**

<img width="319" height="42" alt="image" src="https://github.com/user-attachments/assets/3035f857-ccbb-48c1-b27a-6223b585bd18" />

**Calculate Perplexity :**

<img width="478" height="83" alt="image" src="https://github.com/user-attachments/assets/06bae6b0-12a6-4b21-adf7-6f60caffad5c" />


### Features

- Calculate Perplexity for arbitrary texts
- Model quality assessment: Good / Medium / Bad
- Supports English and Persian GPT models
- Suitable for industrial projects and testing NLP models

### Notes

- Perplexity is the only measure of the quality of the model language; for a more accurate assessment, also check task-specific measures.
- Encoder-only models such as BERT and T5 do not directly calculate Perplexity.
- API-driven models (such as GPT-3.5, GPT-4, GPT-5) require an approximate calculation with logprobs.
