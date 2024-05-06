# English to Mandation Translator

---

## TL;DR

Build, train and test your translator model from scratch.

---

## Requirements

To use our dataset from [Hugging Face](https://huggingface.co/SouthernCrossAI) directly in your code, you are recommended to [register](https://huggingface.co/login) your own Hugging Face account beforehand:

![image-20240506163208066](/Users/yifan/Library/Application Support/typora-user-images/image-20240506163208066.png)

You may need to copy and paste your [Access Tokens](https://huggingface.co/settings/tokens) from your profile:

![image-20240506162842543](/Users/yifan/Library/Application Support/typora-user-images/image-20240506162842543.png)

You can always download and use our datasets manually from [here](https://huggingface.co/datasets/SouthernCrossAI/English_to_Mandarin).

---

## Install Environment

Install all dependencies through [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html):

```bash
conda env create -f environment.yml
```

---

## Reference

### Attention is All You Need

- View PDF: [arXiv:1706.03762 (cs)](https://arxiv.org/abs/1706.03762)
- Summary: "Attention is All You Need" proposes the Transformer architecture, replacing recurrent and convolutional layers with self-attention mechanisms. It achieves state-of-the-art results in machine translation tasks, enabling parallelisation and scalability. The model's key innovation is the self-attention mechanism, allowing it to attend to different positions in the input sequence simultaneously. This paper revolutionised natural language processing and laid the foundation for modern transformer-based models like BERT and GPT.

### LLM Visualisation Tool

- Link: [LLM Visualization](https://bbycroft.net/llm)

### Find Out Other Resources From Us

[Official Website](https://www.southerncross.ai) | [GitHub Repo](https://github.com/southern-cross-ai) | [Hugging Face](https://huggingface.co/SouthernCrossAI) | [Discord Group](https://discord.com/invite/nvVkJShz6K)



