# Hi, I'm Bas

I'm a machine learning engineer working on LLMs and multilingual NLP, with a background in computational neuroscience.
Most of my open source work is in the PyTorch ecosystem, on the parts around the model itself: how you evaluate it, how you train it reliably, and how you make it fast at inference.

## Open source

**[TorchMetrics](https://github.com/Lightning-AI/torchmetrics)** — *core maintainer, 2025*

The evaluation library for PyTorch. I reviewed community pull requests and co-authored several that added new metrics, such as Hausdorff distance, cluster accuracy and DNSMOS. I also built the documentation galleries for text, multimodal and audio metrics (BERTScore, ROUGE, CLIPScore) and fixed issues in BERTScore and the classification metrics. [My pull requests →](https://github.com/Lightning-AI/torchmetrics/pulls?q=is%3Apr+author%3Abaskrahmer)

**[PyTorch Lightning](https://github.com/Lightning-AI/pytorch-lightning)** — *contributor, 2023 and 2025*

Added non-strict checkpoint loading to Fabric and configurable profiler tables, and fixed bugs in the learning-rate finder, `save_last` checkpointing and `no_grad` under AMP. [My pull requests →](https://github.com/Lightning-AI/pytorch-lightning/pulls?q=is%3Apr+author%3Abaskrahmer)

**[Hugging Face Optimum](https://github.com/huggingface/optimum)** — *contributor, 2023*

Added BetterTransformer inference optimization for BLOOM and BLIP-2, ONNX export for Swin2SR, and ViT support in the ONNX Runtime optimizer. [My pull requests →](https://github.com/huggingface/optimum/pulls?q=is%3Apr+author%3Abaskrahmer)

**[perturbers](https://github.com/FairNLP/perturbers)** — *author, 2024*

A neural data augmentation library for fairness in NLP, building on [Qian et al. (2022)](https://arxiv.org/abs/2205.12586). It comes with BART-based perturber models on [Hugging Face](https://huggingface.co/fairnlp), along with BERT/ALBERT debiasing models and bias-evaluation datasets (HolisticBias, WEAT).

**[LEAF](https://github.com/baskrahmer/LEAF)** — *author, 2024*

Multilingual models that predict the environmental impact of a food product from its name alone, in over 50 languages. The repository has the code, data and models behind my [ACL ClimateNLP 2024 paper](https://aclanthology.org/2024.climatenlp-1.10/).

## Research

- **End-to-end topographic networks as models of cortical map formation and human visual behaviour.** Lu, Doerig, Bosch, Krahmer, Kaiser, Cichy & Kietzmann. *Nature Human Behaviour*, 2025. [Paper](https://doi.org/10.1038/s41562-025-02220-7)
- **LEAF: Predicting the Environmental Impact of Food Products based on their Name.** Krahmer. *ACL ClimateNLP*, 2024 (oral). [Paper](https://aclanthology.org/2024.climatenlp-1.10/)

## Find me

[Website](https://baskrahmer.nl) · [LinkedIn](https://www.linkedin.com/in/baskrahmer/) · [Google Scholar](https://scholar.google.com/citations?user=mATiKYgAAAAJ) · [Hugging Face](https://huggingface.co/baskra)
