# evals

## MUST-C 

| Model                     |   BLEU↑ |     AL↓ |    AP↓ |    DAL↓ |
|:--------------------------|--------:|--------:|-------:|--------:|
| Best IWSLT21 system       |   27.4  |  920    |   0.68 | 1420    |
| Best IWSLT21 system       |   29.68 | 1860    |   0.82 | 2650    |
| Best IWSLT21 system       |   30.75 | 2740    |   0.9  | 3630    |
| KIT IWSLT 2020            |   27.05 |  947    |   0.76 | 1993    |
| KIT IWSLT 2020            |   30.3  | 1660    |   0.84 | 2662    |
| KIT IWSLT 2020            |   31.41 | 2966    |   0.93 | 3853    |
| KIT IWSLT 2020            |   31.36 | 5794    |   1    | 5794    |
| KIT IWSLT 2020            |   26.93 |  945    |   0.77 | 2052    |
| KIT IWSLT 2020            |   31.6  | 1906    |   0.86 | 2945    |
| KIT IWSLT 2020            |   32.98 | 3663    |   0.96 | 4452    |
| KIT IWSLT 2020            |   33.14 | 5794    |   1    | 5794    |
| wav2vec2 + mBART          |   16.84 | 2452    |   0.9  | 3212    |
| wav2vec2 + mBART          |   16.99 | 3791    |   0.97 | 4296    |
| wav2vec2 + mBART          |   16.97 | 4140    |   0.98 | 4536    |
| wav2vec2 + mBART          |   16.88 | 5119    |   1    | 5119    |
| wav2vec2 + mBART          |   23.69 | 1761    |   0.85 | 2561    |
| wav2vec2 + mBART          |   24.29 | 2788    |   0.93 | 3500    |
| wav2vec2 + mBART          |   24.56 | 3669    |   0.97 | 4212    |
| wav2vec2 + mBART          |   24.54 | 5119    |   1    | 5119    |
| CUNI-LIT IWSLT 2022       |   30.6  | 1922    | nan    | 3121    |
| CUNI-LIT IWSLT 2023       |   31.7  | 1977    | nan    | 2518    |
| CUNI-LIT IWSLT 2022       |   15.5  | 1902    | nan    | 3000    |
| CUNI-LIT IWSLT 2023       |   15.3  | 1984    | nan    | 3489    |
| CUNI-LIT IWSLT 2022       |   26.8  | 1982    | nan    | 3289    |
| CUNI-LIT IWSLT 2023       |   31.4  | 1985    | nan    | 3072    |
| CUNI-LIT IWSLT 2022       |   15.3  | 1984    | nan    | 3508    |
| CUNI-LIT IWSLT 2023       |   26.6  | 1987    | nan    | 3489    |
| Best IWSLT22 System       |   26.82 |  960    |   0.77 | 2070    |
| HW-TSC                    |   **33.54** | 1880    |   0.83 | 2840    |
| Best IWSLT22 System       |   31.47 | 1930    |   1.06 | 2960    |
| HW-TSC                    |   27.23 | 1980    |   0.83 | 2890    |
| Best IWSLT22 System       |   25.87 | 1990    |   1.04 | 3350    |
| HW-TSC                    |   27.93 | 3970    |   1.08 | 4620    |
| Best IWSLT22 System       |   25.87 | 1990    |   1.04 | 3350    |
| HW-TSC                    |   27.93 | 3970    |   1.08 | 4620    |
| HW-TSC                    |   27.23 | 1980    |   1.08 | 2890    |
| IBWBS                     |   30.6  | 1922    | nan    | 3121    |
| CTC                       |   31.7  | 1946    | nan    | 2518    |
| IBWBS                     |   26.5  | 2855    | nan    | 4285    |
| CTC                       |   25.8  | 1981    | nan    | 3515    |
| wav2vec2 + mBART + LA-2   |   16.34 |  nan |   0.66 | 1435.06 |
| wav2vec2 + mBART + LA-2   |   25.4  |  **727.55** |   0.73 | 1791.21 |
| wav2vec2 + mBART + LA-2   |   30.29 | 1660.59 |   0.83 | 2662.18 |
| wav2vec2 + mBART + LA-2   |   30.29 | 1654.77 |   0.83 | 2657.48 |
| Wait-K (Ma et al., 2020c) |   13.95 | 1750    |   0.79 |    **1.98** |
| CAAT(Liu et al., 2021b)   |   22.1  | 1920    |   0.86 |    2.52 |
| Wang et al. (2022a)       |   22.13 | 2370    |   0.86 |    2.65 |
| Liu et al. (2021a)        |   29.68 | 1860    |   0.82 |    2.65 |
| Polák et al. (2022)       |   31.47 | 1930    |   0.86 |    2.96 |
| R-BI                      |   31.69 | 1920    |   0.77 |    2.63 |
| Wang et al. (2022a)       |   12.82 | 1840    |   0.94 |    3.37 |
| Polák et al. (2022)       |   16.92 | 2460    |   0.9 |    3.22 |
| R-BI                      |   16.28 | 1860    |   0.81 |    2.45 |
| Wang et al. (2022a)       |   20.38 | 1750    |   0.94 |    3.34 |
| Polák et al. (2022)       |   23.61 | 1750    |   0.85 |    2.56 |
| Zhu et al. (2022)         |   22.49 | 1270    |   0.85 |    2.56 |
| R-BI                      |   24.36 | 1870    |   0.92 |    2.68 |
| gpt-3.5-turbo-0613        |    2.08 | 2574.98 |   **0.35** | 2477.55 |
| gpt-4-0613                |   21.82 | 1998.63 |   0.94 | 2314.27 |
| Llama-70b-hf (SFT)        |   18.41 | 1619.64 |   0.84 | 2454.72 |
| Llama-13b-hf (SFT)        |   17.07 | 1880.76 |   0.88 | 2545.74 |
| EDATT                     |   17.01 | 1867.1  |   0.77 | 3251.38 |
| NAIST IWSLT 2023          |   21.08 | 1397.33 |   0.9  | 3066.15 |
|:--------------------------|--------:|--------:|-------:|--------:|
| toby (Ours)               |   **50.1** | 2352.19 |   nan  | nan |


