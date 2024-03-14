# XAI-GANs

Created our own deep faked audio using Generative Adversarial Neural Networks (GANs) and objectively evaluate generator quality using Fréchet Audio Distance (FAD) metric. We augment a pre-existing dataset of real audio samples with our fake generated samples and classify data as real or fake using MobileNet, Inception, VGG and custom CNN models. MobileNet is the best performing model with an accuracy of 91.5% and precision of 0.507. We further convert our black box deep learning models into white box models, by using explainable AI (XAI) models. We quantitatively evaluate the classification of a MEL Spectrogram through LIME, SHAP and GradCAM models. We compare the features of a spectrogram that an XAI model focuses on to provide a qualitative analysis of frequency distribution in spectrograms.

## System Design 

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/b95031f5-0de6-493c-8fa5-1f8276dab211)

## Algorithm 1

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/52db216d-9df3-4e88-bbf1-59d8da1e3652)

## Spectogram results for MobileNet Model

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/84f8cb8b-d9ea-44f5-90c5-34fcec7dda57)


