---
title: wjd
{:.no_toc}
layout: default
---

# wjd
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'wjd' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'wjd'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 1.0 |
| **Curator** | Martin Pfleiderer |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | mean of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Pfleiderer2017](bib/Pfleiderer2017.bib) |
| **Annotator,&nbsp;ref_url** | [https://jazzomat.hfm-weimar.de](https://jazzomat.hfm-weimar.de) |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 2.0 |
| **Curator** | [Hendrik Schreiber](mailto:hs@tagtraum.com) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of corresponding inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Pfleiderer2017](bib/Pfleiderer2017.bib) |
| **Annotator,&nbsp;ref_url** | [https://jazzomat.hfm-weimar.de](https://jazzomat.hfm-weimar.de) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   456   |   36.99   |   361.84   |   177.45   |   68.50   |   124.00   |   0.60   |
| [2.0](#20)                                         |   456   |   36.06   |   360.83   |   177.24   |   68.45   |   124.00   |   0.61   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/wjd_reference_basic_stats.csv "Download data as CSV") [JSON](data/wjd_reference_basic_stats.json "Download data as JSON") [LATEX](data/wjd_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/wjd_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/wjd_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/wjd_reference_dist.csv "Download data as CSV") [JSON](data/wjd_reference_dist.json "Download data as JSON") [LATEX](data/wjd_reference_dist.latex "Download data as LATEX") [PICKLE](data/wjd_reference_dist.pickle "Download data as PICKLE") [SVG](figures/wjd_reference_dist.svg "Open Figure") [PDF](figures/wjd_reference_dist.pdf "Open Figure") [PNG](figures/wjd_reference_dist.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/wjd_variation.svg">
</figure>

<a name="figure2"></a>Figure 2: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/wjd_variation.csv "Download data as CSV") [JSON](data/wjd_variation.json "Download data as JSON") [LATEX](data/wjd_variation.latex "Download data as LATEX") [PICKLE](data/wjd_variation.pickle "Download data as PICKLE") [SVG](figures/wjd_variation.svg "Open Figure") [PDF](figures/wjd_variation.pdf "Open Figure") [PNG](figures/wjd_variation.png "Open Figure") 

# Estimates for 'wjd'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | wjd |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   456   |   48.39   |   240.00   |   131.67   |   41.00   |   97.00   |   0.73   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   456   |   69.84   |   215.33   |   130.12   |   25.81   |   90.00   |   0.91   |
| [percival2014/stem](#percival2014stem)             |   456   |   53.42   |   20671.90   |   147.51   |   963.58   |   68.00   |   0.82   |
| [schreiber2014/default](#schreiber2014default)     |   456   |   56.99   |   149.43   |   97.74   |   23.60   |   68.00   |   0.87   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   456   |   54.51   |   199.67   |   104.19   |   26.64   |   69.00   |   0.90   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   456   |   54.81   |   198.72   |   104.16   |   26.32   |   69.00   |   0.87   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   456   |   61.00   |   232.00   |   139.60   |   39.74   |   109.00   |   0.78   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   456   |   48.00   |   237.00   |   126.78   |   40.12   |   101.00   |   0.68   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   456   |   67.00   |   237.00   |   137.52   |   34.93   |   101.00   |   0.82   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/wjd_estimates_basic_stats.csv "Download data as CSV") [JSON](data/wjd_estimates_basic_stats.json "Download data as JSON") [LATEX](data/wjd_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/wjd_estimates_dist.csv "Download data as CSV") [JSON](data/wjd_estimates_dist.json "Download data as JSON") [LATEX](data/wjd_estimates_dist.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_dist.svg "Open Figure") [PDF](figures/wjd_estimates_dist.pdf "Open Figure") [PNG](figures/wjd_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.5811__ |   0.9627   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5789   |   0.9496   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5680   | __0.9912__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.4934   |   0.9276   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4320   |   0.9276   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3026   |   0.9013   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3004   |   0.8838   |
| [percival2014/stem](#percival2014stem)             |   0.2675   |   0.8991   |
| [schreiber2014/default](#schreiber2014default)     |   0.2215   |   0.8947   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/wjd_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/wjd_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/wjd_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/wjd_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/wjd_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.5877__ |   0.9715   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5833   |   0.9605   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5724   | __0.9956__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5022   |   0.9364   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4364   |   0.9364   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3048   |   0.9101   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3026   |   0.8925   |
| [percival2014/stem](#percival2014stem)             |   0.2675   |   0.9079   |
| [schreiber2014/default](#schreiber2014default)     |   0.2215   |   0.8925   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/wjd_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/wjd_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/wjd_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/wjd_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/wjd_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (197 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BennyGoodman\_Whispering\_Solo' ...
[CSV](data/wjd_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (259 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' ...
[CSV](data/wjd_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (334 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (355 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (319 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (318 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (191 differences):*
'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_BluesForBela\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (231 differences):*
'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BixBeiderbecke\_RiverboatShuffle\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_BluesForBela\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (192 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (195 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BennyGoodman\_Whispering\_Solo' ...
[CSV](data/wjd_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (257 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' ...
[CSV](data/wjd_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (334 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (355 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (318 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_ByeByeBlackbird\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (317 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_Desafinado\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BenWebster\_NightAndDay\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyCarter\_LongAgoAndFarAway-1\_Solo' 'BennyCarter\_LongAgoAndFarAway-2\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (188 differences):*
'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_BluesForBela\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (227 differences):*
'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BixBeiderbecke\_RiverboatShuffle\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_BluesForBela\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (190 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BennyCarter\_JustFriends\_Solo' 'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 128 items 'correctly' using Accuracy<sub>1</sub>:__
'BennyGoodman\_Avalon\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BennyGoodman\_Runnin'Wild\_Solo' 'BennyGoodman\_TigerRag-1\_Solo' 'BennyGoodman\_TigerRag-2\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_BluesForBela\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'BranfordMarsalis\_ThreeLittleWords\_Solo' 'BuckClayton\_DestinationK.C.\_Solo' ...
[CSV](data/wjd_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (4 differences):*
'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DonByas\_OutOfNowhere\_Solo' 'SonnyStitt\_Teapot\_Solo' 
[CSV](data/wjd_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (33 differences):*
'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_HowDeepIsTheOcean\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidLiebman\_NoGreaterLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DavidMurray\_BodyAndSoul-1\_Solo' ...
[CSV](data/wjd_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (46 differences):*
'ArtPepper\_Stardust-1\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_YouAndTheNightAndTheMusic\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' ...
[CSV](data/wjd_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (48 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BobBerg\_YouAndTheNightAndTheMusic\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_EmbraceableYou\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_Item1,D.I.T.\_Solo' 'ChrisPotter\_PopTune#1\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (53 differences):*
'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_Item1,D.I.T.\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (45 differences):*
'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DizzyGillespie\_Be=Bop\_Solo' 'DonByas\_Be=Bop\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (17 differences):*
'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DonByas\_OutOfNowhere\_Solo' 'JoeHenderson\_In'NOut-2\_Solo' 'JohnAbercrombie\_Ralph'sPianoWaltz\_Solo' 'JohnColtrane\_BlueTrain\_Solo' 'JohnColtrane\_Impressions\_1961\_Solo' 'JoshuaRedman\_SweetSorrow\_Solo' 'KennyWheeler\_DoubleVision\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (33 differences):*
'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidLiebman\_Milestones\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DavidMurray\_BodyAndSoul-2\_Solo' 'DizzyGillespie\_Be=Bop\_Solo' 'DonByas\_Be=Bop\_Solo' 'DonByas\_OutOfNowhere\_Solo' 'FatsNavarro\_Anthropology\_No1\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (23 differences):*
'CharlieParker\_EmbraceableYou\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_InASentimentalMood\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DexterGordon\_Montmartre\_Solo' 'DonByas\_OutOfNowhere\_Solo' 'JoeHenderson\_In'NOut-2\_Solo' 'JoeLovano\_BodyAndSoul-2\_Solo' 'JohnAbercrombie\_Ralph'sPianoWaltz\_Solo' ...
[CSV](data/wjd_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2 differences):*
'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 
[CSV](data/wjd_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (29 differences):*
'ArtPepper\_Stardust-1\_Solo' 'ArtPepper\_Stardust-2\_Solo' 'BennyCarter\_IGotItBad\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_HowDeepIsTheOcean\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidLiebman\_NoGreaterLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DavidMurray\_BodyAndSoul-1\_Solo' ...
[CSV](data/wjd_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (42 differences):*
'ArtPepper\_Stardust-1\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BobBerg\_Angles\_Solo' 'BobBerg\_YouAndTheNightAndTheMusic\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' ...
[CSV](data/wjd_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (49 differences):*
'ArtPepper\_Anthropology\_Solo' 'ArtPepper\_BluesForBlanche\_Solo' 'ArtPepper\_InAMellowTone\_Solo' 'BennyGoodman\_HandfulOfKeys\_Solo' 'BennyGoodman\_Nobody'sSweetheart\_Solo' 'BobBerg\_YouAndTheNightAndTheMusic\_Solo' 'BranfordMarsalis\_TheNearnessOfYou\_Solo' 'CharlieParker\_EmbraceableYou\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_Item1,D.I.T.\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (49 differences):*
'BennyGoodman\_Nobody'sSweetheart\_Solo' 'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_Item1,D.I.T.\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DizzyGillespie\_Be=Bop\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (41 differences):*
'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'CliffordBrown\_I'llRememberApril\_AlternateTake2\_Solo' 'CliffordBrown\_I'llRememberApril\_Solo' 'DavidLiebman\_SecretLove\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DizzyGillespie\_Be=Bop\_Solo' 'DonByas\_Be=Bop\_Solo' 'FatsNavarro\_Anthropology\_No1\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (13 differences):*
'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'JoeHenderson\_In'NOut-2\_Solo' 'JohnAbercrombie\_Ralph'sPianoWaltz\_Solo' 'JohnColtrane\_Impressions\_1961\_Solo' 'JoshuaRedman\_SweetSorrow\_Solo' 'KennyWheeler\_DoubleVision\_Solo' 'MilesDavis\_TuneUp\_Solo' 'RoyEldridge\_St.LouisBlues\_Solo' 'WayneShorter\_InfantEyes\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (29 differences):*
'CharlieParker\_Ko=Ko\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidLiebman\_Milestones\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DizzyGillespie\_Be=Bop\_Solo' 'DonByas\_Be=Bop\_Solo' 'FatsNavarro\_Anthropology\_No1\_Solo' 'JoeHenderson\_In'NOut-2\_Solo' 'JoeLovano\_LittleWillieLeapsIn\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (18 differences):*
'CharlieParker\_EmbraceableYou\_Solo' 'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 'DavidMurray\_BluesForTwo-1\_Solo' 'DavidMurray\_BluesForTwo-2\_Solo' 'DexterGordon\_Montmartre\_Solo' 'JoeHenderson\_In'NOut-2\_Solo' 'JoeLovano\_BodyAndSoul-2\_Solo' 'JohnAbercrombie\_Ralph'sPianoWaltz\_Solo' 'JohnColtrane\_NatureBoy\_Solo' 'JoshuaRedman\_SweetSorrow\_Solo' ...
[CSV](data/wjd_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 2 items 'correctly' using Accuracy<sub>2</sub>:__
'ChrisPotter\_Arjuna\_Solo' 'ChrisPotter\_PopTune#1\_Solo' 
[CSV](data/wjd_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5382   | __0.0026__ |   0.6750   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0116__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0099__ |   0.0812   | __0.0396__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0099__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.0812   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0396__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5382   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8899   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0026__ | __0.0116__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6750   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8899   | __0.0000__ |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6098   | __0.0015__ |   0.6750   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0188__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0086__ |   0.1013   |   0.0519   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0086__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.1013   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0519   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6098   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0015__ | __0.0188__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.6750   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.0919   | __0.0169__ | __0.0187__ |   0.1550   | __0.0090__ |   1.0000   |   0.0801   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0919   |   1.0000   |   0.3817   |   0.3240   |   1.0000   | __0.0000__ |   0.0660   | __0.0004__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0169__ |   0.3817   |   1.0000   |   1.0000   |   0.2682   | __0.0000__ | __0.0022__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0187__ |   0.3240   |   1.0000   |   1.0000   | __0.0386__ | __0.0000__ | __0.0017__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.1550   |   1.0000   |   0.2682   | __0.0386__ |   1.0000   | __0.0000__ |   0.0501   | __0.0008__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0010__ | __0.0090__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0009__ |   0.2266   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   1.0000   |   0.0660   | __0.0022__ | __0.0017__ |   0.0501   | __0.0009__ |   1.0000   | __0.0347__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.0801   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0008__ |   0.2266   | __0.0347__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.0919   |   0.0769   | __0.0205__ |   0.1619   | __0.0113__ |   1.0000   |   0.1433   |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0919   |   1.0000   |   0.8804   |   0.3368   |   1.0000   | __0.0000__ |   0.0725   | __0.0014__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.0769   |   0.8804   |   1.0000   |   0.4869   |   0.7359   | __0.0000__ | __0.0201__ | __0.0003__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0205__ |   0.3368   |   0.4869   |   1.0000   | __0.0386__ | __0.0000__ | __0.0022__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.1619   |   1.0000   |   0.7359   | __0.0386__ |   1.0000   | __0.0000__ |   0.0576   | __0.0016__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0002__ | __0.0113__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0015__ |   0.1796   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   1.0000   |   0.0725   | __0.0201__ | __0.0022__ |   0.0576   | __0.0015__ |   1.0000   |   0.0755   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.1433   | __0.0014__ | __0.0003__ | __0.0000__ | __0.0016__ |   0.1796   |   0.0755   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure16"></a>Figure 16: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure18"></a>Figure 18: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3815   | __0.5469__ |   -0.0021   | __0.0180__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.2925   |   0.5633   |   -0.0052   |   0.0738   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __-0.2846__ |   0.5704   | __-0.0017__ |   0.0658   |
| [schreiber2014/default](#schreiber2014default)     |   -0.7802   |   0.5874   |   -0.0347   |   0.1120   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.4363   |   0.6287   |   -0.0214   |   0.1000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.6919   |   0.6515   |   -0.0330   |   0.1093   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.3538   |   0.6628   |   0.0203   |   0.0657   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.6919   |   0.6881   |   -0.0393   |   0.1205   |
| [percival2014/stem](#percival2014stem)             |   -0.6983   |   0.7411   |   -0.0191   |   0.2769   |

<a name="table9"></a>Table 9: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/wjd_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/wjd_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/wjd_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure20"></a>Figure 20: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure21"></a>Figure 21: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3798   | __0.5469__ |   -0.0005   | __0.0131__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.2908   |   0.5629   |   -0.0036   |   0.0731   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __-0.2829__ |   0.5702   | __-0.0000__ |   0.0649   |
| [schreiber2014/default](#schreiber2014default)     |   -0.7786   |   0.5869   |   -0.0330   |   0.1120   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.4347   |   0.6288   |   -0.0198   |   0.0995   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.6902   |   0.6510   |   -0.0313   |   0.1087   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.3521   |   0.6626   |   0.0220   |   0.0649   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.6902   |   0.6877   |   -0.0377   |   0.1201   |
| [percival2014/stem](#percival2014stem)             |   -0.6966   |   0.7402   |   -0.0174   |   0.2765   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/wjd_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/wjd_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/wjd_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure22"></a>Figure 22: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2530   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0243__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2530   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0048__ | __0.0018__ | __0.0033__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0012__ |   0.8177   |   0.8110   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0012__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.8177   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.8110   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0048__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.6148   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0243__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0033__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6148   | __0.0000__ |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2530   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0243__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2530   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0048__ | __0.0018__ | __0.0033__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0012__ |   0.8177   |   0.8110   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0012__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.8177   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.8110   | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0048__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.6148   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0243__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0033__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6148   | __0.0000__ |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1911   | __0.0000__ | __0.0000__ | __0.0000__ |   0.8880   | __0.0000__ |   0.3670   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0032__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1911   | __0.0032__ |   1.0000   |   0.2589   |   0.1183   |   0.2850   |   0.1921   |   0.8591   |   0.2969   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.2589   |   1.0000   |   0.3157   |   0.7151   | __0.0000__ | __0.0101__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.1183   |   0.3157   |   1.0000   |   0.0521   | __0.0000__ | __0.0008__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.2850   |   0.7151   |   0.0521   |   1.0000   | __0.0000__ | __0.0166__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8880   | __0.0000__ |   0.1921   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2090   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.8591   | __0.0101__ | __0.0008__ | __0.0166__ | __0.0000__ |   1.0000   | __0.0003__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3670   | __0.0000__ |   0.2969   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2090   | __0.0003__ |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.1911   | __0.0000__ | __0.0000__ | __0.0000__ |   0.8880   | __0.0000__ |   0.3670   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0032__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1911   | __0.0032__ |   1.0000   |   0.2589   |   0.1183   |   0.2850   |   0.1921   |   0.8591   |   0.2969   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.2589   |   1.0000   |   0.3157   |   0.7151   | __0.0000__ | __0.0101__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.1183   |   0.3157   |   1.0000   |   0.0521   | __0.0000__ | __0.0008__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.2850   |   0.7151   |   0.0521   |   1.0000   | __0.0000__ | __0.0166__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8880   | __0.0000__ |   0.1921   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.2090   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.8591   | __0.0101__ | __0.0008__ | __0.0166__ | __0.0000__ |   1.0000   | __0.0003__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3670   | __0.0000__ |   0.2969   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2090   | __0.0003__ |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_oe1.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean OE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_oe1.png "Open Figure") 

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_oe1.svg">
</figure>

<a name="figure25"></a>Figure 25: Mean OE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_oe2.svg">
</figure>

<a name="figure26"></a>Figure 26: Mean OE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_oe2.png "Open Figure") 

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_oe2.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean OE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure29"></a>Figure 29: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure30"></a>Figure 30: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure32"></a>Figure 32: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure33"></a>Figure 33: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure34"></a>Figure 34: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure35"></a>Figure 35: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.4102__ | __0.4844__ |   0.0246   |   0.0697   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4122   |   0.4862   |   0.0224   |   0.0619   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.4385   |   0.5024   | __0.0107__ | __0.0147__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5266   |   0.5554   |   0.0363   |   0.0956   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5634   |   0.4971   |   0.0322   |   0.0607   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7638   |   0.5656   |   0.0401   |   0.1069   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7812   |   0.5848   |   0.0473   |   0.1176   |
| [percival2014/stem](#percival2014stem)             |   0.8097   |   0.6174   |   0.0518   |   0.2727   |
| [schreiber2014/default](#schreiber2014default)     |   0.8311   |   0.5130   |   0.0448   |   0.1084   |

<a name="table15"></a>Table 15: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/wjd_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/wjd_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/wjd_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/wjd_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/wjd_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure36"></a>Figure 36: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure37"></a>Figure 37: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.4088__ | __0.4841__ |   0.0237   |   0.0693   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4109   |   0.4861   |   0.0214   |   0.0613   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.4368   |   0.5025   | __0.0092__ | __0.0094__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5251   |   0.5556   |   0.0353   |   0.0951   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5628   |   0.4963   |   0.0328   |   0.0602   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7619   |   0.5655   |   0.0385   |   0.1063   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7793   |   0.5848   |   0.0457   |   0.1172   |
| [percival2014/stem](#percival2014stem)             |   0.8079   |   0.6168   |   0.0502   |   0.2725   |
| [schreiber2014/default](#schreiber2014default)     |   0.8292   |   0.5128   |   0.0439   |   0.1082   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/wjd_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/wjd_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/wjd_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/wjd_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/wjd_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/wjd_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure38"></a>Figure 38: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure39"></a>Figure 39: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/wjd_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2297   | __0.0002__ |   0.1843   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1453   | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   |   0.3781   |   0.2559   |   0.0551   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.3781   |   1.0000   | __0.0141__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2559   | __0.0141__ |   1.0000   |   0.2183   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0551   | __0.0005__ |   0.2183   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2297   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8929   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0002__ |   0.1453   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1843   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8929   | __0.0000__ |   1.0000   |

<a name="table17"></a>Table 17: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2236   | __0.0002__ |   0.1792   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1556   | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   |   0.3780   |   0.2561   |   0.0555   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.3780   |   1.0000   | __0.0141__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.2561   | __0.0141__ |   1.0000   |   0.2189   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0555   | __0.0005__ |   0.2189   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.2236   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.8940   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0002__ |   0.1556   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1792   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8940   | __0.0000__ |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.1790   | __0.0450__ | __0.0295__ |   0.3036   | __0.0029__ |   0.6070   | __0.0219__ |
| [percival2014/stem](#percival2014stem)             | __0.0014__ |   0.1790   |   1.0000   |   0.6005   |   0.7264   |   0.3585   | __0.0255__ |   0.2521   | __0.0420__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0450__ |   0.6005   |   1.0000   |   0.6790   |   0.2439   | __0.0000__ |   0.0816   | __0.0002__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0295__ |   0.7264   |   0.6790   |   1.0000   | __0.0193__ | __0.0000__ | __0.0429__ | __0.0002__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.3036   |   0.3585   |   0.2439   | __0.0193__ |   1.0000   | __0.0016__ |   0.4933   | __0.0071__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0029__ | __0.0255__ | __0.0000__ | __0.0000__ | __0.0016__ |   1.0000   | __0.0005__ |   0.3602   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.6070   |   0.2521   |   0.0816   | __0.0429__ |   0.4933   | __0.0005__ |   1.0000   | __0.0031__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0219__ | __0.0420__ | __0.0002__ | __0.0002__ | __0.0071__ |   0.3602   | __0.0031__ |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0014__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.1315   | __0.0231__ | __0.0113__ |   0.1579   | __0.0098__ |   0.3967   |   0.0535   |
| [percival2014/stem](#percival2014stem)             | __0.0014__ |   0.1315   |   1.0000   |   0.5648   |   0.7250   |   0.3586   | __0.0231__ |   0.2363   | __0.0374__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0231__ |   0.5648   |   1.0000   |   0.5816   |   0.3011   | __0.0000__ |   0.0860   | __0.0002__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0113__ |   0.7250   |   0.5816   |   1.0000   | __0.0198__ | __0.0000__ | __0.0345__ | __0.0001__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ |   0.1579   |   0.3586   |   0.3011   | __0.0198__ |   1.0000   | __0.0012__ |   0.4285   | __0.0051__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0098__ | __0.0231__ | __0.0000__ | __0.0000__ | __0.0012__ |   1.0000   | __0.0005__ |   0.3855   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.3967   |   0.2363   |   0.0860   | __0.0345__ |   0.4285   | __0.0005__ |   1.0000   | __0.0027__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ |   0.0535   | __0.0374__ | __0.0002__ | __0.0001__ | __0.0051__ |   0.3855   | __0.0027__ |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/wjd_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/wjd_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/wjd_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure40"></a>Figure 40: Mean AOE<sub>1</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_aoe1.svg">
</figure>

<a name="figure41"></a>Figure 41: Mean AOE<sub>1</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure42"></a>Figure 42: Mean AOE<sub>2</sub> compared to version [1.0](#10) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.0](#10).

[CSV](data/wjd_estimates_1.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_1.0_cv_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 2.0 based on c<sub>var</sub>-Values from 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_1.0_cv_aoe2.svg">
</figure>

<a name="figure43"></a>Figure 43: Mean AOE<sub>2</sub> compared to version [2.0](#20) for tracks with c<sub>var</sub> < τ based on beat annotations from [2.0](#20).

[CSV](data/wjd_estimates_2.0_1.0_cv_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_1.0_cv_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_1.0_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_1.0_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_1.0_cv_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_1.0_cv_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_1.0_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure44"></a>Figure 44: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure45"></a>Figure 45: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure46"></a>Figure 46: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/wjd_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure47"></a>Figure 47: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/wjd_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure48"></a>Figure 48: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure49"></a>Figure 49: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure50"></a>Figure 50: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/wjd_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure51"></a>Figure 51: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/wjd_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/wjd_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/wjd_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/wjd_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/wjd_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/wjd_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/wjd_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-05 19:41. Size L.