## Europarl-ST
| BLEU↑ | System            | Pre-trained Model     | Parameters   | en-es Europarl-ST (dev)   |   en-es Europarl-ST (test) | es-en Europarl-ST (dev)   |   es-en Europarl-ST (test) |
|---:|:------------------|:----------------------|:-------------|:--------------------------|---------------------------:|:--------------------------|---------------------------:|
|  0 | S2UT              | w/o pre-training      | Large (827M) | -                         |                       21.8 | -                         |                       18.8 |
|  1 | wav2vec 2.0+mBART | wav2vec 2.0+mBART     | Large (827M) | 25.7                      |                       26   | 25.7                      |                       23.8 |
|  2 | HuBERT            | HuBERT                | Base (157M)  | 20.2                      |                       19.1 | 21.1                      |                       19.2 |
|  3 | Ours              | HuBERT+mBART          | Base (157M)  | 21.8                      |                       20.9 | 23.2                      |                       21.1 |
|  4 | Speech2S          | Speech2S              | Base (157M)  | 25.3                      |                       25.6 | 26.8                      |                       24.4 |
|  5 | C1 ASR→MT→TTS     | wav2vec 2.0+mBART     | Large (827M) | 28.8                      |                       29.1 | 31.5                      |                       32.4 |
|  6 | C2 ASR→MT→TTS     | wav2vec 2.0+mBART     | Large (827M) | 33.8                      |                       30.3 | 34.2                      |                   **32.5** |
|  7 | C3 S2UT+TTS       | S2UT                  | Base (157M)  | 32.4                      |                       29.1 | 34.8                      |                       31.7 |
|  8 | C4 S2UT+mBART     | S2UT+mBART            | Base (157M)  | **35.6**                  |                   **31.4** | **36.9**                  |                       31.9 |
|  9 | S2UT w/ orig-unit | HuBERT + Kmeans + CTC | nan          | 13.1                      |                       15.6 | 15.4                      |                       16.4 |
| 10 | S2UT w/ orig-unit | HuBERT + Kmeans + CTC | nan          | 16.1                      |                       19.3 | 16.6                      |                       18.5 |
| 11 | S2UT w/ norm-unit | HuBERT + Kmeans + CTC | nan          | 17.8                      |                       20.4 | 18.5                      |                       20.3 |
| 12 | S2UT w/ norm-unit | HuBERT + Kmeans + CTC | nan          | 18.8                      |                       21.8 | 20.3                      |                       21.8 |
| 13 | S2UT w/ norm-unit | HuBERT + Kmeans + CTC | nan          | 18.9                      |                       22.7 | 19.9                      |                       22.7 |
| 14 | S2UT+tf TTS       | HuBERT + Kmeans + CTC | nan          | 19.2                      |                       21.7 | 19.8                      |                       21.7 |
| 15 | S2UT+T2U          | HuBERT + Kmeans + CTC | nan          | 19.4                      |                       21.8 | 19.7                      |                       21.8 |
|---:|:------------------|:----------------------|:-------------|:--------------------------|---------------------------:|:--------------------------|---------------------------:|

