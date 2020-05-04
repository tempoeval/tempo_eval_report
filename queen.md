---
title: queen
{:.no_toc}
layout: default
---

# queen
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'queen' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

> Because reference annotations are not available, we treat the *estimate* [schreiber2018/ismir2018](#schreiber2018ismir2018) as reference. It has the highest Mean Mutual Agreement (MMA), based on Accuracy1 with 4% tolerance.

# References for 'queen'

## References

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** |  |
| **Version** | 0.0.3 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   51   |   69.00   |   156.00   |   104.10   |   23.31   |   67.00   |   0.92   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/queen_reference_basic_stats.csv "Download data as CSV") [JSON](data/queen_reference_basic_stats.json "Download data as JSON") [LATEX](data/queen_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/queen_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/queen_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/queen_reference_dist.csv "Download data as CSV") [JSON](data/queen_reference_dist.json "Download data as JSON") [LATEX](data/queen_reference_dist.latex "Download data as LATEX") [PICKLE](data/queen_reference_dist.pickle "Download data as PICKLE") [SVG](figures/queen_reference_dist.svg "Open Figure") [PDF](figures/queen_reference_dist.pdf "Open Figure") [PNG](figures/queen_reference_dist.png "Open Figure") 

# Estimates for 'queen'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | queen |
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

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   51   |   41.96   |   157.89   |   95.53   |   26.50   |   67.00   |   0.82   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   51   |   71.78   |   166.71   |   120.76   |   26.00   |   81.00   |   0.94   |
| [percival2014/stem](#percival2014stem)             |   51   |   63.41   |   142.56   |   99.08   |   21.25   |   67.00   |   0.96   |
| [schreiber2014/default](#schreiber2014default)     |   51   |   59.73   |   143.87   |   97.74   |   21.00   |   63.00   |   0.92   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   51   |   63.09   |   180.19   |   101.61   |   23.67   |   66.00   |   0.94   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   51   |   44.79   |   180.19   |   100.03   |   25.23   |   66.00   |   0.92   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   51   |   63.00   |   157.00   |   103.78   |   24.44   |   67.00   |   0.90   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   51   |   60.00   |   157.00   |   98.20   |   23.64   |   67.00   |   0.92   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/queen_estimates_basic_stats.csv "Download data as CSV") [JSON](data/queen_estimates_basic_stats.json "Download data as JSON") [LATEX](data/queen_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/queen_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_dist.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of values in tempo interval.

[CSV](data/queen_estimates_dist.csv "Download data as CSV") [JSON](data/queen_estimates_dist.json "Download data as JSON") [LATEX](data/queen_estimates_dist.latex "Download data as LATEX") [PICKLE](data/queen_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_dist.svg "Open Figure") [PDF](figures/queen_estimates_dist.pdf "Open Figure") [PNG](figures/queen_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for schreiber2018/ismir2018

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.9412__ |   0.9608   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8824   |   0.9216   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8824   | __0.9804__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8824   |   0.9608   |
| [percival2014/stem](#percival2014stem)             |   0.8431   |   0.9412   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8235   |   0.9608   |
| [schreiber2014/default](#schreiber2014default)     |   0.8235   |   0.9020   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.7647   |   0.9216   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/queen_estimates_schreiber2018_ismir2018_accuracy_tol04.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_accuracy_tol04.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_accuracy1.svg">
</figure>

<a name="figure3"></a>Figure 3: Mean Accuracy<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_accuracy1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_accuracy1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_accuracy1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_accuracy1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_accuracy1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_accuracy1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_accuracy2.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_accuracy2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_accuracy2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_accuracy2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_accuracy2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_accuracy2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_accuracy2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (9 differences):*
'Greatest Hits II/03 Radio Ga Ga' 'Greatest Hits II/06 Innuendo' 'Greatest Hits II/08 Breakthru' 'Greatest Hits II/10 Headlong' 'Greatest Hits II/16 The Show Must Go On' 'Greatest Hits III/07 Heaven For Everyone' 'Greatest Hits III/09 Driven By You' 'Greatest Hits III/10 Living On My Own' 'Greatest Hits III/12 The Great Pretender' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (12 differences):*
'Greatest Hits I/01 Bohemian Rhapsody' 'Greatest Hits I/05 Bicycle Race' 'Greatest Hits I/13 Play The Game' 'Greatest Hits II/09 Who Wants To Live Forever' 'Greatest Hits II/15 Friends Will Be Friends' 'Greatest Hits III/01 The Show Must Go On' 'Greatest Hits III/03 Barcelona' 'Greatest Hits III/04 Too Much Love Will Kill You' 'Greatest Hits III/08 Las Palabras De Amor' 'Greatest Hits III/11 Let Me Live' 'Greatest Hits III/12 The Great Pretender' ...
[CSV](data/queen_estimates_schreiber2018_ismir2018_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [percival2014/stem](#percival2014stem) (8 differences):*
'Greatest Hits I/07 Don't Stop Me Now' 'Greatest Hits I/09 Crazy Little Thing Called Love' 'Greatest Hits I/10 Somebody To Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits II/09 Who Wants To Live Forever' 'Greatest Hits II/10 Headlong' 'Greatest Hits III/17 Thank God It's Christmas' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2014/default](#schreiber2014default) (9 differences):*
'Greatest Hits I/01 Bohemian Rhapsody' 'Greatest Hits I/07 Don't Stop Me Now' 'Greatest Hits I/09 Crazy Little Thing Called Love' 'Greatest Hits II/06 Innuendo' 'Greatest Hits II/08 Breakthru' 'Greatest Hits III/01 The Show Must Go On' 'Greatest Hits III/03 Barcelona' 'Greatest Hits III/09 Driven By You' 'Greatest Hits III/15 No-One But You' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (6 differences):*
'Greatest Hits I/07 Don't Stop Me Now' 'Greatest Hits I/09 Crazy Little Thing Called Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits II/08 Breakthru' 'Greatest Hits III/17 Thank God It's Christmas' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (6 differences):*
'Greatest Hits I/07 Don't Stop Me Now' 'Greatest Hits I/09 Crazy Little Thing Called Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits II/08 Breakthru' 'Greatest Hits III/03 Barcelona' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/cnn](#schreiber2018cnn) (3 differences):*
'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits III/11 Let Me Live' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/fcn](#schreiber2018fcn) (6 differences):*
'Greatest Hits I/09 Crazy Little Thing Called Love' 'Greatest Hits I/10 Somebody To Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits III/05 Somebody To Love' 'Greatest Hits III/15 No-One But You' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (2 differences):*
'Greatest Hits II/08 Breakthru' 'Greatest Hits III/12 The Great Pretender' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (4 differences):*
'Greatest Hits I/05 Bicycle Race' 'Greatest Hits III/03 Barcelona' 'Greatest Hits III/04 Too Much Love Will Kill You' 'Greatest Hits III/12 The Great Pretender' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [percival2014/stem](#percival2014stem) (3 differences):*
'Greatest Hits I/10 Somebody To Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits III/17 Thank God It's Christmas' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2014/default](#schreiber2014default) (5 differences):*
'Greatest Hits I/01 Bohemian Rhapsody' 'Greatest Hits I/07 Don't Stop Me Now' 'Greatest Hits II/08 Breakthru' 'Greatest Hits III/01 The Show Must Go On' 'Greatest Hits III/03 Barcelona' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (2 differences):*
'Greatest Hits I/17 We Are The Champions' 'Greatest Hits III/17 Thank God It's Christmas' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (1 differences):*
'Greatest Hits I/17 We Are The Champions' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/cnn](#schreiber2018cnn) (2 differences):*
'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[schreiber2018/ismir2018](#schreiber2018ismir2018) compared with [schreiber2018/fcn](#schreiber2018fcn) (4 differences):*
'Greatest Hits I/10 Somebody To Love' 'Greatest Hits I/17 We Are The Champions' 'Greatest Hits II/06 Innuendo' 'Greatest Hits III/05 Somebody To Love' 
[CSV](data/queen_estimates_schreiber2018_ismir2018_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

__All tracks were estimated 'correctly' by at least one system.__
### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6476   |   1.0000   |   1.0000   |   0.5488   |   0.5488   |   0.1094   |   0.5811   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6476   |   1.0000   |   0.4807   |   0.6072   |   0.2379   |   0.2101   | __0.0225__ |   0.2379   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.4807   |   1.0000   |   1.0000   |   0.6250   |   0.6875   |   0.1250   |   0.6875   |
| [schreiber2014/default](#schreiber2014default)     |   1.0000   |   0.6072   |   1.0000   |   1.0000   |   0.4531   |   0.3750   |   0.1094   |   0.5078   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.5488   |   0.2379   |   0.6250   |   0.4531   |   1.0000   |   1.0000   |   0.3750   |   1.0000   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5488   |   0.2101   |   0.6875   |   0.3750   |   1.0000   |   1.0000   |   0.3750   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1094   | __0.0225__ |   0.1250   |   0.1094   |   0.3750   |   0.3750   |   1.0000   |   0.3750   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5811   |   0.2379   |   0.6875   |   0.5078   |   1.0000   |   1.0000   |   0.3750   |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/queen_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/queen_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6250   |   1.0000   |   0.3750   |   1.0000   |   1.0000   |   1.0000   |   0.6875   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6250   |   1.0000   |   1.0000   |   1.0000   |   0.6875   |   0.3750   |   0.6875   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   1.0000   |   1.0000   |   0.7266   |   1.0000   |   0.5000   |   1.0000   |   1.0000   |
| [schreiber2014/default](#schreiber2014default)     |   0.3750   |   1.0000   |   0.7266   |   1.0000   |   0.4531   |   0.2188   |   0.4531   |   1.0000   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   0.6875   |   1.0000   |   0.4531   |   1.0000   |   1.0000   |   1.0000   |   0.6250   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   1.0000   |   0.3750   |   0.5000   |   0.2188   |   1.0000   |   1.0000   |   1.0000   |   0.2500   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   1.0000   |   0.6875   |   1.0000   |   0.4531   |   1.0000   |   1.0000   |   1.0000   |   0.5000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6875   |   1.0000   |   1.0000   |   1.0000   |   0.6250   |   0.2500   |   0.5000   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/queen_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/queen_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_accuracy2.png "Open Figure") 

## MIREX-Style Evaluation

P-Score is defined as the average of two tempi weighted by their perceptual strength, allowing an 8% tolerance for both tempo values [[MIREX 2006 Definition](https://www.music-ir.org/mirex/wiki/2006:Audio_Tempo_Extraction#Evaluation_Procedures)].

One Correct is the fraction of estimate pairs of which at least one of the two values is equal to a reference value (within an 8% tolerance).

Both Correct is the fraction of estimate pairs of which both values are equal to the reference values (within an 8% tolerance).

See [[McKinney2007](bib/McKinney2007.bib)].

*Note: Very few datasets actually have multiple annotations per track along with a salience distributions. References without suitable annotations are not shown.*

### MIREX Results for schreiber2018/ismir2018

| Estimator| P-Score | One Correct | Both Correct |
| ---: | :---: | :---: | :---: |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.9628__ | __1.0000__ | __0.7843__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9586   | __1.0000__ |   0.7647   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.9461   |   0.9804   |   0.7255   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.9261   |   0.9804   |   0.6471   |
| [schreiber2014/default](#schreiber2014default)     |   0.9148   |   0.9608   |   0.7059   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8995   |   0.9608   |   0.6078   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.8964   |   0.9804   |   0.4902   |
| [percival2014/stem](#percival2014stem)             |   0.7848   |   0.9412   |   0.0000   |

<a name="table6"></a>Table 6: Compared to [schreiber2018/ismir2018](#schreiber2018ismir2018) with 8.0% tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tolerance.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tolerance.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tolerance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tolerance.pickle "Download data as PICKLE") 

Raw data P-Score: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_p-score.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_p-score.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_p-score.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_p-score.pickle "Download raw data as PICKLE") 

Raw data One Correct: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_one_correct.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_one_correct.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_one_correct.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_one_correct.pickle "Download raw data as PICKLE") 

Raw data Both Correct: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_both_correct.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_both_correct.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_both_correct.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_both_correct.pickle "Download raw data as PICKLE") 

### P-Score for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_p-score.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean P-Score for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_p-score.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_p-score.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_p-score.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_p-score.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_p-score.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_p-score.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_p-score.png "Open Figure") 

### One Correct for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_one_correct.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean One Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_one_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_one_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_one_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_one_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_one_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_one_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_one_correct.png "Open Figure") 

### Both Correct for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_both_correct.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Both Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) depending on tolerance.

[CSV](data/queen_estimates_schreiber2018_ismir2018_both_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_both_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_both_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_both_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_both_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_both_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_both_correct.png "Open Figure") 

### P-Score on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean P-Score for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### P-Score on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_p-score.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean P-Score for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_p-score.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_p-score.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_p-score.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_p-score.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_p-score.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_p-score.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_p-score.png "Open Figure") 

### One Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean One Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### One Correct on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_one_correct.svg">
</figure>

<a name="figure13"></a>Figure 13: Mean One Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_one_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_one_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_one_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_one_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_one_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_one_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_one_correct.png "Open Figure") 

### Both Correct on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Both Correct for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Both Correct on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_both_correct.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean Both Correct for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_both_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_both_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_both_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_both_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_both_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_both_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_both_correct.png "Open Figure") 

### Estimated P-Score for Tempo

When fitting a generalized additive model (GAM) to P-Score-values and a ground truth, what P-Score can we expect with confidence?

#### Estimated P-Score for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on P-Score for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.svg">
</figure>

<a name="figure15"></a>Figure 15: P-Score predictions of a generalized additive model (GAM) fit to P-Score results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_p-score.png "Open Figure") 

### Estimated One Correct for Tempo

When fitting a generalized additive model (GAM) to One Correct-values and a ground truth, what One Correct can we expect with confidence?

#### Estimated One Correct for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on One Correct for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.svg">
</figure>

<a name="figure16"></a>Figure 16: One Correct predictions of a generalized additive model (GAM) fit to One Correct results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_one_correct.png "Open Figure") 

### Estimated Both Correct for Tempo

When fitting a generalized additive model (GAM) to Both Correct-values and a ground truth, what Both Correct can we expect with confidence?

#### Estimated Both Correct for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on Both Correct for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.svg">
</figure>

<a name="figure17"></a>Figure 17: Both Correct predictions of a generalized additive model (GAM) fit to Both Correct results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_both_correct.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for schreiber2018/ismir2018

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __-0.0082__ | __0.2078__ |   0.0114   | __0.0595__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0892   |   0.2617   |   0.0284   |   0.0975   |
| [schreiber2014/default](#schreiber2014default)     |   -0.0886   |   0.2842   |   0.0094   |   0.0722   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0367   |   0.2975   |   0.0026   |   0.0843   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0677   |   0.3108   |   0.0107   |   0.0598   |
| [percival2014/stem](#percival2014stem)             |   -0.0687   |   0.3340   |   0.0097   |   0.1030   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2155   |   0.3779   |   0.0195   |   0.0805   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.1466   |   0.3969   | __0.0021__ |   0.0830   |

<a name="table7"></a>Table 7: Mean OE1/OE2 for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) ordered by standard deviation.

[CSV](data/queen_estimates_schreiber2018_ismir2018_moe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_moe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_moe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_oe1.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_oe1.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_oe2.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_oe2.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_distribution_oe1.svg">
</figure>

<a name="figure18"></a>Figure 18: OE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/queen_estimates_schreiber2018_ismir2018_distribution_oe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_distribution_oe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_distribution_oe2.svg">
</figure>

<a name="figure19"></a>Figure 19: OE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/queen_estimates_schreiber2018_ismir2018_distribution_oe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_distribution_oe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.2152   |   0.3461   |   0.1227   |   0.2823   | __0.0211__ |   0.3881   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0001__ | __0.0001__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.2152   | __0.0000__ |   1.0000   |   0.6620   |   0.3778   |   0.9820   |   0.1995   |   0.6343   |
| [schreiber2014/default](#schreiber2014default)     |   0.3461   | __0.0000__ |   0.6620   |   1.0000   |   0.1912   |   0.6485   |   0.0637   |   0.9847   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1227   | __0.0004__ |   0.3778   |   0.1912   |   1.0000   |   0.1737   |   0.4930   |   0.1854   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2823   | __0.0001__ |   0.9820   |   0.6485   |   0.1737   |   1.0000   |   0.1747   |   0.6150   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0211__ | __0.0001__ |   0.1995   |   0.0637   |   0.4930   |   0.1747   |   1.0000   | __0.0301__ |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3881   | __0.0000__ |   0.6343   |   0.9847   |   0.1854   |   0.6150   | __0.0301__ |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/queen_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/queen_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.3109   |   0.6835   |   0.6556   |   0.9801   |   0.5500   |   0.5150   |   0.1524   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.3109   |   1.0000   |   0.5906   |   0.5900   |   0.3123   |   0.5431   |   0.5614   |   0.6077   |
| [percival2014/stem](#percival2014stem)             |   0.6835   |   0.5906   |   1.0000   |   0.9862   |   0.3951   |   0.9350   |   0.8874   |   0.1059   |
| [schreiber2014/default](#schreiber2014default)     |   0.6556   |   0.5900   |   0.9862   |   1.0000   |   0.6567   |   0.9219   |   0.8811   |   0.2836   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.9801   |   0.3123   |   0.3951   |   0.6567   |   1.0000   |   0.3221   |   0.2938   |   0.0655   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5500   |   0.5431   |   0.9350   |   0.9219   |   0.3221   |   1.0000   |   0.6729   |   0.1224   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.5150   |   0.5614   |   0.8874   |   0.8811   |   0.2938   |   0.6729   |   1.0000   |   0.1405   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1524   |   0.6077   |   0.1059   |   0.2836   |   0.0655   |   0.1224   |   0.1405   |   1.0000   |

<a name="table9"></a>Table 9: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/queen_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/queen_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_oe1.svg">
</figure>

<a name="figure20"></a>Figure 20: Mean OE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_oe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_oe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_oe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_oe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_oe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_oe2.svg">
</figure>

<a name="figure21"></a>Figure 21: Mean OE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_oe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_oe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_oe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_oe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_oe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.svg">
</figure>

<a name="figure22"></a>Figure 22: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.svg">
</figure>

<a name="figure23"></a>Figure 23: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for schreiber2018/ismir2018

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0522__ | __0.2013__ | __0.0130__ |   0.0592   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0972   |   0.2588   |   0.0311   |   0.0967   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1060   |   0.2804   |   0.0234   |   0.0810   |
| [schreiber2014/default](#schreiber2014default)     |   0.1108   |   0.2763   |   0.0278   |   0.0673   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1126   |   0.2975   |   0.0153   | __0.0588__ |
| [percival2014/stem](#percival2014stem)             |   0.1363   |   0.3126   |   0.0310   |   0.0987   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.1777   |   0.3840   |   0.0240   |   0.0795   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2155   |   0.3779   |   0.0406   |   0.0722   |

<a name="table10"></a>Table 10: Mean AOE1/AOE2 for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) ordered by mean.

[CSV](data/queen_estimates_schreiber2018_ismir2018_maoe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_maoe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_maoe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_aoe1.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_aoe1.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/queen_estimates_schreiber2018_ismir2018_raw_aoe2.csv "Download raw data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_raw_aoe2.json "Download raw data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.svg">
</figure>

<a name="figure24"></a>Figure 24: AOE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.svg">
</figure>

<a name="figure25"></a>Figure 25: AOE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6560   |   0.5079   |   0.2735   |   0.2657   |   0.3250   | __0.0369__ |   0.2222   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.6560   |   1.0000   |   0.2673   |   0.1418   |   0.1332   |   0.1518   | __0.0059__ |   0.0967   |
| [percival2014/stem](#percival2014stem)             |   0.5079   |   0.2673   |   1.0000   |   0.5731   |   0.4019   |   0.5760   |   0.0712   |   0.3608   |
| [schreiber2014/default](#schreiber2014default)     |   0.2735   |   0.1418   |   0.5731   |   1.0000   |   0.9014   |   0.9621   |   0.1776   |   0.6669   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2657   |   0.1332   |   0.4019   |   0.9014   |   1.0000   |   0.7598   |   0.1903   |   0.8240   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.3250   |   0.1518   |   0.5760   |   0.9621   |   0.7598   |   1.0000   |   0.1668   |   0.7166   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0369__ | __0.0059__ |   0.0712   |   0.1776   |   0.1903   |   0.1668   |   1.0000   |   0.2365   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2222   |   0.0967   |   0.3608   |   0.6669   |   0.8240   |   0.7166   |   0.2365   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/queen_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/queen_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2795   |   0.7052   |   0.7866   |   0.9701   |   0.5359   |   0.4390   |   0.6973   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.2795   |   1.0000   |   0.5815   |   0.1943   |   0.2619   |   0.0505   | __0.0409__ |   0.5820   |
| [percival2014/stem](#percival2014stem)             |   0.7052   |   0.5815   |   1.0000   |   0.8555   |   0.3654   |   0.1794   |   0.1275   |   0.9947   |
| [schreiber2014/default](#schreiber2014default)     |   0.7866   |   0.1943   |   0.8555   |   1.0000   |   0.7706   |   0.3209   |   0.2580   |   0.8501   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.9701   |   0.2619   |   0.3654   |   0.7706   |   1.0000   |   0.3221   |   0.2167   |   0.5901   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.5359   |   0.0505   |   0.1794   |   0.3209   |   0.3221   |   1.0000   |   0.1712   |   0.1683   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.4390   | __0.0409__ |   0.1275   |   0.2580   |   0.2167   |   0.1712   |   1.0000   |   0.1162   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6973   |   0.5820   |   0.9947   |   0.8501   |   0.5901   |   0.1683   |   0.1162   |   1.0000   |

<a name="table12"></a>Table 12: Paired t-test p-values, using reference annotations [schreiber2018/ismir2018](#schreiber2018ismir2018) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/queen_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/queen_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/queen_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/queen_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_aoe1.svg">
</figure>

<a name="figure26"></a>Figure 26: Mean AOE<sub>1</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_aoe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_aoe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for schreiber2018/ismir2018

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_inter_aoe2.svg">
</figure>

<a name="figure27"></a>Figure 27: Mean AOE<sub>2</sub> for estimates compared to version [schreiber2018/ismir2018](#schreiber2018ismir2018) for tempo intervals around T.

[CSV](data/queen_estimates_schreiber2018_ismir2018_inter_aoe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_inter_aoe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.svg">
</figure>

<a name="figure28"></a>Figure 28: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for schreiber2018/ismir2018

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [schreiber2018/ismir2018](#schreiber2018ismir2018).

<figure>
<embed type="image/svg+xml" src="figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.svg">
</figure>

<a name="figure29"></a>Figure 29: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [schreiber2018/ismir2018](#schreiber2018ismir2018). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/queen_estimates_schreiber2018_ismir2018_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-05-04 17:56. Size L.
