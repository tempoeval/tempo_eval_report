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
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | rwc_mdb_r |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   15   |   69.77   |   130.43   |   101.28   |   20.83   |   66.00   |   1.00   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   15   |   70.79   |   152.00   |   112.50   |   22.58   |   76.00   |   0.93   |
| [percival2014/stem](#percival2014stem)             |   15   |   70.07   |   130.01   |   101.28   |   20.66   |   66.00   |   1.00   |
| [schreiber2014/default](#schreiber2014default)     |   15   |   74.84   |   139.97   |   107.55   |   18.93   |   70.00   |   1.00   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   15   |   46.68   |   130.00   |   99.78   |   23.85   |   65.00   |   0.93   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   15   |   46.68   |   130.00   |   99.78   |   23.85   |   65.00   |   0.93   |

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

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 0.1

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.8667__ | __1.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.8667__ | __1.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8000   |   0.9333   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8000   |   0.9333   |
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
| [percival2014/stem](#percival2014stem)             | __0.8667__ | __1.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.8667__ | __1.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8000   |   0.9333   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8000   |   0.9333   |
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

*[0.1](#01) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (3 differences):*
'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[0.1](#01) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (3 differences):*
'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_0.1_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

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

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (3 differences):*
'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (3 differences):*
'RM-R012' 'RM-R013' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 2 items 'correctly' using Accuracy<sub>1</sub>:__
'RM-R012' 'RM-R014' 
[CSV](data/rwc_mdb_r_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

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

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.5000   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [0.1](#01) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |   1.0000   |

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

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 0.1

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             |   -0.1340   | __0.3404__ | __-0.0007__ | __0.0016__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1345   |   0.3409   |   -0.0012   |   0.0042   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1723   |   0.3556   |   0.0277   |   0.1037   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1723   |   0.3556   |   0.0277   |   0.1037   |
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
| [percival2014/stem](#percival2014stem)             |   -0.1336   | __0.3413__ | __-0.0002__ | __0.0024__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1341   |   0.3418   |   -0.0008   |   0.0052   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1719   |   0.3566   |   0.0281   |   0.1034   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1719   |   0.3566   |   0.0281   |   0.1034   |
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

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1177   |   0.6951   |   0.1984   |   0.3453   |   0.3453   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1177   |   1.0000   |   0.1182   |   0.4494   |   0.0660   |   0.0660   |
| [percival2014/stem](#percival2014stem)             |   0.6951   |   0.1182   |   1.0000   |   0.1973   |   0.3438   |   0.3438   |
| [schreiber2014/default](#schreiber2014default)     |   0.1984   |   0.4494   |   0.1973   |   1.0000   |   0.1644   |   0.1644   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3453   |   0.0660   |   0.3438   |   0.1644   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3453   |   0.0660   |   0.3438   |   0.1644   |   1.0000   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1177   |   0.6951   |   0.1984   |   0.3453   |   0.3453   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1177   |   1.0000   |   0.1182   |   0.4494   |   0.0660   |   0.0660   |
| [percival2014/stem](#percival2014stem)             |   0.6951   |   0.1182   |   1.0000   |   0.1973   |   0.3438   |   0.3438   |
| [schreiber2014/default](#schreiber2014default)     |   0.1984   |   0.4494   |   0.1973   |   1.0000   |   0.1644   |   0.1644   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3453   |   0.0660   |   0.3438   |   0.1644   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3453   |   0.0660   |   0.3438   |   0.1644   |   1.0000   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6951   |   0.3215   |   0.3201   |   0.3201   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7572   |   0.7550   |   0.7550   |
| [percival2014/stem](#percival2014stem)             |   0.6951   | __0.0000__ |   1.0000   |   0.3226   |   0.3212   |   0.3212   |
| [schreiber2014/default](#schreiber2014default)     |   0.3215   |   0.7572   |   0.3226   |   1.0000   |   0.8146   |   0.8146   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6951   |   0.3215   |   0.3201   |   0.3201   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7572   |   0.7550   |   0.7550   |
| [percival2014/stem](#percival2014stem)             |   0.6951   | __0.0000__ |   1.0000   |   0.3226   |   0.3212   |   0.3212   |
| [schreiber2014/default](#schreiber2014default)     |   0.3215   |   0.7572   |   0.3226   |   1.0000   |   0.8146   |   0.8146   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3201   |   0.7550   |   0.3212   |   0.8146   |   1.0000   |   1.0000   |

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

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 0.1

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [percival2014/stem](#percival2014stem)             | __0.1350__ | __0.3401__ | __0.0016__ | __0.0006__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1364   |   0.3402   |   0.0031   |   0.0031   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1725   |   0.3556   |   0.0279   |   0.1036   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1725   |   0.3556   |   0.0279   |   0.1036   |
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
| [percival2014/stem](#percival2014stem)             | __0.1354__ | __0.3406__ | __0.0021__ | __0.0013__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1371   |   0.3406   |   0.0037   |   0.0037   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1735   |   0.3559   |   0.0288   |   0.1032   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1735   |   0.3559   |   0.0288   |   0.1032   |
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

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1381   |   0.1035   |   0.2102   |   0.3645   |   0.3645   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1381   |   1.0000   |   0.1334   |   0.4850   |   0.3118   |   0.3118   |
| [percival2014/stem](#percival2014stem)             |   0.1035   |   0.1334   |   1.0000   |   0.2033   |   0.3465   |   0.3465   |
| [schreiber2014/default](#schreiber2014default)     |   0.2102   |   0.4850   |   0.2033   |   1.0000   |   0.4286   |   0.4286   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3645   |   0.3118   |   0.3465   |   0.4286   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3645   |   0.3118   |   0.3465   |   0.4286   |   1.0000   |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1386   |   0.1263   |   0.2108   |   0.3694   |   0.3694   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1386   |   1.0000   |   0.1347   |   0.4859   |   0.3112   |   0.3112   |
| [percival2014/stem](#percival2014stem)             |   0.1263   |   0.1347   |   1.0000   |   0.2050   |   0.3523   |   0.3523   |
| [schreiber2014/default](#schreiber2014default)     |   0.2108   |   0.4859   |   0.2050   |   1.0000   |   0.4267   |   0.4267   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3694   |   0.3112   |   0.3523   |   0.4267   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3694   |   0.3112   |   0.3523   |   0.4267   |   1.0000   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [0.1](#01) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1035   |   0.3696   |   0.3776   |   0.3776   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7260   |   0.7371   |   0.7371   |
| [percival2014/stem](#percival2014stem)             |   0.1035   | __0.0000__ |   1.0000   |   0.3440   |   0.3517   |   0.3517   |
| [schreiber2014/default](#schreiber2014default)     |   0.3696   |   0.7260   |   0.3440   |   1.0000   |   0.1994   |   0.1994   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3776   |   0.7371   |   0.3517   |   0.1994   |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3776   |   0.7371   |   0.3517   |   0.1994   |   1.0000   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/rwc_mdb_r_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/rwc_mdb_r_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/rwc_mdb_r_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/rwc_mdb_r_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1263   |   0.3713   |   0.3845   |   0.3845   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ |   0.7314   |   0.7496   |   0.7496   |
| [percival2014/stem](#percival2014stem)             |   0.1263   | __0.0000__ |   1.0000   |   0.3473   |   0.3599   |   0.3599   |
| [schreiber2014/default](#schreiber2014default)     |   0.3713   |   0.7314   |   0.3473   |   1.0000   | __0.0169__ | __0.0169__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3845   |   0.7496   |   0.3599   | __0.0169__ |   1.0000   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3845   |   0.7496   |   0.3599   | __0.0169__ |   1.0000   |   1.0000   |

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
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 17:31. Size L.
