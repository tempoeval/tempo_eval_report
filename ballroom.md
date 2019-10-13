---
title: ballroom
{:.no_toc}
layout: default
---

# ballroom
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'ballroom' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'ballroom'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Curator** | [Simon Dixon](mailto:s.e.dixon@qmul.ac.uk) |
| **Data&nbsp;Source** | BallroomDancers.com, checked by human |
| **Annotator,&nbsp;bibtex** |[Gouyon2006](bib/Gouyon2006.bib) |
| **Annotator,&nbsp;ref_url** | [http://mtg.upf.edu/ismir2004/contest/tempoContest/node5.html](http://mtg.upf.edu/ismir2004/contest/tempoContest/node5.html) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 2.0 |
| **Curator** | [Florian Krebs](mailto:florian.krebs@jku.at) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of corresponding inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Krebs2013](bib/Krebs2013.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/CPJKU/BallroomAnnotations](https://github.com/CPJKU/BallroomAnnotations) |

### 3.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 3.0 |
| **Curator** | [Graham Percival](mailto:graham@percival-music.ca) |
| **Data&nbsp;Source** | BallroomDancers.com, checked by human |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   698   |   60.00   |   224.00   |   130.14   |   39.53   |   91.00   |   0.71   |
| [2.0](#20)                                         |   698   |   68.57   |   214.29   |   129.77   |   39.72   |   72.00   |   0.71   |
| [3.0](#30)                                         |   698   |   58.00   |   219.00   |   129.77   |   39.63   |   71.00   |   0.71   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/ballroom_reference_basic_stats.csv "Download data as CSV") [JSON](data/ballroom_reference_basic_stats.json "Download data as JSON") [LATEX](data/ballroom_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/ballroom_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/ballroom_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/ballroom_reference_dist.csv "Download data as CSV") [JSON](data/ballroom_reference_dist.json "Download data as JSON") [LATEX](data/ballroom_reference_dist.latex "Download data as LATEX") [PICKLE](data/ballroom_reference_dist.pickle "Download data as PICKLE") [SVG](figures/ballroom_reference_dist.svg "Open Figure") [PDF](figures/ballroom_reference_dist.pdf "Open Figure") [PNG](figures/ballroom_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/ballroom_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/ballroom_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/ballroom_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/ballroom_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/ballroom_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/ballroom_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/ballroom_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/ballroom_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/ballroom_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/ballroom_variation.csv "Download data as CSV") [JSON](data/ballroom_variation.json "Download data as JSON") [LATEX](data/ballroom_variation.latex "Download data as LATEX") [PICKLE](data/ballroom_variation.pickle "Download data as PICKLE") [SVG](figures/ballroom_variation.svg "Open Figure") [PDF](figures/ballroom_variation.pdf "Open Figure") [PNG](figures/ballroom_variation.png "Open Figure") 

# Estimates for 'ballroom'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### echonest/version_3_2_1

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 3.2.1 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Echo Nest track analyzer v3.2.1 |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### gkiokas2012/default

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Gkiokas2012 |
| **Annotator,&nbsp;bibtex** |[Gkiokas2012](bib/Gkiokas2012.bib) |

### klapuri2006/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Klapuri 2006 |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### oliveira2010/ibt

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Oliveira 2010 |
| **Annotator,&nbsp;bibtex** |[Oliveira2010](bib/Oliveira2010.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### scheirer1998/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Scheirer 1998 |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

### zplane/auftakt_v3

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 3.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | zplane aufTAKT version 3.0, http://licensing.zplane.de/technology#auftakt |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   698   |   57.69   |   214.29   |   117.51   |   31.52   |   74.00   |   0.83   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   698   |   60.09   |   206.72   |   120.29   |   28.62   |   84.00   |   0.87   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   698   |   0.00   |   207.60   |   104.22   |   31.69   |   67.00   |   0.75   |
| [gkiokas2012/default](#gkiokas2012default)         |   698   |   40.00   |   207.00   |   98.23   |   22.77   |   67.00   |   0.86   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   698   |   59.75   |   169.44   |   106.18   |   16.64   |   76.00   |   0.99   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   698   |   83.00   |   167.00   |   106.53   |   17.34   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   698   |   57.90   |   150.34   |   101.91   |   18.04   |   68.00   |   0.96   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   698   |   0.00   |   181.82   |   105.76   |   42.43   |   69.00   |   0.72   |
| [schreiber2014/default](#schreiber2014default)     |   698   |   55.83   |   142.73   |   101.77   |   17.17   |   69.00   |   0.96   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   698   |   41.91   |   174.75   |   103.70   |   22.03   |   81.00   |   0.92   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   698   |   41.91   |   161.26   |   101.53   |   20.69   |   81.00   |   0.93   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   698   |   71.00   |   216.00   |   129.79   |   39.49   |   70.00   |   0.72   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   698   |   62.00   |   232.00   |   128.65   |   39.00   |   74.00   |   0.73   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   698   |   75.00   |   212.00   |   126.29   |   37.97   |   74.00   |   0.76   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   698   |   65.90   |   166.50   |   105.01   |   17.50   |   74.00   |   0.98   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/ballroom_estimates_basic_stats.csv "Download data as CSV") [JSON](data/ballroom_estimates_basic_stats.json "Download data as JSON") [LATEX](data/ballroom_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/ballroom_estimates_dist.csv "Download data as CSV") [JSON](data/ballroom_estimates_dist.json "Download data as JSON") [LATEX](data/ballroom_estimates_dist.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_dist.svg "Open Figure") [PDF](figures/ballroom_estimates_dist.pdf "Open Figure") [PNG](figures/ballroom_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9341__ |   0.9570   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9155   | __0.9613__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9126   |   0.9599   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8052   |   0.9542   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6619   |   0.8968   |
| [schreiber2014/default](#schreiber2014default)     |   0.6433   |   0.9384   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6418   |   0.9212   |
| [percival2014/stem](#percival2014stem)             |   0.6275   |   0.9198   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6275   |   0.9370   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6232   |   0.9011   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6203   |   0.8782   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6189   |   0.9384   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6003   |   0.9441   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5516   |   0.8410   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5258   |   0.7364   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/ballroom_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/ballroom_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9699__ |   0.9928   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9470   |   0.9914   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9470   |   0.9943   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8453   | __0.9986__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6819   |   0.9284   |
| [schreiber2014/default](#schreiber2014default)     |   0.6719   |   0.9728   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6691   |   0.9527   |
| [percival2014/stem](#percival2014stem)             |   0.6547   |   0.9527   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6533   |   0.9713   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6461   |   0.9284   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6461   |   0.9097   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6447   |   0.9728   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6289   |   0.9799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5745   |   0.8739   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5372   |   0.7579   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/ballroom_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/ballroom_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_accuracy2.png "Open Figure") 

### Accuracy Results for 3.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9570__ | __0.9871__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9341   | __0.9871__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9327   | __0.9871__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8324   | __0.9871__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6762   |   0.9169   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6691   |   0.9484   |
| [schreiber2014/default](#schreiber2014default)     |   0.6676   |   0.9670   |
| [percival2014/stem](#percival2014stem)             |   0.6562   |   0.9499   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6519   |   0.9670   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6490   |   0.9284   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6461   |   0.9699   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6433   |   0.9026   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6318   |   0.9799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5702   |   0.8653   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5372   |   0.7564   |

<a name="table5"></a>Table 5: Mean accuracy of estimates compared to version [3.0](#30) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_3.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/ballroom_estimates_3.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/ballroom_estimates_3.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (136 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (236 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (313 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' ...
[CSV](data/ballroom_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (279 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (263 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (265 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' ...
[CSV](data/ballroom_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (260 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' ...
[CSV](data/ballroom_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (331 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' ...
[CSV](data/ballroom_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (249 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' ...
[CSV](data/ballroom_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (266 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (260 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (46 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (59 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-Fire-13' 'Albums-GloriaEstefan\_MiTierra-06' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (61 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Fire-03' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (250 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (108 differences):*
'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (222 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-15' ...
[CSV](data/ballroom_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (297 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (259 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (247 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (247 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (241 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (323 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' ...
[CSV](data/ballroom_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (229 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (248 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (242 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (21 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Macumba-16' 'Media-103302' 'Media-103315' 'Media-103618' 'Media-103711' 'Media-103715' 'Media-103905' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (37 differences):*
'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' 'Albums-Macumba-16' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (37 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Latin\_Jam3-11' 'Albums-Latin\_Jam3-12' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (231 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (117 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' ...
[CSV](data/ballroom_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (226 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (300 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' ...
[CSV](data/ballroom_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (257 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (245 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (249 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' ...
[CSV](data/ballroom_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (240 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' ...
[CSV](data/ballroom_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (323 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' ...
[CSV](data/ballroom_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (232 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (247 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (243 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (30 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' 'Albums-Macumba-16' 'Albums-Secret\_Garden-05' 'Albums-Step\_By\_Step-15' 'Albums-Step\_By\_Step-16' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (46 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (47 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (231 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>1</sub>:__
'Media-104816' 
[CSV](data/ballroom_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (32 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-05' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-05' ...
[CSV](data/ballroom_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (72 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' ...
[CSV](data/ballroom_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (111 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' ...
[CSV](data/ballroom_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (39 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-15' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' ...
[CSV](data/ballroom_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (69 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' ...
[CSV](data/ballroom_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (85 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' ...
[CSV](data/ballroom_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (56 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' ...
[CSV](data/ballroom_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (184 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (43 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-Fire-13' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' ...
[CSV](data/ballroom_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (43 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (44 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (30 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' 'Albums-Secret\_Garden-02' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (27 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-Fire-13' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (28 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-05' ...
[CSV](data/ballroom_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (55 differences):*
'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' ...
[CSV](data/ballroom_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1 differences):*
'Media-103905' 
[CSV](data/ballroom_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' ...
[CSV](data/ballroom_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (88 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-03' ...
[CSV](data/ballroom_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-02' 'Media-103710' 'Media-103905' 'Media-104711' 'Media-105002' 'Media-105007' ...
[CSV](data/ballroom_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (63 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (33 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100604' 'Media-100609' ...
[CSV](data/ballroom_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (169 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (19 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' 'Media-104703' 'Media-104811' ...
[CSV](data/ballroom_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (19 differences):*
'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-100604' 'Media-104315' 'Media-104416' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (20 differences):*
'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Macumba-16' 'Media-100604' 'Media-104315' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (5 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103315' 'Media-103905' 'Media-104905' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (6 differences):*
'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103905' 'Media-105002' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (4 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103905' 'Media-105911' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (33 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100603' ...
[CSV](data/ballroom_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-05' 'Albums-Secret\_Garden-05' 'Albums-StrictlyDancing\_Tango-08' 'Media-103905' 'Media-104404' 'Media-104908' 'Media-105007' 'Media-105101' 
[CSV](data/ballroom_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (58 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' ...
[CSV](data/ballroom_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (94 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne1-01' ...
[CSV](data/ballroom_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-05' 'Media-103710' 'Media-103905' 'Media-103911' 'Media-104601' 'Media-104711' ...
[CSV](data/ballroom_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (68 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (35 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' ...
[CSV](data/ballroom_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (170 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (23 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' ...
[CSV](data/ballroom_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (21 differences):*
'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-100604' 'Media-104315' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (23 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Macumba-16' 'Albums-Secret\_Garden-05' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Media-103315' 'Media-103709' 'Media-103905' 'Media-104905' 'Media-105007' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-103905' 'Media-103911' 'Media-105007' 'Media-105211' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Albums-StrictlyDancing\_Tango-11' 'Media-103905' 'Media-103911' 'Media-105007' 'Media-105911' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (36 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-05' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' ...
[CSV](data/ballroom_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0009__ | __0.0120__ | __0.0045__ | __0.0437__ | __0.0000__ |   0.3223   | __0.0116__ | __0.0469__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2314   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0144__ | __0.0001__ | __0.0002__ | __0.0000__ |   0.2664   | __0.0000__ | __0.0004__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0009__ | __0.0144__ |   1.0000   |   0.1058   |   0.1800   | __0.0295__ | __0.0012__ | __0.0005__ |   0.2084   |   0.0509   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0021__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0120__ | __0.0001__ |   0.1058   |   1.0000   |   0.8776   |   0.7838   | __0.0000__ |   0.0925   |   0.7911   |   0.7979   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0596   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0045__ | __0.0002__ |   0.1800   |   0.8776   |   1.0000   |   0.6085   | __0.0000__ |   0.0894   |   1.0000   |   0.6143   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0489__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0437__ | __0.0000__ | __0.0295__ |   0.7838   |   0.6085   |   1.0000   | __0.0000__ |   0.1925   |   0.5320   |   0.9020   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2203   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.2664   | __0.0012__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.3223   | __0.0000__ | __0.0005__ |   0.0925   |   0.0894   |   0.1925   | __0.0000__ |   1.0000   | __0.0363__ |   0.1608   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0116__ | __0.0004__ |   0.2084   |   0.7911   |   1.0000   |   0.5320   | __0.0000__ | __0.0363__ |   1.0000   |   0.2379   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0519   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0469__ | __0.0001__ |   0.0509   |   0.7979   |   0.6143   |   0.9020   | __0.0000__ |   0.1608   |   0.2379   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2370   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0660   | __0.0237__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0660   |   1.0000   |   0.8776   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0237__ |   0.8776   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.2314   | __0.0000__ | __0.0021__ |   0.0596   | __0.0489__ |   0.2203   | __0.0000__ |   1.0000   |   0.0519   |   0.2370   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0059__ | __0.0215__ | __0.0180__ |   0.1186   | __0.0000__ |   0.6320   | __0.0346__ |   0.1083   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4812   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0067__ | __0.0001__ | __0.0001__ | __0.0000__ |   0.1037   | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0059__ | __0.0067__ |   1.0000   |   0.2410   |   0.2566   | __0.0356__ | __0.0001__ | __0.0005__ |   0.2945   |   0.0899   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0029__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0215__ | __0.0001__ |   0.2410   |   1.0000   |   1.0000   |   0.5044   | __0.0000__ | __0.0385__ |   1.0000   |   0.6143   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0226__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0180__ | __0.0001__ |   0.2566   |   1.0000   |   1.0000   |   0.5115   | __0.0000__ |   0.0512   |   1.0000   |   0.6143   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.1186   | __0.0000__ | __0.0356__ |   0.5044   |   0.5115   |   1.0000   | __0.0000__ |   0.1619   |   0.4635   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2203   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.1037   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.6320   | __0.0000__ | __0.0005__ | __0.0385__ |   0.0512   |   0.1619   | __0.0000__ |   1.0000   | __0.0226__ |   0.1048   | __0.0000__ | __0.0000__ | __0.0000__ |   0.8955   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0346__ | __0.0003__ |   0.2945   |   1.0000   |   1.0000   |   0.4635   | __0.0000__ | __0.0226__ |   1.0000   |   0.2632   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0464__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.1083   | __0.0000__ |   0.0899   |   0.6143   |   0.6143   |   1.0000   | __0.0000__ |   0.1048   |   0.2632   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2148   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0090__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0090__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.4812   | __0.0000__ | __0.0029__ | __0.0226__ | __0.0365__ |   0.2203   | __0.0000__ |   0.8955   | __0.0464__ |   0.2148   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0195__ |   0.0818   | __0.0286__ |   0.2578   | __0.0000__ |   0.6851   |   0.0852   |   0.1716   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7183   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ | __0.0001__ | __0.0000__ |   0.1478   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0195__ | __0.0020__ |   1.0000   |   0.2410   |   0.4750   | __0.0498__ | __0.0000__ | __0.0035__ |   0.3481   |   0.1561   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0064__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.0818   | __0.0000__ |   0.2410   |   1.0000   |   0.6358   |   0.5901   | __0.0000__ |   0.1299   |   0.8955   |   0.8973   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0286__ | __0.0001__ |   0.4750   |   0.6358   |   1.0000   |   0.2976   | __0.0000__ |   0.0647   |   0.8973   |   0.5254   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0175__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.2578   | __0.0000__ | __0.0498__ |   0.5901   |   0.2976   |   1.0000   | __0.0000__ |   0.3581   |   0.4568   |   0.8041   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2624   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.1478   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.6851   | __0.0000__ | __0.0035__ |   0.1299   |   0.0647   |   0.3581   | __0.0000__ |   1.0000   |   0.0674   |   0.1690   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ |   0.0852   | __0.0001__ |   0.3481   |   0.8955   |   0.8973   |   0.4568   | __0.0000__ |   0.0674   |   1.0000   |   0.4807   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0559   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.1716   | __0.0000__ |   0.1561   |   0.8973   |   0.5254   |   0.8041   | __0.0000__ |   0.1690   |   0.4807   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1550   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0076__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0076__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.7183   | __0.0000__ | __0.0064__ | __0.0436__ | __0.0175__ |   0.2624   | __0.0000__ |   1.0000   |   0.0559   |   0.1550   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.1671   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0433__ | __0.0347__ | __0.0227__ |   0.8036   |   0.2668   |   0.4240   | __0.0002__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.8041   |   0.1237   | __0.0365__ | __0.0000__ | __0.0004__ | __0.0003__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0363__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0034__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1671   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0115__ | __0.0000__ |   0.6177   |   0.5966   |   0.4869   |   0.0931   | __0.0075__ | __0.0127__ | __0.0166__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.8041   | __0.0000__ | __0.0000__ |   1.0000   | __0.0402__ |   0.0854   | __0.0000__ | __0.0003__ | __0.0003__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.1237   | __0.0034__ | __0.0000__ | __0.0402__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0365__ | __0.0000__ | __0.0115__ |   0.0854   | __0.0002__ |   1.0000   | __0.0000__ |   0.0533   | __0.0470__ |   0.0730   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0433__ | __0.0004__ | __0.0000__ |   0.6177   | __0.0003__ | __0.0000__ |   0.0533   | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0106__ | __0.0015__ | __0.0059__ |   0.0961   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0347__ | __0.0003__ | __0.0000__ |   0.5966   | __0.0003__ | __0.0000__ | __0.0470__ | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0146__ | __0.0009__ | __0.0026__ |   0.0807   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0227__ | __0.0006__ | __0.0000__ |   0.4869   | __0.0006__ | __0.0000__ |   0.0730   | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0094__ | __0.0005__ | __0.0015__ |   0.1173   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8036   | __0.0000__ | __0.0000__ |   0.0931   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0106__ | __0.0146__ | __0.0094__ |   1.0000   |   0.5078   |   0.7539   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2668   | __0.0000__ | __0.0000__ | __0.0075__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0009__ | __0.0005__ |   0.5078   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4240   | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ | __0.0026__ | __0.0015__ |   0.7539   |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0002__ | __0.0363__ | __0.0000__ | __0.0166__ | __0.0436__ | __0.0002__ |   1.0000   | __0.0000__ |   0.0961   |   0.0807   |   0.1173   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table9"></a>Table 9: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1250   |   0.0625   |   0.2500   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0984   | __0.0046__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0186__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0046__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ |   0.4869   |   0.4869   |   0.3915   | __0.0490__ |   0.0768   | __0.0213__ | __0.0019__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0919   | __0.0213__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0115__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.0984   | __0.0046__ | __0.0000__ |   0.0919   |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0046__ | __0.0000__ | __0.0019__ | __0.0213__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0385__ | __0.0243__ | __0.0410__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.4869   | __0.0000__ | __0.0000__ | __0.0385__ | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0013__ | __0.0072__ | __0.0007__ | __0.0385__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   0.4869   | __0.0000__ | __0.0000__ | __0.0243__ | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0026__ | __0.0023__ | __0.0007__ | __0.0436__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0001__ | __0.0000__ |   0.3915   | __0.0001__ | __0.0000__ | __0.0410__ | __0.0000__ |   1.0000   |   1.0000   |   1.0000   | __0.0015__ | __0.0013__ | __0.0004__ |   0.0660   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1250   | __0.0000__ | __0.0000__ | __0.0490__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ | __0.0026__ | __0.0015__ |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0625   | __0.0000__ | __0.0000__ |   0.0768   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ | __0.0023__ | __0.0013__ |   1.0000   |   1.0000   |   0.6875   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2500   | __0.0000__ | __0.0000__ | __0.0213__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0007__ | __0.0004__ |   1.0000   |   0.6875   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0186__ | __0.0000__ | __0.0019__ | __0.0115__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0385__ | __0.0436__ |   0.0660   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table10"></a>Table 10: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.3018   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0066__ | __0.0227__ | __0.0066__ |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ |   0.3581   |   0.2370   | __0.0011__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0034__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3018   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.1496   |   0.2810   |   0.1496   |   0.3018   |   0.2266   |   0.2668   | __0.0005__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.3581   | __0.0000__ | __0.0000__ |   1.0000   | __0.0175__ | __0.0489__ | __0.0000__ | __0.0003__ | __0.0001__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.2370   | __0.0034__ | __0.0000__ | __0.0175__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0011__ | __0.0000__ | __0.0008__ | __0.0489__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0730   | __0.0288__ |   0.0652   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0066__ | __0.0000__ | __0.0000__ |   0.1496   | __0.0003__ | __0.0000__ |   0.0730   | __0.0000__ |   1.0000   |   0.8238   |   1.0000   | __0.0013__ | __0.0043__ | __0.0043__ |   0.0596   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0227__ | __0.0000__ | __0.0000__ |   0.2810   | __0.0001__ | __0.0000__ | __0.0288__ | __0.0000__ |   0.8238   |   1.0000   |   0.5000   | __0.0169__ | __0.0169__ | __0.0169__ | __0.0275__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0066__ | __0.0000__ | __0.0000__ |   0.1496   | __0.0003__ | __0.0000__ |   0.0652   | __0.0000__ |   1.0000   |   0.5000   |   1.0000   | __0.0043__ | __0.0043__ | __0.0043__ |   0.0596   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   | __0.0000__ | __0.0000__ |   0.3018   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ | __0.0169__ | __0.0043__ |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   | __0.0000__ | __0.0000__ |   0.2266   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0043__ | __0.0169__ | __0.0043__ |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   | __0.0000__ | __0.0000__ |   0.2668   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0043__ | __0.0169__ | __0.0043__ |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0038__ | __0.0000__ | __0.0005__ | __0.0436__ | __0.0001__ |   1.0000   | __0.0000__ |   0.0596   | __0.0275__ |   0.0596   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table11"></a>Table 11: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_accuracy1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_accuracy2.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure23"></a>Figure 23: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure24"></a>Figure 24: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure25"></a>Figure 25: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure26"></a>Figure 26: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure27"></a>Figure 27: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure28"></a>Figure 28: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean Accuracy<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean Accuracy<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __-0.0037__ | __0.1774__ |   0.0006   |   0.0574   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0403   |   0.2284   |   -0.0016   |   0.0579   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0156   |   0.2311   |   0.0001   |   0.0568   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1312   |   0.3865   |   -0.0032   | __0.0503__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.3127   |   0.4610   |   0.0025   |   0.0840   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2660   |   0.4749   |   0.0042   |   0.0841   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2440   |   0.4841   |   0.0067   |   0.0931   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2478   |   0.4892   |   0.0152   |   0.1012   |
| [percival2014/stem](#percival2014stem)             |   -0.3133   |   0.4924   | __0.0001__ |   0.0767   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.3284   |   0.5146   |   -0.0003   |   0.0855   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0879   |   0.5170   |   0.0241   |   0.0900   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1809   |   0.5199   |   0.0246   |   0.1546   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.2983   |   0.5378   |   0.0003   |   0.0840   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3190   |   0.5379   |   -0.0129   |   0.1318   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3835   |   0.5661   |   -0.0014   |   0.0664   |

<a name="table12"></a>Table 12: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/ballroom_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure35"></a>Figure 35: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure36"></a>Figure 36: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.1616__ |   0.0041   |   0.0299   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0107   |   0.2174   |   0.0037   |   0.0261   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0353   |   0.2179   |   0.0019   |   0.0317   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1263   |   0.3854   | __0.0003__ | __0.0098__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.3077   |   0.4619   |   0.0060   |   0.0682   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2610   |   0.4741   |   0.0055   |   0.0706   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2390   |   0.4865   |   0.0088   |   0.0851   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2428   |   0.4899   |   0.0159   |   0.0916   |
| [percival2014/stem](#percival2014stem)             |   -0.3084   |   0.4925   |   0.0036   |   0.0607   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.3234   |   0.5164   |   0.0032   |   0.0707   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0830   |   0.5202   |   0.0262   |   0.0791   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1745   |   0.5208   |   0.0269   |   0.1521   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.2934   |   0.5385   |   0.0038   |   0.0689   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3140   |   0.5407   |   -0.0108   |   0.1230   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3785   |   0.5673   |   0.0007   |   0.0430   |

<a name="table13"></a>Table 13: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/ballroom_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure37"></a>Figure 37: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure38"></a>Figure 38: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 3.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0012__ | __0.1855__ | __-0.0002__ |   0.0402   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0354   |   0.2365   |   -0.0024   |   0.0405   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0107   |   0.2425   |   -0.0007   |   0.0373   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1263   |   0.3889   |   -0.0040   | __0.0288__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.3078   |   0.4631   |   0.0017   |   0.0729   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2610   |   0.4768   |   0.0020   |   0.0688   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2391   |   0.4851   |   0.0045   |   0.0834   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2429   |   0.4902   |   0.0130   |   0.0898   |
| [percival2014/stem](#percival2014stem)             |   -0.3084   |   0.4931   |   0.0022   |   0.0654   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0830   |   0.5159   |   0.0247   |   0.0786   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.3235   |   0.5180   |   -0.0011   |   0.0754   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1746   |   0.5214   |   0.0231   |   0.1514   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3141   |   0.5408   |   -0.0094   |   0.1257   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.2934   |   0.5426   |   0.0007   |   0.0697   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3785   |   0.5694   |   -0.0022   |   0.0436   |

<a name="table14"></a>Table 14: Mean OE1/OE2 for estimates compared to version [3.0](#30) ordered by standard deviation.

[CSV](data/ballroom_estimates_3.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_oe1.svg">
</figure>

<a name="figure39"></a>Figure 39: OE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_oe2.svg">
</figure>

<a name="figure40"></a>Figure 40: OE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   |   0.2792   |   0.5790   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   |   0.2193   |   0.1958   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   |   0.2342   |   0.1712   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2792   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2193   | __0.0000__ |   0.2342   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.5790   | __0.0002__ | __0.0000__ | __0.0000__ |   0.1958   | __0.0000__ |   0.1712   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table15"></a>Table 15: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   |   0.2792   |   0.5790   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   |   0.2193   |   0.1958   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   |   0.2342   |   0.1712   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2792   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2193   | __0.0000__ |   0.2342   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.5790   | __0.0002__ | __0.0000__ | __0.0000__ |   0.1958   | __0.0000__ |   0.1712   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table16"></a>Table 16: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   |   0.2792   |   0.5790   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   |   0.2193   |   0.1958   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   |   0.2342   |   0.1712   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2792   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2193   | __0.0000__ |   0.2342   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.5790   | __0.0002__ | __0.0000__ | __0.0000__ |   0.1958   | __0.0000__ |   0.1712   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0037__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0409__ |   0.3570   | __0.0000__ | __0.0024__ |   0.1554   | __0.0000__ | __0.0288__ |   0.1841   |   0.2817   | __0.0013__ | __0.0011__ |   0.2169   | __0.0102__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0415__ | __0.0000__ | __0.0000__ |   0.8497   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0409__ | __0.0000__ |   1.0000   | __0.0261__ | __0.0000__ | __0.0010__ | __0.0161__ | __0.0000__ | __0.0054__ | __0.0170__ | __0.0235__ | __0.0057__ | __0.0068__ | __0.0232__ | __0.0028__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3570   | __0.0000__ | __0.0261__ |   1.0000   | __0.0000__ | __0.0202__ |   0.5904   | __0.0000__ |   0.2283   |   0.5981   |   0.7343   |   0.3704   |   0.4764   |   0.9306   |   0.0912   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0415__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0290__ | __0.0002__ |   0.1870   | __0.0009__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0082__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0024__ | __0.0000__ | __0.0010__ | __0.0202__ | __0.0290__ |   1.0000   |   0.0960   | __0.0103__ |   0.3110   |   0.1208   |   0.0936   |   0.0517   | __0.0455__ | __0.0091__ |   0.5573   |
| [percival2014/stem](#percival2014stem)             |   0.1554   | __0.0000__ | __0.0161__ |   0.5904   | __0.0002__ |   0.0960   |   1.0000   | __0.0001__ |   0.4524   |   0.9523   |   0.8980   |   0.8397   |   0.9927   |   0.4584   |   0.2257   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.8497   | __0.0000__ | __0.0000__ |   0.1870   | __0.0103__ | __0.0001__ |   1.0000   | __0.0009__ | __0.0001__ | __0.0001__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ | __0.0000__ | __0.0054__ |   0.2283   | __0.0009__ |   0.3110   |   0.4524   | __0.0009__ |   1.0000   |   0.3872   |   0.2842   |   0.4255   |   0.3397   |   0.1098   |   0.6257   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1841   | __0.0000__ | __0.0170__ |   0.5981   | __0.0001__ |   0.1208   |   0.9523   | __0.0001__ |   0.3872   |   1.0000   |   0.3177   |   0.9104   |   0.9475   |   0.4573   |   0.2884   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2817   | __0.0000__ | __0.0235__ |   0.7343   | __0.0001__ |   0.0936   |   0.8980   | __0.0001__ |   0.2842   |   0.3177   |   1.0000   |   0.7360   |   0.8681   |   0.6167   |   0.2272   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0000__ | __0.0057__ |   0.3704   | __0.0000__ |   0.0517   |   0.8397   | __0.0001__ |   0.4255   |   0.9104   |   0.7360   |   1.0000   |   0.6915   | __0.0487__ |   0.2225   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0000__ | __0.0068__ |   0.4764   | __0.0000__ | __0.0455__ |   0.9927   | __0.0001__ |   0.3397   |   0.9475   |   0.8681   |   0.6915   |   1.0000   |   0.2103   |   0.1580   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   | __0.0000__ | __0.0232__ |   0.9306   | __0.0000__ | __0.0091__ |   0.4584   | __0.0000__ |   0.1098   |   0.4573   |   0.6167   | __0.0487__ |   0.2103   |   1.0000   | __0.0497__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0102__ | __0.0000__ | __0.0028__ |   0.0912   | __0.0082__ |   0.5573   |   0.2257   | __0.0012__ |   0.6257   |   0.2884   |   0.2272   |   0.2225   |   0.1580   | __0.0497__ |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0177__ |   0.8188   | __0.0000__ | __0.0087__ |   0.1572   | __0.0000__ | __0.0288__ |   0.1841   |   0.2817   | __0.0013__ | __0.0011__ |   0.2169   |   0.0558   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ | __0.0000__ |   0.7757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0177__ | __0.0000__ |   1.0000   | __0.0222__ | __0.0000__ | __0.0010__ | __0.0071__ | __0.0000__ | __0.0017__ | __0.0079__ | __0.0113__ | __0.0021__ | __0.0024__ | __0.0098__ | __0.0047__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8188   | __0.0000__ | __0.0222__ |   1.0000   | __0.0001__ | __0.0202__ |   0.2826   | __0.0000__ |   0.0810   |   0.3066   |   0.4154   |   0.0816   |   0.1082   |   0.5587   |   0.1156   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0193__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0787   | __0.0026__ |   0.1069   | __0.0089__ | __0.0013__ | __0.0008__ | __0.0005__ | __0.0004__ | __0.0001__ | __0.0105__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0087__ | __0.0000__ | __0.0010__ | __0.0202__ |   0.0787   |   1.0000   |   0.1865   | __0.0102__ |   0.4990   |   0.2247   |   0.1791   |   0.1317   |   0.1108   | __0.0301__ |   0.4232   |
| [percival2014/stem](#percival2014stem)             |   0.1572   | __0.0000__ | __0.0071__ |   0.2826   | __0.0026__ |   0.1865   |   1.0000   | __0.0002__ |   0.4458   |   0.9521   |   0.8976   |   0.8289   |   0.9927   |   0.4570   |   0.5945   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.7757   | __0.0000__ | __0.0000__ |   0.1069   | __0.0102__ | __0.0002__ |   1.0000   | __0.0014__ | __0.0003__ | __0.0002__ | __0.0002__ | __0.0001__ | __0.0001__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ | __0.0000__ | __0.0017__ |   0.0810   | __0.0089__ |   0.4990   |   0.4458   | __0.0014__ |   1.0000   |   0.3872   |   0.2842   |   0.4255   |   0.3397   |   0.1098   |   0.8716   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1841   | __0.0000__ | __0.0079__ |   0.3066   | __0.0013__ |   0.2247   |   0.9521   | __0.0003__ |   0.3872   |   1.0000   |   0.3177   |   0.9104   |   0.9475   |   0.4573   |   0.6416   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2817   | __0.0000__ | __0.0113__ |   0.4154   | __0.0008__ |   0.1791   |   0.8976   | __0.0002__ |   0.2842   |   0.3177   |   1.0000   |   0.7360   |   0.8681   |   0.6167   |   0.5318   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0000__ | __0.0021__ |   0.0816   | __0.0005__ |   0.1317   |   0.8289   | __0.0002__ |   0.4255   |   0.9104   |   0.7360   |   1.0000   |   0.6915   | __0.0487__ |   0.6243   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0000__ | __0.0024__ |   0.1082   | __0.0004__ |   0.1108   |   0.9927   | __0.0001__ |   0.3397   |   0.9475   |   0.8681   |   0.6915   |   1.0000   |   0.2103   |   0.4977   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   | __0.0000__ | __0.0098__ |   0.5587   | __0.0001__ | __0.0301__ |   0.4570   | __0.0001__ |   0.1098   |   0.4573   |   0.6167   | __0.0487__ |   0.2103   |   1.0000   |   0.1982   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.0558   | __0.0000__ | __0.0047__ |   0.1156   | __0.0105__ |   0.4232   |   0.5945   | __0.0012__ |   0.8716   |   0.6416   |   0.5318   |   0.6243   |   0.4977   |   0.1982   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.2769   |   0.3251   | __0.0000__ | __0.0087__ | __0.0349__ | __0.0000__ | __0.0288__ |   0.0904   |   0.2817   | __0.0013__ | __0.0011__ |   0.2169   | __0.0231__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0057__ | __0.0000__ | __0.0000__ |   0.9621   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2769   | __0.0000__ |   1.0000   |   0.1533   | __0.0005__ | __0.0185__ | __0.0316__ | __0.0000__ |   0.0521   |   0.0685   |   0.1485   |   0.0704   |   0.0811   |   0.1763   | __0.0469__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3251   | __0.0000__ |   0.1533   |   1.0000   | __0.0001__ |   0.0514   |   0.1294   | __0.0000__ |   0.2183   |   0.3414   |   0.7289   |   0.3486   |   0.4448   |   0.9284   |   0.1571   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0057__ | __0.0005__ | __0.0001__ |   1.0000   | __0.0290__ | __0.0089__ |   0.1286   | __0.0028__ | __0.0008__ | __0.0002__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0065__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0087__ | __0.0000__ | __0.0185__ |   0.0514   | __0.0290__ |   1.0000   |   0.5709   | __0.0063__ |   0.4990   |   0.3495   |   0.1791   |   0.1317   |   0.1108   | __0.0301__ |   0.5446   |
| [percival2014/stem](#percival2014stem)             | __0.0349__ | __0.0000__ | __0.0316__ |   0.1294   | __0.0089__ |   0.5709   |   1.0000   | __0.0010__ |   0.8922   |   0.6473   |   0.3685   |   0.4124   |   0.3284   |   0.1150   |   0.9520   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.9621   | __0.0000__ | __0.0000__ |   0.1286   | __0.0063__ | __0.0010__ |   1.0000   | __0.0009__ | __0.0003__ | __0.0001__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ | __0.0000__ |   0.0521   |   0.2183   | __0.0028__ |   0.4990   |   0.8922   | __0.0009__ |   1.0000   |   0.7082   |   0.2842   |   0.4255   |   0.3397   |   0.1098   |   0.9299   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0904   | __0.0000__ |   0.0685   |   0.3414   | __0.0008__ |   0.3495   |   0.6473   | __0.0003__ |   0.7082   |   1.0000   |   0.0833   |   0.7355   |   0.6084   |   0.2515   |   0.7074   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2817   | __0.0000__ |   0.1485   |   0.7289   | __0.0002__ |   0.1791   |   0.3685   | __0.0001__ |   0.2842   |   0.0833   |   1.0000   |   0.7360   |   0.8681   |   0.6167   |   0.3843   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0000__ |   0.0704   |   0.3486   | __0.0001__ |   0.1317   |   0.4124   | __0.0001__ |   0.4255   |   0.7355   |   0.7360   |   1.0000   |   0.6915   | __0.0487__ |   0.4186   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0000__ |   0.0811   |   0.4448   | __0.0001__ |   0.1108   |   0.3284   | __0.0001__ |   0.3397   |   0.6084   |   0.8681   |   0.6915   |   1.0000   |   0.2103   |   0.3101   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   | __0.0000__ |   0.1763   |   0.9284   | __0.0000__ | __0.0301__ |   0.1150   | __0.0000__ |   0.1098   |   0.2515   |   0.6167   | __0.0487__ |   0.2103   |   1.0000   |   0.1047   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0231__ | __0.0000__ | __0.0469__ |   0.1571   | __0.0065__ |   0.5446   |   0.9520   | __0.0012__ |   0.9299   |   0.7074   |   0.3843   |   0.4186   |   0.3101   |   0.1047   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_oe1.svg">
</figure>

<a name="figure43"></a>Figure 43: Mean OE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure45"></a>Figure 45: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_oe2.svg">
</figure>

<a name="figure46"></a>Figure 46: Mean OE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure47"></a>Figure 47: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure48"></a>Figure 48: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_oe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean OE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_oe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean OE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure53"></a>Figure 53: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure54"></a>Figure 54: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_oe1.svg">
</figure>

<a name="figure55"></a>Figure 55: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure56"></a>Figure 56: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure57"></a>Figure 57: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_oe2.svg">
</figure>

<a name="figure58"></a>Figure 58: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure59"></a>Figure 59: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_oe1.svg">
</figure>

<a name="figure60"></a>Figure 60: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_oe1.svg">
</figure>

<a name="figure61"></a>Figure 61: OE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure62"></a>Figure 62: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_oe2.svg">
</figure>

<a name="figure63"></a>Figure 63: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_oe2.svg">
</figure>

<a name="figure64"></a>Figure 64: OE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0433__ | __0.1720__ |   0.0161   |   0.0551   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0647   |   0.2224   |   0.0155   |   0.0546   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0650   |   0.2227   | __0.0155__ |   0.0558   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1748   |   0.3689   |   0.0182   | __0.0470__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3026   |   0.4284   |   0.0436   |   0.0823   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3134   |   0.4450   |   0.0283   |   0.0793   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3213   |   0.4367   |   0.0417   |   0.0836   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3238   |   0.4425   |   0.0380   |   0.0950   |
| [schreiber2014/default](#schreiber2014default)     |   0.3263   |   0.4515   |   0.0258   |   0.0800   |
| [percival2014/stem](#percival2014stem)             |   0.3367   |   0.4767   |   0.0259   |   0.0722   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3431   |   0.4305   |   0.0753   |   0.1372   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3611   |   0.4922   |   0.0265   |   0.0813   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3695   |   0.4916   |   0.0259   |   0.0799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3888   |   0.4899   |   0.0553   |   0.1204   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4115   |   0.5460   |   0.0198   |   0.0634   |

<a name="table21"></a>Table 21: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/ballroom_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure65"></a>Figure 65: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure66"></a>Figure 66: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0324__ | __0.1583__ |   0.0076   |   0.0292   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0537   |   0.2109   |   0.0077   |   0.0252   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0550   |   0.2138   |   0.0075   |   0.0308   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1648   |   0.3705   | __0.0072__ | __0.0066__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3016   |   0.4320   |   0.0383   |   0.0740   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3046   |   0.4473   |   0.0179   |   0.0685   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3161   |   0.4403   |   0.0339   |   0.0785   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3165   |   0.4458   |   0.0286   |   0.0885   |
| [schreiber2014/default](#schreiber2014default)     |   0.3168   |   0.4557   |   0.0142   |   0.0669   |
| [percival2014/stem](#percival2014stem)             |   0.3276   |   0.4799   |   0.0150   |   0.0589   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3398   |   0.4315   |   0.0707   |   0.1373   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3533   |   0.4964   |   0.0149   |   0.0692   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3606   |   0.4960   |   0.0143   |   0.0675   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3822   |   0.4949   |   0.0450   |   0.1149   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4046   |   0.5490   |   0.0105   |   0.0417   |

<a name="table22"></a>Table 22: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/ballroom_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure67"></a>Figure 67: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure68"></a>Figure 68: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 3.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0425__ | __0.1806__ |   0.0102   |   0.0389   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0646   |   0.2303   |   0.0095   |   0.0395   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0659   |   0.2336   | __0.0095__ |   0.0360   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1712   |   0.3713   |   0.0121   | __0.0264__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2975   |   0.4296   |   0.0382   |   0.0730   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3084   |   0.4476   |   0.0214   |   0.0654   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3163   |   0.4386   |   0.0359   |   0.0755   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3183   |   0.4449   |   0.0311   |   0.0852   |
| [schreiber2014/default](#schreiber2014default)     |   0.3212   |   0.4539   |   0.0197   |   0.0702   |
| [percival2014/stem](#percival2014stem)             |   0.3309   |   0.4783   |   0.0202   |   0.0623   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3402   |   0.4320   |   0.0712   |   0.1356   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3576   |   0.4951   |   0.0205   |   0.0725   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3647   |   0.4975   |   0.0188   |   0.0672   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3852   |   0.4927   |   0.0496   |   0.1159   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4061   |   0.5501   |   0.0125   |   0.0418   |

<a name="table23"></a>Table 23: Mean AOE1/AOE2 for estimates compared to version [3.0](#30) ordered by mean.

[CSV](data/ballroom_estimates_3.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_aoe1.svg">
</figure>

<a name="figure69"></a>Figure 69: AOE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_aoe2.svg">
</figure>

<a name="figure70"></a>Figure 70: AOE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1215   |   0.1767   | __0.0445__ | __0.0232__ |   0.1422   | __0.0001__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4642   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   |   0.1913   | __0.0001__ | __0.0000__ | __0.0016__ | __0.0077__ | __0.0001__ |   0.2914   |   0.1200   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ |   0.1913   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0000__ | __0.0045__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.1215   | __0.0001__ | __0.0000__ |   1.0000   |   0.6905   |   0.1382   |   0.2342   |   0.7689   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1114   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.1767   | __0.0000__ | __0.0000__ |   0.6905   |   1.0000   |   0.0849   |   0.1832   |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2140   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0445__ | __0.0016__ | __0.0000__ |   0.1382   |   0.0849   |   1.0000   |   0.6524   |   0.2608   | __0.0048__ | __0.0265__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0232__ | __0.0077__ | __0.0014__ |   0.2342   |   0.1832   |   0.6524   |   1.0000   |   0.3117   |   0.1368   |   0.3475   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0873   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.1422   | __0.0001__ | __0.0000__ |   0.7689   |   0.5806   |   0.2608   |   0.3117   |   1.0000   | __0.0002__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1283   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0001__ |   0.2914   | __0.0045__ | __0.0000__ | __0.0000__ | __0.0048__ |   0.1368   | __0.0002__ |   1.0000   |   0.1781   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0005__ |   0.1200   | __0.0003__ | __0.0002__ | __0.0000__ | __0.0265__ |   0.3475   | __0.0014__ |   0.1781   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0116__ | __0.0062__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0116__ |   1.0000   |   0.9708   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0062__ |   0.9708   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.4642   | __0.0000__ | __0.0000__ |   0.1114   |   0.2140   | __0.0072__ |   0.0873   |   0.1283   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table24"></a>Table 24: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.2803   |   0.2996   |   0.1297   | __0.0380__ |   0.3557   | __0.0004__ | __0.0023__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8410   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   |   0.2013   | __0.0001__ | __0.0001__ | __0.0010__ | __0.0148__ | __0.0001__ |   0.2385   |   0.1080   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ |   0.2013   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0023__ | __0.0000__ | __0.0031__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.2803   | __0.0001__ | __0.0000__ |   1.0000   |   0.9454   |   0.2071   |   0.1679   |   0.9757   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0734   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.2996   | __0.0001__ | __0.0000__ |   0.9454   |   1.0000   |   0.2025   |   0.1596   |   0.9396   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0765   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.1297   | __0.0010__ | __0.0000__ |   0.2071   |   0.2025   |   1.0000   |   0.4723   |   0.2491   | __0.0050__ | __0.0203__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0380__ | __0.0148__ | __0.0023__ |   0.1679   |   0.1596   |   0.4723   |   1.0000   |   0.1874   |   0.2246   |   0.5197   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0444__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.3557   | __0.0001__ | __0.0000__ |   0.9757   |   0.9396   |   0.2491   |   0.1874   |   1.0000   | __0.0002__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1566   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0004__ |   0.2385   | __0.0031__ | __0.0000__ | __0.0000__ | __0.0050__ |   0.2246   | __0.0002__ |   1.0000   |   0.2692   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0023__ |   0.1080   | __0.0003__ | __0.0002__ | __0.0001__ | __0.0203__ |   0.5197   | __0.0010__ |   0.2692   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0126__ | __0.0053__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0126__ |   1.0000   |   0.8801   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0053__ |   0.8801   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.8410   | __0.0000__ | __0.0000__ |   0.0734   |   0.0765   | __0.0081__ | __0.0444__ |   0.1566   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table25"></a>Table 25: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1312   |   0.1787   |   0.0508   | __0.0180__ |   0.1469   | __0.0001__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4625   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   |   0.2314   | __0.0001__ | __0.0000__ | __0.0010__ | __0.0103__ | __0.0001__ |   0.2659   |   0.1235   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ |   0.2314   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ | __0.0051__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.1312   | __0.0001__ | __0.0000__ |   1.0000   |   0.7431   |   0.1534   |   0.1930   |   0.7383   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1351   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.1787   | __0.0000__ | __0.0000__ |   0.7431   |   1.0000   |   0.1047   |   0.1561   |   0.5892   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2235   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0508   | __0.0010__ | __0.0000__ |   0.1534   |   0.1047   |   1.0000   |   0.5673   |   0.2988   | __0.0041__ | __0.0158__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0099__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0180__ | __0.0103__ | __0.0019__ |   0.1930   |   0.1561   |   0.5673   |   1.0000   |   0.2739   |   0.1583   |   0.3993   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0699   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.1469   | __0.0001__ | __0.0000__ |   0.7383   |   0.5892   |   0.2988   |   0.2739   |   1.0000   | __0.0002__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1354   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0001__ |   0.2659   | __0.0051__ | __0.0000__ | __0.0000__ | __0.0041__ |   0.1583   | __0.0002__ |   1.0000   |   0.2759   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0004__ |   0.1235   | __0.0006__ | __0.0001__ | __0.0000__ | __0.0158__ |   0.3993   | __0.0010__ |   0.2759   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0064__ | __0.0067__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0064__ |   1.0000   |   0.8797   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0067__ |   0.8797   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.4625   | __0.0000__ | __0.0000__ |   0.1351   |   0.2235   | __0.0099__ |   0.0699   |   0.1354   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table26"></a>Table 26: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.3037   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0022__ | __0.0021__ | __0.0012__ |   0.0619   | __0.0051__ | __0.0142__ | __0.0001__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0081__ | __0.0000__ |   0.0900   |   0.5027   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0081__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0010__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3037   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0183__ | __0.0000__ | __0.0403__ | __0.0379__ | __0.0255__ |   0.0505   | __0.0149__ | __0.0168__ | __0.0020__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.0900   | __0.0001__ | __0.0000__ |   1.0000   |   0.2410   | __0.0004__ | __0.0000__ | __0.0006__ | __0.0007__ | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.5027   | __0.0010__ | __0.0000__ |   0.2410   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0006__ | __0.0000__ | __0.0000__ | __0.0183__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9726   |   0.9973   |   0.8276   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3900   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0022__ | __0.0000__ | __0.0000__ | __0.0403__ | __0.0006__ | __0.0000__ |   0.9726   | __0.0000__ |   1.0000   |   0.9635   |   0.7754   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4085   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0021__ | __0.0000__ | __0.0000__ | __0.0379__ | __0.0007__ | __0.0000__ |   0.9973   | __0.0000__ |   0.9635   |   1.0000   |   0.3177   | __0.0001__ | __0.0000__ | __0.0000__ |   0.4414   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0012__ | __0.0000__ | __0.0000__ | __0.0255__ | __0.0015__ | __0.0000__ |   0.8276   | __0.0000__ |   0.7754   |   0.3177   |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ |   0.5702   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0619   | __0.0000__ | __0.0000__ |   0.0505   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0001__ |   1.0000   |   0.5978   |   0.5061   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0051__ | __0.0000__ | __0.0000__ | __0.0149__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5978   |   1.0000   |   0.9673   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0142__ | __0.0000__ | __0.0000__ | __0.0168__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5061   |   0.9673   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0001__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0014__ | __0.0000__ |   0.3900   | __0.0000__ |   0.4085   |   0.4414   |   0.5702   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table27"></a>Table 27: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0380__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0059__ | __0.0059__ | __0.0036__ |   0.7549   |   0.5960   |   0.8012   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.1361   | __0.0000__ | __0.0038__ |   0.1321   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.1361   |   1.0000   | __0.0000__ | __0.0002__ | __0.0095__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0380__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0775   | __0.0000__ |   0.2139   |   0.2098   |   0.1543   |   0.1220   |   0.1171   |   0.1023   | __0.0072__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0038__ | __0.0002__ | __0.0000__ |   1.0000   |   0.0979   | __0.0001__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.1321   | __0.0095__ | __0.0000__ |   0.0979   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0004__ | __0.0000__ | __0.0000__ |   0.0775   | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ |   0.7791   |   0.7757   |   0.9475   | __0.0003__ | __0.0009__ | __0.0005__ |   0.3143   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0059__ | __0.0000__ | __0.0000__ |   0.2139   | __0.0001__ | __0.0000__ |   0.7791   | __0.0000__ |   1.0000   |   0.9792   |   0.7949   | __0.0046__ | __0.0069__ | __0.0077__ |   0.2387   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0059__ | __0.0000__ | __0.0000__ |   0.2098   | __0.0001__ | __0.0000__ |   0.7757   | __0.0000__ |   0.9792   |   1.0000   |   0.3177   | __0.0075__ | __0.0062__ | __0.0077__ |   0.2603   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0036__ | __0.0000__ | __0.0000__ |   0.1543   | __0.0002__ | __0.0000__ |   0.9475   | __0.0000__ |   0.7949   |   0.3177   |   1.0000   | __0.0046__ | __0.0037__ | __0.0048__ |   0.3539   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7549   | __0.0000__ | __0.0000__ |   0.1220   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0046__ | __0.0075__ | __0.0046__ |   1.0000   |   0.8901   |   0.9487   | __0.0001__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5960   | __0.0000__ | __0.0000__ |   0.1171   | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0069__ | __0.0062__ | __0.0037__ |   0.8901   |   1.0000   |   0.8330   | __0.0001__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8012   | __0.0000__ | __0.0000__ |   0.1023   | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0077__ | __0.0077__ | __0.0048__ |   0.9487   |   0.8330   |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ | __0.0008__ | __0.0000__ |   0.3143   | __0.0000__ |   0.2387   |   0.2603   |   0.3539   | __0.0001__ | __0.0001__ | __0.0001__ |   1.0000   |

<a name="table28"></a>Table 28: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.7998   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0021__ | __0.0123__ | __0.0011__ |   0.0838   | __0.0056__ | __0.0191__ | __0.0003__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0106__ | __0.0000__ | __0.0324__ |   0.4180   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0106__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7998   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0023__ | __0.0000__ | __0.0126__ | __0.0327__ | __0.0071__ |   0.2085   |   0.0757   |   0.0906   | __0.0010__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0324__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1346   | __0.0015__ | __0.0000__ | __0.0016__ | __0.0005__ | __0.0042__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.4180   | __0.0013__ | __0.0000__ |   0.1346   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0002__ | __0.0000__ | __0.0000__ | __0.0023__ | __0.0015__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8555   |   0.6009   |   0.9086   | __0.0000__ | __0.0000__ | __0.0000__ |   0.6790   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0021__ | __0.0000__ | __0.0000__ | __0.0126__ | __0.0016__ | __0.0000__ |   0.8555   | __0.0000__ |   1.0000   |   0.7123   |   0.7331   | __0.0000__ | __0.0000__ | __0.0000__ |   0.5759   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0123__ | __0.0000__ | __0.0000__ | __0.0327__ | __0.0005__ | __0.0000__ |   0.6009   | __0.0000__ |   0.7123   |   1.0000   |   0.0833   | __0.0012__ | __0.0003__ | __0.0006__ |   0.3940   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0011__ | __0.0000__ | __0.0000__ | __0.0071__ | __0.0042__ | __0.0000__ |   0.9086   | __0.0000__ |   0.7331   |   0.0833   |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ |   0.7904   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0838   | __0.0000__ | __0.0000__ |   0.2085   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0012__ | __0.0001__ |   1.0000   |   0.5200   |   0.4809   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0056__ | __0.0000__ | __0.0000__ |   0.0757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |   0.5200   |   1.0000   |   0.9652   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0191__ | __0.0000__ | __0.0000__ |   0.0906   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ |   0.4809   |   0.9652   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0016__ | __0.0000__ |   0.6790   | __0.0000__ |   0.5759   |   0.3940   |   0.7904   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table29"></a>Table 29: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure71"></a>Figure 71: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure72"></a>Figure 72: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure73"></a>Figure 73: Mean AOE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure74"></a>Figure 74: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure75"></a>Figure 75: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure76"></a>Figure 76: Mean AOE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure77"></a>Figure 77: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure78"></a>Figure 78: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_aoe1.svg">
</figure>

<a name="figure79"></a>Figure 79: Mean AOE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure80"></a>Figure 80: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure81"></a>Figure 81: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_aoe2.svg">
</figure>

<a name="figure82"></a>Figure 82: Mean AOE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure83"></a>Figure 83: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure84"></a>Figure 84: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure85"></a>Figure 85: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure86"></a>Figure 86: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure87"></a>Figure 87: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure88"></a>Figure 88: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure89"></a>Figure 89: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure90"></a>Figure 90: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.svg">
</figure>

<a name="figure91"></a>Figure 91: AOE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure92"></a>Figure 92: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure93"></a>Figure 93: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.svg">
</figure>

<a name="figure94"></a>Figure 94: AOE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 16:43. Size L.
