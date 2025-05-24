# bert-morph-tagger-udmurt

This repository contains the training code for an encoder-based (BERT-like) model for morphological tagging. The trained model performs fine-grained token-level morphological parsing.

🤗 [Morphological parser for Udmurt on HuggingFace Hub](https://huggingface.co/ulyanaisaeva/bert-morph-tagger-udmurt) 🤗

The training code was used to train a morhological tagging model for the Udmurt language, which is morphologically rich and relatively low-resource. The model is based on [`cis-lmu/glot500-base`](https://huggingface.co/cis-lmu/glot500-base) multilingual encoder-only model fine-tuned for morphological analysis. The model weights are available on the Hugging Face Hub.


## Features

- Supports both standart cross-entropy training and soft training for morhological ambiguity
- Training implemented using the `transformers` library for seamless compatibility with Hugging Face ecosystem
- Easily adaptable to other languages

**NB: the [training data](http://udmurt.web-corpora.net/) used in this project is not a public dataset but is available for researchers by request to the owner.**


## Citation

If you use this repository or the model in your research, please cite the related publication:

> [Citation coming soon, paper under anonymous review]


---

Feel free to open issues or contribute improvements via pull requests.  
For questions or support, please contact ulyana.isaeva20@gmail.com.
