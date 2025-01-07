# Genhancer-high-fidelity-generative-speech-enhancement
Official repo for INTERSPEECH 2024 paper <i>Genhancer: High-Fidelity Speech Enhancement via Generative Modeling on Discrete Codec Tokens</i>, providing additional audio samples.

- Paper: https://www.isca-archive.org/interspeech_2024/yang24h_interspeech.pdf
- Website:  https://minjekim.com/research-projects/genhancer/ (Audio examples, illustrations and supplement experimental details for training)
- Authors: [Haici Yang](https://haiciyang.github.io), Jiaqi Su, Minje Kim, Zeyu Jin

## Abstract
We present a high-fidelity generative speech enhancement model, Genhancer, which generates clean speech as discrete codec tokens while conditioning on the input speech features. Discrete codec tokens provide an efficient latent domain in place of the conventional time or time-frequency domain of signals, so as to enable complex modeling of speech and allow generative modeling to enforce speaker consistency and content continuity. We provide insights into the best-fit generation scheme for enhancement among parallel prediction, auto-regression, and masking to demonstrate the benefits of conditioning on both pre-trained and jointly learned speech features. Subjective and objective tests show that Genhancer significantly improves audio quality and speaker-identity retention over the SOTA baselines, including conventional and generative ones while preserving content accuracy.
![title](Images/example.png)
