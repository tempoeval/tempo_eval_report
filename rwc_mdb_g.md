---
title: rwc_mdb_g
{:.no_toc}
layout: default
---

# rwc_mdb_g
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'rwc_mdb_g' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'rwc_mdb_g'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
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
| [1.0](#10)                                         |   102   |   30.15   |   235.81   |   103.57   |   34.17   |   73.00   |   0.75   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/rwc_mdb_g_reference_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_g_reference_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_g_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_g_reference_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_g_reference_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_g_reference_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_reference_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_reference_dist.svg "Open Figure") [PDF](figures/rwc_mdb_g_reference_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_g_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/rwc_mdb_g_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/rwc_mdb_g_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/rwc_mdb_g_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/rwc_mdb_g_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/rwc_mdb_g_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/rwc_mdb_g_variation.csv "Download data as CSV") [JSON](data/rwc_mdb_g_variation.json "Download data as JSON") [LATEX](data/rwc_mdb_g_variation.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_variation.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_variation.svg "Open Figure") [PDF](figures/rwc_mdb_g_variation.pdf "Open Figure") [PNG](figures/rwc_mdb_g_variation.png "Open Figure") 

# Estimates for 'rwc_mdb_g'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_g |
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
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   102   |   41.10   |   214.29   |   98.98   |   31.83   |   70.00   |   0.74   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   102   |   65.42   |   198.77   |   126.49   |   24.86   |   90.00   |   0.92   |
| [percival2014/stem](#percival2014stem)             |   102   |   64.60   |   147.66   |   102.56   |   22.32   |   70.00   |   0.94   |
| [schreiber2014/default](#schreiber2014default)     |   102   |   58.18   |   145.06   |   100.44   |   23.32   |   65.00   |   0.88   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   102   |   40.53   |   203.77   |   104.51   |   26.90   |   73.00   |   0.87   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   102   |   40.53   |   203.77   |   102.90   |   28.78   |   73.00   |   0.84   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   102   |   50.00   |   216.00   |   108.29   |   25.92   |   73.00   |   0.93   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   102   |   41.00   |   208.00   |   106.76   |   28.52   |   74.00   |   0.84   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   102   |   55.00   |   204.00   |   106.61   |   25.89   |   73.00   |   0.88   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/rwc_mdb_g_estimates_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_g_estimates_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_dist.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.7255__ |   0.8431   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7059   |   0.8333   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6961   |   0.8137   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6863   |   0.8235   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6863   |   0.8137   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6667   | __0.8824__ |
| [percival2014/stem](#percival2014stem)             |   0.6569   |   0.8431   |
| [schreiber2014/default](#schreiber2014default)     |   0.6471   |   0.7941   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5882   |   0.7647   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_g_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_g_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_g_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (34 differences):*
'RM-G003' 'RM-G011' 'RM-G012' 'RM-G032' 'RM-G037' 'RM-G039' 'RM-G041' 'RM-G043' 'RM-G046' 'RM-G047' 'RM-G048' ...
[CSV](data/rwc_mdb_g_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (42 differences):*
'RM-G002' 'RM-G005' 'RM-G006' 'RM-G032' 'RM-G033' 'RM-G037' 'RM-G038' 'RM-G044' 'RM-G045' 'RM-G046' 'RM-G047' ...
[CSV](data/rwc_mdb_g_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (35 differences):*
'RM-G010' 'RM-G011' 'RM-G021' 'RM-G032' 'RM-G037' 'RM-G043' 'RM-G046' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G052' ...
[CSV](data/rwc_mdb_g_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (36 differences):*
'RM-G028' 'RM-G032' 'RM-G037' 'RM-G043' 'RM-G046' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G051' 'RM-G052' 'RM-G053' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (31 differences):*
'RM-G029' 'RM-G032' 'RM-G037' 'RM-G043' 'RM-G045' 'RM-G046' 'RM-G047' 'RM-G050' 'RM-G052' 'RM-G053' 'RM-G057' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (32 differences):*
'RM-G029' 'RM-G032' 'RM-G037' 'RM-G043' 'RM-G045' 'RM-G046' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G052' 'RM-G053' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (30 differences):*
'RM-G029' 'RM-G030' 'RM-G032' 'RM-G037' 'RM-G045' 'RM-G046' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G052' 'RM-G056' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (28 differences):*
'RM-G029' 'RM-G032' 'RM-G033' 'RM-G037' 'RM-G045' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G052' 'RM-G056' 'RM-G058\_A' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (32 differences):*
'RM-G029' 'RM-G032' 'RM-G033' 'RM-G037' 'RM-G045' 'RM-G046' 'RM-G047' 'RM-G048' 'RM-G050' 'RM-G052' 'RM-G056' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 14 items 'correctly' using Accuracy<sub>1</sub>:__
'RM-G032' 'RM-G037' 'RM-G047' 'RM-G052' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G063' 'RM-G079' 'RM-G085' 'RM-G089' ...
[CSV](data/rwc_mdb_g_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (12 differences):*
'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G079' 'RM-G085' 'RM-G089' 'RM-G093' 'RM-G095' 'RM-G097' ...
[CSV](data/rwc_mdb_g_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (24 differences):*
'RM-G046' 'RM-G051' 'RM-G052' 'RM-G058\_A' 'RM-G058\_B' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G077' 'RM-G079' ...
[CSV](data/rwc_mdb_g_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (16 differences):*
'RM-G056' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G063' 'RM-G077' 'RM-G079' 'RM-G085' 'RM-G086' 'RM-G087' 'RM-G088' ...
[CSV](data/rwc_mdb_g_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (21 differences):*
'RM-G028' 'RM-G050' 'RM-G051' 'RM-G053' 'RM-G057' 'RM-G058\_A' 'RM-G058\_C' 'RM-G067' 'RM-G068' 'RM-G075' 'RM-G079' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (19 differences):*
'RM-G052' 'RM-G053' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G068' 'RM-G079' 'RM-G084' 'RM-G085' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (19 differences):*
'RM-G052' 'RM-G053' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G068' 'RM-G079' 'RM-G084' 'RM-G085' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (17 differences):*
'RM-G056' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G068' 'RM-G079' 'RM-G085' 'RM-G086' 'RM-G087' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (16 differences):*
'RM-G050' 'RM-G056' 'RM-G058\_A' 'RM-G058\_C' 'RM-G061' 'RM-G063' 'RM-G079' 'RM-G084' 'RM-G085' 'RM-G086' 'RM-G087' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (18 differences):*
'RM-G056' 'RM-G058\_A' 'RM-G058\_C' 'RM-G060' 'RM-G061' 'RM-G063' 'RM-G079' 'RM-G080' 'RM-G084' 'RM-G085' 'RM-G086' ...
[CSV](data/rwc_mdb_g_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 5 items 'correctly' using Accuracy<sub>2</sub>:__
'RM-G058\_A' 'RM-G058\_C' 'RM-G079' 'RM-G095' 'RM-G097' 
[CSV](data/rwc_mdb_g_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2295   |   1.0000   |   0.8238   |   0.6776   |   0.8318   |   0.5413   |   0.3269   |   0.8450   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2295   |   1.0000   |   0.2649   |   0.3616   | __0.0433__ |   0.0639   | __0.0357__ | __0.0066__ |   0.0755   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.2649   |   1.0000   |   1.0000   |   0.5034   |   0.6291   |   0.3018   |   0.1671   |   0.6476   |
| [schreiber2014/default](#schreiber2014default)     |   0.8238   |   0.3616   |   1.0000   |   1.0000   |   0.3323   |   0.4545   |   0.2863   |   0.1338   |   0.4807   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6776   | __0.0433__ |   0.5034   |   0.3323   |   1.0000   |   1.0000   |   1.0000   |   0.5488   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8318   |   0.0639   |   0.6291   |   0.4545   |   1.0000   |   1.0000   |   0.7539   |   0.3437   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5413   | __0.0357__ |   0.3018   |   0.2863   |   1.0000   |   0.7539   |   1.0000   |   0.7266   |   0.7266   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3269   | __0.0066__ |   0.1671   |   0.1338   |   0.5488   |   0.3437   |   0.7266   |   1.0000   |   0.2188   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8450   |   0.0755   |   0.6476   |   0.4807   |   1.0000   |   1.0000   |   0.7266   |   0.2188   |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0042__ |   0.2891   | __0.0352__ | __0.0391__ | __0.0391__ |   0.1250   |   0.3437   | __0.0312__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0042__ |   1.0000   |   0.0574   |   0.6636   |   0.3018   |   0.3018   |   0.1185   |   0.0768   |   0.1796   |
| [percival2014/stem](#percival2014stem)             |   0.2891   |   0.0574   |   1.0000   |   0.3593   |   0.5488   |   0.5488   |   1.0000   |   1.0000   |   0.6875   |
| [schreiber2014/default](#schreiber2014default)     | __0.0352__ |   0.6636   |   0.3593   |   1.0000   |   0.8036   |   0.8036   |   0.4807   |   0.3323   |   0.6072   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0391__ |   0.3018   |   0.5488   |   0.8036   |   1.0000   |   1.0000   |   0.6875   |   0.5078   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0391__ |   0.3018   |   0.5488   |   0.8036   |   1.0000   |   1.0000   |   0.6875   |   0.5078   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1250   |   0.1185   |   1.0000   |   0.4807   |   0.6875   |   0.6875   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3437   |   0.0768   |   1.0000   |   0.3323   |   0.5078   |   0.5078   |   1.0000   |   1.0000   |   0.6875   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0312__ |   0.1796   |   0.6875   |   0.6072   |   1.0000   |   1.0000   |   1.0000   |   0.6875   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0752   | __0.4131__ | __0.0008__ | __0.0814__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0842   |   0.4711   |   0.0098   |   0.1056   |
| [schreiber2014/default](#schreiber2014default)     | __-0.0001__ |   0.4740   |   0.0040   |   0.1273   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0456   |   0.4949   |   0.0064   |   0.1231   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1101   |   0.5001   |   0.0064   |   0.1046   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0105   |   0.5231   |   0.0105   |   0.1229   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3452   |   0.5231   |   0.0477   |   0.1317   |
| [percival2014/stem](#percival2014stem)             |   0.0358   |   0.5328   |   0.0104   |   0.1080   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0604   |   0.5891   |   0.0042   |   0.0864   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/rwc_mdb_g_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure15"></a>Figure 15: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_g_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure16"></a>Figure 16: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_g_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.0595   |   0.1988   | __0.0481__ |   0.1903   | __0.0004__ | __0.0121__ | __0.0033__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.0595   | __0.0000__ |   1.0000   |   0.3348   |   0.8249   |   0.5785   | __0.0446__ |   0.3918   |   0.2488   |
| [schreiber2014/default](#schreiber2014default)     |   0.1988   | __0.0000__ |   0.3348   |   1.0000   |   0.2919   |   0.8112   | __0.0034__ |   0.0531   | __0.0173__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0481__ | __0.0000__ |   0.8249   |   0.2919   |   1.0000   |   0.1214   |   0.0899   |   0.4587   |   0.2787   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1903   | __0.0000__ |   0.5785   |   0.8112   |   0.1214   |   1.0000   | __0.0132__ |   0.1096   | __0.0495__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0004__ | __0.0000__ | __0.0446__ | __0.0034__ |   0.0899   | __0.0132__ |   1.0000   |   0.3222   |   0.2773   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0121__ | __0.0000__ |   0.3918   |   0.0531   |   0.4587   |   0.1096   |   0.3222   |   1.0000   |   0.7272   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0033__ | __0.0000__ |   0.2488   | __0.0173__ |   0.2787   | __0.0495__ |   0.2773   |   0.7272   |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0035__ |   0.4700   |   0.9906   |   0.8261   |   0.5411   |   0.8412   |   0.7104   |   0.5678   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0035__ |   1.0000   | __0.0160__ | __0.0229__ | __0.0258__ | __0.0396__ | __0.0129__ | __0.0016__ | __0.0263__ |
| [percival2014/stem](#percival2014stem)             |   0.4700   | __0.0160__ |   1.0000   |   0.7159   |   0.7689   |   0.9975   |   0.7057   |   0.2997   |   0.9558   |
| [schreiber2014/default](#schreiber2014default)     |   0.9906   | __0.0229__ |   0.7159   |   1.0000   |   0.8764   |   0.6800   |   0.8712   |   0.8531   |   0.6970   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8261   | __0.0258__ |   0.7689   |   0.8764   |   1.0000   |   0.3197   |   0.9967   |   0.6776   |   0.6919   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5411   | __0.0396__ |   0.9975   |   0.6800   |   0.3197   |   1.0000   |   0.7659   |   0.4653   |   0.9353   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8412   | __0.0129__ |   0.7057   |   0.8712   |   0.9967   |   0.7659   |   1.0000   |   0.6564   |   0.7872   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7104   | __0.0016__ |   0.2997   |   0.8531   |   0.6776   |   0.4653   |   0.6564   |   1.0000   |   0.4167   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5678   | __0.0263__ |   0.9558   |   0.6970   |   0.6919   |   0.9353   |   0.7872   |   0.4167   |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure21"></a>Figure 21: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure22"></a>Figure 22: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure24"></a>Figure 24: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.1925__ | __0.3731__ |   0.0349   | __0.0735__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2344   |   0.4172   |   0.0435   |   0.0967   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2368   |   0.4370   |   0.0504   |   0.1124   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2425   |   0.4510   |   0.0421   |   0.0959   |
| [schreiber2014/default](#schreiber2014default)     |   0.2524   |   0.4012   |   0.0583   |   0.1132   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2629   |   0.4524   |   0.0505   |   0.1126   |
| [percival2014/stem](#percival2014stem)             |   0.2844   |   0.4520   |   0.0412   |   0.1003   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3251   |   0.4950   | __0.0322__ |   0.0803   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3748   |   0.5023   |   0.0770   |   0.1170   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/rwc_mdb_g_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_g_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure25"></a>Figure 25: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_g_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure26"></a>Figure 26: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_g_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3962   |   0.3668   |   0.0990   |   0.0873   |   0.2150   |   0.0840   | __0.0095__ |   0.0597   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3962   |   1.0000   |   0.0746   | __0.0202__ | __0.0057__ | __0.0244__ | __0.0066__ | __0.0001__ | __0.0037__ |
| [percival2014/stem](#percival2014stem)             |   0.3668   |   0.0746   |   1.0000   |   0.3532   |   0.2590   |   0.6076   |   0.2533   | __0.0316__ |   0.2058   |
| [schreiber2014/default](#schreiber2014default)     |   0.0990   | __0.0202__ |   0.3532   |   1.0000   |   0.7043   |   0.7963   |   0.7935   |   0.0996   |   0.5974   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0873   | __0.0057__ |   0.2590   |   0.7043   |   1.0000   |   0.1825   |   0.8793   |   0.2486   |   0.9464   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2150   | __0.0244__ |   0.6076   |   0.7963   |   0.1825   |   1.0000   |   0.5888   |   0.0675   |   0.4276   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0840   | __0.0066__ |   0.2533   |   0.7935   |   0.8793   |   0.5888   |   1.0000   |   0.1347   |   0.7319   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0095__ | __0.0001__ | __0.0316__ |   0.0996   |   0.2486   |   0.0675   |   0.1347   |   1.0000   |   0.0830   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0597   | __0.0037__ |   0.2058   |   0.5974   |   0.9464   |   0.4276   |   0.7319   |   0.0830   |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.2501   | __0.0165__ | __0.0075__ | __0.0074__ |   0.2462   |   0.7279   | __0.0215__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0006__ |   0.1957   | __0.0259__ | __0.0265__ | __0.0021__ | __0.0002__ | __0.0032__ |
| [percival2014/stem](#percival2014stem)             |   0.2501   | __0.0006__ |   1.0000   |   0.1890   |   0.3630   |   0.3590   |   0.9097   |   0.4176   |   0.7551   |
| [schreiber2014/default](#schreiber2014default)     | __0.0165__ |   0.1957   |   0.1890   |   1.0000   |   0.4552   |   0.4613   |   0.1545   | __0.0267__ |   0.1557   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0075__ | __0.0259__ |   0.3630   |   0.4552   |   1.0000   |   0.3197   |   0.2793   |   0.1038   |   0.3444   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0074__ | __0.0265__ |   0.3590   |   0.4613   |   0.3197   |   1.0000   |   0.2735   |   0.1022   |   0.3396   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2462   | __0.0021__ |   0.9097   |   0.1545   |   0.2793   |   0.2735   |   1.0000   |   0.3162   |   0.8534   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7279   | __0.0002__ |   0.4176   | __0.0267__ |   0.1038   |   0.1022   |   0.3162   |   1.0000   |   0.2246   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0215__ | __0.0032__ |   0.7551   |   0.1557   |   0.3444   |   0.3396   |   0.8534   |   0.2246   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_g_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_g_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure31"></a>Figure 31: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure32"></a>Figure 32: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure33"></a>Figure 33: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure34"></a>Figure 34: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_g_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-10-14 08:45. Size L.
