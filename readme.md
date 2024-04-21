# T5 Model Fine-Tuning and Optimization

This repository contains two Jupyter notebooks that demonstrate different approaches to fine-tuning the T5 model and the integration of QLoRA in the transformers library.

## Notebooks

### 1. `ft_t5_normal.ipynb`
This notebook demonstrates the conventional fine-tuning process of the T5 model using transformers library.

### 2. `ft_t5_qlora.ipynb`
In contrast, this notebook explores a more advanced fine-tuning approach by employing quantization "nf4" and lora.

## Results
Both notebooks provide a comparative analysis of:
- **BLEU Scores:** To assess the translation quality of the fine-tuned models.
- **Training Time:** To evaluate the efficiency of each fine-tuning approach.
- **Memory Usage:** To understand the resource requirements of each method.


