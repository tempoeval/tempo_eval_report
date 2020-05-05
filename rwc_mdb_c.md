---
title: rwc_mdb_c
{:.no_toc}
layout: default
---

# rwc_mdb_c
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'rwc_mdb_c' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'rwc_mdb_c'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
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
| [1.0](#10)                                         |   61   |   37.97   |   300.00   |   112.38   |   64.71   |   47.00   |   0.51   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/rwc_mdb_c_reference_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_c_reference_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_c_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_c_reference_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_c_reference_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_c_reference_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_reference_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_reference_dist.svg "Open Figure") [PDF](figures/rwc_mdb_c_reference_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_c_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/rwc_mdb_c_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/rwc_mdb_c_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/rwc_mdb_c_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/rwc_mdb_c_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/rwc_mdb_c_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/rwc_mdb_c_variation.csv "Download data as CSV") [JSON](data/rwc_mdb_c_variation.json "Download data as JSON") [LATEX](data/rwc_mdb_c_variation.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_variation.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_variation.svg "Open Figure") [PDF](figures/rwc_mdb_c_variation.pdf "Open Figure") [PNG](figures/rwc_mdb_c_variation.png "Open Figure") 

# Estimates for 'rwc_mdb_c'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_c |
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
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   61   |   45.80   |   200.00   |   113.18   |   36.42   |   91.00   |   0.67   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   61   |   70.79   |   198.77   |   135.77   |   24.13   |   100.00   |   0.97   |
| [percival2014/stem](#percival2014stem)             |   61   |   59.23   |   152.00   |   109.66   |   28.15   |   76.00   |   0.84   |
| [schreiber2014/default](#schreiber2014default)     |   61   |   49.94   |   129.40   |   81.56   |   18.87   |   57.00   |   0.92   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   61   |   41.32   |   151.76   |   102.89   |   30.21   |   73.00   |   0.75   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   61   |   41.32   |   151.76   |   95.30   |   29.83   |   64.00   |   0.75   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   61   |   60.00   |   205.00   |   104.85   |   33.15   |   70.00   |   0.82   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   61   |   57.00   |   205.00   |   99.16   |   28.55   |   67.00   |   0.85   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   61   |   64.00   |   205.00   |   108.92   |   33.57   |   77.00   |   0.79   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/rwc_mdb_c_estimates_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_c_estimates_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_dist.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.5082__ | __0.7541__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3607   |   0.6230   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3607   |   0.6393   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3443   |   0.6393   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2623   |   0.6230   |
| [percival2014/stem](#percival2014stem)             |   0.2623   |   0.6721   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2623   |   0.6230   |
| [schreiber2014/default](#schreiber2014default)     |   0.2459   |   0.4590   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2131   |   0.6066   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_c_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_c_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_c_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (30 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C011' 'RM-C015' 'RM-C016' 'RM-C018' 'RM-C020' ...
[CSV](data/rwc_mdb_c_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (45 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C007' 'RM-C008' 'RM-C009' 'RM-C011' 'RM-C012' 'RM-C015' ...
[CSV](data/rwc_mdb_c_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (45 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C012' 'RM-C014' ...
[CSV](data/rwc_mdb_c_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (46 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C005' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C013' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (48 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C012' 'RM-C014' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (45 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C013' 'RM-C014' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (39 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C014' 'RM-C015' 'RM-C016' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (40 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C014' 'RM-C015' 'RM-C016' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (39 differences):*
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C012' 'RM-C014' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 22 items 'correctly' using Accuracy<sub>1</sub>:__
'RM-C001' 'RM-C002' 'RM-C003' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C016' 'RM-C018' 'RM-C021' 'RM-C025\_B' 'RM-C029' ...
[CSV](data/rwc_mdb_c_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (15 differences):*
'RM-C004' 'RM-C006' 'RM-C008' 'RM-C011' 'RM-C015' 'RM-C021' 'RM-C026' 'RM-C029' 'RM-C030' 'RM-C032' 'RM-C038' ...
[CSV](data/rwc_mdb_c_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (23 differences):*
'RM-C003' 'RM-C006' 'RM-C009' 'RM-C011' 'RM-C015' 'RM-C017' 'RM-C018' 'RM-C021' 'RM-C026' 'RM-C028' 'RM-C029' ...
[CSV](data/rwc_mdb_c_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (20 differences):*
'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C015' 'RM-C018' 'RM-C021' 'RM-C026' 'RM-C028' 'RM-C029' 'RM-C030' ...
[CSV](data/rwc_mdb_c_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (33 differences):*
'RM-C001' 'RM-C003' 'RM-C004' 'RM-C005' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C013' 'RM-C015' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (24 differences):*
'RM-C002' 'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C011' 'RM-C018' 'RM-C021' 'RM-C028' 'RM-C029' 'RM-C030' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (23 differences):*
'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C011' 'RM-C018' 'RM-C021' 'RM-C028' 'RM-C029' 'RM-C030' 'RM-C032' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (22 differences):*
'RM-C004' 'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C015' 'RM-C018' 'RM-C021' 'RM-C023\_D' 'RM-C026' 'RM-C029' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (22 differences):*
'RM-C006' 'RM-C008' 'RM-C009' 'RM-C010' 'RM-C015' 'RM-C018' 'RM-C019' 'RM-C021' 'RM-C022' 'RM-C026' 'RM-C029' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (23 differences):*
'RM-C004' 'RM-C006' 'RM-C009' 'RM-C010' 'RM-C011' 'RM-C015' 'RM-C018' 'RM-C021' 'RM-C023\_D' 'RM-C026' 'RM-C028' ...
[CSV](data/rwc_mdb_c_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 7 items 'correctly' using Accuracy<sub>2</sub>:__
'RM-C006' 'RM-C021' 'RM-C029' 'RM-C032' 'RM-C038' 'RM-C041' 'RM-C050' 
[CSV](data/rwc_mdb_c_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0003__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0352__ | __0.0129__ | __0.0225__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0003__ |   1.0000   |   1.0000   |   1.0000   |   0.5488   |   1.0000   |   0.2379   |   0.4049   |   0.2101   |
| [percival2014/stem](#percival2014stem)             | __0.0001__ |   1.0000   |   1.0000   |   1.0000   |   0.5811   |   1.0000   |   0.2101   |   0.3323   |   0.1460   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   1.0000   |   1.0000   |   1.0000   |   0.8036   |   1.0000   |   0.1185   |   0.1094   |   0.1185   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ |   0.5488   |   0.5811   |   0.8036   |   1.0000   |   0.5078   | __0.0490__ |   0.0963   | __0.0225__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0015__ |   1.0000   |   1.0000   |   1.0000   |   0.5078   |   1.0000   |   0.2379   |   0.3323   |   0.2101   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0352__ |   0.2379   |   0.2101   |   0.1185   | __0.0490__ |   0.2379   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0129__ |   0.4049   |   0.3323   |   0.1094   |   0.0963   |   0.3323   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0225__ |   0.2101   |   0.1460   |   0.1185   | __0.0225__ |   0.2101   |   1.0000   |   1.0000   |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0574   |   0.1250   | __0.0000__ | __0.0225__ | __0.0386__ | __0.0391__ |   0.1185   | __0.0386__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0574   |   1.0000   |   0.5488   | __0.0414__ |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   0.1250   |   0.5488   |   1.0000   | __0.0023__ |   0.2891   |   0.4531   |   0.6875   |   0.7539   |   0.5078   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0414__ | __0.0023__ |   1.0000   |   0.0636   | __0.0309__ | __0.0192__ | __0.0192__ | __0.0309__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0225__ |   1.0000   |   0.2891   |   0.0636   |   1.0000   |   1.0000   |   0.7539   |   0.7744   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0386__ |   1.0000   |   0.4531   | __0.0309__ |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0391__ |   1.0000   |   0.6875   | __0.0192__ |   0.7539   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1185   |   1.0000   |   0.7539   | __0.0192__ |   0.7744   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0386__ |   1.0000   |   0.5078   | __0.0309__ |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0930   | __0.6970__ |   -0.0054   |   0.1624   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1349   |   0.7012   |   0.0201   | __0.1206__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.2934   |   0.7507   |   -0.0187   |   0.1842   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0309   |   0.7611   |   0.0087   |   0.1457   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0386   |   0.7807   | __-0.0010__ |   0.1696   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4535   |   0.7861   |   0.0381   |   0.1387   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1063   |   0.8187   |   0.0140   |   0.1568   |
| [percival2014/stem](#percival2014stem)             |   0.1187   |   0.8734   |   -0.0057   |   0.1664   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0085__ |   0.9123   |   0.0072   |   0.1646   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/rwc_mdb_c_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure15"></a>Figure 15: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_c_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure16"></a>Figure 16: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_c_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.8359   | __0.0000__ |   0.1460   | __0.0029__ |   0.1624   | __0.0087__ |   0.5431   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.8359   | __0.0000__ |   1.0000   | __0.0000__ |   0.1572   | __0.0042__ |   0.2477   | __0.0226__ |   0.7061   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0002__ | __0.0126__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1460   | __0.0000__ |   0.1572   | __0.0002__ |   1.0000   |   0.0703   |   0.7045   |   0.6271   |   0.2641   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0029__ | __0.0000__ | __0.0042__ | __0.0126__ |   0.0703   |   1.0000   |   0.0643   |   0.3286   | __0.0087__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1624   | __0.0000__ |   0.2477   | __0.0000__ |   0.7045   |   0.0643   |   1.0000   |   0.2193   |   0.2408   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0087__ | __0.0000__ | __0.0226__ | __0.0000__ |   0.6271   |   0.3286   |   0.2193   |   1.0000   | __0.0368__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5431   | __0.0000__ |   0.7061   | __0.0000__ |   0.2641   | __0.0087__ |   0.2408   | __0.0368__ |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3266   |   0.2351   |   0.1381   |   0.4719   |   0.7159   |   0.2744   |   0.5468   |   0.1713   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3266   |   1.0000   |   0.0739   |   0.0704   |   0.2286   |   0.3296   |   0.1646   |   0.2930   |   0.0695   |
| [percival2014/stem](#percival2014stem)             |   0.2351   |   0.0739   |   1.0000   |   0.6664   |   0.5924   |   0.3951   |   0.7939   |   0.5165   |   0.9890   |
| [schreiber2014/default](#schreiber2014default)     |   0.1381   |   0.0704   |   0.6664   |   1.0000   |   0.3670   |   0.2426   |   0.4824   |   0.2905   |   0.6421   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4719   |   0.2286   |   0.5924   |   0.3670   |   1.0000   |   0.3213   |   0.7293   |   0.9484   |   0.5845   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7159   |   0.3296   |   0.3951   |   0.2426   |   0.3213   |   1.0000   |   0.5096   |   0.8019   |   0.3780   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2744   |   0.1646   |   0.7939   |   0.4824   |   0.7293   |   0.5096   |   1.0000   |   0.5175   |   0.7510   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5468   |   0.2930   |   0.5165   |   0.2905   |   0.9484   |   0.8019   |   0.5175   |   1.0000   |   0.4976   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1713   |   0.0695   |   0.9890   |   0.6421   |   0.5845   |   0.3780   |   0.7510   |   0.4976   |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure21"></a>Figure 21: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure22"></a>Figure 22: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure24"></a>Figure 24: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.4536__ |   0.5515   | __0.0651__ | __0.1034__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5071   | __0.4870__ |   0.0992   |   0.1287   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5370   |   0.5403   |   0.0874   |   0.1169   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5628   |   0.5425   |   0.1028   |   0.1348   |
| [schreiber2014/default](#schreiber2014default)     |   0.5820   |   0.5576   |   0.1243   |   0.1371   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6038   |   0.5630   |   0.0950   |   0.1255   |
| [percival2014/stem](#percival2014stem)             |   0.7049   |   0.5293   |   0.0974   |   0.1350   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7161   |   0.5653   |   0.1007   |   0.1304   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7274   |   0.5428   |   0.0911   |   0.1114   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/rwc_mdb_c_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_c_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure25"></a>Figure 25: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_c_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure26"></a>Figure 26: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_c_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0001__ | __0.0004__ |   0.1084   | __0.0009__ |   0.0536   |   0.0941   |   0.1614   |   0.4128   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0001__ |   1.0000   |   0.7478   |   0.1556   |   0.8881   |   0.1669   | __0.0410__ | __0.0230__ | __0.0034__ |
| [percival2014/stem](#percival2014stem)             | __0.0004__ |   0.7478   |   1.0000   |   0.1238   |   0.8716   |   0.1503   | __0.0332__ | __0.0075__ | __0.0020__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1084   |   0.1556   |   0.1238   |   1.0000   |   0.0862   |   0.7457   |   0.7845   |   0.4463   |   0.3190   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0009__ |   0.8881   |   0.8716   |   0.0862   |   1.0000   |   0.0518   | __0.0365__ | __0.0168__ | __0.0019__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0536   |   0.1669   |   0.1503   |   0.7457   |   0.0518   |   1.0000   |   0.5742   |   0.3473   |   0.1736   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0941   | __0.0410__ | __0.0332__ |   0.7845   | __0.0365__ |   0.5742   |   1.0000   |   0.6406   |   0.2245   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1614   | __0.0230__ | __0.0075__ |   0.4463   | __0.0168__ |   0.3473   |   0.6406   |   1.0000   |   0.6101   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.4128   | __0.0034__ | __0.0020__ |   0.3190   | __0.0019__ |   0.1736   |   0.2245   |   0.6101   |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0429__ | __0.0077__ | __0.0006__ | __0.0212__ | __0.0365__ | __0.0010__ |   0.0668   | __0.0197__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0429__ |   1.0000   |   0.6215   |   0.0569   |   0.5624   |   0.8022   |   0.3617   |   0.8012   |   0.4942   |
| [percival2014/stem](#percival2014stem)             | __0.0077__ |   0.6215   |   1.0000   |   0.1130   |   0.8201   |   0.8532   |   0.5565   |   0.4434   |   0.8805   |
| [schreiber2014/default](#schreiber2014default)     | __0.0006__ |   0.0569   |   0.1130   |   1.0000   |   0.1887   |   0.0809   |   0.2181   | __0.0417__ |   0.1735   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0212__ |   0.5624   |   0.8201   |   0.1887   |   1.0000   |   0.3213   |   0.8765   |   0.3576   |   0.9221   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0365__ |   0.8022   |   0.8532   |   0.0809   |   0.3213   |   1.0000   |   0.5294   |   0.5650   |   0.7697   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0010__ |   0.3617   |   0.5565   |   0.2181   |   0.8765   |   0.5294   |   1.0000   |   0.1147   |   0.6739   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0668   |   0.8012   |   0.4434   | __0.0417__ |   0.3576   |   0.5650   |   0.1147   |   1.0000   |   0.3796   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0197__ |   0.4942   |   0.8805   |   0.1735   |   0.9221   |   0.7697   |   0.6739   |   0.3796   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_c_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_c_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure31"></a>Figure 31: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure32"></a>Figure 32: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure33"></a>Figure 33: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure34"></a>Figure 34: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_c_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-05 19:29. Size L.
