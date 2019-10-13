---
title: fma_small
{:.no_toc}
layout: default
---

# fma_small
{:.no_toc}

This is the tempo_eval report for the 'fma_small' corpus.

## Table of Contents
{:.no_toc}

- TOC
{:toc}

> Because reference annotations are not available, we treat the *estimate* [schreiber2018/ismir2018](#schreiber2018ismir2018) as reference. It has the highest Mean Mutual Agreement (MMA), based on Accuracy1 with 4% tolerance.

# References for 'fma_small'

## References

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   7997   |   48.00   |   232.00   |   111.23   |   27.28   |   77.00   |   0.87   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/fma_small_reference_basic_stats.csv "Download data as CSV") [JSON](data/fma_small_reference_basic_stats.json "Download data as JSON") [LATEX](data/fma_small_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/fma_small_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/fma_small_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/fma_small_reference_dist.csv "Download data as CSV") [JSON](data/fma_small_reference_dist.json "Download data as JSON") [LATEX](data/fma_small_reference_dist.latex "Download data as LATEX") [PICKLE](data/fma_small_reference_dist.pickle "Download data as PICKLE") [SVG](figures/fma_small_reference_dist.svg "Open Figure") [PDF](figures/fma_small_reference_dist.pdf "Open Figure") [PNG](figures/fma_small_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_fma_genre'

<figure>
<embed type="image/svg+xml" src="figures/fma_small_reference_1.0.0_tag_fma_genre.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_fma_genre'. Annotations are from reference [1.0.0](#100).

[CSV](data/fma_small_reference_1.0.0_tag_fma_genre.csv "Download data as CSV") [JSON](data/fma_small_reference_1.0.0_tag_fma_genre.json "Download data as JSON") [LATEX](data/fma_small_reference_1.0.0_tag_fma_genre.latex "Download data as LATEX") [PICKLE](data/fma_small_reference_1.0.0_tag_fma_genre.pickle "Download data as PICKLE") [SVG](figures/fma_small_reference_1.0.0_tag_fma_genre.svg "Open Figure") [PDF](figures/fma_small_reference_1.0.0_tag_fma_genre.pdf "Open Figure") [PNG](figures/fma_small_reference_1.0.0_tag_fma_genre.png "Open Figure") 

# Estimates for 'fma_small'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | fma_small |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   7997   |   40.00   |   240.00   |   118.87   |   39.52   |   79.00   |   0.71   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   7970   |   60.09   |   246.09   |   123.15   |   28.40   |   84.00   |   0.89   |
| [percival2014/stem](#percival2014stem)             |   7997   |   50.17   |   inf   |   inf   |   nan   |   71.00   |   0.87   |
| [schreiber2014/default](#schreiber2014default)     |   7994   |   34.99   |   177.59   |   102.26   |   23.82   |   71.00   |   0.86   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   7997   |   10.01   |   176.72   |   105.79   |   30.36   |   81.00   |   0.82   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   7997   |   10.01   |   161.46   |   103.94   |   31.06   |   81.00   |   0.80   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   7997   |   41.00   |   232.00   |   114.44   |   31.45   |   77.00   |   0.80   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   7997   |   35.00   |   232.00   |   110.99   |   32.01   |   76.00   |   0.78   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/fma_small_estimates_basic_stats.csv "Download data as CSV") [JSON](data/fma_small_estimates_basic_stats.json "Download data as JSON") [LATEX](data/fma_small_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/fma_small_estimates_dist.csv "Download data as CSV") [JSON](data/fma_small_estimates_dist.json "Download data as JSON") [LATEX](data/fma_small_estimates_dist.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_dist.svg "Open Figure") [PDF](figures/fma_small_estimates_dist.pdf "Open Figure") [PNG](figures/fma_small_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for schreiber2018/ismir2018

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.7757__ |   0.8798   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.7389   | __0.8812__ |
| [schreiber2014/default](#schreiber2014default)     |   0.7086   |   0.8637   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6963   |   0.8646   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6941   |   0.8647   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.6913   |   0.8727   |
| [percival2014/stem](#percival2014stem)             |   0.6860   |   0.8442   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6541   |   0.7953   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_accuracy_tol04.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_accuracy_tol04.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_accuracy1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_accuracy1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_accuracy1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_accuracy1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_accuracy2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_accuracy2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_accuracy2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_accuracy2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2469 differences):*
'000/000140' '000/000148' '000/000193' '000/000197' '000/000200' '000/000207' '000/000210' '000/000256' '000/000424' '000/000534' '000/000540' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (2766 differences):*
'000/000148' '000/000194' '000/000197' '000/000200' '000/000207' '000/000210' '000/000256' '000/000424' '000/000534' '000/000540' '000/000602' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [percival2014/stem](#percival2014stem) (2511 differences):*
'000/000141' '000/000194' '000/000197' '000/000200' '000/000204' '000/000210' '000/000213' '000/000256' '000/000424' '000/000534' '000/000540' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2014/default](#schreiber2014default) (2330 differences):*
'000/000140' '000/000148' '000/000182' '000/000200' '000/000540' '000/000574' '000/000615' '000/000621' '000/000676' '000/000714' '000/000715' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (2429 differences):*
'000/000141' '000/000148' '000/000194' '000/000207' '000/000424' '000/000534' '000/000540' '000/000574' '000/000621' '000/000676' '000/000714' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (2446 differences):*
'000/000141' '000/000148' '000/000193' '000/000194' '000/000197' '000/000207' '000/000424' '000/000540' '000/000574' '000/000621' '000/000676' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/cnn](#schreiber2018cnn) (1794 differences):*
'000/000005' '000/000148' '000/000193' '000/000207' '000/000424' '000/000459' '000/000534' '000/000540' '000/000546' '000/000615' '000/000625' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/fcn](#schreiber2018fcn) (2088 differences):*
'000/000141' '000/000148' '000/000193' '000/000197' '000/000207' '000/000213' '000/000424' '000/000459' '000/000540' '000/000602' '000/000615' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 470 items 'correctly' using Accuracy<sub>1</sub>:__
'000/000540' '000/000676' '000/000714' '000/000715' '000/000718' '000/000890' '001/001197' '001/001249' '001/001673' '003/003263' '003/003534' ...
[CSV](data/fma_small_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1018 differences):*
'000/000140' '000/000148' '000/000197' '000/000207' '000/000424' '000/000540' '000/000615' '000/000676' '000/000690' '000/000714' '000/000715' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (1637 differences):*
'000/000148' '000/000194' '000/000197' '000/000200' '000/000210' '000/000256' '000/000424' '000/000534' '000/000540' '000/000615' '000/000676' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [percival2014/stem](#percival2014stem) (1246 differences):*
'000/000141' '000/000194' '000/000197' '000/000200' '000/000204' '000/000210' '000/000424' '000/000534' '000/000540' '000/000602' '000/000615' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2014/default](#schreiber2014default) (1090 differences):*
'000/000140' '000/000148' '000/000200' '000/000540' '000/000574' '000/000615' '000/000621' '000/000714' '000/000715' '000/000814' '000/000890' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (1083 differences):*
'000/000141' '000/000148' '000/000194' '000/000424' '000/000540' '000/000714' '000/000715' '000/000718' '000/000814' '000/000890' '000/000892' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1082 differences):*
'000/000141' '000/000148' '000/000194' '000/000424' '000/000540' '000/000714' '000/000715' '000/000718' '000/000814' '000/000890' '000/000892' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/cnn](#schreiber2018cnn) (961 differences):*
'000/000148' '000/000207' '000/000424' '000/000534' '000/000540' '000/000615' '000/000625' '000/000690' '000/000714' '000/000715' '000/000716' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/fcn](#schreiber2018fcn) (950 differences):*
'000/000148' '000/000197' '000/000424' '000/000540' '000/000602' '000/000615' '000/000625' '000/000690' '000/000714' '000/000715' '000/000716' ...
[CSV](data/fma_small_estimates_schreiber2018_ismir2018_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 287 items 'correctly' using Accuracy<sub>2</sub>:__
'000/000540' '000/000714' '000/000715' '000/000890' '001/001197' '001/001249' '001/001673' '003/003263' '003/003537' '003/003832' '004/004017' ...
[CSV](data/fma_small_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.3628   | __0.0029__ |   0.3793   |   0.6184   | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.3628   | __0.0000__ |   1.0000   | __0.0000__ |   0.0611   |   0.1375   | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0029__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0170__ | __0.0051__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3793   | __0.0000__ |   0.0611   | __0.0170__ |   1.0000   |   0.1357   | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.6184   | __0.0000__ |   0.1375   | __0.0051__ |   0.1357   |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0052__ | __0.0113__ | __0.0129__ | __0.0306__ | __0.0093__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0052__ | __0.0000__ | __0.0000__ |   1.0000   |   0.7467   |   0.7067   | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0113__ | __0.0000__ | __0.0000__ |   0.7467   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0129__ | __0.0000__ | __0.0000__ |   0.7067   |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0306__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.6767   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0093__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6767   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[CSV](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.csv "Download data as CSV") [JSON](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.json "Download data as JSON") [LATEX](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[CSV](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.csv "Download data as CSV") [JSON](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.json "Download data as JSON") [LATEX](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_accuracy2.png "Open Figure") 

## MIREX-Style Evaluation

P-Score is defined as the average of two tempi weighted by their perceptual strength, allowing an 8% tolerance for both tempo values [[MIREX 2006 Definition](https://www.music-ir.org/mirex/wiki/2006:Audio_Tempo_Extraction#Evaluation_Procedures)].

One Correct is the fraction of estimate pairs of which at least one of the two values is equal to a reference value (within an 8% tolerance).

Both Correct is the fraction of estimate pairs of which both values are equal to the reference values (within an 8% tolerance).

See [[McKinney2007](bib/McKinney2007.bib)].

*Note: Very few datasets actually have multiple annotations per track along with a salience distributions. References without suitable annotations are not shown.*

### MIREX Results for schreiber2018/ismir2018

| Estimator| P-Score | One Correct | Both Correct |
| ---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.9014__ | __0.9619__ |   0.6694   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8998   |   0.9601   | __0.6805__ |
| [schreiber2014/default](#schreiber2014default)     |   0.8674   |   0.9298   |   0.6620   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8455   |   0.9252   |   0.5156   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8415   |   0.9181   |   0.5318   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8270   |   0.9161   |   0.5026   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7828   |   0.8730   |   0.4542   |
| [percival2014/stem](#percival2014stem)             |   0.6710   |   0.8661   |   0.0121   |

<a name="table6"></a>Table 6: Compared to [schreiber2018/ismir2018](#schreiber2018ismir2018) with 8.0% tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tolerance.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tolerance.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tolerance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tolerance.pickle "Download data as PICKLE") 

Raw data P-Score: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_p-score.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_p-score.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_p-score.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_p-score.pickle "Download raw data as PICKLE") 

Raw data One Correct: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_one_correct.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_one_correct.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_one_correct.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_one_correct.pickle "Download raw data as PICKLE") 

Raw data Both Correct: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_both_correct.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_both_correct.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_both_correct.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_both_correct.pickle "Download raw data as PICKLE") 

### P-Score for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_p-score.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean P-Score for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_p-score.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_p-score.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_p-score.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_p-score.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_p-score.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_p-score.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_p-score.png "Open Figure") 

### One Correct for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_one_correct.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean One Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_one_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_one_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_one_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_one_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_one_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_one_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_one_correct.png "Open Figure") 

### Both Correct for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_both_correct.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Both Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_both_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_both_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_both_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_both_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_both_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_both_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_both_correct.png "Open Figure") 

### P-Score on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean P-Score for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### P-Score on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean P-Score for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_p-score.png "Open Figure") 

### One Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean One Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### One Correct on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean One Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_one_correct.png "Open Figure") 

### Both Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Both Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Both Correct on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean Both Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_both_correct.png "Open Figure") 

### Estimated P-Score for Tempo

When fitting a generalized additive model (GAM) to P-Score-values and a ground truth, what P-Score can we expect with confidence?

#### Estimated P-Score for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on P-Score for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.svg">
</figure>

<a name="figure18"></a>Figure 18: P-Score predictions of a generalized additive model (GAM) fit to P-Score results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_p-score.png "Open Figure") 

### Estimated One Correct for Tempo

When fitting a generalized additive model (GAM) to One Correct-values and a ground truth, what One Correct can we expect with confidence?

#### Estimated One Correct for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on One Correct for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.svg">
</figure>

<a name="figure19"></a>Figure 19: One Correct predictions of a generalized additive model (GAM) fit to One Correct results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.png "Open Figure") 

### Estimated Both Correct for Tempo

When fitting a generalized additive model (GAM) to Both Correct-values and a ground truth, what Both Correct can we expect with confidence?

#### Estimated Both Correct for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Both Correct for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.svg">
</figure>

<a name="figure20"></a>Figure 20: Both Correct predictions of a generalized additive model (GAM) fit to Both Correct results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.png "Open Figure") 

### P-Score for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### P-Score for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean P-Score of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[CSV](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.csv "Download data as CSV") [JSON](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.json "Download data as JSON") [LATEX](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_p-score.png "Open Figure") 

### One Correct for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### One Correct for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean One Correct of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[CSV](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_one_correct.png "Open Figure") 

### Both Correct for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Both Correct for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean Both Correct of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[CSV](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.csv "Download data as CSV") [JSON](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.json "Download data as JSON") [LATEX](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_both_correct.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for schreiber2018/ismir2018

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0306   | __0.3631__ |   0.0096   | __0.1084__ |
| [schreiber2014/default](#schreiber2014default)     |   -0.1181   |   0.4163   |   -0.0045   |   0.1187   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __-0.0213__ |   0.4234   | __0.0001__ |   0.1102   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1518   |   0.4341   |   0.0366   |   0.1452   |
| [percival2014/stem](#percival2014stem)             |   -0.1334   |   0.4610   |   0.0133   |   0.1706   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.0603   |   0.4955   |   -0.0006   |   0.1143   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.1020   |   0.5297   |   -0.0089   |   0.1386   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.1339   |   0.5352   |   -0.0089   |   0.1400   |

<a name="table7"></a>Table 7: Mean OE1/OE2 for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) ordered by standard deviation.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_moe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_moe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_moe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe1.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe1.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe2.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe2.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.svg">
</figure>

<a name="figure24"></a>Figure 24: OE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.svg">
</figure>

<a name="figure25"></a>Figure 25: OE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ |   0.9509   | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0020__ |   1.0000   | __0.0059__ | __0.0173__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.9509   | __0.0173__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0158__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6413   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0802   | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0158__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0100__ | __0.0107__ | __0.0000__ | __0.0048__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0100__ |   1.0000   |   0.8959   | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0107__ |   0.8959   |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.0802   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6413   | __0.0000__ | __0.0000__ | __0.0048__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table9"></a>Table 9: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.svg">
</figure>

<a name="figure26"></a>Figure 26: Mean OE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean OE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.svg">
</figure>

<a name="figure28"></a>Figure 28: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.svg">
</figure>

<a name="figure29"></a>Figure 29: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe1.svg">
</figure>

<a name="figure30"></a>Figure 30: OE<sub>1</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe1.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe2.svg">
</figure>

<a name="figure31"></a>Figure 31: OE<sub>2</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe2.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for schreiber2018/ismir2018

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.1549__ | __0.3298__ | __0.0373__ | __0.1023__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2000   |   0.3738   |   0.0388   |   0.1032   |
| [schreiber2014/default](#schreiber2014default)     |   0.2152   |   0.3754   |   0.0441   |   0.1103   |
| [percival2014/stem](#percival2014stem)             |   0.2402   |   0.4155   |   0.0537   |   0.1625   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2546   |   0.3830   |   0.0766   |   0.1287   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.2635   |   0.4240   |   0.0448   |   0.1052   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2692   |   0.4675   |   0.0467   |   0.1308   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2768   |   0.4773   |   0.0467   |   0.1323   |

<a name="table10"></a>Table 10: Mean AOE1/AOE2 for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) ordered by mean.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_maoe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_maoe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_maoe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe1.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe1.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe2.csv "Download raw data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe2.json "Download raw data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.svg">
</figure>

<a name="figure32"></a>Figure 32: AOE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.svg">
</figure>

<a name="figure33"></a>Figure 33: AOE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.0995   | __0.0001__ | __0.0000__ |   0.3459   | __0.0278__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.0995   |   1.0000   | __0.0054__ | __0.0000__ | __0.0149__ | __0.0002__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0001__ | __0.0054__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0042__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3459   | __0.0149__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0278__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0042__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ |   0.5732   |   0.1496   |   0.1585   | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     |   0.5732   | __0.0000__ | __0.0000__ |   1.0000   |   0.0552   |   0.0616   | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1496   | __0.0000__ | __0.0001__ |   0.0552   |   1.0000   |   0.9928   | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1585   | __0.0000__ | __0.0001__ |   0.0616   |   0.9928   |   1.0000   | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1267   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1267   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/fma_small_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/fma_small_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/fma_small_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.svg">
</figure>

<a name="figure34"></a>Figure 34: Mean AOE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.svg">
</figure>

<a name="figure35"></a>Figure 35: Mean AOE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.svg">
</figure>

<a name="figure36"></a>Figure 36: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.svg">
</figure>

<a name="figure37"></a>Figure 37: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe1.svg">
</figure>

<a name="figure38"></a>Figure 38: AOE<sub>1</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe1.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe1.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_fma_genre' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_fma_genre' Tags for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe2.svg">
</figure>

<a name="figure39"></a>Figure 39: AOE<sub>2</sub> of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tag from namespace 'tag_fma_genre'.

[SVG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe2.svg "Open Figure") [PDF](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe2.pdf "Open Figure") [PNG](figures/fma_small_estimates_1.0.0_tag_fma_genre_schreiber2018_ismir2018_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 11:04. Size L.
