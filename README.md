<h1 align="center">Jakob Kauffmann</h1>

<p align="center">
   <a href="https://jakobkauffmann.github.io">jakobkauffmann.github.io</a> &nbsp;·&nbsp; <a href="https://scholar.google.com/citations?user=LZN0dxQAAAAJ">Google Scholar</a> &nbsp;·&nbsp; <a href="https://linkedin.com/in/jakobkauffmann">LinkedIn</a> &nbsp;·&nbsp; <a href="mailto:jakobkauffmann@gmail.com">jakobkauffmann@gmail.com</a>
</p>

## About

- Finished my MS in Computer Science at San José State University in May 2026
- First-author paper accepted at IEEE ICTAI 2026; first-author book chapter forthcoming from Springer (2027)
- Looking for new grad roles in ML engineering, research engineering, AI engineering, and software engineering, especially on ML and AI research teams. Available now.

## Experience

#### Apple · Software Engineering Intern, iOS Accessibility Team (Wearables) &nbsp;·&nbsp; *May 2025 – Aug 2025*
- Proposed bringing an accessibility feature that existed only on iOS to Apple Watch as my intern project, and ported it in Swift and Objective-C with guidance from my mentor, the feature owner
- Carried over the feature's system daemon, built a watch-native Settings UI, wrapped the iOS backend asset-delivery path to work on watchOS, and reached parity with iOS across Settings, Control Center, Shortcuts, and Widgets. Merged to main behind its own feature flag.
- Designed a device-to-device state synchronization layer, largely independently, that keeps the feature's continuity across the user's devices, with a prioritized resync on reconnect. Merged to main behind a separate feature flag for testing and future release.
- Assisted in refactoring wearables code that went into production.
- Merged code that brings the accessibility feature to a wearable device for the first time and keeps it seamless across devices.
- Demoed the work to the 50+ person Accessibility team, and separately to the Accessibility director and managers.

## Education

#### San José State University &nbsp;·&nbsp; *May 2026*
**Master of Science, Computer Science** &nbsp;·&nbsp; Advisor: Dr. Faranak Abri
- Thesis: *Targeted Bottlenecking of Self-Supervised Speech Layers for Generalizable Audio Deepfake Detection*. Defended May 2026; full text under embargo until May 2027 ([DOI](https://doi.org/10.31979/etd.kmc6-t6vf))
- Coursework: Machine Learning, Artificial Intelligence, Natural Language Processing, Biometric Security with AI

#### University of Virginia &nbsp;·&nbsp; *Aug 2020 – Aug 2023*
**Bachelor of Arts, Computer Science** &nbsp;·&nbsp; Minor in Data Science
- Echols Scholar
- Coursework in Data Structures & Algorithms, Machine Learning, Data Science, Cybersecurity, and Audio Engineering

## Research

- **Thesis and ICTAI 2026 paper:** why audio deepfake detectors trained on one dataset break down on unfamiliar recording channels, codecs, and speech synthesizers. The work places variational information bottlenecks and adversarial domain discriminators on groups of layers in self-supervised speech models (WavLM, XLS-R, Wav2Vec2, Data2Vec) and studies where in the model the bottleneck helps most. The thesis and code are under embargo until after ICTAI Proceedings.
- **Book chapter:** *Speech Deepfake Detection: A Survey of Methods, Benchmarks, and Generalization Challenges*, in *Artificial Intelligence for Cyber Defense in Emerging Threats* (ed. Dr. Mark Stamp; Springer, forthcoming 2027).

## Projects

- **[Noise-Robust Voice Authentication](https://github.com/JakobKauffmann/Noise-Robust-Voice-Auth):** speaker verification fusing SincNet (raw waveform) and MobileNetV2 (mel spectrogram) embeddings on VoxCeleb1, trained with MUSAN noise augmentation. Report and slides included.
- **[AI-Generated Text Detection](https://github.com/JakobKauffmann/ai-text-detection):** compares MLP, CNN, and AdaBoost classifiers on SBERT, InferSent, and USE embeddings to separate human-written text from GPT and Llama output. With Christofer Berruz.
- **[IoT Intrusion Detection](https://github.com/JakobKauffmann/iot-intrusion-detection):** seven classifiers on CICIoT2023, tested for transfer to CICIoMT2024, with a [Streamlit demo](https://github.com/JakobKauffmann/streamlit). With Zhuoqun Wei.
- **[Political Bias and Sentiment Analysis](https://github.com/JakobKauffmann/news-bias-sentiment-analyzer):** Flask web app combining transformer classifiers with Llama 3 summaries of news articles. With Vibha Bhavikatti, Rudraksh Naik, and Michael Vong.
