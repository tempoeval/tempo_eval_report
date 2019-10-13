---
title: lmd_tempo
{:.no_toc}
layout: default
---

# lmd_tempo
{:.no_toc}

This is the tempo_eval report for the 'lmd_tempo' corpus.

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'lmd_tempo'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 1.0 |
| **Curator** | [Hendrik Schreiber](mailto:hs@tagtraum.com) |
| **Data&nbsp;Source** | LMD 0.1, https://colinraffel.com/projects/lmd/ |
| **Annotation&nbsp;Tools** | Schreiber2017, MIDI parser |
| **Annotation&nbsp;Rules** | Consensus between Schreiber2017 and MIDI messages (2% tolerance). |
| **Annotator,&nbsp;bibtex** |[Schreiber2018a](bib/Schreiber2018a.bib) |
| **Annotator,&nbsp;ref_url** | [http://www.tagtraum.com/tempo\_estimation.html](http://www.tagtraum.com/tempo_estimation.html) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   3611   |   44.44   |   161.42   |   113.59   |   21.25   |   77.00   |   0.94   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/lmd_tempo_reference_basic_stats.csv "Download data as CSV") [JSON](data/lmd_tempo_reference_basic_stats.json "Download data as JSON") [LATEX](data/lmd_tempo_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/lmd_tempo_reference_dist.csv "Download data as CSV") [JSON](data/lmd_tempo_reference_dist.json "Download data as JSON") [LATEX](data/lmd_tempo_reference_dist.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_reference_dist.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_reference_dist.svg "Open Figure") [PDF](figures/lmd_tempo_reference_dist.pdf "Open Figure") [PNG](figures/lmd_tempo_reference_dist.png "Open Figure") 

## Tag Distribution for 'tag_open'

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_reference_1.0_tag_open.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of tracks tagged with tags from namespace 'tag_open'. Annotations are from reference [1.0](#10).

[CSV](data/lmd_tempo_reference_1.0_tag_open.csv "Download data as CSV") [JSON](data/lmd_tempo_reference_1.0_tag_open.json "Download data as JSON") [LATEX](data/lmd_tempo_reference_1.0_tag_open.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_reference_1.0_tag_open.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_reference_1.0_tag_open.svg "Open Figure") [PDF](figures/lmd_tempo_reference_1.0_tag_open.pdf "Open Figure") [PNG](figures/lmd_tempo_reference_1.0_tag_open.png "Open Figure") 

# Estimates for 'lmd_tempo'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | lmd_tempo |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   3611   |   41.96   |   240.00   |   113.00   |   24.72   |   74.00   |   0.89   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   3611   |   64.60   |   234.91   |   121.64   |   21.04   |   79.00   |   0.95   |
| [percival2014/stem](#percival2014stem)             |   3611   |   50.54   |   20671.90   |   115.52   |   342.85   |   72.00   |   0.93   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   3611   |   44.28   |   177.03   |   114.17   |   21.57   |   77.00   |   0.94   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   3611   |   44.00   |   161.46   |   113.55   |   21.52   |   77.00   |   0.94   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   3611   |   41.00   |   232.00   |   114.41   |   22.77   |   77.00   |   0.92   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   3611   |   40.00   |   224.00   |   113.99   |   24.66   |   76.00   |   0.89   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   3611   |   56.00   |   224.00   |   114.86   |   21.56   |   77.00   |   0.94   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/lmd_tempo_estimates_basic_stats.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_basic_stats.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/lmd_tempo_estimates_dist.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_dist.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_dist.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_dist.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_dist.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, &frac12; or &frac13; (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.9823__ | __0.9983__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.9754   | __0.9983__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.9574   |   0.9914   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.9554   |   0.9900   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.9308   |   0.9889   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.9241   |   0.9925   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8892   |   0.9693   |
| [percival2014/stem](#percival2014stem)             |   0.8887   |   0.9809   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/lmd_tempo_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/lmd_tempo_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/lmd_tempo_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (274 differences):*
'TRABYWC128F9307C66' 'TRABZZD128F9334C0B' 'TRAEMIU128F14641D6' 'TRAFOZW128F92F1594' 'TRAHQST128F425CBE6' 'TRALWYN128F429887F' 'TRAQKCT128F426C28F' 'TRARQNM128F92E1E52' 'TRATFNI12903CEF67A' 'TRAWBPY128F425512E' 'TRAZQSW128F9308F88' ...
[CSV](data/lmd_tempo_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (400 differences):*
'TRABYWC128F9307C66' 'TRADFPY128F92D2B4E' 'TRAEMIU128F14641D6' 'TRAEOOG128F148B494' 'TRAGHBO128F92D8C9E' 'TRAHOOM128F427F234' 'TRAHQST128F425CBE6' 'TRAPVQY128F9333E52' 'TRAQKCT128F426C28F' 'TRASUWA128F933E6F7' 'TRATMIZ128F428E152' ...
[CSV](data/lmd_tempo_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (402 differences):*
'TRACYOR128F427FB1D' 'TRADFPY128F92D2B4E' 'TRAFOZW128F92F1594' 'TRAHQST128F425CBE6' 'TRAJPPO128F428AEB1' 'TRALWYN128F429887F' 'TRANKTK128E07921D9' 'TRAOMMX128F92E4E60' 'TRAOVNR128F4275781' 'TRAPPUJ128F931B3D1' 'TRAPVQY128F9333E52' ...
[CSV](data/lmd_tempo_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (89 differences):*
'TRADFPY128F92D2B4E' 'TRANPKC128F93486B9' 'TRAPVQY128F9333E52' 'TRARQNM128F92E1E52' 'TRBFNOR128F933B0F5' 'TRBVHSJ128F1471230' 'TRCNNLU128F42850AB' 'TRCYKOV128E07917EB' 'TRCZIUO12903CE5274' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (64 differences):*
'TRADFPY128F92D2B4E' 'TRANPKC128F93486B9' 'TRARQNM128F92E1E52' 'TRBFNOR128F933B0F5' 'TRBVDGU128F92FDD3C' 'TRBVHSJ128F1471230' 'TRCYKOV128E07917EB' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRDXYDY128F9341F9B' 'TREPGCE128E0791C5D' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (161 differences):*
'TRAEMIU128F14641D6' 'TRAJZLQ128F424E12B' 'TRARQNM128F92E1E52' 'TRATMIZ128F428E152' 'TRAWBPY128F425512E' 'TRBBQPP128F92EE611' 'TRBISBN128F4267AB6' 'TRBRSTH128F4296255' 'TRCFKSY128F14B0FA5' 'TRCJRZW128F930113B' 'TRCKPMP128F423984C' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (250 differences):*
'TRAEMIU128F14641D6' 'TRAFOZW128F92F1594' 'TRAKGGU128F428D83C' 'TRALWYN128F429887F' 'TRANKTK128E07921D9' 'TRAOCHX128F42A00AE' 'TRAPPUJ128F931B3D1' 'TRAQKCT128F426C28F' 'TRARQNM128F92E1E52' 'TRATFNI12903CEF67A' 'TRAVULK128F4232387' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (154 differences):*
'TRABYWC128F9307C66' 'TRAEMIU128F14641D6' 'TRAHQST128F425CBE6' 'TRANPKC128F93486B9' 'TRARQNM128F92E1E52' 'TRASUWA128F933E6F7' 'TRBQWGI128E0793D38' 'TRCABMS128F42A0EFC' 'TRCJETO128F425FE38' 'TRCJRZW128F930113B' 'TRCKPMP128F423984C' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 6 items 'correctly' using Accuracy<sub>1</sub>:__
'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRGBTIM128F427FFF0' 'TRIRCFN128F4280243' 'TRVKVHJ12903CF3934' 'TRZJFFH128F14647FC' 
[CSV](data/lmd_tempo_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (27 differences):*
'TRBISBN128F4267AB6' 'TRCSBQX12903CFA040' 'TRDPAGI12903CA69AD' 'TRFTLJV128F92EEDBD' 'TRFYUKH128F42B0BDA' 'TRGBHFD128F422A9D3' 'TRGKGAA128F147706C' 'TRHTLCM128E0783A19' 'TRIRCFN128F4280243' 'TRKTRGF128F42B323B' 'TRLLLKU128F425FF8B' ...
[CSV](data/lmd_tempo_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (111 differences):*
'TRAEOOG128F148B494' 'TRAHOOM128F427F234' 'TRAPVQY128F9333E52' 'TRAQKCT128F426C28F' 'TRAWASU12903D07A25' 'TRAZASM128F932FBEE' 'TRAZQSW128F9308F88' 'TRBDNEG128F93562C0' 'TRBISBN128F4267AB6' 'TRBKSUX128EF342BD6' 'TRCSBQX12903CFA040' ...
[CSV](data/lmd_tempo_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (69 differences):*
'TRAHQST128F425CBE6' 'TRAPVQY128F9333E52' 'TRAQKCT128F426C28F' 'TRBISBN128F4267AB6' 'TRCILWH128F4288159' 'TRCSBQX12903CFA040' 'TRCYHJI128F147B1DC' 'TRDPAGI12903CA69AD' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRDYZYY128F4284F78' ...
[CSV](data/lmd_tempo_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (6 differences):*
'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRHTLCM128E0783A19' 'TRIRCFN128F4280243' 'TRVKVHJ12903CF3934' 'TRZJFFH128F14647FC' 
[CSV](data/lmd_tempo_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (6 differences):*
'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRHTLCM128E0783A19' 'TRIRCFN128F4280243' 'TRVKVHJ12903CF3934' 'TRZJFFH128F14647FC' 
[CSV](data/lmd_tempo_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (36 differences):*
'TRBISBN128F4267AB6' 'TRBRSTH128F4296255' 'TRCSBQX12903CFA040' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRETAHF128F425309E' 'TRFPDPQ12903CA9803' 'TRGKGAA128F147706C' 'TRINNMP12903CC4C64' 'TRIRCFN128F4280243' 'TRJUJAH128F425A752' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (40 differences):*
'TRAQKCT128F426C28F' 'TRAZQSW128F9308F88' 'TRBISBN128F4267AB6' 'TRBRSTH128F4296255' 'TRCSBQX12903CFA040' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRFPDPQ12903CA9803' 'TRGASIV128F429230D' 'TRINNMP12903CC4C64' 'TRIRCFN128F4280243' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (31 differences):*
'TRCSBQX12903CFA040' 'TRDPAGI12903CA69AD' 'TRDPTCF128F93002CE' 'TRDWVQX128F9335CED' 'TRFWOOG128F1485DA5' 'TRGKGAA128F147706C' 'TRINNMP12903CC4C64' 'TRIRCFN128F4280243' 'TRKTRGF128F42B323B' 'TRKUWVV128F4268367' 'TRLLLKU128F425FF8B' ...
[CSV](data/lmd_tempo_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following 2 items 'correctly' using Accuracy<sub>2</sub>:__
'TRIRCFN128F4280243' 'TRZJFFH128F14647FC' 
[CSV](data/lmd_tempo_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1886   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.9651   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.9651   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.6207   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1886   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6207   | __0.0000__ |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1628   | __0.0470__ |   0.5572   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1628   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5716   |   0.4731   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0470__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ |   0.5716   |   1.0000   |   0.1221   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5572   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4731   |   0.1221   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Mean Accuracy<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean Accuracy<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[CSV](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, &frac12;, and &frac13;: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __-0.0014__ | __0.1279__ |   -0.0003   | __0.0145__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0069   |   0.1537   |   -0.0003   |   0.0145   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0169   |   0.1918   | __-0.0000__ |   0.0353   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0079   |   0.1995   |   0.0011   |   0.0359   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0029   |   0.2484   |   0.0009   |   0.0361   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0159   |   0.2717   |   0.0001   |   0.0338   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1048   |   0.2972   |   0.0246   |   0.0611   |
| [percival2014/stem](#percival2014stem)             |   -0.0488   |   0.3323   |   0.0042   |   0.1044   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/lmd_tempo_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure12"></a>Figure 12: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/lmd_tempo_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure13"></a>Figure 13: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/lmd_tempo_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0025__ | __0.0000__ | __0.0084__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.7909   | __0.0350__ | __0.0072__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0025__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0108__ |   0.7475   | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.7909   | __0.0108__ |   1.0000   | __0.0047__ | __0.0058__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0084__ | __0.0000__ | __0.0000__ | __0.0350__ |   0.7475   | __0.0047__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0072__ | __0.0000__ | __0.0058__ | __0.0000__ |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0190__ |   0.4519   |   0.4519   |   0.0814   |   0.1946   |   0.8685   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0190__ | __0.0000__ |   1.0000   | __0.0100__ | __0.0100__ |   0.0865   |   0.0670   | __0.0185__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4519   | __0.0000__ | __0.0100__ |   1.0000   |   0.9374   | __0.0258__ | __0.0340__ |   0.6134   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.4519   | __0.0000__ | __0.0100__ |   0.9374   |   1.0000   | __0.0258__ | __0.0340__ |   0.6134   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0814   | __0.0000__ |   0.0865   | __0.0258__ | __0.0258__ |   1.0000   |   0.6973   |   0.0639   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1946   | __0.0000__ |   0.0670   | __0.0340__ | __0.0340__ |   0.6973   |   1.0000   |   0.1804   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8685   | __0.0000__ | __0.0185__ |   0.6134   |   0.6134   |   0.0639   |   0.1804   |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure16"></a>Figure 16: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure17"></a>Figure 17: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

### OE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe1.svg">
</figure>

<a name="figure18"></a>Figure 18: OE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe1.png "Open Figure") 

### OE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### OE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe2.svg">
</figure>

<a name="figure19"></a>Figure 19: OE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, &frac12;, and &frac13;: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0170__ | __0.1268__ | __0.0009__ | __0.0145__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.0242   |   0.1519   |   0.0009   |   0.0145   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0414   |   0.1880   |   0.0059   |   0.0348   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0429   |   0.1950   |   0.0059   |   0.0354   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0663   |   0.2394   |   0.0066   |   0.0355   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.0795   |   0.2603   |   0.0091   |   0.0326   |
| [percival2014/stem](#percival2014stem)             |   0.1062   |   0.3186   |   0.0099   |   0.1040   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1178   |   0.2923   |   0.0295   |   0.0589   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/lmd_tempo_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/lmd_tempo_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/lmd_tempo_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure20"></a>Figure 20: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/lmd_tempo_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure21"></a>Figure 21: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/lmd_tempo_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0060__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   |   0.0703   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0703   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |   0.6290   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0060__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6290   | __0.0000__ |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0000__ |   0.6354   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.6354   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0212__ |   0.0528   | __0.0186__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0164__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0164__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0212__ | __0.0000__ | __0.0000__ |   1.0000   |   0.1893   |   0.9332   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.0528   | __0.0000__ | __0.0000__ |   0.1893   |   1.0000   |   0.2001   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0186__ | __0.0000__ | __0.0000__ |   0.9332   |   0.2001   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/lmd_tempo_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/lmd_tempo_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure24"></a>Figure 24: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure25"></a>Figure 25: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/lmd_tempo_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/lmd_tempo_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/lmd_tempo_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/lmd_tempo_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

### AOE<sub>1</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>1</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe1.svg">
</figure>

<a name="figure26"></a>Figure 26: AOE<sub>1</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe1.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe1.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe1.png "Open Figure") 

### AOE<sub>2</sub> for 'tag_open' Tags

How well does an estimator perform, when only taking tracks into account that are tagged with some kind of label? Note that some values may be based on very few estimates.

#### AOE<sub>2</sub> for 'tag_open' Tags for 1.0

<figure>
<embed type="image/svg+xml" src="figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe2.svg">
</figure>

<a name="figure27"></a>Figure 27: AOE<sub>2</sub> of estimates compared to version [1.0](#10) depending on tag from namespace 'tag_open'.

[SVG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe2.svg "Open Figure") [PDF](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe2.pdf "Open Figure") [PNG](figures/lmd_tempo_estimates_1.0_tag_open_1.0_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2019-10-13 11:28. Size L.
