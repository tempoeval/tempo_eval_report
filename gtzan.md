---
title: gtzan
{:.no_toc}
layout: default
---

# gtzan
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'gtzan' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'gtzan'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | GTZAN |
| **Version** | 1.0 |
| **Curator** | [George Tzanetakis](mailto:gtzan@cs.uvic.ca) |
| **Annotator,&nbsp;bibtex** |[Tzanetakis2013](bib/Tzanetakis2013.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | GTZAN |
| **Version** | 2.0 |
| **Curator** | [Graham Percival](mailto:graham@percival-music.ca) |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

### GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

| Attribute | Value |
| --- | --- |
| **Corpus** | GTZAN |
| **Version** | GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 |
| **Curator** | [Ugo Marchand & Quentin Fresnel](mailto:ugo.marchand@ircam.fr) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Marchand2015](bib/Marchand2015.bib) |
| **Annotator,&nbsp;ref_url** | [https://hal.archives-ouvertes.fr/hal-01252603/document](https://hal.archives-ouvertes.fr/hal-01252603/document) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   1000   |   38.00   |   168.00   |   94.27   |   24.45   |   66.00   |   0.81   |
| [2.0](#20)                                         |   999   |   38.00   |   168.00   |   94.92   |   24.41   |   66.00   |   0.81   |
| [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) |   1000   |   37.68   |   339.29   |   119.53   |   40.13   |   79.00   |   0.74   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/gtzan_reference_basic_stats.csv "Download data as CSV") [JSON](data/gtzan_reference_basic_stats.json "Download data as JSON") [LATEX](data/gtzan_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/gtzan_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/gtzan_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/gtzan_reference_dist.csv "Download data as CSV") [JSON](data/gtzan_reference_dist.json "Download data as JSON") [LATEX](data/gtzan_reference_dist.latex "Download data as LATEX") [PICKLE](data/gtzan_reference_dist.pickle "Download data as PICKLE") [SVG](figures/gtzan_reference_dist.svg "Open Figure") [PDF](figures/gtzan_reference_dist.pdf "Open Figure") [PNG](figures/gtzan_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_gtzan'

<figure>
<embed type="image/svg+xml" src="figures/gtzan_reference_1.0_tag_gtzan.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_gtzan'. Annotations are from reference [1.0](#10).

[CSV](data/gtzan_reference_1.0_tag_gtzan.csv "Download data as CSV") [JSON](data/gtzan_reference_1.0_tag_gtzan.json "Download data as JSON") [LATEX](data/gtzan_reference_1.0_tag_gtzan.latex "Download data as LATEX") [PICKLE](data/gtzan_reference_1.0_tag_gtzan.pickle "Download data as PICKLE") [SVG](figures/gtzan_reference_1.0_tag_gtzan.svg "Open Figure") [PDF](figures/gtzan_reference_1.0_tag_gtzan.pdf "Open Figure") [PNG](figures/gtzan_reference_1.0_tag_gtzan.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.csv "Download data as CSV") [JSON](data/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.json "Download data as JSON") [LATEX](data/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.latex "Download data as LATEX") [PICKLE](data/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.pickle "Download data as PICKLE") [SVG](figures/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.svg "Open Figure") [PDF](figures/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.pdf "Open Figure") [PNG](figures/gtzan_reference_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/gtzan_variation.svg">
</figure>

<a name="figure4"></a>Figure 4: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/gtzan_variation.csv "Download data as CSV") [JSON](data/gtzan_variation.json "Download data as JSON") [LATEX](data/gtzan_variation.latex "Download data as LATEX") [PICKLE](data/gtzan_variation.pickle "Download data as PICKLE") [SVG](figures/gtzan_variation.svg "Open Figure") [PDF](figures/gtzan_variation.pdf "Open Figure") [PNG](figures/gtzan_variation.png "Open Figure") 

# Estimates for 'gtzan'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### echonest/version_3_2_1

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 3.2.1 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Echo Nest track analyzer v3.2.1 |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### gkiokas2012/default

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Gkiokas2012 |
| **Annotator,&nbsp;bibtex** |[Gkiokas2012](bib/Gkiokas2012.bib) |

### klapuri2006/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Klapuri 2006 |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### oliveira2010/ibt

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Oliveira 2010 |
| **Annotator,&nbsp;bibtex** |[Oliveira2010](bib/Oliveira2010.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### scheirer1998/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Scheirer 1998 |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

### zplane/auftakt_v3

| Attribute | Value |
| --- | --- |
| **Corpus** | gtzan |
| **Version** | 3.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | zplane aufTAKT version 3.0, http://licensing.zplane.de/technology#auftakt |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1000   |   41.10   |   240.00   |   114.70   |   33.90   |   72.00   |   0.79   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1000   |   63.02   |   258.40   |   122.69   |   27.27   |   84.00   |   0.90   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   1000   |   0.00   |   199.68   |   104.18   |   27.71   |   67.00   |   0.80   |
| [gkiokas2012/default](#gkiokas2012default)         |   1000   |   31.00   |   246.00   |   107.52   |   30.05   |   71.00   |   0.80   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   1000   |   62.64   |   161.50   |   110.85   |   20.30   |   76.00   |   0.95   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   1000   |   80.00   |   161.00   |   116.43   |   20.75   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   1000   |   50.42   |   154.27   |   102.55   |   21.52   |   71.00   |   0.92   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   1000   |   0.00   |   179.81   |   101.55   |   31.27   |   64.00   |   0.78   |
| [schreiber2014/default](#schreiber2014default)     |   1000   |   52.05   |   163.94   |   101.61   |   21.62   |   71.00   |   0.91   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1000   |   20.27   |   163.94   |   104.97   |   27.05   |   80.00   |   0.82   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1000   |   20.27   |   161.46   |   103.15   |   27.81   |   80.00   |   0.79   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1000   |   50.00   |   237.00   |   112.00   |   31.25   |   75.00   |   0.81   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1000   |   38.00   |   222.00   |   109.14   |   30.57   |   71.00   |   0.81   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1000   |   53.00   |   232.00   |   112.89   |   28.19   |   77.00   |   0.87   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   1000   |   65.00   |   165.40   |   109.51   |   22.56   |   73.00   |   0.89   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/gtzan_estimates_basic_stats.csv "Download data as CSV") [JSON](data/gtzan_estimates_basic_stats.json "Download data as JSON") [LATEX](data/gtzan_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_dist.svg">
</figure>

<a name="figure5"></a>Figure 5: Percentage of values in tempo interval.

[CSV](data/gtzan_estimates_dist.csv "Download data as CSV") [JSON](data/gtzan_estimates_dist.json "Download data as JSON") [LATEX](data/gtzan_estimates_dist.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_dist.svg "Open Figure") [PDF](figures/gtzan_estimates_dist.pdf "Open Figure") [PNG](figures/gtzan_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.7690__ |   0.9280   |
| [schreiber2014/default](#schreiber2014default)     |   0.7600   |   0.9170   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7160   |   0.9270   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7120   |   0.9270   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7060   |   0.9200   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7040   |   0.9270   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7020   |   0.9360   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6930   | __0.9420__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.6900   |   0.9100   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6790   |   0.8780   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6740   |   0.9200   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6700   |   0.8570   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6010   |   0.8610   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5870   |   0.8860   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5580   |   0.7570   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/gtzan_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/gtzan_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/gtzan_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/gtzan_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/gtzan_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.7808__ |   0.9419   |
| [schreiber2014/default](#schreiber2014default)     |   0.7738   |   0.9339   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7267   |   0.9379   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7217   |   0.9419   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7167   |   0.9510   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7167   |   0.9379   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7157   |   0.9419   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.7067   | __0.9560__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7037   |   0.9249   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6887   |   0.8919   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6857   |   0.9329   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6797   |   0.8699   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6096   |   0.8699   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6006   |   0.9009   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5666   |   0.7628   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/gtzan_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/gtzan_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/gtzan_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/gtzan_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/gtzan_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_accuracy2.png "Open Figure") 

### Accuracy Results for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.7810__ | __0.9580__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7740   |   0.9340   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7700   |   0.9490   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7540   |   0.9540   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7080   |   0.9160   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.7050   |   0.9290   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.6890   |   0.8750   |
| [schreiber2014/default](#schreiber2014default)     |   0.6850   |   0.9370   |
| [percival2014/stem](#percival2014stem)             |   0.6820   |   0.9440   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.6800   |   0.8900   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6710   |   0.9390   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6630   |   0.9380   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.6620   |   0.9340   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.6580   |   0.8730   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.5160   |   0.7690   |

<a name="table5"></a>Table 5: Mean accuracy of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy_tol04.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy_tol04.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tolerance.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tolerance.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (307 differences):*
'blues.00008' 'blues.00011' 'blues.00016' 'blues.00023' 'blues.00025' 'blues.00031' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00036' 'blues.00037' ...
[CSV](data/gtzan_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (413 differences):*
'blues.00006' 'blues.00007' 'blues.00008' 'blues.00009' 'blues.00011' 'blues.00023' 'blues.00025' 'blues.00029' 'blues.00030' 'blues.00032' 'blues.00034' ...
[CSV](data/gtzan_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (330 differences):*
'blues.00002' 'blues.00005' 'blues.00011' 'blues.00017' 'blues.00020' 'blues.00022' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00031' 'blues.00032' ...
[CSV](data/gtzan_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (294 differences):*
'blues.00000' 'blues.00002' 'blues.00004' 'blues.00008' 'blues.00010' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00033' 'blues.00035' 'blues.00036' ...
[CSV](data/gtzan_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (310 differences):*
'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00037' ...
[CSV](data/gtzan_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (399 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00023' 'blues.00025' 'blues.00032' 'blues.00035' ...
[CSV](data/gtzan_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (231 differences):*
'blues.00002' 'blues.00003' 'blues.00008' 'blues.00010' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' ...
[CSV](data/gtzan_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (442 differences):*
'blues.00000' 'blues.00004' 'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00013' 'blues.00014' 'blues.00017' 'blues.00019' 'blues.00020' ...
[CSV](data/gtzan_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (240 differences):*
'blues.00001' 'blues.00002' 'blues.00003' 'blues.00005' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00031' ...
[CSV](data/gtzan_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (296 differences):*
'blues.00006' 'blues.00008' 'blues.00009' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00023' 'blues.00026' 'blues.00029' ...
[CSV](data/gtzan_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (288 differences):*
'blues.00008' 'blues.00009' 'blues.00014' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00023' 'blues.00026' 'blues.00029' ...
[CSV](data/gtzan_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (298 differences):*
'blues.00006' 'blues.00011' 'blues.00015' 'blues.00017' 'blues.00022' 'blues.00023' 'blues.00029' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00037' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (284 differences):*
'blues.00001' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00037' 'blues.00040' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (326 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00011' 'blues.00017' 'blues.00023' 'blues.00029' 'blues.00031' 'blues.00033' 'blues.00035' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (321 differences):*
'blues.00002' 'blues.00003' 'blues.00006' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00018' 'blues.00023' 'blues.00029' 'blues.00032' 'blues.00035' ...
[CSV](data/gtzan_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (293 differences):*
'blues.00008' 'blues.00011' 'blues.00016' 'blues.00025' 'blues.00031' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00036' 'blues.00037' 'blues.00040' ...
[CSV](data/gtzan_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (399 differences):*
'blues.00006' 'blues.00007' 'blues.00008' 'blues.00009' 'blues.00011' 'blues.00025' 'blues.00030' 'blues.00032' 'blues.00034' 'blues.00035' 'blues.00037' ...
[CSV](data/gtzan_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (320 differences):*
'blues.00002' 'blues.00005' 'blues.00011' 'blues.00017' 'blues.00020' 'blues.00022' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00037' ...
[CSV](data/gtzan_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (283 differences):*
'blues.00000' 'blues.00002' 'blues.00004' 'blues.00008' 'blues.00010' 'blues.00017' 'blues.00033' 'blues.00035' 'blues.00036' 'blues.00037' 'blues.00040' ...
[CSV](data/gtzan_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (296 differences):*
'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00042' 'blues.00047' ...
[CSV](data/gtzan_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (390 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00025' 'blues.00032' 'blues.00035' 'blues.00037' ...
[CSV](data/gtzan_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (219 differences):*
'blues.00002' 'blues.00003' 'blues.00008' 'blues.00010' 'blues.00017' 'blues.00029' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00036' ...
[CSV](data/gtzan_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (433 differences):*
'blues.00000' 'blues.00004' 'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00013' 'blues.00014' 'blues.00017' 'blues.00019' 'blues.00020' ...
[CSV](data/gtzan_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (226 differences):*
'blues.00001' 'blues.00002' 'blues.00003' 'blues.00005' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00031' 'blues.00032' 'blues.00033' ...
[CSV](data/gtzan_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (284 differences):*
'blues.00006' 'blues.00008' 'blues.00009' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00026' 'blues.00031' 'blues.00032' ...
[CSV](data/gtzan_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (278 differences):*
'blues.00008' 'blues.00009' 'blues.00014' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00026' 'blues.00031' 'blues.00032' ...
[CSV](data/gtzan_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (283 differences):*
'blues.00006' 'blues.00011' 'blues.00015' 'blues.00017' 'blues.00022' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00037' 'blues.00040' 'blues.00047' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (273 differences):*
'blues.00001' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00037' 'blues.00040' 'blues.00047' 'blues.00049' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (314 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00011' 'blues.00017' 'blues.00031' 'blues.00033' 'blues.00035' 'blues.00037' 'blues.00042' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (311 differences):*
'blues.00002' 'blues.00003' 'blues.00006' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00018' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00038' ...
[CSV](data/gtzan_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (219 differences):*
'blues.00008' 'blues.00010' 'blues.00011' 'blues.00016' 'blues.00025' 'blues.00031' 'blues.00032' 'blues.00033' 'blues.00036' 'blues.00038' 'blues.00042' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (292 differences):*
'blues.00008' 'blues.00009' 'blues.00010' 'blues.00011' 'blues.00025' 'blues.00030' 'blues.00034' 'blues.00038' 'blues.00040' 'blues.00042' 'blues.00044' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (342 differences):*
'blues.00002' 'blues.00005' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00020' 'blues.00022' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [gkiokas2012/default](#gkiokas2012default) (338 differences):*
'blues.00000' 'blues.00002' 'blues.00004' 'blues.00008' 'blues.00017' 'blues.00031' 'blues.00032' 'blues.00033' 'blues.00036' 'blues.00038' 'blues.00041' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (295 differences):*
'blues.00006' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00031' 'blues.00038' 'blues.00040' 'blues.00042' 'blues.00044' 'blues.00045' 'blues.00049' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [oliveira2010/ibt](#oliveira2010ibt) (311 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00037' 'blues.00039' 'blues.00040' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [percival2014/stem](#percival2014stem) (318 differences):*
'blues.00002' 'blues.00003' 'blues.00008' 'blues.00017' 'blues.00029' 'blues.00030' 'blues.00032' 'blues.00036' 'blues.00038' 'blues.00040' 'blues.00044' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (484 differences):*
'blues.00000' 'blues.00004' 'blues.00006' 'blues.00008' 'blues.00011' 'blues.00012' 'blues.00013' 'blues.00014' 'blues.00017' 'blues.00019' 'blues.00020' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2014/default](#schreiber2014default) (315 differences):*
'blues.00001' 'blues.00002' 'blues.00003' 'blues.00005' 'blues.00008' 'blues.00011' 'blues.00017' 'blues.00032' 'blues.00033' 'blues.00035' 'blues.00038' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (337 differences):*
'blues.00006' 'blues.00008' 'blues.00009' 'blues.00010' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00026' 'blues.00032' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (329 differences):*
'blues.00008' 'blues.00009' 'blues.00010' 'blues.00014' 'blues.00015' 'blues.00017' 'blues.00018' 'blues.00021' 'blues.00022' 'blues.00026' 'blues.00032' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/cnn](#schreiber2018cnn) (230 differences):*
'blues.00006' 'blues.00010' 'blues.00011' 'blues.00015' 'blues.00017' 'blues.00022' 'blues.00032' 'blues.00033' 'blues.00038' 'blues.00044' 'blues.00045' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/fcn](#schreiber2018fcn) (246 differences):*
'blues.00001' 'blues.00011' 'blues.00017' 'blues.00033' 'blues.00038' 'blues.00044' 'blues.00045' 'blues.00047' 'blues.00049' 'blues.00077' 'blues.00078' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (226 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00032' 'blues.00033' 'blues.00038' 'blues.00040' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (320 differences):*
'blues.00002' 'blues.00003' 'blues.00006' 'blues.00008' 'blues.00010' 'blues.00011' 'blues.00017' 'blues.00018' 'blues.00035' 'blues.00037' 'blues.00038' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 9 items 'correctly' using Accuracy<sub>1</sub>:__
'classical.00036' 'classical.00080' 'classical.00087' 'country.00007' 'country.00097' 'jazz.00026' 'reggae.00098' 'reggae.00099' 'rock.00065' 
[CSV](data/gtzan_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (58 differences):*
'blues.00023' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00093' 'classical.00032' 'classical.00033' 'classical.00034' 'classical.00036' 'classical.00037' ...
[CSV](data/gtzan_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (114 differences):*
'blues.00006' 'blues.00007' 'blues.00009' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00037' 'blues.00038' 'blues.00040' 'blues.00042' 'blues.00068' ...
[CSV](data/gtzan_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (143 differences):*
'blues.00005' 'blues.00011' 'blues.00022' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00038' ...
[CSV](data/gtzan_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (80 differences):*
'blues.00023' 'blues.00029' 'blues.00036' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00093' 'classical.00003' 'classical.00009' 'classical.00019' 'classical.00027' ...
[CSV](data/gtzan_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (90 differences):*
'blues.00006' 'blues.00011' 'blues.00023' 'blues.00029' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00056' 'blues.00069' 'blues.00072' ...
[CSV](data/gtzan_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (139 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00011' 'blues.00023' 'blues.00025' 'blues.00035' 'blues.00037' 'blues.00038' 'blues.00039' ...
[CSV](data/gtzan_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (72 differences):*
'blues.00023' 'blues.00029' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00036' 'blues.00037' 'blues.00072' 'blues.00093' 'classical.00003' 'classical.00007' ...
[CSV](data/gtzan_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (243 differences):*
'blues.00006' 'blues.00010' 'blues.00011' 'blues.00013' 'blues.00014' 'blues.00017' 'blues.00019' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00032' ...
[CSV](data/gtzan_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (83 differences):*
'blues.00003' 'blues.00023' 'blues.00029' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00056' 'blues.00069' ...
[CSV](data/gtzan_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (73 differences):*
'blues.00023' 'blues.00029' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00069' 'blues.00093' 'blues.00096' ...
[CSV](data/gtzan_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (73 differences):*
'blues.00023' 'blues.00029' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00069' 'blues.00093' 'blues.00096' ...
[CSV](data/gtzan_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (64 differences):*
'blues.00006' 'blues.00023' 'blues.00029' 'blues.00032' 'blues.00037' 'blues.00047' 'blues.00093' 'classical.00007' 'classical.00009' 'classical.00012' 'classical.00015' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (73 differences):*
'blues.00023' 'blues.00029' 'blues.00037' 'blues.00047' 'blues.00093' 'classical.00001' 'classical.00003' 'classical.00007' 'classical.00009' 'classical.00012' 'classical.00015' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (80 differences):*
'blues.00006' 'blues.00011' 'blues.00023' 'blues.00029' 'blues.00031' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00056' 'blues.00093' 'classical.00007' ...
[CSV](data/gtzan_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (122 differences):*
'blues.00011' 'blues.00023' 'blues.00029' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00056' 'blues.00063' ...
[CSV](data/gtzan_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (44 differences):*
'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00093' 'classical.00006' 'classical.00032' 'classical.00033' 'classical.00036' 'classical.00037' 'classical.00041' ...
[CSV](data/gtzan_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (99 differences):*
'blues.00006' 'blues.00007' 'blues.00009' 'blues.00030' 'blues.00037' 'blues.00038' 'blues.00040' 'blues.00042' 'blues.00068' 'blues.00072' 'blues.00089' ...
[CSV](data/gtzan_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (130 differences):*
'blues.00005' 'blues.00011' 'blues.00022' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00038' 'blues.00042' 'blues.00047' ...
[CSV](data/gtzan_estimates_2.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [gkiokas2012/default](#gkiokas2012default) (62 differences):*
'blues.00036' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00093' 'classical.00003' 'classical.00009' 'classical.00031' 'classical.00032' 'classical.00036' 'classical.00037' ...
[CSV](data/gtzan_estimates_2.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (75 differences):*
'blues.00006' 'blues.00011' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00056' 'blues.00069' 'blues.00072' 'blues.00093' 'classical.00003' ...
[CSV](data/gtzan_estimates_2.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [oliveira2010/ibt](#oliveira2010ibt) (130 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00011' 'blues.00025' 'blues.00035' 'blues.00037' 'blues.00038' 'blues.00039' 'blues.00042' ...
[CSV](data/gtzan_estimates_2.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (58 differences):*
'blues.00030' 'blues.00031' 'blues.00032' 'blues.00036' 'blues.00037' 'blues.00072' 'blues.00093' 'classical.00003' 'classical.00006' 'classical.00007' 'classical.00009' ...
[CSV](data/gtzan_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (237 differences):*
'blues.00006' 'blues.00010' 'blues.00011' 'blues.00013' 'blues.00014' 'blues.00017' 'blues.00019' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00032' ...
[CSV](data/gtzan_estimates_2.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (66 differences):*
'blues.00003' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00056' 'blues.00069' 'blues.00072' 'blues.00093' ...
[CSV](data/gtzan_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (58 differences):*
'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00069' 'blues.00093' 'blues.00096' 'classical.00001' 'classical.00006' ...
[CSV](data/gtzan_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (58 differences):*
'blues.00031' 'blues.00032' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00052' 'blues.00069' 'blues.00093' 'blues.00096' 'classical.00001' 'classical.00006' ...
[CSV](data/gtzan_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (49 differences):*
'blues.00006' 'blues.00032' 'blues.00037' 'blues.00047' 'blues.00093' 'classical.00007' 'classical.00009' 'classical.00012' 'classical.00015' 'classical.00023' 'classical.00030' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (62 differences):*
'blues.00037' 'blues.00047' 'blues.00093' 'classical.00001' 'classical.00003' 'classical.00006' 'classical.00007' 'classical.00009' 'classical.00012' 'classical.00015' 'classical.00018' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (67 differences):*
'blues.00006' 'blues.00011' 'blues.00031' 'blues.00037' 'blues.00042' 'blues.00047' 'blues.00056' 'blues.00093' 'classical.00006' 'classical.00007' 'classical.00009' ...
[CSV](data/gtzan_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (108 differences):*
'blues.00011' 'blues.00032' 'blues.00035' 'blues.00037' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00056' 'blues.00063' 'blues.00069' 'blues.00072' ...
[CSV](data/gtzan_estimates_2.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (42 differences):*
'blues.00032' 'blues.00038' 'blues.00042' 'blues.00092' 'blues.00093' 'classical.00009' 'classical.00032' 'classical.00033' 'classical.00034' 'classical.00036' 'classical.00037' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (84 differences):*
'blues.00009' 'blues.00030' 'blues.00040' 'blues.00042' 'blues.00072' 'blues.00089' 'blues.00092' 'blues.00093' 'blues.00099' 'classical.00001' 'classical.00003' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (127 differences):*
'blues.00005' 'blues.00011' 'blues.00022' 'blues.00030' 'blues.00031' 'blues.00032' 'blues.00037' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00056' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [gkiokas2012/default](#gkiokas2012default) (66 differences):*
'blues.00031' 'blues.00036' 'blues.00038' 'blues.00042' 'blues.00073' 'blues.00092' 'blues.00093' 'classical.00003' 'classical.00007' 'classical.00026' 'classical.00027' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (71 differences):*
'blues.00006' 'blues.00011' 'blues.00031' 'blues.00038' 'blues.00042' 'blues.00056' 'blues.00069' 'blues.00072' 'blues.00092' 'classical.00003' 'classical.00006' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [oliveira2010/ibt](#oliveira2010ibt) (125 differences):*
'blues.00001' 'blues.00003' 'blues.00005' 'blues.00006' 'blues.00011' 'blues.00037' 'blues.00039' 'blues.00042' 'blues.00044' 'blues.00069' 'blues.00072' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [percival2014/stem](#percival2014stem) (56 differences):*
'blues.00030' 'blues.00032' 'blues.00036' 'blues.00038' 'blues.00072' 'blues.00092' 'blues.00093' 'classical.00003' 'classical.00009' 'classical.00015' 'classical.00027' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (231 differences):*
'blues.00006' 'blues.00011' 'blues.00012' 'blues.00013' 'blues.00014' 'blues.00019' 'blues.00023' 'blues.00029' 'blues.00030' 'blues.00032' 'blues.00034' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2014/default](#schreiber2014default) (63 differences):*
'blues.00003' 'blues.00032' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00056' 'blues.00069' 'blues.00072' 'blues.00092' 'classical.00023' 'classical.00031' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (62 differences):*
'blues.00032' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00069' 'blues.00092' 'blues.00096' 'classical.00001' 'classical.00012' 'classical.00021' 'classical.00023' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (61 differences):*
'blues.00032' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00069' 'blues.00096' 'classical.00001' 'classical.00012' 'classical.00021' 'classical.00023' 'classical.00026' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/cnn](#schreiber2018cnn) (51 differences):*
'blues.00006' 'blues.00032' 'blues.00038' 'blues.00092' 'classical.00001' 'classical.00009' 'classical.00015' 'classical.00021' 'classical.00023' 'classical.00030' 'classical.00032' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/fcn](#schreiber2018fcn) (46 differences):*
'blues.00038' 'blues.00092' 'blues.00093' 'classical.00003' 'classical.00009' 'classical.00015' 'classical.00018' 'classical.00032' 'classical.00033' 'classical.00034' 'classical.00036' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (66 differences):*
'blues.00011' 'blues.00032' 'blues.00038' 'blues.00042' 'blues.00056' 'blues.00073' 'blues.00092' 'classical.00001' 'classical.00009' 'classical.00027' 'classical.00030' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (110 differences):*
'blues.00011' 'blues.00035' 'blues.00038' 'blues.00042' 'blues.00052' 'blues.00056' 'blues.00063' 'blues.00069' 'blues.00072' 'blues.00092' 'blues.00093' ...
[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4188   |   0.0546   |   0.6158   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0014__ | __0.0070__ |   0.8681   |   0.1158   |   0.0948   | __0.0000__ |   0.1649   | __0.0029__ | __0.0159__ | __0.0000__ | __0.0033__ | __0.0000__ | __0.0489__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0014__ |   1.0000   |   0.8352   | __0.0011__ | __0.0455__ |   0.1056   | __0.0000__ |   0.0599   |   0.7820   |   0.4087   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1454   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0070__ |   0.8352   |   1.0000   | __0.0045__ |   0.1089   |   0.1636   | __0.0000__ |   0.1058   |   1.0000   |   0.5836   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2517   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ |   0.8681   | __0.0011__ | __0.0045__ |   1.0000   |   0.1745   |   0.0564   | __0.0000__ |   0.1331   | __0.0021__ | __0.0144__ | __0.0000__ | __0.0007__ | __0.0000__ | __0.0360__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.1158   | __0.0455__ |   0.1089   |   0.1745   |   1.0000   |   0.6824   | __0.0000__ |   0.8458   |   0.0697   |   0.2385   | __0.0000__ | __0.0001__ | __0.0000__ |   0.5150   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0948   |   0.1056   |   0.1636   |   0.0564   |   0.6824   |   1.0000   | __0.0000__ |   0.8613   |   0.1951   |   0.4739   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9349   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.1649   |   0.0599   |   0.1058   |   0.1331   |   0.8458   |   0.8613   | __0.0000__ |   1.0000   |   0.1093   |   0.3100   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7610   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0029__ |   0.7820   |   1.0000   | __0.0021__ |   0.0697   |   0.1951   | __0.0000__ |   0.1093   |   1.0000   |   0.1338   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2470   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0159__ |   0.4087   |   0.5836   | __0.0144__ |   0.2385   |   0.4739   | __0.0000__ |   0.3100   |   0.1338   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.5726   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4188   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2081   |   0.7984   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0546   | __0.0033__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2081   |   1.0000   |   0.1306   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6158   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7984   |   0.1306   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0489__ |   0.1454   |   0.2517   | __0.0360__ |   0.5150   |   0.9349   | __0.0000__ |   0.7610   |   0.2470   |   0.5726   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.0885   |   0.5458   |   0.8855   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5922   |   0.3419   |   0.4795   |   0.1613   |   0.0898   |   0.2101   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4595   | __0.0000__ |   0.0518   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.0885   | __0.0000__ |   1.0000   | __0.0145__ |   0.0935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0194__ | __0.0062__ | __0.0184__ | __0.0025__ |   0.7372   |   0.5836   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.5458   | __0.0000__ | __0.0145__ |   1.0000   |   0.4109   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.7869   |   0.9470   |   0.5422   | __0.0465__ |   0.0700   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.8855   | __0.0000__ |   0.0935   |   0.4109   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4123   |   0.2126   |   0.3950   |   0.1170   |   0.1537   |   0.2248   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.4595   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0165__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.6029   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.0518   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0165__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6029   | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0001__ | __0.0006__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5922   | __0.0000__ | __0.0194__ |   1.0000   |   0.4123   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2863   |   1.0000   |   0.5050   | __0.0393__ |   0.0653   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3419   | __0.0000__ | __0.0062__ |   0.7869   |   0.2126   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.2863   |   1.0000   |   0.7768   |   0.7879   | __0.0124__ | __0.0276__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4795   | __0.0000__ | __0.0184__ |   0.9470   |   0.3950   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.7768   |   1.0000   |   0.4564   | __0.0109__ |   0.0575   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1613   | __0.0000__ | __0.0025__ |   0.5422   |   0.1170   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0006__ |   0.5050   |   0.7879   |   0.4564   |   1.0000   | __0.0014__ | __0.0107__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0898   | __0.0000__ |   0.7372   | __0.0465__ |   0.1537   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0393__ | __0.0124__ | __0.0109__ | __0.0014__ |   1.0000   |   0.8784   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2101   | __0.0000__ |   0.5836   |   0.0700   |   0.2248   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0653   | __0.0276__ |   0.0575   | __0.0107__ |   0.8784   |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1442   |   0.4153   |   0.8843   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5031   |   0.2217   |   0.5258   |   0.1020   |   0.1213   |   0.3352   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2234   | __0.0000__ |   0.0937   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1442   | __0.0000__ |   1.0000   | __0.0157__ |   0.1636   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0254__ | __0.0057__ | __0.0383__ | __0.0029__ |   0.8397   |   0.5818   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4153   | __0.0000__ | __0.0157__ |   1.0000   |   0.2960   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.9460   |   0.7325   |   0.8397   |   0.5365   | __0.0358__ |   0.0789   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.8843   | __0.0000__ |   0.1636   |   0.2960   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3271   |   0.1196   |   0.4224   |   0.0727   |   0.2016   |   0.3823   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.2234   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0155__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.4778   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.0937   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0155__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.4778   | __0.0000__ |   1.0000   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0012__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5031   | __0.0000__ | __0.0254__ |   0.9460   |   0.3271   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1338   |   0.9428   |   0.4603   | __0.0373__ |   0.0873   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2217   | __0.0000__ | __0.0057__ |   0.7325   |   0.1196   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0002__ |   0.1338   |   1.0000   |   0.5182   |   0.8397   | __0.0079__ | __0.0269__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5258   | __0.0000__ | __0.0383__ |   0.8397   |   0.4224   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9428   |   0.5182   |   1.0000   |   0.2685   | __0.0188__ |   0.1133   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1020   | __0.0000__ | __0.0029__ |   0.5365   |   0.0727   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0012__ |   0.4603   |   0.8397   |   0.2685   |   1.0000   | __0.0010__ | __0.0119__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1213   | __0.0000__ |   0.8397   | __0.0358__ |   0.2016   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0373__ | __0.0079__ | __0.0188__ | __0.0010__ |   1.0000   |   0.7555   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3352   | __0.0000__ |   0.5818   |   0.0789   |   0.3823   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0873   | __0.0269__ |   0.1133   | __0.0119__ |   0.7555   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0005__ | __0.0004__ | __0.0000__ | __0.0436__ | __0.0000__ | __0.0038__ | __0.0105__ | __0.0163__ |   0.1628   |   0.6177   | __0.0005__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0001__ |   0.0605   |   0.1659   | __0.0001__ | __0.0008__ | __0.0000__ | __0.0320__ | __0.0204__ | __0.0157__ | __0.0001__ | __0.0000__ | __0.0451__ | __0.0124__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ |   0.9279   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1288   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0005__ |   0.0605   | __0.0000__ |   1.0000   |   0.6350   | __0.0000__ |   0.2288   | __0.0000__ |   0.7946   |   0.7077   |   0.6198   |   0.0581   | __0.0078__ |   0.9005   | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0004__ |   0.1659   | __0.0000__ |   0.6350   |   1.0000   | __0.0000__ |   0.0722   | __0.0000__ |   0.3816   |   0.3355   |   0.2821   | __0.0135__ | __0.0010__ |   0.6143   | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0001__ |   0.9279   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1719   |
| [percival2014/stem](#percival2014stem)             | __0.0436__ | __0.0008__ | __0.0000__ |   0.2288   |   0.0722   | __0.0000__ |   1.0000   | __0.0000__ |   0.4101   |   0.5186   |   0.6085   |   0.5224   |   0.2026   |   0.2116   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0038__ | __0.0320__ | __0.0000__ |   0.7946   |   0.3816   | __0.0000__ |   0.4101   | __0.0000__ |   1.0000   |   1.0000   |   0.8642   |   0.1114   | __0.0331__ |   0.7838   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0105__ | __0.0204__ | __0.0000__ |   0.7077   |   0.3355   | __0.0000__ |   0.5186   | __0.0000__ |   1.0000   |   1.0000   |   1.0000   |   0.1263   | __0.0365__ |   0.6778   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0163__ | __0.0157__ | __0.0000__ |   0.6198   |   0.2821   | __0.0000__ |   0.6085   | __0.0000__ |   0.8642   |   1.0000   |   1.0000   |   0.1742   |   0.0534   |   0.5831   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1628   | __0.0001__ | __0.0000__ |   0.0581   | __0.0135__ | __0.0000__ |   0.5224   | __0.0000__ |   0.1114   |   0.1263   |   0.1742   |   1.0000   |   0.4869   | __0.0167__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6177   | __0.0000__ | __0.0000__ | __0.0078__ | __0.0010__ | __0.0000__ |   0.2026   | __0.0000__ | __0.0331__ | __0.0365__ |   0.0534   |   0.4869   |   1.0000   | __0.0037__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0005__ | __0.0451__ | __0.0000__ |   0.9005   |   0.6143   | __0.0000__ |   0.2116   | __0.0000__ |   0.7838   |   0.6778   |   0.5831   | __0.0167__ | __0.0037__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0124__ |   0.1288   | __0.0000__ | __0.0000__ |   0.1719   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table9"></a>Table 9: McNemar p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0114__ | __0.0004__ | __0.0000__ |   0.0541   | __0.0000__ | __0.0026__ |   0.0649   |   0.0649   |   0.5515   | __0.0175__ | __0.0027__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0121__ | __0.0003__ | __0.0153__ | __0.0060__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0017__ |   0.4812   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0121__ |   1.0000   | __0.0000__ | __0.0000__ |   0.9279   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0532   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0114__ | __0.0003__ | __0.0000__ |   1.0000   |   0.1931   | __0.0000__ |   0.6936   | __0.0000__ |   0.7032   |   0.7077   |   0.7077   |   0.0984   |   0.8937   |   0.6198   | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0004__ | __0.0153__ | __0.0000__ |   0.1931   |   1.0000   | __0.0000__ | __0.0363__ | __0.0000__ |   0.3284   | __0.0498__ | __0.0498__ | __0.0019__ |   0.1299   |   0.3816   | __0.0007__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0060__ |   0.9279   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0433__ |
| [percival2014/stem](#percival2014stem)             |   0.0541   | __0.0000__ | __0.0000__ |   0.6936   | __0.0363__ | __0.0000__ |   1.0000   | __0.0000__ |   0.3409   |   0.8937   |   0.8937   |   0.2221   |   0.6778   |   0.2806   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0026__ | __0.0020__ | __0.0000__ |   0.7032   |   0.3284   | __0.0000__ |   0.3409   | __0.0000__ |   1.0000   |   0.1849   |   0.1849   | __0.0213__ |   0.6985   |   1.0000   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0649   | __0.0000__ | __0.0000__ |   0.7077   | __0.0498__ | __0.0000__ |   0.8937   | __0.0000__ |   0.1849   |   1.0000   |   1.0000   |   0.2529   |   0.6778   |   0.2624   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0649   | __0.0000__ | __0.0000__ |   0.7077   | __0.0498__ | __0.0000__ |   0.8937   | __0.0000__ |   0.1849   |   1.0000   |   1.0000   |   0.2529   |   0.6778   |   0.2624   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5515   | __0.0000__ | __0.0000__ |   0.0984   | __0.0019__ | __0.0000__ |   0.2221   | __0.0000__ | __0.0213__ |   0.2529   |   0.2529   |   1.0000   |   0.0725   | __0.0096__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0175__ | __0.0002__ | __0.0000__ |   0.8937   |   0.1299   | __0.0000__ |   0.6778   | __0.0000__ |   0.6985   |   0.6778   |   0.6778   |   0.0725   |   1.0000   |   0.5831   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0027__ | __0.0017__ | __0.0000__ |   0.6198   |   0.3816   | __0.0000__ |   0.2806   | __0.0000__ |   1.0000   |   0.2624   |   0.2624   | __0.0096__ |   0.5831   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.4812   |   0.0532   | __0.0000__ | __0.0007__ | __0.0433__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table10"></a>Table 10: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0016__ | __0.0003__ | __0.0000__ |   0.0595   | __0.0000__ | __0.0005__ | __0.0444__ | __0.0444__ |   0.4514   |   0.0534   | __0.0038__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0184__ | __0.0007__ | __0.0142__ | __0.0265__ | __0.0000__ | __0.0000__ | __0.0034__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ |   0.5228   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0184__ |   1.0000   | __0.0000__ | __0.0000__ |   0.7842   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0622   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0016__ | __0.0007__ | __0.0000__ |   1.0000   |   0.3019   | __0.0000__ |   0.3409   | __0.0000__ |   0.7946   |   0.4424   |   0.4424   | __0.0365__ |   0.4270   |   0.8937   | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0003__ | __0.0142__ | __0.0000__ |   0.3019   |   1.0000   | __0.0000__ | __0.0222__ | __0.0000__ |   0.4424   | __0.0430__ | __0.0430__ | __0.0011__ | __0.0430__ |   0.2370   | __0.0007__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0265__ |   0.7842   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1219   |
| [percival2014/stem](#percival2014stem)             |   0.0595   | __0.0000__ | __0.0000__ |   0.3409   | __0.0222__ | __0.0000__ |   1.0000   | __0.0000__ |   0.1608   |   1.0000   |   1.0000   |   0.2800   |   1.0000   |   0.3020   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0005__ | __0.0034__ | __0.0000__ |   0.7946   |   0.4424   | __0.0000__ |   0.1608   | __0.0000__ |   1.0000   |   0.0872   |   0.0872   | __0.0079__ |   0.2288   |   0.7754   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0444__ | __0.0000__ | __0.0000__ |   0.4424   | __0.0430__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0872   |   1.0000   |   1.0000   |   0.2327   |   1.0000   |   0.4011   | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0444__ | __0.0000__ | __0.0000__ |   0.4424   | __0.0430__ | __0.0000__ |   1.0000   | __0.0000__ |   0.0872   |   1.0000   |   1.0000   |   0.2327   |   1.0000   |   0.4011   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4514   | __0.0000__ | __0.0000__ | __0.0365__ | __0.0011__ | __0.0000__ |   0.2800   | __0.0000__ | __0.0079__ |   0.2327   |   0.2327   |   1.0000   |   0.2110   | __0.0195__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0534   | __0.0000__ | __0.0000__ |   0.4270   | __0.0430__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2288   |   1.0000   |   1.0000   |   0.2110   |   1.0000   |   0.3916   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0038__ | __0.0008__ | __0.0000__ |   0.8937   |   0.2370   | __0.0000__ |   0.3020   | __0.0000__ |   0.7754   |   0.4011   |   0.4011   | __0.0195__ |   0.3916   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.5228   |   0.0622   | __0.0000__ | __0.0007__ |   0.1219   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table11"></a>Table 11: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>1</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>2</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean Accuracy<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Accuracy<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure24"></a>Figure 24: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure25"></a>Figure 25: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.svg">
</figure>

<a name="figure26"></a>Figure 26: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure27"></a>Figure 27: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure28"></a>Figure 28: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.svg">
</figure>

<a name="figure29"></a>Figure 29: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean Accuracy<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean Accuracy<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure37"></a>Figure 37: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg">
</figure>

<a name="figure38"></a>Figure 38: Mean Accuracy<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.svg">
</figure>

<a name="figure39"></a>Figure 39: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.svg">
</figure>

<a name="figure40"></a>Figure 40: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg">
</figure>

<a name="figure41"></a>Figure 41: Mean Accuracy<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[CSV](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             |   0.1399   | __0.4119__ |   -0.0008   |   0.0728   |
| [schreiber2014/default](#schreiber2014default)     |   0.1258   |   0.4130   |   -0.0107   |   0.0895   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2068   |   0.4507   |   -0.0047   |   0.0698   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2473   |   0.4514   |   -0.0043   |   0.0741   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1468   |   0.4524   |   -0.0091   |   0.1115   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2610   |   0.4597   |   -0.0076   |   0.0840   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2691   |   0.4657   |   -0.0050   |   0.0900   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2372   |   0.4738   |   -0.0119   |   0.1109   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3338   |   0.4843   |   -0.0121   |   0.1021   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1870   |   0.4878   |   -0.0032   |   0.0863   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2759   |   0.4898   | __0.0006__ | __0.0684__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.1212__ |   0.4921   |   -0.0051   |   0.0715   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1522   |   0.4978   |   -0.0057   |   0.0700   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3979   |   0.5083   |   0.0173   |   0.0769   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.1383   |   0.5280   |   0.0207   |   0.1605   |

<a name="table12"></a>Table 12: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/gtzan_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/gtzan_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/gtzan_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure43"></a>Figure 43: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             |   0.1292   | __0.4110__ | __0.0003__ |   0.0739   |
| [schreiber2014/default](#schreiber2014default)     |   0.1141   |   0.4122   |   -0.0126   |   0.0860   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1951   |   0.4506   |   -0.0056   |   0.0699   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2356   |   0.4528   |   -0.0041   |   0.0743   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2500   |   0.4543   |   -0.0077   |   0.0832   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1366   |   0.4605   |   -0.0095   |   0.1093   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2573   |   0.4676   |   -0.0064   |   0.0871   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2256   |   0.4685   |   -0.0120   |   0.1105   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3223   |   0.4827   |   -0.0118   |   0.1023   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2643   |   0.4878   |   -0.0007   | __0.0612__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1758   |   0.4884   |   -0.0028   |   0.0819   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1405   |   0.4933   |   -0.0064   |   0.0683   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.1095__ |   0.4934   |   -0.0064   |   0.0683   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3867   |   0.5042   |   0.0169   |   0.0741   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.1263   |   0.5228   |   0.0241   |   0.1601   |

<a name="table13"></a>Table 13: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/gtzan_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/gtzan_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/gtzan_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure44"></a>Figure 44: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure45"></a>Figure 45: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0491   | __0.4310__ |   -0.0057   |   0.0923   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0709   |   0.4514   |   -0.0020   |   0.0768   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.1115   |   0.4610   |   0.0020   | __0.0687__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0423   |   0.4660   |   0.0018   |   0.0688   |
| [schreiber2014/default](#schreiber2014default)     |   -0.1924   |   0.4904   |   -0.0084   |   0.0833   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   -0.1707   |   0.4999   |   -0.0038   |   0.1113   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0156__ |   0.5026   |   -0.0103   |   0.0972   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   -0.0572   |   0.5082   |   -0.0042   |   0.0818   |
| [percival2014/stem](#percival2014stem)             |   -0.1783   |   0.5137   | __-0.0001__ |   0.0733   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   -0.0810   |   0.5192   |   -0.0089   |   0.1099   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0797   |   0.5222   |   0.0194   |   0.0742   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1970   |   0.5332   |   -0.0051   |   0.0842   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1660   |   0.5470   |   -0.0038   |   0.0863   |
| [gkiokas2012/default](#gkiokas2012default)         |   -0.1313   |   0.5600   |   0.0010   |   0.0821   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   -0.1766   |   0.5890   |   0.0228   |   0.1566   |

<a name="table14"></a>Table 14: Mean OE1/OE2 for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) ordered by standard deviation.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_moe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_moe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_moe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.svg">
</figure>

<a name="figure46"></a>Figure 46: OE<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.svg">
</figure>

<a name="figure47"></a>Figure 47: OE<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2873   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0256__ | __0.0000__ |   0.5785   | __0.0049__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0072__ | __0.0000__ | __0.0000__ |   0.6144   |   0.6945   |   0.0926   |   0.7059   |   0.0793   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0072__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0051__ | __0.0000__ | __0.0314__ | __0.0001__ | __0.0001__ |   0.2040   | __0.0000__ | __0.0005__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2873   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3244   | __0.0001__ |   0.4935   | __0.0241__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.6144   | __0.0006__ | __0.0000__ | __0.0000__ |   1.0000   |   0.9737   |   0.1875   |   0.3920   |   0.2008   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.6945   | __0.0051__ | __0.0000__ | __0.0000__ |   0.9737   |   1.0000   |   0.3727   |   0.5869   |   0.2127   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.0926   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1875   |   0.3727   |   1.0000   |   0.0572   |   0.7351   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.7059   | __0.0314__ | __0.0000__ | __0.0000__ |   0.3920   |   0.5869   |   0.0572   |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0793   | __0.0001__ | __0.0000__ | __0.0000__ |   0.2008   |   0.2127   |   0.7351   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0256__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.3244   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0007__ |   0.0569   |   0.4600   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2040   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0007__ |   1.0000   | __0.0000__ | __0.0352__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5785   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0569   | __0.0000__ |   1.0000   | __0.0113__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0049__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0241__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4600   | __0.0352__ | __0.0113__ |   1.0000   |

<a name="table15"></a>Table 15: Paired t-test p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3064   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0252__ | __0.0000__ |   0.5706   | __0.0049__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0085__ | __0.0000__ | __0.0000__ |   0.5867   |   0.6238   |   0.0688   |   0.7827   |   0.0614   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0085__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0045__ | __0.0000__ | __0.0285__ | __0.0001__ | __0.0001__ |   0.2172   | __0.0000__ | __0.0006__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3064   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3007   | __0.0001__ |   0.5328   | __0.0206__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.5867   | __0.0006__ | __0.0000__ | __0.0000__ |   1.0000   |   0.9174   |   0.1562   |   0.4305   |   0.1767   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.6238   | __0.0045__ | __0.0000__ | __0.0000__ |   0.9174   |   1.0000   |   0.3731   |   0.5864   |   0.2129   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.0688   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1562   |   0.3731   |   1.0000   |   0.0572   |   0.7351   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.7827   | __0.0285__ | __0.0000__ | __0.0000__ |   0.4305   |   0.5864   |   0.0572   |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0614   | __0.0001__ | __0.0000__ | __0.0000__ |   0.1767   |   0.2129   |   0.7351   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0252__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.3007   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0008__ |   0.0577   |   0.4637   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0001__ |   0.2172   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0008__ |   1.0000   | __0.0000__ | __0.0352__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5706   | __0.0000__ | __0.0000__ | __0.0000__ |   0.5328   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0577   | __0.0000__ |   1.0000   | __0.0117__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0049__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0206__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4637   | __0.0352__ | __0.0117__ |   1.0000   |

<a name="table16"></a>Table 16: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2873   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0256__ | __0.0000__ |   0.5785   | __0.0049__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   1.0000   | __0.0072__ | __0.0000__ | __0.0000__ |   0.6144   |   0.6945   |   0.0926   |   0.7059   |   0.0793   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0072__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0051__ | __0.0000__ | __0.0314__ | __0.0001__ | __0.0001__ |   0.2040   | __0.0000__ | __0.0005__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2873   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3244   | __0.0001__ |   0.4935   | __0.0241__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   0.6144   | __0.0006__ | __0.0000__ | __0.0000__ |   1.0000   |   0.9737   |   0.1875   |   0.3920   |   0.2008   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ |   0.6945   | __0.0051__ | __0.0000__ | __0.0000__ |   0.9737   |   1.0000   |   0.3727   |   0.5869   |   0.2127   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.0926   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1875   |   0.3727   |   1.0000   |   0.0572   |   0.7351   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.7059   | __0.0314__ | __0.0000__ | __0.0000__ |   0.3920   |   0.5869   |   0.0572   |   1.0000   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0793   | __0.0001__ | __0.0000__ | __0.0000__ |   0.2008   |   0.2127   |   0.7351   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0256__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.3244   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0007__ |   0.0569   |   0.4600   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.2040   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0007__ |   1.0000   | __0.0000__ | __0.0352__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5785   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4935   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0569   | __0.0000__ |   1.0000   | __0.0113__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0049__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0241__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4600   | __0.0352__ | __0.0113__ |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1358   |   0.7734   | __0.0404__ | __0.0008__ |   0.4625   | __0.0001__ | __0.0004__ |   0.0791   | __0.0299__ |   0.1959   |   0.9519   | __0.0278__ | __0.0030__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4763   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1358   | __0.0000__ |   1.0000   |   0.2531   |   0.9281   |   0.1340   |   0.3380   | __0.0000__ |   0.2323   |   0.9985   |   0.7578   |   0.6773   |   0.1297   |   0.6677   |   0.2580   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.7734   | __0.0000__ |   0.2531   |   1.0000   |   0.1426   | __0.0054__ |   0.7139   | __0.0001__ | __0.0025__ |   0.1292   |   0.0579   |   0.3739   |   0.7607   |   0.0691   | __0.0185__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0404__ | __0.0000__ |   0.9281   |   0.1426   |   1.0000   |   0.0821   |   0.1971   | __0.0000__ |   0.1878   |   0.9168   |   0.7846   |   0.5288   | __0.0376__ |   0.6927   |   0.2145   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0008__ | __0.0000__ |   0.1340   | __0.0054__ |   0.0821   |   1.0000   | __0.0056__ | __0.0000__ |   0.5802   |   0.0921   |   0.1665   | __0.0365__ | __0.0009__ |   0.2492   |   0.7377   |
| [percival2014/stem](#percival2014stem)             |   0.4625   | __0.0000__ |   0.3380   |   0.7139   |   0.1971   | __0.0056__ |   1.0000   | __0.0000__ | __0.0048__ |   0.2285   |   0.1069   |   0.5325   |   0.4651   |   0.0701   | __0.0191__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0001__ |   0.4763   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0004__ | __0.0000__ |   0.2323   | __0.0025__ |   0.1878   |   0.5802   | __0.0048__ | __0.0000__ |   1.0000   |   0.0887   |   0.2099   |   0.0500   | __0.0023__ |   0.4452   |   0.8752   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0791   | __0.0000__ |   0.9985   |   0.1292   |   0.9168   |   0.0921   |   0.2285   | __0.0000__ |   0.0887   |   1.0000   |   0.0833   |   0.5174   |   0.0738   |   0.6331   |   0.1825   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0299__ | __0.0000__ |   0.7578   |   0.0579   |   0.7846   |   0.1665   |   0.1069   | __0.0000__ |   0.2099   |   0.0833   |   1.0000   |   0.2751   | __0.0280__ |   0.8765   |   0.3153   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1959   | __0.0000__ |   0.6773   |   0.3739   |   0.5288   | __0.0365__ |   0.5325   | __0.0000__ |   0.0500   |   0.5174   |   0.2751   |   1.0000   |   0.1533   |   0.3139   |   0.0827   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9519   | __0.0000__ |   0.1297   |   0.7607   | __0.0376__ | __0.0009__ |   0.4651   | __0.0001__ | __0.0023__ |   0.0738   | __0.0280__ |   0.1533   |   1.0000   | __0.0224__ | __0.0039__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0278__ | __0.0000__ |   0.6677   |   0.0691   |   0.6927   |   0.2492   |   0.0701   | __0.0000__ |   0.4452   |   0.6331   |   0.8765   |   0.3139   | __0.0224__ |   1.0000   |   0.4395   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0030__ | __0.0000__ |   0.2580   | __0.0185__ |   0.2145   |   0.7377   | __0.0191__ | __0.0000__ |   0.8752   |   0.1825   |   0.3153   |   0.0827   | __0.0039__ |   0.4395   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0130__ |   0.4492   | __0.0159__ | __0.0020__ |   0.7020   | __0.0000__ | __0.0001__ | __0.0449__ | __0.0449__ |   0.2252   |   0.0711   |   0.0710   | __0.0013__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1828   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0130__ | __0.0000__ |   1.0000   |   0.1194   |   0.6542   |   0.5822   | __0.0106__ | __0.0000__ |   0.4033   |   0.4026   |   0.4026   |   0.2012   |   0.3398   |   0.4587   |   0.5699   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4492   | __0.0000__ |   0.1194   |   1.0000   |   0.1551   | __0.0218__ |   0.3253   | __0.0000__ | __0.0026__ |   0.2190   |   0.2190   |   0.6842   |   0.3591   |   0.3375   | __0.0228__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0159__ | __0.0000__ |   0.6542   |   0.1551   |   1.0000   |   0.2359   | __0.0130__ | __0.0000__ |   0.1241   |   0.6453   |   0.6453   |   0.2815   |   0.4989   |   0.7058   |   0.2584   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0020__ | __0.0000__ |   0.5822   | __0.0218__ |   0.2359   |   1.0000   | __0.0011__ | __0.0000__ |   0.8343   |   0.1225   |   0.1225   |   0.0504   |   0.1036   |   0.1881   |   0.9582   |
| [percival2014/stem](#percival2014stem)             |   0.7020   | __0.0000__ | __0.0106__ |   0.3253   | __0.0130__ | __0.0011__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0198__ | __0.0198__ |   0.1800   |   0.0612   | __0.0297__ | __0.0021__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.1828   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0001__ | __0.0000__ |   0.4033   | __0.0026__ |   0.1241   |   0.8343   | __0.0000__ | __0.0000__ |   1.0000   | __0.0040__ | __0.0040__ | __0.0069__ | __0.0284__ |   0.0617   |   0.8777   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0449__ | __0.0000__ |   0.4026   |   0.2190   |   0.6453   |   0.1225   | __0.0198__ | __0.0000__ | __0.0040__ |   1.0000   |   0.1879   |   0.4014   |   0.7716   |   0.9995   |   0.1154   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0449__ | __0.0000__ |   0.4026   |   0.2190   |   0.6453   |   0.1225   | __0.0198__ | __0.0000__ | __0.0040__ |   0.1879   |   1.0000   |   0.4014   |   0.7716   |   0.9995   |   0.1154   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2252   | __0.0000__ |   0.2012   |   0.6842   |   0.2815   |   0.0504   |   0.1800   | __0.0000__ | __0.0069__ |   0.4014   |   0.4014   |   1.0000   |   0.5346   |   0.5189   | __0.0373__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0711   | __0.0000__ |   0.3398   |   0.3591   |   0.4989   |   0.1036   |   0.0612   | __0.0000__ | __0.0284__ |   0.7716   |   0.7716   |   0.5346   |   1.0000   |   0.8162   |   0.1064   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0710   | __0.0000__ |   0.4587   |   0.3375   |   0.7058   |   0.1881   | __0.0297__ | __0.0000__ |   0.0617   |   0.9995   |   0.9995   |   0.5189   |   0.8162   |   1.0000   |   0.1756   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0013__ | __0.0000__ |   0.5699   | __0.0228__ |   0.2584   |   0.9582   | __0.0021__ | __0.0000__ |   0.8777   |   0.1154   |   0.1154   | __0.0373__ |   0.1064   |   0.1756   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0102__ |   0.1745   | __0.0072__ | __0.0005__ |   0.6177   | __0.0001__ | __0.0003__ | __0.0302__ | __0.0446__ |   0.0889   | __0.0494__ |   0.0931   | __0.0004__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5136   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0102__ | __0.0000__ |   1.0000   |   0.1779   |   0.7085   |   0.4875   | __0.0319__ | __0.0000__ |   0.6645   |   0.3584   |   0.2765   |   0.2533   |   0.2849   |   0.3126   |   0.5444   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1745   | __0.0000__ |   0.1779   |   1.0000   |   0.1974   | __0.0253__ |   0.4716   | __0.0000__ | __0.0284__ |   0.4295   |   0.5405   |   0.7416   |   0.6388   |   0.6666   | __0.0310__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0072__ | __0.0000__ |   0.7085   |   0.1974   |   1.0000   |   0.1883   | __0.0451__ | __0.0000__ |   0.3512   |   0.5201   |   0.4116   |   0.3435   |   0.3586   |   0.4595   |   0.2688   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0005__ | __0.0000__ |   0.4875   | __0.0253__ |   0.1883   |   1.0000   | __0.0024__ | __0.0000__ |   0.7137   |   0.0610   | __0.0421__ | __0.0478__ | __0.0474__ |   0.0884   |   0.9616   |
| [percival2014/stem](#percival2014stem)             |   0.6177   | __0.0000__ | __0.0319__ |   0.4716   | __0.0451__ | __0.0024__ |   1.0000   | __0.0001__ | __0.0011__ |   0.0858   |   0.1228   |   0.2775   |   0.1931   |   0.1841   | __0.0062__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0001__ |   0.5136   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0003__ | __0.0000__ |   0.6645   | __0.0284__ |   0.3512   |   0.7137   | __0.0011__ | __0.0000__ |   1.0000   | __0.0293__ | __0.0119__ | __0.0496__ |   0.0619   |   0.0911   |   0.7573   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0302__ | __0.0000__ |   0.3584   |   0.4295   |   0.5201   |   0.0610   |   0.0858   | __0.0000__ | __0.0293__ |   1.0000   |   0.3176   |   0.6342   |   0.7216   |   0.8184   |   0.0798   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0446__ | __0.0000__ |   0.2765   |   0.5405   |   0.4116   | __0.0421__ |   0.1228   | __0.0000__ | __0.0119__ |   0.3176   |   1.0000   |   0.7824   |   0.8932   |   0.9637   |   0.0585   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0889   | __0.0000__ |   0.2533   |   0.7416   |   0.3435   | __0.0478__ |   0.2775   | __0.0000__ | __0.0496__ |   0.6342   |   0.7824   |   1.0000   |   0.8652   |   0.8607   |   0.0508   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0494__ | __0.0000__ |   0.2849   |   0.6388   |   0.3586   | __0.0474__ |   0.1931   | __0.0000__ |   0.0619   |   0.7216   |   0.8932   |   0.8652   |   1.0000   |   0.9519   |   0.0664   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0931   | __0.0000__ |   0.3126   |   0.6666   |   0.4595   |   0.0884   |   0.1841   | __0.0000__ |   0.0911   |   0.8184   |   0.9637   |   0.8607   |   0.9519   |   1.0000   |   0.1055   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0004__ | __0.0000__ |   0.5444   | __0.0310__ |   0.2688   |   0.9616   | __0.0062__ | __0.0000__ |   0.7573   |   0.0798   |   0.0585   |   0.0508   |   0.0664   |   0.1055   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg">
</figure>

<a name="figure48"></a>Figure 48: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean OE<sub>1</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg">
</figure>

<a name="figure53"></a>Figure 53: Mean OE<sub>2</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure54"></a>Figure 54: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure55"></a>Figure 55: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.svg">
</figure>

<a name="figure56"></a>Figure 56: Mean OE<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure57"></a>Figure 57: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure58"></a>Figure 58: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.svg">
</figure>

<a name="figure59"></a>Figure 59: Mean OE<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure60"></a>Figure 60: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure61"></a>Figure 61: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.svg">
</figure>

<a name="figure62"></a>Figure 62: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure63"></a>Figure 63: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure64"></a>Figure 64: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.svg">
</figure>

<a name="figure65"></a>Figure 65: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe1.svg">
</figure>

<a name="figure66"></a>Figure 66: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe1.svg">
</figure>

<a name="figure67"></a>Figure 67: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.svg">
</figure>

<a name="figure68"></a>Figure 68: OE<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.png "Open Figure") 

### OE<sub>1</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe1.svg">
</figure>

<a name="figure69"></a>Figure 69: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe1.svg">
</figure>

<a name="figure70"></a>Figure 70: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.svg">
</figure>

<a name="figure71"></a>Figure 71: OE<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe2.svg">
</figure>

<a name="figure72"></a>Figure 72: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe2.svg">
</figure>

<a name="figure73"></a>Figure 73: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.svg">
</figure>

<a name="figure74"></a>Figure 74: OE<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.png "Open Figure") 

### OE<sub>2</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe2.svg">
</figure>

<a name="figure75"></a>Figure 75: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe2.svg">
</figure>

<a name="figure76"></a>Figure 76: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.svg">
</figure>

<a name="figure77"></a>Figure 77: OE<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.2030__ |   0.3847   |   0.0255   |   0.0682   |
| [schreiber2014/default](#schreiber2014default)     |   0.2055   | __0.3797__ |   0.0317   |   0.0844   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2534   |   0.4262   | __0.0238__ |   0.0658   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2541   |   0.4021   |   0.0461   |   0.1019   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2643   |   0.4324   |   0.0250   |   0.0672   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2733   |   0.4362   |   0.0241   |   0.0702   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2754   |   0.4439   |   0.0297   |   0.0811   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2768   |   0.4409   |   0.0247   |   0.0658   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2877   |   0.4449   |   0.0440   |   0.1025   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2878   |   0.4435   |   0.0309   |   0.0785   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2986   |   0.4473   |   0.0310   |   0.0846   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3026   |   0.4737   |   0.0242   | __0.0640__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3355   |   0.4305   |   0.0817   |   0.1397   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3558   |   0.4684   |   0.0451   |   0.0925   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4046   |   0.5031   |   0.0376   |   0.0693   |

<a name="table21"></a>Table 21: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/gtzan_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/gtzan_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/gtzan_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure78"></a>Figure 78: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure79"></a>Figure 79: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.1992__ |   0.3821   |   0.0247   |   0.0696   |
| [schreiber2014/default](#schreiber2014default)     |   0.2009   | __0.3776__ |   0.0294   |   0.0818   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2489   |   0.4233   |   0.0226   |   0.0664   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2564   |   0.4061   |   0.0441   |   0.1004   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2626   |   0.4318   |   0.0231   |   0.0646   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2695   |   0.4335   |   0.0230   |   0.0708   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2700   |   0.4362   |   0.0231   |   0.0646   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.2734   |   0.4413   |   0.0273   |   0.0773   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2786   |   0.4373   |   0.0295   |   0.0782   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2810   |   0.4375   |   0.0427   |   0.1027   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2936   |   0.4457   |   0.0291   |   0.0824   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2956   |   0.4695   | __0.0217__ | __0.0573__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3280   |   0.4262   |   0.0811   |   0.1401   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.3481   |   0.4644   |   0.0443   |   0.0929   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3940   |   0.4985   |   0.0359   |   0.0670   |

<a name="table22"></a>Table 22: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/gtzan_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/gtzan_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/gtzan_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure80"></a>Figure 80: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure81"></a>Figure 81: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.2002__ | __0.3848__ |   0.0280   |   0.0882   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2154   |   0.4030   |   0.0220   |   0.0736   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2164   |   0.4148   |   0.0206   | __0.0656__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2309   |   0.4143   |   0.0197   |   0.0658   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.2697   |   0.4244   |   0.0400   |   0.0892   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2699   |   0.4345   |   0.0247   |   0.0781   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2854   |   0.4413   |   0.0378   |   0.1036   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2855   |   0.4445   |   0.0368   |   0.0673   |
| [schreiber2014/default](#schreiber2014default)     |   0.2877   |   0.4413   |   0.0227   |   0.0806   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2908   |   0.4410   |   0.0403   |   0.1038   |
| [percival2014/stem](#percival2014stem)             |   0.2976   |   0.4550   | __0.0190__ |   0.0708   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3150   |   0.4731   |   0.0219   |   0.0815   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3195   |   0.4740   |   0.0226   |   0.0834   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3268   |   0.4733   |   0.0250   |   0.0783   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.3981   |   0.4686   |   0.0767   |   0.1384   |

<a name="table23"></a>Table 23: Mean AOE1/AOE2 for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) ordered by mean.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_maoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_maoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_maoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe1.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe1.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe2.csv "Download raw data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe2.json "Download raw data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.svg">
</figure>

<a name="figure82"></a>Figure 82: AOE<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.svg">
</figure>

<a name="figure83"></a>Figure 83: AOE<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9391   |   0.2842   |   0.1722   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.7506   | __0.0102__ |   0.1564   |   0.1033   |   0.4191   | __0.0000__ |   0.8895   | __0.0257__ |   0.0608   | __0.0000__ | __0.0004__ | __0.0000__ |   0.9922   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.7506   |   1.0000   | __0.0130__ |   0.1110   |   0.1297   |   0.6375   | __0.0000__ |   0.7522   |   0.0506   |   0.0947   | __0.0000__ | __0.0000__ | __0.0000__ |   0.6533   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0102__ | __0.0130__ |   1.0000   | __0.0001__ | __0.0002__ | __0.0305__ | __0.0000__ | __0.0032__ |   0.6259   |   0.4358   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0034__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0001__ |   0.1564   |   0.1110   | __0.0001__ |   1.0000   |   0.9828   | __0.0107__ | __0.0000__ |   0.1359   | __0.0002__ | __0.0010__ | __0.0001__ | __0.0047__ | __0.0000__ |   0.1374   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0001__ |   0.1033   |   0.1297   | __0.0002__ |   0.9828   |   1.0000   | __0.0380__ | __0.0000__ |   0.1984   | __0.0002__ | __0.0013__ | __0.0001__ | __0.0082__ | __0.0000__ |   0.1408   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.4191   |   0.6375   | __0.0305__ | __0.0107__ | __0.0380__ |   1.0000   | __0.0000__ |   0.3438   |   0.1203   |   0.2220   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2803   |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.8895   |   0.7522   | __0.0032__ |   0.1359   |   0.1984   |   0.3438   | __0.0000__ |   1.0000   | __0.0188__ | __0.0393__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8514   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0257__ |   0.0506   |   0.6259   | __0.0002__ | __0.0002__ |   0.1203   | __0.0000__ | __0.0188__ |   1.0000   |   0.3870   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0150__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.0608   |   0.0947   |   0.4358   | __0.0010__ | __0.0013__ |   0.2220   | __0.0000__ | __0.0393__ |   0.3870   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0400__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9391   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1895   |   0.1780   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2842   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0047__ | __0.0082__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1895   |   1.0000   | __0.0112__ | __0.0001__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1722   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1780   | __0.0112__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.9922   |   0.6533   | __0.0034__ |   0.1374   |   0.1408   |   0.2803   | __0.0000__ |   0.8514   | __0.0150__ | __0.0400__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |

<a name="table24"></a>Table 24: Paired t-test p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0079__ |   0.1432   |   0.2123   | __0.0001__ | __0.0000__ | __0.0434__ | __0.0000__ |   0.1013   | __0.0343__ | __0.0362__ | __0.0005__ |   0.8661   |   0.2708   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0079__ | __0.0000__ |   1.0000   |   0.2191   |   0.0959   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3293   |   0.6456   |   0.3847   |   0.5540   | __0.0078__ |   0.0695   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1432   | __0.0000__ |   0.2191   |   1.0000   |   0.7094   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |   0.8185   |   0.4683   |   0.7905   |   0.1013   |   0.1783   |   0.5884   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2123   | __0.0000__ |   0.0959   |   0.7094   |   1.0000   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ |   0.5067   |   0.2346   |   0.5017   | __0.0309__ |   0.1960   |   0.8201   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2211   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8716   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0434__ | __0.0001__ | __0.0000__ | __0.0003__ | __0.0004__ |   0.2211   | __0.0000__ |   1.0000   | __0.0000__ | __0.0002__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0181__ | __0.0009__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8716   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1013   | __0.0000__ |   0.3293   |   0.8185   |   0.5067   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   1.0000   |   0.1494   |   0.9714   |   0.1645   |   0.0947   |   0.4252   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0343__ | __0.0000__ |   0.6456   |   0.4683   |   0.2346   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1494   |   1.0000   |   0.6343   |   0.3635   | __0.0288__ |   0.1987   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0362__ | __0.0000__ |   0.3847   |   0.7905   |   0.5017   | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.9714   |   0.6343   |   1.0000   |   0.0819   | __0.0326__ |   0.3906   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0005__ | __0.0000__ |   0.5540   |   0.1013   | __0.0309__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0002__ |   0.1645   |   0.3635   |   0.0819   |   1.0000   | __0.0002__ | __0.0224__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8661   | __0.0000__ | __0.0078__ |   0.1783   |   0.1960   | __0.0000__ | __0.0000__ | __0.0181__ | __0.0000__ |   0.0947   | __0.0288__ | __0.0326__ | __0.0002__ |   1.0000   |   0.3066   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2708   | __0.0000__ |   0.0695   |   0.5884   |   0.8201   | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ |   0.4252   |   0.1987   |   0.3906   | __0.0224__ |   0.3066   |   1.0000   |

<a name="table25"></a>Table 25: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0010__ |   0.0712   |   0.2748   | __0.0001__ | __0.0000__ | __0.0407__ | __0.0000__ |   0.0989   | __0.0141__ | __0.0184__ | __0.0002__ |   0.7333   |   0.2602   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0010__ | __0.0000__ |   1.0000   |   0.1246   | __0.0121__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.1051   |   0.4509   |   0.1910   |   0.9167   | __0.0014__ | __0.0145__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0712   | __0.0000__ |   0.1246   |   1.0000   |   0.3734   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   0.9280   |   0.4601   |   0.8870   |   0.1392   |   0.1207   |   0.3790   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.2748   | __0.0000__ | __0.0121__ |   0.3734   |   1.0000   | __0.0000__ | __0.0000__ | __0.0007__ | __0.0000__ |   0.3996   |   0.0842   |   0.2874   | __0.0123__ |   0.3514   |   0.9923   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2105   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8121   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0407__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0007__ |   0.2105   | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0116__ | __0.0008__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8121   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0989   | __0.0000__ |   0.1051   |   0.9280   |   0.3996   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0179__ |   0.8080   |   0.1229   |   0.1223   |   0.4297   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0141__ | __0.0000__ |   0.4509   |   0.4601   |   0.0842   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0179__ |   1.0000   |   0.5325   |   0.4683   | __0.0154__ |   0.1065   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0184__ | __0.0000__ |   0.1910   |   0.8870   |   0.2874   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   0.8080   |   0.5325   |   1.0000   |   0.0916   | __0.0246__ |   0.2835   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0002__ | __0.0000__ |   0.9167   |   0.1392   | __0.0123__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0001__ |   0.1229   |   0.4683   |   0.0916   |   1.0000   | __0.0002__ | __0.0146__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7333   | __0.0000__ | __0.0014__ |   0.1207   |   0.3514   | __0.0000__ | __0.0000__ | __0.0116__ | __0.0000__ |   0.1223   | __0.0154__ | __0.0246__ | __0.0002__ |   1.0000   |   0.3778   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.2602   | __0.0000__ | __0.0145__ |   0.3790   |   0.9923   | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.4297   |   0.1065   |   0.2835   | __0.0146__ |   0.3778   |   1.0000   |

<a name="table26"></a>Table 26: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.0609   |   0.1140   | __0.0000__ |   0.4637   | __0.0000__ |   0.4024   |   0.4395   |   0.6114   |   0.5312   |   0.6648   | __0.0029__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.2834   | __0.0000__ | __0.0000__ |   0.2863   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0022__ |   0.7531   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.2834   |   1.0000   | __0.0000__ | __0.0000__ |   0.9451   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.4972   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.0609   | __0.0000__ | __0.0000__ |   1.0000   |   0.9165   | __0.0000__ | __0.0199__ | __0.0000__ |   0.3939   |   0.4097   |   0.2831   |   0.2768   | __0.0408__ |   0.2785   | __0.0002__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.1140   | __0.0000__ | __0.0000__ |   0.9165   |   1.0000   | __0.0000__ | __0.0302__ | __0.0000__ |   0.4501   |   0.4582   |   0.3183   |   0.3249   | __0.0392__ |   0.2167   | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.2863   |   0.9451   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.4984   |
| [percival2014/stem](#percival2014stem)             |   0.4637   | __0.0000__ | __0.0000__ | __0.0199__ | __0.0302__ | __0.0000__ |   1.0000   | __0.0000__ |   0.1285   |   0.1798   |   0.2789   |   0.1855   |   0.7800   | __0.0004__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.4024   | __0.0000__ | __0.0000__ |   0.3939   |   0.4501   | __0.0000__ |   0.1285   | __0.0000__ |   1.0000   |   0.9667   |   0.7037   |   0.7703   |   0.2426   | __0.0489__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4395   | __0.0000__ | __0.0000__ |   0.4097   |   0.4582   | __0.0000__ |   0.1798   | __0.0000__ |   0.9667   |   1.0000   |   0.2270   |   0.7898   |   0.2459   | __0.0441__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6114   | __0.0000__ | __0.0000__ |   0.2831   |   0.3183   | __0.0000__ |   0.2789   | __0.0000__ |   0.7037   |   0.2270   |   1.0000   |   0.9794   |   0.3730   | __0.0256__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5312   | __0.0000__ | __0.0000__ |   0.2768   |   0.3249   | __0.0000__ |   0.1855   | __0.0000__ |   0.7703   |   0.7898   |   0.9794   |   1.0000   |   0.2625   | __0.0052__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6648   | __0.0000__ | __0.0000__ | __0.0408__ | __0.0392__ | __0.0000__ |   0.7800   | __0.0000__ |   0.2426   |   0.2459   |   0.3730   |   0.2625   |   1.0000   | __0.0008__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0029__ | __0.0022__ | __0.0002__ |   0.2785   |   0.2167   | __0.0002__ | __0.0004__ | __0.0000__ | __0.0489__ | __0.0441__ | __0.0256__ | __0.0052__ | __0.0008__ |   1.0000   | __0.0036__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ |   0.7531   |   0.4972   | __0.0002__ | __0.0000__ |   0.4984   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0036__ |   1.0000   |

<a name="table27"></a>Table 27: Paired t-test p-values, using reference annotations [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0181__ | __0.0033__ | __0.0000__ |   0.1781   | __0.0000__ | __0.0021__ |   0.5288   |   0.5288   |   0.5395   |   0.6931   | __0.0040__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0125__ | __0.0021__ | __0.0141__ | __0.0056__ | __0.0000__ | __0.0000__ | __0.0268__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0197__ | __0.0439__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0125__ |   1.0000   | __0.0000__ | __0.0000__ |   0.9561   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6915   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0181__ | __0.0021__ | __0.0000__ |   1.0000   |   0.4601   | __0.0000__ |   0.3299   | __0.0000__ |   0.4510   |   0.1002   |   0.1002   |   0.1133   |   0.0767   |   0.5366   | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0033__ | __0.0141__ | __0.0000__ |   0.4601   |   1.0000   | __0.0000__ |   0.0646   | __0.0000__ |   0.9685   | __0.0097__ | __0.0097__ | __0.0197__ | __0.0057__ |   0.8812   | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0056__ |   0.9561   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6091   |
| [percival2014/stem](#percival2014stem)             |   0.1781   | __0.0000__ | __0.0000__ |   0.3299   |   0.0646   | __0.0000__ |   1.0000   | __0.0000__ |   0.0664   |   0.4926   |   0.4926   |   0.4215   |   0.3503   |   0.0660   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0021__ | __0.0268__ | __0.0000__ |   0.4510   |   0.9685   | __0.0000__ |   0.0664   | __0.0000__ |   1.0000   | __0.0005__ | __0.0005__ | __0.0093__ | __0.0088__ |   0.9116   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5288   | __0.0000__ | __0.0000__ |   0.1002   | __0.0097__ | __0.0000__ |   0.4926   | __0.0000__ | __0.0005__ |   1.0000   |   0.1056   |   0.9846   |   0.8360   | __0.0142__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5288   | __0.0000__ | __0.0000__ |   0.1002   | __0.0097__ | __0.0000__ |   0.4926   | __0.0000__ | __0.0005__ |   0.1056   |   1.0000   |   0.9846   |   0.8360   | __0.0142__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5395   | __0.0000__ | __0.0000__ |   0.1133   | __0.0197__ | __0.0000__ |   0.4215   | __0.0000__ | __0.0093__ |   0.9846   |   0.9846   |   1.0000   |   0.8271   | __0.0061__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6931   | __0.0000__ | __0.0000__ |   0.0767   | __0.0057__ | __0.0000__ |   0.3503   | __0.0000__ | __0.0088__ |   0.8360   |   0.8360   |   0.8271   |   1.0000   | __0.0097__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0040__ | __0.0197__ | __0.0000__ |   0.5366   |   0.8812   | __0.0000__ |   0.0660   | __0.0000__ |   0.9116   | __0.0142__ | __0.0142__ | __0.0061__ | __0.0097__ |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0439__ |   0.6915   | __0.0000__ | __0.0000__ |   0.6091   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |

<a name="table28"></a>Table 28: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0172__ | __0.0095__ | __0.0000__ |   0.5518   | __0.0000__ | __0.0032__ |   0.8184   |   0.6977   |   0.9831   |   0.8634   | __0.0089__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0106__ | __0.0047__ | __0.0080__ | __0.0117__ | __0.0000__ | __0.0000__ | __0.0427__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0211__ | __0.0492__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0106__ |   1.0000   | __0.0000__ | __0.0000__ |   0.7786   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5657   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0172__ | __0.0047__ | __0.0000__ |   1.0000   |   0.6854   | __0.0000__ |   0.1009   | __0.0000__ |   0.4835   |   0.0539   |   0.0704   | __0.0360__ | __0.0235__ |   0.6609   | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0095__ | __0.0080__ | __0.0000__ |   0.6854   |   1.0000   | __0.0000__ | __0.0313__ | __0.0000__ |   0.7636   | __0.0078__ | __0.0129__ | __0.0103__ | __0.0028__ |   0.9669   | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0117__ |   0.7786   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7299   |
| [percival2014/stem](#percival2014stem)             |   0.5518   | __0.0000__ | __0.0000__ |   0.1009   | __0.0313__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0123__ |   0.7248   |   0.8390   |   0.4895   |   0.4342   | __0.0178__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0032__ | __0.0427__ | __0.0000__ |   0.4835   |   0.7636   | __0.0000__ | __0.0123__ | __0.0000__ |   1.0000   | __0.0002__ | __0.0003__ | __0.0013__ | __0.0016__ |   0.7816   | __0.0001__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8184   | __0.0000__ | __0.0000__ |   0.0539   | __0.0078__ | __0.0000__ |   0.7248   | __0.0000__ | __0.0002__ |   1.0000   |   0.3176   |   0.7990   |   0.6685   | __0.0093__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6977   | __0.0000__ | __0.0000__ |   0.0704   | __0.0129__ | __0.0000__ |   0.8390   | __0.0000__ | __0.0003__ |   0.3176   |   1.0000   |   0.6766   |   0.5590   | __0.0132__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9831   | __0.0000__ | __0.0000__ | __0.0360__ | __0.0103__ | __0.0000__ |   0.4895   | __0.0000__ | __0.0013__ |   0.7990   |   0.6766   |   1.0000   |   0.8520   | __0.0018__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8634   | __0.0000__ | __0.0000__ | __0.0235__ | __0.0028__ | __0.0000__ |   0.4342   | __0.0000__ | __0.0016__ |   0.6685   |   0.5590   |   0.8520   |   1.0000   | __0.0029__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0089__ | __0.0211__ | __0.0000__ |   0.6609   |   0.9669   | __0.0000__ | __0.0178__ | __0.0000__ |   0.7816   | __0.0093__ | __0.0132__ | __0.0018__ | __0.0029__ |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0492__ |   0.5657   | __0.0000__ | __0.0000__ |   0.7299   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |

<a name="table29"></a>Table 29: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/gtzan_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/gtzan_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/gtzan_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg">
</figure>

<a name="figure84"></a>Figure 84: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg">
</figure>

<a name="figure85"></a>Figure 85: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg">
</figure>

<a name="figure86"></a>Figure 86: Mean AOE<sub>1</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg">
</figure>

<a name="figure87"></a>Figure 87: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg">
</figure>

<a name="figure88"></a>Figure 88: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28 based on c<sub>var</sub>-Values from GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg">
</figure>

<a name="figure89"></a>Figure 89: Mean AOE<sub>2</sub> compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tracks with c<sub>var</sub> < τ based on beat annotations from [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure90"></a>Figure 90: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure91"></a>Figure 91: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.svg">
</figure>

<a name="figure92"></a>Figure 92: Mean AOE<sub>1</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure93"></a>Figure 93: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/gtzan_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure94"></a>Figure 94: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/gtzan_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.svg">
</figure>

<a name="figure95"></a>Figure 95: Mean AOE<sub>2</sub> for estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) for tempo intervals around T.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure96"></a>Figure 96: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure97"></a>Figure 97: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.svg">
</figure>

<a name="figure98"></a>Figure 98: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure99"></a>Figure 99: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure100"></a>Figure 100: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28).

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.svg">
</figure>

<a name="figure101"></a>Figure 101: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure102"></a>Figure 102: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure103"></a>Figure 103: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.svg">
</figure>

<a name="figure104"></a>Figure 104: AOE<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe1.svg">
</figure>

<a name="figure105"></a>Figure 105: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe1.svg">
</figure>

<a name="figure106"></a>Figure 106: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.svg">
</figure>

<a name="figure107"></a>Figure 107: AOE<sub>1</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure108"></a>Figure 108: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure109"></a>Figure 109: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_2.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.svg">
</figure>

<a name="figure110"></a>Figure 110: AOE<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_open'.

[SVG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_tag_open_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_gtzan' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_gtzan' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe2.svg">
</figure>

<a name="figure111"></a>Figure 111: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_gtzan' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe2.svg">
</figure>

<a name="figure112"></a>Figure 112: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_2.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_gtzan' Tags for GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28

<figure>
<embed type="image/svg+xml" src="figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.svg">
</figure>

<a name="figure113"></a>Figure 113: AOE<sub>2</sub> of estimates compared to version [GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28](#gtzan-rhythm_v2_ismir2015_lbd_2015-10-28) depending on tag from namespace 'tag_gtzan'.

[SVG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.svg "Open Figure") [PDF](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.pdf "Open Figure") [PNG](figures/gtzan_estimates_1.0_tag_gtzan_GTZAN-Rhythm_v2_ismir2015_lbd_2015-10-28_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 17:13. Size L.
