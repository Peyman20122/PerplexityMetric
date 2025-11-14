# PerplexityCalculator

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

<img width="537" height="282" alt="image" src="https://github.com/user-attachments/assets/ce2e5fc6-d800-434e-bda9-528b8d166b3c" />

### Use with Persian model:

<img width="635" height="181" alt="image" src="https://github.com/user-attachments/assets/220c03bb-de71-4242-a036-a387362463c9" />

### Features

- Calculate Perplexity for arbitrary texts
- Model quality assessment: Good / Medium / Bad
- Supports English and Persian GPT models
- Suitable for industrial projects and testing NLP models

### Notes

- Perplexity is the only measure of the quality of the model language; for a more accurate assessment, also check task-specific measures.
- Encoder-only models such as BERT and T5 do not directly calculate Perplexity.
- API-driven models (such as GPT-3.5, GPT-4, GPT-5) require an approximate calculation with logprobs.
