# CS3 – DS4002: Can You Trust Your Eyes?

This repository contains the dataset instructions, rubric, and reference materials necessary to complete the case study on AI vs. Real image classification.

## Important Information
The attached PDFs include both the Hook Document, which introduces the case study and your mission, and the Rubric, which outlines all requirements and criteria you must meet to complete the assignment successfully.

## Data
The dataset used for this case study is sourced from Hugging Face and can be loaded directly in Python using the following code:

```python
from datasets import load_dataset
ds = load_dataset("Hemg/AI-Generated-vs-Real-Images-Datasets")
```

No manual download is required. Make sure you have the `datasets` package installed before running this. You can install it by running:

```bash
pip install datasets
```

## Reference Materials
The Reference Materials folder contains helpful resources related to AI-generated imagery, an introduction to Convolutional Neural Networks, and technical documentation to support your implementation. These are a starting point. You are encouraged to seek out additional sources as needed.

## References:
Dataset: Hugging Face — AI-Generated vs Real Images  
https://huggingface.co/datasets/Hemg/AI-Generated-vs-Real-Images-Datasets

Image on Hook Document: C. Bush, "How to Spot AI-Generated Photos: Real vs. Fake," Charles Bush Photography, Nov. 3, 2025. [Online]. Available: https://charlesbushphoto.com/charles-bush-photography-news/2025/11/ai-generated-vs-real-photos.
