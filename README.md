# ATST-SED
This repo includes the official implementations of "Fine-tune the pretrained ATST model for sound event detection".

This work is submitted to ICASSP 2024.

[Paper :star_struck:](TBC) **|** [Issues :sweat_smile:](https://github.com/Audio-WestlakeU/ATST-SED/issues)
 **|** [Lab :hear_no_evil:](https://github.com/Audio-WestlakeU) **|** [Contact :kissing_heart:](sao_year@126.com)

# Introduction

In a nutshell, ATST-SED proposes a fine-tuning strategy for the pretrained model integrated with the CRNN SED system.
<div align="center">
<image src="/src/flowchart.png"  width="500" alt="The proposed fine-tuning method for ATST-SED" />

---

# Performance

| Dataset | External set | PSDS_1 | PSDS_2 |
| :--------: | :--: | :----: | :----: |
| DCASE dev. set | - | 0.583 | 0.810 |
| DCASE public eval. set | - | 0.62x | 0.83x |
| DCASE dev. set | Used | 0.587 | 0.812 |
| DCASE public eval. set | Used | 0.62x | 0.83x |