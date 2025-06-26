#  Article Summarization 

This project demonstrates how to perform **abstractive text summarization** using Hugging Face's `T5-small` transformer model. We utilize the **Multi-News** dataset, which contains clusters of related news articles along with their human-written summaries.

The main objective is to generate summaries from the model and **compare them with summaries from online summarizers** to evaluate their quality and coherence.

---

## Project Objectives

- Load and explore the **Multi-News** dataset
- Compare model-generated summaries with those from online summarizers
- Lay groundwork for further fine-tuning and evaluation

---

##  Technologies & Libraries Used

| Tool/Library     | Purpose                                      |
|------------------|----------------------------------------------|
| Python           | Core programming language                    |
| Google Colab     | Interactive development and experimentation |
| `transformers`   | Pretrained NLP models (T5-small)             |
| `datasets`       | Accessing and handling the Multi-News dataset |
| `accelerate`     | Efficient model execution on CPU/GPU/TPU     |
| `pandas`         | Data handling and transformation             |

---

