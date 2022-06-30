---
title: hjdb
{:.no_toc}
layout: default
---

# hjdb
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'hjdb' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'hjdb'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 1.0 |
| **Curator** | [Jason Hockman](mailto:Jason.Hockman@bcu.ac.uk) |
| **Data&nbsp;Source** | manual annotation, GitHub repository of Sebastian Böck |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Hockman2012](bib/Hockman2012.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/superbock/ISMIR2019](https://github.com/superbock/ISMIR2019) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 2.0 |
| **Curator** | [Jason Hockman](mailto:Jason.Hockman@bcu.ac.uk) |
| **Data&nbsp;Source** | manual annotation, GitHub repository of Sebastian Böck |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | based on median of inter corresponding beat intervals |
| **Annotator,&nbsp;bibtex** |[Hockman2012](bib/Hockman2012.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/superbock/ISMIR2019](https://github.com/superbock/ISMIR2019) |

### 3.0

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 3.0 |
| **Curator** | [Sebastian Böck](mailto:sebastian.boeck@ofai.at) |
| **Data&nbsp;Source** | GitHub repository of Sebastian Böck |
| **Annotation&nbsp;Tools** | unknown |
| **Annotation&nbsp;Rules** | unknown |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |
| **Annotator,&nbsp;ref_url** | [https://github.com/superbock/ISMIR2019](https://github.com/superbock/ISMIR2019) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   235   |   120.00   |   171.43   |   152.15   |   10.24   |   86.00   |   1.00   |
| [2.0](#20)                                         |   235   |   120.00   |   172.66   |   152.38   |   10.36   |   87.00   |   1.00   |
| [3.0](#30)                                         |   235   |   120.00   |   171.43   |   152.14   |   10.24   |   86.00   |   1.00   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/hjdb_reference_basic_stats.csv "Download data as CSV") [JSON](data/hjdb_reference_basic_stats.json "Download data as JSON") [LATEX](data/hjdb_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/hjdb_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/hjdb_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/hjdb_reference_dist.csv "Download data as CSV") [JSON](data/hjdb_reference_dist.json "Download data as JSON") [LATEX](data/hjdb_reference_dist.latex "Download data as LATEX") [PICKLE](data/hjdb_reference_dist.pickle "Download data as PICKLE") [SVG](figures/hjdb_reference_dist.svg "Open Figure") [PDF](figures/hjdb_reference_dist.pdf "Open Figure") [PNG](figures/hjdb_reference_dist.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/hjdb_variation.svg">
</figure>

<a name="figure2"></a>Figure 2: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/hjdb_variation.csv "Download data as CSV") [JSON](data/hjdb_variation.json "Download data as JSON") [LATEX](data/hjdb_variation.latex "Download data as LATEX") [PICKLE](data/hjdb_variation.pickle "Download data as PICKLE") [SVG](figures/hjdb_variation.svg "Open Figure") [PDF](figures/hjdb_variation.pdf "Open Figure") [PNG](figures/hjdb_variation.png "Open Figure") 

# Estimates for 'hjdb'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### boeck2019/multi_task

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2019/multi_task_hjdb

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task_hjdb, 8-fold cross validation, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2020/dar

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | https://github.com/superbock/ISMIR2020 |
| **Annotator,&nbsp;bibtex** |[Boeck2020](bib/Boeck2020.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.4 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.4 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | hjdb |
| **Version** | 0.0.4 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   236   |   42.55   |   171.43   |   146.62   |   22.57   |   86.00   |   0.93   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   235   |   76.04   |   204.93   |   141.07   |   27.73   |   100.00   |   0.86   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   235   |   119.79   |   170.96   |   152.42   |   10.26   |   86.00   |   1.00   |
| [boeck2020/dar](#boeck2020dar)                     |   235   |   120.26   |   172.58   |   151.71   |   10.03   |   87.00   |   1.00   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   236   |   71.78   |   166.71   |   125.27   |   30.86   |   79.00   |   0.82   |
| [percival2014/stem](#percival2014stem)             |   236   |   69.84   |   159.63   |   96.34   |   29.52   |   70.00   |   0.83   |
| [schreiber2014/default](#schreiber2014default)     |   236   |   64.90   |   169.46   |   111.01   |   35.65   |   76.00   |   0.69   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   236   |   69.00   |   167.18   |   120.13   |   34.81   |   75.00   |   0.70   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   236   |   72.53   |   169.46   |   132.10   |   31.83   |   80.00   |   0.77   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   236   |   77.00   |   170.00   |   148.10   |   19.45   |   85.00   |   0.95   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   236   |   79.00   |   173.00   |   149.74   |   16.49   |   87.00   |   0.97   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   236   |   77.00   |   176.00   |   145.80   |   22.31   |   85.00   |   0.92   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/hjdb_estimates_basic_stats.csv "Download data as CSV") [JSON](data/hjdb_estimates_basic_stats.json "Download data as JSON") [LATEX](data/hjdb_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/hjdb_estimates_dist.csv "Download data as CSV") [JSON](data/hjdb_estimates_dist.json "Download data as JSON") [LATEX](data/hjdb_estimates_dist.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_dist.svg "Open Figure") [PDF](figures/hjdb_estimates_dist.pdf "Open Figure") [PNG](figures/hjdb_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __1.0000__ | __1.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.9957   |   0.9957   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9660   | __1.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9447   | __1.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.9277   | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9064   |   0.9915   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8255   |   0.9617   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7404   |   0.9830   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5915   |   0.9830   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5660   |   0.7872   |
| [schreiber2014/default](#schreiber2014default)     |   0.4638   |   0.9787   |
| [percival2014/stem](#percival2014stem)             |   0.2851   | __1.0000__ |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hjdb_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hjdb_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hjdb_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/hjdb_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/hjdb_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __1.0000__ | __1.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.9957   |   0.9957   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9660   | __1.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9447   | __1.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.9277   | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9064   |   0.9915   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8298   |   0.9660   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7404   |   0.9872   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5915   |   0.9872   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5660   |   0.7872   |
| [schreiber2014/default](#schreiber2014default)     |   0.4681   |   0.9830   |
| [percival2014/stem](#percival2014stem)             |   0.2851   | __1.0000__ |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hjdb_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hjdb_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hjdb_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/hjdb_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/hjdb_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_accuracy2.png "Open Figure") 

### Accuracy Results for 3.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __1.0000__ | __1.0000__ |
| [boeck2020/dar](#boeck2020dar)                     |   0.9957   |   0.9957   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9660   | __1.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9447   | __1.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.9277   | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9064   |   0.9915   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8255   |   0.9617   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7404   |   0.9830   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5915   |   0.9830   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5660   |   0.7872   |
| [schreiber2014/default](#schreiber2014default)     |   0.4638   |   0.9787   |
| [percival2014/stem](#percival2014stem)             |   0.2851   | __1.0000__ |

<a name="table5"></a>Table 5: Mean accuracy of estimates compared to version [3.0](#30) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/hjdb_estimates_3.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/hjdb_estimates_3.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/hjdb_estimates_3.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/hjdb_estimates_3.0_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) depending on tolerance.

[CSV](data/hjdb_estimates_3.0_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (17 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Champion\_Sound' 'Champion\_Sound\_(Doc\_Scott\_Remix)' 'Dance\_Factor' 'Here\_Comes\_The\_Drumz\_(Drumz\_VIP\_Mix)' 'Light\_Years' 'NHS\_(Midday\_Mix)' 'Nightmare\_Walking' 'Renegade\_Snares\_(Foul\_Play\_Remix)' 'Serious\_Sounds' 'Spiritual\_Aura' ...
[CSV](data/hjdb_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (41 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breaking\_Free\_2' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Chasin\_A\_Dream' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Darkman' 'Devotion' ...
[CSV](data/hjdb_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[1.0](#10) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_1.0_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (102 differences):*
'A\_Musical\_Box' 'Aftershock' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free\_2' 'Cant\_Stop\_Thinking\_About' 'Champion\_Sound' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' ...
[CSV](data/hjdb_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (168 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'Another\_Direction' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bish\_Bosh' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (126 differences):*
'2\_Bad\_Mice\_Take\_You' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Alright\_With\_Me' 'Being\_With\_You' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breakage4' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' ...
[CSV](data/hjdb_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (96 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (61 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Champion\_Sound' ...
[CSV](data/hjdb_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (13 differences):*
'4\_Am' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Devotion' 'Further\_Intrigue' 'Last\_Action\_Hero' 'Open\_Your\_Mind' 'Rhythm' 'Rock\_To\_The\_Groove' 'Sweet\_Vibrations' 'The\_Helicopter\_Tune' ...
[CSV](data/hjdb_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (8 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Jump\_Mk\_II' 'No\_Worries' 'Skanka' 'Something\_I\_Feel\_(2\_Bad\_Mice\_Remix)' 'Stay\_Calm\_(Foul\_Play\_Remix)' 'Sweet\_Vibrations' 'Touch\_Somebody' 
[CSV](data/hjdb_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (22 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_1' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Chasin\_A\_Dream' 'Come\_Back\_2\_Me' 'Fearless\_Wonder\_(Remix)' 'Fuckin\_Hardcore' 'Hands\_Of\_Time' 'I\_Need\_Your\_Lovin' ...
[CSV](data/hjdb_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (17 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Champion\_Sound' 'Champion\_Sound\_(Doc\_Scott\_Remix)' 'Dance\_Factor' 'Here\_Comes\_The\_Drumz\_(Drumz\_VIP\_Mix)' 'Light\_Years' 'NHS\_(Midday\_Mix)' 'Nightmare\_Walking' 'Renegade\_Snares\_(Foul\_Play\_Remix)' 'Serious\_Sounds' 'Spiritual\_Aura' ...
[CSV](data/hjdb_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (40 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breaking\_Free\_2' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Chasin\_A\_Dream' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Darkman' 'Devotion' ...
[CSV](data/hjdb_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[2.0](#20) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_2.0_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (102 differences):*
'A\_Musical\_Box' 'Aftershock' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free\_2' 'Cant\_Stop\_Thinking\_About' 'Champion\_Sound' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' ...
[CSV](data/hjdb_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (168 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'Another\_Direction' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bish\_Bosh' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (125 differences):*
'2\_Bad\_Mice\_Take\_You' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Alright\_With\_Me' 'Being\_With\_You' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breakage4' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' ...
[CSV](data/hjdb_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (96 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (61 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Champion\_Sound' ...
[CSV](data/hjdb_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (13 differences):*
'4\_Am' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Devotion' 'Further\_Intrigue' 'Last\_Action\_Hero' 'Open\_Your\_Mind' 'Rhythm' 'Rock\_To\_The\_Groove' 'Sweet\_Vibrations' 'The\_Helicopter\_Tune' ...
[CSV](data/hjdb_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (8 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Jump\_Mk\_II' 'No\_Worries' 'Skanka' 'Something\_I\_Feel\_(2\_Bad\_Mice\_Remix)' 'Stay\_Calm\_(Foul\_Play\_Remix)' 'Sweet\_Vibrations' 'Touch\_Somebody' 
[CSV](data/hjdb_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (22 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_1' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Chasin\_A\_Dream' 'Come\_Back\_2\_Me' 'Fearless\_Wonder\_(Remix)' 'Fuckin\_Hardcore' 'Hands\_Of\_Time' 'I\_Need\_Your\_Lovin' ...
[CSV](data/hjdb_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (17 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Champion\_Sound' 'Champion\_Sound\_(Doc\_Scott\_Remix)' 'Dance\_Factor' 'Here\_Comes\_The\_Drumz\_(Drumz\_VIP\_Mix)' 'Light\_Years' 'NHS\_(Midday\_Mix)' 'Nightmare\_Walking' 'Renegade\_Snares\_(Foul\_Play\_Remix)' 'Serious\_Sounds' 'Spiritual\_Aura' ...
[CSV](data/hjdb_estimates_3.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (41 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breaking\_Free\_2' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Chasin\_A\_Dream' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Darkman' 'Devotion' ...
[CSV](data/hjdb_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[3.0](#30) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_3.0_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (102 differences):*
'A\_Musical\_Box' 'Aftershock' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free\_2' 'Cant\_Stop\_Thinking\_About' 'Champion\_Sound' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' ...
[CSV](data/hjdb_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem) (168 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'Another\_Direction' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bish\_Bosh' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_3.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (126 differences):*
'2\_Bad\_Mice\_Take\_You' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Alright\_With\_Me' 'Being\_With\_You' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Breakage4' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' ...
[CSV](data/hjdb_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (96 differences):*
'4\_Am' '6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'A21' 'A\_Musical\_Box' 'A\_New\_Dawn' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Being\_With\_You\_1' 'Beyond\_Bass' 'Bouncing' 'Breakage4' ...
[CSV](data/hjdb_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (61 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_(Foul\_Play\_Remix)' 'Beyond\_Bass' 'Bouncing' 'Breakage4' 'Breaking\_Free' 'Cant\_Stop\_The\_Rush\_(93\_Remix)' 'Cant\_Stop\_Thinking\_About' 'Casanova\_(Down\_To\_Earth\_Remix)' 'Champion\_Sound' ...
[CSV](data/hjdb_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn) (13 differences):*
'4\_Am' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Devotion' 'Further\_Intrigue' 'Last\_Action\_Hero' 'Open\_Your\_Mind' 'Rhythm' 'Rock\_To\_The\_Groove' 'Sweet\_Vibrations' 'The\_Helicopter\_Tune' ...
[CSV](data/hjdb_estimates_3.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn) (8 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Jump\_Mk\_II' 'No\_Worries' 'Skanka' 'Something\_I\_Feel\_(2\_Bad\_Mice\_Remix)' 'Stay\_Calm\_(Foul\_Play\_Remix)' 'Sweet\_Vibrations' 'Touch\_Somebody' 
[CSV](data/hjdb_estimates_3.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (22 differences):*
'A\_Musical\_Box' 'Being\_With\_You' 'Being\_With\_You\_1' 'Breakage4' 'Cant\_Stop\_Thinking\_About' 'Chasin\_A\_Dream' 'Come\_Back\_2\_Me' 'Fearless\_Wonder\_(Remix)' 'Fuckin\_Hardcore' 'Hands\_Of\_Time' 'I\_Need\_Your\_Lovin' ...
[CSV](data/hjdb_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[1.0](#10) compared with [boeck2019/multi_task](#boeck2019multi_task) (9 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Devotion' 'Finest\_Illusion\_(Legal\_Mix)' 'Promised\_Land' 'T-N-T' 'The\_Element\_(Highnoon)' 'The\_R' 'We\_Are\_Hardcore' 
[CSV](data/hjdb_estimates_1.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[1.0](#10) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_1.0_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Breaking\_Free\_2' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' 'Crystalize' 'Dream\_Sequence' 'Enticer' 'Fearless\_Wonder\_(Remix)' 'Feel\_(Feel\_Good)' 'Finest\_Illusion\_(Legal\_Mix)' 'Get\_High\_(New\_Jack\_London)' ...
[CSV](data/hjdb_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem): No differences.*

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (5 differences):*
'Cant\_Stop\_Thinking\_About' 'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (4 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (4 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (2 differences):*
'Fearless\_Wonder\_(Remix)' 'Inna\_Year\_4000' 
[CSV](data/hjdb_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[2.0](#20) compared with [boeck2019/multi_task](#boeck2019multi_task) (8 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Devotion' 'Promised\_Land' 'T-N-T' 'The\_Element\_(Highnoon)' 'The\_R' 'We\_Are\_Hardcore' 
[CSV](data/hjdb_estimates_2.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[2.0](#20) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_2.0_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Breaking\_Free\_2' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' 'Crystalize' 'Dream\_Sequence' 'Enticer' 'Fearless\_Wonder\_(Remix)' 'Feel\_(Feel\_Good)' 'Finest\_Illusion\_(Legal\_Mix)' 'Get\_High\_(New\_Jack\_London)' ...
[CSV](data/hjdb_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem): No differences.*

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (4 differences):*
'Cant\_Stop\_Thinking\_About' 'Crystalize' 'Deep\_Space' 'Horizons' 
[CSV](data/hjdb_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (3 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 
[CSV](data/hjdb_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (3 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 
[CSV](data/hjdb_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (2 differences):*
'Fearless\_Wonder\_(Remix)' 'Inna\_Year\_4000' 
[CSV](data/hjdb_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[3.0](#30) compared with [boeck2019/multi_task](#boeck2019multi_task) (9 differences):*
'6\_Million\_Ways\_To\_Die\_(DJ\_Hype\_Remix)' 'Dark\_Stranger\_(Origin\_Unknown\_Remix)' 'Devotion' 'Finest\_Illusion\_(Legal\_Mix)' 'Promised\_Land' 'T-N-T' 'The\_Element\_(Highnoon)' 'The\_R' 'We\_Are\_Hardcore' 
[CSV](data/hjdb_estimates_3.0_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb): No differences.*

*[3.0](#30) compared with [boeck2020/dar](#boeck2020dar) (1 differences):*
'Ruff!' 
[CSV](data/hjdb_estimates_3.0_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (50 differences):*
'Being\_With\_You\_(Foul\_Play\_Remix)' 'Breaking\_Free\_2' 'Cold\_Fresh\_Air\_(Remix)' 'Come\_Back\_2\_Me' 'Crystalize' 'Dream\_Sequence' 'Enticer' 'Fearless\_Wonder\_(Remix)' 'Feel\_(Feel\_Good)' 'Finest\_Illusion\_(Legal\_Mix)' 'Get\_High\_(New\_Jack\_London)' ...
[CSV](data/hjdb_estimates_3.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [percival2014/stem](#percival2014stem): No differences.*

*[3.0](#30) compared with [schreiber2014/default](#schreiber2014default) (5 differences):*
'Cant\_Stop\_Thinking\_About' 'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_3.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (4 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_3.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (4 differences):*
'Crystalize' 'Deep\_Space' 'Horizons' 'My\_Own\_(Hixxy\_and\_UFO\_Remix)' 
[CSV](data/hjdb_estimates_3.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[3.0](#30) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[3.0](#30) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[3.0](#30) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (2 differences):*
'Fearless\_Wonder\_(Remix)' 'Inna\_Year\_4000' 
[CSV](data/hjdb_estimates_3.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0018__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5716   |   0.0931   |   0.5114   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0018__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0205__ | __0.0001__ | __0.0000__ | __0.0110__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0078__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0391__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0153__ |   0.5713   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0153__ | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5713   | __0.0000__ | __0.0020__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0205__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5716   | __0.0001__ | __0.0002__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3593   |   0.1078   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0931   | __0.0000__ | __0.0078__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3593   |   1.0000   | __0.0043__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5114   | __0.0110__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1078   | __0.0043__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0027__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5716   |   0.0931   |   0.5114   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0027__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0154__ | __0.0001__ | __0.0000__ | __0.0153__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0078__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0391__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0211__ |   0.5713   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0211__ | __0.0000__ |   1.0000   | __0.0030__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5713   | __0.0000__ | __0.0030__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0154__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5716   | __0.0001__ | __0.0002__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3593   |   0.1078   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0931   | __0.0000__ | __0.0078__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3593   |   1.0000   | __0.0043__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5114   | __0.0153__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1078   | __0.0043__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0018__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5716   |   0.0931   |   0.5114   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0018__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0205__ | __0.0001__ | __0.0000__ | __0.0110__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0078__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0391__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0153__ |   0.5713   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0153__ | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5713   | __0.0000__ | __0.0020__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0205__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5716   | __0.0001__ | __0.0002__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3593   |   0.1078   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0931   | __0.0000__ | __0.0078__ | __0.0391__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3593   |   1.0000   | __0.0043__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5114   | __0.0110__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1078   | __0.0043__ |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0039__ |   1.0000   | __0.0039__ | __0.0215__ | __0.0000__ | __0.0039__ |   0.4240   |   0.2668   |   0.2668   | __0.0039__ | __0.0039__ |   0.0654   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2020/dar](#boeck2020dar)                     |   1.0000   | __0.0215__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.2188   |   0.3750   |   0.3750   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2014/default](#schreiber2014default)     |   0.0625   |   0.4240   |   0.0625   |   0.2188   | __0.0000__ |   0.0625   |   1.0000   |   1.0000   |   1.0000   |   0.0625   |   0.0625   |   0.4531   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1250   |   0.2668   |   0.1250   |   0.3750   | __0.0000__ |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   0.1250   |   0.6875   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1250   |   0.2668   |   0.1250   |   0.3750   | __0.0000__ |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   0.1250   |   0.6875   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5000   |   0.0654   |   0.5000   |   1.0000   | __0.0000__ |   0.5000   |   0.4531   |   0.6875   |   0.6875   |   0.5000   |   0.5000   |   1.0000   |

<a name="table9"></a>Table 9: McNemar p-values, using reference annotations [3.0](#30) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0078__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.1250   |   0.2500   |   0.2500   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0078__ |   1.0000   | __0.0078__ | __0.0391__ | __0.0000__ | __0.0078__ |   0.3877   |   0.2266   |   0.2266   | __0.0078__ | __0.0078__ |   0.1094   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   | __0.0078__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.1250   |   0.2500   |   0.2500   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2020/dar](#boeck2020dar)                     |   1.0000   | __0.0391__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.3750   |   0.6250   |   0.6250   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   1.0000   | __0.0078__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.1250   |   0.2500   |   0.2500   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2014/default](#schreiber2014default)     |   0.1250   |   0.3877   |   0.1250   |   0.3750   | __0.0000__ |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   0.1250   |   0.6875   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2500   |   0.2266   |   0.2500   |   0.6250   | __0.0000__ |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   0.2500   |   0.2500   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2500   |   0.2266   |   0.2500   |   0.6250   | __0.0000__ |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   0.2500   |   0.2500   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   | __0.0078__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.1250   |   0.2500   |   0.2500   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   | __0.0078__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.1250   |   0.2500   |   0.2500   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5000   |   0.1094   |   0.5000   |   1.0000   | __0.0000__ |   0.5000   |   0.6875   |   1.0000   |   1.0000   |   0.5000   |   0.5000   |   1.0000   |

<a name="table10"></a>Table 10: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0039__ |   1.0000   | __0.0039__ | __0.0215__ | __0.0000__ | __0.0039__ |   0.4240   |   0.2668   |   0.2668   | __0.0039__ | __0.0039__ |   0.0654   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [boeck2020/dar](#boeck2020dar)                     |   1.0000   | __0.0215__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.2188   |   0.3750   |   0.3750   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2014/default](#schreiber2014default)     |   0.0625   |   0.4240   |   0.0625   |   0.2188   | __0.0000__ |   0.0625   |   1.0000   |   1.0000   |   1.0000   |   0.0625   |   0.0625   |   0.4531   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1250   |   0.2668   |   0.1250   |   0.3750   | __0.0000__ |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   0.1250   |   0.6875   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1250   |   0.2668   |   0.1250   |   0.3750   | __0.0000__ |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   0.1250   |   0.6875   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   | __0.0039__ |   1.0000   |   1.0000   | __0.0000__ |   1.0000   |   0.0625   |   0.1250   |   0.1250   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5000   |   0.0654   |   0.5000   |   1.0000   | __0.0000__ |   0.5000   |   0.4531   |   0.6875   |   0.6875   |   0.5000   |   0.5000   |   1.0000   |

<a name="table11"></a>Table 11: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_accuracy2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure22"></a>Figure 22: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure23"></a>Figure 23: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure24"></a>Figure 24: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure25"></a>Figure 25: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure26"></a>Figure 26: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure27"></a>Figure 27: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0025__ | __0.0106__ |   0.0025   |   0.0106   |
| [boeck2020/dar](#boeck2020dar)                     |   -0.0041   |   0.0107   |   -0.0041   |   0.0107   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0312   |   0.1793   |   0.0029   |   0.0113   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0525   |   0.2286   |   0.0029   |   0.0111   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0748   |   0.2705   | __0.0000__ | __0.0077__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0809   |   0.2805   |   0.0042   |   0.0205   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.1413   |   0.3502   |   0.0034   |   0.0740   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.3228   |   0.4197   |   0.1027   |   0.1694   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.2529   |   0.4327   |   0.0024   |   0.0414   |
| [percival2014/stem](#percival2014stem)             |   -0.7131   |   0.4507   |   0.0018   |   0.0105   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.4019   |   0.4877   |   0.0024   |   0.0414   |
| [schreiber2014/default](#schreiber2014default)     |   -0.5290   |   0.4968   |   0.0029   |   0.0332   |

<a name="table12"></a>Table 12: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/hjdb_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hjdb_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hjdb_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure28"></a>Figure 28: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure29"></a>Figure 29: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0005__ | __0.0036__ |   0.0005   |   0.0036   |
| [boeck2020/dar](#boeck2020dar)                     |   -0.0061   |   0.0053   |   -0.0061   |   0.0053   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0332   |   0.1809   |   0.0008   |   0.0044   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0545   |   0.2290   |   0.0008   |   0.0039   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0768   |   0.2701   |   -0.0020   |   0.0105   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0829   |   0.2800   |   0.0022   |   0.0174   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.1433   |   0.3518   |   0.0013   |   0.0729   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.3248   |   0.4213   |   0.1007   |   0.1696   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.2550   |   0.4325   |   0.0004   |   0.0404   |
| [percival2014/stem](#percival2014stem)             |   -0.7152   |   0.4519   | __-0.0003__ | __0.0029__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.4039   |   0.4880   |   0.0004   |   0.0404   |
| [schreiber2014/default](#schreiber2014default)     |   -0.5310   |   0.4986   |   0.0009   |   0.0319   |

<a name="table13"></a>Table 13: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/hjdb_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hjdb_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hjdb_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure30"></a>Figure 30: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 3.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2020/dar](#boeck2020dar)                     |   -0.0039   | __0.0107__ |   -0.0039   |   0.0107   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0027__ |   0.0107   |   0.0027   |   0.0107   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0310   |   0.1793   |   0.0030   |   0.0113   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0523   |   0.2287   |   0.0030   |   0.0112   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0746   |   0.2706   | __0.0002__ | __0.0075__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0807   |   0.2805   |   0.0044   |   0.0205   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.1412   |   0.3503   |   0.0035   |   0.0740   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.3226   |   0.4197   |   0.1029   |   0.1695   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.2528   |   0.4330   |   0.0026   |   0.0413   |
| [percival2014/stem](#percival2014stem)             |   -0.7130   |   0.4505   |   0.0019   |   0.0106   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.4017   |   0.4878   |   0.0026   |   0.0413   |
| [schreiber2014/default](#schreiber2014default)     |   -0.5288   |   0.4968   |   0.0031   |   0.0332   |

<a name="table14"></a>Table 14: Mean OE1/OE2 for estimates compared to version [3.0](#30) ordered by standard deviation.

[CSV](data/hjdb_estimates_3.0_moe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_moe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_moe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/hjdb_estimates_3.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/hjdb_estimates_3.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_distribution_oe1.svg">
</figure>

<a name="figure32"></a>Figure 32: OE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_3.0_distribution_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_distribution_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_distribution_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_distribution_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_distribution_oe2.svg">
</figure>

<a name="figure33"></a>Figure 33: OE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_3.0_distribution_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_distribution_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_distribution_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_distribution_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0269__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3345   | __0.0375__ |   0.8146   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0269__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0012__ | __0.0000__ | __0.0279__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0048__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0222__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0263__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0263__ | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3345   | __0.0012__ | __0.0003__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2518   |   0.1648   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0375__ | __0.0000__ | __0.0048__ | __0.0222__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2518   |   1.0000   | __0.0088__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8146   | __0.0279__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1648   | __0.0088__ |   1.0000   |

<a name="table15"></a>Table 15: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0269__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3345   | __0.0375__ |   0.8146   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0269__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0012__ | __0.0000__ | __0.0279__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0048__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0222__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0263__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0263__ | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3345   | __0.0012__ | __0.0003__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2518   |   0.1648   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0375__ | __0.0000__ | __0.0048__ | __0.0222__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2518   |   1.0000   | __0.0088__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8146   | __0.0279__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1648   | __0.0088__ |   1.0000   |

<a name="table16"></a>Table 16: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0269__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3345   | __0.0375__ |   0.8146   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0269__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0012__ | __0.0000__ | __0.0279__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0048__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0222__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0263__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0263__ | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0481__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3345   | __0.0012__ | __0.0003__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2518   |   0.1648   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0375__ | __0.0000__ | __0.0048__ | __0.0222__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2518   |   1.0000   | __0.0088__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8146   | __0.0279__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1648   | __0.0088__ |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.4893   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0099__ |   0.1902   |   0.3876   |   0.3876   | __0.0001__ | __0.0001__ | __0.0018__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.4893   |   1.0000   |   0.8610   |   0.1158   | __0.0000__ |   0.7339   |   0.9291   |   0.8581   |   0.8581   |   0.9144   |   0.9180   |   0.8576   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0002__ |   0.8610   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ |   0.8617   |   0.9598   |   0.9598   |   0.2095   |   0.2480   |   0.1359   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ |   0.1158   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0014__ | __0.0165__ | __0.0165__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0099__ |   0.7339   | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5856   |   0.8084   |   0.8084   | __0.0000__ | __0.0000__ | __0.0279__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1902   |   0.9291   |   0.8617   | __0.0014__ | __0.0000__ |   0.5856   |   1.0000   |   0.7574   |   0.7574   |   0.9824   |   0.9903   |   0.5730   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   1.0000   |   0.8152   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   0.8152   |   1.0000   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ |   0.9144   |   0.2095   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9824   |   0.8629   |   0.8629   |   1.0000   |   0.9452   |   0.2291   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0001__ |   0.9180   |   0.2480   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9903   |   0.8581   |   0.8581   |   0.9452   |   1.0000   |   0.2213   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0018__ |   0.8576   |   0.1359   | __0.0000__ | __0.0000__ | __0.0279__ |   0.5730   |   0.5226   |   0.5226   |   0.2291   |   0.2213   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.4893   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0099__ |   0.1902   |   0.3876   |   0.3876   | __0.0001__ | __0.0001__ | __0.0018__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.4893   |   1.0000   |   0.8610   |   0.1158   | __0.0000__ |   0.7339   |   0.9291   |   0.8581   |   0.8581   |   0.9144   |   0.9180   |   0.8576   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0002__ |   0.8610   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ |   0.8617   |   0.9598   |   0.9598   |   0.2095   |   0.2480   |   0.1359   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ |   0.1158   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0014__ | __0.0165__ | __0.0165__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0099__ |   0.7339   | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5856   |   0.8084   |   0.8084   | __0.0000__ | __0.0000__ | __0.0279__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1902   |   0.9291   |   0.8617   | __0.0014__ | __0.0000__ |   0.5856   |   1.0000   |   0.7574   |   0.7574   |   0.9824   |   0.9903   |   0.5730   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   1.0000   |   0.8152   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   0.8152   |   1.0000   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ |   0.9144   |   0.2095   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9824   |   0.8629   |   0.8629   |   1.0000   |   0.9452   |   0.2291   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0001__ |   0.9180   |   0.2480   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9903   |   0.8581   |   0.8581   |   0.9452   |   1.0000   |   0.2213   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0018__ |   0.8576   |   0.1359   | __0.0000__ | __0.0000__ | __0.0279__ |   0.5730   |   0.5226   |   0.5226   |   0.2291   |   0.2213   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.4893   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0099__ |   0.1902   |   0.3876   |   0.3876   | __0.0001__ | __0.0001__ | __0.0018__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.4893   |   1.0000   |   0.8610   |   0.1158   | __0.0000__ |   0.7339   |   0.9291   |   0.8581   |   0.8581   |   0.9144   |   0.9180   |   0.8576   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0002__ |   0.8610   |   1.0000   | __0.0000__ | __0.0000__ | __0.0002__ |   0.8617   |   0.9598   |   0.9598   |   0.2095   |   0.2480   |   0.1359   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ |   0.1158   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0014__ | __0.0165__ | __0.0165__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0099__ |   0.7339   | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5856   |   0.8084   |   0.8084   | __0.0000__ | __0.0000__ | __0.0279__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1902   |   0.9291   |   0.8617   | __0.0014__ | __0.0000__ |   0.5856   |   1.0000   |   0.7574   |   0.7574   |   0.9824   |   0.9903   |   0.5730   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   1.0000   |   0.8152   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3876   |   0.8581   |   0.9598   | __0.0165__ | __0.0000__ |   0.8084   |   0.7574   |   0.8152   |   1.0000   |   0.8629   |   0.8581   |   0.5226   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ |   0.9144   |   0.2095   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9824   |   0.8629   |   0.8629   |   1.0000   |   0.9452   |   0.2291   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0001__ |   0.9180   |   0.2480   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9903   |   0.8581   |   0.8581   |   0.9452   |   1.0000   |   0.2213   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0018__ |   0.8576   |   0.1359   | __0.0000__ | __0.0000__ | __0.0279__ |   0.5730   |   0.5226   |   0.5226   |   0.2291   |   0.2213   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_oe1.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean OE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure37"></a>Figure 37: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure38"></a>Figure 38: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_oe2.svg">
</figure>

<a name="figure39"></a>Figure 39: Mean OE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure40"></a>Figure 40: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: Mean OE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure43"></a>Figure 43: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_oe2.svg">
</figure>

<a name="figure45"></a>Figure 45: Mean OE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure46"></a>Figure 46: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure47"></a>Figure 47: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_oe1.svg">
</figure>

<a name="figure48"></a>Figure 48: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure49"></a>Figure 49: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure50"></a>Figure 50: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_oe2.svg">
</figure>

<a name="figure51"></a>Figure 51: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2020/dar](#boeck2020dar)                     | __0.0087__ |   0.0074   |   0.0087   |   0.0074   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0093   | __0.0057__ |   0.0093   |   0.0057   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0425   |   0.1769   |   0.0096   |   0.0066   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0643   |   0.2256   |   0.0096   |   0.0063   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.0762   |   0.2702   | __0.0025__ |   0.0073   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0944   |   0.2762   |   0.0103   |   0.0182   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1616   |   0.3413   |   0.0259   |   0.0695   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2607   |   0.4281   |   0.0136   |   0.0392   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3488   |   0.3984   |   0.1079   |   0.1661   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4076   |   0.4829   |   0.0136   |   0.0392   |
| [schreiber2014/default](#schreiber2014default)     |   0.5329   |   0.4926   |   0.0129   |   0.0308   |
| [percival2014/stem](#percival2014stem)             |   0.7157   |   0.4466   |   0.0091   | __0.0056__ |

<a name="table21"></a>Table 21: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/hjdb_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hjdb_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hjdb_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure52"></a>Figure 52: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure53"></a>Figure 53: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0028__ | __0.0023__ |   0.0028   |   0.0023   |
| [boeck2020/dar](#boeck2020dar)                     |   0.0067   |   0.0045   |   0.0067   |   0.0045   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0369   |   0.1801   |   0.0032   |   0.0032   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0579   |   0.2282   |   0.0027   |   0.0029   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.0831   |   0.2683   |   0.0083   |   0.0067   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0897   |   0.2779   |   0.0051   |   0.0168   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1593   |   0.3449   |   0.0221   |   0.0695   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2562   |   0.4318   |   0.0068   |   0.0398   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3499   |   0.4007   |   0.1058   |   0.1665   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4049   |   0.4871   |   0.0068   |   0.0398   |
| [schreiber2014/default](#schreiber2014default)     |   0.5319   |   0.4977   |   0.0062   |   0.0312   |
| [percival2014/stem](#percival2014stem)             |   0.7160   |   0.4506   | __0.0023__ | __0.0018__ |

<a name="table22"></a>Table 22: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/hjdb_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hjdb_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hjdb_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure54"></a>Figure 54: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure55"></a>Figure 55: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 3.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2020/dar](#boeck2020dar)                     | __0.0087__ |   0.0074   |   0.0087   |   0.0074   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.0095   | __0.0057__ |   0.0095   |   0.0057   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0425   |   0.1769   |   0.0096   |   0.0068   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0644   |   0.2256   |   0.0097   |   0.0063   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.0760   |   0.2702   | __0.0023__ |   0.0071   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0945   |   0.2761   |   0.0105   |   0.0182   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1616   |   0.3413   |   0.0259   |   0.0695   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2608   |   0.4282   |   0.0137   |   0.0391   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3488   |   0.3982   |   0.1081   |   0.1662   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4077   |   0.4828   |   0.0137   |   0.0391   |
| [schreiber2014/default](#schreiber2014default)     |   0.5329   |   0.4926   |   0.0130   |   0.0308   |
| [percival2014/stem](#percival2014stem)             |   0.7155   |   0.4465   |   0.0092   | __0.0056__ |

<a name="table23"></a>Table 23: Mean AOE1/AOE2 for estimates compared to version [3.0](#30) ordered by mean.

[CSV](data/hjdb_estimates_3.0_maoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_maoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_maoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/hjdb_estimates_3.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/hjdb_estimates_3.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/hjdb_estimates_3.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/hjdb_estimates_3.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/hjdb_estimates_3.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_distribution_aoe1.svg">
</figure>

<a name="figure56"></a>Figure 56: AOE<sub>1</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_3.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_distribution_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_distribution_aoe2.svg">
</figure>

<a name="figure57"></a>Figure 57: AOE<sub>2</sub> for estimates compared to version [3.0](#30). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/hjdb_estimates_3.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_distribution_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0040__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6132   |   0.1082   |   0.4682   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0040__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0029__ | __0.0003__ | __0.0000__ | __0.0130__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0002__ | __0.0000__ |   1.0000   |   0.0941   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0044__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0002__ | __0.0000__ |   0.0941   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0039__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0876   | __0.0103__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0876   | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0029__ | __0.0000__ | __0.0000__ | __0.0103__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6132   | __0.0003__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2313   |   0.1356   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1082   | __0.0000__ | __0.0044__ | __0.0039__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2313   |   1.0000   | __0.0054__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4682   | __0.0130__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1356   | __0.0054__ |   1.0000   |

<a name="table24"></a>Table 24: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0106__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2739   | __0.0273__ |   0.7960   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0106__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0040__ | __0.0002__ | __0.0000__ | __0.0109__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0041__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0105__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.1146   | __0.0068__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1146   | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0040__ | __0.0000__ | __0.0000__ | __0.0068__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2739   | __0.0002__ | __0.0003__ | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2589   |   0.1171   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0273__ | __0.0000__ | __0.0041__ | __0.0105__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2589   |   1.0000   | __0.0052__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7960   | __0.0109__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1171   | __0.0052__ |   1.0000   |

<a name="table25"></a>Table 25: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0041__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6037   |   0.1060   |   0.4762   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0041__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0030__ | __0.0003__ | __0.0000__ | __0.0129__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0002__ | __0.0000__ |   1.0000   |   0.2211   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0042__ | __0.0000__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0002__ | __0.0000__ |   0.2211   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0040__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.0882   | __0.0101__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0882   | __0.0000__ | __0.0015__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0030__ | __0.0000__ | __0.0000__ | __0.0101__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6037   | __0.0003__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2336   |   0.1360   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1060   | __0.0000__ | __0.0042__ | __0.0040__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2336   |   1.0000   | __0.0055__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4762   | __0.0129__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1360   | __0.0055__ |   1.0000   |

<a name="table26"></a>Table 26: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   | __0.0004__ | __0.0002__ | __0.0000__ | __0.0003__ | __0.0106__ | __0.0212__ | __0.0212__ | __0.0005__ | __0.0004__ | __0.0012__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0004__ |   1.0000   |   0.0941   | __0.0000__ |   0.0999   |   0.0821   |   0.1018   |   0.1018   |   0.3790   |   0.7426   |   0.3823   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0002__ |   0.0941   |   1.0000   | __0.0000__ |   0.2577   | __0.0309__ | __0.0499__ | __0.0499__ |   0.0660   |   0.1183   |   0.1492   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0003__ |   0.0999   |   0.2577   | __0.0000__ |   1.0000   |   0.0608   |   0.0786   |   0.0786   | __0.0434__ |   0.1318   |   0.2525   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0106__ |   0.0821   | __0.0309__ | __0.0000__ |   0.0608   |   1.0000   |   0.6556   |   0.6556   |   0.1070   |   0.0929   |   0.2851   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0212__ |   0.1018   | __0.0499__ | __0.0000__ |   0.0786   |   0.6556   |   1.0000   |   0.3734   |   0.1213   |   0.1076   |   0.2516   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0212__ |   0.1018   | __0.0499__ | __0.0000__ |   0.0786   |   0.6556   |   0.3734   |   1.0000   |   0.1213   |   0.1076   |   0.2516   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0005__ |   0.3790   |   0.0660   | __0.0000__ | __0.0434__ |   0.1070   |   0.1213   |   0.1213   |   1.0000   |   0.6820   |   0.4906   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0004__ |   0.7426   |   0.1183   | __0.0000__ |   0.1318   |   0.0929   |   0.1076   |   0.1076   |   0.6820   |   1.0000   |   0.4153   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0012__ |   0.3823   |   0.1492   | __0.0000__ |   0.2525   |   0.2851   |   0.2516   |   0.2516   |   0.4906   |   0.4153   |   1.0000   |

<a name="table27"></a>Table 27: Paired t-test p-values, using reference annotations [3.0](#30) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0030__ | __0.0000__ | __0.0011__ | __0.0000__ | __0.0000__ |   0.3307   |   0.5766   |   0.5766   | __0.0000__ | __0.0000__ | __0.0068__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0030__ |   1.0000   | __0.0000__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0017__ | __0.0039__ | __0.0039__ | __0.0000__ | __0.0000__ | __0.0003__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0050__ |   0.0896   |   0.1191   |   0.1191   |   0.7010   |   0.1546   | __0.0395__ |
| [boeck2020/dar](#boeck2020dar)                     | __0.0011__ | __0.0009__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |   0.8203   |   0.9608   |   0.9608   | __0.0000__ | __0.0000__ |   0.1690   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0050__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0557   |   0.0853   |   0.0853   |   0.0727   | __0.0004__ | __0.0127__ |
| [schreiber2014/default](#schreiber2014default)     |   0.3307   | __0.0017__ |   0.0896   |   0.8203   | __0.0000__ |   0.0557   |   1.0000   |   0.7220   |   0.7220   |   0.0864   |   0.1300   |   0.6372   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5766   | __0.0039__ |   0.1191   |   0.9608   | __0.0000__ |   0.0853   |   0.7220   |   1.0000   |   0.9513   |   0.1164   |   0.1590   |   0.5531   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5766   | __0.0039__ |   0.1191   |   0.9608   | __0.0000__ |   0.0853   |   0.7220   |   0.9513   |   1.0000   |   0.1164   |   0.1590   |   0.5531   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.7010   | __0.0000__ | __0.0000__ |   0.0727   |   0.0864   |   0.1164   |   0.1164   |   1.0000   | __0.0388__ | __0.0314__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.1546   | __0.0000__ | __0.0000__ | __0.0004__ |   0.1300   |   0.1590   |   0.1590   | __0.0388__ |   1.0000   |   0.0715   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0068__ | __0.0003__ | __0.0395__ |   0.1690   | __0.0000__ | __0.0127__ |   0.6372   |   0.5531   |   0.5531   | __0.0314__ |   0.0715   |   1.0000   |

<a name="table28"></a>Table 28: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0000__ |   1.0000   | __0.0003__ | __0.0003__ | __0.0000__ | __0.0003__ | __0.0101__ | __0.0202__ | __0.0202__ | __0.0004__ | __0.0004__ | __0.0011__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) | __0.0000__ | __0.0003__ |   1.0000   |   0.2211   | __0.0000__ |   0.2051   |   0.0753   |   0.0959   |   0.0959   |   0.2228   |   0.3526   |   0.3654   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0000__ | __0.0003__ |   0.2211   |   1.0000   | __0.0000__ |   0.4141   | __0.0367__ |   0.0565   |   0.0565   |   0.1113   |   0.1343   |   0.1938   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0003__ |   0.2051   |   0.4141   | __0.0000__ |   1.0000   |   0.0603   |   0.0792   |   0.0792   | __0.0379__ |   0.0591   |   0.2658   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0101__ |   0.0753   | __0.0367__ | __0.0000__ |   0.0603   |   1.0000   |   0.6558   |   0.6558   |   0.1070   |   0.1014   |   0.2765   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0202__ |   0.0959   |   0.0565   | __0.0000__ |   0.0792   |   0.6558   |   1.0000   |   0.3734   |   0.1227   |   0.1164   |   0.2466   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0202__ |   0.0959   |   0.0565   | __0.0000__ |   0.0792   |   0.6558   |   0.3734   |   1.0000   |   0.1227   |   0.1164   |   0.2466   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0004__ |   0.2228   |   0.1113   | __0.0000__ | __0.0379__ |   0.1070   |   0.1227   |   0.1227   |   1.0000   |   0.9102   |   0.5143   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0004__ |   0.3526   |   0.1343   | __0.0000__ |   0.0591   |   0.1014   |   0.1164   |   0.1164   |   0.9102   |   1.0000   |   0.4837   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0011__ |   0.3654   |   0.1938   | __0.0000__ |   0.2658   |   0.2765   |   0.2466   |   0.2466   |   0.5143   |   0.4837   |   1.0000   |

<a name="table29"></a>Table 29: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/hjdb_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/hjdb_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/hjdb_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure58"></a>Figure 58: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure59"></a>Figure 59: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure60"></a>Figure 60: Mean AOE<sub>1</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure61"></a>Figure 61: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/hjdb_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure62"></a>Figure 62: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/hjdb_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 3.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure63"></a>Figure 63: Mean AOE<sub>2</sub> compared to version [3.0](#30) for tracks with c<sub>var</sub> < τ based on beat annotations from [3.0](#30).

[CSV](data/hjdb_estimates_3.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure64"></a>Figure 64: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure65"></a>Figure 65: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_aoe1.svg">
</figure>

<a name="figure66"></a>Figure 66: Mean AOE<sub>1</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure67"></a>Figure 67: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/hjdb_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure68"></a>Figure 68: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/hjdb_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 3.0

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_inter_aoe2.svg">
</figure>

<a name="figure69"></a>Figure 69: Mean AOE<sub>2</sub> for estimates compared to version [3.0](#30) for tempo intervals around T.

[CSV](data/hjdb_estimates_3.0_inter_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_inter_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_inter_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_inter_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure70"></a>Figure 70: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure71"></a>Figure 71: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure72"></a>Figure 72: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure73"></a>Figure 73: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure74"></a>Figure 74: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 3.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [3.0](#30).

<figure>
<embed type="image/svg+xml" src="figures/hjdb_estimates_3.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure75"></a>Figure 75: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [3.0](#30). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/hjdb_estimates_3.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/hjdb_estimates_3.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/hjdb_estimates_3.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/hjdb_estimates_3.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/hjdb_estimates_3.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/hjdb_estimates_3.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/hjdb_estimates_3.0_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.1 on 2022-06-29 18:46. Size L.
