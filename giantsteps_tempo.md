---
title: giantsteps_tempo
{:.no_toc}
layout: default
---

# giantsteps_tempo
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'giantsteps_tempo' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'giantsteps_tempo'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | GiantSteps Tempo |
| **Version** | 1.0 |
| **Curator** | [Peter Knees](mailto:peter.knees@jku.at) |
| **Validation** | http://www.cp.jku.at/datasets/giantsteps/ |
| **Data&nbsp;Source** | P. Knees, Á. Faraldo, P. Herrera, R. Vogl, S. Böck, F. Hörschläger, and M. Le Goff.: 'Two Data Sets for Tempo Estimation and Key Detection in Electronic Dance Music Annotated from User Corrections.' In Proc. of the 16th International Society for Music Information Retrieval Conference (ISMIR), Málaga, Spain, 2015. |
| **Annotation&nbsp;Tools** | Beatport Forum |

### 2.0

| Attribute | Value |
| --- | --- |
| **Corpus** | GiantSteps Tempo |
| **Version** | 2.0 |
| **Curator** | [Hendrik Schreiber](mailto:hs@tagtraum.com) |
| **Data&nbsp;Source** | crowdsource |
| **Annotation&nbsp;Tools** | crowdsourced, web-based experiment |
| **Annotator,&nbsp;bibtex** |[Schreiber2018b](bib/Schreiber2018b.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.tagtraum.com/tempo\_estimation.html](http://www.tagtraum.com/tempo_estimation.html) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   664   |   53.00   |   200.00   |   136.66   |   28.35   |   91.00   |   0.88   |
| [2.0](#20)                                         |   661   |   64.00   |   197.00   |   138.58   |   25.91   |   90.00   |   0.92   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/giantsteps_tempo_reference_basic_stats.csv "Download data as CSV") [JSON](data/giantsteps_tempo_reference_basic_stats.json "Download data as JSON") [LATEX](data/giantsteps_tempo_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/giantsteps_tempo_reference_dist.csv "Download data as CSV") [JSON](data/giantsteps_tempo_reference_dist.json "Download data as JSON") [LATEX](data/giantsteps_tempo_reference_dist.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_reference_dist.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_reference_dist.svg "Open Figure") [PDF](figures/giantsteps_tempo_reference_dist.pdf "Open Figure") [PNG](figures/giantsteps_tempo_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/giantsteps_tempo_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/giantsteps_tempo_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/giantsteps_tempo_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/giantsteps_tempo_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/giantsteps_tempo_reference_1.0_tag_open.png "Open Figure") 

# Estimates for 'giantsteps_tempo'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | giantsteps_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   664   |   41.10   |   214.29   |   112.49   |   37.34   |   74.00   |   0.70   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   664   |   63.80   |   191.41   |   115.46   |   27.09   |   84.00   |   0.89   |
| [percival2014/stem](#percival2014stem)             |   664   |   54.98   |   160.25   |   106.59   |   27.22   |   75.00   |   0.85   |
| [schreiber2014/default](#schreiber2014default)     |   664   |   63.03   |   171.91   |   112.05   |   27.01   |   78.00   |   0.87   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   664   |   41.87   |   160.00   |   120.14   |   24.05   |   81.00   |   1.00   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   664   |   41.87   |   160.00   |   120.14   |   24.05   |   81.00   |   1.00   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   664   |   67.00   |   216.00   |   135.25   |   27.24   |   90.00   |   0.88   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   664   |   63.00   |   201.00   |   138.38   |   26.85   |   90.00   |   0.90   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   664   |   69.00   |   186.00   |   129.66   |   26.96   |   89.00   |   0.84   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/giantsteps_tempo_estimates_basic_stats.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_basic_stats.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/giantsteps_tempo_estimates_dist.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_dist.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_dist.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_dist.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_dist.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.7982__ | __0.9066__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.7636   |   0.8931   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.7349   |   0.8946   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6310   |   0.8870   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6310   |   0.8870   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5798   |   0.8630   |
| [schreiber2014/default](#schreiber2014default)     |   0.5663   |   0.8690   |
| [percival2014/stem](#percival2014stem)             |   0.5151   |   0.8855   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2666   |   0.4639   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/giantsteps_tempo_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_accuracy2.png "Open Figure") 

### Accuracy Results for 2.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.8986__ | __0.9803__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8638   |   0.9758   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8245   |   0.9758   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7050   |   0.9561   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.7050   |   0.9561   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6384   |   0.9410   |
| [schreiber2014/default](#schreiber2014default)     |   0.6051   |   0.9319   |
| [percival2014/stem](#percival2014stem)             |   0.5703   |   0.9607   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3540   |   0.5325   |

<a name="table4"></a>Table 4: Mean accuracy of estimates compared to version [2.0](#20) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/giantsteps_tempo_estimates_2.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (279 differences):*
'1030011.LOFI' '1068430.LOFI' '1092771.LOFI' '1177875.LOFI' '1198571.LOFI' '1234668.LOFI' '1240669.LOFI' '1240672.LOFI' '1317507.LOFI' '1327052.LOFI' '1329955.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (487 differences):*
'1030011.LOFI' '1068430.LOFI' '1084996.LOFI' '1092771.LOFI' '1114156.LOFI' '1118326.LOFI' '1120171.LOFI' '1171800.LOFI' '1174239.LOFI' '1177875.LOFI' '1183908.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (322 differences):*
'1030011.LOFI' '1068430.LOFI' '1092771.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1177875.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1240672.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (288 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1177875.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1240672.LOFI' '1317507.LOFI' '1327052.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (245 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1240672.LOFI' '1317507.LOFI' '1327052.LOFI' '1380256.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (245 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1240672.LOFI' '1317507.LOFI' '1327052.LOFI' '1380256.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (157 differences):*
'1114156.LOFI' '1240669.LOFI' '1240672.LOFI' '1327052.LOFI' '1329955.LOFI' '1461087.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1747518.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (134 differences):*
'1327052.LOFI' '1329955.LOFI' '1461087.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1765409.LOFI' '1885798.LOFI' '1905592.LOFI' '1950701.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (176 differences):*
'1068430.LOFI' '1327052.LOFI' '1461087.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1765409.LOFI' '1817444.LOFI' '1855660.LOFI' '1905591.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (239 differences):*
'1030011.LOFI' '1068430.LOFI' '1092771.LOFI' '1177875.LOFI' '1198571.LOFI' '1234668.LOFI' '1240669.LOFI' '1317507.LOFI' '1329955.LOFI' '1380256.LOFI' '1418652.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (427 differences):*
'1030011.LOFI' '1068430.LOFI' '1084996.LOFI' '1092771.LOFI' '1114156.LOFI' '1118326.LOFI' '1120171.LOFI' '1171800.LOFI' '1174239.LOFI' '1177875.LOFI' '1183908.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (284 differences):*
'1030011.LOFI' '1068430.LOFI' '1092771.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1177875.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1317507.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (261 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1177875.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1317507.LOFI' '1329955.LOFI' '1380256.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (195 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1317507.LOFI' '1380256.LOFI' '1418652.LOFI' '1569136.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (195 differences):*
'1068430.LOFI' '1118326.LOFI' '1120171.LOFI' '1174239.LOFI' '1234668.LOFI' '1234669.LOFI' '1240669.LOFI' '1317507.LOFI' '1380256.LOFI' '1418652.LOFI' '1569136.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (90 differences):*
'1114156.LOFI' '1240669.LOFI' '1329955.LOFI' '1418652.LOFI' '1698047.LOFI' '1743969.LOFI' '1874244.LOFI' '1905591.LOFI' '2083969.LOFI' '2757093.LOFI' '3023605.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (67 differences):*
'1240672.LOFI' '1329955.LOFI' '1418652.LOFI' '1698047.LOFI' '1743969.LOFI' '1747518.LOFI' '1885798.LOFI' '2083969.LOFI' '2741734.LOFI' '3013673.LOFI' '3023605.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (116 differences):*
'1240672.LOFI' '1418652.LOFI' '1698047.LOFI' '1747518.LOFI' '1817444.LOFI' '1855660.LOFI' '1905591.LOFI' '1929611.LOFI' '2706792.LOFI' '2734649.LOFI' '2734862.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 12 items 'correctly' using Accuracy<sub>1</sub>:__
'3630279.LOFI' '3642438.LOFI' '3787878.LOFI' '3801596.LOFI' '3907042.LOFI' '3920460.LOFI' '3980001.LOFI' '4625875.LOFI' '5089294.LOFI' '5137154.LOFI' '5214755.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (91 differences):*
'1240669.LOFI' '1327052.LOFI' '1479462.LOFI' '1698047.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1747518.LOFI' '1905592.LOFI' '1950701.LOFI' '2726350.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (356 differences):*
'1030011.LOFI' '1068430.LOFI' '1084996.LOFI' '1092771.LOFI' '1114156.LOFI' '1118326.LOFI' '1120171.LOFI' '1171800.LOFI' '1174239.LOFI' '1177875.LOFI' '1183908.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (76 differences):*
'1030011.LOFI' '1327052.LOFI' '1329955.LOFI' '1424458.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1874244.LOFI' '1905592.LOFI' '2432724.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (87 differences):*
'1327052.LOFI' '1380256.LOFI' '1418652.LOFI' '1479462.LOFI' '1676961.LOFI' '1735621.LOFI' '1743969.LOFI' '1905592.LOFI' '1974485.LOFI' '2676506.LOFI' '2726350.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (75 differences):*
'1327052.LOFI' '1380256.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1905592.LOFI' '1974485.LOFI' '2422602.LOFI' '2726350.LOFI' '2726353.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (75 differences):*
'1327052.LOFI' '1380256.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1905592.LOFI' '1974485.LOFI' '2422602.LOFI' '2726350.LOFI' '2726353.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (71 differences):*
'1327052.LOFI' '1329955.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1874244.LOFI' '1905592.LOFI' '2726350.LOFI' '2726353.LOFI' '2726355.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (62 differences):*
'1327052.LOFI' '1329955.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1905592.LOFI' '2726350.LOFI' '2726353.LOFI' '2726355.LOFI' '2745205.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (70 differences):*
'1068430.LOFI' '1327052.LOFI' '1479462.LOFI' '1728723.LOFI' '1735621.LOFI' '1743969.LOFI' '1905591.LOFI' '1905592.LOFI' '2726350.LOFI' '2726353.LOFI' '2726355.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (39 differences):*
'1240669.LOFI' '1418652.LOFI' '1747518.LOFI' '3069960.LOFI' '3312045.LOFI' '3377892.LOFI' '3414605.LOFI' '3480108.LOFI' '3509304.LOFI' '3564559.LOFI' '3630279.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (309 differences):*
'1030011.LOFI' '1068430.LOFI' '1084996.LOFI' '1092771.LOFI' '1114156.LOFI' '1118326.LOFI' '1120171.LOFI' '1171800.LOFI' '1174239.LOFI' '1177875.LOFI' '1183908.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [percival2014/stem](#percival2014stem) (26 differences):*
'1030011.LOFI' '1329955.LOFI' '1418652.LOFI' '1424458.LOFI' '1874244.LOFI' '2432724.LOFI' '3435022.LOFI' '3480108.LOFI' '3565815.LOFI' '3711752.LOFI' '3787878.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2014/default](#schreiber2014default) (45 differences):*
'1380256.LOFI' '1418652.LOFI' '1676961.LOFI' '1728723.LOFI' '1974485.LOFI' '2676506.LOFI' '2759853.LOFI' '3013772.LOFI' '3023605.LOFI' '3069960.LOFI' '3128068.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (29 differences):*
'1380256.LOFI' '1418652.LOFI' '1974485.LOFI' '2422602.LOFI' '3023605.LOFI' '3069960.LOFI' '3480108.LOFI' '3630279.LOFI' '3642438.LOFI' '3692859.LOFI' '3787878.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (29 differences):*
'1380256.LOFI' '1418652.LOFI' '1974485.LOFI' '2422602.LOFI' '3023605.LOFI' '3069960.LOFI' '3480108.LOFI' '3630279.LOFI' '3642438.LOFI' '3692859.LOFI' '3787878.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/cnn](#schreiber2018cnn) (16 differences):*
'1329955.LOFI' '1418652.LOFI' '1874244.LOFI' '3023605.LOFI' '3069960.LOFI' '3480108.LOFI' '3630279.LOFI' '3642438.LOFI' '3787878.LOFI' '4044591.LOFI' '4283854.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/fcn](#schreiber2018fcn) (13 differences):*
'1329955.LOFI' '1418652.LOFI' '3023605.LOFI' '3480108.LOFI' '3630279.LOFI' '3642438.LOFI' '3787878.LOFI' '4043892.LOFI' '4288893.LOFI' '4332592.LOFI' '5137153.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[2.0](#20) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (16 differences):*
'1418652.LOFI' '1905591.LOFI' '3069960.LOFI' '3189712.LOFI' '3480108.LOFI' '3630279.LOFI' '3642438.LOFI' '3787878.LOFI' '4043892.LOFI' '4044591.LOFI' '4288893.LOFI' ...
[CSV](data/giantsteps_tempo_estimates_2.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>2</sub>:__
'3787878.LOFI' 
[CSV](data/giantsteps_tempo_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0026__ |   0.5938   | __0.0144__ | __0.0144__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0026__ | __0.0000__ |   1.0000   | __0.0047__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.5938   | __0.0000__ | __0.0047__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0144__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0144__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0044__ |   0.0536   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0044__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0536   | __0.0000__ |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0022__ |   0.1716   | __0.0021__ | __0.0021__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0022__ | __0.0000__ |   1.0000   |   0.0620   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1716   | __0.0000__ |   0.0620   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0021__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0021__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0059__ | __0.0099__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0099__ | __0.0000__ |   1.0000   |

<a name="table6"></a>Table 6: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0444__ |   0.6936   | __0.0166__ | __0.0166__ | __0.0022__ | __0.0000__ | __0.0015__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0444__ | __0.0000__ |   1.0000   |   0.1690   |   1.0000   |   1.0000   |   0.4049   | __0.0043__ |   0.3771   |
| [schreiber2014/default](#schreiber2014default)     |   0.6936   | __0.0000__ |   0.1690   |   1.0000   |   0.0576   |   0.0576   | __0.0195__ | __0.0001__ | __0.0161__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0166__ | __0.0000__ |   1.0000   |   0.0576   |   1.0000   |   1.0000   |   0.5235   | __0.0044__ |   0.3833   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0166__ | __0.0000__ |   1.0000   |   0.0576   |   1.0000   |   1.0000   |   0.5235   | __0.0044__ |   0.3833   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0022__ | __0.0000__ |   0.4049   | __0.0195__ |   0.5235   |   0.5235   |   1.0000   | __0.0117__ |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0043__ | __0.0001__ | __0.0044__ | __0.0044__ | __0.0117__ |   1.0000   | __0.0386__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0015__ | __0.0000__ |   0.3771   | __0.0161__ |   0.3833   |   0.3833   |   1.0000   | __0.0386__ |   1.0000   |

<a name="table7"></a>Table 7: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.0725   |   0.5044   |   0.1433   |   0.1433   | __0.0003__ | __0.0000__ | __0.0002__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.0725   | __0.0000__ |   1.0000   | __0.0127__ |   0.7283   |   0.7283   |   0.0639   | __0.0072__ |   0.0987   |
| [schreiber2014/default](#schreiber2014default)     |   0.5044   | __0.0000__ | __0.0127__ |   1.0000   | __0.0052__ | __0.0052__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1433   | __0.0000__ |   0.7283   | __0.0052__ |   1.0000   |   1.0000   | __0.0106__ | __0.0001__ | __0.0072__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1433   | __0.0000__ |   0.7283   | __0.0052__ |   1.0000   |   1.0000   | __0.0106__ | __0.0001__ | __0.0072__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0003__ | __0.0000__ |   0.0639   | __0.0000__ | __0.0106__ | __0.0106__ |   1.0000   |   0.5488   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0072__ | __0.0000__ | __0.0001__ | __0.0001__ |   0.5488   |   1.0000   |   0.5488   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0002__ | __0.0000__ |   0.0987   | __0.0000__ | __0.0072__ | __0.0072__ |   1.0000   |   0.5488   |   1.0000   |

<a name="table8"></a>Table 8: McNemar p-values, using reference annotations [2.0](#20) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_accuracy1.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure12"></a>Figure 12: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

#### Estimated Accuracy<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure13"></a>Figure 13: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure14"></a>Figure 14: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

#### Estimated Accuracy<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure15"></a>Figure 15: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Accuracy<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.svg">
</figure>

<a name="figure19"></a>Figure 19: Mean Accuracy<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_accuracy2.png "Open Figure") 

## MIREX-Style Evaluation

P-Score is defined as the average of two tempi weighted by their perceptual strength, allowing an 8% tolerance for both tempo values [[MIREX 2006 Definition](https://www.music-ir.org/mirex/wiki/2006:Audio_Tempo_Extraction#Evaluation_Procedures)].

One Correct is the fraction of estimate pairs of which at least one of the two values is equal to a reference value (within an 8% tolerance).

Both Correct is the fraction of estimate pairs of which both values are equal to the reference values (within an 8% tolerance).

See [[McKinney2007](bib/McKinney2007.bib)].

*Note: Very few datasets actually have multiple annotations per track along with a salience distributions. References without suitable annotations are not shown.*

### MIREX Results for 2.0

| Estimator| P-Score | One Correct | Both Correct |
| ---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9636__ | __0.9955__ | __0.6354__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9572   |   0.9939   |   0.6157   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9564   |   0.9924   |   0.6142   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.9207   |   0.9758   |   0.6112   |
| [schreiber2014/default](#schreiber2014default)     |   0.9119   |   0.9531   |   0.6021   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9101   |   0.9758   |   0.5915   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8442   |   0.9818   |   0.3132   |
| [percival2014/stem](#percival2014stem)             |   0.5909   |   0.8956   |   0.0408   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4060   |   0.5507   |   0.2148   |

<a name="table9"></a>Table 9: Compared to [2.0](#20) with 8.0% tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_tolerance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tolerance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tolerance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tolerance.pickle "Download data as PICKLE") 

Raw data P-Score: [CSV](data/giantsteps_tempo_estimates_2.0_raw_p-score.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_p-score.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_p-score.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_p-score.pickle "Download raw data as PICKLE") 

Raw data One Correct: [CSV](data/giantsteps_tempo_estimates_2.0_raw_one_correct.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_one_correct.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_one_correct.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_one_correct.pickle "Download raw data as PICKLE") 

Raw data Both Correct: [CSV](data/giantsteps_tempo_estimates_2.0_raw_both_correct.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_both_correct.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_both_correct.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_both_correct.pickle "Download raw data as PICKLE") 

### P-Score for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_p-score.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean P-Score for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_p-score.png "Open Figure") 

### One Correct for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_one_correct.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean One Correct for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_one_correct.png "Open Figure") 

### Both Correct for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_both_correct.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean Both Correct for estimates compared to version [2.0](#20) depending on tolerance.

[CSV](data/giantsteps_tempo_estimates_2.0_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_both_correct.png "Open Figure") 

### P-Score on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean P-Score for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### P-Score on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_p-score.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean P-Score for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_p-score.png "Open Figure") 

#### P-Score on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_p-score.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean P-Score for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_p-score.png "Open Figure") 

### One Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean One Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### One Correct on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_one_correct.svg">
</figure>

<a name="figure25"></a>Figure 25: Mean One Correct for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_one_correct.png "Open Figure") 

#### One Correct on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_one_correct.svg">
</figure>

<a name="figure26"></a>Figure 26: Mean One Correct for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_one_correct.png "Open Figure") 

### Both Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Both Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Both Correct on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_both_correct.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean Both Correct for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_both_correct.png "Open Figure") 

#### Both Correct on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_both_correct.svg">
</figure>

<a name="figure28"></a>Figure 28: Mean Both Correct for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_both_correct.png "Open Figure") 

### Estimated P-Score for Tempo

When fitting a generalized additive model (GAM) to P-Score-values and a ground truth, what P-Score can we expect with confidence?

#### Estimated P-Score for Tempo for 1.0

Predictions of GAMs trained on P-Score for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.svg">
</figure>

<a name="figure29"></a>Figure 29: P-Score predictions of a generalized additive model (GAM) fit to P-Score results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_p-score.png "Open Figure") 

#### Estimated P-Score for Tempo for 2.0

Predictions of GAMs trained on P-Score for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.svg">
</figure>

<a name="figure30"></a>Figure 30: P-Score predictions of a generalized additive model (GAM) fit to P-Score results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_p-score.png "Open Figure") 

### Estimated One Correct for Tempo

When fitting a generalized additive model (GAM) to One Correct-values and a ground truth, what One Correct can we expect with confidence?

#### Estimated One Correct for Tempo for 1.0

Predictions of GAMs trained on One Correct for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.svg">
</figure>

<a name="figure31"></a>Figure 31: One Correct predictions of a generalized additive model (GAM) fit to One Correct results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_one_correct.png "Open Figure") 

#### Estimated One Correct for Tempo for 2.0

Predictions of GAMs trained on One Correct for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.svg">
</figure>

<a name="figure32"></a>Figure 32: One Correct predictions of a generalized additive model (GAM) fit to One Correct results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_one_correct.png "Open Figure") 

### Estimated Both Correct for Tempo

When fitting a generalized additive model (GAM) to Both Correct-values and a ground truth, what Both Correct can we expect with confidence?

#### Estimated Both Correct for Tempo for 1.0

Predictions of GAMs trained on Both Correct for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.svg">
</figure>

<a name="figure33"></a>Figure 33: Both Correct predictions of a generalized additive model (GAM) fit to Both Correct results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_both_correct.png "Open Figure") 

#### Estimated Both Correct for Tempo for 2.0

Predictions of GAMs trained on Both Correct for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.svg">
</figure>

<a name="figure34"></a>Figure 34: Both Correct predictions of a generalized additive model (GAM) fit to Both Correct results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_both_correct.png "Open Figure") 

### P-Score for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### P-Score for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean P-Score of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_p-score.png "Open Figure") 

#### P-Score for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.svg">
</figure>

<a name="figure36"></a>Figure 36: Mean P-Score of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_p-score.png "Open Figure") 

### One Correct for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### One Correct for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.svg">
</figure>

<a name="figure37"></a>Figure 37: Mean One Correct of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_one_correct.png "Open Figure") 

#### One Correct for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.svg">
</figure>

<a name="figure38"></a>Figure 38: Mean One Correct of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_one_correct.png "Open Figure") 

### Both Correct for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Both Correct for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.svg">
</figure>

<a name="figure39"></a>Figure 39: Mean Both Correct of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_both_correct.png "Open Figure") 

#### Both Correct for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.svg">
</figure>

<a name="figure40"></a>Figure 40: Mean Both Correct of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[CSV](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_both_correct.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0231   | __0.3658__ | __-0.0025__ | __0.0874__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __-0.0118__ |   0.3910   |   -0.0052   |   0.0981   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.0744   |   0.4236   |   -0.0045   |   0.0917   |
| [schreiber2014/default](#schreiber2014default)     |   -0.2953   |   0.4982   |   -0.0056   |   0.1088   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1820   |   0.5024   |   -0.0058   |   0.0985   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1820   |   0.5024   |   -0.0058   |   0.0985   |
| [percival2014/stem](#percival2014stem)             |   -0.3716   |   0.5215   |   0.0130   |   0.1003   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.2466   |   0.5271   |   0.1751   |   0.2304   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3380   |   0.6087   |   -0.0163   |   0.1192   |

<a name="table10"></a>Table 10: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/giantsteps_tempo_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure41"></a>Figure 41: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure42"></a>Figure 42: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_distribution_oe2.png "Open Figure") 

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 2.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __-0.0020__ | __0.2935__ |   0.0010   | __0.0465__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   -0.0388   |   0.3414   | __0.0005__ |   0.0568   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   -0.1022   |   0.3833   |   -0.0008   |   0.0541   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.2080   |   0.4643   |   -0.0037   |   0.0691   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.2080   |   0.4643   |   -0.0037   |   0.0691   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   -0.2755   |   0.4871   |   0.1805   |   0.2200   |
| [percival2014/stem](#percival2014stem)             |   -0.3978   |   0.4936   |   0.0121   |   0.0723   |
| [schreiber2014/default](#schreiber2014default)     |   -0.3239   |   0.4941   |   -0.0046   |   0.0874   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.3658   |   0.5811   |   -0.0120   |   0.0920   |

<a name="table11"></a>Table 11: Mean OE1/OE2 for estimates compared to version [2.0](#20) ordered by standard deviation.

[CSV](data/giantsteps_tempo_estimates_2.0_moe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_moe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_moe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_distribution_oe1.svg">
</figure>

<a name="figure43"></a>Figure 43: OE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_2.0_distribution_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_distribution_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_distribution_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_distribution_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_distribution_oe2.svg">
</figure>

<a name="figure44"></a>Figure 44: OE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_2.0_distribution_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_distribution_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_distribution_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_distribution_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0001__ |   0.1542   |   0.0921   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0001__ |   1.0000   | __0.0000__ | __0.0080__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1542   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.0921   | __0.0080__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0031__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0031__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0002__ |   0.1738   |   0.0968   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0002__ |   1.0000   | __0.0000__ | __0.0086__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.1738   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.0968   | __0.0086__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0017__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0017__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table13"></a>Table 13: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0357__ | __0.0267__ | __0.0267__ | __0.0200__ | __0.0018__ | __0.0095__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0357__ | __0.0000__ | __0.0000__ |   1.0000   |   0.9348   |   0.9348   |   0.9175   |   0.3962   |   0.7899   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0267__ | __0.0000__ | __0.0000__ |   0.9348   |   1.0000   |   1.0000   |   0.8205   |   0.2202   |   0.6643   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0267__ | __0.0000__ | __0.0000__ |   0.9348   |   1.0000   |   1.0000   |   0.8205   |   0.2202   |   0.6643   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0200__ | __0.0000__ | __0.0000__ |   0.9175   |   0.8205   |   0.8205   |   1.0000   |   0.2475   |   0.8119   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0018__ | __0.0000__ | __0.0000__ |   0.3962   |   0.2202   |   0.2202   |   0.2475   |   1.0000   |   0.3874   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0095__ | __0.0000__ | __0.0000__ |   0.7899   |   0.6643   |   0.6643   |   0.8119   |   0.3874   |   1.0000   |

<a name="table14"></a>Table 14: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_oe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.0994   | __0.0302__ | __0.0302__ | __0.0014__ | __0.0006__ | __0.0050__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0002__ | __0.0001__ |
| [schreiber2014/default](#schreiber2014default)     |   0.0994   | __0.0000__ | __0.0000__ |   1.0000   |   0.7546   |   0.7546   |   0.1341   |   0.0800   |   0.2735   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0302__ | __0.0000__ | __0.0000__ |   0.7546   |   1.0000   |   1.0000   |   0.0891   | __0.0289__ |   0.2838   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0302__ | __0.0000__ | __0.0000__ |   0.7546   |   1.0000   |   1.0000   |   0.0891   | __0.0289__ |   0.2838   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0014__ | __0.0000__ | __0.0001__ |   0.1341   |   0.0891   |   0.0891   |   1.0000   |   0.7883   |   0.5223   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0006__ | __0.0000__ | __0.0002__ |   0.0800   | __0.0289__ | __0.0289__ |   0.7883   |   1.0000   |   0.3700   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0050__ | __0.0000__ | __0.0001__ |   0.2735   |   0.2838   |   0.2838   |   0.5223   |   0.3700   |   1.0000   |

<a name="table15"></a>Table 15: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure45"></a>Figure 45: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_oe1.png "Open Figure") 

#### OE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_oe1.svg">
</figure>

<a name="figure46"></a>Figure 46: Mean OE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure47"></a>Figure 47: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_oe2.png "Open Figure") 

#### OE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_oe2.svg">
</figure>

<a name="figure48"></a>Figure 48: Mean OE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure49"></a>Figure 49: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

#### Estimated OE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.svg">
</figure>

<a name="figure50"></a>Figure 50: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure51"></a>Figure 51: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

#### Estimated OE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.svg">
</figure>

<a name="figure52"></a>Figure 52: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure53"></a>Figure 53: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

#### OE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe1.svg">
</figure>

<a name="figure54"></a>Figure 54: OE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure55"></a>Figure 55: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

#### OE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe2.svg">
</figure>

<a name="figure56"></a>Figure 56: OE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.1504__ | __0.3342__ | __0.0275__ | __0.0830__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1731   |   0.3508   |   0.0319   |   0.0930   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.2032   |   0.3790   |   0.0295   |   0.0870   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3024   |   0.4406   |   0.0323   |   0.0932   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3024   |   0.4406   |   0.0323   |   0.0932   |
| [schreiber2014/default](#schreiber2014default)     |   0.3589   |   0.4546   |   0.0386   |   0.1019   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.4129   |   0.5606   |   0.0470   |   0.1108   |
| [percival2014/stem](#percival2014stem)             |   0.4278   |   0.4765   |   0.0342   |   0.0952   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4662   |   0.3484   |   0.2141   |   0.1946   |

<a name="table16"></a>Table 16: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/giantsteps_tempo_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure57"></a>Figure 57: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure58"></a>Figure 58: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 2.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0968__ | __0.2771__ | __0.0135__ | __0.0446__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1299   |   0.3182   |   0.0159   |   0.0545   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1683   |   0.3592   |   0.0154   |   0.0519   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2731   |   0.4292   |   0.0207   |   0.0661   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2731   |   0.4292   |   0.0207   |   0.0661   |
| [schreiber2014/default](#schreiber2014default)     |   0.3662   |   0.4636   |   0.0287   |   0.0827   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.3974   |   0.5599   |   0.0302   |   0.0877   |
| [percival2014/stem](#percival2014stem)             |   0.4156   |   0.4787   |   0.0217   |   0.0701   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4325   |   0.3552   |   0.2026   |   0.1998   |

<a name="table17"></a>Table 17: Mean AOE1/AOE2 for estimates compared to version [2.0](#20) ordered by mean.

[CSV](data/giantsteps_tempo_estimates_2.0_maoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_maoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_maoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/giantsteps_tempo_estimates_2.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_distribution_aoe1.svg">
</figure>

<a name="figure59"></a>Figure 59: AOE<sub>1</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_2.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_distribution_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_distribution_aoe2.svg">
</figure>

<a name="figure60"></a>Figure 60: AOE<sub>2</sub> for estimates compared to version [2.0](#20). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/giantsteps_tempo_estimates_2.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_distribution_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0174__ |   0.5153   | __0.0272__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0174__ |   1.0000   | __0.0350__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.5153   | __0.0350__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0272__ | __0.0000__ | __0.0001__ |   1.0000   | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.0509   | __0.0291__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0509   |   1.0000   | __0.0001__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0291__ | __0.0001__ |   1.0000   |

<a name="table18"></a>Table 18: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.1200   |   0.4302   |   0.2061   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1200   |   1.0000   |   0.3503   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.4302   |   0.3503   |   1.0000   | __0.0036__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.2061   | __0.0002__ | __0.0036__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0036__ | __0.0056__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0036__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0056__ | __0.0000__ |   1.0000   |

<a name="table19"></a>Table 19: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0020__ | __0.0475__ | __0.0001__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0020__ | __0.0000__ |   1.0000   |   0.2598   |   0.5591   |   0.5591   |   0.4194   | __0.0184__ |   0.1419   |
| [schreiber2014/default](#schreiber2014default)     | __0.0475__ | __0.0000__ |   0.2598   |   1.0000   | __0.0270__ | __0.0270__ | __0.0411__ | __0.0004__ | __0.0058__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0001__ | __0.0000__ |   0.5591   | __0.0270__ |   1.0000   |   1.0000   |   0.8666   | __0.0237__ |   0.2016   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0001__ | __0.0000__ |   0.5591   | __0.0270__ |   1.0000   |   1.0000   |   0.8666   | __0.0237__ |   0.2016   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ | __0.0000__ |   0.4194   | __0.0411__ |   0.8666   |   0.8666   |   1.0000   | __0.0287__ |   0.2110   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0184__ | __0.0004__ | __0.0237__ | __0.0237__ | __0.0287__ |   1.0000   |   0.3123   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ |   0.1419   | __0.0058__ |   0.2016   |   0.2016   |   0.2110   |   0.3123   |   1.0000   |

<a name="table20"></a>Table 20: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_aoe2_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0360__ |   0.7097   | __0.0076__ | __0.0076__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0360__ | __0.0000__ |   1.0000   |   0.0771   |   0.7435   |   0.7435   | __0.0416__ | __0.0028__ | __0.0431__ |
| [schreiber2014/default](#schreiber2014default)     |   0.7097   | __0.0000__ |   0.0771   |   1.0000   | __0.0048__ | __0.0048__ | __0.0001__ | __0.0000__ | __0.0001__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0076__ | __0.0000__ |   0.7435   | __0.0048__ |   1.0000   |   1.0000   | __0.0478__ | __0.0008__ | __0.0245__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0076__ | __0.0000__ |   0.7435   | __0.0048__ |   1.0000   |   1.0000   | __0.0478__ | __0.0008__ | __0.0245__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0001__ | __0.0000__ | __0.0416__ | __0.0001__ | __0.0478__ | __0.0478__ |   1.0000   |   0.1911   |   0.7931   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0028__ | __0.0000__ | __0.0008__ | __0.0008__ |   0.1911   |   1.0000   |   0.3085   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0431__ | __0.0001__ | __0.0245__ | __0.0245__ |   0.7931   |   0.3085   |   1.0000   |

<a name="table21"></a>Table 21: Paired t-test p-values, using reference annotations [2.0](#20) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/giantsteps_tempo_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure61"></a>Figure 61: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_aoe1.svg">
</figure>

<a name="figure62"></a>Figure 62: Mean AOE<sub>1</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure63"></a>Figure 63: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_inter_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> on Tempo-Subsets for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_inter_aoe2.svg">
</figure>

<a name="figure64"></a>Figure 64: Mean AOE<sub>2</sub> for estimates compared to version [2.0](#20) for tempo intervals around T.

[CSV](data/giantsteps_tempo_estimates_2.0_inter_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_inter_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_inter_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_inter_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure65"></a>Figure 65: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

#### Estimated AOE<sub>1</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure66"></a>Figure 66: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure67"></a>Figure 67: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

#### Estimated AOE<sub>2</sub> for Tempo for 2.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [2.0](#20).

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure68"></a>Figure 68: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [2.0](#20). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_2.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure69"></a>Figure 69: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

#### AOE<sub>1</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe1.svg">
</figure>

<a name="figure70"></a>Figure 70: AOE<sub>1</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe1.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe1.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure71"></a>Figure 71: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

#### AOE<sub>2</sub> for 'tag_open' Tags for 2.0

<figure>
<embed type="image/svg+xml" src="figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe2.svg">
</figure>

<a name="figure72"></a>Figure 72: AOE<sub>2</sub> of estimates compared to version [2.0](#20) depending on tag from namespace 'tag_open'.

[SVG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe2.svg "Open Figure") [PDF](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe2.pdf "Open Figure") [PNG](figures/giantsteps_tempo_estimates_1.0_tag_open_2.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 17:05. Size L.
