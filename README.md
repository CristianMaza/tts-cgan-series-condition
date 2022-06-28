# TTS-CGAN: A Transformer Time-Series Conditional GAN for Biosignal Data Augmentation
---

This repository contains code from the paper "TTS-CGAN: A Transformer Time-Series Conditional GAN for Biosignal Data Augmentation".

The paper is under review.

This work is extended from the paper "TTS-GAN: A Transformer-based Time-Series Generative Adversarial Network".

Check previous paper from [here](https://arxiv.org/abs/2202.02691). Get the code from [here](https://github.com/imics-lab/tts-gan).

---

**Abstract:**
Signal measurement appearing in the form of time series is one of the most common types of data used in medical machine learning applications. Such datasets are often small in size, expensive to collect and annotate, and might involve privacy issues, which hinders our ability to train large, state-of-the-art deep learning models for biomedical applications. For time-series data, the suite of data augmentation strategies we can use to expand the size of the dataset is limited by the need to maintain the basic properties of the signal. Generative Adversarial Networks (GANs) can be utilized as another data augmentation tool. In this paper, we present TTS-CGAN, a transformer-based conditional GAN model that can be trained on existing multi-class datasets and generate class-specific synthetic time-series sequences of arbitrary length. We elaborate on the model architecture and design strategies. Synthetic sequences generated by our model are indistinguishable from real ones, and can be used to complement or replace real signals of the same type, thus achieving the goal of data augmentation. To evaluate the quality of the generated data, we modify the wavelet coherence metric to be able to compare the similarity between two sets of signals, and also conduct a case study where a mix of synthetic and real data are used to train a deep learning model for sequence classification. Together with other visualization techniques and qualitative evaluation approaches, we demonstrate that TTS-CGAN generated synthetic data are similar to real data, and that our model performs better than the other state-of-the-art GAN models built for time-series data generation. 

**Major Contributions:**

Use Transformer GAN to generate multi-category synthetic time-series data.

Use Wavelet Coherence score to compare the similarity between two sets of signals.

**The TTS-CGAN Architecture** 
![TTS-CGAN Architecture](./TTS-CGAN.png)




