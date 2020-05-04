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
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Krebs2013](bib/Krebs2013.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/CPJKU/BallroomAnnotations](https://github.com/CPJKU/BallroomAnnotations) |

### 2.0-no-dupes

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 2.0-no-dupes |
| **Curator** | [Florian Krebs](mailto:florian.krebs@jku.at) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals, duplicate tracks removed (http://media.aau.dk/null_space_pursuits/2014/01/ballroom-dataset.html) |
| **Annotator,&nbsp;bibtex** |[Krebs2013](bib/Krebs2013.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/CPJKU/BallroomAnnotations](https://github.com/CPJKU/BallroomAnnotations) |

### 3.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 3.0 |
| **Curator** | [Florian Krebs](mailto:florian.krebs@jku.at) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | based on median of inter corresponding beat intervals |
| **Annotator,&nbsp;bibtex** |[Krebs2013](bib/Krebs2013.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/CPJKU/BallroomAnnotations](https://github.com/CPJKU/BallroomAnnotations) |

### 3.0-no-dupes

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 3.0-no-dupes |
| **Curator** | [Florian Krebs](mailto:florian.krebs@jku.at) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | based on median of inter corresponding beat intervals, duplicate tracks removed (http://media.aau.dk/null_space_pursuits/2014/01/ballroom-dataset.html) |
| **Annotator,&nbsp;bibtex** |[Krebs2013](bib/Krebs2013.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/CPJKU/BallroomAnnotations](https://github.com/CPJKU/BallroomAnnotations) |

### 4.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 4.0 |
| **Curator** | [Graham Percival](mailto:graham@percival-music.ca) |
| **Data&nbsp;Source** | BallroomDancers.com, checked by human |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   698   |   60.00   |   224.00   |   130.14   |   39.53   |   91.00   |   0.71   |
| [2.0](#20)                                         |   698   |   68.85   |   214.29   |   129.80   |   39.69   |   72.00   |   0.71   |
| [2.0-no-dupes](#20-no-dupes)                       |   685   |   68.85   |   214.29   |   130.03   |   39.83   |   72.00   |   0.71   |
| [3.0](#30)                                         |   698   |   68.57   |   214.29   |   129.77   |   39.72   |   72.00   |   0.71   |
| [3.0-no-dupes](#30-no-dupes)                       |   685   |   68.57   |   214.29   |   130.00   |   39.87   |   72.00   |   0.71   |
| [4.0](#40)                                         |   698   |   58.00   |   219.00   |   129.77   |   39.63   |   71.00   |   0.71   |

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

### boeck2019/multi_task

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2019/multi_task_hjdb

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task_hjdb, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

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
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | ballroom |
| **Version** | 0.0.4 |
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
| [boeck2019/multi_task](#boeck2019multi_task)       |   685   |   73.23   |   211.40   |   130.61   |   39.91   |   72.00   |   0.71   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   685   |   52.38   |   212.21   |   130.79   |   39.93   |   73.00   |   0.70   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   698   |   60.09   |   206.72   |   120.29   |   28.62   |   84.00   |   0.87   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   698   |   0.00   |   207.60   |   104.22   |   31.69   |   67.00   |   0.75   |
| [gkiokas2012/default](#gkiokas2012default)         |   698   |   40.00   |   207.00   |   98.23   |   22.77   |   67.00   |   0.86   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   698   |   59.75   |   169.44   |   106.18   |   16.64   |   76.00   |   0.99   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   698   |   83.00   |   167.00   |   106.53   |   17.34   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   698   |   57.90   |   150.34   |   101.91   |   18.04   |   68.00   |   0.96   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   698   |   0.00   |   181.82   |   105.76   |   42.43   |   69.00   |   0.72   |
| [schreiber2014/default](#schreiber2014default)     |   698   |   55.83   |   142.73   |   101.77   |   17.17   |   69.00   |   0.96   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   698   |   60.25   |   208.50   |   122.75   |   36.08   |   72.00   |   0.78   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   698   |   42.27   |   211.97   |   126.02   |   38.12   |   72.00   |   0.74   |
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
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.9370__ |   0.9499   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9341   |   0.9570   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9327   |   0.9470   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9155   | __0.9613__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9126   |   0.9599   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8825   |   0.9527   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8309   |   0.9484   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8052   |   0.9542   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6619   |   0.8968   |
| [schreiber2014/default](#schreiber2014default)     |   0.6433   |   0.9384   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6418   |   0.9212   |
| [percival2014/stem](#percival2014stem)             |   0.6275   |   0.9198   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6232   |   0.9011   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6203   |   0.8782   |
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
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9685__ |   0.9928   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9670   |   0.9814   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9656   |   0.9799   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9470   |   0.9943   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9456   |   0.9900   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9169   |   0.9885   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8682   |   0.9842   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8453   | __1.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6762   |   0.9241   |
| [schreiber2014/default](#schreiber2014default)     |   0.6719   |   0.9728   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6676   |   0.9513   |
| [percival2014/stem](#percival2014stem)             |   0.6576   |   0.9556   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6461   |   0.9284   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6447   |   0.9069   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6304   |   0.9814   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5745   |   0.8739   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5387   |   0.7607   |

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

### Accuracy Results for 2.0-no-dupes

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.9854__ | __1.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9839   |   0.9985   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9679   |   0.9927   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9460   |   0.9942   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9445   |   0.9898   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9153   |   0.9883   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8657   |   0.9839   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8423   | __1.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6730   |   0.9226   |
| [schreiber2014/default](#schreiber2014default)     |   0.6672   |   0.9723   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6642   |   0.9518   |
| [percival2014/stem](#percival2014stem)             |   0.6540   |   0.9547   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6423   |   0.9285   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6409   |   0.9051   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6248   |   0.9810   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5693   |   0.8730   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5416   |   0.7635   |

<a name="table5"></a>Table 5: Mean accuracy of estimates compared to version [2.0-no-dupes](#20-no-dupes) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_2.0-no-dupes_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tolerance.

[CSV](data/ballroom_estimates_2.0-no-dupes_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tolerance.

[CSV](data/ballroom_estimates_2.0-no-dupes_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_accuracy2.png "Open Figure") 

### Accuracy Results for 3.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9699__ |   0.9928   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9670   |   0.9814   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9656   |   0.9799   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9470   |   0.9914   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9470   |   0.9943   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9169   |   0.9885   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8682   |   0.9842   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8453   | __0.9986__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6819   |   0.9284   |
| [schreiber2014/default](#schreiber2014default)     |   0.6719   |   0.9728   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6691   |   0.9527   |
| [percival2014/stem](#percival2014stem)             |   0.6547   |   0.9527   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6461   |   0.9284   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6461   |   0.9097   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6289   |   0.9799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5745   |   0.8739   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5372   |   0.7579   |

<a name="table6"></a>Table 6: Mean accuracy of estimates compared to version [3.0](#30) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_3.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/ballroom_estimates_3.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/ballroom_estimates_3.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_accuracy2.png "Open Figure") 

### Accuracy Results for 3.0-no-dupes

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.9854__ | __1.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9839   |   0.9985   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9693   |   0.9927   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9460   |   0.9912   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9460   |   0.9942   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9153   |   0.9883   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8657   |   0.9839   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8423   |   0.9985   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6788   |   0.9270   |
| [schreiber2014/default](#schreiber2014default)     |   0.6672   |   0.9723   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6657   |   0.9533   |
| [percival2014/stem](#percival2014stem)             |   0.6511   |   0.9518   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6423   |   0.9285   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6423   |   0.9080   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6234   |   0.9796   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5693   |   0.8730   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5401   |   0.7606   |

<a name="table7"></a>Table 7: Mean accuracy of estimates compared to version [3.0-no-dupes](#30-no-dupes) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_3.0-no-dupes_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tolerance.

[CSV](data/ballroom_estimates_3.0-no-dupes_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tolerance.

[CSV](data/ballroom_estimates_3.0-no-dupes_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_accuracy2.png "Open Figure") 

### Accuracy Results for 4.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9570__ | __0.9871__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.9542   |   0.9756   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.9513   |   0.9756   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9341   | __0.9871__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9327   | __0.9871__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9054   |   0.9842   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8539   |   0.9799   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8324   | __0.9871__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6762   |   0.9169   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6691   |   0.9484   |
| [schreiber2014/default](#schreiber2014default)     |   0.6676   |   0.9670   |
| [percival2014/stem](#percival2014stem)             |   0.6562   |   0.9499   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6490   |   0.9284   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6433   |   0.9026   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6318   |   0.9799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5702   |   0.8653   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5372   |   0.7564   |

<a name="table8"></a>Table 8: Mean accuracy of estimates compared to version [4.0](#40) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ballroom_estimates_4.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ballroom_estimates_4.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ballroom_estimates_4.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_accuracy1.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>1</sub> for estimates compared to version [4.0](#40) depending on tolerance.

[CSV](data/ballroom_estimates_4.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> for estimates compared to version [4.0](#40) depending on tolerance.

[CSV](data/ballroom_estimates_4.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (136 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (44 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Latin\_Jam-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (47 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Latin\_Jam-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

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

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (118 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (82 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-03' ...
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

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (23 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (24 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (226 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-15' ...
[CSV](data/ballroom_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (297 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (258 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (247 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (248 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (239 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (322 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' ...
[CSV](data/ballroom_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (229 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (92 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-07' 'Albums-Fire-13' 'Albums-Latin\_Jam-12' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (22 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Macumba-16' 'Media-103302' 'Media-103315' 'Media-103618' 'Media-103711' 'Media-103715' 'Media-103905' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (38 differences):*
'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' 'Albums-Macumba-16' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (37 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Latin\_Jam3-11' 'Albums-Latin\_Jam3-12' ...
[CSV](data/ballroom_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (232 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (108 differences):*
'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2019/multi_task](#boeck2019multi_task) (10 differences):*
'Albums-Chrisanne3-03' 'Albums-Mambo\_Kings-10' 'Albums-Step\_By\_Step-16' 'Media-103606' 'Media-103614' 'Media-103715' 'Media-103905' 'Media-105207' 'Media-105403' 'Media-106009' 
[CSV](data/ballroom_estimates_2.0-no-dupes_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (11 differences):*
'Albums-Chrisanne3-03' 'Albums-Mambo\_Kings-10' 'Media-103606' 'Media-103715' 'Media-103905' 'Media-104418' 'Media-105207' 'Media-105302' 'Media-105403' 'Media-106009' 'Media-106118' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (224 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-15' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (295 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [gkiokas2012/default](#gkiokas2012default) (257 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (245 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [oliveira2010/ibt](#oliveira2010ibt) (246 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [percival2014/stem](#percival2014stem) (237 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (314 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2014/default](#schreiber2014default) (228 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (92 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-07' 'Albums-Fire-13' 'Albums-Latin\_Jam-12' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/cnn](#schreiber2018cnn) (22 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Macumba-16' 'Media-103302' 'Media-103315' 'Media-103618' 'Media-103711' 'Media-103715' 'Media-103905' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/fcn](#schreiber2018fcn) (38 differences):*
'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' 'Albums-Macumba-16' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (37 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Latin\_Jam3-11' 'Albums-Latin\_Jam3-12' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (230 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (108 differences):*
'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (23 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (24 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_3.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (222 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-15' ...
[CSV](data/ballroom_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (297 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (259 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (247 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (247 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (241 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (323 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' ...
[CSV](data/ballroom_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (229 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (92 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-07' 'Albums-Fire-13' 'Albums-Latin\_Jam-12' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (21 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Macumba-16' 'Media-103302' 'Media-103315' 'Media-103618' 'Media-103711' 'Media-103715' 'Media-103905' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (37 differences):*
'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' 'Albums-Macumba-16' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (37 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Latin\_Jam3-11' 'Albums-Latin\_Jam3-12' ...
[CSV](data/ballroom_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (231 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (108 differences):*
'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2019/multi_task](#boeck2019multi_task) (10 differences):*
'Albums-Chrisanne3-03' 'Albums-Mambo\_Kings-10' 'Albums-Step\_By\_Step-16' 'Media-103606' 'Media-103614' 'Media-103715' 'Media-103905' 'Media-105207' 'Media-105403' 'Media-106009' 
[CSV](data/ballroom_estimates_3.0-no-dupes_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (11 differences):*
'Albums-Chrisanne3-03' 'Albums-Mambo\_Kings-10' 'Media-103606' 'Media-103715' 'Media-103905' 'Media-104418' 'Media-105207' 'Media-105302' 'Media-105403' 'Media-106009' 'Media-106118' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (220 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-15' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (295 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [gkiokas2012/default](#gkiokas2012default) (258 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (245 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [oliveira2010/ibt](#oliveira2010ibt) (245 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [percival2014/stem](#percival2014stem) (239 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (315 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2014/default](#schreiber2014default) (228 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-09' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (92 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-07' 'Albums-Fire-13' 'Albums-Latin\_Jam-12' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/cnn](#schreiber2018cnn) (21 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Macumba-16' 'Media-103302' 'Media-103315' 'Media-103618' 'Media-103711' 'Media-103715' 'Media-103905' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/fcn](#schreiber2018fcn) (37 differences):*
'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' 'Albums-Macumba-16' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (37 differences):*
'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' 'Albums-Latin\_Jam3-11' 'Albums-Latin\_Jam3-12' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (229 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (117 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-14' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-12' ...
[CSV](data/ballroom_estimates_4.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2019/multi_task](#boeck2019multi_task) (32 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' ...
[CSV](data/ballroom_estimates_4.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (34 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' ...
[CSV](data/ballroom_estimates_4.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (226 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_4.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (300 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' ...
[CSV](data/ballroom_estimates_4.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [gkiokas2012/default](#gkiokas2012default) (257 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-09' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' ...
[CSV](data/ballroom_estimates_4.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (245 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_4.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [oliveira2010/ibt](#oliveira2010ibt) (249 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' ...
[CSV](data/ballroom_estimates_4.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [percival2014/stem](#percival2014stem) (240 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-13' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' ...
[CSV](data/ballroom_estimates_4.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (323 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-11' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-08' 'Albums-Ballroom\_Classics4-11' ...
[CSV](data/ballroom_estimates_4.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2014/default](#schreiber2014default) (232 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' 'Albums-Ballroom\_Magic-04' ...
[CSV](data/ballroom_estimates_4.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (102 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-16' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-13' ...
[CSV](data/ballroom_estimates_4.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (66 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-19' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Commitments-10' 'Albums-Fire-07' ...
[CSV](data/ballroom_estimates_4.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/cnn](#schreiber2018cnn) (30 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' 'Albums-Macumba-16' 'Albums-Secret\_Garden-05' 'Albums-Step\_By\_Step-15' 'Albums-Step\_By\_Step-16' ...
[CSV](data/ballroom_estimates_4.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/fcn](#schreiber2018fcn) (46 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Cafe\_Paradiso-02' 'Albums-Chrisanne2-11' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-13' 'Albums-Latin\_Jam3-04' 'Albums-Latin\_Jam3-05' 'Albums-Latin\_Jam4-02' ...
[CSV](data/ballroom_estimates_4.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (47 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-15' 'Albums-Ballroom\_Magic-17' 'Albums-Cafe\_Paradiso-15' 'Albums-Chrisanne2-07' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-08' 'Albums-Chrisanne3-09' 'Albums-Chrisanne3-15' ...
[CSV](data/ballroom_estimates_4.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[4.0](#40) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (231 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-12' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Classics4-14' 'Albums-Ballroom\_Classics4-18' 'Albums-Ballroom\_Classics4-19' 'Albums-Ballroom\_Classics4-20' ...
[CSV](data/ballroom_estimates_4.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (32 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-05' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-05' ...
[CSV](data/ballroom_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (35 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Latin\_Jam-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (37 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Chrisanne3-03' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Latin\_Jam-13' ...
[CSV](data/ballroom_estimates_1.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

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

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (36 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-Fire-13' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' ...
[CSV](data/ballroom_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (33 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Chrisanne3-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-03' 'Albums-Fire-09' 'Albums-Fire-13' 'Albums-GloriaEstefan\_MiTierra-06' 'Albums-GloriaEstefan\_MiTierra-08' 'Albums-GloriaEstefan\_MiTierra-11' 'Albums-Secret\_Garden-01' ...
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

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (13 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' 'Media-103414' ...
[CSV](data/ballroom_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (14 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' 'Media-103414' ...
[CSV](data/ballroom_estimates_2.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (53 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' ...
[CSV](data/ballroom_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (88 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-03' ...
[CSV](data/ballroom_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (13 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-02' 'Media-103710' 'Media-103905' 'Media-104711' 'Media-105002' 'Media-105007' 'Media-105111' ...
[CSV](data/ballroom_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (65 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (31 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100604' 'Media-100609' ...
[CSV](data/ballroom_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (167 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (19 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' 'Media-104703' 'Media-104811' ...
[CSV](data/ballroom_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (11 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-104303' 'Media-104608' 'Media-105004' 'Media-105420' 'Media-105701' 'Media-105702' ...
[CSV](data/ballroom_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (8 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103315' 'Media-104303' 'Media-104608' 'Media-105214' 'Media-105420' 
[CSV](data/ballroom_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (5 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103315' 'Media-104905' 'Media-105302' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (7 differences):*
'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103905' 'Media-105002' 'Media-105302' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (4 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103905' 'Media-105911' 
[CSV](data/ballroom_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (34 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100603' ...
[CSV](data/ballroom_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2019/multi_task](#boeck2019multi_task): No differences.*

*[2.0-no-dupes](#20-no-dupes) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (1 differences):*
'Media-105302' 
[CSV](data/ballroom_estimates_2.0-no-dupes_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (53 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (87 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-03' 'Albums-Chrisanne1-07' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [gkiokas2012/default](#gkiokas2012default) (13 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-02' 'Media-103710' 'Media-103905' 'Media-104711' 'Media-105002' 'Media-105007' 'Media-105111' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (49 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [oliveira2010/ibt](#oliveira2010ibt) (65 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [percival2014/stem](#percival2014stem) (31 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100604' 'Media-100609' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (162 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2014/default](#schreiber2014default) (19 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' 'Media-104703' 'Media-104811' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (11 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-104303' 'Media-104608' 'Media-105004' 'Media-105420' 'Media-105701' 'Media-105702' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (8 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103315' 'Media-104303' 'Media-104608' 'Media-105214' 'Media-105420' 
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/cnn](#schreiber2018cnn) (5 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103315' 'Media-104905' 'Media-105302' 
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/fcn](#schreiber2018fcn) (7 differences):*
'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103905' 'Media-105002' 'Media-105302' 
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (4 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103905' 'Media-105911' 
[CSV](data/ballroom_estimates_2.0-no-dupes_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0-no-dupes](#20-no-dupes) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (33 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100603' ...
[CSV](data/ballroom_estimates_2.0-no-dupes_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1 differences):*
'Media-103905' 
[CSV](data/ballroom_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (13 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' 'Media-103414' ...
[CSV](data/ballroom_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (14 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' 'Media-103414' ...
[CSV](data/ballroom_estimates_3.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' ...
[CSV](data/ballroom_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (88 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-03' ...
[CSV](data/ballroom_estimates_3.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [gkiokas2012/default](#gkiokas2012default) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-02' 'Media-103710' 'Media-103905' 'Media-104711' 'Media-105002' 'Media-105007' ...
[CSV](data/ballroom_estimates_3.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_3.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [oliveira2010/ibt](#oliveira2010ibt) (63 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_3.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (33 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100604' 'Media-100609' ...
[CSV](data/ballroom_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (169 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_3.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (19 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' 'Media-104703' 'Media-104811' ...
[CSV](data/ballroom_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (11 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-104303' 'Media-104608' 'Media-105004' 'Media-105420' 'Media-105701' 'Media-105702' ...
[CSV](data/ballroom_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (8 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103315' 'Media-104303' 'Media-104608' 'Media-105214' 'Media-105420' 
[CSV](data/ballroom_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (5 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103315' 'Media-103905' 'Media-104905' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (6 differences):*
'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103905' 'Media-105002' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (4 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103905' 'Media-105911' 
[CSV](data/ballroom_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (33 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100603' ...
[CSV](data/ballroom_estimates_3.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1 differences):*
'Media-103905' 
[CSV](data/ballroom_estimates_3.0-no-dupes_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2019/multi_task](#boeck2019multi_task): No differences.*

*[3.0-no-dupes](#30-no-dupes) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (1 differences):*
'Media-105302' 
[CSV](data/ballroom_estimates_3.0-no-dupes_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Latino\_Latino-03' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (87 differences):*
'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-03' 'Albums-Chrisanne1-07' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [gkiokas2012/default](#gkiokas2012default) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-02' 'Media-103710' 'Media-103905' 'Media-104711' 'Media-105002' 'Media-105007' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (49 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [oliveira2010/ibt](#oliveira2010ibt) (63 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [percival2014/stem](#percival2014stem) (33 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100604' 'Media-100609' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (164 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-10' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2014/default](#schreiber2014default) (19 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' 'Media-104703' 'Media-104811' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (11 differences):*
'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-104303' 'Media-104608' 'Media-105004' 'Media-105420' 'Media-105701' 'Media-105702' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (8 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103315' 'Media-104303' 'Media-104608' 'Media-105214' 'Media-105420' 
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/cnn](#schreiber2018cnn) (5 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103315' 'Media-103905' 'Media-104905' 
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/fcn](#schreiber2018fcn) (6 differences):*
'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Media-103905' 'Media-105002' 
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (4 differences):*
'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Media-103905' 'Media-105911' 
[CSV](data/ballroom_estimates_3.0-no-dupes_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0-no-dupes](#30-no-dupes) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (32 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' 'Media-100603' ...
[CSV](data/ballroom_estimates_3.0-no-dupes_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-05' 'Albums-Secret\_Garden-05' 'Albums-StrictlyDancing\_Tango-08' 'Media-103905' 'Media-104404' 'Media-104908' 'Media-105007' 'Media-105101' 
[CSV](data/ballroom_estimates_4.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2019/multi_task](#boeck2019multi_task) (17 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_4.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (17 differences):*
'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne2-12' 'Albums-Fire-09' 'Albums-Latin\_Jam-13' 'Albums-Latin\_Jam-14' 'Albums-Latin\_Jam-15' 'Albums-Latin\_Jam2-13' 'Albums-Latin\_Jam2-14' 'Albums-Latin\_Jam2-15' ...
[CSV](data/ballroom_estimates_4.0_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (58 differences):*
'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-14' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' 'Albums-Chrisanne3-02' 'Albums-Chrisanne3-07' ...
[CSV](data/ballroom_estimates_4.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (94 differences):*
'Albums-AnaBelen\_Veneo-11' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Ballroom\_Magic-07' 'Albums-Ballroom\_Magic-18' 'Albums-Chrisanne1-01' ...
[CSV](data/ballroom_estimates_4.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [gkiokas2012/default](#gkiokas2012default) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne1-03' 'Albums-Chrisanne2-01' 'Albums-Chrisanne3-15' 'Albums-Latino\_Latino-03' 'Albums-Secret\_Garden-05' 'Media-103710' 'Media-103905' 'Media-103911' 'Media-104601' 'Media-104711' ...
[CSV](data/ballroom_estimates_4.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-11' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-01' 'Albums-Chrisanne1-02' 'Albums-Chrisanne1-08' 'Albums-Chrisanne2-01' 'Albums-Chrisanne2-03' ...
[CSV](data/ballroom_estimates_4.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [oliveira2010/ibt](#oliveira2010ibt) (68 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-13' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-05' 'Albums-Cafe\_Paradiso-16' 'Albums-Chrisanne1-12' 'Albums-Chrisanne1-14' ...
[CSV](data/ballroom_estimates_4.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [percival2014/stem](#percival2014stem) (35 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' 'Albums-Chrisanne1-13' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' ...
[CSV](data/ballroom_estimates_4.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (170 differences):*
'Albums-AnaBelen\_Veneo-03' 'Albums-AnaBelen\_Veneo-15' 'Albums-Ballroom\_Classics4-01' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Classics4-05' 'Albums-Ballroom\_Classics4-07' 'Albums-Ballroom\_Classics4-13' 'Albums-Ballroom\_Magic-01' 'Albums-Ballroom\_Magic-02' 'Albums-Ballroom\_Magic-04' 'Albums-Ballroom\_Magic-05' ...
[CSV](data/ballroom_estimates_4.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2014/default](#schreiber2014default) (23 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-103308' 'Media-103315' 'Media-104302' 'Media-104608' ...
[CSV](data/ballroom_estimates_4.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (14 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-104303' 'Media-104608' 'Media-105004' 'Media-105007' ...
[CSV](data/ballroom_estimates_4.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (11 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-103315' 'Media-104303' 'Media-104608' 'Media-105007' 'Media-105214' 'Media-105420' ...
[CSV](data/ballroom_estimates_4.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/cnn](#schreiber2018cnn) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Media-103315' 'Media-103709' 'Media-103905' 'Media-104905' 'Media-105007' 
[CSV](data/ballroom_estimates_4.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/fcn](#schreiber2018fcn) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-09' 'Albums-Commitments-11' 'Albums-Fire-13' 'Albums-Secret\_Garden-05' 'Media-103905' 'Media-103911' 'Media-105007' 'Media-105211' 
[CSV](data/ballroom_estimates_4.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (9 differences):*
'Albums-Ballroom\_Classics4-03' 'Albums-Chrisanne3-07' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-05' 'Albums-StrictlyDancing\_Tango-11' 'Media-103905' 'Media-103911' 'Media-105007' 'Media-105911' 
[CSV](data/ballroom_estimates_4.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[4.0](#40) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (36 differences):*
'Albums-AnaBelen\_Veneo-02' 'Albums-Ballroom\_Classics4-02' 'Albums-Ballroom\_Classics4-03' 'Albums-Ballroom\_Magic-04' 'Albums-Chrisanne1-14' 'Albums-Chrisanne3-01' 'Albums-Chrisanne3-09' 'Albums-Secret\_Garden-02' 'Albums-Secret\_Garden-05' 'Albums-Secret\_Garden-06' 'Albums-Step\_By\_Step-04' ...
[CSV](data/ballroom_estimates_4.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1176   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.3750   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8776   |   0.0534   | __0.0300__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.3750   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1263   |   0.0869   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0009__ | __0.0120__ | __0.0045__ | __0.0437__ | __0.0000__ |   0.3223   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2314   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0144__ | __0.0001__ | __0.0002__ | __0.0000__ |   0.2664   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ | __0.0144__ |   1.0000   |   0.1058   |   0.1800   | __0.0295__ | __0.0012__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0021__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0120__ | __0.0001__ |   0.1058   |   1.0000   |   0.8776   |   0.7838   | __0.0000__ |   0.0925   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0596   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0045__ | __0.0002__ |   0.1800   |   0.8776   |   1.0000   |   0.6085   | __0.0000__ |   0.0894   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0489__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0437__ | __0.0000__ | __0.0295__ |   0.7838   |   0.6085   |   1.0000   | __0.0000__ |   0.1925   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2203   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2664   | __0.0012__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.3223   | __0.0000__ | __0.0005__ |   0.0925   |   0.0894   |   0.1925   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1176   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0095__ | __0.0170__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.8776   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0660   | __0.0237__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.0534   |   0.1263   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0095__ |   0.0660   |   1.0000   |   0.8776   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0300__ |   0.0869   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0170__ | __0.0237__ |   0.8776   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2314   | __0.0000__ | __0.0021__ |   0.0596   | __0.0489__ |   0.2203   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table9"></a>Table 9: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.8746   |   0.0759   |   0.0704   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.7493   |   0.0919   |   0.0984   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0059__ | __0.0215__ | __0.0180__ |   0.1186   | __0.0000__ |   0.6320   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4812   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0067__ | __0.0001__ | __0.0001__ | __0.0000__ |   0.1037   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ | __0.0067__ |   1.0000   |   0.2410   |   0.2566   | __0.0356__ | __0.0001__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0029__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0215__ | __0.0001__ |   0.2410   |   1.0000   |   1.0000   |   0.5044   | __0.0000__ | __0.0385__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0226__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0180__ | __0.0001__ |   0.2566   |   1.0000   |   1.0000   |   0.5115   | __0.0000__ |   0.0512   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.1186   | __0.0000__ | __0.0356__ |   0.5044   |   0.5115   |   1.0000   | __0.0000__ |   0.1619   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2203   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1037   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.6320   | __0.0000__ | __0.0005__ | __0.0385__ |   0.0512   |   0.1619   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8955   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0170__ | __0.0154__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.8746   |   0.7493   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0090__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.0759   |   0.0919   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0170__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.0704   |   0.0984   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0154__ | __0.0090__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.4812   | __0.0000__ | __0.0029__ | __0.0226__ | __0.0365__ |   0.2203   | __0.0000__ |   0.8955   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table10"></a>Table 10: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0522   | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0755   | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0045__ | __0.0215__ | __0.0180__ |   0.1158   | __0.0000__ |   0.5752   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4812   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0081__ | __0.0001__ | __0.0001__ | __0.0000__ |   0.2083   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0045__ | __0.0081__ |   1.0000   |   0.1983   |   0.2134   | __0.0248__ | __0.0003__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0019__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0215__ | __0.0001__ |   0.1983   |   1.0000   |   1.0000   |   0.4966   | __0.0000__ | __0.0498__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0226__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0180__ | __0.0001__ |   0.2134   |   1.0000   |   1.0000   |   0.5044   | __0.0000__ |   0.0647   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.1158   | __0.0000__ | __0.0248__ |   0.4966   |   0.5044   |   1.0000   | __0.0000__ |   0.2000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2116   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2083   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.5752   | __0.0000__ | __0.0005__ | __0.0498__ |   0.0647   |   0.2000   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0170__ | __0.0154__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.0522   |   0.0755   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0090__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0170__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0154__ | __0.0090__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.4812   | __0.0000__ | __0.0019__ | __0.0226__ | __0.0365__ |   0.2116   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table11"></a>Table 11: McNemar p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0581   |   0.0704   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.8714   |   0.0649   |   0.0984   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0174__ |   0.0554   | __0.0357__ |   0.2981   | __0.0000__ |   0.8732   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6610   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0055__ | __0.0001__ | __0.0001__ | __0.0000__ |   0.1190   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0174__ | __0.0055__ |   1.0000   |   0.2891   |   0.3481   | __0.0248__ | __0.0001__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0058__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0554   | __0.0001__ |   0.2891   |   1.0000   |   1.0000   |   0.3409   | __0.0000__ | __0.0385__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ | __0.0001__ |   0.3481   |   1.0000   |   1.0000   |   0.2976   | __0.0000__ | __0.0402__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2981   | __0.0000__ | __0.0248__ |   0.3409   |   0.2976   |   1.0000   | __0.0000__ |   0.2451   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4188   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1190   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.8732   | __0.0000__ | __0.0008__ | __0.0385__ | __0.0402__ |   0.2451   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7946   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0245__ | __0.0154__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   1.0000   |   0.8714   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0167__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.0581   |   0.0649   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0245__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.0704   |   0.0984   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0154__ | __0.0167__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.6610   | __0.0000__ | __0.0058__ | __0.0357__ | __0.0365__ |   0.4188   | __0.0000__ |   0.7946   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table12"></a>Table 12: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0433__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0138__ |   0.0554   | __0.0357__ |   0.2944   | __0.0000__ |   0.8102   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6610   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0067__ | __0.0001__ | __0.0001__ | __0.0000__ |   0.2343   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0138__ | __0.0067__ |   1.0000   |   0.2410   |   0.2945   | __0.0169__ | __0.0003__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0039__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0554   | __0.0001__ |   0.2410   |   1.0000   |   1.0000   |   0.3317   | __0.0000__ | __0.0498__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ | __0.0001__ |   0.2945   |   1.0000   |   1.0000   |   0.2892   | __0.0000__ |   0.0512   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0365__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2944   | __0.0000__ | __0.0169__ |   0.3317   |   0.2892   |   1.0000   | __0.0000__ |   0.2976   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4101   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2343   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.8102   | __0.0000__ | __0.0008__ | __0.0498__ |   0.0512   |   0.2976   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8955   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1637   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0245__ | __0.0154__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0357__ | __0.0433__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0167__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0245__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0154__ | __0.0167__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.6610   | __0.0000__ | __0.0039__ | __0.0357__ | __0.0365__ |   0.4101   | __0.0000__ |   0.8955   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table13"></a>Table 13: McNemar p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2031   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.6250   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.8776   |   0.0759   |   0.0581   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.6250   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   0.6358   |   0.1189   |   0.1048   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0195__ |   0.0818   | __0.0286__ |   0.2578   | __0.0000__ |   0.6851   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7183   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ | __0.0001__ | __0.0000__ |   0.1478   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0195__ | __0.0020__ |   1.0000   |   0.2410   |   0.4750   | __0.0498__ | __0.0000__ | __0.0035__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0064__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0818   | __0.0000__ |   0.2410   |   1.0000   |   0.6358   |   0.5901   | __0.0000__ |   0.1299   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0286__ | __0.0001__ |   0.4750   |   0.6358   |   1.0000   |   0.2976   | __0.0000__ |   0.0647   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0175__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2578   | __0.0000__ | __0.0498__ |   0.5901   |   0.2976   |   1.0000   | __0.0000__ |   0.3581   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2624   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1478   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.6851   | __0.0000__ | __0.0035__ |   0.1299   |   0.0647   |   0.3581   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2031   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0001__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0245__ | __0.0319__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.8776   |   0.6358   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0195__ | __0.0076__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.0759   |   0.1189   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0245__ | __0.0195__ |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.0581   |   0.1048   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0319__ | __0.0076__ |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.7183   | __0.0000__ | __0.0064__ | __0.0436__ | __0.0175__ |   0.2624   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table14"></a>Table 14: McNemar p-values, using reference annotations [4.0](#40) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6776   |   0.4049   | __0.0000__ | __0.0000__ |   0.1671   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0433__ |   0.4807   |   1.0000   |   0.8036   |   0.2668   |   0.4240   | __0.0002__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.6776   |   1.0000   |   0.5000   | __0.0000__ | __0.0000__ |   0.5847   | __0.0000__ | __0.0000__ | __0.0031__ | __0.0000__ |   0.2295   |   1.0000   |   0.8388   |   0.4049   |   0.1153   |   0.2100   | __0.0037__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.4049   |   0.5000   |   1.0000   | __0.0001__ | __0.0000__ |   0.8555   | __0.0000__ | __0.0000__ | __0.0079__ | __0.0000__ |   0.3915   |   1.0000   |   0.5413   |   0.2100   |   0.0525   |   0.1078   | __0.0096__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ |   0.8041   |   0.1237   | __0.0365__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0363__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0034__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1671   |   0.5847   |   0.8555   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0115__ | __0.0000__ |   0.6177   |   0.6900   |   0.2863   |   0.0931   | __0.0075__ | __0.0127__ | __0.0166__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.8041   | __0.0000__ | __0.0000__ |   1.0000   | __0.0402__ |   0.0854   | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1237   | __0.0034__ | __0.0000__ | __0.0402__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0031__ | __0.0079__ | __0.0365__ | __0.0000__ | __0.0115__ |   0.0854   | __0.0002__ |   1.0000   | __0.0000__ |   0.0533   | __0.0017__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0433__ |   0.2295   |   0.3915   | __0.0004__ | __0.0000__ |   0.6177   | __0.0003__ | __0.0000__ |   0.0533   | __0.0000__ |   1.0000   |   0.0923   | __0.0309__ | __0.0106__ | __0.0015__ | __0.0059__ |   0.0961   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4807   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   0.6900   | __0.0000__ | __0.0000__ | __0.0017__ | __0.0000__ |   0.0923   |   1.0000   |   0.4531   |   0.2379   | __0.0352__ |   0.0768   | __0.0034__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   0.8388   |   0.5413   | __0.0000__ | __0.0000__ |   0.2863   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0309__ |   0.4531   |   1.0000   |   0.5488   |   0.1460   |   0.2668   | __0.0005__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8036   |   0.4049   |   0.2100   | __0.0000__ | __0.0000__ |   0.0931   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0106__ |   0.2379   |   0.5488   |   1.0000   |   0.5078   |   0.7539   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2668   |   0.1153   |   0.0525   | __0.0000__ | __0.0000__ | __0.0075__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0352__ |   0.1460   |   0.5078   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4240   |   0.2100   |   0.1078   | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ |   0.0768   |   0.2668   |   0.7539   |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0002__ | __0.0037__ | __0.0096__ | __0.0363__ | __0.0000__ | __0.0166__ | __0.0436__ | __0.0002__ |   1.0000   | __0.0000__ |   0.0961   | __0.0034__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table15"></a>Table 15: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0018__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0391__ |   0.1250   |   0.0625   |   0.2500   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0018__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0045__ | __0.0000__ |   0.3771   |   0.8388   |   0.3833   |   0.0963   |   0.1671   | __0.0490__ | __0.0037__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0010__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0066__ | __0.0000__ |   0.4869   |   0.6900   |   0.2863   |   0.0636   |   0.1153   | __0.0309__ | __0.0054__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0984   | __0.0046__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0186__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0046__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0002__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ |   0.4869   |   0.6900   |   0.2863   | __0.0490__ |   0.0768   | __0.0213__ | __0.0019__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0919   | __0.0213__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0115__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.0984   | __0.0046__ | __0.0000__ |   0.0919   |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0045__ | __0.0066__ | __0.0046__ | __0.0000__ | __0.0019__ | __0.0213__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0385__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.3771   |   0.4869   | __0.0000__ | __0.0000__ |   0.4869   | __0.0000__ | __0.0000__ | __0.0385__ | __0.0000__ |   1.0000   | __0.0215__ | __0.0074__ | __0.0013__ | __0.0072__ | __0.0007__ | __0.0385__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0063__ |   0.8388   |   0.6900   | __0.0000__ | __0.0000__ |   0.6900   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0215__ |   1.0000   |   0.4531   |   0.1460   |   0.2668   |   0.0654   | __0.0005__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0391__ |   0.3833   |   0.2863   | __0.0000__ | __0.0000__ |   0.2863   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |   0.4531   |   1.0000   |   0.4531   |   0.7539   |   0.2891   | __0.0001__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1250   |   0.0963   |   0.0636   | __0.0000__ | __0.0000__ | __0.0490__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.1460   |   0.4531   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0625   |   0.1671   |   0.1153   | __0.0000__ | __0.0000__ |   0.0768   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ |   0.2668   |   0.7539   |   1.0000   |   1.0000   |   0.6875   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2500   | __0.0490__ | __0.0309__ | __0.0000__ | __0.0000__ | __0.0213__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ |   0.0654   |   0.2891   |   1.0000   |   0.6875   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0037__ | __0.0054__ | __0.0186__ | __0.0000__ | __0.0019__ | __0.0115__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0385__ | __0.0005__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table16"></a>Table 16: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0391__ |   0.1250   |   0.0625   |   0.2500   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0078__ |   0.0625   | __0.0312__ |   0.1250   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0391__ |   0.2188   |   0.1250   |   0.3750   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0984   | __0.0046__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0114__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0063__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0002__ | __0.0001__ | __0.0010__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ |   0.4869   |   0.6900   |   0.2863   | __0.0490__ |   0.0768   | __0.0213__ | __0.0029__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   |   0.0649   | __0.0293__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0115__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.0984   | __0.0063__ | __0.0000__ |   0.0649   |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0046__ | __0.0000__ | __0.0019__ | __0.0293__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0385__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4869   | __0.0001__ | __0.0000__ | __0.0385__ | __0.0000__ |   1.0000   | __0.0215__ | __0.0074__ | __0.0013__ | __0.0072__ | __0.0007__ |   0.0533   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0063__ | __0.0010__ | __0.0063__ | __0.0000__ | __0.0000__ |   0.6900   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0215__ |   1.0000   |   0.4531   |   0.1460   |   0.2668   |   0.0654   | __0.0008__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0391__ | __0.0078__ | __0.0391__ | __0.0000__ | __0.0000__ |   0.2863   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |   0.4531   |   1.0000   |   0.4531   |   0.7539   |   0.2891   | __0.0001__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1250   |   0.0625   |   0.2188   | __0.0000__ | __0.0000__ | __0.0490__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.1460   |   0.4531   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0625   | __0.0312__ |   0.1250   | __0.0000__ | __0.0000__ |   0.0768   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ |   0.2668   |   0.7539   |   1.0000   |   1.0000   |   0.6875   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2500   |   0.1250   |   0.3750   | __0.0000__ | __0.0000__ | __0.0213__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ |   0.0654   |   0.2891   |   1.0000   |   0.6875   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0114__ | __0.0000__ | __0.0029__ | __0.0115__ | __0.0001__ |   1.0000   | __0.0000__ |   0.0533   | __0.0008__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table17"></a>Table 17: McNemar p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0002__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0078__ |   0.0625   | __0.0156__ |   0.1250   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0002__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0096__ | __0.0000__ |   0.3771   |   0.8388   |   0.3833   |   0.0963   |   0.2632   | __0.0490__ | __0.0025__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0001__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0137__ | __0.0000__ |   0.4869   |   0.6900   |   0.2863   | __0.0490__ |   0.1671   | __0.0309__ | __0.0037__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ |   0.7877   |   0.1263   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0110__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0086__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0002__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0029__ | __0.0000__ |   0.3771   |   0.8388   |   0.3833   |   0.0963   |   0.2101   | __0.0352__ | __0.0005__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.7877   | __0.0000__ | __0.0000__ |   1.0000   |   0.0534   | __0.0079__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0195__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1263   | __0.0086__ | __0.0000__ |   0.0534   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0096__ | __0.0137__ | __0.0003__ | __0.0000__ | __0.0029__ | __0.0079__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0730   | __0.0008__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7428   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.3771   |   0.4869   | __0.0000__ | __0.0000__ |   0.3771   | __0.0000__ | __0.0000__ |   0.0730   | __0.0000__ |   1.0000   | __0.0215__ | __0.0074__ | __0.0013__ | __0.0169__ | __0.0007__ | __0.0275__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0010__ |   0.8388   |   0.6900   | __0.0000__ | __0.0000__ |   0.8388   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ | __0.0215__ |   1.0000   |   0.4531   |   0.1460   |   0.4240   |   0.0654   | __0.0003__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0078__ |   0.3833   |   0.2863   | __0.0000__ | __0.0000__ |   0.3833   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0074__ |   0.4531   |   1.0000   |   0.4531   |   1.0000   |   0.2891   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0625   |   0.0963   | __0.0490__ | __0.0000__ | __0.0000__ |   0.0963   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.1460   |   0.4531   |   1.0000   |   0.7266   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0156__ |   0.2632   |   0.1671   | __0.0000__ | __0.0000__ |   0.2101   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0169__ |   0.4240   |   1.0000   |   0.7266   |   1.0000   |   0.4531   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1250   | __0.0490__ | __0.0309__ | __0.0000__ | __0.0000__ | __0.0352__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ |   0.0654   |   0.2891   |   1.0000   |   0.4531   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0025__ | __0.0037__ | __0.0110__ | __0.0000__ | __0.0005__ | __0.0195__ | __0.0001__ |   0.7428   | __0.0000__ | __0.0275__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table18"></a>Table 18: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0078__ |   0.0625   | __0.0156__ |   0.1250   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0078__ |   0.0625   | __0.0156__ |   0.1250   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0391__ |   0.1250   | __0.0312__ |   0.3750   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ |   0.6835   |   0.1263   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0066__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0115__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0002__ | __0.0002__ | __0.0018__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0029__ | __0.0000__ |   0.3771   |   0.8388   |   0.3833   |   0.0963   |   0.2101   | __0.0352__ | __0.0008__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.6835   | __0.0000__ | __0.0000__ |   1.0000   | __0.0365__ | __0.0114__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0195__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1263   | __0.0115__ | __0.0000__ | __0.0365__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0029__ | __0.0114__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0730   | __0.0008__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8679   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3771   | __0.0001__ | __0.0000__ |   0.0730   | __0.0000__ |   1.0000   | __0.0215__ | __0.0074__ | __0.0013__ | __0.0169__ | __0.0007__ | __0.0385__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0010__ | __0.0010__ | __0.0063__ | __0.0000__ | __0.0000__ |   0.8388   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ | __0.0215__ |   1.0000   |   0.4531   |   0.1460   |   0.4240   |   0.0654   | __0.0005__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0078__ | __0.0078__ | __0.0391__ | __0.0000__ | __0.0000__ |   0.3833   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0074__ |   0.4531   |   1.0000   |   0.4531   |   1.0000   |   0.2891   | __0.0001__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0625   |   0.0625   |   0.1250   | __0.0000__ | __0.0000__ |   0.0963   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.1460   |   0.4531   |   1.0000   |   0.7266   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0156__ | __0.0156__ | __0.0312__ | __0.0000__ | __0.0000__ |   0.2101   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0169__ |   0.4240   |   1.0000   |   0.7266   |   1.0000   |   0.4531   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1250   |   0.1250   |   0.3750   | __0.0000__ | __0.0000__ | __0.0352__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ |   0.0654   |   0.2891   |   1.0000   |   0.4531   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0066__ | __0.0000__ | __0.0008__ | __0.0195__ | __0.0001__ |   0.8679   | __0.0000__ | __0.0385__ | __0.0005__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table19"></a>Table 19: McNemar p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1153   |   0.1153   | __0.0000__ | __0.0000__ |   0.3018   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0066__ |   0.3323   |   0.7905   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1153   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   0.6900   | __0.0000__ | __0.0000__ | __0.0096__ | __0.0000__ |   0.3915   |   0.6900   |   0.2863   |   0.1153   |   0.1153   |   0.1153   | __0.0054__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1153   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |   0.6900   | __0.0000__ | __0.0000__ | __0.0096__ | __0.0000__ |   0.3915   |   0.6900   |   0.2863   |   0.1153   |   0.1153   |   0.1153   | __0.0054__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ |   0.3581   |   0.2370   | __0.0011__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0034__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3018   |   0.6900   |   0.6900   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.1496   |   1.0000   |   0.6476   |   0.3018   |   0.2266   |   0.2668   | __0.0005__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.3581   | __0.0000__ | __0.0000__ |   1.0000   | __0.0175__ | __0.0489__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0436__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.2370   | __0.0034__ | __0.0000__ | __0.0175__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0096__ | __0.0096__ | __0.0011__ | __0.0000__ | __0.0008__ | __0.0489__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0730   | __0.0005__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0066__ |   0.3915   |   0.3915   | __0.0000__ | __0.0000__ |   0.1496   | __0.0003__ | __0.0000__ |   0.0730   | __0.0000__ |   1.0000   | __0.0117__ | __0.0042__ | __0.0013__ | __0.0043__ | __0.0043__ |   0.0596   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3323   |   0.6900   |   0.6900   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0117__ |   1.0000   |   0.4531   |   0.2668   |   0.2668   |   0.2668   | __0.0005__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7905   |   0.2863   |   0.2863   | __0.0000__ | __0.0000__ |   0.6476   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0042__ |   0.4531   |   1.0000   |   0.7266   |   0.7539   |   0.7539   | __0.0001__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   0.1153   |   0.1153   | __0.0000__ | __0.0000__ |   0.3018   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.2668   |   0.7266   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   0.1153   |   0.1153   | __0.0000__ | __0.0000__ |   0.2266   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0043__ |   0.2668   |   0.7539   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   0.1153   |   0.1153   | __0.0000__ | __0.0000__ |   0.2668   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0043__ |   0.2668   |   0.7539   |   1.0000   |   1.0000   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0054__ | __0.0054__ | __0.0038__ | __0.0000__ | __0.0005__ | __0.0436__ | __0.0001__ |   1.0000   | __0.0000__ |   0.0596   | __0.0005__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table20"></a>Table 20: McNemar p-values, using reference annotations [4.0](#40) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>1</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean Accuracy<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>1</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>1</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.svg">
</figure>

<a name="figure25"></a>Figure 25: Mean Accuracy<sub>2</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure26"></a>Figure 26: Mean Accuracy<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean Accuracy<sub>2</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean Accuracy<sub>2</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_accuracy1.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_accuracy1.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_accuracy1.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_accuracy1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean Accuracy<sub>1</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_accuracy2.svg">
</figure>

<a name="figure37"></a>Figure 37: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_accuracy2.svg">
</figure>

<a name="figure38"></a>Figure 38: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_accuracy2.svg">
</figure>

<a name="figure39"></a>Figure 39: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_accuracy2.svg">
</figure>

<a name="figure40"></a>Figure 40: Mean Accuracy<sub>2</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure41"></a>Figure 41: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure42"></a>Figure 42: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.svg">
</figure>

<a name="figure43"></a>Figure 43: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure44"></a>Figure 44: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.svg">
</figure>

<a name="figure45"></a>Figure 45: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 4.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure46"></a>Figure 46: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure47"></a>Figure 47: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure48"></a>Figure 48: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.svg">
</figure>

<a name="figure49"></a>Figure 49: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure50"></a>Figure 50: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.svg">
</figure>

<a name="figure51"></a>Figure 51: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 4.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure52"></a>Figure 52: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure53"></a>Figure 53: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure54"></a>Figure 54: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.svg">
</figure>

<a name="figure55"></a>Figure 55: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.svg">
</figure>

<a name="figure56"></a>Figure 56: Mean Accuracy<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.svg">
</figure>

<a name="figure57"></a>Figure 57: Mean Accuracy<sub>1</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_accuracy1.svg">
</figure>

<a name="figure58"></a>Figure 58: Mean Accuracy<sub>1</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_4.0_accuracy1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_4.0_accuracy1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_4.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_4.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure59"></a>Figure 59: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure60"></a>Figure 60: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.svg">
</figure>

<a name="figure61"></a>Figure 61: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.svg">
</figure>

<a name="figure62"></a>Figure 62: Mean Accuracy<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.svg">
</figure>

<a name="figure63"></a>Figure 63: Mean Accuracy<sub>2</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_accuracy2.svg">
</figure>

<a name="figure64"></a>Figure 64: Mean Accuracy<sub>2</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[CSV](data/ballroom_estimates_1.0_tag_open_4.0_accuracy2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tag_open_4.0_accuracy2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tag_open_4.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tag_open_4.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0018__ | __0.1407__ |   -0.0026   | __0.0485__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0037   |   0.1474   |   -0.0022   |   0.0497   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0037   |   0.1774   |   0.0006   |   0.0574   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0403   |   0.2284   |   -0.0016   |   0.0579   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0156   |   0.2311   |   0.0001   |   0.0568   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0456   |   0.2765   |   -0.0027   |   0.0668   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0779   |   0.3494   |   0.0003   |   0.0716   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1312   |   0.3865   |   -0.0032   |   0.0503   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3127   |   0.4610   |   0.0025   |   0.0840   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2660   |   0.4749   |   0.0042   |   0.0841   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2440   |   0.4841   |   0.0067   |   0.0931   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2478   |   0.4892   |   0.0152   |   0.1012   |
| [percival2014/stem](#percival2014stem)             |   -0.3133   |   0.4924   | __0.0001__ |   0.0767   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0879   |   0.5170   |   0.0241   |   0.0900   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1809   |   0.5199   |   0.0246   |   0.1546   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3190   |   0.5379   |   -0.0129   |   0.1318   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3835   |   0.5661   |   -0.0014   |   0.0664   |

<a name="table21"></a>Table 21: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/ballroom_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure65"></a>Figure 65: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure66"></a>Figure 66: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0066   | __0.1206__ |   0.0007   | __0.0084__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0084   |   0.1229   |   0.0012   |   0.0151   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0008__ |   0.1613   |   0.0037   |   0.0307   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0111   |   0.2170   |   0.0032   |   0.0268   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0358   |   0.2173   |   0.0029   |   0.0315   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0411   |   0.2706   |   0.0004   |   0.0450   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0734   |   0.3414   |   0.0034   |   0.0527   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1267   |   0.3846   | __-0.0002__ |   0.0101   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3082   |   0.4613   |   0.0056   |   0.0686   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2615   |   0.4735   |   0.0050   |   0.0716   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2395   |   0.4860   |   0.0084   |   0.0855   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2433   |   0.4893   |   0.0154   |   0.0919   |
| [percival2014/stem](#percival2014stem)             |   -0.3088   |   0.4920   |   0.0032   |   0.0613   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0834   |   0.5198   |   0.0257   |   0.0794   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1751   |   0.5206   |   0.0264   |   0.1524   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3145   |   0.5408   |   -0.0126   |   0.1225   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3789   |   0.5666   |   0.0002   |   0.0439   |

<a name="table22"></a>Table 22: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/ballroom_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure67"></a>Figure 67: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure68"></a>Figure 68: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0-no-dupes

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0066   | __0.1206__ |   0.0007   | __0.0084__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0084   |   0.1229   |   0.0012   |   0.0151   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0008__ |   0.1628   |   0.0037   |   0.0310   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0114   |   0.2191   |   0.0032   |   0.0270   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0365   |   0.2193   |   0.0029   |   0.0318   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0419   |   0.2731   |   0.0005   |   0.0454   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0747   |   0.3445   |   0.0035   |   0.0532   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1291   |   0.3878   | __-0.0002__ |   0.0101   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3125   |   0.4630   |   0.0057   |   0.0692   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2659   |   0.4746   |   0.0056   |   0.0711   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2438   |   0.4866   |   0.0088   |   0.0862   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2475   |   0.4906   |   0.0161   |   0.0923   |
| [percival2014/stem](#percival2014stem)             |   -0.3117   |   0.4936   |   0.0033   |   0.0619   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1745   |   0.5197   |   0.0254   |   0.1520   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0854   |   0.5217   |   0.0258   |   0.0802   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3181   |   0.5437   |   -0.0135   |   0.1223   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3847   |   0.5691   |   0.0002   |   0.0443   |

<a name="table23"></a>Table 23: Mean OE1/OE2 for estimates compared to version [2.0-no-dupes](#20-no-dupes) ordered by standard deviation.

[CSV](data/ballroom_estimates_2.0-no-dupes_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_distribution_oe1.svg">
</figure>

<a name="figure69"></a>Figure 69: OE<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0-no-dupes_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_distribution_oe2.svg">
</figure>

<a name="figure70"></a>Figure 70: OE<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0-no-dupes_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 3.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0070   | __0.1209__ |   0.0011   | __0.0050__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0089   |   0.1231   |   0.0016   |   0.0130   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ |   0.1616   |   0.0041   |   0.0299   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0107   |   0.2174   |   0.0037   |   0.0261   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0353   |   0.2179   |   0.0019   |   0.0317   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0407   |   0.2708   |   0.0009   |   0.0446   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0729   |   0.3415   |   0.0038   |   0.0523   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1263   |   0.3854   | __0.0003__ |   0.0098   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3077   |   0.4619   |   0.0060   |   0.0682   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2610   |   0.4741   |   0.0055   |   0.0706   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2390   |   0.4865   |   0.0088   |   0.0851   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2428   |   0.4899   |   0.0159   |   0.0916   |
| [percival2014/stem](#percival2014stem)             |   -0.3084   |   0.4925   |   0.0036   |   0.0607   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0830   |   0.5202   |   0.0262   |   0.0791   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1745   |   0.5208   |   0.0269   |   0.1521   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3140   |   0.5407   |   -0.0108   |   0.1230   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3785   |   0.5673   |   0.0007   |   0.0430   |

<a name="table24"></a>Table 24: Mean OE1/OE2 for estimates compared to version [3.0](#30) ordered by standard deviation.

[CSV](data/ballroom_estimates_3.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_oe1.svg">
</figure>

<a name="figure71"></a>Figure 71: OE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_oe2.svg">
</figure>

<a name="figure72"></a>Figure 72: OE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 3.0-no-dupes

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0070   | __0.1209__ |   0.0011   | __0.0050__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0089   |   0.1231   |   0.0016   |   0.0130   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0012__ |   0.1631   |   0.0041   |   0.0302   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0109   |   0.2194   |   0.0037   |   0.0263   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0361   |   0.2199   |   0.0019   |   0.0319   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0415   |   0.2733   |   0.0009   |   0.0450   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0743   |   0.3445   |   0.0039   |   0.0528   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1287   |   0.3886   | __0.0003__ |   0.0098   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3121   |   0.4637   |   0.0061   |   0.0688   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2655   |   0.4753   |   0.0061   |   0.0701   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2434   |   0.4872   |   0.0092   |   0.0858   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2471   |   0.4912   |   0.0166   |   0.0919   |
| [percival2014/stem](#percival2014stem)             |   -0.3113   |   0.4942   |   0.0037   |   0.0613   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1739   |   0.5199   |   0.0260   |   0.1517   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0850   |   0.5221   |   0.0262   |   0.0799   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3177   |   0.5437   |   -0.0116   |   0.1228   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3843   |   0.5699   |   0.0006   |   0.0434   |

<a name="table25"></a>Table 25: Mean OE1/OE2 for estimates compared to version [3.0-no-dupes](#30-no-dupes) ordered by standard deviation.

[CSV](data/ballroom_estimates_3.0-no-dupes_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_distribution_oe1.svg">
</figure>

<a name="figure73"></a>Figure 73: OE<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0-no-dupes_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_distribution_oe2.svg">
</figure>

<a name="figure74"></a>Figure 74: OE<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0-no-dupes_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 4.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.0072   | __0.1519__ |   -0.0031   | __0.0275__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0090   |   0.1632   |   -0.0026   |   0.0294   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0012__ |   0.1855   | __-0.0002__ |   0.0402   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0354   |   0.2365   |   -0.0024   |   0.0405   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0107   |   0.2425   |   -0.0007   |   0.0373   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0407   |   0.2863   |   -0.0035   |   0.0521   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0730   |   0.3578   |   -0.0005   |   0.0587   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1263   |   0.3889   |   -0.0040   |   0.0288   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3078   |   0.4631   |   0.0017   |   0.0729   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.2610   |   0.4768   |   0.0020   |   0.0688   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   -0.2391   |   0.4851   |   0.0045   |   0.0834   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.2429   |   0.4902   |   0.0130   |   0.0898   |
| [percival2014/stem](#percival2014stem)             |   -0.3084   |   0.4931   |   0.0022   |   0.0654   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.0830   |   0.5159   |   0.0247   |   0.0786   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1746   |   0.5214   |   0.0231   |   0.1514   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.3141   |   0.5408   |   -0.0094   |   0.1257   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.3785   |   0.5694   |   -0.0022   |   0.0436   |

<a name="table26"></a>Table 26: Mean OE1/OE2 for estimates compared to version [4.0](#40) ordered by standard deviation.

[CSV](data/ballroom_estimates_4.0_moe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_moe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_moe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ballroom_estimates_4.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ballroom_estimates_4.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_distribution_oe1.svg">
</figure>

<a name="figure75"></a>Figure 75: OE<sub>1</sub> for estimates compared to version [4.0](#40). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_4.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_distribution_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_distribution_oe2.svg">
</figure>

<a name="figure76"></a>Figure 76: OE<sub>2</sub> for estimates compared to version [4.0](#40). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_4.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_distribution_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0264__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0264__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0108__ |   0.6452   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0108__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6452   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table27"></a>Table 27: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0264__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0264__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0108__ |   0.6452   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0108__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6452   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table28"></a>Table 28: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0190__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5620   | __0.0240__ | __0.0000__ | __0.0002__ | __0.0116__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0003__ | __0.0001__ | __0.0000__ |   0.7311   | __0.0000__ |   0.7607   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5661   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0078__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5661   |   1.0000   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7311   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9337   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0190__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0002__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7607   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9337   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5620   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0240__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0110__ |   0.6498   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0110__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0116__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6498   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ | __0.0000__ | __0.0078__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table29"></a>Table 29: Paired t-test p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0264__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0264__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0108__ |   0.6452   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0108__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6452   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table30"></a>Table 30: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0190__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5620   | __0.0240__ | __0.0000__ | __0.0002__ | __0.0116__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0003__ | __0.0001__ | __0.0000__ |   0.7311   | __0.0000__ |   0.7607   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5661   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0078__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5661   |   1.0000   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7311   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9337   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0190__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0002__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7607   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9337   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5620   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0240__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0110__ |   0.6498   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0110__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0116__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6498   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ | __0.0000__ | __0.0078__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table31"></a>Table 31: Paired t-test p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0080__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.5376   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4201   | __0.0429__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.5376   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2688   | __0.0184__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0080__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0264__ | __0.0000__ | __0.0002__ | __0.0127__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0001__ | __0.0000__ |   0.7582   | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.5485   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0074__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5485   |   1.0000   | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7582   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9477   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7238   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9477   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0000__ | __0.0000__ |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0014__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0264__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |   1.0000   | __0.0001__ | __0.0108__ |   0.6452   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.4201   |   0.2688   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.1677   | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0429__ | __0.0184__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0108__ |   0.1677   |   1.0000   | __0.0047__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ |   0.6452   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0074__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table32"></a>Table 32: Paired t-test p-values, using reference annotations [4.0](#40) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ | __0.0409__ |   0.3570   | __0.0000__ | __0.0024__ |   0.1554   | __0.0000__ | __0.0288__ |   0.0813   |   0.7460   | __0.0013__ | __0.0011__ |   0.2169   | __0.0102__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ | __0.0184__ |   0.6232   | __0.0000__ | __0.0040__ |   0.2820   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.5422   | __0.0122__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ | __0.0151__ |   0.7943   | __0.0000__ | __0.0061__ |   0.3490   | __0.0000__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.8194   | __0.0165__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0415__ | __0.0000__ | __0.0000__ |   0.8497   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0409__ | __0.0184__ | __0.0151__ | __0.0000__ |   1.0000   | __0.0261__ | __0.0000__ | __0.0010__ | __0.0161__ | __0.0000__ | __0.0054__ | __0.0112__ | __0.0373__ | __0.0057__ | __0.0068__ | __0.0232__ | __0.0028__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3570   |   0.6232   |   0.7943   | __0.0000__ | __0.0261__ |   1.0000   | __0.0000__ | __0.0202__ |   0.5904   | __0.0000__ |   0.2283   |   0.5372   |   0.6302   |   0.3704   |   0.4764   |   0.9306   |   0.0912   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0415__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0290__ | __0.0002__ |   0.1870   | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0082__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0024__ | __0.0040__ | __0.0061__ | __0.0000__ | __0.0010__ | __0.0202__ | __0.0290__ |   1.0000   |   0.0960   | __0.0103__ |   0.3110   |   0.0755   | __0.0050__ |   0.0517   | __0.0455__ | __0.0091__ |   0.5573   |
| [percival2014/stem](#percival2014stem)             |   0.1554   |   0.2820   |   0.3490   | __0.0000__ | __0.0161__ |   0.5904   | __0.0002__ |   0.0960   |   1.0000   | __0.0001__ |   0.4524   |   0.9451   |   0.2892   |   0.8397   |   0.9927   |   0.4584   |   0.2257   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.8497   | __0.0000__ | __0.0000__ |   0.1870   | __0.0103__ | __0.0001__ |   1.0000   | __0.0009__ | __0.0002__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ |   0.0577   |   0.0891   | __0.0000__ | __0.0054__ |   0.2283   | __0.0009__ |   0.3110   |   0.4524   | __0.0009__ |   1.0000   |   0.2496   | __0.0262__ |   0.4255   |   0.3397   |   0.1098   |   0.6257   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0813   |   0.1700   |   0.2631   | __0.0000__ | __0.0112__ |   0.5372   | __0.0000__ |   0.0755   |   0.9451   | __0.0002__ |   0.2496   |   1.0000   |   0.0587   |   0.8821   |   0.9283   |   0.3290   |   0.2333   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7460   |   0.8820   |   0.6985   | __0.0000__ | __0.0373__ |   0.6302   | __0.0000__ | __0.0050__ |   0.2892   | __0.0000__ | __0.0262__ |   0.0587   |   1.0000   | __0.0184__ |   0.0729   |   0.5386   | __0.0335__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ | __0.0057__ |   0.3704   | __0.0000__ |   0.0517   |   0.8397   | __0.0001__ |   0.4255   |   0.8821   | __0.0184__ |   1.0000   |   0.6915   | __0.0487__ |   0.2225   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0138__ |   0.0570   | __0.0000__ | __0.0068__ |   0.4764   | __0.0000__ | __0.0455__ |   0.9927   | __0.0001__ |   0.3397   |   0.9283   |   0.0729   |   0.6915   |   1.0000   |   0.2103   |   0.1580   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   |   0.5422   |   0.8194   | __0.0000__ | __0.0232__ |   0.9306   | __0.0000__ | __0.0091__ |   0.4584   | __0.0000__ |   0.1098   |   0.3290   |   0.5386   | __0.0487__ |   0.2103   |   1.0000   | __0.0497__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0102__ | __0.0122__ | __0.0165__ | __0.0000__ | __0.0028__ |   0.0912   | __0.0082__ |   0.5573   |   0.2257   | __0.0012__ |   0.6257   |   0.2333   | __0.0335__ |   0.2225   |   0.1580   | __0.0497__ |   1.0000   |

<a name="table33"></a>Table 33: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ | __0.0177__ |   0.8188   | __0.0000__ | __0.0087__ |   0.1572   | __0.0000__ | __0.0288__ |   0.0813   |   0.7460   | __0.0013__ | __0.0011__ |   0.2169   |   0.0558   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ | __0.0073__ |   0.7633   | __0.0000__ | __0.0143__ |   0.2769   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.5422   |   0.0671   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ | __0.0059__ |   0.5845   | __0.0000__ | __0.0209__ |   0.4038   | __0.0001__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.8194   |   0.0893   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ | __0.0000__ |   0.7757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0177__ | __0.0073__ | __0.0059__ | __0.0000__ |   1.0000   | __0.0222__ | __0.0000__ | __0.0010__ | __0.0071__ | __0.0000__ | __0.0017__ | __0.0047__ | __0.0171__ | __0.0021__ | __0.0024__ | __0.0098__ | __0.0047__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8188   |   0.7633   |   0.5845   | __0.0000__ | __0.0222__ |   1.0000   | __0.0001__ | __0.0202__ |   0.2826   | __0.0000__ |   0.0810   |   0.2209   |   0.9386   |   0.0816   |   0.1082   |   0.5587   |   0.1156   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0787   | __0.0026__ |   0.1069   | __0.0089__ | __0.0008__ | __0.0001__ | __0.0005__ | __0.0004__ | __0.0001__ | __0.0105__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0087__ | __0.0143__ | __0.0209__ | __0.0000__ | __0.0010__ | __0.0202__ |   0.0787   |   1.0000   |   0.1865   | __0.0102__ |   0.4990   |   0.1635   | __0.0163__ |   0.1317   |   0.1108   | __0.0301__ |   0.4232   |
| [percival2014/stem](#percival2014stem)             |   0.1572   |   0.2769   |   0.4038   | __0.0000__ | __0.0071__ |   0.2826   | __0.0026__ |   0.1865   |   1.0000   | __0.0002__ |   0.4458   |   0.9448   |   0.2866   |   0.8289   |   0.9927   |   0.4570   |   0.5945   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0001__ |   0.7757   | __0.0000__ | __0.0000__ |   0.1069   | __0.0102__ | __0.0002__ |   1.0000   | __0.0014__ | __0.0003__ | __0.0000__ | __0.0002__ | __0.0001__ | __0.0001__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ |   0.0577   |   0.0891   | __0.0000__ | __0.0017__ |   0.0810   | __0.0089__ |   0.4990   |   0.4458   | __0.0014__ |   1.0000   |   0.2496   | __0.0262__ |   0.4255   |   0.3397   |   0.1098   |   0.8716   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0813   |   0.1700   |   0.2631   | __0.0000__ | __0.0047__ |   0.2209   | __0.0008__ |   0.1635   |   0.9448   | __0.0003__ |   0.2496   |   1.0000   |   0.0587   |   0.8821   |   0.9283   |   0.3290   |   0.5970   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7460   |   0.8820   |   0.6985   | __0.0000__ | __0.0171__ |   0.9386   | __0.0001__ | __0.0163__ |   0.2866   | __0.0000__ | __0.0262__ |   0.0587   |   1.0000   | __0.0184__ |   0.0729   |   0.5386   |   0.1314   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ | __0.0021__ |   0.0816   | __0.0005__ |   0.1317   |   0.8289   | __0.0002__ |   0.4255   |   0.8821   | __0.0184__ |   1.0000   |   0.6915   | __0.0487__ |   0.6243   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0138__ |   0.0570   | __0.0000__ | __0.0024__ |   0.1082   | __0.0004__ |   0.1108   |   0.9927   | __0.0001__ |   0.3397   |   0.9283   |   0.0729   |   0.6915   |   1.0000   |   0.2103   |   0.4977   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   |   0.5422   |   0.8194   | __0.0000__ | __0.0098__ |   0.5587   | __0.0001__ | __0.0301__ |   0.4570   | __0.0001__ |   0.1098   |   0.3290   |   0.5386   | __0.0487__ |   0.2103   |   1.0000   |   0.1982   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.0558   |   0.0671   |   0.0893   | __0.0000__ | __0.0047__ |   0.1156   | __0.0105__ |   0.4232   |   0.5945   | __0.0012__ |   0.8716   |   0.5970   |   0.1314   |   0.6243   |   0.4977   |   0.1982   |   1.0000   |

<a name="table34"></a>Table 34: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ | __0.0118__ |   0.8171   | __0.0000__ | __0.0069__ |   0.1541   | __0.0000__ | __0.0271__ |   0.0762   |   0.7198   | __0.0013__ | __0.0012__ |   0.2205   | __0.0320__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ | __0.0073__ |   0.7633   | __0.0000__ | __0.0143__ |   0.2769   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.5422   |   0.0671   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ | __0.0059__ |   0.5845   | __0.0000__ | __0.0209__ |   0.4038   | __0.0001__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.8194   |   0.0893   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0300__ | __0.0000__ | __0.0000__ |   0.8935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0118__ | __0.0073__ | __0.0059__ | __0.0000__ |   1.0000   | __0.0156__ | __0.0000__ | __0.0006__ | __0.0048__ | __0.0000__ | __0.0010__ | __0.0030__ | __0.0112__ | __0.0013__ | __0.0015__ | __0.0066__ | __0.0023__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8171   |   0.7633   |   0.5845   | __0.0000__ | __0.0156__ |   1.0000   | __0.0001__ | __0.0167__ |   0.2792   | __0.0001__ |   0.0776   |   0.2127   |   0.9196   |   0.0831   |   0.1102   |   0.5642   |   0.0762   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0300__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0711   | __0.0018__ |   0.1697   | __0.0065__ | __0.0005__ | __0.0000__ | __0.0003__ | __0.0002__ | __0.0000__ | __0.0114__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0069__ | __0.0143__ | __0.0209__ | __0.0000__ | __0.0006__ | __0.0167__ |   0.0711   |   1.0000   |   0.1680   | __0.0180__ |   0.4709   |   0.1480   | __0.0138__ |   0.1112   |   0.0935   | __0.0242__ |   0.4614   |
| [percival2014/stem](#percival2014stem)             |   0.1541   |   0.2769   |   0.4038   | __0.0000__ | __0.0048__ |   0.2792   | __0.0018__ |   0.1680   |   1.0000   | __0.0004__ |   0.4384   |   0.9344   |   0.2928   |   0.8425   |   0.9941   |   0.4471   |   0.4916   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0001__ |   0.8935   | __0.0000__ | __0.0001__ |   0.1697   | __0.0180__ | __0.0004__ |   1.0000   | __0.0027__ | __0.0006__ | __0.0001__ | __0.0004__ | __0.0003__ | __0.0001__ | __0.0028__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0271__ |   0.0577   |   0.0891   | __0.0000__ | __0.0010__ |   0.0776   | __0.0065__ |   0.4709   |   0.4384   | __0.0027__ |   1.0000   |   0.2490   | __0.0261__ |   0.4070   |   0.3241   |   0.1033   |   0.9822   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0762   |   0.1700   |   0.2631   | __0.0000__ | __0.0030__ |   0.2127   | __0.0005__ |   0.1480   |   0.9344   | __0.0006__ |   0.2490   |   1.0000   |   0.0587   |   0.9125   |   0.8967   |   0.3107   |   0.4905   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7198   |   0.8820   |   0.6985   | __0.0000__ | __0.0112__ |   0.9196   | __0.0000__ | __0.0138__ |   0.2928   | __0.0001__ | __0.0261__ |   0.0587   |   1.0000   | __0.0212__ |   0.0807   |   0.5676   |   0.0921   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ | __0.0013__ |   0.0831   | __0.0003__ |   0.1112   |   0.8425   | __0.0004__ |   0.4070   |   0.9125   | __0.0212__ |   1.0000   |   0.6915   | __0.0487__ |   0.4843   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0012__ | __0.0138__ |   0.0570   | __0.0000__ | __0.0015__ |   0.1102   | __0.0002__ |   0.0935   |   0.9941   | __0.0003__ |   0.3241   |   0.8967   |   0.0807   |   0.6915   |   1.0000   |   0.2103   |   0.3680   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2205   |   0.5422   |   0.8194   | __0.0000__ | __0.0066__ |   0.5642   | __0.0000__ | __0.0242__ |   0.4471   | __0.0001__ |   0.1033   |   0.3107   |   0.5676   | __0.0487__ |   0.2103   |   1.0000   |   0.1310   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0320__ |   0.0671   |   0.0893   | __0.0000__ | __0.0023__ |   0.0762   | __0.0114__ |   0.4614   |   0.4916   | __0.0028__ |   0.9822   |   0.4905   |   0.0921   |   0.4843   |   0.3680   |   0.1310   |   1.0000   |

<a name="table35"></a>Table 35: Paired t-test p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ | __0.0073__ |   0.8188   | __0.0000__ | __0.0087__ |   0.1572   | __0.0000__ | __0.0288__ |   0.0813   |   0.7460   | __0.0013__ | __0.0011__ | __0.0121__ |   0.0558   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ | __0.0028__ |   0.7633   | __0.0000__ | __0.0143__ |   0.2769   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.0751   |   0.0671   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ | __0.0022__ |   0.5845   | __0.0000__ | __0.0209__ |   0.4038   | __0.0001__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.1855   |   0.0893   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ | __0.0000__ |   0.7757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0073__ | __0.0028__ | __0.0022__ | __0.0000__ |   1.0000   | __0.0101__ | __0.0000__ | __0.0004__ | __0.0031__ | __0.0000__ | __0.0006__ | __0.0019__ | __0.0073__ | __0.0007__ | __0.0009__ | __0.0011__ | __0.0021__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8188   |   0.7633   |   0.5845   | __0.0000__ | __0.0101__ |   1.0000   | __0.0001__ | __0.0202__ |   0.2826   | __0.0000__ |   0.0810   |   0.2209   |   0.9386   |   0.0816   |   0.1082   |   0.1649   |   0.1156   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0787   | __0.0026__ |   0.1069   | __0.0089__ | __0.0008__ | __0.0001__ | __0.0005__ | __0.0004__ | __0.0003__ | __0.0105__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0087__ | __0.0143__ | __0.0209__ | __0.0000__ | __0.0004__ | __0.0202__ |   0.0787   |   1.0000   |   0.1865   | __0.0102__ |   0.4990   |   0.1635   | __0.0163__ |   0.1317   |   0.1108   |   0.0893   |   0.4232   |
| [percival2014/stem](#percival2014stem)             |   0.1572   |   0.2769   |   0.4038   | __0.0000__ | __0.0031__ |   0.2826   | __0.0026__ |   0.1865   |   1.0000   | __0.0002__ |   0.4458   |   0.9448   |   0.2866   |   0.8289   |   0.9927   |   0.8924   |   0.5945   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0001__ |   0.7757   | __0.0000__ | __0.0000__ |   0.1069   | __0.0102__ | __0.0002__ |   1.0000   | __0.0014__ | __0.0003__ | __0.0000__ | __0.0002__ | __0.0001__ | __0.0001__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ |   0.0577   |   0.0891   | __0.0000__ | __0.0006__ |   0.0810   | __0.0089__ |   0.4990   |   0.4458   | __0.0014__ |   1.0000   |   0.2496   | __0.0262__ |   0.4255   |   0.3397   |   0.3000   |   0.8716   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0813   |   0.1700   |   0.2631   | __0.0000__ | __0.0019__ |   0.2209   | __0.0008__ |   0.1635   |   0.9448   | __0.0003__ |   0.2496   |   1.0000   |   0.0587   |   0.8821   |   0.9283   |   0.8043   |   0.5970   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7460   |   0.8820   |   0.6985   | __0.0000__ | __0.0073__ |   0.9386   | __0.0001__ | __0.0163__ |   0.2866   | __0.0000__ | __0.0262__ |   0.0587   |   1.0000   | __0.0184__ |   0.0729   |   0.1496   |   0.1314   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ | __0.0007__ |   0.0816   | __0.0005__ |   0.1317   |   0.8289   | __0.0002__ |   0.4255   |   0.8821   | __0.0184__ |   1.0000   |   0.6915   |   0.4350   |   0.6243   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0138__ |   0.0570   | __0.0000__ | __0.0009__ |   0.1082   | __0.0004__ |   0.1108   |   0.9927   | __0.0001__ |   0.3397   |   0.9283   |   0.0729   |   0.6915   |   1.0000   |   0.7731   |   0.4977   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0121__ |   0.0751   |   0.1855   | __0.0000__ | __0.0011__ |   0.1649   | __0.0003__ |   0.0893   |   0.8924   | __0.0001__ |   0.3000   |   0.8043   |   0.1496   |   0.4350   |   0.7731   |   1.0000   |   0.4565   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.0558   |   0.0671   |   0.0893   | __0.0000__ | __0.0021__ |   0.1156   | __0.0105__ |   0.4232   |   0.5945   | __0.0012__ |   0.8716   |   0.5970   |   0.1314   |   0.6243   |   0.4977   |   0.4565   |   1.0000   |

<a name="table36"></a>Table 36: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ | __0.0047__ |   0.8171   | __0.0000__ | __0.0069__ |   0.1541   | __0.0000__ | __0.0271__ |   0.0762   |   0.7198   | __0.0013__ | __0.0012__ | __0.0124__ | __0.0320__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ | __0.0028__ |   0.7633   | __0.0000__ | __0.0143__ |   0.2769   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.0751   |   0.0671   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ | __0.0022__ |   0.5845   | __0.0000__ | __0.0209__ |   0.4038   | __0.0001__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.1855   |   0.0893   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0300__ | __0.0000__ | __0.0000__ |   0.8935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0047__ | __0.0028__ | __0.0022__ | __0.0000__ |   1.0000   | __0.0068__ | __0.0000__ | __0.0002__ | __0.0020__ | __0.0000__ | __0.0004__ | __0.0012__ | __0.0046__ | __0.0004__ | __0.0005__ | __0.0006__ | __0.0010__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.8171   |   0.7633   |   0.5845   | __0.0000__ | __0.0068__ |   1.0000   | __0.0001__ | __0.0167__ |   0.2792   | __0.0001__ |   0.0776   |   0.2127   |   0.9196   |   0.0831   |   0.1102   |   0.1677   |   0.0762   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0300__ | __0.0000__ | __0.0001__ |   1.0000   |   0.0711   | __0.0018__ |   0.1697   | __0.0065__ | __0.0005__ | __0.0000__ | __0.0003__ | __0.0002__ | __0.0002__ | __0.0114__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0069__ | __0.0143__ | __0.0209__ | __0.0000__ | __0.0002__ | __0.0167__ |   0.0711   |   1.0000   |   0.1680   | __0.0180__ |   0.4709   |   0.1480   | __0.0138__ |   0.1112   |   0.0935   |   0.0748   |   0.4614   |
| [percival2014/stem](#percival2014stem)             |   0.1541   |   0.2769   |   0.4038   | __0.0000__ | __0.0020__ |   0.2792   | __0.0018__ |   0.1680   |   1.0000   | __0.0004__ |   0.4384   |   0.9344   |   0.2928   |   0.8425   |   0.9941   |   0.8789   |   0.4916   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0001__ |   0.8935   | __0.0000__ | __0.0001__ |   0.1697   | __0.0180__ | __0.0004__ |   1.0000   | __0.0027__ | __0.0006__ | __0.0001__ | __0.0004__ | __0.0003__ | __0.0002__ | __0.0028__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0271__ |   0.0577   |   0.0891   | __0.0000__ | __0.0004__ |   0.0776   | __0.0065__ |   0.4709   |   0.4384   | __0.0027__ |   1.0000   |   0.2490   | __0.0261__ |   0.4070   |   0.3241   |   0.2863   |   0.9822   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0762   |   0.1700   |   0.2631   | __0.0000__ | __0.0012__ |   0.2127   | __0.0005__ |   0.1480   |   0.9344   | __0.0006__ |   0.2490   |   1.0000   |   0.0587   |   0.9125   |   0.8967   |   0.7757   |   0.4905   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7198   |   0.8820   |   0.6985   | __0.0000__ | __0.0046__ |   0.9196   | __0.0000__ | __0.0138__ |   0.2928   | __0.0001__ | __0.0261__ |   0.0587   |   1.0000   | __0.0212__ |   0.0807   |   0.1621   |   0.0921   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ | __0.0004__ |   0.0831   | __0.0003__ |   0.1112   |   0.8425   | __0.0004__ |   0.4070   |   0.9125   | __0.0212__ |   1.0000   |   0.6915   |   0.4350   |   0.4843   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0012__ | __0.0138__ |   0.0570   | __0.0000__ | __0.0005__ |   0.1102   | __0.0002__ |   0.0935   |   0.9941   | __0.0003__ |   0.3241   |   0.8967   |   0.0807   |   0.6915   |   1.0000   |   0.7731   |   0.3680   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0124__ |   0.0751   |   0.1855   | __0.0000__ | __0.0006__ |   0.1677   | __0.0002__ |   0.0748   |   0.8789   | __0.0002__ |   0.2863   |   0.7757   |   0.1621   |   0.4350   |   0.7731   |   1.0000   |   0.3417   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0320__ |   0.0671   |   0.0893   | __0.0000__ | __0.0010__ |   0.0762   | __0.0114__ |   0.4614   |   0.4916   | __0.0028__ |   0.9822   |   0.4905   |   0.0921   |   0.4843   |   0.3680   |   0.3417   |   1.0000   |

<a name="table37"></a>Table 37: Paired t-test p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0191__ | __0.0197__ | __0.0000__ |   0.2769   |   0.3251   | __0.0000__ | __0.0087__ | __0.0349__ | __0.0000__ | __0.0288__ |   0.0813   |   0.7460   | __0.0013__ | __0.0011__ |   0.2169   | __0.0231__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0191__ |   1.0000   |   0.3775   | __0.0000__ |   0.1676   |   0.6080   | __0.0000__ | __0.0143__ |   0.0665   | __0.0000__ |   0.0577   |   0.1700   |   0.8820   | __0.0106__ | __0.0138__ |   0.5422   | __0.0279__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0197__ |   0.3775   |   1.0000   | __0.0000__ |   0.1452   |   0.7862   | __0.0000__ | __0.0209__ |   0.0817   | __0.0000__ |   0.0891   |   0.2631   |   0.6985   | __0.0386__ |   0.0570   |   0.8194   | __0.0382__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0057__ | __0.0000__ | __0.0000__ |   0.9621   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2769   |   0.1676   |   0.1452   | __0.0000__ |   1.0000   |   0.1533   | __0.0005__ | __0.0185__ | __0.0316__ | __0.0000__ |   0.0521   |   0.0992   |   0.2474   |   0.0704   |   0.0811   |   0.1763   | __0.0469__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3251   |   0.6080   |   0.7862   | __0.0000__ |   0.1533   |   1.0000   | __0.0001__ |   0.0514   |   0.1294   | __0.0000__ |   0.2183   |   0.5250   |   0.6183   |   0.3486   |   0.4448   |   0.9284   |   0.1571   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0057__ | __0.0005__ | __0.0001__ |   1.0000   | __0.0290__ | __0.0089__ |   0.1286   | __0.0028__ | __0.0002__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0065__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0087__ | __0.0143__ | __0.0209__ | __0.0000__ | __0.0185__ |   0.0514   | __0.0290__ |   1.0000   |   0.5709   | __0.0063__ |   0.4990   |   0.1635   | __0.0163__ |   0.1317   |   0.1108   | __0.0301__ |   0.5446   |
| [percival2014/stem](#percival2014stem)             | __0.0349__ |   0.0665   |   0.0817   | __0.0000__ | __0.0316__ |   0.1294   | __0.0089__ |   0.5709   |   1.0000   | __0.0010__ |   0.8922   |   0.4102   |   0.0744   |   0.4124   |   0.3284   |   0.1150   |   0.9520   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.9621   | __0.0000__ | __0.0000__ |   0.1286   | __0.0063__ | __0.0010__ |   1.0000   | __0.0009__ | __0.0002__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0012__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0288__ |   0.0577   |   0.0891   | __0.0000__ |   0.0521   |   0.2183   | __0.0028__ |   0.4990   |   0.8922   | __0.0009__ |   1.0000   |   0.2496   | __0.0262__ |   0.4255   |   0.3397   |   0.1098   |   0.9299   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0813   |   0.1700   |   0.2631   | __0.0000__ |   0.0992   |   0.5250   | __0.0002__ |   0.1635   |   0.4102   | __0.0002__ |   0.2496   |   1.0000   |   0.0587   |   0.8821   |   0.9283   |   0.3290   |   0.4170   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7460   |   0.8820   |   0.6985   | __0.0000__ |   0.2474   |   0.6183   | __0.0000__ | __0.0163__ |   0.0744   | __0.0000__ | __0.0262__ |   0.0587   |   1.0000   | __0.0184__ |   0.0729   |   0.5386   |   0.0699   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0013__ | __0.0106__ | __0.0386__ | __0.0000__ |   0.0704   |   0.3486   | __0.0001__ |   0.1317   |   0.4124   | __0.0001__ |   0.4255   |   0.8821   | __0.0184__ |   1.0000   |   0.6915   | __0.0487__ |   0.4186   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0011__ | __0.0138__ |   0.0570   | __0.0000__ |   0.0811   |   0.4448   | __0.0001__ |   0.1108   |   0.3284   | __0.0001__ |   0.3397   |   0.9283   |   0.0729   |   0.6915   |   1.0000   |   0.2103   |   0.3101   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2169   |   0.5422   |   0.8194   | __0.0000__ |   0.1763   |   0.9284   | __0.0000__ | __0.0301__ |   0.1150   | __0.0000__ |   0.1098   |   0.3290   |   0.5386   | __0.0487__ |   0.2103   |   1.0000   |   0.1047   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0231__ | __0.0279__ | __0.0382__ | __0.0000__ | __0.0469__ |   0.1571   | __0.0065__ |   0.5446   |   0.9520   | __0.0012__ |   0.9299   |   0.4170   |   0.0699   |   0.4186   |   0.3101   |   0.1047   |   1.0000   |

<a name="table38"></a>Table 38: Paired t-test p-values, using reference annotations [4.0](#40) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure77"></a>Figure 77: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure78"></a>Figure 78: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.svg">
</figure>

<a name="figure79"></a>Figure 79: Mean OE<sub>1</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_oe1.svg">
</figure>

<a name="figure80"></a>Figure 80: Mean OE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.svg">
</figure>

<a name="figure81"></a>Figure 81: Mean OE<sub>1</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_oe1.svg">
</figure>

<a name="figure82"></a>Figure 82: Mean OE<sub>1</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure83"></a>Figure 83: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure84"></a>Figure 84: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.svg">
</figure>

<a name="figure85"></a>Figure 85: Mean OE<sub>2</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_oe2.svg">
</figure>

<a name="figure86"></a>Figure 86: Mean OE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.svg">
</figure>

<a name="figure87"></a>Figure 87: Mean OE<sub>2</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_oe2.svg">
</figure>

<a name="figure88"></a>Figure 88: Mean OE<sub>2</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure89"></a>Figure 89: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure90"></a>Figure 90: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_oe1.svg">
</figure>

<a name="figure91"></a>Figure 91: Mean OE<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_oe1.svg">
</figure>

<a name="figure92"></a>Figure 92: Mean OE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_oe1.svg">
</figure>

<a name="figure93"></a>Figure 93: Mean OE<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_oe1.svg">
</figure>

<a name="figure94"></a>Figure 94: Mean OE<sub>1</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure95"></a>Figure 95: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure96"></a>Figure 96: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_oe2.svg">
</figure>

<a name="figure97"></a>Figure 97: Mean OE<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_oe2.svg">
</figure>

<a name="figure98"></a>Figure 98: Mean OE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_oe2.svg">
</figure>

<a name="figure99"></a>Figure 99: Mean OE<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_oe2.svg">
</figure>

<a name="figure100"></a>Figure 100: Mean OE<sub>2</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure101"></a>Figure 101: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure102"></a>Figure 102: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.svg">
</figure>

<a name="figure103"></a>Figure 103: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_oe1.svg">
</figure>

<a name="figure104"></a>Figure 104: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.svg">
</figure>

<a name="figure105"></a>Figure 105: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 4.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_oe1.svg">
</figure>

<a name="figure106"></a>Figure 106: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure107"></a>Figure 107: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure108"></a>Figure 108: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.svg">
</figure>

<a name="figure109"></a>Figure 109: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_oe2.svg">
</figure>

<a name="figure110"></a>Figure 110: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.svg">
</figure>

<a name="figure111"></a>Figure 111: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 4.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_oe2.svg">
</figure>

<a name="figure112"></a>Figure 112: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure113"></a>Figure 113: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_oe1.svg">
</figure>

<a name="figure114"></a>Figure 114: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe1.svg">
</figure>

<a name="figure115"></a>Figure 115: OE<sub>1</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_oe1.svg">
</figure>

<a name="figure116"></a>Figure 116: OE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe1.svg">
</figure>

<a name="figure117"></a>Figure 117: OE<sub>1</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_oe1.svg">
</figure>

<a name="figure118"></a>Figure 118: OE<sub>1</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_4.0_oe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_oe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure119"></a>Figure 119: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_oe2.svg">
</figure>

<a name="figure120"></a>Figure 120: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe2.svg">
</figure>

<a name="figure121"></a>Figure 121: OE<sub>2</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_oe2.svg">
</figure>

<a name="figure122"></a>Figure 122: OE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe2.svg">
</figure>

<a name="figure123"></a>Figure 123: OE<sub>2</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_oe2.svg">
</figure>

<a name="figure124"></a>Figure 124: OE<sub>2</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_4.0_oe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_oe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0308__ | __0.1373__ | __0.0143__ | __0.0464__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0331   |   0.1437   |   0.0147   |   0.0476   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0433   |   0.1720   |   0.0161   |   0.0551   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0647   |   0.2224   |   0.0155   |   0.0546   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0650   |   0.2227   |   0.0155   |   0.0558   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0921   |   0.2647   |   0.0195   |   0.0640   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1414   |   0.3289   |   0.0213   |   0.0684   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1748   |   0.3689   |   0.0182   |   0.0470   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3026   |   0.4284   |   0.0436   |   0.0823   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3134   |   0.4450   |   0.0283   |   0.0793   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3213   |   0.4367   |   0.0417   |   0.0836   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3238   |   0.4425   |   0.0380   |   0.0950   |
| [schreiber2014/default](#schreiber2014default)     |   0.3263   |   0.4515   |   0.0258   |   0.0800   |
| [percival2014/stem](#percival2014stem)             |   0.3367   |   0.4767   |   0.0259   |   0.0722   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3431   |   0.4305   |   0.0753   |   0.1372   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3888   |   0.4899   |   0.0553   |   0.1204   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4115   |   0.5460   |   0.0198   |   0.0634   |

<a name="table39"></a>Table 39: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/ballroom_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure125"></a>Figure 125: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure126"></a>Figure 126: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0203__ | __0.1191__ |   0.0059   | __0.0061__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0211   |   0.1213   |   0.0063   |   0.0138   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0344   |   0.1576   |   0.0096   |   0.0294   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0556   |   0.2101   |   0.0098   |   0.0252   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0567   |   0.2128   |   0.0094   |   0.0302   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0830   |   0.2609   |   0.0107   |   0.0437   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1296   |   0.3243   |   0.0124   |   0.0513   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1628   |   0.3708   | __0.0055__ |   0.0084   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3010   |   0.4320   |   0.0380   |   0.0743   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3064   |   0.4458   |   0.0207   |   0.0687   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3171   |   0.4450   |   0.0301   |   0.0882   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3173   |   0.4391   |   0.0357   |   0.0781   |
| [schreiber2014/default](#schreiber2014default)     |   0.3186   |   0.4541   |   0.0171   |   0.0667   |
| [percival2014/stem](#percival2014stem)             |   0.3294   |   0.4785   |   0.0176   |   0.0588   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3399   |   0.4314   |   0.0712   |   0.1373   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3839   |   0.4939   |   0.0471   |   0.1138   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4057   |   0.5478   |   0.0126   |   0.0421   |

<a name="table40"></a>Table 40: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/ballroom_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure127"></a>Figure 127: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure128"></a>Figure 128: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0-no-dupes

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0203__ | __0.1191__ |   0.0059   | __0.0061__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0211   |   0.1213   |   0.0063   |   0.0138   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0349   |   0.1591   |   0.0096   |   0.0297   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0565   |   0.2119   |   0.0098   |   0.0254   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0576   |   0.2147   |   0.0095   |   0.0305   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0845   |   0.2631   |   0.0108   |   0.0441   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1319   |   0.3269   |   0.0126   |   0.0518   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1659   |   0.3736   | __0.0056__ |   0.0085   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3034   |   0.4329   |   0.0384   |   0.0750   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3096   |   0.4473   |   0.0205   |   0.0683   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3203   |   0.4400   |   0.0362   |   0.0788   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3204   |   0.4463   |   0.0302   |   0.0887   |
| [schreiber2014/default](#schreiber2014default)     |   0.3231   |   0.4557   |   0.0173   |   0.0673   |
| [percival2014/stem](#percival2014stem)             |   0.3326   |   0.4799   |   0.0178   |   0.0593   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3386   |   0.4311   |   0.0709   |   0.1368   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3888   |   0.4956   |   0.0472   |   0.1137   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4117   |   0.5499   |   0.0127   |   0.0425   |

<a name="table41"></a>Table 41: Mean AOE1/AOE2 for estimates compared to version [2.0-no-dupes](#20-no-dupes) ordered by mean.

[CSV](data/ballroom_estimates_2.0-no-dupes_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_2.0-no-dupes_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_distribution_aoe1.svg">
</figure>

<a name="figure129"></a>Figure 129: AOE<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0-no-dupes_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_distribution_aoe2.svg">
</figure>

<a name="figure130"></a>Figure 130: AOE<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_2.0-no-dupes_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 3.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0179__ | __0.1198__ | __0.0034__ | __0.0039__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0188   |   0.1220   |   0.0038   |   0.0125   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0324   |   0.1583   |   0.0076   |   0.0292   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0537   |   0.2109   |   0.0077   |   0.0252   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0550   |   0.2138   |   0.0075   |   0.0308   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0803   |   0.2618   |   0.0078   |   0.0439   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1270   |   0.3252   |   0.0096   |   0.0516   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1648   |   0.3705   |   0.0072   |   0.0066   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3016   |   0.4320   |   0.0383   |   0.0740   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3046   |   0.4473   |   0.0179   |   0.0685   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3161   |   0.4403   |   0.0339   |   0.0785   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3165   |   0.4458   |   0.0286   |   0.0885   |
| [schreiber2014/default](#schreiber2014default)     |   0.3168   |   0.4557   |   0.0142   |   0.0669   |
| [percival2014/stem](#percival2014stem)             |   0.3276   |   0.4799   |   0.0150   |   0.0589   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3398   |   0.4315   |   0.0707   |   0.1373   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3822   |   0.4949   |   0.0450   |   0.1149   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4046   |   0.5490   |   0.0105   |   0.0417   |

<a name="table42"></a>Table 42: Mean AOE1/AOE2 for estimates compared to version [3.0](#30) ordered by mean.

[CSV](data/ballroom_estimates_3.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_aoe1.svg">
</figure>

<a name="figure131"></a>Figure 131: AOE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_distribution_aoe2.svg">
</figure>

<a name="figure132"></a>Figure 132: AOE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 3.0-no-dupes

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0179__ | __0.1198__ | __0.0034__ | __0.0039__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0188   |   0.1220   |   0.0038   |   0.0125   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0330   |   0.1597   |   0.0076   |   0.0295   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0546   |   0.2128   |   0.0078   |   0.0254   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0559   |   0.2157   |   0.0076   |   0.0311   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0818   |   0.2640   |   0.0079   |   0.0443   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1294   |   0.3278   |   0.0097   |   0.0521   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1678   |   0.3733   |   0.0072   |   0.0066   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3040   |   0.4329   |   0.0386   |   0.0747   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3079   |   0.4489   |   0.0177   |   0.0681   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3191   |   0.4413   |   0.0343   |   0.0792   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3199   |   0.4472   |   0.0287   |   0.0889   |
| [schreiber2014/default](#schreiber2014default)     |   0.3213   |   0.4574   |   0.0144   |   0.0676   |
| [percival2014/stem](#percival2014stem)             |   0.3308   |   0.4813   |   0.0153   |   0.0594   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3385   |   0.4313   |   0.0704   |   0.1368   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3871   |   0.4967   |   0.0451   |   0.1148   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4107   |   0.5511   |   0.0106   |   0.0421   |

<a name="table43"></a>Table 43: Mean AOE1/AOE2 for estimates compared to version [3.0-no-dupes](#30-no-dupes) ordered by mean.

[CSV](data/ballroom_estimates_3.0-no-dupes_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_3.0-no-dupes_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_distribution_aoe1.svg">
</figure>

<a name="figure133"></a>Figure 133: AOE<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0-no-dupes_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_distribution_aoe2.svg">
</figure>

<a name="figure134"></a>Figure 134: AOE<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_3.0-no-dupes_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 4.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0305__ | __0.1490__ | __0.0085__ | __0.0264__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0344   |   0.1598   |   0.0088   |   0.0281   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0425   |   0.1806   |   0.0102   |   0.0389   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0646   |   0.2303   |   0.0095   |   0.0395   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0659   |   0.2336   |   0.0095   |   0.0360   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0932   |   0.2737   |   0.0135   |   0.0505   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1426   |   0.3362   |   0.0152   |   0.0567   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1712   |   0.3713   |   0.0121   |   0.0264   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2975   |   0.4296   |   0.0382   |   0.0730   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3084   |   0.4476   |   0.0214   |   0.0654   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3163   |   0.4386   |   0.0359   |   0.0755   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3183   |   0.4449   |   0.0311   |   0.0852   |
| [schreiber2014/default](#schreiber2014default)     |   0.3212   |   0.4539   |   0.0197   |   0.0702   |
| [percival2014/stem](#percival2014stem)             |   0.3309   |   0.4783   |   0.0202   |   0.0623   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3402   |   0.4320   |   0.0712   |   0.1356   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3852   |   0.4927   |   0.0496   |   0.1159   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4061   |   0.5501   |   0.0125   |   0.0418   |

<a name="table44"></a>Table 44: Mean AOE1/AOE2 for estimates compared to version [4.0](#40) ordered by mean.

[CSV](data/ballroom_estimates_4.0_maoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_maoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ballroom_estimates_4.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ballroom_estimates_4.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ballroom_estimates_4.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ballroom_estimates_4.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ballroom_estimates_4.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_distribution_aoe1.svg">
</figure>

<a name="figure135"></a>Figure 135: AOE<sub>1</sub> for estimates compared to version [4.0](#40). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_4.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_distribution_aoe2.svg">
</figure>

<a name="figure136"></a>Figure 136: AOE<sub>2</sub> for estimates compared to version [4.0](#40). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ballroom_estimates_4.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0268__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.4058   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0611   | __0.0001__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.4058   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1183   | __0.0001__ | __0.0002__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1215   |   0.1767   | __0.0445__ | __0.0232__ |   0.1422   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4642   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1913   | __0.0001__ | __0.0000__ | __0.0016__ | __0.0077__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1913   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.1215   | __0.0001__ | __0.0000__ |   1.0000   |   0.6905   |   0.1382   |   0.2342   |   0.7689   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1114   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1767   | __0.0000__ | __0.0000__ |   0.6905   |   1.0000   |   0.0849   |   0.1832   |   0.5806   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2140   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0445__ | __0.0016__ | __0.0000__ |   0.1382   |   0.0849   |   1.0000   |   0.6524   |   0.2608   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0232__ | __0.0077__ | __0.0014__ |   0.2342   |   0.1832   |   0.6524   |   1.0000   |   0.3117   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0873   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.1422   | __0.0001__ | __0.0000__ |   0.7689   |   0.5806   |   0.2608   |   0.3117   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1283   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0268__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0169__ | __0.0159__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.0611   |   0.1183   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0116__ | __0.0062__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0169__ | __0.0116__ |   1.0000   |   0.9708   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0159__ | __0.0062__ |   0.9708   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.4642   | __0.0000__ | __0.0000__ |   0.1114   |   0.2140   | __0.0072__ |   0.0873   |   0.1283   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table45"></a>Table 45: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0136__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.7786   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0346__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.7786   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.2803   |   0.2996   |   0.1297   | __0.0380__ |   0.3557   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8410   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2013   | __0.0001__ | __0.0001__ | __0.0010__ | __0.0148__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2013   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0023__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.2803   | __0.0001__ | __0.0000__ |   1.0000   |   0.9454   |   0.2071   |   0.1679   |   0.9757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0734   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.2996   | __0.0001__ | __0.0000__ |   0.9454   |   1.0000   |   0.2025   |   0.1596   |   0.9396   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0765   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.1297   | __0.0010__ | __0.0000__ |   0.2071   |   0.2025   |   1.0000   |   0.4723   |   0.2491   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0380__ | __0.0148__ | __0.0023__ |   0.1679   |   0.1596   |   0.4723   |   1.0000   |   0.1874   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0444__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.3557   | __0.0001__ | __0.0000__ |   0.9757   |   0.9396   |   0.2491   |   0.1874   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1566   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0136__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0220__ | __0.0276__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0346__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0126__ | __0.0053__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0220__ | __0.0126__ |   1.0000   |   0.8801   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0276__ | __0.0053__ |   0.8801   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.8410   | __0.0000__ | __0.0000__ |   0.0734   |   0.0765   | __0.0081__ | __0.0444__ |   0.1566   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table46"></a>Table 46: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0138__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.7786   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0346__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.7786   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.2608   |   0.2910   |   0.1224   |   0.0576   |   0.3010   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7987   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1864   | __0.0001__ | __0.0000__ | __0.0008__ | __0.0078__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1864   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.2608   | __0.0001__ | __0.0000__ |   1.0000   |   0.9007   |   0.2099   |   0.2392   |   0.8699   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0782   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.2910   | __0.0000__ | __0.0000__ |   0.9007   |   1.0000   |   0.1895   |   0.2219   |   0.8093   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0911   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.1224   | __0.0008__ | __0.0000__ |   0.2099   |   0.1895   |   1.0000   |   0.5819   |   0.3122   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0083__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0576   | __0.0078__ | __0.0010__ |   0.2392   |   0.2219   |   0.5819   |   1.0000   |   0.2883   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0715   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.3010   | __0.0001__ | __0.0000__ |   0.8699   |   0.8093   |   0.3122   |   0.2883   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1248   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0138__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0218__ | __0.0273__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0346__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0126__ | __0.0053__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0218__ | __0.0126__ |   1.0000   |   0.8801   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0273__ | __0.0053__ |   0.8801   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.7987   | __0.0000__ | __0.0000__ |   0.0782   |   0.0911   | __0.0083__ |   0.0715   |   0.1248   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table47"></a>Table 47: Paired t-test p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0298__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.7882   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0400__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.7882   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0447__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.2437   |   0.2427   |   0.0977   | __0.0340__ |   0.2843   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7189   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2125   | __0.0001__ | __0.0001__ | __0.0010__ | __0.0118__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2125   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.2437   | __0.0001__ | __0.0000__ |   1.0000   |   0.9722   |   0.1614   |   0.1787   |   0.8634   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1053   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.2427   | __0.0001__ | __0.0000__ |   0.9722   |   1.0000   |   0.1809   |   0.1808   |   0.8903   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0912   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0977   | __0.0010__ | __0.0000__ |   0.1614   |   0.1809   |   1.0000   |   0.5293   |   0.2486   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0079__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0340__ | __0.0118__ | __0.0019__ |   0.1787   |   0.1808   |   0.5293   |   1.0000   |   0.2215   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0554   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.2843   | __0.0001__ | __0.0000__ |   0.8634   |   0.8903   |   0.2486   |   0.2215   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1539   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0298__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0183__ | __0.0216__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0400__ | __0.0447__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0127__ | __0.0058__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0183__ | __0.0127__ |   1.0000   |   0.9033   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0216__ | __0.0058__ |   0.9033   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.7189   | __0.0000__ | __0.0000__ |   0.1053   |   0.0912   | __0.0079__ |   0.0554   |   0.1539   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table48"></a>Table 48: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0294__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.7882   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0400__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.7882   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0447__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.2253   |   0.2347   |   0.0922   |   0.0519   |   0.2378   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6802   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1974   | __0.0001__ | __0.0000__ | __0.0008__ | __0.0061__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1974   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.2253   | __0.0001__ | __0.0000__ |   1.0000   |   0.9822   |   0.1652   |   0.2534   |   0.7636   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1098   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.2347   | __0.0000__ | __0.0000__ |   0.9822   |   1.0000   |   0.1707   |   0.2489   |   0.7645   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1061   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0922   | __0.0008__ | __0.0000__ |   0.1652   |   0.1707   |   1.0000   |   0.6441   |   0.3125   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0519   | __0.0061__ | __0.0008__ |   0.2534   |   0.2489   |   0.6441   |   1.0000   |   0.3337   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0875   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.2378   | __0.0001__ | __0.0000__ |   0.7636   |   0.7645   |   0.3125   |   0.3337   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1221   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0294__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0181__ | __0.0213__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0400__ | __0.0447__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0127__ | __0.0058__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0181__ | __0.0127__ |   1.0000   |   0.9033   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0213__ | __0.0058__ |   0.9033   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.6802   | __0.0000__ | __0.0000__ |   0.1098   |   0.1061   | __0.0081__ |   0.0875   |   0.1221   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table49"></a>Table 49: Paired t-test p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0613   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.2034   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0739   | __0.0000__ | __0.0001__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.2034   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2013   | __0.0001__ | __0.0004__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1312   |   0.1787   |   0.0508   | __0.0180__ |   0.1469   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4625   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2314   | __0.0001__ | __0.0000__ | __0.0010__ | __0.0103__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2314   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0019__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.1312   | __0.0001__ | __0.0000__ |   1.0000   |   0.7431   |   0.1534   |   0.1930   |   0.7383   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1351   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1787   | __0.0000__ | __0.0000__ |   0.7431   |   1.0000   |   0.1047   |   0.1561   |   0.5892   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2235   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0508   | __0.0010__ | __0.0000__ |   0.1534   |   0.1047   |   1.0000   |   0.5673   |   0.2988   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0099__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0180__ | __0.0103__ | __0.0019__ |   0.1930   |   0.1561   |   0.5673   |   1.0000   |   0.2739   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0699   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   0.1469   | __0.0001__ | __0.0000__ |   0.7383   |   0.5892   |   0.2988   |   0.2739   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1354   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0613   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0189__ | __0.0127__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ |   0.0739   |   0.2013   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0064__ | __0.0067__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0189__ | __0.0064__ |   1.0000   |   0.8797   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0001__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ | __0.0067__ |   0.8797   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.4625   | __0.0000__ | __0.0000__ |   0.1351   |   0.2235   | __0.0099__ |   0.0699   |   0.1354   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table50"></a>Table 50: Paired t-test p-values, using reference annotations [4.0](#40) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3037   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0022__ |   0.1130   |   0.4266   |   0.0619   | __0.0051__ | __0.0142__ | __0.0001__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.1827   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0026__ |   0.1574   |   0.3086   |   0.4115   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.1827   |   1.0000   | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0012__ | __0.0066__ |   0.3172   |   0.5733   |   0.6518   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0081__ | __0.0000__ |   0.0900   |   0.5027   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0010__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3037   | __0.0006__ | __0.0018__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0183__ | __0.0000__ | __0.0403__ |   0.5495   |   0.9031   |   0.0505   | __0.0149__ | __0.0168__ | __0.0020__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ |   0.0900   | __0.0001__ | __0.0000__ |   1.0000   |   0.2410   | __0.0004__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.5027   | __0.0010__ | __0.0000__ |   0.2410   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0183__ | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ |   0.9726   |   0.0680   | __0.0120__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3900   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0022__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0403__ | __0.0006__ | __0.0000__ |   0.9726   | __0.0000__ |   1.0000   | __0.0125__ | __0.0052__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4085   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1130   | __0.0005__ | __0.0012__ | __0.0000__ | __0.0000__ |   0.5495   | __0.0000__ | __0.0000__ |   0.0680   | __0.0000__ | __0.0125__ |   1.0000   |   0.2658   | __0.0065__ | __0.0014__ | __0.0026__ | __0.0164__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.4266   | __0.0026__ | __0.0066__ | __0.0000__ | __0.0000__ |   0.9031   | __0.0000__ | __0.0000__ | __0.0120__ | __0.0000__ | __0.0052__ |   0.2658   |   1.0000   | __0.0112__ | __0.0076__ | __0.0138__ | __0.0025__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0619   |   0.1574   |   0.3172   | __0.0000__ | __0.0000__ |   0.0505   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0065__ | __0.0112__ |   1.0000   |   0.5978   |   0.5061   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0051__ |   0.3086   |   0.5733   | __0.0000__ | __0.0000__ | __0.0149__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0076__ |   0.5978   |   1.0000   |   0.9673   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0142__ |   0.4115   |   0.6518   | __0.0000__ | __0.0000__ | __0.0168__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0026__ | __0.0138__ |   0.5061   |   0.9673   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0014__ | __0.0000__ |   0.3900   | __0.0000__ |   0.4085   | __0.0164__ | __0.0025__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table51"></a>Table 51: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0380__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0059__ |   0.2236   |   0.7170   |   0.7549   |   0.5960   |   0.8012   | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.3895   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0074__ | __0.0002__ | __0.0000__ | __0.0004__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.3895   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0035__ | __0.0177__ | __0.0013__ | __0.0001__ | __0.0027__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1361   | __0.0000__ | __0.0038__ |   0.1321   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1361   |   1.0000   | __0.0000__ | __0.0002__ | __0.0095__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0380__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0775   | __0.0000__ |   0.2139   |   0.7198   |   0.2403   |   0.1220   |   0.1171   |   0.1023   | __0.0072__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0002__ | __0.0000__ |   1.0000   |   0.0979   | __0.0001__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1321   | __0.0095__ | __0.0000__ |   0.0979   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0775   | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ |   0.7791   | __0.0345__ | __0.0042__ | __0.0003__ | __0.0009__ | __0.0005__ |   0.3143   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0059__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.2139   | __0.0001__ | __0.0000__ |   0.7791   | __0.0000__ |   1.0000   | __0.0116__ | __0.0043__ | __0.0046__ | __0.0069__ | __0.0077__ |   0.2387   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2236   | __0.0015__ | __0.0035__ | __0.0000__ | __0.0000__ |   0.7198   | __0.0000__ | __0.0000__ | __0.0345__ | __0.0000__ | __0.0116__ |   1.0000   |   0.2470   |   0.2829   |   0.2963   |   0.2759   | __0.0061__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7170   | __0.0074__ | __0.0177__ | __0.0000__ | __0.0000__ |   0.2403   | __0.0000__ | __0.0000__ | __0.0042__ | __0.0000__ | __0.0043__ |   0.2470   |   1.0000   |   0.8477   |   0.9407   |   0.8411   | __0.0007__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7549   | __0.0002__ | __0.0013__ | __0.0000__ | __0.0000__ |   0.1220   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0046__ |   0.2829   |   0.8477   |   1.0000   |   0.8901   |   0.9487   | __0.0001__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5960   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.1171   | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0069__ |   0.2963   |   0.9407   |   0.8901   |   1.0000   |   0.8330   | __0.0001__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8012   | __0.0004__ | __0.0027__ | __0.0000__ | __0.0000__ |   0.1023   | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0077__ |   0.2759   |   0.8411   |   0.9487   |   0.8330   |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ | __0.0008__ | __0.0000__ |   0.3143   | __0.0000__ |   0.2387   | __0.0061__ | __0.0007__ | __0.0001__ | __0.0001__ | __0.0001__ |   1.0000   |

<a name="table52"></a>Table 52: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0360__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0053__ |   0.2073   |   0.6791   |   0.7265   |   0.5655   |   0.7729   | __0.0001__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.3895   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0074__ | __0.0002__ | __0.0000__ | __0.0004__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.3895   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0035__ | __0.0177__ | __0.0013__ | __0.0001__ | __0.0027__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1514   | __0.0000__ | __0.0036__ |   0.1472   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1514   |   1.0000   | __0.0000__ | __0.0003__ | __0.0121__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0360__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0748   | __0.0000__ |   0.2077   |   0.7352   |   0.2495   |   0.1228   |   0.1180   |   0.1031   | __0.0103__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0036__ | __0.0003__ | __0.0000__ |   1.0000   |   0.0857   | __0.0001__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.1472   | __0.0121__ | __0.0000__ |   0.0857   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0748   | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ |   0.7814   | __0.0348__ | __0.0043__ | __0.0003__ | __0.0008__ | __0.0005__ |   0.3939   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0053__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.2077   | __0.0001__ | __0.0000__ |   0.7814   | __0.0000__ |   1.0000   | __0.0116__ | __0.0043__ | __0.0044__ | __0.0065__ | __0.0073__ |   0.2996   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2073   | __0.0015__ | __0.0035__ | __0.0000__ | __0.0000__ |   0.7352   | __0.0000__ | __0.0000__ | __0.0348__ | __0.0000__ | __0.0116__ |   1.0000   |   0.2470   |   0.2725   |   0.2851   |   0.2659   | __0.0089__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6791   | __0.0074__ | __0.0177__ | __0.0000__ | __0.0000__ |   0.2495   | __0.0000__ | __0.0000__ | __0.0043__ | __0.0000__ | __0.0043__ |   0.2470   |   1.0000   |   0.8223   |   0.9167   |   0.8196   | __0.0011__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7265   | __0.0002__ | __0.0013__ | __0.0000__ | __0.0000__ |   0.1228   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0044__ |   0.2725   |   0.8223   |   1.0000   |   0.8901   |   0.9487   | __0.0002__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5655   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.1180   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ | __0.0065__ |   0.2851   |   0.9167   |   0.8901   |   1.0000   |   0.8331   | __0.0001__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7729   | __0.0004__ | __0.0027__ | __0.0000__ | __0.0000__ |   0.1031   | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0073__ |   0.2659   |   0.8196   |   0.9487   |   0.8331   |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0103__ | __0.0007__ | __0.0000__ |   0.3939   | __0.0000__ |   0.2996   | __0.0089__ | __0.0011__ | __0.0002__ | __0.0001__ | __0.0001__ |   1.0000   |

<a name="table53"></a>Table 53: Paired t-test p-values, using reference annotations [3.0-no-dupes](#30-no-dupes) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3443   |   0.1935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0021__ | __0.0003__ | __0.0000__ | __0.0006__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.3443   |   1.0000   |   0.4278   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0040__ | __0.0011__ | __0.0000__ | __0.0016__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1935   |   0.4278   |   1.0000   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0021__ | __0.0107__ | __0.0056__ | __0.0006__ | __0.0094__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0413__ | __0.0000__ | __0.0184__ |   0.4352   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0413__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0076__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0549   | __0.0000__ |   0.1314   |   0.9387   |   0.3899   |   0.1146   |   0.1125   |   0.0866   | __0.0035__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0184__ | __0.0001__ | __0.0000__ |   1.0000   |   0.0779   | __0.0003__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0033__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.4352   | __0.0076__ | __0.0000__ |   0.0779   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0549   | __0.0003__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8774   | __0.0450__ | __0.0060__ | __0.0001__ | __0.0004__ | __0.0002__ |   0.2739   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1314   | __0.0004__ | __0.0000__ |   0.8774   | __0.0000__ |   1.0000   | __0.0101__ | __0.0038__ | __0.0013__ | __0.0021__ | __0.0019__ |   0.2521   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0004__ | __0.0008__ | __0.0021__ | __0.0000__ | __0.0000__ |   0.9387   | __0.0000__ | __0.0000__ | __0.0450__ | __0.0000__ | __0.0101__ |   1.0000   |   0.2481   |   0.1332   |   0.1380   |   0.1119   | __0.0062__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0021__ | __0.0040__ | __0.0107__ | __0.0000__ | __0.0000__ |   0.3899   | __0.0000__ | __0.0000__ | __0.0060__ | __0.0000__ | __0.0038__ |   0.2481   |   1.0000   |   0.4263   |   0.5389   |   0.4298   | __0.0008__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0003__ | __0.0011__ | __0.0056__ | __0.0000__ | __0.0000__ |   0.1146   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0013__ |   0.1332   |   0.4263   |   1.0000   |   0.8643   |   0.8745   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ |   0.1125   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0021__ |   0.1380   |   0.5389   |   0.8643   |   1.0000   |   0.7354   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0006__ | __0.0016__ | __0.0094__ | __0.0000__ | __0.0000__ |   0.0866   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0019__ |   0.1119   |   0.4298   |   0.8745   |   0.7354   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0035__ | __0.0033__ | __0.0000__ |   0.2739   | __0.0000__ |   0.2521   | __0.0062__ | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table54"></a>Table 54: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3443   |   0.1935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0024__ | __0.0004__ | __0.0000__ | __0.0009__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.3443   |   1.0000   |   0.4278   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0040__ | __0.0011__ | __0.0000__ | __0.0016__ | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1935   |   0.4278   |   1.0000   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0021__ | __0.0107__ | __0.0056__ | __0.0006__ | __0.0094__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0481__ | __0.0000__ | __0.0175__ |   0.4601   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0481__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0099__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0529   | __0.0000__ |   0.1260   |   0.9594   |   0.4058   |   0.1166   |   0.1147   |   0.0883   | __0.0050__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0175__ | __0.0001__ | __0.0000__ |   1.0000   |   0.0692   | __0.0004__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0028__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.4601   | __0.0099__ | __0.0000__ |   0.0692   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0529   | __0.0004__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8835   | __0.0460__ | __0.0061__ | __0.0001__ | __0.0004__ | __0.0002__ |   0.3430   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1260   | __0.0005__ | __0.0000__ |   0.8835   | __0.0000__ |   1.0000   | __0.0101__ | __0.0038__ | __0.0012__ | __0.0020__ | __0.0018__ |   0.3149   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0005__ | __0.0008__ | __0.0021__ | __0.0000__ | __0.0000__ |   0.9594   | __0.0000__ | __0.0000__ | __0.0460__ | __0.0000__ | __0.0101__ |   1.0000   |   0.2481   |   0.1268   |   0.1310   |   0.1062   | __0.0090__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0024__ | __0.0040__ | __0.0107__ | __0.0000__ | __0.0000__ |   0.4058   | __0.0000__ | __0.0000__ | __0.0061__ | __0.0000__ | __0.0038__ |   0.2481   |   1.0000   |   0.4059   |   0.5172   |   0.4120   | __0.0012__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0004__ | __0.0011__ | __0.0056__ | __0.0000__ | __0.0000__ |   0.1166   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0012__ |   0.1268   |   0.4059   |   1.0000   |   0.8643   |   0.8745   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ |   0.1147   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0020__ |   0.1310   |   0.5172   |   0.8643   |   1.0000   |   0.7354   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0009__ | __0.0016__ | __0.0094__ | __0.0000__ | __0.0000__ |   0.0883   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0018__ |   0.1062   |   0.4120   |   0.8745   |   0.7354   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0050__ | __0.0028__ | __0.0000__ |   0.3430   | __0.0000__ |   0.3149   | __0.0090__ | __0.0012__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table55"></a>Table 55: Paired t-test p-values, using reference annotations [2.0-no-dupes](#20-no-dupes) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7998   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0021__ |   0.1103   |   0.4185   |   0.0838   | __0.0056__ | __0.0191__ | __0.0003__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   |   0.2536   | __0.0000__ | __0.0000__ | __0.0073__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0027__ |   0.1257   |   0.3043   |   0.3633   | __0.0000__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ |   0.2536   |   1.0000   | __0.0000__ | __0.0000__ | __0.0158__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0011__ | __0.0061__ |   0.2450   |   0.5316   |   0.5589   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0106__ | __0.0000__ | __0.0324__ |   0.4180   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0106__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7998   | __0.0073__ | __0.0158__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0023__ | __0.0000__ | __0.0126__ |   0.2656   |   0.6635   |   0.2085   |   0.0757   |   0.0906   | __0.0010__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0324__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1346   | __0.0015__ | __0.0000__ | __0.0016__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ |   0.4180   | __0.0013__ | __0.0000__ |   0.1346   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0023__ | __0.0015__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8555   | __0.0442__ | __0.0063__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6790   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0021__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0126__ | __0.0016__ | __0.0000__ |   0.8555   | __0.0000__ |   1.0000   | __0.0111__ | __0.0047__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5759   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1103   | __0.0005__ | __0.0011__ | __0.0000__ | __0.0000__ |   0.2656   | __0.0000__ | __0.0000__ | __0.0442__ | __0.0000__ | __0.0111__ |   1.0000   |   0.2658   | __0.0081__ | __0.0014__ | __0.0031__ | __0.0345__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.4185   | __0.0027__ | __0.0061__ | __0.0000__ | __0.0000__ |   0.6635   | __0.0000__ | __0.0000__ | __0.0063__ | __0.0000__ | __0.0047__ |   0.2658   |   1.0000   | __0.0149__ | __0.0063__ | __0.0141__ | __0.0064__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0838   |   0.1257   |   0.2450   | __0.0000__ | __0.0000__ |   0.2085   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ | __0.0149__ |   1.0000   |   0.5200   |   0.4809   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0056__ |   0.3043   |   0.5316   | __0.0000__ | __0.0000__ |   0.0757   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0063__ |   0.5200   |   1.0000   |   0.9652   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0191__ |   0.3633   |   0.5589   | __0.0000__ | __0.0000__ |   0.0906   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0031__ | __0.0141__ |   0.4809   |   0.9652   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0016__ | __0.0000__ |   0.6790   | __0.0000__ |   0.5759   | __0.0345__ | __0.0064__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table56"></a>Table 56: Paired t-test p-values, using reference annotations [4.0](#40) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ballroom_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ballroom_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ballroom_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure137"></a>Figure 137: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure138"></a>Figure 138: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.svg">
</figure>

<a name="figure139"></a>Figure 139: Mean AOE<sub>1</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure140"></a>Figure 140: Mean AOE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.svg">
</figure>

<a name="figure141"></a>Figure 141: Mean AOE<sub>1</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure142"></a>Figure 142: Mean AOE<sub>1</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure143"></a>Figure 143: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/ballroom_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure144"></a>Figure 144: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/ballroom_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.svg">
</figure>

<a name="figure145"></a>Figure 145: Mean AOE<sub>2</sub> compared to version [2.0-no-dupes](#20-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0-no-dupes](#20-no-dupes).

[CSV](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure146"></a>Figure 146: Mean AOE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/ballroom_estimates_3.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0-no-dupes based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.svg">
</figure>

<a name="figure147"></a>Figure 147: Mean AOE<sub>2</sub> compared to version [3.0-no-dupes](#30-no-dupes) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0-no-dupes](#30-no-dupes).

[CSV](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 4.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure148"></a>Figure 148: Mean AOE<sub>2</sub> compared to version [4.0](#40) for tracks with c<sub>var</sub> < τ based on beat annotations from [4.0](#40).

[CSV](data/ballroom_estimates_4.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure149"></a>Figure 149: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure150"></a>Figure 150: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_aoe1.svg">
</figure>

<a name="figure151"></a>Figure 151: Mean AOE<sub>1</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_aoe1.svg">
</figure>

<a name="figure152"></a>Figure 152: Mean AOE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_aoe1.svg">
</figure>

<a name="figure153"></a>Figure 153: Mean AOE<sub>1</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_aoe1.svg">
</figure>

<a name="figure154"></a>Figure 154: Mean AOE<sub>1</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure155"></a>Figure 155: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ballroom_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure156"></a>Figure 156: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_inter_aoe2.svg">
</figure>

<a name="figure157"></a>Figure 157: Mean AOE<sub>2</sub> for estimates compared to version [2.0-no-dupes](#20-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_2.0-no-dupes_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_inter_aoe2.svg">
</figure>

<a name="figure158"></a>Figure 158: Mean AOE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_inter_aoe2.svg">
</figure>

<a name="figure159"></a>Figure 159: Mean AOE<sub>2</sub> for estimates compared to version [3.0-no-dupes](#30-no-dupes) for tempo intervals around T.

[CSV](data/ballroom_estimates_3.0-no-dupes_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_inter_aoe2.svg">
</figure>

<a name="figure160"></a>Figure 160: Mean AOE<sub>2</sub> for estimates compared to version [4.0](#40) for tempo intervals around T.

[CSV](data/ballroom_estimates_4.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_inter_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure161"></a>Figure 161: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure162"></a>Figure 162: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.svg">
</figure>

<a name="figure163"></a>Figure 163: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure164"></a>Figure 164: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.svg">
</figure>

<a name="figure165"></a>Figure 165: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 4.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure166"></a>Figure 166: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure167"></a>Figure 167: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure168"></a>Figure 168: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0-no-dupes

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0-no-dupes](#20-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.svg">
</figure>

<a name="figure169"></a>Figure 169: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0-no-dupes](#20-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_2.0-no-dupes_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure170"></a>Figure 170: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 3.0-no-dupes

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [3.0-no-dupes](#30-no-dupes).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.svg">
</figure>

<a name="figure171"></a>Figure 171: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [3.0-no-dupes](#30-no-dupes). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_3.0-no-dupes_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 4.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [4.0](#40).

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_4.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure172"></a>Figure 172: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [4.0](#40). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ballroom_estimates_4.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ballroom_estimates_4.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ballroom_estimates_4.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ballroom_estimates_4.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ballroom_estimates_4.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_4.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_4.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure173"></a>Figure 173: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure174"></a>Figure 174: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe1.svg">
</figure>

<a name="figure175"></a>Figure 175: AOE<sub>1</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.svg">
</figure>

<a name="figure176"></a>Figure 176: AOE<sub>1</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe1.svg">
</figure>

<a name="figure177"></a>Figure 177: AOE<sub>1</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_aoe1.svg">
</figure>

<a name="figure178"></a>Figure 178: AOE<sub>1</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_4.0_aoe1.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_aoe1.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure179"></a>Figure 179: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure180"></a>Figure 180: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe2.svg">
</figure>

<a name="figure181"></a>Figure 181: AOE<sub>2</sub> of estimates compared to version [2.0-no-dupes](#20-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_2.0-no-dupes_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 3.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.svg">
</figure>

<a name="figure182"></a>Figure 182: AOE<sub>2</sub> of estimates compared to version [3.0](#30) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 3.0-no-dupes

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe2.svg">
</figure>

<a name="figure183"></a>Figure 183: AOE<sub>2</sub> of estimates compared to version [3.0-no-dupes](#30-no-dupes) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_3.0-no-dupes_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 4.0

<figure>
<embed type="image/svg+xml" src="figures/ballroom_estimates_1.0_tag_open_4.0_aoe2.svg">
</figure>

<a name="figure184"></a>Figure 184: AOE<sub>2</sub> of estimates compared to version [4.0](#40) depending on tag from namespace 'tag_open'.

[SVG](figures/ballroom_estimates_1.0_tag_open_4.0_aoe2.svg "Open Figure") [PDF](figures/ballroom_estimates_1.0_tag_open_4.0_aoe2.pdf "Open Figure") [PNG](figures/ballroom_estimates_1.0_tag_open_4.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-04 17:08. Size L.