### Naturalness
| Method                     |   MOS↑ |   SMOS↑ |
|:---------------------------|------:|-------:|
| S2UT w/ orig-unit          |  2.32 |   2.08 |
| S2UT w/ norm-unit (10-min) |  2.99 |   3.07 |
| S2UT w/ norm-unit (1-hr)   |  3.2  |   3.26 |
| S2UT w/ norm-unit (10-hr)  |  3.26 |   3.27 |
| S2UT+tf TTS                |  3.23 |   3.22 |
| Translation GT             |  4.22 | nan    |
| DirectS2ST                 |  4.01 | nan    |
| TextlessS2ST               |  4.05 | nan    |
| TranSpeech                 |  4.03 | nan    |
| Direct S2ST                |  3.66 |   3.51 |
| StyleS2ST                  |  3.76 |   3.83 |
| StyleS2ST-base             |  3.72 |   **3.85** |
| Baseline (YourTTS)         |  3.36 | 3.42    |
| VALL-E X                   |  3.54 | 4.0    | 
| Speech2S                   |  4.1  | nan    |
| Speech2S+DAT               |  **4.3**  | nan    |
| UnitY               |  4.2  | nan    |
| ASR (beam=10) + MT (beam=5) + TTS                | 3.37                 | nan |
| S2T (beam=10) + TTS                              | 3.43                 | nan |
| S2UT                       |  4.02    | nan    |
| S2UT, no reduction (r = 1, w/ sc, tc)            | 3.35                 | nan |
| S2UT stacked + CTC (r = 5, w/ sc, tc)            | 3.32                 | nan |
| S2UT reduced + CTC (w/ sc, tc, beam=10)          | 3.41                 | nan |
| Translatotron                 | 3.69                 | nan |
| Translatotron + Transformer (r = 5, w/ sc, tc)     | 3.31                 | nan |
| Translatotron 2                | 3.98                 | nan |
| Translatotron 2 + data augmentation            | 3.79                 | nan |

|    | Method       |   SNR↑ |
|---:|:-------------|------:|
|  0 | DirectS2ST   | 46.45 |
|  1 | TextlessS2ST | 47.22 |
|  2 | TranSpeech   | 46.56 |

## Libri
|    | Method                          |   CER↓ (%) |   WER↓ (%) |   Speaker Classification Accuracy↑ (%) |
|---:|:--------------------------------|------:|------:|--------------------------------------:|
|  0 | GROUND TRUTH                    |   0.8 |   2.5 |                                 100   |
|  1 | Reconstruction with SoundStream |   0.9 |   2.6 |                                 100   |
|  2 | AudioLM                         |   3.4 |   6.0 |                                   **92.6** |
|  3 | GSLM unit-to-speech             |   2.9 |   6.6 |                                  nan |
|  4 | w2v2-CTC                        |   **1.7** |   5.4 |                                  12.8 |
|  5 | Transformer                     |   2.5 |   5.6 |                                  15   |
|  6 | w2v2-CTC+TDN                    |   2.3 |   **5.3** |                                  17.6 |
| 7 | w2v-large | nan | 26.17 | nan | 
| 8 | Whisper-base | nan | 38.04 | nan |
| 9 | StreamSpeech | nan | 24.67 | nan |  

## Inference
| model               | mode | quantization | system message | size, bn param. | RTF↑ |
|---------------------|------|--------------|----------------|-----------------|-----|
| TRANSLLAMA                | T2TT | 4-bit        | no             | 70              | 14.6 |
| TRANSLLAMA                | T2TT | 4-bit        | yes            | 70              | 20.2 |
| TRANSLLAMA                | S2TT | 4-bit        | no             | 70              | 15.3 |
| TRANSLLAMA                | S2TT | 4-bit        | yes            | 70              | **23.9** |
| GPT-4               | T2TT | nan      | yes            | nan         | 1.5 |
| GPT-4               | S2TT | nan      | yes            | nan         | 4.8 |
| EDATT | S2TT | 16-bit       | nan            | 1.04            | 0.7 |
| NAIST IWSLT 2023  | S2TT | 16-bit       | nan            | 0.176           | 1.4 |
| UnitY | S2TT | nan | nan | 0.95 | 1.19 | 
| StreamSpeech | S2TT | nan | nan | 0.7 | 4.5 | 
| S2UT                              | S2TT   | L11 km1000     |     nan             |              0.65 |   1    |
| TranSpeech - Distill              | S2TT   |  nan              |    nan              |              0.39 |  11.04 |
| TranSpeech (iter=15)              | S2TT   |         nan       |     nan             |              0.39 |   5.34 |
| TranSpeech (iter=15 + b=15)       | S2TT   |        nan        |         nan         |              0.39 |   2.75 |
| TranSpeech (iter=15 + b=15 + NPD) | S2TT   |        nan        |      nan            |              0.39 |   2.53 |
