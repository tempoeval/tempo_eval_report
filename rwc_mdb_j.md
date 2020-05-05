---
title: rwc_mdb_j
{:.no_toc}
layout: default
---

# rwc_mdb_j
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'rwc_mdb_j' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'rwc_mdb_j'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
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
| [1.0](#10)                                         |   50   |   37.27   |   157.89   |   90.71   |   27.53   |   61.00   |   0.76   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/rwc_mdb_j_reference_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_j_reference_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_j_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_j_reference_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_j_reference_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_j_reference_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_reference_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_reference_dist.svg "Open Figure") [PDF](figures/rwc_mdb_j_reference_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_j_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/rwc_mdb_j_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/rwc_mdb_j_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/rwc_mdb_j_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/rwc_mdb_j_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/rwc_mdb_j_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/rwc_mdb_j_variation.csv "Download data as CSV") [JSON](data/rwc_mdb_j_variation.json "Download data as JSON") [LATEX](data/rwc_mdb_j_variation.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_variation.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_variation.svg "Open Figure") [PDF](figures/rwc_mdb_j_variation.pdf "Open Figure") [PNG](figures/rwc_mdb_j_variation.png "Open Figure") 

# Estimates for 'rwc_mdb_j'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_j |
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
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   50   |   54.05   |   162.16   |   99.10   |   28.77   |   69.00   |   0.76   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   50   |   89.10   |   191.41   |   128.66   |   23.63   |   84.00   |   0.96   |
| [percival2014/stem](#percival2014stem)             |   50   |   54.11   |   143.56   |   96.14   |   24.18   |   68.00   |   0.86   |
| [schreiber2014/default](#schreiber2014default)     |   50   |   55.75   |   141.82   |   91.30   |   21.66   |   62.00   |   0.88   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   50   |   58.83   |   196.67   |   101.39   |   25.54   |   67.00   |   0.92   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   50   |   41.72   |   206.76   |   98.04   |   27.70   |   66.00   |   0.88   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   50   |   54.00   |   216.00   |   114.68   |   43.19   |   65.00   |   0.64   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   50   |   43.00   |   208.00   |   104.68   |   35.74   |   73.00   |   0.78   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   50   |   56.00   |   208.00   |   109.52   |   33.08   |   73.00   |   0.78   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/rwc_mdb_j_estimates_basic_stats.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_basic_stats.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/rwc_mdb_j_estimates_dist.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_dist.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_dist.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_dist.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_dist.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.7800__ | __0.9800__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.7400   | __0.9800__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6200   |   0.8800   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6200   |   0.8800   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6000   |   0.8600   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5800   |   0.8600   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5800   |   0.9000   |
| [schreiber2014/default](#schreiber2014default)     |   0.5600   |   0.7400   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4800   |   0.9000   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/rwc_mdb_j_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_j_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/rwc_mdb_j_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (13 differences):*
'RM-J001' 'RM-J006' 'RM-J008' 'RM-J009' 'RM-J018' 'RM-J028' 'RM-J031' 'RM-J038' 'RM-J040' 'RM-J044' 'RM-J045' ...
[CSV](data/rwc_mdb_j_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (26 differences):*
'RM-J001' 'RM-J002' 'RM-J003' 'RM-J004' 'RM-J006' 'RM-J007' 'RM-J008' 'RM-J009' 'RM-J012' 'RM-J013' 'RM-J014' ...
[CSV](data/rwc_mdb_j_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (11 differences):*
'RM-J004' 'RM-J009' 'RM-J010' 'RM-J012' 'RM-J031' 'RM-J032' 'RM-J038' 'RM-J040' 'RM-J044' 'RM-J046' 'RM-J050' ...
[CSV](data/rwc_mdb_j_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (22 differences):*
'RM-J005' 'RM-J008' 'RM-J009' 'RM-J010' 'RM-J011' 'RM-J013' 'RM-J015' 'RM-J019' 'RM-J020' 'RM-J022' 'RM-J023' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (19 differences):*
'RM-J002' 'RM-J005' 'RM-J008' 'RM-J009' 'RM-J011' 'RM-J012' 'RM-J017' 'RM-J022' 'RM-J025' 'RM-J027' 'RM-J030' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (19 differences):*
'RM-J002' 'RM-J005' 'RM-J008' 'RM-J009' 'RM-J015' 'RM-J016' 'RM-J017' 'RM-J022' 'RM-J025' 'RM-J027' 'RM-J030' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (20 differences):*
'RM-J001' 'RM-J003' 'RM-J004' 'RM-J006' 'RM-J009' 'RM-J015' 'RM-J016' 'RM-J017' 'RM-J021' 'RM-J024' 'RM-J026' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (21 differences):*
'RM-J001' 'RM-J003' 'RM-J006' 'RM-J008' 'RM-J009' 'RM-J015' 'RM-J016' 'RM-J017' 'RM-J020' 'RM-J021' 'RM-J024' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (21 differences):*
'RM-J001' 'RM-J002' 'RM-J004' 'RM-J006' 'RM-J008' 'RM-J009' 'RM-J021' 'RM-J022' 'RM-J024' 'RM-J026' 'RM-J028' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 5 items 'correctly' using Accuracy<sub>1</sub>:__
'RM-J009' 'RM-J031' 'RM-J038' 'RM-J040' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1 differences):*
'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (5 differences):*
'RM-J013' 'RM-J014' 'RM-J018' 'RM-J031' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (1 differences):*
'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (13 differences):*
'RM-J005' 'RM-J009' 'RM-J011' 'RM-J013' 'RM-J015' 'RM-J019' 'RM-J020' 'RM-J022' 'RM-J023' 'RM-J025' 'RM-J030' ...
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (6 differences):*
'RM-J005' 'RM-J025' 'RM-J030' 'RM-J035' 'RM-J036' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (6 differences):*
'RM-J005' 'RM-J025' 'RM-J030' 'RM-J035' 'RM-J036' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (7 differences):*
'RM-J001' 'RM-J015' 'RM-J030' 'RM-J031' 'RM-J035' 'RM-J036' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (7 differences):*
'RM-J003' 'RM-J020' 'RM-J030' 'RM-J031' 'RM-J035' 'RM-J036' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (5 differences):*
'RM-J002' 'RM-J030' 'RM-J035' 'RM-J036' 'RM-J044' 
[CSV](data/rwc_mdb_j_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0044__ |   0.7539   |   0.0636   |   0.2379   |   0.2379   |   0.1671   | __0.0386__ |   0.0574   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0044__ |   1.0000   | __0.0015__ |   0.5716   |   0.1892   |   0.2100   |   0.2863   |   0.3833   |   0.3323   |
| [percival2014/stem](#percival2014stem)             |   0.7539   | __0.0015__ |   1.0000   | __0.0127__ |   0.0574   |   0.0768   |   0.0636   | __0.0309__ | __0.0213__ |
| [schreiber2014/default](#schreiber2014default)     |   0.0636   |   0.5716   | __0.0127__ |   1.0000   |   0.5811   |   0.5811   |   0.8318   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2379   |   0.1892   |   0.0574   |   0.5811   |   1.0000   |   1.0000   |   1.0000   |   0.8145   |   0.7905   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2379   |   0.2100   |   0.0768   |   0.5811   |   1.0000   |   1.0000   |   1.0000   |   0.7905   |   0.7905   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1671   |   0.2863   |   0.0636   |   0.8318   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0386__ |   0.3833   | __0.0309__ |   1.0000   |   0.8145   |   0.7905   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0574   |   0.3323   | __0.0213__ |   1.0000   |   0.7905   |   0.7905   |   1.0000   |   1.0000   |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1250   |   1.0000   | __0.0018__ |   0.0625   |   0.0625   | __0.0312__ | __0.0312__ |   0.1250   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1250   |   1.0000   |   0.1250   |   0.0768   |   1.0000   |   1.0000   |   0.7266   |   0.7266   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.1250   |   1.0000   | __0.0018__ |   0.0625   |   0.0625   | __0.0312__ | __0.0312__ |   0.1250   |
| [schreiber2014/default](#schreiber2014default)     | __0.0018__ |   0.0768   | __0.0018__ |   1.0000   | __0.0391__ | __0.0391__ |   0.1460   |   0.1460   | __0.0386__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0625   |   1.0000   |   0.0625   | __0.0391__ |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0625   |   1.0000   |   0.0625   | __0.0391__ |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0312__ |   0.7266   | __0.0312__ |   0.1460   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   0.6250   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0312__ |   0.7266   | __0.0312__ |   0.1460   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   0.6250   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1250   |   1.0000   |   0.1250   | __0.0386__ |   1.0000   |   1.0000   |   0.6250   |   0.6250   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure11"></a>Figure 11: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             |   0.1045   | __0.4670__ | __0.0045__ | __0.0341__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1331   |   0.4829   |   -0.0069   |   0.0590   |
| [schreiber2014/default](#schreiber2014default)     | __0.0360__ |   0.5049   |   0.0243   |   0.1471   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2768   |   0.5208   |   0.0168   |   0.0846   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1856   |   0.5323   |   0.0456   |   0.1256   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5487   |   0.5478   |   0.0253   |   0.1185   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1256   |   0.5861   |   0.0373   |   0.1096   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3095   |   0.5991   |   0.0461   |   0.1351   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1967   |   0.6355   |   0.0250   |   0.1027   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/rwc_mdb_j_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure15"></a>Figure 15: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_j_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure16"></a>Figure 16: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_j_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6639   |   0.1468   |   0.5038   |   0.9287   |   0.0522   |   0.3398   | __0.0277__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0049__ | __0.0000__ | __0.0003__ |
| [percival2014/stem](#percival2014stem)             |   0.6639   | __0.0000__ |   1.0000   |   0.2219   |   0.2178   |   0.7865   | __0.0115__ |   0.2567   | __0.0147__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1468   | __0.0000__ |   0.2219   |   1.0000   | __0.0395__ |   0.2117   | __0.0004__ | __0.0126__ | __0.0008__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5038   | __0.0000__ |   0.2178   | __0.0395__ |   1.0000   |   0.1824   |   0.1760   |   0.8964   |   0.2289   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9287   | __0.0000__ |   0.7865   |   0.2117   |   0.1824   |   1.0000   | __0.0365__ |   0.3548   |   0.0603   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0522   | __0.0049__ | __0.0115__ | __0.0004__ |   0.1760   | __0.0365__ |   1.0000   |   0.0989   |   0.6604   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3398   | __0.0000__ |   0.2567   | __0.0126__ |   0.8964   |   0.3548   |   0.0989   |   1.0000   |   0.2508   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0277__ | __0.0003__ | __0.0147__ | __0.0008__ |   0.2289   |   0.0603   |   0.6604   |   0.2508   |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1200   |   0.3852   |   0.1713   | __0.0114__ | __0.0161__ | __0.0364__ | __0.0293__ |   0.0620   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1200   |   1.0000   |   0.2209   |   0.9690   |   0.4165   |   0.6080   |   0.3352   |   0.9879   |   0.6908   |
| [percival2014/stem](#percival2014stem)             |   0.3852   |   0.2209   |   1.0000   |   0.3629   | __0.0288__ | __0.0456__ | __0.0207__ |   0.2299   |   0.3893   |
| [schreiber2014/default](#schreiber2014default)     |   0.1713   |   0.9690   |   0.3629   |   1.0000   |   0.1588   |   0.4025   |   0.2925   |   0.9732   |   0.6831   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0114__ |   0.4165   | __0.0288__ |   0.1588   |   1.0000   |   0.3222   |   0.9815   |   0.2546   |   0.0523   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0161__ |   0.6080   | __0.0456__ |   0.4025   |   0.3222   |   1.0000   |   0.6300   |   0.4082   |   0.0798   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0364__ |   0.3352   | __0.0207__ |   0.2925   |   0.9815   |   0.6300   |   1.0000   |   0.2277   |   0.1144   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0293__ |   0.9879   |   0.2299   |   0.9732   |   0.2546   |   0.4082   |   0.2277   |   1.0000   |   0.3672   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0620   |   0.6908   |   0.3893   |   0.6831   |   0.0523   |   0.0798   |   0.1144   |   0.3672   |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure21"></a>Figure 21: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure22"></a>Figure 22: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure24"></a>Figure 24: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.2284__ |   0.4206   | __0.0109__ | __0.0326__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2604   |   0.4278   |   0.0168   |   0.0569   |
| [schreiber2014/default](#schreiber2014default)     |   0.2930   | __0.4127__ |   0.0807   |   0.1254   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3472   |   0.4442   |   0.0538   |   0.1223   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3672   |   0.4738   |   0.0455   |   0.1064   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3698   |   0.4594   |   0.0319   |   0.0801   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3871   |   0.5521   |   0.0551   |   0.1316   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3931   |   0.5366   |   0.0416   |   0.0972   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5488   |   0.5476   |   0.0549   |   0.1081   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/rwc_mdb_j_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/rwc_mdb_j_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure25"></a>Figure 25: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_j_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure26"></a>Figure 26: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/rwc_mdb_j_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0008__ |   0.6234   |   0.6199   |   0.2621   |   0.1943   |   0.1608   | __0.0412__ |   0.0916   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0008__ |   1.0000   | __0.0002__ | __0.0051__ | __0.0128__ | __0.0460__ |   0.0580   |   0.0810   | __0.0207__ |
| [percival2014/stem](#percival2014stem)             |   0.6234   | __0.0002__ |   1.0000   |   0.2451   |   0.0637   |   0.0669   |   0.0520   | __0.0382__ | __0.0466__ |
| [schreiber2014/default](#schreiber2014default)     |   0.6199   | __0.0051__ |   0.2451   |   1.0000   |   0.4173   |   0.2525   |   0.2317   |   0.1130   |   0.2889   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2621   | __0.0128__ |   0.0637   |   0.4173   |   1.0000   |   0.6547   |   0.6601   |   0.5846   |   0.7612   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1943   | __0.0460__ |   0.0669   |   0.2525   |   0.6547   |   1.0000   |   0.8215   |   0.7341   |   0.9741   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1608   |   0.0580   |   0.0520   |   0.2317   |   0.6601   |   0.8215   |   1.0000   |   0.9294   |   0.8122   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0412__ |   0.0810   | __0.0382__ |   0.1130   |   0.5846   |   0.7341   |   0.9294   |   1.0000   |   0.7332   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0916   | __0.0207__ | __0.0466__ |   0.2889   |   0.7612   |   0.9741   |   0.8122   |   0.7332   |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0250__ |   0.1183   | __0.0021__ |   0.0546   |   0.0944   | __0.0213__ |   0.0927   |   0.2361   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0250__ |   1.0000   | __0.0068__ |   0.3016   |   0.9655   |   0.6796   |   0.9899   |   0.4637   |   0.2464   |
| [percival2014/stem](#percival2014stem)             |   0.1183   | __0.0068__ |   1.0000   | __0.0004__ | __0.0198__ | __0.0302__ | __0.0110__ | __0.0271__ |   0.0667   |
| [schreiber2014/default](#schreiber2014default)     | __0.0021__ |   0.3016   | __0.0004__ |   1.0000   | __0.0396__ | __0.0079__ |   0.2075   | __0.0287__ | __0.0024__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0546   |   0.9655   | __0.0198__ | __0.0396__ |   1.0000   |   0.3222   |   0.9479   |   0.4465   |   0.1194   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0944   |   0.6796   | __0.0302__ | __0.0079__ |   0.3222   |   1.0000   |   0.5951   |   0.7728   |   0.2012   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0213__ |   0.9899   | __0.0110__ |   0.2075   |   0.9479   |   0.5951   |   1.0000   |   0.2044   |   0.0955   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0927   |   0.4637   | __0.0271__ | __0.0287__ |   0.4465   |   0.7728   |   0.2044   |   1.0000   |   0.2437   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2361   |   0.2464   |   0.0667   | __0.0024__ |   0.1194   |   0.2012   |   0.0955   |   0.2437   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_j_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/rwc_mdb_j_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure31"></a>Figure 31: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure32"></a>Figure 32: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure33"></a>Figure 33: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure34"></a>Figure 34: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/rwc_mdb_j_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-05 19:32. Size L.
