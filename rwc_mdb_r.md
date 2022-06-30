---
title: rwc_mdb_r
{:.no_toc}
layout: default
---

# rwc_mdb_r
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'rwc_mdb_r' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'rwc_mdb_r'

## References

### 0.1

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
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
| **Corpus** | rwc_mdb_r |
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
| [0.1](#01)                                         |   15   |   70.00   |   200.00   |   114.00   |   37.21   |   66.00   |   0.87   |
| [1.0](#10)                                         |   15   |   69.97   |   200.00   |   113.97   |   37.25   |   65.00   |   0.87   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/rwc_mdb_r_reference_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_r_reference_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_r_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_r_reference_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_r_reference_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_r_reference_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_reference_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_reference_dist.svg "Open Figure") [PDF](figures/rwc_mdb_r_reference_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_r_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/rwc_mdb_r_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/rwc_mdb_r_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/rwc_mdb_r_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/rwc_mdb_r_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/rwc_mdb_r_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/rwc_mdb_r_variation.csv "Download data as CSV") [JSON](data/rwc_mdb_r_variation.json "Download data as JSON") [LATEX](data/rwc_mdb_r_variation.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_variation.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_variation.svg "Open Figure") [PDF](figures/rwc_mdb_r_variation.pdf "Open Figure") [PNG](figures/rwc_mdb_r_variation.png "Open Figure") 

# Estimates for 'rwc_mdb_r'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
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
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   15   |   69.77   |   130.43   |   101.28   |   20.83   |   66.00   |   1.00   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   15   |   70.79   |   152.00   |   112.50   |   22.58   |   76.00   |   0.93   |
| [percival2014/stem](#percival2014stem)             |   15   |   70.07   |   130.01   |   101.28   |   20.66   |   66.00   |   1.00   |
| [schreiber2014/default](#schreiber2014default)     |   15   |   74.84   |   139.97   |   107.55   |   18.93   |   70.00   |   1.00   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   15   |   70.02   |   199.98   |   122.22   |   41.44   |   65.00   |   0.80   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   15   |   46.68   |   199.98   |   112.44   |   39.58   |   65.00   |   0.80   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   15   |   70.00   |   200.00   |   108.07   |   32.72   |   66.00   |   0.93   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   15   |   70.00   |   200.00   |   108.13   |   32.72   |   66.00   |   0.93   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   15   |   70.00   |   200.00   |   108.00   |   32.80   |   66.00   |   0.93   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/rwc_mdb_r_estimates_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_r_estimates_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_dist.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 0.1

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.9333__ | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.9333__ | __1.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9333__ | __1.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.9333__ |   0.9333   |
| [percival2014/stem](#percival2014stem)             |   0.8667   | __1.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8667   |   0.9333   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8667   | __1.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7333   | __1.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.7333   |   0.9333   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [0.1](#01) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_r_estimates_0.1_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [0.1](#01) depending on tolerance.

[CSV](data/rwc_mdb_r_estimates_0.1_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [0.1](#01) depending on tolerance.

[CSV](data/rwc_mdb_r_estimates_0.1_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_accuracy2.png "Open Figure") 

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.9333__ | __1.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.9333__ | __1.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9333__ | __1.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.9333__ |   0.9333   |
| [percival2014/stem](#percival2014stem)             |   0.8667   | __1.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8667   |   0.9333   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8667   | __1.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7333   | __1.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.7333   |   0.9333   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_r_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_r_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_r_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[0.1](#01) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2 differences):*
'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (4 differences):*
'RM-R003' 'RM-R004' 'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [percival2014/stem](#percival2014stem) (2 differences):*
'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2014/default](#schreiber2014default) (4 differences):*
'RM-R004' 'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (2 differences):*
'RM-R007' 'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/cnn](#schreiber2018cnn) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/fcn](#schreiber2018fcn) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2 differences):*
'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (4 differences):*
'RM-R003' 'RM-R004' 'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (2 differences):*
'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (4 differences):*
'RM-R004' 'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (2 differences):*
'RM-R007' 'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (1 differences):*
'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[0.1](#01) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[0.1](#01) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker): No differences.*

*[0.1](#01) compared with [percival2014/stem](#percival2014stem): No differences.*

*[0.1](#01) compared with [schreiber2014/default](#schreiber2014default) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[0.1](#01) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[0.1](#01) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018): No differences.*

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default): No differences.*

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker): No differences.*

*[1.0](#10) compared with [percival2014/stem](#percival2014stem): No differences.*

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'RM-R013' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn): No differences.*

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn): No differences.*

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018): No differences.*

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   0.6875   |   0.3750   |   0.2500   |   0.2500   |   0.2500   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   0.6250   |   0.2500   |   0.2500   |   0.2500   |   0.2500   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   0.6875   |   1.0000   |   0.6250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   0.3750   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   0.6875   |   0.3750   |   0.2500   |   0.2500   |   0.2500   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   0.6250   |   0.2500   |   0.2500   |   0.2500   |   0.2500   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   0.6875   |   1.0000   |   0.6250   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   0.3750   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   0.2500   |   1.0000   |   0.2500   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [0.1](#01) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [0.1](#01) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Accuracy<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 0.1

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0390   | __0.1458__ |   0.0277   |   0.1037   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0667   |   0.2494   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0653   |   0.2499   |   0.0014   |   0.0051   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0645   |   0.2501   |   0.0022   |   0.0055   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0943   |   0.2632   |   0.0277   |   0.1037   |
| [percival2014/stem](#percival2014stem)             |   -0.1340   |   0.3404   |   -0.0007   |   0.0016   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1345   |   0.3409   |   -0.0012   |   0.0042   |
| [schreiber2014/default](#schreiber2014default)     |   -0.0391   |   0.4581   |   0.0276   |   0.1037   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0188__ |   0.5198   |   0.0188   |   0.0091   |

<a name="table9"></a>Table 9: Mean OE1/OE2 for estimates compared to version [0.1](#01) ordered by standard deviation.

[CSV](data/rwc_mdb_r_estimates_0.1_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_distribution_oe1.svg">
</figure>

<a name="figure25"></a>Figure 25: OE<sub>1</sub> for estimates compared to version [0.1](#01). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_0.1_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_distribution_oe2.svg">
</figure>

<a name="figure26"></a>Figure 26: OE<sub>2</sub> for estimates compared to version [0.1](#01). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_0.1_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0386   | __0.1461__ |   0.0281   |   0.1034   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0662   |   0.2505   |   0.0004   | __0.0016__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0649   |   0.2509   |   0.0018   |   0.0050   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0641   |   0.2512   |   0.0026   |   0.0056   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0948   |   0.2629   |   0.0281   |   0.1034   |
| [percival2014/stem](#percival2014stem)             |   -0.1336   |   0.3413   | __-0.0002__ |   0.0024   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1341   |   0.3418   |   -0.0008   |   0.0052   |
| [schreiber2014/default](#schreiber2014default)     |   -0.0387   |   0.4587   |   0.0280   |   0.1034   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0192__ |   0.5203   |   0.0192   |   0.0101   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/rwc_mdb_r_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure27"></a>Figure 27: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure28"></a>Figure 28: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1177   |   0.6951   |   0.1984   |   0.0506   |   0.3679   |   0.3157   |   0.3100   |   0.3255   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1177   |   1.0000   |   0.1182   |   0.4494   |   0.6349   |   0.6948   |   0.4915   |   0.4956   |   0.4844   |
| [percival2014/stem](#percival2014stem)             |   0.6951   |   0.1182   |   1.0000   |   0.1973   |   0.0508   |   0.3706   |   0.3202   |   0.3146   |   0.3302   |
| [schreiber2014/default](#schreiber2014default)     |   0.1984   |   0.4494   |   0.1973   |   1.0000   |   0.3340   |   0.9996   |   0.7991   |   0.8058   |   0.7897   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0506   |   0.6349   |   0.0508   |   0.3340   |   1.0000   |   0.1643   |   0.1043   |   0.1077   |   0.1025   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3679   |   0.6948   |   0.3706   |   0.9996   |   0.1643   |   1.0000   |   0.7482   |   0.7534   |   0.7333   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3157   |   0.4915   |   0.3202   |   0.7991   |   0.1043   |   0.7482   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3100   |   0.4956   |   0.3146   |   0.8058   |   0.1077   |   0.7534   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3255   |   0.4844   |   0.3302   |   0.7897   |   0.1025   |   0.7333   |   0.3343   |   0.1671   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1177   |   0.6951   |   0.1984   |   0.0506   |   0.3679   |   0.3157   |   0.3100   |   0.3255   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1177   |   1.0000   |   0.1182   |   0.4494   |   0.6349   |   0.6948   |   0.4915   |   0.4956   |   0.4844   |
| [percival2014/stem](#percival2014stem)             |   0.6951   |   0.1182   |   1.0000   |   0.1973   |   0.0508   |   0.3706   |   0.3202   |   0.3146   |   0.3302   |
| [schreiber2014/default](#schreiber2014default)     |   0.1984   |   0.4494   |   0.1973   |   1.0000   |   0.3340   |   0.9996   |   0.7991   |   0.8058   |   0.7897   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0506   |   0.6349   |   0.0508   |   0.3340   |   1.0000   |   0.1643   |   0.1043   |   0.1077   |   0.1025   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3679   |   0.6948   |   0.3706   |   0.9996   |   0.1643   |   1.0000   |   0.7482   |   0.7534   |   0.7333   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3157   |   0.4915   |   0.3202   |   0.7991   |   0.1043   |   0.7482   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3100   |   0.4956   |   0.3146   |   0.8058   |   0.1077   |   0.7534   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3255   |   0.4844   |   0.3302   |   0.7897   |   0.1025   |   0.7333   |   0.3343   |   0.1671   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6951   |   0.3215   |   0.3201   |   0.3201   |   0.2118   |   0.0772   |   0.3060   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7572   |   0.7550   |   0.7550   | __0.0000__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.6951   | __0.0000__ |   1.0000   |   0.3226   |   0.3212   |   0.3212   |   0.1308   |   0.0680   |   0.1392   |
| [schreiber2014/default](#schreiber2014default)     |   0.3215   |   0.7572   |   0.3226   |   1.0000   |   0.8146   |   0.8146   |   0.3366   |   0.3775   |   0.3365   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |   0.3351   |   0.3760   |   0.3351   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |   0.3351   |   0.3760   |   0.3351   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2118   | __0.0000__ |   0.1308   |   0.3366   |   0.3351   |   0.3351   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0772   | __0.0001__ |   0.0680   |   0.3775   |   0.3760   |   0.3760   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3060   | __0.0000__ |   0.1392   |   0.3365   |   0.3351   |   0.3351   |   0.3343   |   0.1671   |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6951   |   0.3215   |   0.3201   |   0.3201   |   0.2118   |   0.0772   |   0.3060   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7572   |   0.7550   |   0.7550   | __0.0000__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.6951   | __0.0000__ |   1.0000   |   0.3226   |   0.3212   |   0.3212   |   0.1308   |   0.0680   |   0.1392   |
| [schreiber2014/default](#schreiber2014default)     |   0.3215   |   0.7572   |   0.3226   |   1.0000   |   0.8146   |   0.8146   |   0.3366   |   0.3775   |   0.3365   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |   0.3351   |   0.3760   |   0.3351   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |   0.3351   |   0.3760   |   0.3351   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2118   | __0.0000__ |   0.1308   |   0.3366   |   0.3351   |   0.3351   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0772   | __0.0001__ |   0.0680   |   0.3775   |   0.3760   |   0.3760   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3060   | __0.0000__ |   0.1392   |   0.3365   |   0.3351   |   0.3351   |   0.3343   |   0.1671   |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean OE<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean OE<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_oe1.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean OE<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_oe2.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean OE<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.svg">
</figure>

<a name="figure37"></a>Figure 37: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure38"></a>Figure 38: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.svg">
</figure>

<a name="figure39"></a>Figure 39: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure40"></a>Figure 40: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: OE<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe2.svg">
</figure>

<a name="figure43"></a>Figure 43: OE<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 0.1

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0391__ | __0.1457__ |   0.0279   |   0.1036   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0667   |   0.2494   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0680   |   0.2491   |   0.0014   |   0.0051   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0688   |   0.2489   |   0.0022   |   0.0055   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0945   |   0.2631   |   0.0279   |   0.1036   |
| [percival2014/stem](#percival2014stem)             |   0.1350   |   0.3401   |   0.0016   |   0.0006   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1364   |   0.3402   |   0.0031   |   0.0031   |
| [schreiber2014/default](#schreiber2014default)     |   0.2284   |   0.3990   |   0.0285   |   0.1034   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2815   |   0.4374   |   0.0188   |   0.0091   |

<a name="table15"></a>Table 15: Mean AOE1/AOE2 for estimates compared to version [0.1](#01) ordered by mean.

[CSV](data/rwc_mdb_r_estimates_0.1_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_0.1_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_distribution_aoe1.svg">
</figure>

<a name="figure45"></a>Figure 45: AOE<sub>1</sub> for estimates compared to version [0.1](#01). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_0.1_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_distribution_aoe2.svg">
</figure>

<a name="figure46"></a>Figure 46: AOE<sub>2</sub> for estimates compared to version [0.1](#01). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_0.1_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0401__ | __0.1457__ |   0.0288   |   0.1032   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0677   |   0.2501   | __0.0010__ | __0.0013__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0689   |   0.2498   |   0.0023   |   0.0048   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0698   |   0.2496   |   0.0032   |   0.0053   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0954   |   0.2627   |   0.0288   |   0.1032   |
| [percival2014/stem](#percival2014stem)             |   0.1354   |   0.3406   |   0.0021   |   0.0013   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1371   |   0.3406   |   0.0037   |   0.0037   |
| [schreiber2014/default](#schreiber2014default)     |   0.2292   |   0.3992   |   0.0292   |   0.1031   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2824   |   0.4375   |   0.0192   |   0.0101   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/rwc_mdb_r_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_r_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure47"></a>Figure 47: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure48"></a>Figure 48: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_r_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1381   |   0.1035   |   0.2102   |   0.7389   |   0.3605   |   0.3235   |   0.3302   |   0.3142   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1381   |   1.0000   |   0.1334   |   0.4850   |   0.2296   |   0.0816   |   0.0655   |   0.0668   |   0.0637   |
| [percival2014/stem](#percival2014stem)             |   0.1035   |   0.1334   |   1.0000   |   0.2033   |   0.7487   |   0.3688   |   0.3367   |   0.3435   |   0.3272   |
| [schreiber2014/default](#schreiber2014default)     |   0.2102   |   0.4850   |   0.2033   |   1.0000   |   0.3321   |   0.1044   |   0.1029   |   0.1064   |   0.1013   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7389   |   0.2296   |   0.7487   |   0.3321   |   1.0000   |   0.4325   |   0.7972   |   0.8047   |   0.7885   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3605   |   0.0816   |   0.3688   |   0.1044   |   0.4325   |   1.0000   |   0.7203   |   0.7143   |   0.7342   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3235   |   0.0655   |   0.3367   |   0.1029   |   0.7972   |   0.7203   |   1.0000   |   0.6672   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3302   |   0.0668   |   0.3435   |   0.1064   |   0.8047   |   0.7143   |   0.6672   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3142   |   0.0637   |   0.3272   |   0.1013   |   0.7885   |   0.7342   |   0.3343   |   0.1671   |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1386   |   0.1263   |   0.2108   |   0.7375   |   0.3587   |   0.3216   |   0.3275   |   0.3116   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1386   |   1.0000   |   0.1347   |   0.4859   |   0.2296   |   0.0814   |   0.0655   |   0.0666   |   0.0636   |
| [percival2014/stem](#percival2014stem)             |   0.1263   |   0.1347   |   1.0000   |   0.2050   |   0.7460   |   0.3658   |   0.3333   |   0.3392   |   0.3231   |
| [schreiber2014/default](#schreiber2014default)     |   0.2108   |   0.4859   |   0.2050   |   1.0000   |   0.3317   |   0.1040   |   0.1026   |   0.1060   |   0.1009   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7375   |   0.2296   |   0.7460   |   0.3317   |   1.0000   |   0.4315   |   0.7971   |   0.8038   |   0.7877   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3587   |   0.0814   |   0.3658   |   0.1040   |   0.4315   |   1.0000   |   0.7193   |   0.7144   |   0.7343   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3216   |   0.0655   |   0.3333   |   0.1026   |   0.7971   |   0.7193   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3275   |   0.0666   |   0.3392   |   0.1060   |   0.8038   |   0.7144   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3116   |   0.0636   |   0.3231   |   0.1009   |   0.7877   |   0.7343   |   0.3343   |   0.1671   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1035   |   0.3696   |   0.3776   |   0.3776   |   0.2826   |   0.7648   | __0.0018__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7260   |   0.7371   |   0.7371   | __0.0001__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1035   | __0.0000__ |   1.0000   |   0.3440   |   0.3517   |   0.3517   |   0.8988   |   0.4585   | __0.0073__ |
| [schreiber2014/default](#schreiber2014default)     |   0.3696   |   0.7260   |   0.3440   |   1.0000   |   0.1994   |   0.1994   |   0.3239   |   0.3647   |   0.3243   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3776   |   0.7371   |   0.3517   |   0.1994   |   1.0000   |   1.0000   |   0.3316   |   0.3726   |   0.3317   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3776   |   0.7371   |   0.3517   |   0.1994   |   1.0000   |   1.0000   |   0.3316   |   0.3726   |   0.3317   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2826   | __0.0001__ |   0.8988   |   0.3239   |   0.3316   |   0.3316   |   1.0000   |   0.6672   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7648   | __0.0001__ |   0.4585   |   0.3647   |   0.3726   |   0.3726   |   0.6672   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0018__ | __0.0000__ | __0.0073__ |   0.3243   |   0.3317   |   0.3317   |   0.3343   |   0.1671   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1263   |   0.3713   |   0.3845   |   0.3845   |   0.2639   |   0.6366   | __0.0020__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7314   |   0.7496   |   0.7496   | __0.0000__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1263   | __0.0000__ |   1.0000   |   0.3473   |   0.3599   |   0.3599   |   0.8454   |   0.7263   | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.3713   |   0.7314   |   0.3473   |   1.0000   | __0.0169__ | __0.0169__ |   0.3188   |   0.3594   |   0.3196   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3845   |   0.7496   |   0.3599   | __0.0169__ |   1.0000   |   1.0000   |   0.3313   |   0.3722   |   0.3314   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3845   |   0.7496   |   0.3599   | __0.0169__ |   1.0000   |   1.0000   |   0.3313   |   0.3722   |   0.3314   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2639   | __0.0000__ |   0.8454   |   0.3188   |   0.3313   |   0.3313   |   1.0000   |   0.7148   |   0.3343   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6366   | __0.0001__ |   0.7263   |   0.3594   |   0.3722   |   0.3722   |   0.7148   |   1.0000   |   0.1671   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0020__ | __0.0000__ | __0.0000__ |   0.3196   |   0.3314   |   0.3314   |   0.3343   |   0.1671   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean AOE<sub>1</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 0.1 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean AOE<sub>2</sub> compared to version [0.1](#01) for tracks with c<sub>var</sub> < τ based on beat annotations from [0.1](#01).

[CSV](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_aoe1.svg">
</figure>

<a name="figure53"></a>Figure 53: Mean AOE<sub>1</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure54"></a>Figure 54: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_inter_aoe2.svg">
</figure>

<a name="figure55"></a>Figure 55: Mean AOE<sub>2</sub> for estimates compared to version [0.1](#01) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_0.1_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure56"></a>Figure 56: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_r_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 0.1

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.svg">
</figure>

<a name="figure57"></a>Figure 57: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure58"></a>Figure 58: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 0.1

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [0.1](#01).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.svg">
</figure>

<a name="figure59"></a>Figure 59: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [0.1](#01). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_0.1_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure60"></a>Figure 60: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe1.svg">
</figure>

<a name="figure61"></a>Figure 61: AOE<sub>1</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure62"></a>Figure 62: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 0.1

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe2.svg">
</figure>

<a name="figure63"></a>Figure 63: AOE<sub>2</sub> of estimates compared to version [0.1](#01) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_0.1_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure64"></a>Figure 64: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_r_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.1 on 2022-06-29 18:55. Size L.
