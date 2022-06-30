---
title: acm_mirum
{:.no_toc}
layout: default
---

# acm_mirum
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'acm_mirum' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'acm_mirum'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Curator** | [Geoffroy Peeters](mailto:geoffroy.peeters@telecom-paristech.fr) |
| **Annotator,&nbsp;bibtex** |[Peeters2012](bib/Peeters2012.bib) |
| **Annotator,&nbsp;ref_url** | [http://recherche.ircam.fr/anasyn/peeters/pub/2012\_ACMMIRUM/](http://recherche.ircam.fr/anasyn/peeters/pub/2012_ACMMIRUM/) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 2.0 |
| **Curator** | [Graham Percival](mailto:graham@percival-music.ca) |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   1410   |   36.00   |   257.00   |   102.54   |   32.73   |   69.00   |   0.73   |
| [2.0](#20)                                         |   1410   |   37.00   |   257.00   |   102.72   |   32.59   |   69.00   |   0.73   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/acm_mirum_reference_basic_stats.csv "Download data as CSV") [JSON](data/acm_mirum_reference_basic_stats.json "Download data as JSON") [LATEX](data/acm_mirum_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/acm_mirum_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/acm_mirum_reference_dist.csv "Download data as CSV") [JSON](data/acm_mirum_reference_dist.json "Download data as JSON") [LATEX](data/acm_mirum_reference_dist.latex "Download data as LATEX") [PICKLE](data/acm_mirum_reference_dist.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_reference_dist.svg "Open Figure") [PDF](figures/acm_mirum_reference_dist.pdf "Open Figure") [PNG](figures/acm_mirum_reference_dist.png "Open Figure") 

# Estimates for 'acm_mirum'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### boeck2019/multi_task

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2019/multi_task_hjdb

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task_hjdb, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2020/dar

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | https://github.com/superbock/ISMIR2020 |
| **Annotator,&nbsp;bibtex** |[Boeck2020](bib/Boeck2020.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### echonest/version_3_2_1

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 3.2.1 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Echo Nest track analyzer v3.2.1 |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### gkiokas2012/default

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Gkiokas2012 |
| **Annotator,&nbsp;bibtex** |[Gkiokas2012](bib/Gkiokas2012.bib) |

### klapuri2006/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Klapuri 2006 |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### oliveira2010/ibt

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Oliveira 2010 |
| **Annotator,&nbsp;bibtex** |[Oliveira2010](bib/Oliveira2010.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### scheirer1998/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Scheirer 1998 |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

### sun2021/default

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Xiaoheng Sun, Qiqi He, Yongwei Gao, Wei Li. Musical Tempo Estimation Using a Multi-scale Network. in Proc. of the 22nd Int. Society for Music Information Retrieval Conf., Online, 2021 |
| **Annotation&nbsp;Tools** | https://github.com/Qqi-HE/TempoEstimation_MGANet |
| **Annotator,&nbsp;bibtex** |[Sun2021](bib/Sun2021.bib) |

### zplane/auftakt_v3

| Attribute | Value |
| --- | --- |
| **Corpus** | acm_mirum |
| **Version** | 3.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | zplane aufTAKT version 3.0, http://licensing.zplane.de/technology#auftakt |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1410   |   41.96   |   240.00   |   118.09   |   34.59   |   84.00   |   0.72   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   1410   |   39.89   |   206.08   |   107.56   |   28.79   |   72.00   |   0.82   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1410   |   39.64   |   204.80   |   108.48   |   29.73   |   72.00   |   0.79   |
| [boeck2020/dar](#boeck2020dar)                     |   1410   |   48.02   |   237.16   |   109.24   |   32.30   |   73.00   |   0.76   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1410   |   60.80   |   191.41   |   120.01   |   27.50   |   84.00   |   0.87   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   1410   |   45.91   |   197.99   |   108.64   |   30.82   |   72.00   |   0.76   |
| [gkiokas2012/default](#gkiokas2012default)         |   1410   |   44.00   |   218.00   |   107.42   |   30.72   |   73.00   |   0.77   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   1410   |   65.01   |   164.06   |   110.33   |   23.89   |   76.00   |   0.93   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   1410   |   80.00   |   167.00   |   118.42   |   23.87   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   1410   |   50.67   |   156.60   |   102.13   |   22.97   |   72.00   |   0.92   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   1312   |   61.35   |   181.82   |   106.51   |   31.06   |   77.00   |   0.72   |
| [schreiber2014/default](#schreiber2014default)     |   1410   |   56.34   |   160.08   |   99.91   |   22.74   |   68.00   |   0.90   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1410   |   40.72   |   203.92   |   105.72   |   27.80   |   72.00   |   0.83   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1410   |   28.86   |   193.36   |   104.59   |   29.61   |   72.00   |   0.79   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1410   |   41.00   |   204.00   |   111.56   |   31.17   |   74.00   |   0.77   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1410   |   40.00   |   214.00   |   109.67   |   33.17   |   72.00   |   0.75   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1410   |   56.00   |   204.00   |   110.56   |   28.18   |   74.00   |   0.85   |
| [sun2021/default](#sun2021default)                 |   1410   |   47.00   |   240.00   |   110.64   |   32.64   |   73.00   |   0.75   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   1410   |   65.00   |   171.00   |   108.30   |   25.58   |   79.00   |   0.85   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/acm_mirum_estimates_basic_stats.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_basic_stats.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_dist.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of values in tempo interval.

[CSV](data/acm_mirum_estimates_dist.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_dist.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_dist.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_dist.svg "Open Figure") [PDF](figures/acm_mirum_estimates_dist.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.8348__ |   0.9078   |
| [boeck2020/dar](#boeck2020dar)                     |   0.7844   | __0.9085__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7645   |   0.9071   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7631   |   0.9007   |
| [sun2021/default](#sun2021default)                 |   0.7582   |   0.8851   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7511   |   0.8936   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7163   |   0.8972   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.6936   |   0.9000   |
| [schreiber2014/default](#schreiber2014default)     |   0.6922   |   0.8794   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6858   |   0.9000   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6851   |   0.8972   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6766   |   0.8539   |
| [percival2014/stem](#percival2014stem)             |   0.6702   |   0.9000   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6610   |   0.8972   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6461   |   0.8660   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6270   |   0.8865   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6085   |   0.8645   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.5794   |   0.8603   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4957   |   0.7149   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/acm_mirum_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure3"></a>Figure 3: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/acm_mirum_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/acm_mirum_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.9092__ |   0.9872   |
| [boeck2020/dar](#boeck2020dar)                     |   0.8475   | __0.9908__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8291   |   0.9844   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8277   |   0.9794   |
| [sun2021/default](#sun2021default)                 |   0.8206   |   0.9638   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8184   |   0.9730   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7809   |   0.9766   |
| [schreiber2014/default](#schreiber2014default)     |   0.7617   |   0.9603   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.7574   |   0.9773   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.7489   |   0.9738   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.7404   |   0.9780   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.7390   |   0.9291   |
| [percival2014/stem](#percival2014stem)             |   0.7369   |   0.9794   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7270   |   0.9801   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.7021   |   0.9390   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6879   |   0.9688   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6603   |   0.9348   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6305   |   0.9312   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5355   |   0.7723   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/acm_mirum_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/acm_mirum_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/acm_mirum_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (443 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10503810.clip' '105233.clip' '10563001.clip' '10563039.clip' '1071042.clip' '10766976.clip' '10809231.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (432 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563001.clip' '10726039.clip' '10809231.clip' '10875997.clip' '10893272.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (444 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563001.clip' '10726039.clip' '10809231.clip' '10875997.clip' '10893272.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2020/dar](#boeck2020dar) (304 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10503810.clip' '10563039.clip' '1071042.clip' '10726039.clip' '10809231.clip' '10875997.clip' '10893272.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (552 differences):*
'10118334.clip' '10258351.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563001.clip' '10563039.clip' '1071042.clip' '10726076.clip' '1074945.clip' '10809231.clip' ...
[CSV](data/acm_mirum_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (456 differences):*
'10118334.clip' '10258351.clip' '104260.clip' '10503810.clip' '10563001.clip' '10563039.clip' '1074945.clip' '10766976.clip' '10809231.clip' '10893272.clip' '10894070.clip' ...
[CSV](data/acm_mirum_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (478 differences):*
'10118334.clip' '10258351.clip' '10270809.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563001.clip' '10563039.clip' '1074945.clip' '10809231.clip' ...
[CSV](data/acm_mirum_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (526 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '10503810.clip' '105233.clip' '10563039.clip' '1071042.clip' '10726076.clip' ...
[CSV](data/acm_mirum_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (593 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563039.clip' '1071042.clip' '10726058.clip' '10726076.clip' '1074945.clip' ...
[CSV](data/acm_mirum_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (465 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563039.clip' '1071042.clip' '10726076.clip' '10809231.clip' '10893272.clip' ...
[CSV](data/acm_mirum_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (711 differences):*
'10118334.clip' '10258351.clip' '10270809.clip' '10332517.clip' '104186.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '10503810.clip' '105233.clip' ...
[CSV](data/acm_mirum_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (434 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '10503810.clip' '10563039.clip' '1071042.clip' '10726058.clip' '10809231.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (351 differences):*
'10118334.clip' '10258351.clip' '104260.clip' '10443543.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '10894286.clip' '11173645.clip' '11430821.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (233 differences):*
'10118334.clip' '10258351.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '12185327.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (332 differences):*
'10118334.clip' '10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '10503810.clip' '10563001.clip' '10563039.clip' '1071042.clip' '10726058.clip' '10726076.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (334 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10503810.clip' '10563001.clip' '10563039.clip' '1071042.clip' '10726058.clip' '10766976.clip' '10809231.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (400 differences):*
'10118334.clip' '10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '10503810.clip' '10563039.clip' '1071042.clip' '10809231.clip' '10875997.clip' '10893272.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [sun2021/default](#sun2021default) (341 differences):*
'10118334.clip' '10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '10503810.clip' '105233.clip' '10563039.clip' '1071042.clip' '10726039.clip' '10726076.clip' ...
[CSV](data/acm_mirum_estimates_1.0_sun2021_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (499 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10503810.clip' '1071042.clip' '10726032.clip' '10726058.clip' '10726076.clip' '1074945.clip' ...
[CSV](data/acm_mirum_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (366 differences):*
'10258351.clip' '104222.clip' '104260.clip' '105233.clip' '10563001.clip' '1071042.clip' '10766976.clip' '10875997.clip' '10894070.clip' '10894286.clip' '1094919.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (342 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10563001.clip' '10726039.clip' '10875997.clip' '10894070.clip' '10894286.clip' '11116238.clip' '11173645.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (354 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10563001.clip' '10726039.clip' '10875997.clip' '10894070.clip' '10894286.clip' '11116238.clip' '11173645.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2020/dar](#boeck2020dar) (215 differences):*
'10258351.clip' '104222.clip' '104260.clip' '1071042.clip' '10726039.clip' '10875997.clip' '10894070.clip' '10894286.clip' '11173645.clip' '11401306.clip' '11622.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (479 differences):*
'10258351.clip' '104260.clip' '10443543.clip' '10563001.clip' '10563039.clip' '1071042.clip' '10726076.clip' '1074945.clip' '10894070.clip' '10894286.clip' '11030307.clip' ...
[CSV](data/acm_mirum_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (368 differences):*
'10258351.clip' '104260.clip' '10563001.clip' '1074945.clip' '10766976.clip' '10893272.clip' '10894070.clip' '10894286.clip' '11173645.clip' '11409728.clip' '11430821.clip' ...
[CSV](data/acm_mirum_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (385 differences):*
'10258351.clip' '10270809.clip' '104222.clip' '104260.clip' '10443543.clip' '10563001.clip' '1074945.clip' '10894286.clip' '11030307.clip' '11173645.clip' '11471649.clip' ...
[CSV](data/acm_mirum_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (440 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '105233.clip' '10563039.clip' '1071042.clip' '10894070.clip' '10894286.clip' '1108465.clip' ...
[CSV](data/acm_mirum_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (521 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10563039.clip' '1071042.clip' '10726058.clip' '10726076.clip' '1074945.clip' '10894070.clip' ...
[CSV](data/acm_mirum_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (371 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '10563039.clip' '1071042.clip' '10894286.clip' '11030307.clip' '11116238.clip' '11173645.clip' '11554698.clip' ...
[CSV](data/acm_mirum_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (655 differences):*
'10118334.clip' '10258351.clip' '10270809.clip' '10332517.clip' '104186.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '105233.clip' '10563001.clip' ...
[CSV](data/acm_mirum_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (336 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '105009.clip' '1071042.clip' '10726058.clip' '10894286.clip' '11030307.clip' '11116238.clip' '11173645.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (256 differences):*
'10258351.clip' '104260.clip' '10443543.clip' '10894286.clip' '11173645.clip' '11612127.clip' '11622.clip' '1162915.clip' '11812770.clip' '12185327.clip' '1245162.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (128 differences):*
'10258351.clip' '11173645.clip' '11612127.clip' '12185327.clip' '1245162.clip' '12638738.clip' '129570.clip' '13041056.clip' '13086293.clip' '1358509.clip' '1393863.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (241 differences):*
'10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '10563001.clip' '1071042.clip' '10726058.clip' '10726076.clip' '10875997.clip' '10894070.clip' '10894286.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (243 differences):*
'10258351.clip' '104222.clip' '104260.clip' '10563001.clip' '1071042.clip' '10726058.clip' '10766976.clip' '10875997.clip' '10894286.clip' '1094938.clip' '11030307.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (309 differences):*
'10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '1071042.clip' '10875997.clip' '10894070.clip' '10894286.clip' '11173645.clip' '11612127.clip' '11622.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [sun2021/default](#sun2021default) (253 differences):*
'10258351.clip' '10389587.clip' '104222.clip' '104260.clip' '105233.clip' '1071042.clip' '10726039.clip' '10726076.clip' '10875997.clip' '10894070.clip' '10894286.clip' ...
[CSV](data/acm_mirum_estimates_2.0_sun2021_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (420 differences):*
'10118334.clip' '10258351.clip' '104222.clip' '104260.clip' '10443543.clip' '1071042.clip' '10726032.clip' '10726058.clip' '10726076.clip' '1074945.clip' '10894286.clip' ...
[CSV](data/acm_mirum_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 46 items 'correctly' using Accuracy<sub>1</sub>:__
'10258351.clip' '11173645.clip' '12185327.clip' '1245162.clip' '12638738.clip' '129570.clip' '1358509.clip' '1393863.clip' '1433718.clip' '1492191.clip' '14970371.clip' ...
[CSV](data/acm_mirum_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (141 differences):*
'10118334.clip' '104260.clip' '10503810.clip' '105233.clip' '10563039.clip' '10809231.clip' '10893272.clip' '1108465.clip' '11173645.clip' '11430821.clip' '1173974.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (141 differences):*
'10118334.clip' '10503810.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' '12906077.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (145 differences):*
'10118334.clip' '10503810.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' '12906123.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2020/dar](#boeck2020dar) (129 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '1248986.clip' ...
[CSV](data/acm_mirum_estimates_1.0_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (191 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10726076.clip' '10809231.clip' '10893272.clip' '1108465.clip' '11193878.clip' '11430821.clip' '11552767.clip' '1173974.clip' ...
[CSV](data/acm_mirum_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (206 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10766976.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '1173975.clip' '11883189.clip' ...
[CSV](data/acm_mirum_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (145 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' ...
[CSV](data/acm_mirum_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (160 differences):*
'10118334.clip' '105009.clip' '10503810.clip' '105233.clip' '10563039.clip' '10726076.clip' '10809231.clip' '10893272.clip' '1108465.clip' '11430821.clip' '1173974.clip' ...
[CSV](data/acm_mirum_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (197 differences):*
'10118334.clip' '104260.clip' '10503810.clip' '10726058.clip' '10726076.clip' '10809231.clip' '10893272.clip' '1107612.clip' '11095374.clip' '11173645.clip' '11430821.clip' ...
[CSV](data/acm_mirum_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (141 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10726076.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' ...
[CSV](data/acm_mirum_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (402 differences):*
'10118334.clip' '10270809.clip' '104260.clip' '105009.clip' '10503810.clip' '10563001.clip' '10563039.clip' '10726076.clip' '1077416.clip' '10809231.clip' '10875997.clip' ...
[CSV](data/acm_mirum_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (170 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10726058.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (150 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (130 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (131 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10726058.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (140 differences):*
'10118334.clip' '104260.clip' '10503810.clip' '10563039.clip' '10726058.clip' '10766976.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '11612127.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (145 differences):*
'10118334.clip' '10503810.clip' '10563039.clip' '10809231.clip' '10893272.clip' '11173645.clip' '11430821.clip' '1173974.clip' '11883189.clip' '1245162.clip' '12643846.clip' ...
[CSV](data/acm_mirum_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [sun2021/default](#sun2021default) (162 differences):*
'10118334.clip' '104260.clip' '10503810.clip' '105233.clip' '10563039.clip' '10726076.clip' '10809231.clip' '10893272.clip' '1107612.clip' '11173645.clip' '11430821.clip' ...
[CSV](data/acm_mirum_estimates_1.0_sun2021_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (189 differences):*
'10118334.clip' '10503810.clip' '10726032.clip' '10726058.clip' '10726076.clip' '10809231.clip' '10893272.clip' '11119266.clip' '11430821.clip' '1173974.clip' '11883189.clip' ...
[CSV](data/acm_mirum_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (31 differences):*
'104260.clip' '105233.clip' '1108465.clip' '11173645.clip' '1358509.clip' '14600040.clip' '164628.clip' '1827592.clip' '208474.clip' '2252893.clip' '2347473.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (32 differences):*
'11173645.clip' '12906077.clip' '1359069.clip' '1435815.clip' '14600040.clip' '164628.clip' '168497.clip' '168499.clip' '2373182.clip' '2517897.clip' '253654.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (37 differences):*
'11173645.clip' '1245162.clip' '1359069.clip' '1435815.clip' '14600040.clip' '164628.clip' '168497.clip' '168499.clip' '168502.clip' '2373182.clip' '2517897.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2020/dar](#boeck2020dar) (13 differences):*
'11173645.clip' '1245162.clip' '13036093.clip' '164628.clip' '168499.clip' '250576.clip' '3333901.clip' '4326130.clip' '458707.clip' '6018930.clip' '8231796.clip' ...
[CSV](data/acm_mirum_estimates_2.0_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (92 differences):*
'10726076.clip' '1108465.clip' '11193878.clip' '11552767.clip' '12185327.clip' '13036093.clip' '13376370.clip' '1355192.clip' '1359069.clip' '143682.clip' '15416738.clip' ...
[CSV](data/acm_mirum_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (100 differences):*
'10766976.clip' '11173645.clip' '11430821.clip' '1173975.clip' '13036093.clip' '13065657.clip' '13167246.clip' '13376370.clip' '13561397.clip' '1385105.clip' '13851876.clip' ...
[CSV](data/acm_mirum_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (28 differences):*
'11173645.clip' '13036093.clip' '1393863.clip' '15416738.clip' '168499.clip' '1827592.clip' '2252893.clip' '2284109.clip' '2347473.clip' '256907.clip' '281623.clip' ...
[CSV](data/acm_mirum_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (44 differences):*
'105009.clip' '105233.clip' '1108465.clip' '129570.clip' '13376370.clip' '14180121.clip' '14600040.clip' '166285.clip' '168497.clip' '168499.clip' '168502.clip' ...
[CSV](data/acm_mirum_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (97 differences):*
'104260.clip' '10563039.clip' '10726058.clip' '10726076.clip' '1107612.clip' '11095374.clip' '11173645.clip' '12185327.clip' '12643846.clip' '129570.clip' '13036093.clip' ...
[CSV](data/acm_mirum_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (29 differences):*
'11173645.clip' '1245162.clip' '13851876.clip' '14600040.clip' '15416738.clip' '164628.clip' '168499.clip' '1949678.clip' '2232914.clip' '2411992.clip' '282894.clip' ...
[CSV](data/acm_mirum_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (321 differences):*
'10118334.clip' '10270809.clip' '104260.clip' '105009.clip' '10563001.clip' '10726076.clip' '1077416.clip' '10875997.clip' '10893272.clip' '1103942.clip' '1108465.clip' ...
[CSV](data/acm_mirum_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (56 differences):*
'10726058.clip' '11173645.clip' '11612127.clip' '14180121.clip' '1447613.clip' '14600040.clip' '14634350.clip' '15952618.clip' '164628.clip' '168497.clip' '168499.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (38 differences):*
'11173645.clip' '11612127.clip' '1245162.clip' '14180121.clip' '1447613.clip' '14600040.clip' '15952618.clip' '164628.clip' '1827592.clip' '2214125.clip' '2232914.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (18 differences):*
'11173645.clip' '11612127.clip' '1245162.clip' '1447613.clip' '14600040.clip' '164628.clip' '2232914.clip' '2233308.clip' '3188766.clip' '3732728.clip' '4326130.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (22 differences):*
'10726058.clip' '11173645.clip' '11612127.clip' '14600040.clip' '15416738.clip' '164628.clip' '168499.clip' '281623.clip' '282894.clip' '3110264.clip' '3176577.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (29 differences):*
'104260.clip' '10726058.clip' '10766976.clip' '11173645.clip' '14600040.clip' '14634350.clip' '15416738.clip' '164628.clip' '168499.clip' '281623.clip' '3030777.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (33 differences):*
'11173645.clip' '11612127.clip' '1245162.clip' '12937673.clip' '13851876.clip' '14600040.clip' '15416738.clip' '168499.clip' '1827592.clip' '3073826.clip' '3110264.clip' ...
[CSV](data/acm_mirum_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [sun2021/default](#sun2021default) (51 differences):*
'104260.clip' '105233.clip' '10726076.clip' '1107612.clip' '11173645.clip' '12185327.clip' '14180121.clip' '15952618.clip' '168499.clip' '1827592.clip' '2284109.clip' ...
[CSV](data/acm_mirum_estimates_2.0_sun2021_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (86 differences):*
'10726032.clip' '10726058.clip' '10726076.clip' '11119266.clip' '11612127.clip' '1173974.clip' '1245162.clip' '12937673.clip' '13036093.clip' '13376370.clip' '1385105.clip' ...
[CSV](data/acm_mirum_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1783   |   0.5183   | __0.0000__ | __0.0000__ |   0.9574   |   0.3552   | __0.0001__ | __0.0000__ |   0.8385   | __0.0000__ |   0.1410   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0063__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1783   |   1.0000   |   0.1691   | __0.0000__ | __0.0000__ |   0.1649   | __0.0242__ | __0.0000__ | __0.0000__ |   0.0725   | __0.0000__ |   0.7416   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0393__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.5183   |   0.1691   |   1.0000   | __0.0000__ | __0.0000__ |   0.4821   |   0.1093   | __0.0000__ | __0.0000__ |   0.3416   | __0.0000__ |   0.2954   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0051__ | __0.0000__ | __0.0002__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0054__ | __0.0000__ |   0.0566   |   0.0501   | __0.0000__ | __0.0019__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0077__ | __0.0032__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0012__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.9574   |   0.1649   |   0.4821   | __0.0000__ | __0.0000__ |   1.0000   |   0.3904   | __0.0001__ | __0.0000__ |   0.9125   | __0.0000__ |   0.0773   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0055__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3552   | __0.0242__ |   0.1093   | __0.0000__ | __0.0000__ |   0.3904   |   1.0000   | __0.0028__ | __0.0000__ |   0.4306   | __0.0000__ | __0.0057__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0577   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0077__ | __0.0001__ | __0.0028__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2369   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0032__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.8385   |   0.0725   |   0.3416   | __0.0000__ | __0.0000__ |   0.9125   |   0.4306   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0120__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0035__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1410   |   0.7416   |   0.2954   | __0.0000__ | __0.0000__ |   0.0773   | __0.0057__ | __0.0000__ | __0.0000__ | __0.0120__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0871   | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0054__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.3282   |   0.4020   | __0.0003__ |   0.8944   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0566   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3282   | __0.0000__ |   1.0000   |   0.9385   | __0.0000__ |   0.3904   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0501   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4020   | __0.0000__ |   0.9385   |   1.0000   | __0.0000__ |   0.5182   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0005__ | __0.0393__ | __0.0051__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   0.0871   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0002__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8944   | __0.0000__ |   0.3904   |   0.5182   | __0.0002__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0063__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0012__ | __0.0055__ |   0.0577   |   0.2369   | __0.0000__ | __0.0035__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5435   |   1.0000   | __0.0000__ | __0.0000__ |   0.5030   |   0.0680   | __0.0000__ | __0.0000__ |   0.2657   | __0.0000__ |   0.6703   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0057__ | __0.0000__ | __0.0031__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5435   |   1.0000   |   0.1550   | __0.0000__ | __0.0000__ |   0.1900   | __0.0124__ | __0.0000__ | __0.0000__ | __0.0368__ | __0.0000__ |   0.9455   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0401__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   |   0.1550   |   1.0000   | __0.0000__ | __0.0000__ |   0.5411   |   0.0676   | __0.0000__ | __0.0000__ |   0.2295   | __0.0000__ |   0.5692   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0048__ | __0.0000__ | __0.0012__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0350__ | __0.0307__ | __0.0000__ | __0.0028__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ |   0.0727   | __0.0038__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5030   |   0.1900   |   0.5411   | __0.0000__ | __0.0000__ |   1.0000   |   0.2360   | __0.0001__ | __0.0000__ |   0.6490   | __0.0000__ |   0.2143   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0000__ | __0.0172__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0680   | __0.0124__ |   0.0676   | __0.0000__ | __0.0001__ |   0.2360   |   1.0000   | __0.0068__ | __0.0000__ |   0.4541   | __0.0000__ | __0.0084__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2410   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0727   | __0.0001__ | __0.0068__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0899   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.2657   | __0.0368__ |   0.2295   | __0.0000__ | __0.0000__ |   0.6490   |   0.4541   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0210__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0361__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.6703   |   0.9455   |   0.5692   | __0.0000__ | __0.0000__ |   0.2143   | __0.0084__ | __0.0000__ | __0.0000__ | __0.0210__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0234__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2020   |   0.2567   | __0.0007__ |   0.5476   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0350__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2020   | __0.0000__ |   1.0000   |   0.9362   | __0.0000__ |   0.5309   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0307__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2567   | __0.0000__ |   0.9362   |   1.0000   | __0.0000__ |   0.6556   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0057__ | __0.0401__ | __0.0048__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0234__ | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ | __0.0028__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5476   | __0.0000__ |   0.5309   |   0.6556   | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0031__ | __0.0000__ | __0.0012__ | __0.0000__ | __0.0025__ | __0.0172__ |   0.2410   |   0.0899   | __0.0000__ | __0.0361__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   0.4799   | __0.0039__ | __0.0000__ | __0.0000__ |   0.7552   |   0.1175   | __0.0000__ |   0.8804   | __0.0000__ | __0.0026__ |   0.3817   | __0.0470__ |   0.2110   |   0.8830   |   0.8804   | __0.0105__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   1.0000   |   1.0000   |   0.2266   | __0.0005__ | __0.0000__ | __0.0000__ |   0.6177   |   0.1550   | __0.0000__ |   0.7359   | __0.0000__ | __0.0012__ |   0.4709   | __0.0243__ |   0.1102   |   0.7428   |   1.0000   | __0.0127__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.4799   |   0.2266   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2327   |   0.4500   | __0.0000__ |   0.2800   | __0.0000__ | __0.0145__ |   1.0000   | __0.0019__ | __0.0201__ |   0.2800   |   0.6718   |   0.0925   | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0039__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0081__ | __0.0000__ | __0.0000__ | __0.0025__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3018   |   0.0784   | __0.0025__ | __0.0005__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5625   | __0.0000__ | __0.0000__ |   0.7139   | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.6612   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5625   |   1.0000   | __0.0000__ | __0.0000__ |   0.8467   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1980   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7552   |   0.6177   |   0.2327   | __0.0081__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0365__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1539   |   0.1325   |   0.3449   |   1.0000   |   0.4731   | __0.0004__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.1175   |   0.1550   |   0.4500   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |   1.0000   | __0.0000__ | __0.0444__ | __0.0000__ |   0.1550   |   0.4966   | __0.0003__ | __0.0009__ |   0.0627   |   0.1690   |   0.4011   | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7139   |   0.8467   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3049   |
| [percival2014/stem](#percival2014stem)             |   0.8804   |   0.7359   |   0.2800   | __0.0025__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0444__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0004__ |   0.2221   |   0.0522   |   0.2478   |   1.0000   |   0.5966   | __0.0026__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0026__ | __0.0012__ | __0.0145__ | __0.0000__ | __0.0013__ | __0.0000__ | __0.0000__ |   0.1550   | __0.0000__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   0.5758   | __0.0002__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3817   |   0.4709   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1539   |   0.4966   | __0.0000__ |   0.2221   | __0.0000__ | __0.0009__ |   1.0000   | __0.0000__ | __0.0090__ |   0.1877   |   0.4996   |   0.0854   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0470__ | __0.0243__ | __0.0019__ |   0.3018   | __0.0000__ | __0.0000__ |   0.1325   | __0.0003__ | __0.0000__ |   0.0522   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5235   | __0.0433__ | __0.0107__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2110   |   0.1102   | __0.0201__ |   0.0784   | __0.0000__ | __0.0000__ |   0.3449   | __0.0009__ | __0.0000__ |   0.2478   | __0.0000__ | __0.0000__ | __0.0090__ |   0.5235   |   1.0000   |   0.1892   |   0.0614   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8830   |   0.7428   |   0.2800   | __0.0025__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0627   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1877   | __0.0433__ |   0.1892   |   1.0000   |   0.6076   | __0.0026__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8804   |   1.0000   |   0.6718   | __0.0005__ | __0.0000__ | __0.0000__ |   0.4731   |   0.1690   | __0.0000__ |   0.5966   | __0.0000__ | __0.0014__ |   0.4996   | __0.0107__ |   0.0614   |   0.6076   |   1.0000   | __0.0133__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0105__ | __0.0127__ |   0.0925   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0004__ |   0.4011   | __0.0000__ | __0.0026__ | __0.0000__ |   0.5758   |   0.0854   | __0.0000__ | __0.0000__ | __0.0026__ | __0.0133__ |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6612   |   0.1980   | __0.0000__ | __0.0000__ |   0.3049   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.8918   |   0.6936   |   0.0884   | __0.0000__ | __0.0000__ |   0.6778   | __0.0327__ | __0.0000__ |   0.8918   | __0.0000__ | __0.0008__ |   0.2717   |   0.1263   |   0.2116   |   1.0000   |   0.6655   | __0.0154__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8918   |   1.0000   |   0.3437   |   0.0501   | __0.0000__ | __0.0000__ |   0.6516   | __0.0248__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ |   0.2221   |   0.0614   |   0.1325   |   1.0000   |   0.6655   | __0.0170__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6936   |   0.3437   |   1.0000   | __0.0070__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0919   | __0.0000__ |   0.6587   | __0.0000__ | __0.0013__ |   0.5515   | __0.0135__ | __0.0385__ |   0.5601   |   0.8918   |   0.0647   | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.0884   |   0.0501   | __0.0070__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0090__ | __0.0000__ | __0.0000__ |   0.0501   | __0.0000__ | __0.0000__ | __0.0008__ |   1.0000   |   0.8555   |   0.0895   | __0.0139__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2699   | __0.0000__ | __0.0041__ |   0.6634   | __0.0000__ | __0.0000__ |   0.0783   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0176__ |   0.9312   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2699   |   1.0000   | __0.0000__ | __0.0000__ |   0.4517   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1219   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6778   |   0.6516   |   1.0000   | __0.0090__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0722   | __0.0000__ |   0.6516   | __0.0000__ | __0.0003__ |   0.5515   | __0.0275__ | __0.0288__ |   0.5424   |   1.0000   | __0.0270__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0327__ | __0.0248__ |   0.0919   | __0.0000__ | __0.0041__ | __0.0000__ |   0.0722   |   1.0000   | __0.0002__ | __0.0163__ | __0.0000__ |   0.2530   |   0.2203   | __0.0000__ | __0.0001__ | __0.0225__ |   0.0674   |   0.9020   | __0.0008__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6634   |   0.4517   | __0.0000__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0048__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ |   0.4655   |
| [percival2014/stem](#percival2014stem)             |   0.8918   |   1.0000   |   0.6587   |   0.0501   | __0.0000__ | __0.0000__ |   0.6516   | __0.0163__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ |   0.2430   |   0.0708   |   0.1742   |   1.0000   |   0.6440   | __0.0125__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0008__ | __0.0001__ | __0.0013__ | __0.0000__ |   0.0783   | __0.0001__ | __0.0003__ |   0.2530   | __0.0048__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ |   0.3662   | __0.0204__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2717   |   0.2221   |   0.5515   | __0.0008__ | __0.0002__ | __0.0000__ |   0.5515   |   0.2203   | __0.0000__ |   0.2430   | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0034__ |   0.1641   |   0.5327   |   0.1550   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1263   |   0.0614   | __0.0135__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0275__ | __0.0000__ | __0.0000__ |   0.0708   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   |   0.0987   | __0.0201__ | __0.0001__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2116   |   0.1325   | __0.0385__ |   0.8555   | __0.0000__ | __0.0000__ | __0.0288__ | __0.0001__ | __0.0000__ |   0.1742   | __0.0000__ | __0.0000__ | __0.0034__ |   1.0000   |   1.0000   |   0.1221   | __0.0201__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   1.0000   |   0.5601   |   0.0895   | __0.0000__ | __0.0000__ |   0.5424   | __0.0225__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1641   |   0.0987   |   0.1221   |   1.0000   |   0.5114   | __0.0054__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6655   |   0.6655   |   0.8918   | __0.0139__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0674   | __0.0000__ |   0.6440   | __0.0000__ | __0.0005__ |   0.5327   | __0.0201__ | __0.0201__ |   0.5114   |   1.0000   | __0.0270__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0154__ | __0.0170__ |   0.0647   | __0.0000__ | __0.0176__ | __0.0000__ | __0.0270__ |   0.9020   | __0.0005__ | __0.0125__ | __0.0000__ |   0.3662   |   0.1550   | __0.0001__ | __0.0000__ | __0.0054__ | __0.0270__ |   1.0000   | __0.0053__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9312   |   0.1219   | __0.0000__ | __0.0008__ |   0.4655   | __0.0000__ | __0.0000__ | __0.0204__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0053__ |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure13"></a>Figure 13: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0430   | __0.3048__ |   -0.0044   |   0.0699   |
| [sun2021/default](#sun2021default)                 |   0.1207   |   0.3878   |   -0.0172   |   0.0879   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1386   |   0.3923   |   -0.0046   |   0.0729   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1026   |   0.3999   |   -0.0031   | __0.0683__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1050   |   0.4075   |   -0.0064   |   0.0772   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0678   |   0.4191   |   -0.0091   |   0.0859   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1355   |   0.4572   |   -0.0088   |   0.0824   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.0985   |   0.4642   |   -0.0089   |   0.1044   |
| [schreiber2014/default](#schreiber2014default)     | __-0.0013__ |   0.4664   |   -0.0159   |   0.0956   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0907   |   0.4862   |   -0.0033   |   0.0793   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0997   |   0.4925   | __-0.0025__ |   0.0819   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2135   |   0.4983   |   -0.0046   |   0.0765   |
| [percival2014/stem](#percival2014stem)             |   0.0307   |   0.5103   |   -0.0040   |   0.0751   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.1116   |   0.5119   |   -0.0136   |   0.1059   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0821   |   0.5199   |   -0.0076   |   0.0831   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2614   |   0.5321   |   0.0221   |   0.0914   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.2509   |   0.5421   |   -0.0066   |   0.0984   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.1444   |   0.5490   |   -0.0051   |   0.0839   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.0736   |   0.5693   |   0.0302   |   0.1589   |

<a name="table9"></a>Table 9: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/acm_mirum_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure15"></a>Figure 15: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure16"></a>Figure 16: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0394   | __0.2958__ |   -0.0044   |   0.0384   |
| [sun2021/default](#sun2021default)                 |   0.1172   |   0.3845   |   -0.0187   |   0.0664   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1350   |   0.3886   |   -0.0046   |   0.0441   |
| [boeck2020/dar](#boeck2020dar)                     |   0.0991   |   0.3962   |   -0.0041   | __0.0368__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1014   |   0.4024   |   -0.0064   |   0.0517   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0643   |   0.4141   |   -0.0091   |   0.0629   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1320   |   0.4518   |   -0.0084   |   0.0590   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.0950   |   0.4614   |   -0.0132   |   0.0875   |
| [schreiber2014/default](#schreiber2014default)     | __-0.0048__ |   0.4615   |   -0.0159   |   0.0760   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0872   |   0.4829   |   -0.0050   |   0.0561   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0962   |   0.4887   |   -0.0056   |   0.0616   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2100   |   0.4957   |   -0.0049   |   0.0487   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.1080   |   0.5032   |   -0.0183   |   0.0921   |
| [percival2014/stem](#percival2014stem)             |   0.0271   |   0.5040   | __-0.0036__ |   0.0510   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0786   |   0.5136   |   -0.0074   |   0.0581   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2578   |   0.5266   |   0.0229   |   0.0714   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.2473   |   0.5368   |   -0.0074   |   0.0815   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.1409   |   0.5433   |   -0.0053   |   0.0580   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.0697   |   0.5681   |   0.0306   |   0.1516   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/acm_mirum_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure17"></a>Figure 17: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure18"></a>Figure 18: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0067__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.1105   |   0.2844   | __0.0000__ |   0.5284   |   0.5252   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3366   | __0.0000__ | __0.0314__ | __0.0000__ | __0.0000__ |   0.2300   | __0.0001__ | __0.0111__ |   0.0805   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.1105   |   1.0000   |   0.7938   | __0.0000__ |   0.9264   |   0.1975   | __0.0003__ | __0.0000__ | __0.0000__ |   0.0873   | __0.0000__ | __0.0042__ | __0.0000__ | __0.0006__ |   0.6574   | __0.0014__ |   0.0752   |   0.3264   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ |   0.2844   |   0.7938   |   1.0000   | __0.0000__ |   0.7256   |   0.1375   | __0.0018__ | __0.0000__ | __0.0000__ |   0.0573   | __0.0000__ | __0.0006__ | __0.0000__ | __0.0001__ |   0.8179   | __0.0018__ | __0.0322__ |   0.4812   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.5284   |   0.9264   |   0.7256   | __0.0000__ |   1.0000   |   0.2104   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0453__ | __0.0000__ | __0.0064__ | __0.0000__ | __0.0005__ |   0.5907   | __0.0018__ |   0.0603   |   0.3123   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ |   0.5252   |   0.1975   |   0.1375   | __0.0000__ |   0.2104   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2579   | __0.0000__ |   0.2650   | __0.0026__ | __0.0000__ |   0.0860   | __0.0000__ | __0.0032__ | __0.0163__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0003__ | __0.0018__ | __0.0000__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6424   | __0.0045__ |   0.4080   |   0.0845   | __0.0025__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0067__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0062__ | __0.0004__ | __0.0011__ |   0.3013   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.3366   |   0.0873   |   0.0573   | __0.0000__ | __0.0453__ |   0.2579   | __0.0000__ | __0.0000__ | __0.0062__ |   1.0000   | __0.0000__ |   0.9128   | __0.0463__ | __0.0000__ | __0.0324__ | __0.0000__ | __0.0017__ | __0.0074__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0314__ | __0.0042__ | __0.0006__ | __0.0000__ | __0.0064__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0011__ |   0.9128   | __0.0000__ |   1.0000   | __0.0044__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0026__ | __0.0000__ | __0.0000__ |   0.3013   | __0.0463__ | __0.0000__ | __0.0044__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0006__ | __0.0001__ | __0.0000__ | __0.0005__ | __0.0000__ |   0.6424   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ |   0.7457   |   0.0526   | __0.0258__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.2300   |   0.6574   |   0.8179   | __0.0000__ |   0.5907   |   0.0860   | __0.0045__ | __0.0000__ | __0.0000__ | __0.0324__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0050__ |   0.1092   |   0.6207   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0001__ | __0.0014__ | __0.0018__ | __0.0000__ | __0.0018__ | __0.0000__ |   0.4080   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7457   | __0.0050__ |   1.0000   |   0.1645   | __0.0341__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0111__ |   0.0752   | __0.0322__ | __0.0000__ |   0.0603   | __0.0032__ |   0.0845   | __0.0000__ | __0.0000__ | __0.0017__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0526   |   0.1092   |   0.1645   |   1.0000   |   0.4676   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.0805   |   0.3264   |   0.4812   | __0.0000__ |   0.3123   | __0.0163__ | __0.0025__ | __0.0000__ | __0.0000__ | __0.0074__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0258__ |   0.6207   | __0.0341__ |   0.4676   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0067__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.1105   |   0.2844   | __0.0000__ |   0.5284   |   0.5252   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3366   | __0.0000__ | __0.0314__ | __0.0000__ | __0.0000__ |   0.2300   | __0.0001__ | __0.0111__ |   0.0805   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.1105   |   1.0000   |   0.7938   | __0.0000__ |   0.9264   |   0.1975   | __0.0003__ | __0.0000__ | __0.0000__ |   0.0873   | __0.0000__ | __0.0042__ | __0.0000__ | __0.0006__ |   0.6574   | __0.0014__ |   0.0752   |   0.3264   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ |   0.2844   |   0.7938   |   1.0000   | __0.0000__ |   0.7256   |   0.1375   | __0.0018__ | __0.0000__ | __0.0000__ |   0.0573   | __0.0000__ | __0.0006__ | __0.0000__ | __0.0001__ |   0.8179   | __0.0018__ | __0.0322__ |   0.4812   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.5284   |   0.9264   |   0.7256   | __0.0000__ |   1.0000   |   0.2104   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0453__ | __0.0000__ | __0.0064__ | __0.0000__ | __0.0005__ |   0.5907   | __0.0018__ |   0.0603   |   0.3123   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ |   0.5252   |   0.1975   |   0.1375   | __0.0000__ |   0.2104   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2579   | __0.0000__ |   0.2650   | __0.0026__ | __0.0000__ |   0.0860   | __0.0000__ | __0.0032__ | __0.0163__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0003__ | __0.0018__ | __0.0000__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6424   | __0.0045__ |   0.4080   |   0.0845   | __0.0025__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0067__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0062__ | __0.0004__ | __0.0011__ |   0.3013   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.3366   |   0.0873   |   0.0573   | __0.0000__ | __0.0453__ |   0.2579   | __0.0000__ | __0.0000__ | __0.0062__ |   1.0000   | __0.0000__ |   0.9128   | __0.0463__ | __0.0000__ | __0.0324__ | __0.0000__ | __0.0017__ | __0.0074__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0314__ | __0.0042__ | __0.0006__ | __0.0000__ | __0.0064__ |   0.2650   | __0.0000__ | __0.0000__ | __0.0011__ |   0.9128   | __0.0000__ |   1.0000   | __0.0044__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0026__ | __0.0000__ | __0.0000__ |   0.3013   | __0.0463__ | __0.0000__ | __0.0044__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0006__ | __0.0001__ | __0.0000__ | __0.0005__ | __0.0000__ |   0.6424   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ |   0.7457   |   0.0526   | __0.0258__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.2300   |   0.6574   |   0.8179   | __0.0000__ |   0.5907   |   0.0860   | __0.0045__ | __0.0000__ | __0.0000__ | __0.0324__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0050__ |   0.1092   |   0.6207   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0001__ | __0.0014__ | __0.0018__ | __0.0000__ | __0.0018__ | __0.0000__ |   0.4080   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7457   | __0.0050__ |   1.0000   |   0.1645   | __0.0341__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0111__ |   0.0752   | __0.0322__ | __0.0000__ |   0.0603   | __0.0032__ |   0.0845   | __0.0000__ | __0.0000__ | __0.0017__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0526   |   0.1092   |   0.1645   |   1.0000   |   0.4676   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.0805   |   0.3264   |   0.4812   | __0.0000__ |   0.3123   | __0.0163__ | __0.0025__ | __0.0000__ | __0.0000__ | __0.0074__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0258__ |   0.6207   | __0.0341__ |   0.4676   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.9315   |   0.6956   |   0.5957   | __0.0000__ | __0.0006__ |   0.1088   |   0.8152   |   0.2494   |   0.4725   | __0.0000__ | __0.0000__ | __0.0129__ |   0.7336   |   0.8650   |   0.3635   | __0.0205__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9315   |   1.0000   |   0.5629   |   0.5151   | __0.0000__ | __0.0007__ |   0.1332   |   0.8874   |   0.3180   |   0.3772   | __0.0000__ | __0.0000__ | __0.0307__ |   0.6790   |   0.7758   |   0.3699   | __0.0460__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6956   |   0.5629   |   1.0000   |   0.3323   | __0.0000__ | __0.0023__ |   0.3173   |   0.8820   |   0.4520   |   0.2961   | __0.0000__ | __0.0000__ |   0.0695   |   0.4587   |   0.5392   |   0.6340   |   0.1217   | __0.0000__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.5957   |   0.5151   |   0.3323   |   1.0000   | __0.0000__ | __0.0001__ | __0.0315__ |   0.4663   |   0.1493   |   0.7277   | __0.0000__ | __0.0000__ | __0.0026__ |   0.7923   |   0.6600   |   0.0763   | __0.0022__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0848   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0006__ | __0.0007__ | __0.0023__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0142__ | __0.0010__ | __0.0400__ | __0.0001__ | __0.0000__ |   0.2504   |   0.0863   | __0.0002__ | __0.0004__ | __0.0039__ | __0.0496__ | __0.0117__ |   0.0604   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1088   |   0.1332   |   0.3173   | __0.0315__ | __0.0000__ | __0.0142__ |   1.0000   |   0.2318   |   0.9969   | __0.0134__ | __0.0000__ | __0.0000__ |   0.3207   | __0.0473__ | __0.0383__ |   0.4655   |   0.5170   | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.8152   |   0.8874   |   0.8820   |   0.4663   | __0.0000__ | __0.0010__ |   0.2318   |   1.0000   |   0.3003   |   0.3771   | __0.0000__ | __0.0000__ | __0.0423__ |   0.6079   |   0.6827   |   0.5557   |   0.1001   | __0.0000__ | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.2494   |   0.3180   |   0.4520   |   0.1493   | __0.0000__ | __0.0400__ |   0.9969   |   0.3003   |   1.0000   |   0.1095   | __0.0000__ | __0.0003__ |   0.4727   |   0.1855   |   0.2286   |   0.6675   |   0.6843   | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             |   0.4725   |   0.3772   |   0.2961   |   0.7277   | __0.0000__ | __0.0001__ | __0.0134__ |   0.3771   |   0.1095   |   1.0000   | __0.0000__ | __0.0000__ | __0.0021__ |   0.5542   |   0.5121   |   0.0729   | __0.0020__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0848   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2504   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0859   |   0.2549   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0129__ | __0.0307__ |   0.0695   | __0.0026__ | __0.0000__ |   0.0863   |   0.3207   | __0.0423__ |   0.4727   | __0.0021__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0011__ | __0.0076__ |   0.1227   |   0.6926   | __0.0000__ | __0.0001__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7336   |   0.6790   |   0.4587   |   0.7923   | __0.0000__ | __0.0002__ | __0.0473__ |   0.6079   |   0.1855   |   0.5542   | __0.0000__ | __0.0000__ | __0.0011__ |   1.0000   |   0.8536   |   0.1151   | __0.0064__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8650   |   0.7758   |   0.5392   |   0.6600   | __0.0000__ | __0.0004__ | __0.0383__ |   0.6827   |   0.2286   |   0.5121   | __0.0000__ | __0.0000__ | __0.0076__ |   0.8536   |   1.0000   |   0.0896   | __0.0112__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3635   |   0.3699   |   0.6340   |   0.0763   | __0.0000__ | __0.0039__ |   0.4655   |   0.5557   |   0.6675   |   0.0729   | __0.0000__ | __0.0000__ |   0.1227   |   0.1151   |   0.0896   |   1.0000   |   0.1878   | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0205__ | __0.0460__ |   0.1217   | __0.0022__ | __0.0000__ | __0.0496__ |   0.5170   |   0.1001   |   0.6843   | __0.0020__ | __0.0000__ | __0.0000__ |   0.6926   | __0.0064__ | __0.0112__ |   0.1878   |   1.0000   | __0.0000__ | __0.0001__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0117__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0859   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.8738   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0604   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.2549   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.8738   |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.4684   |   0.2678   |   0.3061   | __0.0000__ |   0.0955   |   0.0925   |   0.7844   |   0.4103   |   0.7647   | __0.0000__ | __0.0000__ | __0.0088__ |   0.8997   |   0.9845   |   0.2850   | __0.0134__ | __0.0000__ | __0.0008__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.4684   |   1.0000   |   0.4164   |   0.8994   | __0.0000__ | __0.0245__ | __0.0201__ |   0.3981   |   0.2038   |   0.6498   | __0.0000__ | __0.0000__ | __0.0030__ |   0.4887   |   0.3943   |   0.0562   | __0.0041__ | __0.0000__ | __0.0001__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2678   |   0.4164   |   1.0000   |   0.6782   | __0.0000__ | __0.0120__ | __0.0132__ |   0.2353   |   0.1099   |   0.3874   | __0.0000__ | __0.0000__ | __0.0015__ |   0.2814   |   0.2079   | __0.0269__ | __0.0018__ | __0.0000__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.3061   |   0.8994   |   0.6782   |   1.0000   | __0.0000__ | __0.0236__ | __0.0102__ |   0.2720   |   0.1669   |   0.4681   | __0.0000__ | __0.0000__ | __0.0003__ |   0.2214   |   0.1960   | __0.0135__ | __0.0003__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0808   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.0955   | __0.0245__ | __0.0120__ | __0.0236__ | __0.0000__ |   1.0000   |   0.6050   |   0.1602   |   0.4190   |   0.0627   | __0.0000__ | __0.0096__ |   0.9496   |   0.0847   |   0.0942   |   0.3147   |   0.9695   | __0.0008__ |   0.1218   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0925   | __0.0201__ | __0.0132__ | __0.0102__ | __0.0000__ |   0.6050   |   1.0000   |   0.1797   |   0.6699   | __0.0363__ | __0.0000__ | __0.0000__ |   0.4085   |   0.0688   |   0.0635   |   0.4786   |   0.3920   | __0.0000__ | __0.0246__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7844   |   0.3981   |   0.2353   |   0.2720   | __0.0000__ |   0.1602   |   0.1797   |   1.0000   |   0.4953   |   0.6075   | __0.0000__ | __0.0000__ |   0.0541   |   0.7114   |   0.7863   |   0.5354   |   0.0617   | __0.0000__ | __0.0013__ |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4103   |   0.2038   |   0.1099   |   0.1669   | __0.0000__ |   0.4190   |   0.6699   |   0.4953   |   1.0000   |   0.3200   | __0.0000__ | __0.0001__ |   0.3091   |   0.3850   |   0.4419   |   0.9495   |   0.3551   | __0.0000__ | __0.0104__ |
| [percival2014/stem](#percival2014stem)             |   0.7647   |   0.6498   |   0.3874   |   0.4681   | __0.0000__ |   0.0627   | __0.0363__ |   0.6075   |   0.3200   |   1.0000   | __0.0000__ | __0.0000__ | __0.0058__ |   0.7999   |   0.6924   |   0.1094   | __0.0023__ | __0.0000__ | __0.0001__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0808   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0096__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.4677   |   0.3381   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0088__ | __0.0030__ | __0.0015__ | __0.0003__ | __0.0000__ |   0.9496   |   0.4085   |   0.0541   |   0.3091   | __0.0058__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0011__ | __0.0076__ |   0.1227   |   0.8864   | __0.0000__ |   0.0667   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8997   |   0.4887   |   0.2814   |   0.2214   | __0.0000__ |   0.0847   |   0.0688   |   0.7114   |   0.3850   |   0.7999   | __0.0000__ | __0.0000__ | __0.0011__ |   1.0000   |   0.8536   |   0.1151   | __0.0077__ | __0.0000__ | __0.0004__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9845   |   0.3943   |   0.2079   |   0.1960   | __0.0000__ |   0.0942   |   0.0635   |   0.7863   |   0.4419   |   0.6924   | __0.0000__ | __0.0000__ | __0.0076__ |   0.8536   |   1.0000   |   0.0896   | __0.0079__ | __0.0000__ | __0.0005__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2850   |   0.0562   | __0.0269__ | __0.0135__ | __0.0000__ |   0.3147   |   0.4786   |   0.5354   |   0.9495   |   0.1094   | __0.0000__ | __0.0000__ |   0.1227   |   0.1151   |   0.0896   |   1.0000   |   0.1333   | __0.0000__ | __0.0052__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0134__ | __0.0041__ | __0.0018__ | __0.0003__ | __0.0000__ |   0.9695   |   0.3920   |   0.0617   |   0.3551   | __0.0023__ | __0.0000__ | __0.0002__ |   0.8864   | __0.0077__ | __0.0079__ |   0.1333   |   1.0000   | __0.0000__ |   0.0696   |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4677   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1541   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0008__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1218   | __0.0246__ | __0.0013__ | __0.0104__ | __0.0001__ | __0.0000__ |   0.3381   |   0.0667   | __0.0004__ | __0.0005__ | __0.0052__ |   0.0696   |   0.1541   |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure24"></a>Figure 24: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure25"></a>Figure 25: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure26"></a>Figure 26: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.1109__ | __0.2871__ | __0.0262__ |   0.0650   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1758   |   0.3735   |   0.0264   | __0.0631__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1862   |   0.3721   |   0.0271   |   0.0679   |
| [sun2021/default](#sun2021default)                 |   0.1870   |   0.3605   |   0.0379   |   0.0812   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1882   |   0.3763   |   0.0290   |   0.0718   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1949   |   0.3772   |   0.0322   |   0.0801   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2357   |   0.4145   |   0.0307   |   0.0770   |
| [schreiber2014/default](#schreiber2014default)     |   0.2415   |   0.3990   |   0.0366   |   0.0897   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2461   |   0.4057   |   0.0427   |   0.0957   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2569   |   0.4227   |   0.0304   |   0.0733   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2643   |   0.4273   |   0.0313   |   0.0757   |
| [percival2014/stem](#percival2014stem)             |   0.2764   |   0.4300   |   0.0285   |   0.0697   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2859   |   0.4606   |   0.0310   |   0.0701   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2877   |   0.4407   |   0.0309   |   0.0775   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2922   |   0.4349   |   0.0424   |   0.0980   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3268   |   0.4642   |   0.0329   |   0.0773   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3488   |   0.4793   |   0.0440   |   0.0831   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3613   |   0.4461   |   0.0804   |   0.1403   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3671   |   0.4712   |   0.0424   |   0.0890   |

<a name="table15"></a>Table 15: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/acm_mirum_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/acm_mirum_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure27"></a>Figure 27: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure28"></a>Figure 28: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0957__ | __0.2826__ | __0.0128__ |   0.0365   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1640   |   0.3740   |   0.0131   | __0.0347__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1727   |   0.3734   |   0.0136   |   0.0422   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1748   |   0.3764   |   0.0159   |   0.0497   |
| [sun2021/default](#sun2021default)                 |   0.1750   |   0.3618   |   0.0252   |   0.0642   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1808   |   0.3780   |   0.0188   |   0.0607   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2221   |   0.4151   |   0.0175   |   0.0570   |
| [schreiber2014/default](#schreiber2014default)     |   0.2275   |   0.4015   |   0.0233   |   0.0740   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2342   |   0.4087   |   0.0302   |   0.0832   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2450   |   0.4251   |   0.0176   |   0.0535   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2523   |   0.4295   |   0.0191   |   0.0588   |
| [percival2014/stem](#percival2014stem)             |   0.2623   |   0.4313   |   0.0158   |   0.0486   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2745   |   0.4411   |   0.0170   |   0.0560   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2746   |   0.4631   |   0.0176   |   0.0457   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2801   |   0.4318   |   0.0311   |   0.0886   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3141   |   0.4651   |   0.0188   |   0.0552   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3384   |   0.4789   |   0.0325   |   0.0676   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3552   |   0.4488   |   0.0708   |   0.1375   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3562   |   0.4717   |   0.0307   |   0.0759   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/acm_mirum_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/acm_mirum_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/acm_mirum_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/acm_mirum_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure29"></a>Figure 29: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure30"></a>Figure 30: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/acm_mirum_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0161__ |   0.0688   | __0.0000__ | __0.0000__ | __0.0022__ |   0.9949   | __0.0035__ | __0.0000__ |   0.3908   | __0.0000__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6914   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0161__ |   1.0000   |   0.1903   | __0.0000__ | __0.0000__ |   0.3717   | __0.0260__ | __0.0000__ | __0.0000__ |   0.1168   | __0.0000__ |   0.0980   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0359__ | __0.0000__ | __0.0025__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0688   |   0.1903   |   1.0000   | __0.0000__ | __0.0000__ |   0.1451   |   0.0941   | __0.0000__ | __0.0000__ |   0.3994   | __0.0000__ | __0.0281__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0000__ | __0.0188__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0954   | __0.0000__ |   0.3469   |   0.2855   | __0.0000__ |   0.1860   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0127__ |   0.0552   | __0.0000__ |   0.3032   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0022__ |   0.3717   |   0.1451   | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0222__ | __0.0000__ |   0.5738   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2949   | __0.0000__ | __0.0003__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.9949   | __0.0260__ |   0.0941   | __0.0000__ | __0.0000__ | __0.0015__ |   1.0000   | __0.0017__ | __0.0000__ |   0.2922   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6477   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0035__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0017__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0552   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8445   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.3908   |   0.1168   |   0.3994   | __0.0000__ | __0.0000__ | __0.0222__ |   0.2922   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.1000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3032   | __0.0000__ | __0.0000__ | __0.0018__ |   0.8445   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0008__ |   0.0980   | __0.0281__ | __0.0000__ | __0.0000__ |   0.5738   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6058   | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0954   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.4215   |   0.5511   | __0.0001__ |   0.5775   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.3469   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4215   | __0.0000__ |   1.0000   |   0.8258   | __0.0000__ |   0.7965   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2855   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5511   | __0.0000__ |   0.8258   |   1.0000   | __0.0000__ |   0.9785   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0359__ | __0.0063__ | __0.0000__ | __0.0000__ |   0.2949   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.6058   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ |   0.1860   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5775   | __0.0000__ |   0.7965   |   0.9785   | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6914   | __0.0025__ | __0.0188__ | __0.0000__ | __0.0000__ | __0.0003__ |   0.6477   | __0.0016__ | __0.0000__ |   0.1000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0164__ |   0.0738   | __0.0000__ | __0.0000__ | __0.0022__ |   0.8944   | __0.0022__ | __0.0000__ |   0.5050   | __0.0000__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6397   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0164__ |   1.0000   |   0.1764   | __0.0000__ | __0.0000__ |   0.3636   | __0.0179__ | __0.0000__ | __0.0000__ |   0.0723   | __0.0000__ |   0.1407   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0497__ | __0.0000__ | __0.0019__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0738   |   0.1764   |   1.0000   | __0.0000__ | __0.0000__ |   0.1351   |   0.0728   | __0.0000__ | __0.0000__ |   0.3027   | __0.0000__ | __0.0410__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0088__ | __0.0000__ | __0.0167__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0555   | __0.0000__ |   0.2548   |   0.2104   | __0.0000__ |   0.1759   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0221__ | __0.0469__ | __0.0000__ |   0.4824   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0022__ |   0.3636   |   0.1351   | __0.0000__ | __0.0000__ |   1.0000   | __0.0008__ | __0.0000__ | __0.0000__ | __0.0122__ | __0.0000__ |   0.6968   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3647   | __0.0000__ | __0.0002__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8944   | __0.0179__ |   0.0728   | __0.0000__ | __0.0000__ | __0.0008__ |   1.0000   | __0.0017__ | __0.0000__ |   0.3238   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7065   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0022__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0221__ | __0.0000__ | __0.0017__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0084__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0012__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0469__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.5590   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.5050   |   0.0723   |   0.3027   | __0.0000__ | __0.0000__ | __0.0122__ |   0.3238   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.1391   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4824   | __0.0000__ | __0.0000__ | __0.0084__ |   0.5590   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0014__ |   0.1407   | __0.0410__ | __0.0000__ | __0.0000__ |   0.6968   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5818   | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0555   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.3870   |   0.5129   | __0.0001__ |   0.4431   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2548   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3870   | __0.0000__ |   1.0000   |   0.8220   | __0.0000__ |   0.9280   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2104   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5129   | __0.0000__ |   0.8220   |   1.0000   | __0.0000__ |   0.8928   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0497__ | __0.0088__ | __0.0000__ | __0.0000__ |   0.3647   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.5818   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0000__ |   0.1759   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4431   | __0.0000__ |   0.9280   |   0.8928   | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6397   | __0.0019__ | __0.0167__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.7065   | __0.0012__ | __0.0000__ |   0.1391   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.9937   |   0.4098   | __0.0007__ | __0.0000__ | __0.0000__ |   0.6997   |   0.4706   | __0.0000__ |   0.2819   | __0.0000__ | __0.0039__ |   0.4474   | __0.0003__ | __0.0070__ |   0.2751   |   0.9416   | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9937   |   1.0000   |   0.1345   | __0.0007__ | __0.0000__ | __0.0000__ |   0.6958   |   0.5093   | __0.0000__ |   0.2413   | __0.0000__ | __0.0025__ |   0.5087   | __0.0009__ | __0.0041__ |   0.2364   |   0.9427   | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.4098   |   0.1345   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2482   |   0.9069   | __0.0000__ |   0.0559   | __0.0000__ | __0.0295__ |   0.8942   | __0.0000__ | __0.0004__ | __0.0486__ |   0.3775   | __0.0010__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0007__ | __0.0007__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0076__ | __0.0002__ | __0.0000__ | __0.0141__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.7345   |   0.6108   | __0.0184__ | __0.0011__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3969   | __0.0000__ | __0.0000__ |   0.4393   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |   0.6000   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3969   |   1.0000   | __0.0000__ | __0.0000__ |   0.8334   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0084__ |   0.7325   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6997   |   0.6958   |   0.2482   | __0.0076__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2831   | __0.0000__ |   0.4208   | __0.0000__ | __0.0003__ |   0.2681   | __0.0050__ | __0.0110__ |   0.4177   |   0.7234   | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.4706   |   0.5093   |   0.9069   | __0.0002__ | __0.0000__ | __0.0000__ |   0.2831   |   1.0000   | __0.0000__ |   0.0667   | __0.0000__ | __0.0176__ |   0.9914   | __0.0001__ | __0.0007__ |   0.0791   |   0.4415   | __0.0001__ | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4393   |   0.8334   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0057__ |   0.8778   |
| [percival2014/stem](#percival2014stem)             |   0.2819   |   0.2413   |   0.0559   | __0.0141__ | __0.0000__ | __0.0000__ |   0.4208   |   0.0667   | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ |   0.0840   | __0.0140__ |   0.0762   |   0.9914   |   0.2265   | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0039__ | __0.0025__ | __0.0295__ | __0.0000__ | __0.0002__ | __0.0004__ | __0.0003__ | __0.0176__ | __0.0002__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |   0.2286   | __0.0001__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4474   |   0.5087   |   0.8942   | __0.0002__ | __0.0000__ | __0.0000__ |   0.2681   |   0.9914   | __0.0000__ |   0.0840   | __0.0000__ | __0.0009__ |   1.0000   | __0.0000__ | __0.0005__ |   0.0555   |   0.3866   | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0003__ | __0.0009__ | __0.0000__ |   0.7345   | __0.0000__ | __0.0000__ | __0.0050__ | __0.0001__ | __0.0000__ | __0.0140__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.4675   | __0.0120__ | __0.0007__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0070__ | __0.0041__ | __0.0004__ |   0.6108   | __0.0000__ | __0.0000__ | __0.0110__ | __0.0007__ | __0.0000__ |   0.0762   | __0.0000__ | __0.0000__ | __0.0005__ |   0.4675   |   1.0000   | __0.0254__ | __0.0036__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2751   |   0.2364   | __0.0486__ | __0.0184__ | __0.0000__ | __0.0000__ |   0.4177   |   0.0791   | __0.0000__ |   0.9914   | __0.0000__ | __0.0000__ |   0.0555   | __0.0120__ | __0.0254__ |   1.0000   |   0.2300   | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9416   |   0.9427   |   0.3775   | __0.0011__ | __0.0000__ | __0.0000__ |   0.7234   |   0.4415   | __0.0000__ |   0.2265   | __0.0000__ | __0.0009__ |   0.3866   | __0.0007__ | __0.0036__ |   0.2300   |   1.0000   | __0.0000__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0000__ | __0.0000__ | __0.0010__ | __0.0000__ | __0.0018__ | __0.0084__ | __0.0000__ | __0.0001__ | __0.0057__ | __0.0000__ | __0.0000__ |   0.2286   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0065__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6000   |   0.7325   | __0.0000__ | __0.0000__ |   0.8778   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0065__ |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | sun2021/default | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.7217   |   0.8502   | __0.0005__ | __0.0000__ | __0.0000__ |   0.9722   |   0.2553   | __0.0000__ |   0.1165   | __0.0000__ | __0.0036__ |   0.4346   | __0.0003__ | __0.0078__ |   0.2086   |   0.8692   | __0.0001__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.7217   |   1.0000   |   0.3124   | __0.0015__ | __0.0000__ | __0.0000__ |   0.7346   |   0.1657   | __0.0000__ |   0.1754   | __0.0000__ | __0.0007__ |   0.3079   | __0.0029__ | __0.0125__ |   0.3208   |   0.8276   | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8502   |   0.3124   |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ |   0.8277   |   0.3860   | __0.0000__ |   0.0806   | __0.0000__ | __0.0050__ |   0.5966   | __0.0004__ | __0.0032__ |   0.1288   |   0.7470   | __0.0002__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0005__ | __0.0015__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ |   0.0631   | __0.0000__ | __0.0000__ | __0.0001__ |   0.8028   |   0.4661   | __0.0205__ | __0.0011__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.6022   | __0.0000__ | __0.0000__ |   0.4540   | __0.0000__ | __0.0000__ | __0.0029__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0077__ |   0.5309   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6022   |   1.0000   | __0.0000__ | __0.0000__ |   0.8885   | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0094__ |   0.8916   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.9722   |   0.7346   |   0.8277   | __0.0020__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2317   | __0.0000__ |   0.0898   | __0.0000__ | __0.0008__ |   0.4282   | __0.0019__ | __0.0052__ |   0.1812   |   0.8990   | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2553   |   0.1657   |   0.3860   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2317   |   1.0000   | __0.0000__ | __0.0053__ | __0.0000__ |   0.0511   |   0.6883   | __0.0000__ | __0.0001__ | __0.0198__ |   0.2004   | __0.0026__ | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4540   |   0.8885   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0043__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0218__ |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   0.1165   |   0.1754   |   0.0806   |   0.0631   | __0.0000__ | __0.0000__ |   0.0898   | __0.0053__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0266__ |   0.0608   |   0.2647   |   0.6959   |   0.0907   | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0036__ | __0.0007__ | __0.0050__ | __0.0000__ | __0.0029__ | __0.0013__ | __0.0008__ |   0.0511   | __0.0043__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   0.4260   | __0.0031__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4346   |   0.3079   |   0.5966   | __0.0001__ | __0.0000__ | __0.0000__ |   0.4282   |   0.6883   | __0.0000__ | __0.0266__ | __0.0000__ | __0.0007__ |   1.0000   | __0.0000__ | __0.0006__ | __0.0335__ |   0.3211   | __0.0003__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0003__ | __0.0029__ | __0.0004__ |   0.8028   | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ | __0.0000__ |   0.0608   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.4118   | __0.0190__ | __0.0008__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0078__ | __0.0125__ | __0.0032__ |   0.4661   | __0.0000__ | __0.0000__ | __0.0052__ | __0.0001__ | __0.0000__ |   0.2647   | __0.0000__ | __0.0000__ | __0.0006__ |   0.4118   |   1.0000   |   0.0605   | __0.0051__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2086   |   0.3208   |   0.1288   | __0.0205__ | __0.0000__ | __0.0000__ |   0.1812   | __0.0198__ | __0.0000__ |   0.6959   | __0.0000__ | __0.0000__ | __0.0335__ | __0.0190__ |   0.0605   |   1.0000   |   0.1904   | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8692   |   0.8276   |   0.7470   | __0.0011__ | __0.0000__ | __0.0000__ |   0.8990   |   0.2004   | __0.0000__ |   0.0907   | __0.0000__ | __0.0004__ |   0.3211   | __0.0008__ | __0.0051__ |   0.1904   |   1.0000   | __0.0000__ | __0.0000__ |
| [sun2021/default](#sun2021default)                 | __0.0001__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0077__ | __0.0094__ | __0.0000__ | __0.0026__ | __0.0218__ | __0.0000__ | __0.0000__ |   0.4260   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0267__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5309   |   0.8916   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0031__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0267__ |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/acm_mirum_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/acm_mirum_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure35"></a>Figure 35: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure36"></a>Figure 36: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure37"></a>Figure 37: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/acm_mirum_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure38"></a>Figure 38: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/acm_mirum_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/acm_mirum_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/acm_mirum_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/acm_mirum_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/acm_mirum_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/acm_mirum_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/acm_mirum_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.1 on 2022-06-29 18:07. Size L.
