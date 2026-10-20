# Artificial Intelligence Based Noise Modulation Approaches for Modern Communication Systems

A literature review by **Team 9**. We screened about 90 research papers on noise, modulation, and AI/machine-learning techniques in communication systems, classified them, and wrote structured summaries of 10 selected papers.

## Team

| Name | Registration No. |
|---|---|
| Ritvik Anish | 23BEE1018 |
| Sanjh Yadav | 23BEE1043 |
| Sriram V | 23BEE1110 |

## What's in this repository

| Item | Description |
|---|---|
| [`docs/TEAM_9_Final.docx`](TEAM_9_Final.docx) | The final report: structured summaries of 10 selected papers |
| [`data/Research_Paper_Classification.xlsx`](Research_Paper_Classification.xlsx) | Classification of all 94 papers screened during the research |

> The original PDFs we read are **not** included. They are copyrighted by their publishers. Titles are listed in the classification sheet so you can find each paper through its publisher, IEEE Xplore, or your library.

## Scope

The review covers how noise is handled, exploited, and modelled in modern communication systems, with an emphasis on AI-based methods. Topics across the screened papers include:

- Automatic modulation recognition / classification (CNN, DNN, autoencoder-based)
- SNR estimation and spectrum monitoring
- Phase noise in coherent optical and high-order modulation systems
- Noise-robust feature enhancement (e.g., speaker recognition)
- Artificial noise for physical-layer security and directional modulation
- Noise modulation schemes (thermal-noise, on-off, energy-transfer, data hiding)
- Noise shaping and denoising in receivers, ADCs and optical links
- RIS-aided, 5G/6G, and IoT communication systems

## Papers reviewed in depth

Each paper is summarized in the report under these headings: objective, methodology, key findings, applications, and limitations / future work.

| # | Paper | Key takeaway |
|---|---|---|
| 1 | An Improved Ranking-Based Feature Enhancement Approach for Robust Speaker Recognition | Ranking-based feature enhancement beats conventional feature warping and missing-data methods across all tested noise types and SNRs |
| 2 | Phase Noise Effects on Phase-Modulated Coherent Optical OFDM | A mean-phase-compensation method prevents phase-wrapping errors; low-frequency subcarriers suffer most from phase noise |
| 3 | Pragmatic Phase Noise Compensation for High-Order Coded Modulations | An iterative receiver separating decoding from synchronization comes within about 0.1 dB of joint MAP at much lower complexity |
| 4 | Joint Modulation Format/Bit-Rate Classification and SNR Estimation in Multipath Fading Channels Using Deep Machine Learning | Deep networks on asynchronous delay-tap plots reach about 99.8% classification accuracy with about 1 dB mean SNR error |
| 5 | Modulation Scheme Recognition Using Convolutional Neural Network | Spectrogram images plus an AlexNet-style CNN approach 100% accuracy above 12 dB SNR across AM, FM, FSK and BPSK |
| 6 | End-to-End Learning From Spectrum Data: A Deep Learning Approach for Wireless Signal Identification in Spectrum Monitoring Applications | The best data representation (IQ, amplitude-phase, or FFT) depends on the identification task |
| 7 | GPI-Based Secrecy Rate Maximization Beamforming Scheme for Wireless Transmission With AN-Aided Directional Modulation | Joint beamforming and artificial-noise optimization improves secrecy rate over null-space and leakage-based baselines |
| 8 | A Pulse Frequency Modulation Interpretation of VCOs Enabling VCO-ADC Architectures with Extended Noise Shaping | Reinterpreting VCOs as pulse frequency modulators enables higher-order noise shaping in open-loop VCO-ADCs |
| 9 | Effects of Multi-Level Format in MMF System Based on Mode-Field Matched Center-Launching Technique | PAM4 is far more sensitive to beat noise than OOK; a multimode-fiber-pigtailed receiver cuts the power penalty from 3.9 dB to 0.9 dB |
| 10 | Simultaneous Determination of Modulation Types and Signal-to-Noise Ratios Using Feature-Based Approach | Amplitude histograms with PCA and SVM reach 99.83% modulation accuracy and 0.79 dB SNR error with a single low-speed sampler |

## Classification of screened papers

All screened papers are listed in [`data/Research_Paper_Classification.xlsx`](data/Research_Paper_Classification.xlsx) with a category label.

| Category | Count |
|---|---|
| Journal / General Paper | 93 |
| Conference Paper | 1 |
| **Total rows** | **94** |

## Citation

If you reference this work:

```
Anish, R., Yadav, S., & V, S. (2026). Artificial Intelligence Based Noise Modulation
Approaches for Modern Communication Systems [Literature review]. Team 9.
```

## Notes on the sources

This report summarizes and discusses work by other authors. All credit for the original research belongs to the authors of the papers listed above. Please cite the original papers when using their results.
