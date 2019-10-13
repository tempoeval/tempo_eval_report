---
title: smc_mirex
{:.no_toc}
layout: default
---

# smc_mirex
{:.no_toc}

This is the tempo_eval report for the 'smc_mirex' corpus.

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'smc_mirex'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | SMC_MIREX |
| **Version** | 1.0 |
| **Curator** | [Matthew Davies](mailto:mdavies@inescporto.pt) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Holzapfel2012](bib/Holzapfel2012.bib) |
| **Annotator,&nbsp;ref_url** | [https://repositorio.inesctec.pt/bitstream/123456789/2539/1/PS-07771.pdf](https://repositorio.inesctec.pt/bitstream/123456789/2539/1/PS-07771.pdf) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | SMC_MIREX |
| **Version** | 2.0 |
| **Curator** | [Graham Percival](mailto:graham@percival-music.ca) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | unknown |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.marsyas.info/tempo/](http://www.marsyas.info/tempo/) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   217   |   32.71   |   206.90   |   78.02   |   31.89   |   51.00   |   0.69   |
| [2.0](#20)                                         |   217   |   32.71   |   206.90   |   78.01   |   31.89   |   51.00   |   0.69   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/smc_mirex_reference_basic_stats.csv "Download data as CSV") [JSON](data/smc_mirex_reference_basic_stats.json "Download data as JSON") [LATEX](data/smc_mirex_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/smc_mirex_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/smc_mirex_reference_dist.csv "Download data as CSV") [JSON](data/smc_mirex_reference_dist.json "Download data as JSON") [LATEX](data/smc_mirex_reference_dist.latex "Download data as LATEX") [PICKLE](data/smc_mirex_reference_dist.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_reference_dist.svg "Open Figure") [PDF](figures/smc_mirex_reference_dist.pdf "Open Figure") [PNG](figures/smc_mirex_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/smc_mirex_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/smc_mirex_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/smc_mirex_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/smc_mirex_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/smc_mirex_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/smc_mirex_reference_1.0_tag_open.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_variation.svg">
</figure>

<a name="figure3"></a>Figure 3: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/smc_mirex_variation.csv "Download data as CSV") [JSON](data/smc_mirex_variation.json "Download data as JSON") [LATEX](data/smc_mirex_variation.latex "Download data as LATEX") [PICKLE](data/smc_mirex_variation.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_variation.svg "Open Figure") [PDF](figures/smc_mirex_variation.pdf "Open Figure") [PNG](figures/smc_mirex_variation.png "Open Figure") 

# Estimates for 'smc_mirex'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | smc_mirex |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   217   |   40.82   |   240.00   |   102.30   |   44.73   |   58.00   |   0.58   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   217   |   71.78   |   215.33   |   136.10   |   31.83   |   96.00   |   0.86   |
| [percival2014/stem](#percival2014stem)             |   217   |   51.94   |   150.89   |   92.58   |   20.31   |   69.00   |   0.88   |
| [schreiber2014/default](#schreiber2014default)     |   217   |   47.79   |   154.05   |   88.34   |   20.46   |   61.00   |   0.88   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   217   |   11.20   |   176.17   |   86.03   |   34.68   |   53.00   |   0.59   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   217   |   11.20   |   159.09   |   75.95   |   30.99   |   45.00   |   0.61   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   217   |   49.00   |   224.00   |   96.84   |   27.94   |   61.00   |   0.85   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   217   |   38.00   |   198.00   |   94.95   |   31.03   |   63.00   |   0.75   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   217   |   53.00   |   205.00   |   96.91   |   26.05   |   67.00   |   0.89   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/smc_mirex_estimates_basic_stats.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_basic_stats.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_dist.svg">
</figure>

<a name="figure4"></a>Figure 4: Percentage of values in tempo interval.

[CSV](data/smc_mirex_estimates_dist.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_dist.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_dist.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_dist.svg "Open Figure") [PDF](figures/smc_mirex_estimates_dist.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.4654__ | __0.6728__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3825   |   0.5760   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3594   |   0.4793   |
| [schreiber2014/default](#schreiber2014default)     |   0.3502   |   0.5484   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3410   |   0.5115   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3180   |   0.5530   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3041   |   0.4793   |
| [percival2014/stem](#percival2014stem)             |   0.2765   |   0.4562   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1336   |   0.3180   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/smc_mirex_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/smc_mirex_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/smc_mirex_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.4654__ | __0.6728__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3825   |   0.5760   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3594   |   0.4793   |
| [schreiber2014/default](#schreiber2014default)     |   0.3502   |   0.5484   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3410   |   0.5115   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3180   |   0.5530   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3041   |   0.4793   |
| [percival2014/stem](#percival2014stem)             |   0.2765   |   0.4562   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1336   |   0.3134   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/smc_mirex_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/smc_mirex_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/smc_mirex_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (116 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_008' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_018' 'SMC\_019' ...
[CSV](data/smc_mirex_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (188 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_012' 'SMC\_013' ...
[CSV](data/smc_mirex_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (157 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_007' 'SMC\_008' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (141 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (148 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (134 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_008' 'SMC\_009' 'SMC\_012' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (143 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (139 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (151 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (116 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_008' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_018' 'SMC\_019' ...
[CSV](data/smc_mirex_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (188 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_012' 'SMC\_013' ...
[CSV](data/smc_mirex_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (157 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_007' 'SMC\_008' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (141 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (148 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (134 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_008' 'SMC\_009' 'SMC\_012' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (143 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (139 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_017' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (151 differences):*
'SMC\_001' 'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 64 items 'correctly' using Accuracy<sub>1</sub>:__
'SMC\_002' 'SMC\_015' 'SMC\_018' 'SMC\_022' 'SMC\_023' 'SMC\_024' 'SMC\_032' 'SMC\_037' 'SMC\_042' 'SMC\_048' 'SMC\_080' ...
[CSV](data/smc_mirex_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (71 differences):*
'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_008' 'SMC\_014' 'SMC\_015' 'SMC\_018' 'SMC\_021' 'SMC\_022' 'SMC\_024' 'SMC\_032' ...
[CSV](data/smc_mirex_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (148 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_012' 'SMC\_013' 'SMC\_014' ...
[CSV](data/smc_mirex_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (118 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_007' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_016' 'SMC\_018' 'SMC\_022' 'SMC\_023' ...
[CSV](data/smc_mirex_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (98 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_022' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (97 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' 'SMC\_024' 'SMC\_028' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (92 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' 'SMC\_024' 'SMC\_028' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (106 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_007' 'SMC\_011' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (113 differences):*
'SMC\_003' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (113 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' 'SMC\_017' 'SMC\_018' ...
[CSV](data/smc_mirex_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (71 differences):*
'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_008' 'SMC\_014' 'SMC\_015' 'SMC\_018' 'SMC\_021' 'SMC\_022' 'SMC\_024' 'SMC\_032' ...
[CSV](data/smc_mirex_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (149 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_011' 'SMC\_012' 'SMC\_013' 'SMC\_014' ...
[CSV](data/smc_mirex_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (118 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_007' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_016' 'SMC\_018' 'SMC\_022' 'SMC\_023' ...
[CSV](data/smc_mirex_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (98 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_007' 'SMC\_008' 'SMC\_009' 'SMC\_011' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_022' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (97 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' 'SMC\_024' 'SMC\_028' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (92 differences):*
'SMC\_002' 'SMC\_004' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' 'SMC\_024' 'SMC\_028' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (106 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_007' 'SMC\_011' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' 'SMC\_023' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (113 differences):*
'SMC\_003' 'SMC\_005' 'SMC\_006' 'SMC\_007' 'SMC\_008' 'SMC\_011' 'SMC\_014' 'SMC\_015' 'SMC\_017' 'SMC\_018' 'SMC\_021' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (113 differences):*
'SMC\_002' 'SMC\_003' 'SMC\_004' 'SMC\_006' 'SMC\_007' 'SMC\_009' 'SMC\_014' 'SMC\_015' 'SMC\_016' 'SMC\_017' 'SMC\_018' ...
[CSV](data/smc_mirex_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 23 items 'correctly' using Accuracy<sub>2</sub>:__
'SMC\_015' 'SMC\_018' 'SMC\_032' 'SMC\_111' 'SMC\_119' 'SMC\_137' 'SMC\_149' 'SMC\_152' 'SMC\_158' 'SMC\_174' 'SMC\_179' ...
[CSV](data/smc_mirex_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0022__ | __0.0000__ | __0.0153__ | __0.0011__ | __0.0052__ | __0.0001__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0402__ |   0.3211   | __0.0145__ |   0.0649   | __0.0247__ |   0.4514   |
| [schreiber2014/default](#schreiber2014default)     | __0.0022__ | __0.0000__ | __0.0402__ |   1.0000   |   0.3916   |   0.4347   |   0.8679   |   0.8804   |   0.2026   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.3211   |   0.3916   |   1.0000   | __0.0043__ |   0.6025   |   0.2976   |   0.7979   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0153__ | __0.0000__ | __0.0145__ |   0.4347   | __0.0043__ |   1.0000   |   0.3211   |   0.6198   |   0.0647   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0011__ | __0.0000__ |   0.0649   |   0.8679   |   0.6025   |   0.3211   |   1.0000   |   0.6655   |   0.2005   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0052__ | __0.0000__ | __0.0247__ |   0.8804   |   0.2976   |   0.6198   |   0.6655   |   1.0000   |   0.1114   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0001__ | __0.0000__ |   0.4514   |   0.2026   |   0.7979   |   0.0647   |   0.2005   |   0.1114   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0022__ | __0.0000__ | __0.0153__ | __0.0011__ | __0.0052__ | __0.0001__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0402__ |   0.3211   | __0.0145__ |   0.0649   | __0.0247__ |   0.4514   |
| [schreiber2014/default](#schreiber2014default)     | __0.0022__ | __0.0000__ | __0.0402__ |   1.0000   |   0.3916   |   0.4347   |   0.8679   |   0.8804   |   0.2026   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.3211   |   0.3916   |   1.0000   | __0.0043__ |   0.6025   |   0.2976   |   0.7979   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0153__ | __0.0000__ | __0.0145__ |   0.4347   | __0.0043__ |   1.0000   |   0.3211   |   0.6198   |   0.0647   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0011__ | __0.0000__ |   0.0649   |   0.8679   |   0.6025   |   0.3211   |   1.0000   |   0.6655   |   0.2005   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0052__ | __0.0000__ | __0.0247__ |   0.8804   |   0.2976   |   0.6198   |   0.6655   |   1.0000   |   0.1114   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0001__ | __0.0000__ |   0.4514   |   0.2026   |   0.7979   |   0.0647   |   0.2005   |   0.1114   |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0007__ | __0.0065__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0002__ |   1.0000   | __0.0315__ | __0.0170__ | __0.0034__ |   0.1550   |   0.6350   |   0.6025   |
| [schreiber2014/default](#schreiber2014default)     | __0.0004__ | __0.0000__ | __0.0315__ |   1.0000   |   1.0000   |   0.4709   |   0.3740   |   0.0817   |   0.0872   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0007__ | __0.0000__ | __0.0170__ |   1.0000   |   1.0000   |   0.0625   |   0.3135   |   0.0812   |   0.0689   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0065__ | __0.0000__ | __0.0034__ |   0.4709   |   0.0625   |   1.0000   |   0.0980   | __0.0192__ | __0.0139__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.1550   |   0.3740   |   0.3135   |   0.0980   |   1.0000   |   0.4101   |   0.3713   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0001__ |   0.6350   |   0.0817   |   0.0812   | __0.0192__ |   0.4101   |   1.0000   |   0.8897   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ |   0.6025   |   0.0872   |   0.0689   | __0.0139__ |   0.3713   |   0.8897   |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0007__ | __0.0065__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0001__ |   1.0000   | __0.0315__ | __0.0170__ | __0.0034__ |   0.1550   |   0.6350   |   0.6025   |
| [schreiber2014/default](#schreiber2014default)     | __0.0004__ | __0.0000__ | __0.0315__ |   1.0000   |   1.0000   |   0.4709   |   0.3740   |   0.0817   |   0.0872   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0007__ | __0.0000__ | __0.0170__ |   1.0000   |   1.0000   |   0.0625   |   0.3135   |   0.0812   |   0.0689   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0065__ | __0.0000__ | __0.0034__ |   0.4709   |   0.0625   |   1.0000   |   0.0980   | __0.0192__ | __0.0139__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.1550   |   0.3740   |   0.3135   |   0.0980   |   1.0000   |   0.4101   |   0.3713   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.6350   |   0.0817   |   0.0812   | __0.0192__ |   0.4101   |   1.0000   |   0.8897   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ |   0.6025   |   0.0872   |   0.0689   | __0.0139__ |   0.3713   |   0.8897   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure18"></a>Figure 18: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure20"></a>Figure 20: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3748   | __0.5772__ |   -0.0151   |   0.2257   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3680   |   0.5783   | __-0.0043__ |   0.1957   |
| [schreiber2014/default](#schreiber2014default)     |   0.2463   |   0.5907   |   -0.0214   |   0.1942   |
| [percival2014/stem](#percival2014stem)             |   0.3198   |   0.6156   |   0.0071   |   0.2074   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3147   |   0.6172   |   -0.0134   |   0.2054   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8693   |   0.6634   |   0.0506   |   0.2209   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3676   |   0.6921   |   0.0234   | __0.1460__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __-0.0565__ |   0.7587   |   -0.0189   |   0.2017   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1186   |   0.8104   |   -0.0093   |   0.2114   |

<a name="table9"></a>Table 9: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/smc_mirex_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure25"></a>Figure 25: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure26"></a>Figure 26: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3750   | __0.5772__ |   -0.0149   |   0.2259   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3681   |   0.5783   | __-0.0041__ |   0.1960   |
| [schreiber2014/default](#schreiber2014default)     |   0.2465   |   0.5906   |   -0.0213   |   0.1943   |
| [percival2014/stem](#percival2014stem)             |   0.3200   |   0.6158   |   0.0073   |   0.2076   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3149   |   0.6172   |   -0.0132   |   0.2056   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8695   |   0.6634   |   0.0508   |   0.2210   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3678   |   0.6922   |   0.0236   | __0.1461__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __-0.0563__ |   0.7588   |   -0.0187   |   0.2017   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1188   |   0.8105   |   -0.0091   |   0.2114   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/smc_mirex_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure27"></a>Figure 27: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure28"></a>Figure 28: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.2863   | __0.0096__ | __0.0000__ | __0.0000__ |   0.9936   |   0.2140   |   0.8693   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.2863   | __0.0000__ |   1.0000   | __0.0112__ | __0.0000__ | __0.0000__ |   0.1344   |   0.8895   |   0.0750   |
| [schreiber2014/default](#schreiber2014default)     | __0.0096__ | __0.0000__ | __0.0112__ |   1.0000   | __0.0081__ | __0.0000__ | __0.0000__ |   0.0626   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9936   | __0.0000__ |   0.1344   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1067   |   0.7890   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2140   | __0.0000__ |   0.8895   |   0.0626   | __0.0003__ | __0.0000__ |   0.1067   |   1.0000   |   0.0889   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8693   | __0.0000__ |   0.0750   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7890   |   0.0889   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.2863   | __0.0096__ | __0.0000__ | __0.0000__ |   0.9936   |   0.2140   |   0.8693   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.2863   | __0.0000__ |   1.0000   | __0.0112__ | __0.0000__ | __0.0000__ |   0.1344   |   0.8895   |   0.0750   |
| [schreiber2014/default](#schreiber2014default)     | __0.0096__ | __0.0000__ | __0.0112__ |   1.0000   | __0.0081__ | __0.0000__ | __0.0000__ |   0.0626   | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0081__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9936   | __0.0000__ |   0.1344   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1067   |   0.7890   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2140   | __0.0000__ |   0.8895   |   0.0626   | __0.0003__ | __0.0000__ |   0.1067   |   1.0000   |   0.0889   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8693   | __0.0000__ |   0.0750   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7890   |   0.0889   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0704   |   0.3036   | __0.0023__ | __0.0341__ | __0.0052__ |   0.0780   | __0.0232__ | __0.0246__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0704   |   1.0000   | __0.0398__ | __0.0001__ | __0.0008__ | __0.0001__ | __0.0069__ | __0.0010__ | __0.0013__ |
| [percival2014/stem](#percival2014stem)             |   0.3036   | __0.0398__ |   1.0000   |   0.1258   |   0.3532   |   0.1361   |   0.4850   |   0.2493   |   0.2250   |
| [schreiber2014/default](#schreiber2014default)     | __0.0023__ | __0.0001__ |   0.1258   |   1.0000   |   0.4034   |   0.8582   |   0.2881   |   0.6110   |   0.7158   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0341__ | __0.0008__ |   0.3532   |   0.4034   |   1.0000   | __0.0250__ |   0.7769   |   0.8152   |   0.7609   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0052__ | __0.0001__ |   0.1361   |   0.8582   | __0.0250__ |   1.0000   |   0.4016   |   0.7472   |   0.8416   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0780   | __0.0069__ |   0.4850   |   0.2881   |   0.7769   |   0.4016   |   1.0000   |   0.5390   |   0.5151   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0232__ | __0.0010__ |   0.2493   |   0.6110   |   0.8152   |   0.7472   |   0.5390   |   1.0000   |   0.9184   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0246__ | __0.0013__ |   0.2250   |   0.7158   |   0.7609   |   0.8416   |   0.5151   |   0.9184   |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0704   |   0.3036   | __0.0023__ | __0.0341__ | __0.0052__ |   0.0780   | __0.0232__ | __0.0246__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0704   |   1.0000   | __0.0398__ | __0.0001__ | __0.0008__ | __0.0001__ | __0.0069__ | __0.0010__ | __0.0013__ |
| [percival2014/stem](#percival2014stem)             |   0.3036   | __0.0398__ |   1.0000   |   0.1258   |   0.3532   |   0.1361   |   0.4850   |   0.2493   |   0.2250   |
| [schreiber2014/default](#schreiber2014default)     | __0.0023__ | __0.0001__ |   0.1258   |   1.0000   |   0.4034   |   0.8582   |   0.2881   |   0.6110   |   0.7158   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0341__ | __0.0008__ |   0.3532   |   0.4034   |   1.0000   | __0.0250__ |   0.7769   |   0.8152   |   0.7609   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0052__ | __0.0001__ |   0.1361   |   0.8582   | __0.0250__ |   1.0000   |   0.4016   |   0.7472   |   0.8416   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0780   | __0.0069__ |   0.4850   |   0.2881   |   0.7769   |   0.4016   |   1.0000   |   0.5390   |   0.5151   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0232__ | __0.0010__ |   0.2493   |   0.6110   |   0.8152   |   0.7472   |   0.5390   |   1.0000   |   0.9184   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0246__ | __0.0013__ |   0.2250   |   0.7158   |   0.7609   |   0.8416   |   0.5151   |   0.9184   |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure32"></a>Figure 32: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure33"></a>Figure 33: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure37"></a>Figure 37: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure38"></a>Figure 38: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure39"></a>Figure 39: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure40"></a>Figure 40: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_oe1.svg">
</figure>

<a name="figure42"></a>Figure 42: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure43"></a>Figure 43: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2014/default](#schreiber2014default)     | __0.4576__ | __0.4475__ |   0.1268   |   0.1486   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.4777   |   0.5018   |   0.1351   |   0.1552   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4820   |   0.4874   |   0.1272   |   0.1488   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5012   |   0.6025   | __0.0770__ | __0.1262__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5014   |   0.4714   |   0.1546   |   0.1651   |
| [percival2014/stem](#percival2014stem)             |   0.5055   |   0.4751   |   0.1464   |   0.1471   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5156   |   0.5594   |   0.1221   |   0.1617   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5905   |   0.5676   |   0.1308   |   0.1663   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.9124   |   0.6028   |   0.1675   |   0.1527   |

<a name="table15"></a>Table 15: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/smc_mirex_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/smc_mirex_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure45"></a>Figure 45: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure46"></a>Figure 46: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2014/default](#schreiber2014default)     | __0.4577__ | __0.4473__ |   0.1270   |   0.1486   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.4778   |   0.5018   |   0.1352   |   0.1554   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4821   |   0.4873   |   0.1273   |   0.1491   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5013   |   0.6026   | __0.0771__ | __0.1263__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5016   |   0.4714   |   0.1548   |   0.1652   |
| [percival2014/stem](#percival2014stem)             |   0.5056   |   0.4753   |   0.1466   |   0.1472   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5157   |   0.5595   |   0.1222   |   0.1616   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5906   |   0.5676   |   0.1309   |   0.1662   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.9126   |   0.6028   |   0.1677   |   0.1526   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/smc_mirex_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/smc_mirex_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/smc_mirex_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/smc_mirex_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure47"></a>Figure 47: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure48"></a>Figure 48: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/smc_mirex_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.9178   |   0.3170   | __0.0341__ |   0.7360   |   0.6262   |   0.5601   |   0.9953   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.9178   | __0.0000__ |   1.0000   |   0.0820   | __0.0299__ |   0.8107   |   0.4472   |   0.4227   |   0.8909   |
| [schreiber2014/default](#schreiber2014default)     |   0.3170   | __0.0000__ |   0.0820   |   1.0000   | __0.0008__ |   0.1674   |   0.3601   |   0.5561   |   0.1023   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0341__ | __0.0000__ | __0.0299__ | __0.0008__ |   1.0000   | __0.0031__ | __0.0121__ | __0.0072__ | __0.0443__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7360   | __0.0000__ |   0.8107   |   0.1674   | __0.0031__ |   1.0000   |   0.4436   |   0.3638   |   0.7581   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6262   | __0.0000__ |   0.4472   |   0.3601   | __0.0121__ |   0.4436   |   1.0000   |   0.8924   |   0.4249   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5601   | __0.0000__ |   0.4227   |   0.5561   | __0.0072__ |   0.3638   |   0.8924   |   1.0000   |   0.4833   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9953   | __0.0000__ |   0.8909   |   0.1023   | __0.0443__ |   0.7581   |   0.4249   |   0.4833   |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.9176   |   0.3171   | __0.0341__ |   0.7359   |   0.6264   |   0.5600   |   0.9936   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.9176   | __0.0000__ |   1.0000   |   0.0820   | __0.0299__ |   0.8108   |   0.4472   |   0.4225   |   0.8931   |
| [schreiber2014/default](#schreiber2014default)     |   0.3171   | __0.0000__ |   0.0820   |   1.0000   | __0.0008__ |   0.1674   |   0.3601   |   0.5564   |   0.1016   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0341__ | __0.0000__ | __0.0299__ | __0.0008__ |   1.0000   | __0.0031__ | __0.0121__ | __0.0072__ | __0.0445__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7359   | __0.0000__ |   0.8108   |   0.1674   | __0.0031__ |   1.0000   |   0.4436   |   0.3637   |   0.7594   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6264   | __0.0000__ |   0.4472   |   0.3601   | __0.0121__ |   0.4436   |   1.0000   |   0.8920   |   0.4229   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5600   | __0.0000__ |   0.4225   |   0.5564   | __0.0072__ |   0.3637   |   0.8920   |   1.0000   |   0.4814   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9936   | __0.0000__ |   0.8931   |   0.1016   | __0.0445__ |   0.7594   |   0.4229   |   0.4814   |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.0976   | __0.0017__ | __0.0044__ | __0.0005__ | __0.0040__ | __0.0180__ |   0.3658   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0976   |   1.0000   |   0.1049   |   0.2148   |   0.0517   |   0.0621   |   0.3485   |   0.4708   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0017__ |   0.1049   |   1.0000   |   0.7164   |   0.6585   |   0.9787   |   0.5182   | __0.0339__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0044__ |   0.2148   |   0.7164   |   1.0000   | __0.0258__ |   0.7838   |   0.7568   |   0.0718   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0002__ | __0.0005__ |   0.0517   |   0.6585   | __0.0258__ |   1.0000   |   0.6949   |   0.3318   | __0.0124__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0040__ |   0.0621   |   0.9787   |   0.7838   |   0.6949   |   1.0000   |   0.4522   | __0.0026__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0180__ |   0.3485   |   0.5182   |   0.7568   |   0.3318   |   0.4522   |   1.0000   |   0.0664   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.3658   |   0.4708   | __0.0339__ |   0.0718   | __0.0124__ | __0.0026__ |   0.0664   |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.0974   | __0.0017__ | __0.0043__ | __0.0005__ | __0.0040__ | __0.0178__ |   0.3658   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0974   |   1.0000   |   0.1050   |   0.2130   |   0.0512   |   0.0622   |   0.3459   |   0.4702   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0017__ |   0.1050   |   1.0000   |   0.7213   |   0.6538   |   0.9788   |   0.5220   | __0.0338__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0043__ |   0.2130   |   0.7213   |   1.0000   | __0.0258__ |   0.7878   |   0.7569   |   0.0710   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0002__ | __0.0005__ |   0.0512   |   0.6538   | __0.0258__ |   1.0000   |   0.6910   |   0.3319   | __0.0122__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0040__ |   0.0622   |   0.9788   |   0.7878   |   0.6910   |   1.0000   |   0.4565   | __0.0026__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0178__ |   0.3459   |   0.5220   |   0.7569   |   0.3319   |   0.4565   |   1.0000   |   0.0655   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.3658   |   0.4702   | __0.0338__ |   0.0710   | __0.0122__ | __0.0026__ |   0.0655   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/smc_mirex_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure49"></a>Figure 49: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure50"></a>Figure 50: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure51"></a>Figure 51: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/smc_mirex_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure52"></a>Figure 52: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/smc_mirex_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure53"></a>Figure 53: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure54"></a>Figure 54: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure55"></a>Figure 55: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure56"></a>Figure 56: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/smc_mirex_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure57"></a>Figure 57: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure58"></a>Figure 58: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure59"></a>Figure 59: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure60"></a>Figure 60: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/smc_mirex_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/smc_mirex_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/smc_mirex_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/smc_mirex_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/smc_mirex_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure61"></a>Figure 61: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure62"></a>Figure 62: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure63"></a>Figure 63: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure64"></a>Figure 64: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/smc_mirex_estimates_1.0_tag_open_2.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 11:38. Size L.
