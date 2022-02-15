# Visual-Sound-Localization-in-the-Wild
Code for Visual Sound Localization in the Wild by Cross-Modal Interference Erasing (AAAI 2022).

Paper Link: [https://arxiv.org/pdf/2202.06406.pdf](https://arxiv.org/pdf/2202.06406.pdf)

Authors: 

Xian Liu*, Rui Qian*, Hang Zhou*, Di Hu, Weiyao Lin, Ziwei Liu, Bolei Zhou, and Xiaowei Zhou. (* denotes equal contribution)

The task of audio-visual sound source localization has been well studied under constrained scenes, where the audio recordings are clean. However, in real-world scenarios, audios are usually contaminated by off-screen sound and background noise. They will interfere with the procedure of identifying desired sources and building visual-sound connections, making previous studies non-applicable. In this work, we propose the \textbf{Interference Eraser (IEr)} framework, which tackles the problem of audio-visual sound source localization in the wild. The key idea is to eliminate the interference by redefining and carving discriminative audio representations. Specifically, we observe that the previous practice of learning only a single audio representation is insufficient due to the additive nature of audio signals. We thus extend the audio representation with our Audio-Instance-Identifier module, which clearly distinguishes sounding instances when audio signals of different volumes are unevenly mixed. Then we erase the influence of the audible but off-screen sounds and the silent but visible objects by a Cross-modal Referrer module with cross-modality distillation. Quantitative and qualitative evaluations demonstrate that our proposed framework achieves superior results on sound localization tasks, especially under real-world scenarios.

The authors are currently organizing the code and will release them once this is done.
