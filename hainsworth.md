---
title: hainsworth
{:.no_toc}
layout: default
---

# hainsworth
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'hainsworth' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'hainsworth'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Curator** | [Stephen Webley Hainsworth](mailto:swh21@eng.cam.ac.uk) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | mean of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Hainsworth2004](bib/Hainsworth2004.bib) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 2.0 |
| **Curator** | [Stephen Webley Hainsworth](mailto:swh21@eng.cam.ac.uk) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of corresponding inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Hainsworth2004](bib/Hainsworth2004.bib) |

### 3.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 3.0 |
| **Curator** | [Stephen Webley Hainsworth](mailto:swh21@eng.cam.ac.uk) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Hainsworth2004](bib/Hainsworth2004.bib) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   222   |   51.86   |   198.15   |   113.30   |   28.84   |   79.00   |   0.82   |
| [2.0](#20)                                         |   222   |   55.51   |   198.95   |   114.59   |   29.56   |   76.00   |   0.81   |
| [3.0](#30)                                         |   222   |   55.72   |   198.26   |   114.62   |   29.36   |   77.00   |   0.82   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/hainsworth_reference_basic_stats.csv "Download data as CSV") [JSON](data/hainsworth_reference_basic_stats.json "Download data as JSON") [LATEX](data/hainsworth_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/hainsworth_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/hainsworth_reference_dist.csv "Download data as CSV") [JSON](data/hainsworth_reference_dist.json "Download data as JSON") [LATEX](data/hainsworth_reference_dist.latex "Download data as LATEX") [PICKLE](data/hainsworth_reference_dist.pickle "Download data as PICKLE") [SVG](figures/hainsworth_reference_dist.svg "Open Figure") [PDF](figures/hainsworth_reference_dist.pdf "Open Figure") [PNG](figures/hainsworth_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/hainsworth_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/hainsworth_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/hainsworth_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/hainsworth_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/hainsworth_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/hainsworth_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/hainsworth_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/hainsworth_variation.csv "Download data as CSV") [JSON](data/hainsworth_variation.json "Download data as JSON") [LATEX](data/hainsworth_variation.latex "Download data as LATEX") [PICKLE](data/hainsworth_variation.pickle "Download data as PICKLE") [SVG](figures/hainsworth_variation.svg "Open Figure") [PDF](figures/hainsworth_variation.pdf "Open Figure") [PNG](figures/hainsworth_variation.png "Open Figure") 

# Estimates for 'hainsworth'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### boeck2019/multi_task

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2019/multi_task_hjdb

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task_hjdb, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### echonest/version_3_2_1

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 3.2.1 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Echo Nest track analyzer v3.2.1 |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### gkiokas2012/default

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Gkiokas2012 |
| **Annotator,&nbsp;bibtex** |[Gkiokas2012](bib/Gkiokas2012.bib) |

### klapuri2006/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Klapuri 2006 |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### oliveira2010/ibt

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Oliveira 2010 |
| **Annotator,&nbsp;bibtex** |[Oliveira2010](bib/Oliveira2010.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### scheirer1998/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Scheirer 1998 |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

### zplane/auftakt_v3

| Attribute | Value |
| --- | --- |
| **Corpus** | hainsworth |
| **Version** | 3.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | zplane aufTAKT version 3.0, http://licensing.zplane.de/technology#auftakt |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   222   |   41.96   |   230.77   |   112.29   |   30.61   |   70.00   |   0.82   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   222   |   55.32   |   208.46   |   112.94   |   29.11   |   71.00   |   0.84   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   222   |   45.53   |   208.12   |   112.57   |   28.84   |   70.00   |   0.82   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   222   |   80.75   |   234.91   |   125.65   |   26.74   |   81.00   |   0.93   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   222   |   0.00   |   191.72   |   99.74   |   28.19   |   71.00   |   0.76   |
| [gkiokas2012/default](#gkiokas2012default)         |   222   |   52.00   |   244.00   |   112.24   |   31.59   |   73.00   |   0.83   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   222   |   74.36   |   161.50   |   114.11   |   19.76   |   76.00   |   0.98   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   222   |   82.00   |   161.00   |   116.20   |   20.30   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   222   |   50.79   |   152.00   |   105.84   |   22.20   |   72.00   |   0.93   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   222   |   0.00   |   181.82   |   104.54   |   35.87   |   74.00   |   0.77   |
| [schreiber2014/default](#schreiber2014default)     |   222   |   54.85   |   164.50   |   101.41   |   22.60   |   69.00   |   0.90   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   222   |   26.50   |   193.51   |   106.25   |   26.09   |   71.00   |   0.84   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   222   |   13.25   |   197.54   |   105.21   |   29.14   |   74.00   |   0.81   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   222   |   63.00   |   216.00   |   116.03   |   29.14   |   81.00   |   0.88   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   222   |   50.00   |   208.00   |   114.58   |   30.17   |   75.00   |   0.82   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   222   |   65.00   |   208.00   |   114.31   |   26.12   |   77.00   |   0.91   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   222   |   65.50   |   164.80   |   111.46   |   22.53   |   76.00   |   0.92   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/hainsworth_estimates_basic_stats.csv "Download data as CSV") [JSON](data/hainsworth_estimates_basic_stats.json "Download data as JSON") [LATEX](data/hainsworth_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/hainsworth_estimates_dist.csv "Download data as CSV") [JSON](data/hainsworth_estimates_dist.json "Download data as JSON") [LATEX](data/hainsworth_estimates_dist.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_dist.svg "Open Figure") [PDF](figures/hainsworth_estimates_dist.pdf "Open Figure") [PNG](figures/hainsworth_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.8063__ |   0.8829   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.7973   |   0.8874   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.7973   | __0.8964__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7748   |   0.8423   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7703   |   0.8649   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7658   |   0.8468   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7387   |   0.8604   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7297   |   0.8514   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.7252   |   0.8198   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7207   |   0.8288   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7162   |   0.8423   |
| [schreiber2014/default](#schreiber2014default)     |   0.7072   |   0.8694   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6982   |   0.8243   |
| [percival2014/stem](#percival2014stem)             |   0.6982   |   0.8694   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6667   |   0.8559   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6441   |   0.8468   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4910   |   0.6532   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hainsworth_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hainsworth_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hainsworth_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/hainsworth_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/hainsworth_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.8514__ |   0.9279   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8333   | __0.9324__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8243   | __0.9324__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8018   |   0.8784   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7928   |   0.8919   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7838   |   0.8739   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7523   |   0.8649   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7477   |   0.8964   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7477   |   0.8919   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.7432   |   0.8378   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7297   |   0.8559   |
| [percival2014/stem](#percival2014stem)             |   0.7117   |   0.9054   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.7117   |   0.8468   |
| [schreiber2014/default](#schreiber2014default)     |   0.6982   |   0.8829   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6847   |   0.8829   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6757   |   0.8829   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5180   |   0.6847   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hainsworth_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hainsworth_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hainsworth_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/hainsworth_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/hainsworth_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_accuracy2.png "Open Figure") 

### Accuracy Results for 3.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.8604__ | __0.9369__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8243   |   0.9279   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8153   |   0.9279   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8018   |   0.8739   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7928   |   0.8919   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7793   |   0.8694   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7523   |   0.8559   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7477   |   0.8919   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.7432   |   0.8378   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7432   |   0.8919   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7297   |   0.8559   |
| [percival2014/stem](#percival2014stem)             |   0.7117   |   0.8919   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.7117   |   0.8423   |
| [schreiber2014/default](#schreiber2014default)     |   0.7072   |   0.8829   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6802   |   0.8784   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6712   |   0.8784   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5180   |   0.6892   |

<a name="table5"></a>Table 5: Mean accuracy of estimates compared to version [3.0](#30) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hainsworth_estimates_3.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hainsworth_estimates_3.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hainsworth_estimates_3.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/hainsworth_estimates_3.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/hainsworth_estimates_3.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (43 differences):*
'006' '012' '013' '022' '024' '025' '038' '053' '055' '058' '059' ...
[CSV](data/hainsworth_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (45 differences):*
'006' '012' '013' '022' '024' '025' '047' '048' '055' '057' '058' ...
[CSV](data/hainsworth_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (45 differences):*
'006' '007' '012' '013' '022' '024' '025' '047' '055' '057' '058' ...
[CSV](data/hainsworth_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (62 differences):*
'006' '007' '012' '013' '022' '024' '025' '035' '037' '047' '055' ...
[CSV](data/hainsworth_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (74 differences):*
'003' '006' '009' '012' '013' '019' '024' '037' '053' '055' '059' ...
[CSV](data/hainsworth_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (79 differences):*
'003' '006' '007' '008' '009' '010' '012' '013' '022' '024' '037' ...
[CSV](data/hainsworth_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (63 differences):*
'006' '007' '009' '012' '013' '022' '024' '025' '047' '053' '055' ...
[CSV](data/hainsworth_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (61 differences):*
'006' '007' '012' '013' '022' '024' '025' '035' '047' '055' '058' ...
[CSV](data/hainsworth_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (67 differences):*
'006' '007' '009' '012' '013' '022' '024' '042' '047' '053' '055' ...
[CSV](data/hainsworth_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (113 differences):*
'001' '002' '003' '006' '007' '009' '010' '012' '013' '019' '020' ...
[CSV](data/hainsworth_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (65 differences):*
'006' '007' '009' '012' '013' '016' '022' '024' '037' '052' '053' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (60 differences):*
'006' '009' '012' '013' '016' '024' '025' '055' '058' '059' '061' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'006' '009' '012' '013' '024' '025' '035' '058' '059' '061' '062' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (52 differences):*
'006' '007' '012' '013' '019' '022' '024' '037' '056' '057' '059' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (51 differences):*
'006' '007' '010' '012' '013' '024' '035' '037' '052' '059' '062' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (50 differences):*
'006' '007' '012' '013' '022' '024' '025' '037' '047' '053' '057' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (67 differences):*
'006' '007' '010' '012' '013' '022' '024' '025' '047' '055' '057' ...
[CSV](data/hainsworth_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (33 differences):*
'006' '013' '022' '025' '038' '053' '055' '058' '059' '066' '072' ...
[CSV](data/hainsworth_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (39 differences):*
'006' '013' '022' '024' '025' '047' '048' '055' '058' '059' '072' ...
[CSV](data/hainsworth_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (37 differences):*
'006' '013' '022' '025' '047' '055' '058' '059' '060' '072' '073' ...
[CSV](data/hainsworth_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (55 differences):*
'006' '007' '012' '013' '022' '025' '047' '055' '057' '058' '059' ...
[CSV](data/hainsworth_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (70 differences):*
'003' '006' '009' '013' '019' '024' '037' '053' '055' '059' '078' ...
[CSV](data/hainsworth_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (72 differences):*
'003' '006' '007' '008' '009' '010' '013' '022' '053' '055' '059' ...
[CSV](data/hainsworth_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (60 differences):*
'006' '007' '009' '013' '022' '025' '047' '053' '055' '057' '059' ...
[CSV](data/hainsworth_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (57 differences):*
'006' '007' '013' '022' '024' '025' '047' '055' '058' '059' '069' ...
[CSV](data/hainsworth_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (64 differences):*
'006' '007' '009' '013' '022' '042' '047' '053' '055' '057' '059' ...
[CSV](data/hainsworth_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (107 differences):*
'001' '002' '003' '006' '007' '009' '010' '012' '013' '019' '020' ...
[CSV](data/hainsworth_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (67 differences):*
'006' '007' '009' '013' '016' '022' '024' '052' '053' '055' '059' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (56 differences):*
'006' '009' '013' '016' '024' '025' '055' '058' '059' '061' '067' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (56 differences):*
'006' '009' '013' '025' '035' '058' '059' '061' '062' '067' '075' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (48 differences):*
'006' '007' '013' '019' '022' '056' '059' '060' '062' '070' '073' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (46 differences):*
'006' '007' '010' '013' '035' '052' '059' '062' '074' '075' '079' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (44 differences):*
'006' '007' '013' '022' '025' '047' '053' '057' '059' '062' '075' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (64 differences):*
'006' '007' '010' '013' '022' '025' '047' '055' '057' '059' '062' ...
[CSV](data/hainsworth_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (31 differences):*
'006' '013' '022' '025' '038' '053' '055' '058' '059' '066' '072' ...
[CSV](data/hainsworth_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (41 differences):*
'006' '013' '022' '024' '025' '047' '048' '055' '058' '059' '072' ...
[CSV](data/hainsworth_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (39 differences):*
'006' '013' '022' '025' '047' '055' '058' '059' '060' '072' '073' ...
[CSV](data/hainsworth_estimates_3.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (55 differences):*
'006' '007' '012' '013' '022' '025' '047' '055' '057' '058' '059' ...
[CSV](data/hainsworth_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (71 differences):*
'003' '006' '007' '009' '013' '019' '024' '037' '053' '055' '059' ...
[CSV](data/hainsworth_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (73 differences):*
'003' '006' '007' '008' '009' '010' '013' '022' '053' '055' '059' ...
[CSV](data/hainsworth_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (60 differences):*
'006' '007' '009' '013' '022' '025' '047' '053' '055' '057' '059' ...
[CSV](data/hainsworth_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (57 differences):*
'006' '007' '013' '022' '024' '025' '047' '055' '058' '059' '069' ...
[CSV](data/hainsworth_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (64 differences):*
'006' '007' '009' '013' '022' '042' '047' '053' '055' '059' '067' ...
[CSV](data/hainsworth_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (107 differences):*
'001' '002' '003' '006' '007' '009' '010' '012' '013' '019' '020' ...
[CSV](data/hainsworth_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (65 differences):*
'006' '009' '013' '016' '022' '024' '052' '053' '055' '059' '062' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (56 differences):*
'006' '009' '013' '016' '024' '025' '055' '058' '059' '061' '067' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (57 differences):*
'006' '009' '013' '025' '035' '058' '059' '061' '062' '067' '075' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (49 differences):*
'006' '007' '013' '019' '022' '056' '059' '060' '062' '070' '073' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (46 differences):*
'006' '007' '010' '013' '035' '052' '059' '062' '074' '075' '079' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (44 differences):*
'006' '007' '013' '022' '025' '047' '053' '057' '059' '062' '075' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (64 differences):*
'006' '007' '010' '013' '022' '025' '047' '055' '057' '059' '062' ...
[CSV](data/hainsworth_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 6 items 'correctly' using Accuracy<sub>1</sub>:__
'006' '013' '059' '127' '137' '138' 
[CSV](data/hainsworth_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (26 differences):*
'006' '012' '013' '024' '059' '062' '072' '075' '078' '107' '125' ...
[CSV](data/hainsworth_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (23 differences):*
'006' '012' '013' '024' '057' '058' '059' '062' '072' '107' '126' ...
[CSV](data/hainsworth_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (25 differences):*
'006' '007' '012' '013' '024' '057' '058' '059' '062' '072' '075' ...
[CSV](data/hainsworth_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (38 differences):*
'006' '007' '012' '013' '024' '035' '037' '059' '062' '075' '091' ...
[CSV](data/hainsworth_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (32 differences):*
'006' '012' '013' '024' '059' '062' '094' '103' '106' '107' '121' ...
[CSV](data/hainsworth_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (34 differences):*
'003' '006' '010' '012' '013' '024' '037' '057' '059' '062' '091' ...
[CSV](data/hainsworth_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (35 differences):*
'006' '012' '013' '024' '057' '059' '062' '075' '091' '103' '107' ...
[CSV](data/hainsworth_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (40 differences):*
'006' '007' '012' '024' '035' '058' '059' '062' '070' '075' '091' ...
[CSV](data/hainsworth_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (29 differences):*
'006' '007' '012' '013' '024' '057' '059' '062' '075' '107' '123' ...
[CSV](data/hainsworth_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (77 differences):*
'001' '002' '003' '007' '009' '010' '012' '013' '020' '024' '043' ...
[CSV](data/hainsworth_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (29 differences):*
'006' '007' '012' '024' '037' '052' '059' '062' '072' '075' '091' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (33 differences):*
'006' '012' '013' '024' '058' '059' '061' '062' '075' '091' '107' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (31 differences):*
'006' '012' '013' '024' '058' '059' '062' '075' '091' '107' '124' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (34 differences):*
'006' '007' '012' '013' '024' '037' '057' '059' '062' '091' '107' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (30 differences):*
'006' '007' '010' '012' '013' '024' '037' '052' '062' '078' '107' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (35 differences):*
'006' '007' '012' '013' '024' '037' '057' '059' '062' '078' '091' ...
[CSV](data/hainsworth_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (39 differences):*
'006' '007' '010' '012' '013' '024' '057' '059' '062' '075' '107' ...
[CSV](data/hainsworth_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (16 differences):*
'006' '013' '059' '072' '075' '107' '125' '126' '127' '132' '133' ...
[CSV](data/hainsworth_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (15 differences):*
'006' '013' '058' '059' '072' '107' '126' '127' '132' '137' '138' ...
[CSV](data/hainsworth_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (15 differences):*
'006' '013' '058' '059' '072' '075' '107' '127' '132' '134' '137' ...
[CSV](data/hainsworth_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (30 differences):*
'006' '007' '012' '013' '059' '075' '091' '122' '123' '124' '126' ...
[CSV](data/hainsworth_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (26 differences):*
'006' '013' '024' '059' '094' '103' '106' '107' '122' '123' '124' ...
[CSV](data/hainsworth_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (26 differences):*
'003' '006' '010' '013' '059' '091' '107' '121' '122' '124' '125' ...
[CSV](data/hainsworth_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (32 differences):*
'006' '013' '057' '059' '075' '090' '091' '103' '107' '121' '122' ...
[CSV](data/hainsworth_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (36 differences):*
'006' '007' '024' '058' '059' '070' '075' '091' '103' '121' '122' ...
[CSV](data/hainsworth_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (21 differences):*
'006' '007' '013' '057' '059' '075' '123' '124' '125' '126' '127' ...
[CSV](data/hainsworth_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (70 differences):*
'001' '002' '003' '006' '007' '009' '010' '012' '013' '020' '043' ...
[CSV](data/hainsworth_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (26 differences):*
'006' '007' '024' '052' '059' '072' '075' '084' '091' '123' '124' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (24 differences):*
'006' '013' '058' '059' '061' '075' '091' '124' '125' '126' '127' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (23 differences):*
'006' '013' '058' '059' '075' '091' '124' '125' '126' '127' '128' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (28 differences):*
'006' '007' '013' '059' '091' '107' '121' '122' '123' '124' '125' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (24 differences):*
'006' '007' '010' '013' '052' '107' '121' '124' '125' '126' '127' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (27 differences):*
'006' '007' '013' '057' '059' '091' '107' '122' '123' '125' '126' ...
[CSV](data/hainsworth_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (34 differences):*
'006' '007' '010' '013' '057' '059' '075' '107' '121' '122' '123' ...
[CSV](data/hainsworth_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (14 differences):*
'006' '013' '059' '072' '075' '107' '126' '127' '133' '137' '138' ...
[CSV](data/hainsworth_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (16 differences):*
'006' '058' '059' '072' '107' '122' '126' '127' '132' '133' '137' ...
[CSV](data/hainsworth_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (16 differences):*
'006' '058' '059' '072' '075' '107' '122' '127' '132' '133' '134' ...
[CSV](data/hainsworth_estimates_3.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (32 differences):*
'006' '007' '012' '013' '059' '075' '091' '122' '123' '124' '125' ...
[CSV](data/hainsworth_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (27 differences):*
'006' '007' '013' '024' '059' '094' '103' '106' '107' '122' '123' ...
[CSV](data/hainsworth_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (27 differences):*
'003' '006' '010' '013' '059' '091' '107' '121' '122' '124' '125' ...
[CSV](data/hainsworth_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (32 differences):*
'006' '013' '057' '059' '075' '090' '091' '103' '107' '121' '122' ...
[CSV](data/hainsworth_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (36 differences):*
'006' '007' '024' '058' '059' '070' '075' '091' '103' '121' '122' ...
[CSV](data/hainsworth_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (24 differences):*
'006' '007' '013' '059' '075' '107' '121' '122' '123' '124' '125' ...
[CSV](data/hainsworth_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (69 differences):*
'001' '002' '003' '006' '007' '009' '010' '012' '020' '043' '058' ...
[CSV](data/hainsworth_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (26 differences):*
'006' '024' '052' '059' '072' '075' '084' '091' '107' '122' '123' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (24 differences):*
'006' '013' '058' '059' '061' '075' '091' '107' '124' '125' '126' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (24 differences):*
'006' '013' '058' '059' '075' '091' '107' '124' '125' '126' '127' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (29 differences):*
'006' '007' '013' '059' '091' '107' '121' '122' '123' '124' '125' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (24 differences):*
'006' '007' '010' '013' '052' '107' '121' '124' '126' '127' '129' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (28 differences):*
'006' '007' '013' '057' '059' '091' '107' '122' '123' '125' '126' ...
[CSV](data/hainsworth_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (35 differences):*
'006' '007' '010' '013' '057' '059' '075' '107' '112' '121' '122' ...
[CSV](data/hainsworth_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.8318   |   0.8450   | __0.0026__ | __0.0000__ | __0.0000__ | __0.0029__ | __0.0064__ | __0.0003__ | __0.0000__ | __0.0013__ | __0.0033__ | __0.0201__ |   0.2110   |   0.2430   |   0.2478   | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8318   |   1.0000   |   1.0000   | __0.0076__ | __0.0002__ | __0.0000__ | __0.0079__ | __0.0139__ | __0.0013__ | __0.0000__ | __0.0078__ | __0.0167__ |   0.0596   |   0.3368   |   0.4408   |   0.4731   | __0.0009__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8450   |   1.0000   |   1.0000   | __0.0060__ | __0.0003__ | __0.0000__ | __0.0064__ | __0.0113__ | __0.0013__ | __0.0000__ | __0.0078__ | __0.0201__ |   0.0660   |   0.3105   |   0.4408   |   0.4583   | __0.0007__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0026__ | __0.0076__ | __0.0060__ |   1.0000   |   0.1337   | __0.0115__ |   1.0000   |   1.0000   |   0.5114   | __0.0000__ |   0.7838   |   0.8714   |   0.6177   |   0.1214   |   0.1173   | __0.0227__ |   0.4049   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0002__ | __0.0003__ |   0.1337   |   1.0000   |   0.5114   |   0.1352   |   0.1048   |   0.3489   | __0.0000__ |   0.2221   | __0.0436__ | __0.0226__ | __0.0038__ | __0.0008__ | __0.0009__ |   0.3916   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0115__ |   0.5114   |   1.0000   | __0.0139__ | __0.0114__ |   0.0730   | __0.0001__ | __0.0488__ | __0.0079__ | __0.0031__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.0807   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0029__ | __0.0079__ | __0.0064__ |   1.0000   |   0.1352   | __0.0139__ |   1.0000   |   0.8145   |   0.5413   | __0.0000__ |   0.8804   |   0.7428   |   0.5224   |   0.0895   |   0.0807   | __0.0146__ |   0.5413   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0064__ | __0.0139__ | __0.0113__ |   1.0000   |   0.1048   | __0.0114__ |   0.8145   |   1.0000   |   0.3915   | __0.0000__ |   0.6885   |   1.0000   |   0.7428   |   0.1755   |   0.1641   |   0.0522   |   0.3269   |
| [percival2014/stem](#percival2014stem)             | __0.0003__ | __0.0013__ | __0.0013__ |   0.5114   |   0.3489   |   0.0730   |   0.5413   |   0.3915   |   1.0000   | __0.0000__ |   0.8714   |   0.2962   |   0.1877   | __0.0357__ | __0.0195__ | __0.0060__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0013__ | __0.0078__ | __0.0078__ |   0.7838   |   0.2221   | __0.0488__ |   0.8804   |   0.6885   |   0.8714   | __0.0000__ |   1.0000   |   0.5224   |   0.3489   |   0.0854   |   0.0595   | __0.0444__ |   0.8776   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0033__ | __0.0167__ | __0.0201__ |   0.8714   | __0.0436__ | __0.0079__ |   0.7428   |   1.0000   |   0.2962   | __0.0000__ |   0.5224   |   1.0000   |   0.8036   |   0.2800   |   0.1996   |   0.1214   |   0.3240   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0201__ |   0.0596   |   0.0660   |   0.6177   | __0.0226__ | __0.0031__ |   0.5224   |   0.7428   |   0.1877   | __0.0000__ |   0.3489   |   0.8036   |   1.0000   |   0.4408   |   0.3368   |   0.2559   |   0.1755   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2110   |   0.3368   |   0.3105   |   0.1214   | __0.0038__ | __0.0001__ |   0.0895   |   0.1755   | __0.0357__ | __0.0000__ |   0.0854   |   0.2800   |   0.4408   |   1.0000   |   1.0000   |   0.8388   | __0.0315__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2430   |   0.4408   |   0.4408   |   0.1173   | __0.0008__ | __0.0000__ |   0.0807   |   0.1641   | __0.0195__ | __0.0000__ |   0.0595   |   0.1996   |   0.3368   |   1.0000   |   1.0000   |   1.0000   | __0.0195__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2478   |   0.4731   |   0.4583   | __0.0227__ | __0.0009__ | __0.0000__ | __0.0146__ |   0.0522   | __0.0060__ | __0.0000__ | __0.0444__ |   0.1214   |   0.2559   |   0.8388   |   1.0000   |   1.0000   | __0.0033__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0009__ | __0.0007__ |   0.4049   |   0.3916   |   0.0807   |   0.5413   |   0.3269   |   1.0000   | __0.0000__ |   0.8776   |   0.3240   |   0.1755   | __0.0315__ | __0.0195__ | __0.0033__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3075   |   0.5716   | __0.0016__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0006__ | __0.0237__ |   0.0596   |   0.0708   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.3075   |   1.0000   |   0.7905   | __0.0226__ | __0.0001__ | __0.0001__ | __0.0031__ | __0.0079__ | __0.0005__ | __0.0000__ | __0.0001__ | __0.0060__ | __0.0161__ |   0.2110   |   0.3713   |   0.4996   | __0.0005__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.5716   |   0.7905   |   1.0000   | __0.0064__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0029__ | __0.0002__ | __0.0000__ | __0.0001__ | __0.0034__ | __0.0066__ |   0.1081   |   0.2327   |   0.2962   | __0.0001__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0016__ | __0.0226__ | __0.0064__ |   1.0000   |   0.0722   | __0.0161__ |   0.3833   |   0.8036   |   0.1877   | __0.0000__ |   0.1480   |   1.0000   |   1.0000   |   0.3240   |   0.2430   |   0.0614   |   0.1221   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0001__ | __0.0000__ |   0.0722   |   1.0000   |   0.8776   |   0.1934   |   0.1048   |   0.4408   | __0.0000__ |   0.7709   | __0.0488__ |   0.0595   | __0.0046__ | __0.0009__ | __0.0007__ |   0.4799   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0001__ | __0.0000__ | __0.0161__ |   0.8776   |   1.0000   |   0.0730   | __0.0357__ |   0.2682   | __0.0000__ |   0.5682   | __0.0328__ | __0.0293__ | __0.0005__ | __0.0003__ | __0.0001__ |   0.2912   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0001__ | __0.0031__ | __0.0008__ |   0.3833   |   0.1934   |   0.0730   |   1.0000   |   0.6476   |   0.5413   | __0.0000__ |   0.3817   |   0.6358   |   0.6358   |   0.0652   | __0.0436__ | __0.0037__ |   0.5572   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0004__ | __0.0079__ | __0.0029__ |   0.8036   |   0.1048   | __0.0357__ |   0.6476   |   1.0000   |   0.3240   | __0.0000__ |   0.2370   |   1.0000   |   1.0000   |   0.1628   |   0.1263   | __0.0241__ |   0.2478   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0005__ | __0.0002__ |   0.1877   |   0.4408   |   0.2682   |   0.5413   |   0.3240   |   1.0000   | __0.0000__ |   0.7493   |   0.2295   |   0.2559   | __0.0226__ | __0.0096__ | __0.0022__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0001__ | __0.0001__ |   0.1480   |   0.7709   |   0.5682   |   0.3817   |   0.2370   |   0.7493   | __0.0000__ |   1.0000   |   0.1081   |   0.1173   | __0.0110__ | __0.0055__ | __0.0022__ |   0.7608   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0001__ | __0.0060__ | __0.0034__ |   1.0000   | __0.0488__ | __0.0328__ |   0.6358   |   1.0000   |   0.2295   | __0.0000__ |   0.1081   |   1.0000   |   1.0000   |   0.2800   |   0.1641   |   0.0652   |   0.2800   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0006__ | __0.0161__ | __0.0066__ |   1.0000   |   0.0595   | __0.0293__ |   0.6358   |   1.0000   |   0.2559   | __0.0000__ |   0.1173   |   1.0000   |   1.0000   |   0.2682   |   0.1433   |   0.0730   |   0.2430   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0237__ |   0.2110   |   0.1081   |   0.3240   | __0.0046__ | __0.0005__ |   0.0652   |   0.1628   | __0.0226__ | __0.0000__ | __0.0110__ |   0.2800   |   0.2682   |   1.0000   |   0.8450   |   0.5413   | __0.0195__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0596   |   0.3713   |   0.2327   |   0.2430   | __0.0009__ | __0.0003__ | __0.0436__ |   0.1263   | __0.0096__ | __0.0000__ | __0.0055__ |   0.1641   |   0.1433   |   0.8450   |   1.0000   |   0.8450   | __0.0079__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0708   |   0.4996   |   0.2962   |   0.0614   | __0.0007__ | __0.0001__ | __0.0037__ | __0.0241__ | __0.0022__ | __0.0000__ | __0.0022__ |   0.0652   |   0.0730   |   0.5413   |   0.8450   |   1.0000   | __0.0005__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0005__ | __0.0001__ |   0.1221   |   0.4799   |   0.2912   |   0.5572   |   0.2478   |   1.0000   | __0.0000__ |   0.7608   |   0.2800   |   0.2430   | __0.0195__ | __0.0079__ | __0.0005__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0639   |   0.1849   | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0079__ | __0.0275__ | __0.0351__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0639   |   1.0000   |   0.7905   | __0.0436__ | __0.0001__ | __0.0001__ | __0.0066__ | __0.0166__ | __0.0011__ | __0.0000__ | __0.0007__ | __0.0167__ | __0.0195__ |   0.2682   |   0.5424   |   0.7283   | __0.0011__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1849   |   0.7905   |   1.0000   | __0.0139__ | __0.0000__ | __0.0000__ | __0.0019__ | __0.0064__ | __0.0005__ | __0.0000__ | __0.0004__ | __0.0095__ | __0.0079__ |   0.1325   |   0.3604   |   0.4731   | __0.0002__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0007__ | __0.0436__ | __0.0139__ |   1.0000   |   0.0519   | __0.0096__ |   0.3833   |   0.8036   |   0.1877   | __0.0000__ |   0.2288   |   1.0000   |   0.8746   |   0.4050   |   0.2430   |   0.0614   |   0.1221   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0001__ | __0.0000__ |   0.0519   |   1.0000   |   0.8746   |   0.1439   |   0.0759   |   0.3489   | __0.0000__ |   0.4614   | __0.0357__ |   0.0595   | __0.0038__ | __0.0005__ | __0.0004__ |   0.3916   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0001__ | __0.0000__ | __0.0096__ |   0.8746   |   1.0000   | __0.0470__ | __0.0226__ |   0.1877   | __0.0000__ |   0.3020   | __0.0213__ | __0.0259__ | __0.0005__ | __0.0001__ | __0.0001__ |   0.2221   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0066__ | __0.0019__ |   0.3833   |   0.1439   | __0.0470__ |   1.0000   |   0.6476   |   0.5413   | __0.0000__ |   0.5515   |   0.6358   |   0.7493   |   0.0895   | __0.0436__ | __0.0037__ |   0.5572   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0002__ | __0.0166__ | __0.0064__ |   0.8036   |   0.0759   | __0.0226__ |   0.6476   |   1.0000   |   0.3105   | __0.0000__ |   0.3497   |   1.0000   |   1.0000   |   0.2153   |   0.1263   | __0.0241__ |   0.2478   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0011__ | __0.0005__ |   0.1877   |   0.3489   |   0.1877   |   0.5413   |   0.3105   |   1.0000   | __0.0000__ |   1.0000   |   0.2295   |   0.3105   | __0.0315__ | __0.0079__ | __0.0022__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0007__ | __0.0004__ |   0.2288   |   0.4614   |   0.3020   |   0.5515   |   0.3497   |   1.0000   | __0.0000__ |   1.0000   |   0.1877   |   0.2430   | __0.0328__ | __0.0110__ | __0.0046__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0167__ | __0.0095__ |   1.0000   | __0.0357__ | __0.0213__ |   0.6358   |   1.0000   |   0.2295   | __0.0000__ |   0.1877   |   1.0000   |   1.0000   |   0.3604   |   0.1641   |   0.0652   |   0.2800   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0001__ | __0.0195__ | __0.0079__ |   0.8746   |   0.0595   | __0.0259__ |   0.7493   |   1.0000   |   0.3105   | __0.0000__ |   0.2430   |   1.0000   |   1.0000   |   0.2559   |   0.0989   | __0.0470__ |   0.3105   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0079__ |   0.2682   |   0.1325   |   0.4050   | __0.0038__ | __0.0005__ |   0.0895   |   0.2153   | __0.0315__ | __0.0000__ | __0.0328__ |   0.3604   |   0.2559   |   1.0000   |   0.6900   |   0.4049   | __0.0275__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0275__ |   0.5424   |   0.3604   |   0.2430   | __0.0005__ | __0.0001__ | __0.0436__ |   0.1263   | __0.0079__ | __0.0000__ | __0.0110__ |   0.1641   |   0.0989   |   0.6900   |   1.0000   |   0.8450   | __0.0079__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0351__ |   0.7283   |   0.4731   |   0.0614   | __0.0004__ | __0.0001__ | __0.0037__ | __0.0241__ | __0.0022__ | __0.0000__ | __0.0046__ |   0.0652   | __0.0470__ |   0.4049   |   0.8450   |   1.0000   | __0.0005__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0011__ | __0.0002__ |   0.1221   |   0.3916   |   0.2221   |   0.5572   |   0.2478   |   1.0000   | __0.0000__ |   1.0000   |   0.2800   |   0.3105   | __0.0275__ | __0.0079__ | __0.0005__ |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5078   |   1.0000   | __0.0118__ |   0.2101   |   0.0963   |   0.0636   | __0.0066__ |   0.5488   | __0.0000__ |   0.6072   |   0.0923   |   0.2668   |   0.1153   |   0.4545   | __0.0352__ | __0.0106__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5078   |   1.0000   |   0.6250   | __0.0026__ | __0.0490__ | __0.0127__ | __0.0169__ | __0.0009__ |   0.1460   | __0.0000__ |   0.2632   | __0.0129__ |   0.0574   | __0.0266__ |   0.1892   | __0.0042__ | __0.0015__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   |   0.6250   |   1.0000   | __0.0072__ |   0.1892   |   0.0784   |   0.0525   | __0.0041__ |   0.3437   | __0.0000__ |   0.4807   |   0.0768   |   0.2101   |   0.0784   |   0.3833   | __0.0309__ | __0.0066__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0118__ | __0.0026__ | __0.0072__ |   1.0000   |   0.2863   |   0.4807   |   0.6476   |   0.8036   | __0.0225__ | __0.0000__ |   0.0636   |   0.3323   |   0.1435   |   0.4545   |   0.1338   |   0.6072   |   1.0000   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2101   | __0.0490__ |   0.1892   |   0.2863   |   1.0000   |   0.8145   |   0.6072   |   0.1153   |   0.6072   | __0.0000__ |   0.6776   |   1.0000   |   1.0000   |   0.8145   |   0.8145   |   0.6291   |   0.1671   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0963   | __0.0127__ |   0.0784   |   0.4807   |   0.8145   |   1.0000   |   1.0000   |   0.2863   |   0.3323   | __0.0000__ |   0.4049   |   1.0000   |   0.6072   |   1.0000   |   0.4807   |   1.0000   |   0.3323   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0636   | __0.0169__ |   0.0525   |   0.6476   |   0.6072   |   1.0000   |   1.0000   |   0.3323   |   0.2632   | __0.0000__ |   0.3269   |   0.8036   |   0.4545   |   1.0000   |   0.3593   |   1.0000   |   0.5235   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0066__ | __0.0009__ | __0.0041__ |   0.8036   |   0.1153   |   0.2863   |   0.3323   |   1.0000   | __0.0192__ | __0.0000__ |   0.0522   |   0.1671   |   0.0636   |   0.2632   |   0.0872   |   0.3593   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   0.5488   |   0.1460   |   0.3437   | __0.0225__ |   0.6072   |   0.3323   |   0.2632   | __0.0192__ |   1.0000   | __0.0000__ |   1.0000   |   0.3877   |   0.7744   |   0.3018   |   1.0000   |   0.1094   | __0.0129__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.6072   |   0.2632   |   0.4807   |   0.0636   |   0.6776   |   0.4049   |   0.3269   |   0.0522   |   1.0000   | __0.0000__ |   1.0000   |   0.5034   |   0.8238   |   0.3593   |   1.0000   |   0.2632   |   0.0755   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0923   | __0.0129__ |   0.0768   |   0.3323   |   1.0000   |   1.0000   |   0.8036   |   0.1671   |   0.3877   | __0.0000__ |   0.5034   |   1.0000   |   0.5000   |   1.0000   |   0.6636   |   0.8145   |   0.2101   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2668   |   0.0574   |   0.2101   |   0.1435   |   1.0000   |   0.6072   |   0.4545   |   0.0636   |   0.7744   | __0.0000__ |   0.8238   |   0.5000   |   1.0000   |   0.6291   |   1.0000   |   0.4807   |   0.0768   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1153   | __0.0266__ |   0.0784   |   0.4545   |   0.8145   |   1.0000   |   1.0000   |   0.2632   |   0.3018   | __0.0000__ |   0.3593   |   1.0000   |   0.6291   |   1.0000   |   0.4807   |   1.0000   |   0.3323   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.4545   |   0.1892   |   0.3833   |   0.1338   |   0.8145   |   0.4807   |   0.3593   |   0.0872   |   1.0000   | __0.0000__ |   1.0000   |   0.6636   |   1.0000   |   0.4807   |   1.0000   |   0.3323   |   0.0931   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0352__ | __0.0042__ | __0.0309__ |   0.6072   |   0.6291   |   1.0000   |   1.0000   |   0.3593   |   0.1094   | __0.0000__ |   0.2632   |   0.8145   |   0.4807   |   1.0000   |   0.3323   |   1.0000   |   0.5034   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0106__ | __0.0015__ | __0.0066__ |   1.0000   |   0.1671   |   0.3323   |   0.5235   |   1.0000   | __0.0129__ | __0.0000__ |   0.0755   |   0.2101   |   0.0768   |   0.3323   |   0.0931   |   0.5034   |   1.0000   |

<a name="table9"></a>Table 9: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   | __0.0094__ | __0.0309__ | __0.0213__ | __0.0015__ | __0.0001__ |   0.3018   | __0.0000__ | __0.0309__ | __0.0386__ |   0.0654   | __0.0042__ |   0.0963   | __0.0127__ | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   1.0000   |   1.0000   |   1.0000   | __0.0059__ | __0.0192__ | __0.0074__ | __0.0023__ | __0.0000__ |   0.2379   | __0.0000__ | __0.0266__ | __0.0225__ | __0.0386__ | __0.0044__ |   0.0636   | __0.0075__ | __0.0003__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   |   1.0000   |   1.0000   | __0.0059__ | __0.0266__ | __0.0192__ | __0.0015__ | __0.0001__ |   0.2379   | __0.0000__ | __0.0266__ | __0.0352__ |   0.0574   | __0.0072__ |   0.0784   | __0.0169__ | __0.0005__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0094__ | __0.0059__ | __0.0059__ |   1.0000   |   0.5413   |   0.5235   |   0.8318   |   0.2379   | __0.0352__ | __0.0000__ |   0.5572   |   0.2863   |   0.1892   |   0.8145   |   0.3075   |   0.6476   |   0.5413   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0309__ | __0.0192__ | __0.0266__ |   0.5413   |   1.0000   |   1.0000   |   0.2379   | __0.0309__ |   0.3323   | __0.0000__ |   1.0000   |   0.8238   |   0.6476   |   0.8145   |   0.8318   |   1.0000   |   0.1338   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0213__ | __0.0074__ | __0.0192__ |   0.5235   |   1.0000   |   1.0000   |   0.2632   | __0.0414__ |   0.3593   | __0.0000__ |   1.0000   |   0.7905   |   0.5811   |   0.7905   |   0.8145   |   1.0000   |   0.0963   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0015__ | __0.0023__ | __0.0015__ |   0.8318   |   0.2379   |   0.2632   |   1.0000   |   0.4807   | __0.0347__ | __0.0000__ |   0.3915   |   0.1516   |   0.0931   |   0.4807   |   0.1338   |   0.4049   |   0.8318   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0001__ | __0.0000__ | __0.0001__ |   0.2379   | __0.0309__ | __0.0414__ |   0.4807   |   1.0000   | __0.0007__ | __0.0000__ |   0.0755   | __0.0118__ | __0.0044__ |   0.0768   | __0.0227__ |   0.0636   |   0.8238   |
| [percival2014/stem](#percival2014stem)             |   0.3018   |   0.2379   |   0.2379   | __0.0352__ |   0.3323   |   0.3593   | __0.0347__ | __0.0007__ |   1.0000   | __0.0000__ |   0.3833   |   0.6072   |   0.7905   |   0.1185   |   0.6476   |   0.1796   | __0.0010__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0309__ | __0.0266__ | __0.0266__ |   0.5572   |   1.0000   |   1.0000   |   0.3915   |   0.0755   |   0.3833   | __0.0000__ |   1.0000   |   0.8238   |   0.6476   |   0.8318   |   0.8450   |   1.0000   |   0.1686   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0386__ | __0.0225__ | __0.0352__ |   0.2863   |   0.8238   |   0.7905   |   0.1516   | __0.0118__ |   0.6072   | __0.0000__ |   0.8238   |   1.0000   |   1.0000   |   0.4545   |   1.0000   |   0.6291   | __0.0414__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0654   | __0.0386__ |   0.0574   |   0.1892   |   0.6476   |   0.5811   |   0.0931   | __0.0044__ |   0.7905   | __0.0000__ |   0.6476   |   1.0000   |   1.0000   |   0.3018   |   1.0000   |   0.4545   | __0.0192__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0042__ | __0.0044__ | __0.0072__ |   0.8145   |   0.8145   |   0.7905   |   0.4807   |   0.0768   |   0.1185   | __0.0000__ |   0.8318   |   0.4545   |   0.3018   |   1.0000   |   0.4240   |   1.0000   |   0.2101   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0963   |   0.0636   |   0.0784   |   0.3075   |   0.8318   |   0.8145   |   0.1338   | __0.0227__ |   0.6476   | __0.0000__ |   0.8450   |   1.0000   |   1.0000   |   0.4240   |   1.0000   |   0.6476   | __0.0414__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0127__ | __0.0075__ | __0.0169__ |   0.6476   |   1.0000   |   1.0000   |   0.4049   |   0.0636   |   0.1796   | __0.0000__ |   1.0000   |   0.6291   |   0.4545   |   1.0000   |   0.6476   |   1.0000   |   0.1435   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0003__ | __0.0005__ |   0.5413   |   0.1338   |   0.0963   |   0.8318   |   0.8238   | __0.0010__ | __0.0000__ |   0.1686   | __0.0414__ | __0.0192__ |   0.2101   | __0.0414__ |   0.1435   |   1.0000   |

<a name="table10"></a>Table 10: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6875   |   0.6875   | __0.0003__ | __0.0072__ | __0.0044__ | __0.0003__ | __0.0000__ | __0.0213__ | __0.0000__ | __0.0018__ | __0.0129__ | __0.0063__ | __0.0007__ | __0.0309__ | __0.0026__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.6875   |   1.0000   |   1.0000   | __0.0025__ | __0.0192__ | __0.0127__ | __0.0037__ | __0.0000__ |   0.0963   | __0.0000__ | __0.0129__ |   0.0574   | __0.0386__ | __0.0044__ |   0.1338   | __0.0075__ | __0.0002__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6875   |   1.0000   |   1.0000   | __0.0025__ | __0.0266__ | __0.0266__ | __0.0025__ | __0.0001__ |   0.0963   | __0.0000__ | __0.0129__ |   0.0768   |   0.0574   | __0.0072__ |   0.1516   | __0.0169__ | __0.0003__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0003__ | __0.0025__ | __0.0025__ |   1.0000   |   0.3833   |   0.3593   |   1.0000   |   0.4240   |   0.0574   | __0.0000__ |   0.2863   |   0.1153   |   0.0963   |   0.5811   |   0.1338   |   0.4545   |   0.6476   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0072__ | __0.0192__ | __0.0266__ |   0.3833   |   1.0000   |   1.0000   |   0.3593   | __0.0490__ |   0.5811   | __0.0000__ |   1.0000   |   0.6636   |   0.6476   |   0.8036   |   0.6636   |   1.0000   |   0.1153   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0044__ | __0.0127__ | __0.0266__ |   0.3593   |   1.0000   |   1.0000   |   0.3593   |   0.0636   |   0.6291   | __0.0000__ |   1.0000   |   0.5811   |   0.5811   |   0.7905   |   0.6291   |   1.0000   |   0.0963   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0003__ | __0.0037__ | __0.0025__ |   1.0000   |   0.3593   |   0.3593   |   1.0000   |   0.4807   |   0.1153   | __0.0000__ |   0.3449   |   0.1516   |   0.1338   |   0.6291   |   0.1338   |   0.5235   |   0.6776   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0001__ |   0.4240   | __0.0490__ |   0.0636   |   0.4807   |   1.0000   | __0.0042__ | __0.0000__ |   0.0639   | __0.0169__ | __0.0118__ |   0.1185   | __0.0227__ |   0.0963   |   1.0000   |
| [percival2014/stem](#percival2014stem)             | __0.0213__ |   0.0963   |   0.0963   |   0.0574   |   0.5811   |   0.6291   |   0.1153   | __0.0042__ |   1.0000   | __0.0000__ |   0.8238   |   1.0000   |   1.0000   |   0.2266   |   1.0000   |   0.4240   | __0.0010__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0018__ | __0.0129__ | __0.0129__ |   0.2863   |   1.0000   |   1.0000   |   0.3449   |   0.0639   |   0.8238   | __0.0000__ |   1.0000   |   0.8145   |   0.8036   |   0.6476   |   0.8388   |   0.8238   |   0.1078   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0129__ |   0.0574   |   0.0768   |   0.1153   |   0.6636   |   0.5811   |   0.1516   | __0.0169__ |   1.0000   | __0.0000__ |   0.8145   |   1.0000   |   1.0000   |   0.3323   |   1.0000   |   0.4807   | __0.0192__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0063__ | __0.0386__ |   0.0574   |   0.0963   |   0.6476   |   0.5811   |   0.1338   | __0.0118__ |   1.0000   | __0.0000__ |   0.8036   |   1.0000   |   1.0000   |   0.3018   |   1.0000   |   0.4545   | __0.0127__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0007__ | __0.0044__ | __0.0072__ |   0.5811   |   0.8036   |   0.7905   |   0.6291   |   0.1185   |   0.2266   | __0.0000__ |   0.6476   |   0.3323   |   0.3018   |   1.0000   |   0.2668   |   1.0000   |   0.1796   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0309__ |   0.1338   |   0.1516   |   0.1338   |   0.6636   |   0.6291   |   0.1338   | __0.0227__ |   1.0000   | __0.0000__ |   0.8388   |   1.0000   |   1.0000   |   0.2668   |   1.0000   |   0.5034   | __0.0192__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0026__ | __0.0075__ | __0.0169__ |   0.4545   |   1.0000   |   1.0000   |   0.5235   |   0.0963   |   0.4240   | __0.0000__ |   0.8238   |   0.4807   |   0.4545   |   1.0000   |   0.5034   |   1.0000   |   0.1435   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0002__ | __0.0003__ |   0.6476   |   0.1153   |   0.0963   |   0.6776   |   1.0000   | __0.0010__ | __0.0000__ |   0.1078   | __0.0192__ | __0.0127__ |   0.1796   | __0.0192__ |   0.1435   |   1.0000   |

<a name="table11"></a>Table 11: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_accuracy1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_accuracy2.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure23"></a>Figure 23: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure24"></a>Figure 24: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure25"></a>Figure 25: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure26"></a>Figure 26: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure27"></a>Figure 27: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure28"></a>Figure 28: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean Accuracy<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean Accuracy<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0178   | __0.3321__ |   0.0092   | __0.0843__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0251   |   0.3390   |   0.0090   |   0.1093   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0402   |   0.3517   |   0.0150   |   0.1248   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   -0.0100   |   0.3579   |   0.0132   |   0.0946   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __-0.0042__ |   0.3690   |   0.0138   |   0.0918   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.0633   |   0.3835   |   0.0002   |   0.1433   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0136   |   0.4133   |   0.0147   |   0.0950   |
| [schreiber2014/default](#schreiber2014default)     |   -0.1485   |   0.4165   | __0.0002__ |   0.1083   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0366   |   0.4218   |   0.0096   |   0.1268   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0908   |   0.4244   |   0.0117   |   0.1149   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.0050   |   0.4379   |   -0.0005   |   0.1391   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.1828   |   0.4396   |   0.0009   |   0.1036   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1669   |   0.4416   |   0.0095   |   0.1098   |
| [percival2014/stem](#percival2014stem)             |   -0.0826   |   0.4537   |   0.0165   |   0.1003   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1249   |   0.4554   |   0.0099   |   0.1200   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.0182   |   0.5383   |   0.0189   |   0.1088   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.0452   |   0.5400   |   0.0256   |   0.1798   |

<a name="table12"></a>Table 12: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/hainsworth_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hainsworth_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hainsworth_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure35"></a>Figure 35: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure36"></a>Figure 36: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0332   | __0.3376__ |   -0.0035   | __0.0612__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0098   |   0.3512   |   -0.0018   |   0.0976   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0249   |   0.3575   | __-0.0003__ |   0.1097   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   -0.0254   |   0.3737   |   -0.0021   |   0.0711   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.0480   |   0.3851   |   0.0029   |   0.1337   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.0196   |   0.3865   |   -0.0015   |   0.0681   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0213   |   0.4203   |   -0.0057   |   0.1104   |
| [schreiber2014/default](#schreiber2014default)     |   -0.1638   |   0.4234   |   -0.0106   |   0.0995   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __-0.0017__ |   0.4235   |   0.0039   |   0.0750   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1515   |   0.4353   |   0.0085   |   0.1013   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1061   |   0.4372   |   0.0009   |   0.0961   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.1981   |   0.4434   |   -0.0054   |   0.0916   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.0203   |   0.4444   |   -0.0068   |   0.1232   |
| [percival2014/stem](#percival2014stem)             |   -0.0979   |   0.4600   |   0.0102   |   0.0831   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1403   |   0.4666   |   -0.0010   |   0.1050   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.0610   |   0.5405   |   0.0239   |   0.1732   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.0336   |   0.5414   |   0.0081   |   0.0896   |

<a name="table13"></a>Table 13: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/hainsworth_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hainsworth_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hainsworth_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure37"></a>Figure 37: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure38"></a>Figure 38: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 3.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0342   | __0.3365__ |   -0.0046   | __0.0615__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0087   |   0.3481   |   -0.0029   |   0.0960   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0238   |   0.3559   |   0.0031   |   0.1099   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   -0.0264   |   0.3721   |   -0.0031   |   0.0709   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.0469   |   0.3828   |   0.0018   |   0.1350   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.0206   |   0.3841   |   -0.0026   |   0.0691   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0202   |   0.4177   |   -0.0068   |   0.1106   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __-0.0028__ |   0.4193   |   0.0028   |   0.0758   |
| [schreiber2014/default](#schreiber2014default)     |   -0.1649   |   0.4221   |   -0.0117   |   0.0997   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1505   |   0.4324   |   0.0074   |   0.1005   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1072   |   0.4349   | __-0.0002__ |   0.0956   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.0214   |   0.4411   |   -0.0079   |   0.1262   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.1993   |   0.4417   |   -0.0066   |   0.0913   |
| [percival2014/stem](#percival2014stem)             |   -0.0989   |   0.4568   |   0.0092   |   0.0810   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1413   |   0.4656   |   -0.0020   |   0.1059   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.0346   |   0.5384   |   0.0070   |   0.0904   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.0621   |   0.5388   |   0.0228   |   0.1736   |

<a name="table14"></a>Table 14: Mean OE1/OE2 for estimates compared to version [3.0](#30) ordered by standard deviation.

[CSV](data/hainsworth_estimates_3.0_moe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_moe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_moe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hainsworth_estimates_3.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hainsworth_estimates_3.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_distribution_oe1.svg">
</figure>

<a name="figure39"></a>Figure 39: OE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_3.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_distribution_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_distribution_oe2.svg">
</figure>

<a name="figure40"></a>Figure 40: OE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_3.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_distribution_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5938   |   0.7672   | __0.0000__ | __0.0000__ |   0.9913   |   0.0677   | __0.0026__ | __0.0341__ |   0.4576   | __0.0000__ | __0.0153__ | __0.0018__ | __0.0208__ |   0.2878   |   0.0625   |   0.6677   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5938   |   1.0000   |   0.7486   | __0.0000__ | __0.0000__ |   0.7105   |   0.1644   | __0.0096__ | __0.0063__ |   0.2050   | __0.0000__ | __0.0008__ | __0.0001__ |   0.0745   |   0.5399   |   0.1978   |   0.9777   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.7672   |   0.7486   |   1.0000   | __0.0000__ | __0.0000__ |   0.8269   |   0.1139   | __0.0047__ | __0.0114__ |   0.2685   | __0.0000__ | __0.0026__ | __0.0001__ | __0.0393__ |   0.4422   |   0.1235   |   0.8561   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0010__ |   0.2335   | __0.0010__ | __0.0488__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.9913   |   0.7105   |   0.8269   | __0.0000__ | __0.0000__ |   1.0000   | __0.0495__ | __0.0072__ | __0.0355__ |   0.3517   | __0.0000__ | __0.0466__ | __0.0119__ |   0.0839   |   0.3557   |   0.2170   |   0.6674   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0677   |   0.1644   |   0.1139   | __0.0000__ | __0.0000__ | __0.0495__ |   1.0000   |   0.1107   | __0.0000__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8964   |   0.4430   |   0.6348   |   0.0621   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0026__ | __0.0096__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0072__ |   0.1107   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3292   |   0.0826   |   0.0809   | __0.0010__ |
| [percival2014/stem](#percival2014stem)             | __0.0341__ | __0.0063__ | __0.0114__ | __0.0000__ | __0.0007__ | __0.0355__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3064   | __0.0075__ |   0.7640   |   0.2000   | __0.0000__ | __0.0019__ | __0.0000__ | __0.0015__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4576   |   0.2050   |   0.2685   | __0.0000__ | __0.0010__ |   0.3517   | __0.0047__ | __0.0001__ |   0.3064   |   1.0000   | __0.0058__ |   0.2376   |   0.0591   | __0.0078__ |   0.1425   | __0.0348__ |   0.1864   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2335   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0075__ | __0.0058__ |   1.0000   | __0.0350__ |   0.4504   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0153__ | __0.0008__ | __0.0026__ | __0.0000__ | __0.0010__ | __0.0466__ | __0.0000__ | __0.0000__ |   0.7640   |   0.2376   | __0.0350__ |   1.0000   |   0.1374   | __0.0000__ | __0.0008__ | __0.0000__ | __0.0035__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0018__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0488__ | __0.0119__ | __0.0000__ | __0.0000__ |   0.2000   |   0.0591   |   0.4504   |   0.1374   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0004__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0208__ |   0.0745   | __0.0393__ | __0.0000__ | __0.0000__ |   0.0839   |   0.8964   |   0.3292   | __0.0000__ | __0.0078__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2661   |   0.4333   |   0.1130   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2878   |   0.5399   |   0.4422   | __0.0000__ | __0.0000__ |   0.3557   |   0.4430   |   0.0826   | __0.0019__ |   0.1425   | __0.0000__ | __0.0008__ | __0.0001__ |   0.2661   |   1.0000   |   0.6005   |   0.5287   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0625   |   0.1978   |   0.1235   | __0.0000__ | __0.0000__ |   0.2170   |   0.6348   |   0.0809   | __0.0000__ | __0.0348__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4333   |   0.6005   |   1.0000   |   0.2161   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6677   |   0.9777   |   0.8561   | __0.0000__ | __0.0000__ |   0.6674   |   0.0621   | __0.0010__ | __0.0015__ |   0.1864   | __0.0000__ | __0.0035__ | __0.0004__ |   0.1130   |   0.5287   |   0.2161   |   1.0000   |

<a name="table15"></a>Table 15: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5938   |   0.7672   | __0.0000__ | __0.0000__ |   0.9913   |   0.0677   | __0.0026__ | __0.0341__ |   0.4576   | __0.0000__ | __0.0153__ | __0.0018__ | __0.0208__ |   0.2878   |   0.0625   |   0.6677   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5938   |   1.0000   |   0.7486   | __0.0000__ | __0.0000__ |   0.7105   |   0.1644   | __0.0096__ | __0.0063__ |   0.2050   | __0.0000__ | __0.0008__ | __0.0001__ |   0.0745   |   0.5399   |   0.1978   |   0.9777   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.7672   |   0.7486   |   1.0000   | __0.0000__ | __0.0000__ |   0.8269   |   0.1139   | __0.0047__ | __0.0114__ |   0.2685   | __0.0000__ | __0.0026__ | __0.0001__ | __0.0393__ |   0.4422   |   0.1235   |   0.8561   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0010__ |   0.2335   | __0.0010__ | __0.0488__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.9913   |   0.7105   |   0.8269   | __0.0000__ | __0.0000__ |   1.0000   | __0.0495__ | __0.0072__ | __0.0355__ |   0.3517   | __0.0000__ | __0.0466__ | __0.0119__ |   0.0839   |   0.3557   |   0.2170   |   0.6674   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0677   |   0.1644   |   0.1139   | __0.0000__ | __0.0000__ | __0.0495__ |   1.0000   |   0.1107   | __0.0000__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8964   |   0.4430   |   0.6348   |   0.0621   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0026__ | __0.0096__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0072__ |   0.1107   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3292   |   0.0826   |   0.0809   | __0.0010__ |
| [percival2014/stem](#percival2014stem)             | __0.0341__ | __0.0063__ | __0.0114__ | __0.0000__ | __0.0007__ | __0.0355__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3064   | __0.0075__ |   0.7640   |   0.2000   | __0.0000__ | __0.0019__ | __0.0000__ | __0.0015__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4576   |   0.2050   |   0.2685   | __0.0000__ | __0.0010__ |   0.3517   | __0.0047__ | __0.0001__ |   0.3064   |   1.0000   | __0.0058__ |   0.2376   |   0.0591   | __0.0078__ |   0.1425   | __0.0348__ |   0.1864   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2335   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0075__ | __0.0058__ |   1.0000   | __0.0350__ |   0.4504   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0153__ | __0.0008__ | __0.0026__ | __0.0000__ | __0.0010__ | __0.0466__ | __0.0000__ | __0.0000__ |   0.7640   |   0.2376   | __0.0350__ |   1.0000   |   0.1374   | __0.0000__ | __0.0008__ | __0.0000__ | __0.0035__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0018__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0488__ | __0.0119__ | __0.0000__ | __0.0000__ |   0.2000   |   0.0591   |   0.4504   |   0.1374   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0004__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0208__ |   0.0745   | __0.0393__ | __0.0000__ | __0.0000__ |   0.0839   |   0.8964   |   0.3292   | __0.0000__ | __0.0078__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2661   |   0.4333   |   0.1130   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2878   |   0.5399   |   0.4422   | __0.0000__ | __0.0000__ |   0.3557   |   0.4430   |   0.0826   | __0.0019__ |   0.1425   | __0.0000__ | __0.0008__ | __0.0001__ |   0.2661   |   1.0000   |   0.6005   |   0.5287   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0625   |   0.1978   |   0.1235   | __0.0000__ | __0.0000__ |   0.2170   |   0.6348   |   0.0809   | __0.0000__ | __0.0348__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4333   |   0.6005   |   1.0000   |   0.2161   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6677   |   0.9777   |   0.8561   | __0.0000__ | __0.0000__ |   0.6674   |   0.0621   | __0.0010__ | __0.0015__ |   0.1864   | __0.0000__ | __0.0035__ | __0.0004__ |   0.1130   |   0.5287   |   0.2161   |   1.0000   |

<a name="table16"></a>Table 16: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5938   |   0.7672   | __0.0000__ | __0.0000__ |   0.9913   |   0.0677   | __0.0026__ | __0.0341__ |   0.4576   | __0.0000__ | __0.0153__ | __0.0018__ | __0.0208__ |   0.2878   |   0.0625   |   0.6677   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5938   |   1.0000   |   0.7486   | __0.0000__ | __0.0000__ |   0.7105   |   0.1644   | __0.0096__ | __0.0063__ |   0.2050   | __0.0000__ | __0.0008__ | __0.0001__ |   0.0745   |   0.5399   |   0.1978   |   0.9777   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.7672   |   0.7486   |   1.0000   | __0.0000__ | __0.0000__ |   0.8269   |   0.1139   | __0.0047__ | __0.0114__ |   0.2685   | __0.0000__ | __0.0026__ | __0.0001__ | __0.0393__ |   0.4422   |   0.1235   |   0.8561   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0010__ |   0.2335   | __0.0010__ | __0.0488__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.9913   |   0.7105   |   0.8269   | __0.0000__ | __0.0000__ |   1.0000   | __0.0495__ | __0.0072__ | __0.0355__ |   0.3517   | __0.0000__ | __0.0466__ | __0.0119__ |   0.0839   |   0.3557   |   0.2170   |   0.6674   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.0677   |   0.1644   |   0.1139   | __0.0000__ | __0.0000__ | __0.0495__ |   1.0000   |   0.1107   | __0.0000__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8964   |   0.4430   |   0.6348   |   0.0621   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0026__ | __0.0096__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0072__ |   0.1107   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3292   |   0.0826   |   0.0809   | __0.0010__ |
| [percival2014/stem](#percival2014stem)             | __0.0341__ | __0.0063__ | __0.0114__ | __0.0000__ | __0.0007__ | __0.0355__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3064   | __0.0075__ |   0.7640   |   0.2000   | __0.0000__ | __0.0019__ | __0.0000__ | __0.0015__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4576   |   0.2050   |   0.2685   | __0.0000__ | __0.0010__ |   0.3517   | __0.0047__ | __0.0001__ |   0.3064   |   1.0000   | __0.0058__ |   0.2376   |   0.0591   | __0.0078__ |   0.1425   | __0.0348__ |   0.1864   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2335   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0075__ | __0.0058__ |   1.0000   | __0.0350__ |   0.4504   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0153__ | __0.0008__ | __0.0026__ | __0.0000__ | __0.0010__ | __0.0466__ | __0.0000__ | __0.0000__ |   0.7640   |   0.2376   | __0.0350__ |   1.0000   |   0.1374   | __0.0000__ | __0.0008__ | __0.0000__ | __0.0035__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0018__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0488__ | __0.0119__ | __0.0000__ | __0.0000__ |   0.2000   |   0.0591   |   0.4504   |   0.1374   |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0004__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0208__ |   0.0745   | __0.0393__ | __0.0000__ | __0.0000__ |   0.0839   |   0.8964   |   0.3292   | __0.0000__ | __0.0078__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2661   |   0.4333   |   0.1130   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2878   |   0.5399   |   0.4422   | __0.0000__ | __0.0000__ |   0.3557   |   0.4430   |   0.0826   | __0.0019__ |   0.1425   | __0.0000__ | __0.0008__ | __0.0001__ |   0.2661   |   1.0000   |   0.6005   |   0.5287   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0625   |   0.1978   |   0.1235   | __0.0000__ | __0.0000__ |   0.2170   |   0.6348   |   0.0809   | __0.0000__ | __0.0348__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4333   |   0.6005   |   1.0000   |   0.2161   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6677   |   0.9777   |   0.8561   | __0.0000__ | __0.0000__ |   0.6674   |   0.0621   | __0.0010__ | __0.0015__ |   0.1864   | __0.0000__ | __0.0035__ | __0.0004__ |   0.1130   |   0.5287   |   0.2161   |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3130   |   0.3172   |   0.9645   |   0.2667   |   0.1958   |   0.9588   |   0.3735   |   0.2712   |   0.2077   |   0.2162   |   0.7056   |   0.9208   |   0.4597   |   0.4862   |   0.9792   |   0.3027   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.3130   |   1.0000   |   0.8774   |   0.6401   |   0.1176   |   0.4638   |   0.6059   |   0.1784   |   0.6925   |   0.4067   |   0.0741   |   0.7705   |   0.5394   |   0.8701   |   0.9070   |   0.5250   |   0.1235   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.3172   |   0.8774   |   1.0000   |   0.6741   |   0.0916   |   0.4501   |   0.6344   |   0.2038   |   0.6330   |   0.3691   |   0.0761   |   0.8055   |   0.5923   |   0.8267   |   0.8564   |   0.6069   |   0.1459   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.9645   |   0.6401   |   0.6741   |   1.0000   |   0.2750   |   0.2925   |   0.9967   |   0.3551   |   0.4907   |   0.2803   |   0.3580   |   0.8176   |   0.9732   |   0.6158   |   0.5626   |   0.9480   |   0.3809   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2667   |   0.1176   |   0.0916   |   0.2750   |   1.0000   | __0.0265__ |   0.3708   |   0.8338   |   0.0632   |   0.0648   |   0.9395   |   0.1327   |   0.3018   |   0.1642   |   0.1410   |   0.4892   |   0.7348   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1958   |   0.4638   |   0.4501   |   0.2925   | __0.0265__ |   1.0000   |   0.3049   |   0.0531   |   0.7723   |   0.6182   | __0.0394__ |   0.3670   |   0.2816   |   0.6248   |   0.6293   |   0.2500   | __0.0464__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.9588   |   0.6059   |   0.6344   |   0.9967   |   0.3708   |   0.3049   |   1.0000   |   0.4537   |   0.4561   |   0.2315   |   0.3106   |   0.8123   |   0.9757   |   0.6024   |   0.6133   |   0.9517   |   0.3130   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3735   |   0.1784   |   0.2038   |   0.3551   |   0.8338   |   0.0531   |   0.4537   |   1.0000   |   0.1193   |   0.0729   |   0.9963   |   0.2679   |   0.3669   |   0.1840   |   0.2229   |   0.4451   |   0.9452   |
| [percival2014/stem](#percival2014stem)             |   0.2712   |   0.6925   |   0.6330   |   0.4907   |   0.0632   |   0.7723   |   0.4561   |   0.1193   |   1.0000   |   0.5529   | __0.0278__ |   0.5084   |   0.3971   |   0.8589   |   0.8297   |   0.3998   |   0.0921   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.2077   |   0.4067   |   0.3691   |   0.2803   |   0.0648   |   0.6182   |   0.2315   |   0.0729   |   0.5529   |   1.0000   |   0.0604   |   0.3219   |   0.2407   |   0.4966   |   0.5532   |   0.2625   | __0.0342__ |
| [schreiber2014/default](#schreiber2014default)     |   0.2162   |   0.0741   |   0.0761   |   0.3580   |   0.9395   | __0.0394__ |   0.3106   |   0.9963   | __0.0278__ |   0.0604   |   1.0000   |   0.1791   |   0.2454   |   0.1183   |   0.0728   |   0.3575   |   0.9420   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7056   |   0.7705   |   0.8055   |   0.8176   |   0.1327   |   0.3670   |   0.8123   |   0.2679   |   0.5084   |   0.3219   |   0.1791   |   1.0000   |   0.7501   |   0.6886   |   0.7298   |   0.7602   |   0.2305   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9208   |   0.5394   |   0.5923   |   0.9732   |   0.3018   |   0.2816   |   0.9757   |   0.3669   |   0.3971   |   0.2407   |   0.2454   |   0.7501   |   1.0000   |   0.5770   |   0.5967   |   0.9170   |   0.2765   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4597   |   0.8701   |   0.8267   |   0.6158   |   0.1642   |   0.6248   |   0.6024   |   0.1840   |   0.8589   |   0.4966   |   0.1183   |   0.6886   |   0.5770   |   1.0000   |   0.9670   |   0.4497   |   0.1689   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.4862   |   0.9070   |   0.8564   |   0.5626   |   0.1410   |   0.6293   |   0.6133   |   0.2229   |   0.8297   |   0.5532   |   0.0728   |   0.7298   |   0.5967   |   0.9670   |   1.0000   |   0.3957   |   0.1688   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9792   |   0.5250   |   0.6069   |   0.9480   |   0.4892   |   0.2500   |   0.9517   |   0.4451   |   0.3998   |   0.2625   |   0.3575   |   0.7602   |   0.9170   |   0.4497   |   0.3957   |   1.0000   |   0.4232   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3027   |   0.1235   |   0.1459   |   0.3809   |   0.7348   | __0.0464__ |   0.3130   |   0.9452   |   0.0921   | __0.0342__ |   0.9420   |   0.2305   |   0.2765   |   0.1689   |   0.1688   |   0.4232   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5828   |   0.6174   |   0.0540   |   0.7574   |   0.0678   |   0.7561   |   0.4967   | __0.0145__ | __0.0204__ |   0.2464   |   0.4697   |   0.6796   |   0.6627   |   0.2139   |   0.7983   |   0.6877   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5828   |   1.0000   |   0.8774   |   0.1604   |   0.7759   |   0.1325   |   0.6059   |   0.6504   |   0.0752   | __0.0409__ |   0.1939   |   0.7240   |   0.9262   |   0.8701   |   0.3899   |   0.9603   |   0.5350   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6174   |   0.8774   |   1.0000   |   0.1183   |   0.6196   |   0.1413   |   0.6344   |   0.6196   | __0.0367__ | __0.0314__ |   0.2022   |   0.6270   |   0.8598   |   0.8267   |   0.3613   |   0.9755   |   0.5851   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0540   |   0.1604   |   0.1183   |   1.0000   | __0.0480__ |   0.9614   |   0.0909   |   0.6117   |   0.8248   |   0.2332   | __0.0357__ |   0.3838   |   0.2754   |   0.3368   |   0.5510   |   0.1703   |   0.1196   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.7574   |   0.7759   |   0.6196   | __0.0480__ |   1.0000   |   0.1280   |   0.9844   |   0.5174   |   0.0600   | __0.0198__ |   0.5478   |   0.3465   |   0.6479   |   0.6167   |   0.2098   |   0.8044   |   0.7065   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0678   |   0.1325   |   0.1413   |   0.9614   |   0.1280   |   1.0000   |   0.0893   |   0.5487   |   0.7994   |   0.1868   | __0.0211__ |   0.3254   |   0.2450   |   0.2863   |   0.5466   |   0.1577   |   0.0748   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7561   |   0.6059   |   0.6344   |   0.0909   |   0.9844   |   0.0893   |   1.0000   |   0.4294   |   0.0695   | __0.0195__ |   0.5780   |   0.4397   |   0.5771   |   0.6024   |   0.2936   |   0.6748   |   0.9085   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4967   |   0.6504   |   0.6196   |   0.6117   |   0.5174   |   0.5487   |   0.4294   |   1.0000   |   0.5189   |   0.1586   |   0.2027   |   0.8259   |   0.7071   |   0.7632   |   0.9255   |   0.6612   |   0.3737   |
| [percival2014/stem](#percival2014stem)             | __0.0145__ |   0.0752   | __0.0367__ |   0.8248   |   0.0600   |   0.7994   |   0.0695   |   0.5189   |   1.0000   |   0.3388   | __0.0059__ |   0.1796   |   0.1400   |   0.2460   |   0.3643   |   0.1360   |   0.0847   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0204__ | __0.0409__ | __0.0314__ |   0.2332   | __0.0198__ |   0.1868   | __0.0195__ |   0.1586   |   0.3388   |   1.0000   | __0.0073__ |   0.0745   | __0.0438__ |   0.0670   |   0.1632   | __0.0429__ | __0.0110__ |
| [schreiber2014/default](#schreiber2014default)     |   0.2464   |   0.1939   |   0.2022   | __0.0357__ |   0.5478   | __0.0211__ |   0.5780   |   0.2027   | __0.0059__ | __0.0073__ |   1.0000   |   0.1517   |   0.2131   |   0.2511   |   0.0509   |   0.3291   |   0.6997   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4697   |   0.7240   |   0.6270   |   0.3838   |   0.3465   |   0.3254   |   0.4397   |   0.8259   |   0.1796   |   0.0745   |   0.1517   |   1.0000   |   0.7501   |   0.8829   |   0.6894   |   0.7425   |   0.4464   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6796   |   0.9262   |   0.8598   |   0.2754   |   0.6479   |   0.2450   |   0.5771   |   0.7071   |   0.1400   | __0.0438__ |   0.2131   |   0.7501   |   1.0000   |   0.9432   |   0.5486   |   0.9099   |   0.5359   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6627   |   0.8701   |   0.8267   |   0.3368   |   0.6167   |   0.2863   |   0.6024   |   0.7632   |   0.2460   |   0.0670   |   0.2511   |   0.8829   |   0.9432   |   1.0000   |   0.5661   |   0.8198   |   0.5750   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2139   |   0.3899   |   0.3613   |   0.5510   |   0.2098   |   0.5466   |   0.2936   |   0.9255   |   0.3643   |   0.1632   |   0.0509   |   0.6894   |   0.5486   |   0.5661   |   1.0000   |   0.3957   |   0.2714   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7983   |   0.9603   |   0.9755   |   0.1703   |   0.8044   |   0.1577   |   0.6748   |   0.6612   |   0.1360   | __0.0429__ |   0.3291   |   0.7425   |   0.9099   |   0.8198   |   0.3957   |   1.0000   |   0.6070   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6877   |   0.5350   |   0.5851   |   0.1196   |   0.7065   |   0.0748   |   0.9085   |   0.3737   |   0.0847   | __0.0110__ |   0.6997   |   0.4464   |   0.5359   |   0.5750   |   0.2714   |   0.6070   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5828   |   0.6174   |   0.0540   |   0.7574   |   0.0678   |   0.7561   |   0.4629   | __0.0145__ | __0.0204__ |   0.2464   |   0.4697   |   0.6796   |   0.3168   |   0.2139   |   0.7983   |   0.6877   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.5828   |   1.0000   |   0.8774   |   0.1604   |   0.7759   |   0.1325   |   0.6059   |   0.6258   |   0.0752   | __0.0409__ |   0.1939   |   0.7240   |   0.9262   |   0.4723   |   0.3899   |   0.9603   |   0.5350   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.6174   |   0.8774   |   1.0000   |   0.1183   |   0.6196   |   0.1413   |   0.6344   |   0.5933   | __0.0367__ | __0.0314__ |   0.2022   |   0.6270   |   0.8598   |   0.4325   |   0.3613   |   0.9755   |   0.5851   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0540   |   0.1604   |   0.1183   |   1.0000   | __0.0480__ |   0.9614   |   0.0909   |   0.5583   |   0.8248   |   0.2332   | __0.0357__ |   0.3838   |   0.2754   |   0.6543   |   0.5510   |   0.1703   |   0.1196   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.7574   |   0.7759   |   0.6196   | __0.0480__ |   1.0000   |   0.1280   |   0.9844   |   0.4789   |   0.0600   | __0.0198__ |   0.5478   |   0.3465   |   0.6479   |   0.3465   |   0.2098   |   0.8044   |   0.7065   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0678   |   0.1325   |   0.1413   |   0.9614   |   0.1280   |   1.0000   |   0.0893   |   0.5614   |   0.7994   |   0.1868   | __0.0211__ |   0.3254   |   0.2450   |   0.6367   |   0.5466   |   0.1577   |   0.0748   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7561   |   0.6059   |   0.6344   |   0.0909   |   0.9844   |   0.0893   |   1.0000   |   0.4460   |   0.0695   | __0.0195__ |   0.5780   |   0.4397   |   0.5771   |   0.3428   |   0.2936   |   0.6748   |   0.9085   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4629   |   0.6258   |   0.5933   |   0.5583   |   0.4789   |   0.5614   |   0.4460   |   1.0000   |   0.5029   |   0.1451   |   0.2069   |   0.8336   |   0.6947   |   0.9053   |   0.9257   |   0.6264   |   0.4063   |
| [percival2014/stem](#percival2014stem)             | __0.0145__ |   0.0752   | __0.0367__ |   0.8248   |   0.0600   |   0.7994   |   0.0695   |   0.5029   |   1.0000   |   0.3388   | __0.0059__ |   0.1796   |   0.1400   |   0.4484   |   0.3643   |   0.1360   |   0.0847   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0204__ | __0.0409__ | __0.0314__ |   0.2332   | __0.0198__ |   0.1868   | __0.0195__ |   0.1451   |   0.3388   |   1.0000   | __0.0073__ |   0.0745   | __0.0438__ |   0.1537   |   0.1632   | __0.0429__ | __0.0110__ |
| [schreiber2014/default](#schreiber2014default)     |   0.2464   |   0.1939   |   0.2022   | __0.0357__ |   0.5478   | __0.0211__ |   0.5780   |   0.2069   | __0.0059__ | __0.0073__ |   1.0000   |   0.1517   |   0.2131   |   0.1064   |   0.0509   |   0.3291   |   0.6997   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4697   |   0.7240   |   0.6270   |   0.3838   |   0.3465   |   0.3254   |   0.4397   |   0.8336   |   0.1796   |   0.0745   |   0.1517   |   1.0000   |   0.7501   |   0.7085   |   0.6894   |   0.7425   |   0.4464   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6796   |   0.9262   |   0.8598   |   0.2754   |   0.6479   |   0.2450   |   0.5771   |   0.6947   |   0.1400   | __0.0438__ |   0.2131   |   0.7501   |   1.0000   |   0.5977   |   0.5486   |   0.9099   |   0.5359   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3168   |   0.4723   |   0.4325   |   0.6543   |   0.3465   |   0.6367   |   0.3428   |   0.9053   |   0.4484   |   0.1537   |   0.1064   |   0.7085   |   0.5977   |   1.0000   |   0.9629   |   0.4377   |   0.3610   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2139   |   0.3899   |   0.3613   |   0.5510   |   0.2098   |   0.5466   |   0.2936   |   0.9257   |   0.3643   |   0.1632   |   0.0509   |   0.6894   |   0.5486   |   0.9629   |   1.0000   |   0.3957   |   0.2714   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7983   |   0.9603   |   0.9755   |   0.1703   |   0.8044   |   0.1577   |   0.6748   |   0.6264   |   0.1360   | __0.0429__ |   0.3291   |   0.7425   |   0.9099   |   0.4377   |   0.3957   |   1.0000   |   0.6070   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6877   |   0.5350   |   0.5851   |   0.1196   |   0.7065   |   0.0748   |   0.9085   |   0.4063   |   0.0847   | __0.0110__ |   0.6997   |   0.4464   |   0.5359   |   0.3610   |   0.2714   |   0.6070   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_oe1.svg">
</figure>

<a name="figure43"></a>Figure 43: Mean OE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure45"></a>Figure 45: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_oe2.svg">
</figure>

<a name="figure46"></a>Figure 46: Mean OE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure47"></a>Figure 47: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure48"></a>Figure 48: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_oe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean OE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_oe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean OE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure53"></a>Figure 53: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure54"></a>Figure 54: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_oe1.svg">
</figure>

<a name="figure55"></a>Figure 55: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure56"></a>Figure 56: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure57"></a>Figure 57: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_oe2.svg">
</figure>

<a name="figure58"></a>Figure 58: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure59"></a>Figure 59: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_oe1.svg">
</figure>

<a name="figure60"></a>Figure 60: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_oe1.svg">
</figure>

<a name="figure61"></a>Figure 61: OE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_oe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_oe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure62"></a>Figure 62: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_oe2.svg">
</figure>

<a name="figure63"></a>Figure 63: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_oe2.svg">
</figure>

<a name="figure64"></a>Figure 64: OE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_oe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_oe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.1277__ | __0.3071__ | __0.0323__ | __0.0784__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1437   |   0.3080   |   0.0459   |   0.0996   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1440   |   0.3278   |   0.0341   |   0.0893   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1508   |   0.3368   |   0.0328   |   0.0868   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1555   |   0.3180   |   0.0519   |   0.1144   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1804   |   0.3720   |   0.0392   |   0.0878   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.1940   |   0.3368   |   0.0661   |   0.1271   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2083   |   0.3808   |   0.0465   |   0.1057   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2110   |   0.3670   |   0.0526   |   0.1158   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2200   |   0.4178   |   0.0451   |   0.1117   |
| [schreiber2014/default](#schreiber2014default)     |   0.2250   |   0.3807   |   0.0438   |   0.0991   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2261   |   0.3750   |   0.0583   |   0.1263   |
| [percival2014/stem](#percival2014stem)             |   0.2357   |   0.3964   |   0.0384   |   0.0941   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2413   |   0.4057   |   0.0584   |   0.0934   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2493   |   0.4055   |   0.0405   |   0.0954   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2992   |   0.4479   |   0.0434   |   0.1015   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3447   |   0.4182   |   0.1016   |   0.1506   |

<a name="table21"></a>Table 21: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/hainsworth_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hainsworth_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hainsworth_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure65"></a>Figure 65: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure66"></a>Figure 66: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.1246__ | __0.3156__ |   0.0217   | __0.0573__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1439   |   0.3205   |   0.0376   |   0.0901   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1460   |   0.3449   |   0.0221   |   0.0676   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1506   |   0.3252   |   0.0420   |   0.1013   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1541   |   0.3550   | __0.0210__ |   0.0648   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1814   |   0.3827   |   0.0290   |   0.0693   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.1884   |   0.3392   |   0.0584   |   0.1203   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2036   |   0.3683   |   0.0416   |   0.1024   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2118   |   0.3970   |   0.0339   |   0.0900   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2233   |   0.4331   |   0.0334   |   0.0996   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2261   |   0.3831   |   0.0470   |   0.1141   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2297   |   0.3996   |   0.0505   |   0.0882   |
| [schreiber2014/default](#schreiber2014default)     |   0.2304   |   0.3912   |   0.0361   |   0.0934   |
| [percival2014/stem](#percival2014stem)             |   0.2369   |   0.4063   |   0.0266   |   0.0794   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2514   |   0.4155   |   0.0335   |   0.0854   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2964   |   0.4543   |   0.0324   |   0.0840   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3435   |   0.4218   |   0.0953   |   0.1466   |

<a name="table22"></a>Table 22: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/hainsworth_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hainsworth_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hainsworth_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure67"></a>Figure 67: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure68"></a>Figure 68: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 3.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.1243__ | __0.3146__ |   0.0218   | __0.0577__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1422   |   0.3178   |   0.0377   |   0.0884   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1455   |   0.3435   |   0.0223   |   0.0673   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1504   |   0.3234   |   0.0428   |   0.1013   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1536   |   0.3526   | __0.0218__ |   0.0657   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1801   |   0.3787   |   0.0299   |   0.0698   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.1875   |   0.3370   |   0.0592   |   0.1214   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2026   |   0.3659   |   0.0420   |   0.1025   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2111   |   0.3951   |   0.0346   |   0.0891   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2234   |   0.4323   |   0.0344   |   0.1002   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2249   |   0.3801   |   0.0491   |   0.1165   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2283   |   0.3968   |   0.0504   |   0.0872   |
| [schreiber2014/default](#schreiber2014default)     |   0.2306   |   0.3901   |   0.0372   |   0.0932   |
| [percival2014/stem](#percival2014stem)             |   0.2353   |   0.4038   |   0.0270   |   0.0769   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2514   |   0.4142   |   0.0340   |   0.0850   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2961   |   0.4510   |   0.0336   |   0.0842   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3424   |   0.4207   |   0.0955   |   0.1467   |

<a name="table23"></a>Table 23: Mean AOE1/AOE2 for estimates compared to version [3.0](#30) ordered by mean.

[CSV](data/hainsworth_estimates_3.0_maoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_maoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hainsworth_estimates_3.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hainsworth_estimates_3.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hainsworth_estimates_3.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hainsworth_estimates_3.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_distribution_aoe1.svg">
</figure>

<a name="figure69"></a>Figure 69: AOE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_3.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_distribution_aoe2.svg">
</figure>

<a name="figure70"></a>Figure 70: AOE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hainsworth_estimates_3.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3183   |   0.4767   | __0.0001__ | __0.0001__ | __0.0000__ | __0.0029__ | __0.0102__ | __0.0002__ | __0.0000__ | __0.0003__ | __0.0022__ | __0.0026__ |   0.2520   |   0.0637   |   0.4657   | __0.0004__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.3183   |   1.0000   |   0.6885   | __0.0034__ | __0.0013__ | __0.0000__ | __0.0299__ |   0.0743   | __0.0024__ | __0.0000__ | __0.0113__ | __0.0230__ | __0.0226__ |   0.8367   |   0.2850   |   0.7403   | __0.0046__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.4767   |   0.6885   |   1.0000   | __0.0011__ | __0.0005__ | __0.0000__ | __0.0155__ | __0.0340__ | __0.0011__ | __0.0000__ | __0.0058__ | __0.0135__ | __0.0094__ |   0.6135   |   0.2170   |   0.9895   | __0.0017__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0001__ | __0.0034__ | __0.0011__ |   1.0000   |   0.7607   |   0.0539   |   0.1281   | __0.0123__ |   0.8503   | __0.0010__ |   0.6292   |   0.2979   |   0.5218   | __0.0027__ |   0.0508   | __0.0002__ |   0.5185   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0001__ | __0.0013__ | __0.0005__ |   0.7607   |   1.0000   |   0.1165   |   0.2270   |   0.0732   |   0.6450   | __0.0034__ |   0.3711   |   0.1157   |   0.2505   | __0.0030__ | __0.0383__ | __0.0008__ |   0.4183   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ |   0.0539   |   0.1165   |   1.0000   | __0.0011__ | __0.0003__ | __0.0340__ |   0.2384   | __0.0142__ | __0.0062__ | __0.0203__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0107__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0029__ | __0.0299__ | __0.0155__ |   0.1281   |   0.2270   | __0.0011__ |   1.0000   |   0.2724   |   0.2784   | __0.0000__ |   0.6140   |   0.9220   |   0.7737   | __0.0336__ |   0.2745   | __0.0023__ |   0.4645   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0102__ |   0.0743   | __0.0340__ | __0.0123__ |   0.0732   | __0.0003__ |   0.2724   |   1.0000   |   0.0730   | __0.0000__ |   0.2803   |   0.5851   |   0.3812   |   0.0990   |   0.6170   | __0.0147__ |   0.0923   |
| [percival2014/stem](#percival2014stem)             | __0.0002__ | __0.0024__ | __0.0011__ |   0.8503   |   0.6450   | __0.0340__ |   0.2784   |   0.0730   |   1.0000   | __0.0002__ |   0.6548   |   0.2578   |   0.5728   | __0.0042__ |   0.0613   | __0.0003__ |   0.6778   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0034__ |   0.2384   | __0.0000__ | __0.0000__ | __0.0002__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0003__ | __0.0113__ | __0.0058__ |   0.6292   |   0.3711   | __0.0142__ |   0.6140   |   0.2803   |   0.6548   | __0.0002__ |   1.0000   |   0.5022   |   0.8588   | __0.0117__ |   0.1548   | __0.0033__ |   0.9653   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0022__ | __0.0230__ | __0.0135__ |   0.2979   |   0.1157   | __0.0062__ |   0.9220   |   0.5851   |   0.2578   | __0.0000__ |   0.5022   |   1.0000   |   0.5635   |   0.0510   |   0.3250   | __0.0076__ |   0.5011   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0026__ | __0.0226__ | __0.0094__ |   0.5218   |   0.2505   | __0.0203__ |   0.7737   |   0.3812   |   0.5728   | __0.0002__ |   0.8588   |   0.5635   |   1.0000   | __0.0306__ |   0.1818   | __0.0048__ |   0.8302   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2520   |   0.8367   |   0.6135   | __0.0027__ | __0.0030__ | __0.0000__ | __0.0336__ |   0.0990   | __0.0042__ | __0.0000__ | __0.0117__ |   0.0510   | __0.0306__ |   1.0000   |   0.2784   |   0.5194   | __0.0090__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0637   |   0.2850   |   0.2170   |   0.0508   | __0.0383__ | __0.0002__ |   0.2745   |   0.6170   |   0.0613   | __0.0000__ |   0.1548   |   0.3250   |   0.1818   |   0.2784   |   1.0000   |   0.0857   |   0.1073   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4657   |   0.7403   |   0.9895   | __0.0002__ | __0.0008__ | __0.0000__ | __0.0023__ | __0.0147__ | __0.0003__ | __0.0000__ | __0.0033__ | __0.0076__ | __0.0048__ |   0.5194   |   0.0857   |   1.0000   | __0.0003__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0004__ | __0.0046__ | __0.0017__ |   0.5185   |   0.4183   | __0.0107__ |   0.4645   |   0.0923   |   0.6778   | __0.0001__ |   0.9653   |   0.5011   |   0.8302   | __0.0090__ |   0.1073   | __0.0003__ |   1.0000   |

<a name="table24"></a>Table 24: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2161   |   0.3639   | __0.0005__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0142__ | __0.0001__ | __0.0000__ | __0.0001__ | __0.0013__ | __0.0016__ |   0.2930   | __0.0484__ |   0.3820   | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2161   |   1.0000   |   0.6403   | __0.0188__ | __0.0020__ | __0.0001__ |   0.0859   |   0.1726   | __0.0035__ | __0.0000__ | __0.0100__ | __0.0227__ | __0.0267__ |   0.8841   |   0.3384   |   0.6409   | __0.0082__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.3639   |   0.6403   |   1.0000   | __0.0066__ | __0.0008__ | __0.0000__ | __0.0440__ |   0.0835   | __0.0013__ | __0.0000__ | __0.0046__ | __0.0126__ | __0.0098__ |   0.8483   |   0.2397   |   0.9222   | __0.0025__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0005__ | __0.0188__ | __0.0066__ |   1.0000   |   0.5078   | __0.0306__ |   0.1988   | __0.0322__ |   0.8137   | __0.0003__ |   0.9837   |   0.5866   |   0.8505   | __0.0065__ |   0.1314   | __0.0014__ |   0.8816   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0020__ | __0.0008__ |   0.5078   |   1.0000   |   0.1697   |   0.1404   | __0.0464__ |   0.6304   | __0.0058__ |   0.4628   |   0.1433   |   0.2845   | __0.0021__ | __0.0399__ | __0.0009__ |   0.3887   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0001__ | __0.0000__ | __0.0306__ |   0.1697   |   1.0000   | __0.0008__ | __0.0003__ | __0.0498__ |   0.2243   | __0.0311__ | __0.0125__ | __0.0365__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0166__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0063__ |   0.0859   | __0.0440__ |   0.1988   |   0.1404   | __0.0008__ |   1.0000   |   0.3551   |   0.1568   | __0.0000__ |   0.3418   |   0.7835   |   0.5433   | __0.0491__ |   0.4473   | __0.0110__ |   0.3055   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0142__ |   0.1726   |   0.0835   | __0.0322__ | __0.0464__ | __0.0003__ |   0.3551   |   1.0000   | __0.0461__ | __0.0000__ |   0.1541   |   0.3918   |   0.2564   |   0.1053   |   0.7984   | __0.0348__ |   0.0597   |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0035__ | __0.0013__ |   0.8137   |   0.6304   | __0.0498__ |   0.1568   | __0.0461__ |   1.0000   | __0.0004__ |   0.7904   |   0.3085   |   0.6317   | __0.0028__ |   0.0644   | __0.0004__ |   0.6471   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0058__ |   0.2243   | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0004__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0001__ | __0.0100__ | __0.0046__ |   0.9837   |   0.4628   | __0.0311__ |   0.3418   |   0.1541   |   0.7904   | __0.0004__ |   1.0000   |   0.4617   |   0.8023   | __0.0047__ |   0.1249   | __0.0022__ |   0.8667   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0013__ | __0.0227__ | __0.0126__ |   0.5866   |   0.1433   | __0.0125__ |   0.7835   |   0.3918   |   0.3085   | __0.0000__ |   0.4617   |   1.0000   |   0.5926   | __0.0307__ |   0.2988   | __0.0065__ |   0.5993   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0016__ | __0.0267__ | __0.0098__ |   0.8505   |   0.2845   | __0.0365__ |   0.5433   |   0.2564   |   0.6317   | __0.0005__ |   0.8023   |   0.5926   |   1.0000   | __0.0178__ |   0.1656   | __0.0044__ |   0.9227   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2930   |   0.8841   |   0.8483   | __0.0065__ | __0.0021__ | __0.0000__ | __0.0491__ |   0.1053   | __0.0028__ | __0.0000__ | __0.0047__ | __0.0307__ | __0.0178__ |   1.0000   |   0.1861   |   0.7209   | __0.0063__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0484__ |   0.3384   |   0.2397   |   0.1314   | __0.0399__ | __0.0005__ |   0.4473   |   0.7984   |   0.0644   | __0.0000__ |   0.1249   |   0.2988   |   0.1656   |   0.1861   |   1.0000   |   0.0821   |   0.1189   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3820   |   0.6409   |   0.9222   | __0.0014__ | __0.0009__ | __0.0000__ | __0.0110__ | __0.0348__ | __0.0004__ | __0.0000__ | __0.0022__ | __0.0065__ | __0.0044__ |   0.7209   |   0.0821   |   1.0000   | __0.0004__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0082__ | __0.0025__ |   0.8816   |   0.3887   | __0.0166__ |   0.3055   |   0.0597   |   0.6471   | __0.0001__ |   0.8667   |   0.5993   |   0.9227   | __0.0063__ |   0.1189   | __0.0004__ |   1.0000   |

<a name="table25"></a>Table 25: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2192   |   0.3690   | __0.0006__ | __0.0000__ | __0.0000__ | __0.0065__ | __0.0145__ | __0.0001__ | __0.0000__ | __0.0001__ | __0.0013__ | __0.0015__ |   0.2893   |   0.0507   |   0.4143   | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2192   |   1.0000   |   0.6426   | __0.0190__ | __0.0019__ | __0.0001__ |   0.0864   |   0.1726   | __0.0037__ | __0.0000__ | __0.0092__ | __0.0229__ | __0.0249__ |   0.8935   |   0.3471   |   0.6018   | __0.0084__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.3690   |   0.6426   |   1.0000   | __0.0069__ | __0.0007__ | __0.0000__ | __0.0447__ |   0.0840   | __0.0014__ | __0.0000__ | __0.0043__ | __0.0130__ | __0.0090__ |   0.8374   |   0.2476   |   0.8793   | __0.0026__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0006__ | __0.0190__ | __0.0069__ |   1.0000   |   0.4803   | __0.0279__ |   0.2053   | __0.0334__ |   0.8179   | __0.0003__ |   0.9461   |   0.6011   |   0.8851   | __0.0073__ |   0.1305   | __0.0013__ |   0.8878   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0019__ | __0.0007__ |   0.4803   |   1.0000   |   0.1687   |   0.1300   | __0.0424__ |   0.5915   | __0.0062__ |   0.4674   |   0.1370   |   0.2862   | __0.0019__ | __0.0352__ | __0.0007__ |   0.3682   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0001__ | __0.0000__ | __0.0279__ |   0.1687   |   1.0000   | __0.0007__ | __0.0002__ | __0.0443__ |   0.2315   | __0.0314__ | __0.0116__ | __0.0365__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0145__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0065__ |   0.0864   | __0.0447__ |   0.2053   |   0.1300   | __0.0007__ |   1.0000   |   0.3602   |   0.1617   | __0.0000__ |   0.3170   |   0.7720   |   0.5189   |   0.0522   |   0.4414   | __0.0099__ |   0.3057   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0145__ |   0.1726   |   0.0840   | __0.0334__ | __0.0424__ | __0.0002__ |   0.3602   |   1.0000   | __0.0482__ | __0.0000__ |   0.1420   |   0.3850   |   0.2426   |   0.1111   |   0.7875   | __0.0310__ |   0.0591   |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0037__ | __0.0014__ |   0.8179   |   0.5915   | __0.0443__ |   0.1617   | __0.0482__ |   1.0000   | __0.0004__ |   0.8466   |   0.3246   |   0.6755   | __0.0031__ |   0.0657   | __0.0004__ |   0.6593   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0062__ |   0.2315   | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0005__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0001__ | __0.0092__ | __0.0043__ |   0.9461   |   0.4674   | __0.0314__ |   0.3170   |   0.1420   |   0.8466   | __0.0005__ |   1.0000   |   0.4413   |   0.7998   | __0.0043__ |   0.1125   | __0.0017__ |   0.8243   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0013__ | __0.0229__ | __0.0130__ |   0.6011   |   0.1370   | __0.0116__ |   0.7720   |   0.3850   |   0.3246   | __0.0000__ |   0.4413   |   1.0000   |   0.5648   | __0.0312__ |   0.2870   | __0.0057__ |   0.6128   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0015__ | __0.0249__ | __0.0090__ |   0.8851   |   0.2862   | __0.0365__ |   0.5189   |   0.2426   |   0.6755   | __0.0006__ |   0.7998   |   0.5648   |   1.0000   | __0.0171__ |   0.1515   | __0.0037__ |   0.9588   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2893   |   0.8935   |   0.8374   | __0.0073__ | __0.0019__ | __0.0000__ |   0.0522   |   0.1111   | __0.0031__ | __0.0000__ | __0.0043__ | __0.0312__ | __0.0171__ |   1.0000   |   0.1986   |   0.6613   | __0.0066__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0507   |   0.3471   |   0.2476   |   0.1305   | __0.0352__ | __0.0004__ |   0.4414   |   0.7875   |   0.0657   | __0.0000__ |   0.1125   |   0.2870   |   0.1515   |   0.1986   |   1.0000   |   0.0781   |   0.1174   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4143   |   0.6018   |   0.8793   | __0.0013__ | __0.0007__ | __0.0000__ | __0.0099__ | __0.0310__ | __0.0004__ | __0.0000__ | __0.0017__ | __0.0057__ | __0.0037__ |   0.6613   |   0.0781   |   1.0000   | __0.0003__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0084__ | __0.0026__ |   0.8878   |   0.3682   | __0.0145__ |   0.3057   |   0.0591   |   0.6593   | __0.0001__ |   0.8243   |   0.6128   |   0.9588   | __0.0066__ |   0.1174   | __0.0003__ |   1.0000   |

<a name="table26"></a>Table 26: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.9060   |   0.5168   | __0.0000__ |   0.1275   | __0.0461__ | __0.0022__ | __0.0000__ |   0.1672   | __0.0000__ | __0.0238__ | __0.0103__ | __0.0330__ | __0.0025__ |   0.1621   | __0.0198__ | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9060   |   1.0000   |   0.6816   | __0.0000__ |   0.0640   |   0.0539   | __0.0068__ | __0.0000__ |   0.2931   | __0.0000__ |   0.0750   | __0.0059__ | __0.0463__ | __0.0048__ |   0.2258   | __0.0163__ | __0.0006__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.5168   |   0.6816   |   1.0000   | __0.0000__ |   0.2677   |   0.1180   | __0.0081__ | __0.0000__ |   0.3861   | __0.0000__ |   0.0941   | __0.0216__ |   0.0717   | __0.0105__ |   0.3448   |   0.0562   | __0.0015__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0002__ | __0.0047__ |   0.2812   |   0.1873   | __0.0000__ | __0.0000__ | __0.0183__ | __0.0246__ | __0.0339__ |   0.3224   | __0.0007__ | __0.0232__ |   0.9936   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1275   |   0.0640   |   0.2677   | __0.0002__ |   1.0000   |   0.6962   | __0.0344__ | __0.0002__ |   0.7261   | __0.0000__ |   0.6212   |   0.4650   |   0.5042   |   0.0956   |   0.8139   |   0.5058   | __0.0164__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0461__ |   0.0539   |   0.1180   | __0.0047__ |   0.6962   |   1.0000   |   0.1517   | __0.0007__ |   0.3903   | __0.0000__ |   0.9594   |   0.6162   |   0.8127   |   0.1800   |   0.4263   |   0.6554   | __0.0266__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0022__ | __0.0068__ | __0.0081__ |   0.2812   | __0.0344__ |   0.1517   |   1.0000   | __0.0328__ | __0.0483__ | __0.0000__ |   0.2258   |   0.3421   |   0.2496   |   0.9375   | __0.0443__ |   0.3750   |   0.4732   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1873   | __0.0002__ | __0.0007__ | __0.0328__ |   1.0000   | __0.0000__ | __0.0030__ | __0.0047__ | __0.0017__ | __0.0013__ | __0.0401__ | __0.0008__ | __0.0024__ |   0.2674   |
| [percival2014/stem](#percival2014stem)             |   0.1672   |   0.2931   |   0.3861   | __0.0000__ |   0.7261   |   0.3903   | __0.0483__ | __0.0000__ |   1.0000   | __0.0000__ |   0.3870   |   0.1518   |   0.2931   | __0.0049__ |   0.8921   |   0.1020   | __0.0033__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0030__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0238__ |   0.0750   |   0.0941   | __0.0183__ |   0.6212   |   0.9594   |   0.2258   | __0.0047__ |   0.3870   | __0.0000__ |   1.0000   |   0.6829   |   0.8442   |   0.2252   |   0.4292   |   0.7466   |   0.0654   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0103__ | __0.0059__ | __0.0216__ | __0.0246__ |   0.4650   |   0.6162   |   0.3421   | __0.0017__ |   0.1518   | __0.0000__ |   0.6829   |   1.0000   |   0.7473   |   0.4173   |   0.2605   |   0.9264   |   0.0738   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0330__ | __0.0463__ |   0.0717   | __0.0339__ |   0.5042   |   0.8127   |   0.2496   | __0.0013__ |   0.2931   | __0.0000__ |   0.8442   |   0.7473   |   1.0000   |   0.3092   |   0.4097   |   0.8944   |   0.0581   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0025__ | __0.0048__ | __0.0105__ |   0.3224   |   0.0956   |   0.1800   |   0.9375   | __0.0401__ | __0.0049__ | __0.0000__ |   0.2252   |   0.4173   |   0.3092   |   1.0000   | __0.0493__ |   0.1908   |   0.3172   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1621   |   0.2258   |   0.3448   | __0.0007__ |   0.8139   |   0.4263   | __0.0443__ | __0.0008__ |   0.8921   | __0.0000__ |   0.4292   |   0.2605   |   0.4097   | __0.0493__ |   1.0000   |   0.2682   | __0.0067__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0198__ | __0.0163__ |   0.0562   | __0.0232__ |   0.5058   |   0.6554   |   0.3750   | __0.0024__ |   0.1020   | __0.0000__ |   0.7466   |   0.9264   |   0.8944   |   0.1908   |   0.2682   |   1.0000   |   0.0625   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0006__ | __0.0015__ |   0.9936   | __0.0164__ | __0.0266__ |   0.4732   |   0.2674   | __0.0033__ | __0.0001__ |   0.0654   |   0.0738   |   0.0581   |   0.3172   | __0.0067__ |   0.0625   |   1.0000   |

<a name="table27"></a>Table 27: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.8291   |   0.8866   | __0.0000__ | __0.0422__ |   0.0593   | __0.0023__ | __0.0000__ |   0.3065   | __0.0000__ | __0.0057__ | __0.0241__ | __0.0486__ | __0.0019__ |   0.1644   | __0.0079__ | __0.0005__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8291   |   1.0000   |   0.7342   | __0.0000__ | __0.0123__ | __0.0445__ | __0.0046__ | __0.0000__ |   0.3249   | __0.0000__ | __0.0157__ | __0.0083__ | __0.0446__ | __0.0022__ |   0.1572   | __0.0035__ | __0.0005__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8866   |   0.7342   |   1.0000   | __0.0000__ |   0.0698   |   0.0920   | __0.0051__ | __0.0000__ |   0.4078   | __0.0000__ | __0.0171__ | __0.0290__ |   0.0648   | __0.0048__ |   0.2303   | __0.0162__ | __0.0011__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0009__ | __0.0008__ |   0.1181   |   0.1561   | __0.0000__ | __0.0000__ | __0.0360__ | __0.0039__ | __0.0111__ |   0.1941   | __0.0007__ | __0.0312__ |   0.6198   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0422__ | __0.0123__ |   0.0698   | __0.0009__ |   1.0000   |   0.7802   |   0.1836   | __0.0005__ |   0.2631   | __0.0000__ |   0.7055   |   0.8053   |   0.9399   |   0.2138   |   0.4377   |   0.6496   |   0.0840   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0593   | __0.0445__ |   0.0920   | __0.0008__ |   0.7802   |   1.0000   |   0.1562   | __0.0002__ |   0.3259   | __0.0000__ |   0.6070   |   0.8167   |   0.8904   |   0.1274   |   0.5501   |   0.3844   | __0.0395__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0023__ | __0.0046__ | __0.0051__ |   0.1181   |   0.1836   |   0.1562   |   1.0000   | __0.0115__ | __0.0385__ | __0.0000__ |   0.4580   |   0.2377   |   0.2062   |   0.9621   |   0.0655   |   0.5974   |   0.5048   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1561   | __0.0005__ | __0.0002__ | __0.0115__ |   1.0000   | __0.0000__ | __0.0016__ | __0.0065__ | __0.0002__ | __0.0003__ | __0.0178__ | __0.0005__ | __0.0027__ |   0.1088   |
| [percival2014/stem](#percival2014stem)             |   0.3065   |   0.3249   |   0.4078   | __0.0000__ |   0.2631   |   0.3259   | __0.0385__ | __0.0000__ |   1.0000   | __0.0000__ |   0.1491   |   0.2293   |   0.3096   | __0.0021__ |   0.7092   | __0.0386__ | __0.0027__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0057__ | __0.0157__ | __0.0171__ | __0.0360__ |   0.7055   |   0.6070   |   0.4580   | __0.0065__ |   0.1491   | __0.0000__ |   1.0000   |   0.7438   |   0.6815   |   0.3991   |   0.2539   |   0.8290   |   0.1722   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0241__ | __0.0083__ | __0.0290__ | __0.0039__ |   0.8053   |   0.8167   |   0.2377   | __0.0002__ |   0.2293   | __0.0000__ |   0.7438   |   1.0000   |   0.9197   |   0.2382   |   0.4713   |   0.5222   |   0.0534   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0486__ | __0.0446__ |   0.0648   | __0.0111__ |   0.9399   |   0.8904   |   0.2062   | __0.0003__ |   0.3096   | __0.0000__ |   0.6815   |   0.9197   |   1.0000   |   0.2210   |   0.5493   |   0.5396   | __0.0490__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0019__ | __0.0022__ | __0.0048__ |   0.1941   |   0.2138   |   0.1274   |   0.9621   | __0.0178__ | __0.0021__ | __0.0000__ |   0.3991   |   0.2382   |   0.2210   |   1.0000   |   0.0509   |   0.3561   |   0.4262   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1644   |   0.1572   |   0.2303   | __0.0007__ |   0.4377   |   0.5501   |   0.0655   | __0.0005__ |   0.7092   | __0.0000__ |   0.2539   |   0.4713   |   0.5493   |   0.0509   |   1.0000   |   0.1582   | __0.0131__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0079__ | __0.0035__ | __0.0162__ | __0.0312__ |   0.6496   |   0.3844   |   0.5974   | __0.0027__ | __0.0386__ | __0.0000__ |   0.8290   |   0.5222   |   0.5396   |   0.3561   |   0.1582   |   1.0000   |   0.1594   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0005__ | __0.0005__ | __0.0011__ |   0.6198   |   0.0840   | __0.0395__ |   0.5048   |   0.1088   | __0.0027__ | __0.0000__ |   0.1722   |   0.0534   | __0.0490__ |   0.4262   | __0.0131__ |   0.1594   |   1.0000   |

<a name="table28"></a>Table 28: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.9840   |   0.8485   | __0.0000__ | __0.0333__ | __0.0377__ | __0.0020__ | __0.0000__ |   0.2639   | __0.0000__ | __0.0022__ | __0.0175__ | __0.0340__ | __0.0013__ |   0.1243   | __0.0069__ | __0.0002__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9840   |   1.0000   |   0.8621   | __0.0000__ | __0.0120__ | __0.0363__ | __0.0055__ | __0.0000__ |   0.3522   | __0.0000__ | __0.0124__ | __0.0088__ | __0.0411__ | __0.0022__ |   0.1500   | __0.0040__ | __0.0003__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8485   |   0.8621   |   1.0000   | __0.0000__ |   0.0586   |   0.0637   | __0.0047__ | __0.0000__ |   0.3819   | __0.0000__ | __0.0098__ | __0.0220__ | __0.0495__ | __0.0042__ |   0.1882   | __0.0156__ | __0.0006__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0012__ | __0.0014__ |   0.1337   |   0.1112   | __0.0000__ | __0.0000__ | __0.0459__ | __0.0053__ | __0.0167__ |   0.2309   | __0.0011__ | __0.0315__ |   0.8510   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0333__ | __0.0120__ |   0.0586   | __0.0012__ |   1.0000   |   0.8508   |   0.1813   | __0.0004__ |   0.2386   | __0.0000__ |   0.6388   |   0.8436   |   0.9852   |   0.2052   |   0.4819   |   0.7166   | __0.0481__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0377__ | __0.0363__ |   0.0637   | __0.0014__ |   0.8508   |   1.0000   |   0.1959   | __0.0003__ |   0.2471   | __0.0000__ |   0.6076   |   0.8728   |   0.9132   |   0.1437   |   0.5160   |   0.4905   | __0.0298__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0020__ | __0.0055__ | __0.0047__ |   0.1337   |   0.1813   |   0.1959   |   1.0000   | __0.0099__ | __0.0339__ | __0.0000__ |   0.5105   |   0.2604   |   0.2408   |   0.9205   |   0.0823   |   0.5724   |   0.3757   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1112   | __0.0004__ | __0.0003__ | __0.0099__ |   1.0000   | __0.0000__ | __0.0020__ | __0.0070__ | __0.0002__ | __0.0005__ | __0.0179__ | __0.0005__ | __0.0017__ |   0.1536   |
| [percival2014/stem](#percival2014stem)             |   0.2639   |   0.3522   |   0.3819   | __0.0000__ |   0.2386   |   0.2471   | __0.0339__ | __0.0000__ |   1.0000   | __0.0000__ |   0.1045   |   0.1920   |   0.2565   | __0.0013__ |   0.6254   | __0.0330__ | __0.0011__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0022__ | __0.0124__ | __0.0098__ | __0.0459__ |   0.6388   |   0.6076   |   0.5105   | __0.0070__ |   0.1045   | __0.0000__ |   1.0000   |   0.6984   |   0.6623   |   0.4187   |   0.2328   |   0.9391   |   0.1346   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0175__ | __0.0088__ | __0.0220__ | __0.0053__ |   0.8436   |   0.8728   |   0.2604   | __0.0002__ |   0.1920   | __0.0000__ |   0.6984   |   1.0000   |   0.9653   |   0.2304   |   0.4808   |   0.5831   | __0.0355__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0340__ | __0.0411__ | __0.0495__ | __0.0167__ |   0.9852   |   0.9132   |   0.2408   | __0.0005__ |   0.2565   | __0.0000__ |   0.6623   |   0.9653   |   1.0000   |   0.2401   |   0.5416   |   0.6197   | __0.0350__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0022__ | __0.0042__ |   0.2309   |   0.2052   |   0.1437   |   0.9205   | __0.0179__ | __0.0013__ | __0.0000__ |   0.4187   |   0.2304   |   0.2401   |   1.0000   | __0.0486__ |   0.2729   |   0.3148   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1243   |   0.1500   |   0.1882   | __0.0011__ |   0.4819   |   0.5160   |   0.0823   | __0.0005__ |   0.6254   | __0.0000__ |   0.2328   |   0.4808   |   0.5416   | __0.0486__ |   1.0000   |   0.1934   | __0.0081__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0069__ | __0.0040__ | __0.0156__ | __0.0315__ |   0.7166   |   0.4905   |   0.5724   | __0.0017__ | __0.0330__ | __0.0000__ |   0.9391   |   0.5831   |   0.6197   |   0.2729   |   0.1934   |   1.0000   |   0.0833   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0002__ | __0.0003__ | __0.0006__ |   0.8510   | __0.0481__ | __0.0298__ |   0.3757   |   0.1536   | __0.0011__ | __0.0000__ |   0.1346   | __0.0355__ | __0.0350__ |   0.3148   | __0.0081__ |   0.0833   |   1.0000   |

<a name="table29"></a>Table 29: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hainsworth_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hainsworth_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hainsworth_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure71"></a>Figure 71: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure72"></a>Figure 72: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure73"></a>Figure 73: Mean AOE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure74"></a>Figure 74: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hainsworth_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure75"></a>Figure 75: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hainsworth_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure76"></a>Figure 76: Mean AOE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hainsworth_estimates_3.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure77"></a>Figure 77: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure78"></a>Figure 78: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_aoe1.svg">
</figure>

<a name="figure79"></a>Figure 79: Mean AOE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure80"></a>Figure 80: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hainsworth_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure81"></a>Figure 81: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hainsworth_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_inter_aoe2.svg">
</figure>

<a name="figure82"></a>Figure 82: Mean AOE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hainsworth_estimates_3.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_inter_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure83"></a>Figure 83: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure84"></a>Figure 84: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure85"></a>Figure 85: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure86"></a>Figure 86: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure87"></a>Figure 87: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_3.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure88"></a>Figure 88: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hainsworth_estimates_3.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hainsworth_estimates_3.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hainsworth_estimates_3.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hainsworth_estimates_3.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hainsworth_estimates_3.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_3.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_3.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure89"></a>Figure 89: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure90"></a>Figure 90: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_aoe1.svg">
</figure>

<a name="figure91"></a>Figure 91: AOE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe1.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe1.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure92"></a>Figure 92: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure93"></a>Figure 93: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_2.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hainsworth_estimates_1.0_tag_open_3.0_aoe2.svg">
</figure>

<a name="figure94"></a>Figure 94: AOE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe2.svg "Open Figure") [PDF](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe2.pdf "Open Figure") [PNG](figures/hainsworth_estimates_1.0_tag_open_3.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-04 17:47. Size L.
