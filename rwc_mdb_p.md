---
title: rwc_mdb_p
{:.no_toc}
layout: default
---

# rwc_mdb_p
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'rwc_mdb_p' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'rwc_mdb_p'

## References

### 0.1

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 0.1 |
| **Curator** | [Masataka Goto](mailto:m.goto@aist.go.jp) |
| **Data&nbsp;Source** | AIST website. Tempo values are rough estimates and should not be used as data for research purposes. |
| **Annotation&nbsp;Tools** | unknown |
| **Annotation&nbsp;Rules** | unknown |
| **Annotator,&nbsp;name** | Masataka Goto |
| **Annotator,&nbsp;bibtex** |[Goto2006](bib/Goto2006.bib) |
| **Annotator,&nbsp;ref_url** | [https://staff.aist.go.jp/m.goto/RWC-MDB/AIST-Annotation/](https://staff.aist.go.jp/m.goto/RWC-MDB/AIST-Annotation/) |

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 1.0 |
| **Curator** | [Masataka Goto](mailto:m.goto@aist.go.jp) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of corresponding inter beat intervals |
| **Annotator,&nbsp;name** | Masataka Goto |
| **Annotator,&nbsp;bibtex** |[Goto2006](bib/Goto2006.bib) |
| **Annotator,&nbsp;ref_url** | [https://staff.aist.go.jp/m.goto/RWC-MDB/AIST-Annotation/](https://staff.aist.go.jp/m.goto/RWC-MDB/AIST-Annotation/) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [0.1](#01)                                         |   100   |   62.00   |   200.00   |   110.81   |   27.66   |   70.00   |   0.88   |
| [1.0](#10)                                         |   100   |   62.02   |   200.00   |   111.68   |   27.51   |   69.00   |   0.87   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/rwc_mdb_p_reference_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_p_reference_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_p_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_p_reference_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_p_reference_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_p_reference_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_reference_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_reference_dist.svg "Open Figure") [PDF](figures/rwc_mdb_p_reference_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_p_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/rwc_mdb_p_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/rwc_mdb_p_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/rwc_mdb_p_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/rwc_mdb_p_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/rwc_mdb_p_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/rwc_mdb_p_variation.csv "Download data as CSV") [JSON](data/rwc_mdb_p_variation.json "Download data as JSON") [LATEX](data/rwc_mdb_p_variation.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_variation.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_variation.svg "Open Figure") [PDF](figures/rwc_mdb_p_variation.pdf "Open Figure") [PNG](figures/rwc_mdb_p_variation.png "Open Figure") 

# Estimates for 'rwc_mdb_p'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_p |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** |  |
| **Version** | 0.0.3 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** |  |
| **Version** | 0.0.3 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** |  |
| **Version** | 0.0.3 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   100   |   41.96   |   187.50   |   90.99   |   31.62   |   54.00   |   0.67   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   100   |   80.75   |   178.21   |   123.00   |   24.28   |   87.00   |   0.95   |
| [percival2014/stem](#percival2014stem)             |   100   |   60.09   |   148.72   |   102.91   |   22.33   |   70.00   |   0.94   |
| [schreiber2014/default](#schreiber2014default)     |   100   |   59.93   |   157.99   |   101.33   |   22.55   |   68.00   |   0.92   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   100   |   54.00   |   163.00   |   106.23   |   24.79   |   69.00   |   0.90   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   100   |   60.01   |   163.00   |   107.34   |   23.65   |   69.00   |   0.92   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   100   |   60.00   |   188.00   |   113.65   |   29.37   |   70.00   |   0.85   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   100   |   54.00   |   197.00   |   109.32   |   29.51   |   70.00   |   0.87   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   100   |   70.00   |   188.00   |   110.28   |   24.17   |   71.00   |   0.92   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/rwc_mdb_p_estimates_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_p_estimates_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_dist.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 0.1

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9000__ | __0.9900__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8900   | __0.9900__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8700   | __0.9900__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8700   | __0.9900__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8600   | __0.9900__ |
| [percival2014/stem](#percival2014stem)             |   0.8500   | __0.9900__ |
| [schreiber2014/default](#schreiber2014default)     |   0.8200   |   0.9500   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7500   |   0.9600   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6500   |   0.9800   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [0.1](#01) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_p_estimates_0.1_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [0.1](#01) depending on tolerance.

[CSV](data/rwc_mdb_p_estimates_0.1_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [0.1](#01) depending on tolerance.

[CSV](data/rwc_mdb_p_estimates_0.1_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_accuracy2.png "Open Figure") 

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9000__ | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8900   | __1.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8900   | __1.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8700   | __1.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8600   | __1.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.8500   | __1.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.8200   |   0.9600   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7900   |   0.9900   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6500   | __1.0000__ |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_p_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_p_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_p_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[0.1](#01) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (35 differences):*
'RM-P001' 'RM-P003' 'RM-P005' 'RM-P010' 'RM-P012' 'RM-P015' 'RM-P018' 'RM-P020' 'RM-P022' 'RM-P023' 'RM-P027' ...
[CSV](data/rwc_mdb_p_estimates_0.1_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (25 differences):*
'RM-P004' 'RM-P009' 'RM-P037' 'RM-P039' 'RM-P041' 'RM-P045' 'RM-P046' 'RM-P055' 'RM-P056' 'RM-P057' 'RM-P060' ...
[CSV](data/rwc_mdb_p_estimates_0.1_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [percival2014/stem](#percival2014stem) (15 differences):*
'RM-P009' 'RM-P026' 'RM-P035' 'RM-P037' 'RM-P041' 'RM-P043' 'RM-P046' 'RM-P053' 'RM-P060' 'RM-P069' 'RM-P072' ...
[CSV](data/rwc_mdb_p_estimates_0.1_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2014/default](#schreiber2014default) (18 differences):*
'RM-P001' 'RM-P009' 'RM-P031' 'RM-P035' 'RM-P037' 'RM-P038' 'RM-P041' 'RM-P043' 'RM-P046' 'RM-P053' 'RM-P057' ...
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (13 differences):*
'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P056' 'RM-P057' 'RM-P062' 'RM-P072' 'RM-P073' 'RM-P075' 'RM-P077' ...
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (11 differences):*
'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P057' 'RM-P062' 'RM-P069' 'RM-P072' 'RM-P073' 'RM-P077' 'RM-P095' ...
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/cnn](#schreiber2018cnn) (10 differences):*
'RM-P004' 'RM-P034' 'RM-P041' 'RM-P048' 'RM-P056' 'RM-P069' 'RM-P072' 'RM-P077' 'RM-P083' 'RM-P097' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/fcn](#schreiber2018fcn) (14 differences):*
'RM-P004' 'RM-P026' 'RM-P027' 'RM-P041' 'RM-P048' 'RM-P056' 'RM-P060' 'RM-P069' 'RM-P072' 'RM-P073' 'RM-P075' ...
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (13 differences):*
'RM-P009' 'RM-P026' 'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P056' 'RM-P062' 'RM-P069' 'RM-P071' 'RM-P072' ...
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (35 differences):*
'RM-P001' 'RM-P003' 'RM-P005' 'RM-P010' 'RM-P012' 'RM-P015' 'RM-P018' 'RM-P020' 'RM-P022' 'RM-P023' 'RM-P027' ...
[CSV](data/rwc_mdb_p_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (21 differences):*
'RM-P004' 'RM-P009' 'RM-P037' 'RM-P039' 'RM-P041' 'RM-P045' 'RM-P046' 'RM-P055' 'RM-P056' 'RM-P057' 'RM-P060' ...
[CSV](data/rwc_mdb_p_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (15 differences):*
'RM-P009' 'RM-P026' 'RM-P035' 'RM-P037' 'RM-P041' 'RM-P043' 'RM-P046' 'RM-P053' 'RM-P060' 'RM-P069' 'RM-P071' ...
[CSV](data/rwc_mdb_p_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (18 differences):*
'RM-P001' 'RM-P009' 'RM-P031' 'RM-P035' 'RM-P037' 'RM-P038' 'RM-P041' 'RM-P043' 'RM-P046' 'RM-P053' 'RM-P057' ...
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (13 differences):*
'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P056' 'RM-P057' 'RM-P062' 'RM-P071' 'RM-P073' 'RM-P075' 'RM-P077' ...
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (11 differences):*
'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P057' 'RM-P062' 'RM-P069' 'RM-P071' 'RM-P073' 'RM-P077' 'RM-P095' ...
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (10 differences):*
'RM-P004' 'RM-P034' 'RM-P041' 'RM-P048' 'RM-P056' 'RM-P069' 'RM-P071' 'RM-P077' 'RM-P083' 'RM-P097' 
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (14 differences):*
'RM-P004' 'RM-P026' 'RM-P027' 'RM-P041' 'RM-P048' 'RM-P056' 'RM-P060' 'RM-P069' 'RM-P071' 'RM-P073' 'RM-P075' ...
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (11 differences):*
'RM-P009' 'RM-P026' 'RM-P035' 'RM-P037' 'RM-P041' 'RM-P046' 'RM-P056' 'RM-P062' 'RM-P069' 'RM-P095' 'RM-P097' ...
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>1</sub>:__
'RM-P041' 
[CSV](data/rwc_mdb_p_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[0.1](#01) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2 differences):*
'RM-P072' 'RM-P073' 
[CSV](data/rwc_mdb_p_estimates_0.1_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (4 differences):*
'RM-P060' 'RM-P072' 'RM-P073' 'RM-P097' 
[CSV](data/rwc_mdb_p_estimates_0.1_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [percival2014/stem](#percival2014stem) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2014/default](#schreiber2014default) (5 differences):*
'RM-P009' 'RM-P038' 'RM-P053' 'RM-P057' 'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/cnn](#schreiber2018cnn) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/fcn](#schreiber2018fcn) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (1 differences):*
'RM-P072' 
[CSV](data/rwc_mdb_p_estimates_0.1_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (1 differences):*
'RM-P060' 
[CSV](data/rwc_mdb_p_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem): No differences.*

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (4 differences):*
'RM-P009' 'RM-P038' 'RM-P053' 'RM-P057' 
[CSV](data/rwc_mdb_p_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017): No differences.*

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017): No differences.*

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018): No differences.*

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0649   | __0.0012__ | __0.0033__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0001__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0649   |   1.0000   |   0.3075   |   0.7111   |   0.1338   | __0.0414__ | __0.0347__ |   0.2295   | __0.0309__ |
| [percival2014/stem](#percival2014stem)             | __0.0012__ |   0.3075   |   1.0000   |   0.5488   |   0.7744   |   0.3437   |   0.3018   |   1.0000   |   0.3437   |
| [schreiber2014/default](#schreiber2014default)     | __0.0033__ |   0.7111   |   0.5488   |   1.0000   |   0.2266   |   0.0654   |   0.1153   |   0.5235   |   0.1435   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0002__ |   0.1338   |   0.7744   |   0.2266   |   1.0000   |   0.6250   |   0.5811   |   1.0000   |   0.7539   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0414__ |   0.3437   |   0.0654   |   0.6250   |   1.0000   |   1.0000   |   0.6072   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0347__ |   0.3018   |   0.1153   |   0.5811   |   1.0000   |   1.0000   |   0.2891   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0005__ |   0.2295   |   1.0000   |   0.5235   |   1.0000   |   0.6072   |   0.2891   |   1.0000   |   0.6291   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0001__ | __0.0309__ |   0.3437   |   0.1435   |   0.7539   |   1.0000   |   1.0000   |   0.6291   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1934   | __0.0012__ | __0.0033__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0005__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1934   |   1.0000   |   0.0755   |   0.2649   | __0.0169__ | __0.0026__ | __0.0026__ | __0.0433__ | __0.0075__ |
| [percival2014/stem](#percival2014stem)             | __0.0012__ |   0.0755   |   1.0000   |   0.5488   |   0.7744   |   0.3437   |   0.3018   |   1.0000   |   0.7539   |
| [schreiber2014/default](#schreiber2014default)     | __0.0033__ |   0.2649   |   0.5488   |   1.0000   |   0.2266   |   0.0654   |   0.1153   |   0.5235   |   0.3323   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0002__ | __0.0169__ |   0.7744   |   0.2266   |   1.0000   |   0.6250   |   0.5811   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0026__ |   0.3437   |   0.0654   |   0.6250   |   1.0000   |   1.0000   |   0.6072   |   0.7266   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0026__ |   0.3018   |   0.1153   |   0.5811   |   1.0000   |   1.0000   |   0.2891   |   0.5811   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0005__ | __0.0433__ |   1.0000   |   0.5235   |   1.0000   |   0.6072   |   0.2891   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0005__ | __0.0075__ |   0.7539   |   0.3323   |   1.0000   |   0.7266   |   0.5811   |   1.0000   |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [0.1](#01) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1.0000   |   1.0000   |   1.0000   |   0.3750   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.1250   |   0.3750   |   0.1250   |   1.0000   |   0.1250   |   0.1250   |   0.1250   |   0.1250   |   0.1250   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   1.0000   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5000   |   1.0000   |   0.3750   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5000   |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   0.2500   |   0.2500   |   0.2500   |   0.2500   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.3750   |   1.0000   |   0.1250   |   1.0000   |   0.1250   |   0.1250   |   0.1250   |   0.1250   |   0.1250   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   0.2500   |   1.0000   |   0.1250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [0.1](#01) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Accuracy<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 0.1

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0328   | __0.3003__ |   0.0028   |   0.0170   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0375   |   0.3121   |   0.0025   |   0.0153   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0575   |   0.3401   |   0.0025   | __0.0153__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0026__ |   0.3477   |   0.0026   |   0.0170   |
| [schreiber2014/default](#schreiber2014default)     |   -0.1211   |   0.3563   |   -0.0111   |   0.0715   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0274   |   0.3593   |   0.0026   |   0.0171   |
| [percival2014/stem](#percival2014stem)             |   -0.0973   |   0.3610   |   0.0027   |   0.0164   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1665   |   0.4421   |   0.0265   |   0.0442   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3235   |   0.5013   | __0.0024__ |   0.0171   |

<a name="table9"></a>Table 9: Mean OE1/OE2 for estimates compared to version [0.1](#01) ordered by standard deviation.

[CSV](data/rwc_mdb_p_estimates_0.1_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_distribution_oe1.svg">
</figure>

<a name="figure25"></a>Figure 25: OE<sub>1</sub> for estimates compared to version [0.1](#01). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_0.1_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_distribution_oe2.svg">
</figure>

<a name="figure26"></a>Figure 26: OE<sub>2</sub> for estimates compared to version [0.1](#01). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_0.1_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0203   | __0.3155__ |   0.0003   |   0.0031   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0499   |   0.3281   |   0.0001   |   0.0019   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __-0.0098__ |   0.3318   |   0.0002   |   0.0029   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0699   |   0.3541   |   0.0001   | __0.0019__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.1335   |   0.3677   |   -0.0135   |   0.0687   |
| [percival2014/stem](#percival2014stem)             |   -0.1098   |   0.3720   |   0.0002   |   0.0027   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0398   |   0.3725   |   0.0002   |   0.0035   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1541   |   0.4339   |   0.0241   |   0.0415   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3359   |   0.5021   | __-0.0001__ |   0.0054   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/rwc_mdb_p_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure27"></a>Figure 27: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure28"></a>Figure 28: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0049__ | __0.0001__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0000__ |   1.0000   |   0.4618   |   0.2522   |   0.0580   | __0.0006__ |   0.0710   | __0.0013__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0001__ | __0.0000__ |   0.4618   |   1.0000   | __0.0300__ | __0.0040__ | __0.0001__ | __0.0319__ | __0.0012__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2522   | __0.0300__ |   1.0000   |   0.3197   | __0.0116__ |   0.4061   |   0.0569   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0580   | __0.0040__ |   0.3197   |   1.0000   |   0.0507   |   0.7957   |   0.1574   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0049__ | __0.0006__ | __0.0001__ | __0.0116__ |   0.0507   |   1.0000   | __0.0330__ |   0.4058   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0001__ |   0.0710   | __0.0319__ |   0.4061   |   0.7957   | __0.0330__ |   1.0000   |   0.4696   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0001__ | __0.0013__ | __0.0012__ |   0.0569   |   0.1574   |   0.4058   |   0.4696   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0049__ | __0.0001__ | __0.0001__ |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0000__ |   1.0000   |   0.4618   |   0.2522   |   0.0580   | __0.0006__ |   0.0710   | __0.0013__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0001__ | __0.0000__ |   0.4618   |   1.0000   | __0.0300__ | __0.0040__ | __0.0001__ | __0.0319__ | __0.0012__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2522   | __0.0300__ |   1.0000   |   0.3197   | __0.0116__ |   0.4061   |   0.0569   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0580   | __0.0040__ |   0.3197   |   1.0000   |   0.0507   |   0.7957   |   0.1574   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0049__ | __0.0006__ | __0.0001__ | __0.0116__ |   0.0507   |   1.0000   | __0.0330__ |   0.4058   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0001__ |   0.0710   | __0.0319__ |   0.4061   |   0.7957   | __0.0330__ |   1.0000   |   0.4696   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0001__ | __0.0013__ | __0.0012__ |   0.0569   |   0.1574   |   0.4058   |   0.4696   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.5752   |   0.0536   |   0.7522   |   0.7522   |   0.4778   |   0.6639   |   0.6508   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.5752   | __0.0000__ |   1.0000   |   0.0509   |   0.5002   |   0.5002   |   0.7342   |   0.8953   |   0.8052   |
| [schreiber2014/default](#schreiber2014default)     |   0.0536   | __0.0000__ |   0.0509   |   1.0000   |   0.0524   |   0.0524   | __0.0481__ |   0.0504   |   0.0506   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7522   | __0.0000__ |   0.5002   |   0.0524   |   1.0000   |   0.4277   |   0.4172   |   0.7474   |   0.7364   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7522   | __0.0000__ |   0.5002   |   0.0524   |   0.4277   |   1.0000   |   0.4172   |   0.7474   |   0.7364   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4778   | __0.0000__ |   0.7342   | __0.0481__ |   0.4172   |   0.4172   |   1.0000   |   0.5465   |   0.4596   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6639   | __0.0000__ |   0.8953   |   0.0504   |   0.7474   |   0.7474   |   0.5465   |   1.0000   |   0.9230   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6508   | __0.0000__ |   0.8052   |   0.0506   |   0.7364   |   0.7364   |   0.4596   |   0.9230   |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.5752   |   0.0536   |   0.7522   |   0.7522   |   0.4778   |   0.6639   |   0.6508   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.5752   | __0.0000__ |   1.0000   |   0.0509   |   0.5002   |   0.5002   |   0.7342   |   0.8953   |   0.8052   |
| [schreiber2014/default](#schreiber2014default)     |   0.0536   | __0.0000__ |   0.0509   |   1.0000   |   0.0524   |   0.0524   | __0.0481__ |   0.0504   |   0.0506   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7522   | __0.0000__ |   0.5002   |   0.0524   |   1.0000   |   0.4277   |   0.4172   |   0.7474   |   0.7364   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7522   | __0.0000__ |   0.5002   |   0.0524   |   0.4277   |   1.0000   |   0.4172   |   0.7474   |   0.7364   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4778   | __0.0000__ |   0.7342   | __0.0481__ |   0.4172   |   0.4172   |   1.0000   |   0.5465   |   0.4596   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6639   | __0.0000__ |   0.8953   |   0.0504   |   0.7474   |   0.7474   |   0.5465   |   1.0000   |   0.9230   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6508   | __0.0000__ |   0.8052   |   0.0506   |   0.7364   |   0.7364   |   0.4596   |   0.9230   |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean OE<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean OE<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_oe1.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean OE<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_oe2.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean OE<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.svg">
</figure>

<a name="figure37"></a>Figure 37: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure38"></a>Figure 38: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.svg">
</figure>

<a name="figure39"></a>Figure 39: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure40"></a>Figure 40: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: OE<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe2.svg">
</figure>

<a name="figure43"></a>Figure 43: OE<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 0.1

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0942__ | __0.2870__ |   0.0042   |   0.0167   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1027   |   0.2971   |   0.0041   |   0.0149   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1227   |   0.3224   |   0.0041   | __0.0149__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1235   |   0.3250   | __0.0041__ |   0.0167   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1336   |   0.3347   |   0.0044   |   0.0167   |
| [percival2014/stem](#percival2014stem)             |   0.1447   |   0.3448   |   0.0055   |   0.0157   |
| [schreiber2014/default](#schreiber2014default)     |   0.1546   |   0.3430   |   0.0184   |   0.0700   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2379   |   0.4082   |   0.0271   |   0.0438   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3505   |   0.4828   |   0.0070   |   0.0158   |

<a name="table15"></a>Table 15: Mean AOE1/AOE2 for estimates compared to version [0.1](#01) ordered by mean.

[CSV](data/rwc_mdb_p_estimates_0.1_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_0.1_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_distribution_aoe1.svg">
</figure>

<a name="figure45"></a>Figure 45: AOE<sub>1</sub> for estimates compared to version [0.1](#01). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_0.1_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_distribution_aoe2.svg">
</figure>

<a name="figure46"></a>Figure 46: AOE<sub>2</sub> for estimates compared to version [0.1](#01). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_0.1_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.1016__ | __0.2993__ |   0.0018   |   0.0025   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1114   |   0.3126   |   0.0015   |   0.0011   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1116   |   0.3126   |   0.0017   |   0.0024   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1314   |   0.3362   | __0.0015__ | __0.0011__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1419   |   0.3467   |   0.0020   |   0.0029   |
| [percival2014/stem](#percival2014stem)             |   0.1521   |   0.3568   |   0.0022   |   0.0016   |
| [schreiber2014/default](#schreiber2014default)     |   0.1631   |   0.3555   |   0.0156   |   0.0683   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2249   |   0.4018   |   0.0241   |   0.0415   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3587   |   0.4861   |   0.0036   |   0.0040   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/rwc_mdb_p_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_p_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure47"></a>Figure 47: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure48"></a>Figure 48: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_p_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0612   | __0.0005__ | __0.0002__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0612   |   1.0000   |   0.1416   |   0.2366   | __0.0437__ | __0.0099__ | __0.0090__ |   0.0997   | __0.0066__ |
| [percival2014/stem](#percival2014stem)             | __0.0005__ |   0.1416   |   1.0000   |   0.7316   |   0.5534   |   0.1995   |   0.1933   |   0.7949   |   0.2019   |
| [schreiber2014/default](#schreiber2014default)     | __0.0002__ |   0.2366   |   0.7316   |   1.0000   |   0.2832   |   0.0785   |   0.1389   |   0.6315   |   0.1858   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0001__ | __0.0437__ |   0.5534   |   0.2832   |   1.0000   |   0.3195   |   0.4106   |   0.7714   |   0.5333   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0099__ |   0.1995   |   0.0785   |   0.3195   |   1.0000   |   0.7872   |   0.4324   |   0.9944   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0090__ |   0.1933   |   0.1389   |   0.4106   |   0.7872   |   1.0000   |   0.1545   |   0.7832   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0002__ |   0.0997   |   0.7949   |   0.6315   |   0.7714   |   0.4324   |   0.1545   |   1.0000   |   0.4639   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0066__ |   0.2019   |   0.1858   |   0.5333   |   0.9944   |   0.7832   |   0.4639   |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1159   | __0.0006__ | __0.0002__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0002__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1159   |   1.0000   |   0.0596   |   0.1092   | __0.0122__ | __0.0019__ | __0.0023__ | __0.0380__ | __0.0060__ |
| [percival2014/stem](#percival2014stem)             | __0.0006__ |   0.0596   |   1.0000   |   0.7574   |   0.5238   |   0.1809   |   0.1913   |   0.7731   |   0.5049   |
| [schreiber2014/default](#schreiber2014default)     | __0.0002__ |   0.1092   |   0.7574   |   1.0000   |   0.2798   |   0.0774   |   0.1434   |   0.6333   |   0.4237   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0001__ | __0.0122__ |   0.5238   |   0.2798   |   1.0000   |   0.3198   |   0.4277   |   0.7621   |   0.9785   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0019__ |   0.1809   |   0.0774   |   0.3198   |   1.0000   |   0.8136   |   0.4252   |   0.4593   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0023__ |   0.1913   |   0.1434   |   0.4277   |   0.8136   |   1.0000   |   0.1610   |   0.4170   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0002__ | __0.0380__ |   0.7731   |   0.6333   |   0.7621   |   0.4252   |   0.1610   |   1.0000   |   0.8066   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0002__ | __0.0060__ |   0.5049   |   0.4237   |   0.9785   |   0.4593   |   0.4170   |   0.8066   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0015__ |   0.0848   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0007__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.2957   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0015__ | __0.0000__ |   1.0000   |   0.0534   | __0.0001__ | __0.0001__ |   0.1158   |   0.5593   | __0.0199__ |
| [schreiber2014/default](#schreiber2014default)     |   0.0848   |   0.2957   |   0.0534   |   1.0000   | __0.0430__ | __0.0430__ | __0.0483__ |   0.0518   | __0.0462__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0430__ |   1.0000   |   0.2449   |   0.1780   |   0.0565   |   0.3624   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0430__ |   0.2449   |   1.0000   |   0.1780   |   0.0565   |   0.3624   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ | __0.0000__ |   0.1158   | __0.0483__ |   0.1780   |   0.1780   |   1.0000   |   0.1481   |   0.1829   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0007__ | __0.0000__ |   0.5593   |   0.0518   |   0.0565   |   0.0565   |   0.1481   |   1.0000   | __0.0456__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0199__ | __0.0462__ |   0.3624   |   0.3624   |   0.1829   | __0.0456__ |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.1049   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.2862   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   |   0.0640   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1049   |   0.2862   |   0.0640   |   1.0000   | __0.0417__ | __0.0417__ | __0.0429__ | __0.0460__ | __0.0407__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0417__ |   1.0000   |   0.4277   |   0.7770   |   0.3384   |   0.7668   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0417__ |   0.4277   |   1.0000   |   0.7770   |   0.3384   |   0.7669   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0429__ |   0.7770   |   0.7770   |   1.0000   |   0.3747   |   0.4596   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0460__ |   0.3384   |   0.3384   |   0.3747   |   1.0000   | __0.0474__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0407__ |   0.7668   |   0.7669   |   0.4596   | __0.0474__ |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_p_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean AOE<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean AOE<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_aoe1.svg">
</figure>

<a name="figure53"></a>Figure 53: Mean AOE<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure54"></a>Figure 54: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_inter_aoe2.svg">
</figure>

<a name="figure55"></a>Figure 55: Mean AOE<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_0.1_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure56"></a>Figure 56: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_p_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.svg">
</figure>

<a name="figure57"></a>Figure 57: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure58"></a>Figure 58: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.svg">
</figure>

<a name="figure59"></a>Figure 59: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_0.1_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure60"></a>Figure 60: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe1.svg">
</figure>

<a name="figure61"></a>Figure 61: AOE<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure62"></a>Figure 62: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe2.svg">
</figure>

<a name="figure63"></a>Figure 63: AOE<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_0.1_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure64"></a>Figure 64: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_p_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-10-14 08:50. Size L.
