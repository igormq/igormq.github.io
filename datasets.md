---
layout: page
title: Datasets
permalink: /datasets/
---

Here is a list of some publicly available speech/text datasets that I gathered in the last 4 years, mainly in PT-BR.

I hope this helps you :)

## Speech

* CETUC - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/alcaim.tar.gz)
    * CETUC dataset [1] contains almost 145 hours of speech signals performed by 50 male and 50 female speakers, each one pronouncing 1,000 phonetically balanced sentences selected from the CETEN-Folha corpus [38]. The CETUC dataset was recorded in acontrolled environment at a sampling rate of 16kHz.
* LapsBM - Download [part 1](http://www02.smt.ufrj.br/~igor.quintanilha/lapsbm-val.tar.gz) \| [part 2](http://www02.smt.ufrj.br/~igor.quintanilha/lapsbm-test.tar.gz)
    * LapsBM1.4 [2] is a dataset used by the Fala Brasil group of Fed- eral University of Pará to evaluate large vocabulary continuous speech recognition (LVCSR) system in Brazilian Portuguese. It contains 35 speakers (10 women), each one with 20 unique utterances, totaling 700 utterances. Audio has been recorded at 22.05 kHz without environment control.
* Sidney - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/sid.tar.gz)
    * Kindly provided by Dr. Sidney dos Santos for research purposes, this dataset contains recordings by 72 speakers (20 women) from 17 to 59 years old with fields such as place of birth, age, gender, education, and occupation. Recorded at 22.05kHz in a non-controlled environment, its 5,777 utterances were transcribed at word level without time alignment. Contents span from spoken digits, single words, complex sequences, spelling of name, and local of birth to phonetic covering, and semantically unpredictable sentences. Some excerpts were discarded due to a systematic transcription error found.
* VoxForge - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/voxforge-ptbr.tar.gz)
    * VoxForge [3] is the most heterogeneous corpus. The idea of VoxForge is to distribute transcribed speech audio under GPL license, facilitating the development of acoustic models. Everyone can record specific utterances and send to them. Their Portuguese Brazilian language section contains at least 111 speakers not all having information about genre or age. The audio files have been recorded at different sample rates ranging from 16 kHz to 44.1 kHz, and many records are in low-quality, presenting low signal-to-noise ratio (SNR). A total of 4,130 utterances were transcribed at word level for Brazilian Portuguese.



|             |          |  Words |   Words   |        | Speakers |       |
|-------------|----------|:------:|:---------:|-------:|:--------:|------:|
|   Dataset   |  Subset  |  Hours |   Total   | Unique |     M    |   F   |
|   BRSD v1   |    Sid   |  7:23  |   33,189  |  5,676 |     52   |  $20$ |
|             | VoxForge |  4:14  |   20,879  |   729  |    111   |       |
|             | Spoltech |  1:35  |   16,776  |   558  |    477   |       |
|             |  LapsBM  |  0:54  |   7,228   |  2,731 |    25    |   10  |
|             |   Total  |  14:07 |   78,072  |  7,772 |    595   |       |
|   BRSD v2   |   CETUC  | 144:39 | 1,040,278 |  3,528 |    50    |  $50$ |
|             |   Total  | 158:47 | 1,118,350 |  8,328 |    695   |       |

## Text

* LapsNews - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/laps-folha-1.0.txt)
    * LapsNews [4] is a text corpus dataset consisting of automatic crawling of the top ten daily Brazilian newspapers available on the Internet in 2010. It was post-processed to convert to lowercase letters, to remove tags and punctuation marks, and to expand numbers and well-know acronyms to the written form, resulting in a corpus with approximately 120k sentences.
* CETENFolha - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/ceten.xml)
    * CETENFolha [5] dataset is a corpus containing over 24 million Brazilian words crawled from the 1994 editions of Folha de São Paulo newspaper, resulting in approximately 1.6M sentences.
* WikiText PT-BR - [Download](http://www02.smt.ufrj.br/~igor.quintanilha/ptwiki-20181125.txt)
    * WikiText PT-BR dataset is a collection of over 8 million sentences extracted from the Wikipedia articles and was built for this work. The dataset is available under Creative Commons Attribution-ShareAlike license. The dataset was pre-processed to remove all punctuation and tags and convert numbers into their written form, to be well suited for ASR models.

|                |            | Words |        |
|----------------|------------|:-----:|-------:|
| Datasets       | #sentences | Total | Unique |
| LapsNews       |    119k    |  2.7M |   66k  |
| CETENFolha     |    1.5M    |  26M  |  214k  |
| WikiText PT-BR |    8.5M    |  194M |  1.1M  |
| **Total**      |    10.2M   |  223M |  1.2M  |


## References

1. V. F. S. Alencar and A. Alcaim, “LSF and LPC - derived features forlarge vocabulary distributed continuous speech recognition in Brazilian Portuguese,” in Asilomar Conference on Signals, Systems and Computers, October 2008, pp. 1237–124;
2. “Falabrasil  -  UFPA”,  [https://github.com/falabrasil/gitlab-resources](https://github.com/falabrasil/gitlab-resources), accessed: 2020-03-19;
3. “Voxforge”, [https://http://www.voxforge.org](https://http://www.voxforge.org), accessed: 2020-03-19;
4. N. Neto, C. Patrick, A. Klautau, and I. Trancoso, “Free tools andresources for brazilian portuguese speech recognition, ”Journal of theBrazilian Computer Society, vol. 17, no. 1, pp. 53–68, November 2011;
5. Linguateca, "CETENFolha", [https://www.linguateca.pt/cetenfolha/index_info.html](https://www.linguateca.pt/cetenfolha/index_info.html), accessed: 2020-03-19.
