# Speech Synthesis Papers
A curated list of papers and datasets in Speech Synthesis (TTS).

**Please feel free to make a pull request to contribute to the list!**

## Contents

- [Papers](#Papers)
  - [Frontends](#Frontends)
  - [Prosody](#Prosody)
  - [Adaptive TTS](#Adaptive-TTS)
- [Datasets](#Datasets)
  - [Monolingual](#Monolingual)
  - [Multilingual](#Multilingual)

## Papers

### Frontends

- **Deep Voice: Real-time Neural Text-to-Speech** (2017), S. Arik et al. [[pdf](https://arxiv.org/pdf/1702.07825.pdf)]
- **Tacotron: Towards End-to-End Speech Synthesis** (2017), Y. Wang et al. [[pdf](https://arxiv.org/pdf/1703.10135.pdf)]
- **Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions** (2017), J. Shen et al. [[pdf](https://arxiv.org/pdf/1712.05884.pdf)]
- **FastSpeech: Fast, Robust and Controllable Text to Speech** (2019), Y. Ren et al. [[pdf](https://arxiv.org/pdf/1905.09263.pdf)]
- **High Fidelity Speech Synthesis with Adversarial Networks** (2019), M. Binkowski et al. [[pdf](https://arxiv.org/pdf/1909.11646.pdf)]
- **FastSpeech 2: Fast and High-Quality End-to-End Text to Speech** (2020), Y. Ren et al. [[pdf](https://arxiv.org/pdf/2006.04558.pdf)]
- **Flowtron: an Autoregressive Flow-based Generative Network for Text-to-Speech Synthesis** (2020), R. Valle et al. [[pdf](https://arxiv.org/pdf/2005.05957.pdf)]
- **Glow-TTS: A Generative Flow for Text-to-Speech via Monotonic Alignment Search** (2020), J. Kim et al. [[pdf](https://arxiv.org/pdf/2005.11129.pdf)]
- **WaveGrad: Estimating Gradients for Waveform Generation** (2020), N. Chen et al. [[pdf](https://arxiv.org/pdf/2009.00713.pdf)]
- **WaveGrad 2: Iterative Refinement for Text-to-Speech Synthesis** (2021), N. Chen et al. [[pdf](https://arxiv.org/pdf/2106.09660.pdf)]

### Backends

- **WaveNet: A Generative Model for Raw Audio** (2016), A. Oord et al. [[pdf](https://arxiv.org/pdf/1609.03499.pdf)]
- **Parallel WaveNet: Fast High-Fidelity Speech Synthesis** (2017), A. Oord et al. [[pdf](https://arxiv.org/pdf/1711.10433.pdf)]
- **WaveGlow: A Flow-based Generative Network for Speech Synthesis** (2018), R. Prenger et al. [[pdf](https://arxiv.org/pdf/1811.00002.pdf)]
- **Efficient Neural Audio Synthesis** (2018), N. Kalchbrenner et al. [[pdf](https://arxiv.org/pdf/1802.08435.pdf)]
- **Adversarial Audio Synthesis** (2018), C. Donahue et al. [[pdf](https://arxiv.org/pdf/1802.04208.pdf)]
- **MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis** (2019), K. Kumar et al. [[pdf](https://arxiv.org/pdf/1910.06711.pdf)]

### Prosody

- **Towards End-to-End Prosody Transfer for Expressive Speech Synthesis with Tacotron** (2018), R. Skerry-Ryan et al. [[pdf](https://arxiv.org/pdf/1803.09047.pdf)]
- **Style Tokens: Unsupervised Style Modeling, Control and Transfer in End-to-End Speech Synthesis** (2018), Y. Wang et al. [[pdf](https://arxiv.org/pdf/1803.09017.pdf)]
- **Predicting Expressive Speaking Style From Text In End-To-End Speech Synthesis** (2018), D. Stanton et al. [[pdf](https://arxiv.org/pdf/1808.01410.pdf)]
- **Hierarchical Generative Modeling for Controllable Speech Synthesis** (2018), W. Hsu et al. [[pdf](https://arxiv.org/pdf/1810.07217.pdf)]
- **Robust and fine-grained prosody control of end-to-end speech synthesis** (2018), Y. Lee et al. [[pdf](https://arxiv.org/pdf/1811.02122.pdf)]
- **Controllable neural text-to-speech synthesis using intuitive prosodic features** (2020), T. Raitio et al. [[pdf](https://arxiv.org/pdf/2009.06775.pdf)]
- **PnG BERT: Augmented BERT on Phonemes and Graphemes for Neural TTS** (2021), Y. Jia et al. [[pdf](https://arxiv.org/pdf/2103.15060.pdf)]

### Adaptive TTS

- **Deep Speaker: an End-to-End Neural Speaker Embedding System** (2017), C. Li et al. [[pdf](https://arxiv.org/pdf/1705.02304.pdf)]
- **Neural Voice Cloning with a Few Samples** (2018), S. Arik et al. [[pdf](https://arxiv.org/pdf/1802.06006.pdf)]
- **Semi-Supervised Training for Improving Data Efficiency in End-to-End Speech Synthesis** (2018), Y. Chung et al. [[pdf](https://arxiv.org/pdf/1808.10128.pdf)]
- **Sample Efficient Adaptive Text-to-Speech** (2018), Y. Chen et al. [[pdf](https://arxiv.org/pdf/1809.10460.pdf)]
- **Zero-Shot Multi-Speaker Text-To-Speech with State-of-the-art Neural Speaker Embeddings** (2019), E. Cooper et al. [[pdf](https://arxiv.org/pdf/1910.10838.pdf)]
- **BOFFIN TTS: Few-Shot Speaker Adaptation by Bayesian Optimization** (2020), H. Moss et al. [[pdf](https://arxiv.org/pdf/2002.01953.pdf)]
- **AdaSpeech: Adaptive Text to Speech for Custom Voice** (2021), M. Chen et al. [[pdf](https://arxiv.org/pdf/2103.00993.pdf)]

## Datasets

### Monolingual

- **LJSpeech**, K. Ito & L. Johnson (English, 1 female, 24 hours) [[web](https://keithito.com/LJ-Speech-Dataset/)]
- **LibriTTS**, Google Research (English, 2456 speakers, 585 hours) [[web](https://research.google/tools/datasets/libri-tts/)]
- **VCTK**, University of Edinburgh (English, 109 speakers, 44 hours) [[web](https://datashare.ed.ac.uk/handle/10283/2950)]
- **AISHELL-3**, Beijing Shell Shell Tech (Mandarin, 218 speakers, 85 hours) [[web](http://www.aishelltech.com/aishell_3)]
- **KSS Dataset**, K. Park (Korean, 1 female, 12 hours) [[web](https://www.kaggle.com/bryanpark/korean-single-speaker-speech-dataset)]
- **JSUT**, S. Takamichi et al. (Japanese, 1 female, 10 hours) [[web](https://sites.google.com/site/shinnosuketakamichi/publication/jsut)]
- **Pavoque**, DFKI GmbH (German, 1 male, 12 hours) [[web](https://github.com/marytts/pavoque-data)]

### Multilingual

- **Tundra**, University of Edinburgh et al. (14 European) [[web](https://speech.zone/simple4all/product/the-tundra-corpus-2/index.html)]
- **M-AILABS**, I. Solak (9 European) [[web](https://www.caito.de/2019/01/the-m-ailabs-speech-dataset/)]
- **CSS10**, K. Park & T. Mulc (10 languages) [[web](https://github.com/Kyubyong/css10)]
- **LibriVox** (crowdsourced) [[web](https://librivox.org)]
