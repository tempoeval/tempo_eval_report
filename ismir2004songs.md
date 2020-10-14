---
title: ismir2004songs
{:.no_toc}
layout: default
---

# ismir2004songs
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'ismir2004songs' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'ismir2004songs'

## References

### 1.0

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Curator** | [Fabien Gouyon](mailto:fgouyon@pandora.com) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Gouyon2006](bib/Gouyon2006.bib) |
| **Annotator,&nbsp;ref_url** | [http://mtg.upf.edu//ismir2004/contest/tempoContest/node6.html](http://mtg.upf.edu//ismir2004/contest/tempoContest/node6.html) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.0](#10)                                         |   465   |   23.00   |   242.44   |   89.83   |   27.84   |   56.00   |   0.74   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/ismir2004songs_reference_basic_stats.csv "Download data as CSV") [JSON](data/ismir2004songs_reference_basic_stats.json "Download data as JSON") [LATEX](data/ismir2004songs_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/ismir2004songs_reference_dist.csv "Download data as CSV") [JSON](data/ismir2004songs_reference_dist.json "Download data as JSON") [LATEX](data/ismir2004songs_reference_dist.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_reference_dist.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_reference_dist.svg "Open Figure") [PDF](figures/ismir2004songs_reference_dist.pdf "Open Figure") [PNG](figures/ismir2004songs_reference_dist.png "Open Figure") 

# Estimates for 'ismir2004songs'

## Estimators

### alonso2004/ismir2004_corr

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | AlonsoACF, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Alonso2004](bib/Alonso2004.bib) |

### alonso2004/ismir2004_spec

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | AlonsoSP, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Alonso2004](bib/Alonso2004.bib) |

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### dixon2001/ismir2004_indu

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | DixonI, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Dixon2001](bib/Dixon2001.bib) |

### dixon2001/ismir2004_trac

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | DixonT, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Dixon2001](bib/Dixon2001.bib) |

### dixon2003/ismir2004_auco

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | DixonACF, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Dixon2003](bib/Dixon2003.bib) |

### echonest/version_3_2_1

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 3.2.1 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Echo Nest track analyzer v3.2.1 |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### gkiokas2012/default

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Gkiokas2012 |
| **Annotator,&nbsp;bibtex** |[Gkiokas2012](bib/Gkiokas2012.bib) |

### klapuri2006/ismir2004

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | Klapuri, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832\u2013 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### klapuri2006/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Klapuri 2006 |
| **Annotator,&nbsp;bibtex** |[Klapuri2006](bib/Klapuri2006.bib) |

### oliveira2010/ibt

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Oliveira 2010 |
| **Annotator,&nbsp;bibtex** |[Oliveira2010](bib/Oliveira2010.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### scheirer1998/ismir2004

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | Scheirer, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832– 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### scheirer1998/percival2014

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | Scheirer 1998 |
| **Annotator,&nbsp;bibtex** |[Scheirer1998](bib/Scheirer1998.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

### tzanetakis2002/ismir2004_hist

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | TzanetakisH, based on front-end described in Tzanetakis2002, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832– 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Tzanetakis2002](bib/Tzanetakis2002.bib) |

### tzanetakis2002/ismir2004_mmul

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | TzanetakisMM, based on front-end described in Tzanetakis2002, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832– 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Tzanetakis2002](bib/Tzanetakis2002.bib) |

### tzanetakis2002/ismir2004_msum

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | TzanetakisMs, based on front-end described in Tzanetakis2002, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832– 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Tzanetakis2002](bib/Tzanetakis2002.bib) |

### uhle2004/ismir2004

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 1.0 |
| **Data&nbsp;Source** | ISMIR 2004 Songs contest results, http://www.iua.upf.edu/mtg/ismir2004/contest/tempoContest/data3.tar.gz |
| **Annotation&nbsp;Tools** | Uhle, see also: Fabien Gouyon, Anssi P. Klapuri, Simon Dixon, Miguel Alonso, George Tzanetakis, Christian Uhle, and Pedro Cano. An experimental comparison of audio tempo induction algorithms. IEEE Transactions on Audio, Speech, and Language Processing, 14(5):1832– 1844, 2006. |
| **Annotator,&nbsp;bibtex** |[Rohden2004](bib/Rohden2004.bib) |

### zplane/auftakt_v3

| Attribute | Value |
| --- | --- |
| **Corpus** | ismir2004songs |
| **Version** | 3.0 |
| **Data&nbsp;Source** | Graham Percival and George Tzanetakis. Streamlined tempo estimation based on autocorrelation and crosscorrelation with pulses. IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP), 22(12):1765–1776, 2014. |
| **Annotation&nbsp;Tools** | zplane aufTAKT version 3.0, http://licensing.zplane.de/technology#auftakt |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   465   |   57.78   |   245.89   |   131.76   |   49.76   |   92.00   |   0.60   |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) |   459   |   50.06   |   249.17   |   106.80   |   45.47   |   61.00   |   0.59   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   465   |   45.11   |   240.00   |   120.93   |   37.09   |   79.00   |   0.76   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   465   |   65.42   |   246.09   |   126.75   |   31.62   |   84.00   |   0.86   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   465   |   50.09   |   248.80   |   127.38   |   53.03   |   91.00   |   0.51   |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   448   |   54.97   |   248.47   |   157.87   |   44.05   |   121.00   |   0.79   |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) |   465   |   60.00   |   249.00   |   163.38   |   44.85   |   124.00   |   0.81   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   465   |   53.59   |   198.29   |   99.03   |   30.86   |   64.00   |   0.76   |
| [gkiokas2012/default](#gkiokas2012default)         |   464   |   45.00   |   248.00   |   114.30   |   36.35   |   76.00   |   0.74   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     |   465   |   66.00   |   164.00   |   111.45   |   21.14   |   79.00   |   0.96   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   464   |   68.45   |   164.06   |   110.83   |   20.63   |   76.00   |   0.97   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   465   |   81.00   |   161.00   |   115.72   |   21.86   |   81.00   |   1.00   |
| [percival2014/stem](#percival2014stem)             |   465   |   51.55   |   159.01   |   101.36   |   22.21   |   70.00   |   0.89   |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   |   465   |   51.50   |   220.00   |   106.08   |   35.85   |   66.00   |   0.69   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   416   |   61.35   |   181.82   |   104.23   |   27.96   |   77.00   |   0.79   |
| [schreiber2014/default](#schreiber2014default)     |   465   |   43.49   |   161.46   |   97.19   |   21.57   |   68.00   |   0.89   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   465   |   48.81   |   200.14   |   98.49   |   23.27   |   68.00   |   0.87   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   465   |   39.09   |   185.87   |   90.89   |   26.18   |   61.00   |   0.75   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   465   |   43.00   |   224.00   |   109.80   |   31.02   |   76.00   |   0.80   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   465   |   45.00   |   224.00   |   106.12   |   33.87   |   68.00   |   0.73   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   465   |   54.00   |   224.00   |   112.95   |   28.96   |   77.00   |   0.86   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) |   465   |   50.00   |   249.00   |   172.55   |   75.11   |   125.00   |   0.66   |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) |   465   |   52.00   |   240.00   |   140.89   |   45.67   |   113.00   |   0.67   |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   465   |   50.00   |   248.00   |   135.23   |   53.03   |   117.00   |   0.55   |
| [uhle2004/ismir2004](#uhle2004ismir2004)           |   465   |   51.00   |   248.00   |   119.77   |   41.23   |   77.00   |   0.74   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   464   |   65.90   |   164.50   |   109.22   |   23.58   |   79.00   |   0.89   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/ismir2004songs_estimates_basic_stats.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_basic_stats.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_dist.svg">
</figure>

<a name="figure2"></a>Figure 2: Percentage of values in tempo interval.

[CSV](data/ismir2004songs_estimates_dist.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_dist.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_dist.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_dist.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_dist.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.0

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.8989__ | __0.9484__ |
| [schreiber2014/default](#schreiber2014default)     |   0.7312   |   0.9183   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.6753   |   0.9355   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.6688   |   0.9140   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.6452   |   0.9226   |
| [percival2014/stem](#percival2014stem)             |   0.6086   |   0.8602   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.5871   |   0.9183   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     |   0.5828   |   0.9097   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.5785   |   0.8925   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.5699   |   0.7849   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.5677   |   0.9075   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.5613   |   0.8237   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.5548   | __0.9484__ |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4667   |   0.7677   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.4387   |   0.8194   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4258   |   0.6430   |
| [uhle2004/ismir2004](#uhle2004ismir2004)           |   0.4194   |   0.7204   |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   |   0.3785   |   0.6946   |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) |   0.3742   |   0.6860   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.2860   |   0.6280   |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.2731   |   0.5247   |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   0.2344   |   0.5785   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) |   0.2129   |   0.4774   |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   0.1935   |   0.6882   |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) |   0.1892   |   0.4129   |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) |   0.1677   |   0.7677   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.0](#10) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/ismir2004songs_estimates_1.0_accuracy_tol04.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_accuracy_tol04.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_accuracy1.svg">
</figure>

<a name="figure3"></a>Figure 3: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/ismir2004songs_estimates_1.0_accuracy1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_accuracy1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_accuracy1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_accuracy1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_accuracy1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_accuracy2.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) depending on tolerance.

[CSV](data/ismir2004songs_estimates_1.0_accuracy2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_accuracy2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_accuracy2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_accuracy2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_accuracy2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) (356 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/02-Knowing Me, Knowing You' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/06-Super Trouper' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/14-Gimme! Gimme! Gimme! (A Man After Midnight)' 'Abba/Gold - Greatest Hits/20 sec/15-Does Your Mother Know' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/01-A\_Dream\_Within\_A\_Dream' ...
[CSV](data/ismir2004songs_estimates_1.0_alonso2004_ismir2004_corr_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) (291 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/04-Mamma Mia' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/09-Money, Money, Money' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' ...
[CSV](data/ismir2004songs_estimates_1.0_alonso2004_ismir2004_spec_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (207 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (261 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' ...
[CSV](data/ismir2004songs_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) (332 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/09-Money, Money, Money' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2001_ismir2004_indu_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) (375 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/02-Knowing Me, Knowing You' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/06-Super Trouper' 'Abba/Gold - Greatest Hits/20 sec/09-Money, Money, Money' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/14-Gimme! Gimme! Gimme! (A Man After Midnight)' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/01-A\_Dream\_Within\_A\_Dream' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2001_ismir2004_trac_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) (387 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/02-Knowing Me, Knowing You' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/06-Super Trouper' 'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/14-Gimme! Gimme! Gimme! (A Man After Midnight)' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2003_ismir2004_auco_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (200 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/06-Modern\_Apprentice' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/08-Hypocrite' ...
[CSV](data/ismir2004songs_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (201 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/ismir2004](#klapuri2006ismir2004) (194 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' ...
[CSV](data/ismir2004songs_estimates_1.0_klapuri2006_ismir2004_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (196 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' ...
[CSV](data/ismir2004songs_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (248 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' ...
[CSV](data/ismir2004songs_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (182 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' ...
[CSV](data/ismir2004songs_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/ismir2004](#scheirer1998ismir2004) (289 differences):*
'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/04-Mamma Mia' 'Abba/Gold - Greatest Hits/20 sec/06-Super Trouper' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/09-Money, Money, Money' 'Abba/Gold - Greatest Hits/20 sec/13-Voulez Vous' 'Abba/Gold - Greatest Hits/20 sec/15-Does Your Mother Know' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' ...
[CSV](data/ismir2004songs_estimates_1.0_scheirer1998_ismir2004_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (267 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/13-Voulez Vous' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (125 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (154 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (47 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bebel\_Gilberto/Tanto\_Tempo/20sec/04-Sem\_Contencao' 'Bebel\_Gilberto/Tanto\_Tempo/20sec/07-So\_Nice\_\_Summer\_Samba\_' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/05-The\_Miraculous\_Mandarin\_\_\_5.1\_\_Maestoso\_\_\_5.2\_\_Allegro' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (165 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/03-Black\_White' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (151 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/06-Modern\_Apprentice' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (192 differences):*
'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/06-Modern\_Apprentice' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) (366 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_hist_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) (377 differences):*
'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_mmul_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) (338 differences):*
'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_msum_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [uhle2004/ismir2004](#uhle2004ismir2004) (270 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/16-One Of Us' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_uhle2004_ismir2004_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (204 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/17-The Name Of The Game' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/03-The\_Tell-tale\_Heart' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following 13 items 'correctly' using Accuracy<sub>1</sub>:__
'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bernstein\_conducts\_Stravinsky/20sec/01-Introduction\_\_Part\_1-\_The\_adoration\_of\_the\_earth\_' 'Bernstein\_conducts\_Stravinsky/20sec/16-Legerdemain\_scene-\_Russian\_danse' 'Bernstein\_conducts\_Stravinsky/20sec/19-Waltz\_\_ballerina\_and\_the\_moor' 'Classic/20 sec/Pergolesi - Stabat Mater 01' 'Fado/20 sec/03-AudioTrack 03' 'Papakonstantinou/20 sec/02-AudioTrack 02' 'Papakonstantinou/20 sec/13-AudioTrack 13' 'more greek/03 Virginouda' ...
[CSV](data/ismir2004songs_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.0](#10) compared with [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) (196 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/02-Knowing Me, Knowing You' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Abba/Gold - Greatest Hits/20 sec/14-Gimme! Gimme! Gimme! (A Man After Midnight)' 'Abba/Gold - Greatest Hits/20 sec/15-Does Your Mother Know' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' ...
[CSV](data/ismir2004songs_estimates_1.0_alonso2004_ismir2004_corr_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) (146 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/03-Take A Chance On Me' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/06-Modern\_Apprentice' ...
[CSV](data/ismir2004songs_estimates_1.0_alonso2004_ismir2004_spec_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (24 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/01-The\_Miraculous\_Mandarin\_\_\_1.1\_\_Allegro\_\_\_1.2\_\_Curtain' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/11-Music\_for\_Strings\_\_Percussion\_and\_Celesta\_\_III\_\_Adagio' ...
[CSV](data/ismir2004songs_estimates_1.0_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (84 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/12-Culture\_Move' 'Autechre/Amber/20sec/10-Nil' 'Aviador\_Dro/Primer\_Aliento/20sec/04-Varsovia\_en\_llamas' ...
[CSV](data/ismir2004songs_estimates_1.0_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) (173 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Autechre/Amber/20sec/02-Montreal' 'Autechre/Amber/20sec/06-Piezo' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2001_ismir2004_indu_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) (145 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Autechre/Amber/20sec/06-Piezo' 'Bach - Walcha/DGG 419 047-2/20sec/03-Praludium u. Fuge f-moll BWV 534 - I\_ Praludium' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2001_ismir2004_trac_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) (108 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Bach - Walcha/DGG 419 047-2/20sec/02-Toccata u. Fuge d-moll BWV 565 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/03-Praludium u. Fuge f-moll BWV 534 - I\_ Praludium' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' ...
[CSV](data/ismir2004songs_estimates_1.0_dixon2003_ismir2004_auco_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [echonest/version_3_2_1](#echonestversion_3_2_1) (100 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/09-Naxalite' 'Autechre/Amber/20sec/10-Nil' 'Bach - Walcha/DGG 419 047-2/20sec/03-Praludium u. Fuge f-moll BWV 534 - I\_ Praludium' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach - Walcha/DGG 419 047-2/20sec/11-Triosonate Nr. 1 Es-Dur BWV 525 - II\_ Adagio' ...
[CSV](data/ismir2004songs_estimates_1.0_echonest_version_3_2_1_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [gkiokas2012/default](#gkiokas2012default) (43 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/06-Modern\_Apprentice' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Autechre/Amber/20sec/06-Piezo' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' ...
[CSV](data/ismir2004songs_estimates_1.0_gkiokas2012_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/ismir2004](#klapuri2006ismir2004) (42 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/12-Culture\_Move' 'Aviador\_Dro/Primer\_Aliento/20sec/02-Nuclear\_\_si\_\_por\_supuesto\_' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/06-The\_Miraculous\_Mandarin\_\_\_6.1\_\_Sempre\_vivo\_\_\_6.2\_\_Adagio' ...
[CSV](data/ismir2004songs_estimates_1.0_klapuri2006_ismir2004_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [klapuri2006/percival2014](#klapuri2006percival2014) (50 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/06-The\_Miraculous\_Mandarin\_\_\_6.1\_\_Sempre\_vivo\_\_\_6.2\_\_Adagio' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/07-The\_Miraculous\_Mandarin\_\_\_7.1\_\_Agitato\_\_\_7.2\_\_Molto\_moderato' ...
[CSV](data/ismir2004songs_estimates_1.0_klapuri2006_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [oliveira2010/ibt](#oliveira2010ibt) (108 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Autechre/Amber/20sec/10-Nil' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/11-Triosonate Nr. 1 Es-Dur BWV 525 - II\_ Adagio' ...
[CSV](data/ismir2004songs_estimates_1.0_oliveira2010_ibt_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [percival2014/stem](#percival2014stem) (65 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/07-Operation\_Eagle\_Lie' 'Autechre/Amber/20sec/10-Nil' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bebel\_Gilberto/Tanto\_Tempo/20sec/06-Alguem' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/01-The\_Miraculous\_Mandarin\_\_\_1.1\_\_Allegro\_\_\_1.2\_\_Curtain' ...
[CSV](data/ismir2004songs_estimates_1.0_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/ismir2004](#scheirer1998ismir2004) (142 differences):*
'Abba/Gold - Greatest Hits/20 sec/04-Mamma Mia' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/09-Money, Money, Money' 'Abba/Gold - Greatest Hits/20 sec/19-Waterloo' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/12-Culture\_Move' 'Autechre/Amber/20sec/01-Foil' ...
[CSV](data/ismir2004songs_estimates_1.0_scheirer1998_ismir2004_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [scheirer1998/percival2014](#scheirer1998percival2014) (166 differences):*
'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/03-Black\_White' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/05-Free\_Satpal\_Ram' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/09-Naxalite' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/12-Culture\_Move' 'Autechre/Amber/20sec/01-Foil' ...
[CSV](data/ismir2004songs_estimates_1.0_scheirer1998_percival2014_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2014/default](#schreiber2014default) (38 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/01-The\_Miraculous\_Mandarin\_\_\_1.1\_\_Allegro\_\_\_1.2\_\_Curtain' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (40 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/06-The\_Miraculous\_Mandarin\_\_\_6.1\_\_Sempre\_vivo\_\_\_6.2\_\_Adagio' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/09-Music\_for\_Strings\_\_Percussion\_and\_Celesta\_\_I\_\_Andante\_tranquillo' 'Bernstein\_conducts\_Stravinsky/20sec/01-Introduction\_\_Part\_1-\_The\_adoration\_of\_the\_earth\_' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (24 differences):*
'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/06-The\_Miraculous\_Mandarin\_\_\_6.1\_\_Sempre\_vivo\_\_\_6.2\_\_Adagio' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/09-Music\_for\_Strings\_\_Percussion\_and\_Celesta\_\_I\_\_Andante\_tranquillo' 'Bernstein\_conducts\_Stravinsky/20sec/01-Introduction\_\_Part\_1-\_The\_adoration\_of\_the\_earth\_' 'Bernstein\_conducts\_Stravinsky/20sec/02-The\_augurs\_of\_spring' 'Bernstein\_conducts\_Stravinsky/20sec/12-Summoning\_of\_the\_ancestors' 'Bernstein\_conducts\_Stravinsky/20sec/16-Legerdemain\_scene-\_Russian\_danse' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/cnn](#schreiber2018cnn) (36 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bach/20 sec/Bach - Cello suite 1 G - 01 Prelude' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/fcn](#schreiber2018fcn) (30 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/01-The\_Miraculous\_Mandarin\_\_\_1.1\_\_Allegro\_\_\_1.2\_\_Curtain' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/03-The\_Miraculous\_Mandarin\_\_\_3\_\_2nd\_Decoy\_Game' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (38 differences):*
'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' 'Bach - Walcha/DGG 419 047-2/20sec/08-Toccata, Adagio u. Fuge C-dur BWV 564 - II\_ Adagio' 'Bach/20 sec/Bach - BWV 639 - Ich ruf' zu dir, Herr Jesu Christ' 'Bach/20 sec/Bach - Cello suite 1 G - 01 Prelude' 'Bach/20 sec/Bach - Cello suite 2 d - 01 Prelude' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/01-The\_Miraculous\_Mandarin\_\_\_1.1\_\_Allegro\_\_\_1.2\_\_Curtain' 'Bela\_Bartok/The\_Miraculous\_Mandarin\_.\_Music\_For\_Strings\_\_Percussion\_and\_Celesta/20sec/02-The\_Miraculous\_Mandarin\_\_\_2\_\_1st\_Decoy\_Game' ...
[CSV](data/ismir2004songs_estimates_1.0_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) (243 differences):*
'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/01-Assassin' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/02-Change' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/04-Buzzing' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_hist_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) (273 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/10-S. O. S' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/07-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_II\_\_Arrival' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/11-To\_One\_In\_Paradise' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_mmul_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) (221 differences):*
'Abba/Gold - Greatest Hits/20 sec/07-I Have A Dream' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/11-Chiquitita' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/02-The\_Raven' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/04-The\_Cask\_Of\_Amontillado' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' ...
[CSV](data/ismir2004songs_estimates_1.0_tzanetakis2002_ismir2004_msum_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [uhle2004/ismir2004](#uhle2004ismir2004) (130 differences):*
'Abba/Gold - Greatest Hits/20 sec/01-Dancing Queen' 'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/05-\_The\_System\_Of\_\_Doctor\_Tarr\_And\_Professor\_Fether' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/12-Culture\_Move' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/13-Real\_Areas\_For\_Investigation' 'Autechre/Amber/20sec/01-Foil' ...
[CSV](data/ismir2004songs_estimates_1.0_uhle2004_ismir2004_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.0](#10) compared with [zplane/auftakt_v3](#zplaneauftakt_v3) (82 differences):*
'Abba/Gold - Greatest Hits/20 sec/08-The Winner Takes It All' 'Abba/Gold - Greatest Hits/20 sec/12-Fernando' 'Alan\_Parsons\_Project/Tales\_Of\_Mystery\_And\_Imagination/20sec/09-The\_Fall\_Of\_The\_House\_Of\_Usher\_\_IV\_\_Pavane' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/01-Tarrega\_  Recuerdos de la Alhambra' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/02-Lauro\_  Dos Valses Venezolanos - Uno' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/04-Sojo\_  Guaso' 'Alirio Diaz/The Art of Spanish Guitar/20 sec/05-Sojo\_  Cancion' 'Asian\_Dub\_Foundation/R.A.F.I/20sec/09-Naxalite' 'Autechre/Amber/20sec/02-Montreal' 'Autechre/Amber/20sec/10-Nil' 'Bach - Walcha/DGG 419 047-2/20sec/04-Praludium u. Fuge f-moll BWV 534 - II\_ Fuge' ...
[CSV](data/ismir2004songs_estimates_1.0_zplane_auftakt_v3_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>2</sub>:__
'Bernstein\_conducts\_Stravinsky/20sec/16-Legerdemain\_scene-\_Russian\_danse' 
[CSV](data/ismir2004songs_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0587   |   0.0932   | __0.0073__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4469   |   0.0875   |   0.1679   | __0.0000__ | __0.0000__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) | __0.0000__ |   1.0000   | __0.0000__ | __0.0187__ | __0.0013__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ |   0.9366   |   0.0690   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ |   0.1105   | __0.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6342   |   0.6239   |   0.1983   |   0.3099   | __0.0003__ | __0.0240__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1509   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8423   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0187__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1366   | __0.0000__ | __0.0225__ |   0.6658   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4214   | __0.0000__ |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.0587   | __0.0013__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ | __0.0001__ |   0.6769   | __0.0000__ | __0.0000__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   0.0932   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   |   0.2410   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4743   |   0.9233   | __0.0017__ | __0.0000__ | __0.0000__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) | __0.0073__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2410   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0778   |   0.4075   | __0.0001__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ |   0.6342   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   |   0.6790   |   0.8039   | __0.0001__ |   0.1537   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0050__ | __0.0001__ |   0.5676   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7984   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ |   0.6239   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   |   0.5619   |   0.7091   | __0.0001__ |   0.1046   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0009__ | __0.0000__ |   0.4633   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8508   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0000__ | __0.0000__ |   0.1983   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6790   |   0.5619   |   1.0000   |   0.7905   | __0.0000__ |   0.2070   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0037__ | __0.0002__ |   0.9049   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3318   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ |   0.3099   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8039   |   0.7091   |   0.7905   |   1.0000   | __0.0000__ |   0.1307   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0021__ | __0.0002__ |   0.7237   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4504   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0013__ | __0.0003__ |   0.1366   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0017__ |   0.1350   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0395__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0240__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1537   |   0.1046   |   0.2070   |   0.1307   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0059__ | __0.0000__ |   0.1491   | __0.0140__ |   0.3583   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0321__ |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   | __0.0000__ |   0.9366   | __0.0000__ | __0.0225__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0017__ | __0.0000__ |   1.0000   | __0.0395__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ |   0.1534   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.0690   | __0.0000__ |   0.6658   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1350   | __0.0000__ | __0.0395__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8633   | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0116__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0001__ | __0.0002__ | __0.0001__ | __0.0000__ | __0.0059__ | __0.0000__ | __0.0000__ | __0.0002__ |   1.0000   | __0.0000__ |   0.3291   |   0.8453   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0050__ | __0.0009__ | __0.0037__ | __0.0021__ | __0.0000__ |   0.1491   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3291   | __0.0000__ |   1.0000   |   0.1753   | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0002__ | __0.0002__ | __0.0000__ | __0.0140__ | __0.0000__ | __0.0000__ | __0.0116__ |   0.8453   | __0.0000__ |   0.1753   |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ |   0.1509   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5676   |   0.4633   |   0.9049   |   0.7237   | __0.0000__ |   0.3583   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0018__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2616   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) |   0.4469   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0063__ |   0.4743   |   0.0778   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2665   | __0.0005__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) |   0.0875   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   0.9233   |   0.4075   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2665   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.1679   | __0.0005__ | __0.0000__ | __0.0000__ |   0.6769   | __0.0017__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           | __0.0000__ |   0.1105   | __0.0000__ |   0.4214   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0395__ | __0.0000__ |   0.1534   |   0.8633   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ |   0.8423   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7984   |   0.8508   |   0.3318   |   0.4504   | __0.0000__ | __0.0321__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |   0.2616   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0963   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0316__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.0857   | __0.0000__ | __0.0000__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0332__ |   1.0000   | __0.0013__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.8102   |   0.1258   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1814   | __0.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ | __0.0064__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0070__ |   1.0000   |   0.0501   |   0.3449   | __0.0201__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0255__ |   0.1258   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0165__ | __0.0295__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9131   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.0963   | __0.0332__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0129__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0127__ |   0.6299   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0004__ | __0.0000__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0129__ |   1.0000   | __0.0006__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ | __0.0000__ |   0.8707   |   0.1172   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2105   | __0.0000__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) | __0.0000__ | __0.0013__ | __0.0000__ | __0.0255__ | __0.0000__ | __0.0006__ |   1.0000   |   0.5228   | __0.0000__ | __0.0000__ | __0.0000__ |   0.9284   | __0.0000__ | __0.0060__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0492__ | __0.0142__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ |   0.1258   | __0.0000__ | __0.0001__ |   0.5228   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4839   | __0.0004__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0061__ |   0.0700   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   |   0.3604   | __0.0000__ | __0.0054__ | __0.0000__ | __0.0000__ |   0.5327   |   0.7608   | __0.0013__ |   0.2810   | __0.0192__ |   0.4731   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0000__ | __0.0000__ | __0.0064__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   1.0000   |   0.1516   | __0.0000__ | __0.0038__ | __0.0000__ | __0.0000__ |   0.6440   |   0.8830   | __0.0064__ |   0.3915   |   0.0576   |   0.6440   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3604   |   0.1516   |   1.0000   | __0.0000__ |   0.0627   | __0.0000__ | __0.0000__ |   0.1038   |   0.2026   | __0.0001__ | __0.0488__ | __0.0029__ |   0.0884   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0008__ | __0.0000__ | __0.0165__ | __0.0000__ | __0.0013__ |   0.9284   |   0.4839   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0060__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0433__ | __0.0046__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0295__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0054__ | __0.0038__ |   0.0627   | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0004__ | __0.0013__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0498__ |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   | __0.0001__ |   0.8102   | __0.0000__ | __0.0000__ | __0.0127__ |   0.8707   | __0.0060__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0060__ | __0.0000__ |   1.0000   | __0.0283__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3560   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0316__ |   0.1258   | __0.0000__ | __0.0000__ |   0.6299   |   0.1172   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0283__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0045__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5327   |   0.6440   |   0.1038   | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ |   1.0000   |   0.8145   | __0.0125__ |   0.8601   |   0.2153   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0070__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7608   |   0.8830   |   0.2026   | __0.0000__ | __0.0013__ | __0.0000__ | __0.0000__ |   0.8145   |   1.0000   | __0.0001__ |   0.6516   |   0.1641   |   0.8776   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ | __0.0064__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0001__ |   1.0000   |   0.0501   |   0.3771   | __0.0243__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.0501   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2810   |   0.3915   | __0.0488__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ |   0.8601   |   0.6516   |   0.0501   |   1.0000   |   0.3616   |   0.8388   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.3449   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0192__ |   0.0576   | __0.0029__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2153   |   0.1641   |   0.3771   |   0.3616   |   1.0000   |   0.1849   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0201__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4731   |   0.6440   |   0.0884   | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ |   1.0000   |   0.8776   | __0.0243__ |   0.8388   |   0.1849   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) | __0.0008__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0316__ |   0.0717   | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0316__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.0857   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0717   | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           | __0.0000__ |   0.1814   | __0.0000__ | __0.0000__ | __0.0004__ |   0.2105   | __0.0492__ | __0.0061__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0433__ | __0.0000__ |   0.3560   | __0.0045__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.9131   | __0.0000__ | __0.0000__ | __0.0142__ |   0.0700   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0046__ | __0.0498__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.0](#10) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_accuracy1.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_accuracy1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_accuracy1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_accuracy1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_accuracy1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_accuracy2.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_accuracy2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_accuracy2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_accuracy2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_accuracy2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.svg">
</figure>

<a name="figure7"></a>Figure 7: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.svg">
</figure>

<a name="figure8"></a>Figure 8: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.0

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0229__ | __0.2842__ |   -0.0030   | __0.0519__ |
| [schreiber2014/default](#schreiber2014default)     |   0.1444   |   0.4590   |   -0.0130   |   0.0944   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1603   |   0.5139   |   -0.0128   |   0.0918   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.1421   |   0.5146   |   0.0106   |   0.1439   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3019   |   0.5156   |   -0.0036   |   0.0771   |
| [percival2014/stem](#percival2014stem)             |   0.2066   |   0.5242   |   -0.0049   |   0.1192   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3460   |   0.5242   |   -0.0028   |   0.1053   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4071   |   0.5251   |   0.0019   |   0.1532   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3164   |   0.5254   |   -0.0152   |   0.1397   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.2372   |   0.5254   |   -0.0046   |   0.0772   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     |   0.3524   |   0.5275   |   -0.0051   |   0.1065   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3522   |   0.5302   |   -0.0097   |   0.0982   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.4316   |   0.5541   | __0.0016__ |   0.0812   |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) |   0.8706   |   0.5608   |   0.0383   |   0.1690   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.3470   |   0.5687   |   0.0064   |   0.0942   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.2248   |   0.5798   |   0.0078   |   0.1920   |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   0.8089   |   0.5802   |   0.0373   |   0.1747   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5224   |   0.5838   |   0.0462   |   0.1463   |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   |   0.2286   |   0.6392   |   0.0352   |   0.1916   |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) |   0.1958   |   0.6404   |   0.0170   |   0.1796   |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   0.5159   |   0.6759   |   0.0220   |   0.2119   |
| [uhle2004/ismir2004](#uhle2004ismir2004)           |   0.4019   |   0.6868   |   0.0378   |   0.1721   |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) |   0.6371   |   0.7206   |   0.0583   |   0.2416   |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.5418   |   0.7540   |   0.0568   |   0.2202   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.4399   |   0.8120   |   0.0545   |   0.2042   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) |   0.8221   |   0.9669   |   0.1115   |   0.2571   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.0](#10) ordered by standard deviation.

[CSV](data/ismir2004songs_estimates_1.0_moe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_moe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_moe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_oe1.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_oe1.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_oe2.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_oe2.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_distribution_oe1.svg">
</figure>

<a name="figure9"></a>Figure 9: OE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ismir2004songs_estimates_1.0_distribution_oe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_distribution_oe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_distribution_oe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_distribution_oe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_distribution_oe2.svg">
</figure>

<a name="figure10"></a>Figure 10: OE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ismir2004songs_estimates_1.0_distribution_oe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_distribution_oe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_distribution_oe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_distribution_oe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   | __0.0000__ | __0.0065__ |   0.8245   | __0.0483__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ |   0.4914   | __0.0006__ | __0.0000__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0812   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7187   |   0.4669   |   0.4902   |   0.0667   |   0.1749   | __0.0000__ | __0.0005__ |   0.2002   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0065__ | __0.0000__ |   1.0000   | __0.0001__ |   0.8091   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0002__ | __0.0001__ |   0.2732   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0009__ |   0.3070   | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8245   | __0.0000__ | __0.0001__ |   1.0000   | __0.0070__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5083   | __0.0000__ | __0.0000__ |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) | __0.0483__ | __0.0000__ |   0.8091   | __0.0070__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0068__ | __0.0055__ | __0.0027__ |   0.3245   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0106__ | __0.0000__ | __0.0000__ | __0.0039__ |   0.2892   | __0.0001__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0131__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6127   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0131__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2741   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ |   0.0812   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0068__ | __0.0041__ | __0.0093__ |   0.9179   |   0.4202   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0068__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.7928   |   0.9671   | __0.0114__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0653   | __0.0000__ |   0.8110   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0576   |   0.1942   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0055__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7928   |   1.0000   |   0.1464   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0193__ | __0.0000__ |   0.9892   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0273__ | __0.0282__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0027__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9671   |   0.1464   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0428__ | __0.0000__ |   0.6976   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0122__ |   0.0791   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0002__ | __0.0000__ |   0.2732   | __0.0000__ |   0.3245   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0114__ | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0038__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8272   | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.7187   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0068__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.3888   |   0.1155   | __0.0011__ | __0.0141__ | __0.0000__ | __0.0000__ |   0.2368   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   | __0.0000__ |   0.4669   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0041__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3888   |   1.0000   |   0.4122   | __0.0018__ | __0.0107__ | __0.0000__ | __0.0099__ |   0.7712   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ |   0.4902   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0093__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1155   |   0.4122   |   1.0000   | __0.0006__ | __0.0053__ | __0.0000__ | __0.0052__ |   0.6622   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ |   0.0667   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9179   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0011__ | __0.0018__ | __0.0006__ |   1.0000   |   0.3250   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ |   0.1749   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4202   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0141__ | __0.0107__ | __0.0053__ |   0.3250   |   1.0000   | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0653   | __0.0193__ | __0.0428__ | __0.0000__ | __0.0000__ | __0.0099__ | __0.0052__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0019__ | __0.0071__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   0.5239   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ |   0.2002   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2368   |   0.7712   |   0.6622   | __0.0000__ | __0.0009__ | __0.0000__ | __0.0019__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0106__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8110   |   0.9892   |   0.6976   | __0.0038__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0071__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0542   |   0.0660   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6127   |   0.2741   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.4914   | __0.0000__ | __0.0009__ |   0.5083   | __0.0039__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           | __0.0006__ | __0.0000__ |   0.3070   | __0.0000__ |   0.2892   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0576   | __0.0273__ | __0.0122__ |   0.8272   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ |   0.0542   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0009__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1942   | __0.0282__ |   0.0791   | __0.0000__ | __0.0000__ | __0.0009__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5239   | __0.0014__ |   0.0660   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   |   0.9298   | __0.0452__ | __0.0274__ | __0.0172__ |   0.1051   |   0.1638   |   0.2900   |   0.1184   | __0.0089__ | __0.0146__ |   0.0809   | __0.0157__ |   0.3171   |   0.2783   | __0.0012__ | __0.0015__ | __0.0121__ | __0.0150__ | __0.0110__ | __0.0040__ | __0.0000__ | __0.0153__ | __0.0087__ |   0.1636   | __0.0010__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) |   0.9298   |   1.0000   |   0.0732   | __0.0049__ | __0.0027__ |   0.1560   |   0.0591   |   0.4128   |   0.2657   | __0.0202__ | __0.0424__ |   0.1301   | __0.0218__ |   0.1381   |   0.4094   | __0.0014__ | __0.0018__ | __0.0241__ | __0.0316__ | __0.0202__ | __0.0056__ | __0.0000__ | __0.0032__ | __0.0030__ |   0.0899   | __0.0046__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0452__ |   0.0732   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2169   |   0.2892   |   0.2271   |   0.4482   |   0.9750   |   0.2674   | __0.0005__ |   0.5037   | __0.0018__ | __0.0027__ |   0.2303   |   0.2831   |   0.2110   | __0.0181__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0141__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0274__ | __0.0049__ | __0.0000__ |   1.0000   |   0.4223   |   0.5739   |   0.3705   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3026   | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3323   |   0.3349   |   0.3654   | __0.0000__ |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) | __0.0172__ | __0.0027__ | __0.0000__ |   0.4223   |   1.0000   |   0.1334   |   0.1402   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1542   | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7693   |   0.8546   |   0.1616   | __0.0000__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   0.1051   |   0.1560   | __0.0000__ |   0.5739   |   0.1334   |   1.0000   |   0.5862   | __0.0034__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ |   0.8620   | __0.0158__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2492   |   0.3385   |   0.7899   | __0.0000__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) |   0.1638   |   0.0591   | __0.0000__ |   0.3705   |   0.1402   |   0.5862   |   1.0000   | __0.0054__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ |   0.7980   | __0.0117__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1011   |   0.0931   |   0.9604   | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.2900   |   0.4128   |   0.2169   | __0.0000__ | __0.0001__ | __0.0034__ | __0.0054__ |   1.0000   |   0.5695   | __0.0267__ | __0.0500__ |   0.2996   |   0.0589   | __0.0200__ |   0.7226   | __0.0014__ | __0.0016__ | __0.0484__ |   0.0531   | __0.0384__ | __0.0073__ | __0.0000__ | __0.0004__ | __0.0002__ | __0.0071__ | __0.0015__ |
| [gkiokas2012/default](#gkiokas2012default)         |   0.1184   |   0.2657   |   0.2892   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0002__ |   0.5695   |   1.0000   | __0.0275__ |   0.0982   |   0.5626   |   0.1024   | __0.0026__ |   0.8134   | __0.0001__ | __0.0001__ | __0.0296__ | __0.0413__ | __0.0156__ | __0.0031__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0015__ |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0089__ | __0.0202__ |   0.2271   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0267__ | __0.0275__ |   1.0000   |   0.5640   |   0.3531   |   0.9705   | __0.0000__ |   0.1212   |   0.1416   |   0.1537   |   0.6411   |   0.7870   |   0.9152   |   0.4563   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1222   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0146__ | __0.0424__ |   0.4482   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0500__ |   0.0982   |   0.5640   |   1.0000   |   0.5435   |   0.8068   | __0.0001__ |   0.2471   |   0.0563   |   0.0633   |   0.9719   |   0.8718   |   0.7299   |   0.2338   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0494__ |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.0809   |   0.1301   |   0.9750   | __0.0000__ | __0.0000__ | __0.0006__ | __0.0002__ |   0.2996   |   0.5626   |   0.3531   |   0.5435   |   1.0000   |   0.4193   | __0.0021__ |   0.3732   | __0.0438__ | __0.0421__ |   0.4974   |   0.4795   |   0.4294   |   0.1433   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0366__ |
| [percival2014/stem](#percival2014stem)             | __0.0157__ | __0.0218__ |   0.2674   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0589   |   0.1024   |   0.9705   |   0.8068   |   0.4193   |   1.0000   | __0.0002__ |   0.2577   |   0.1408   |   0.1409   |   0.7158   |   0.8312   |   0.9585   |   0.4366   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1547   |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   |   0.3171   |   0.1381   | __0.0005__ |   0.3026   |   0.1542   |   0.8620   |   0.7980   | __0.0200__ | __0.0026__ | __0.0000__ | __0.0001__ | __0.0021__ | __0.0002__ |   1.0000   | __0.0179__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1057   |   0.1042   |   0.8226   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.2783   |   0.4094   |   0.5037   | __0.0006__ | __0.0005__ | __0.0158__ | __0.0117__ |   0.7226   |   0.8134   |   0.1212   |   0.2471   |   0.3732   |   0.2577   | __0.0179__ |   1.0000   | __0.0198__ | __0.0180__ |   0.2292   |   0.2520   |   0.1389   |   0.0934   | __0.0000__ | __0.0002__ | __0.0001__ | __0.0115__ | __0.0084__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0012__ | __0.0014__ | __0.0018__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0014__ | __0.0001__ |   0.1416   |   0.0563   | __0.0438__ |   0.1408   | __0.0000__ | __0.0198__ |   1.0000   |   0.9520   | __0.0139__ | __0.0355__ |   0.0820   |   0.4658   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7430   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0015__ | __0.0018__ | __0.0027__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ | __0.0001__ |   0.1537   |   0.0633   | __0.0421__ |   0.1409   | __0.0000__ | __0.0180__ |   0.9520   |   1.0000   | __0.0152__ |   0.0612   |   0.1029   |   0.5424   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6983   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0121__ | __0.0241__ |   0.2303   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0484__ | __0.0296__ |   0.6411   |   0.9719   |   0.4974   |   0.7158   | __0.0000__ |   0.2292   | __0.0139__ | __0.0152__ |   1.0000   |   0.8506   |   0.6895   |   0.1374   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0499__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0150__ | __0.0316__ |   0.2831   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0531   | __0.0413__ |   0.7870   |   0.8718   |   0.4795   |   0.8312   | __0.0001__ |   0.2520   | __0.0355__ |   0.0612   |   0.8506   |   1.0000   |   0.8140   |   0.1873   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1064   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0110__ | __0.0202__ |   0.2110   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0384__ | __0.0156__ |   0.9152   |   0.7299   |   0.4294   |   0.9585   | __0.0000__ |   0.1389   |   0.0820   |   0.1029   |   0.6895   |   0.8140   |   1.0000   |   0.2914   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1259   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0040__ | __0.0056__ | __0.0181__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0073__ | __0.0031__ |   0.4563   |   0.2338   |   0.1433   |   0.4366   | __0.0000__ |   0.0934   |   0.4658   |   0.5424   |   0.1374   |   0.1873   |   0.2914   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4329   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) | __0.0153__ | __0.0032__ | __0.0000__ |   0.3323   |   0.7693   |   0.2492   |   0.1011   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1057   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |   0.8931   |   0.1162   | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) | __0.0087__ | __0.0030__ | __0.0000__ |   0.3349   |   0.8546   |   0.3385   |   0.0931   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1042   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8931   |   1.0000   |   0.1011   | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           |   0.1636   |   0.0899   | __0.0000__ |   0.3654   |   0.1616   |   0.7899   |   0.9604   | __0.0071__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ |   0.8226   | __0.0115__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1162   |   0.1011   |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0010__ | __0.0046__ | __0.0141__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0015__ | __0.0015__ |   0.1222   | __0.0494__ | __0.0366__ |   0.1547   | __0.0000__ | __0.0084__ |   0.7430   |   0.6983   | __0.0499__ |   0.1064   |   0.1259   |   0.4329   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_oe1.svg">
</figure>

<a name="figure11"></a>Figure 11: Mean OE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_oe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_oe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_oe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_oe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_oe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_oe2.svg">
</figure>

<a name="figure12"></a>Figure 12: Mean OE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_oe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_oe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_oe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_oe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_oe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_oe1.svg">
</figure>

<a name="figure13"></a>Figure 13: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_oe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_oe2.svg">
</figure>

<a name="figure14"></a>Figure 14: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_oe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.0

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0886__ | __0.2710__ | __0.0184__ | __0.0486__ |
| [schreiber2014/default](#schreiber2014default)     |   0.2427   |   0.4155   |   0.0327   |   0.0895   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.2984   |   0.4480   |   0.0322   |   0.0869   |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   |   0.3142   |   0.4316   |   0.0676   |   0.1275   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.3148   |   0.4829   |   0.0255   |   0.0730   |
| [percival2014/stem](#percival2014stem)             |   0.3342   |   0.4536   |   0.0479   |   0.1093   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.3447   |   0.4881   |   0.0263   |   0.0726   |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             |   0.3841   |   0.4781   |   0.0605   |   0.1268   |
| [klapuri2006/percival2014](#klapuri2006percival2014) |   0.3905   |   0.4920   |   0.0371   |   0.0986   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     |   0.3978   |   0.4942   |   0.0365   |   0.1002   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.3990   |   0.4960   |   0.0343   |   0.0925   |
| [scheirer1998/percival2014](#scheirer1998percival2014) |   0.4119   |   0.4659   |   0.1040   |   0.1616   |
| [gkiokas2012/default](#gkiokas2012default)         |   0.4247   |   0.5132   |   0.0335   |   0.0883   |
| [oliveira2010/ibt](#oliveira2010ibt)               |   0.4511   |   0.4878   |   0.0746   |   0.1338   |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   0.4599   |   0.5309   |   0.0248   |   0.0774   |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) |   0.4764   |   0.4707   |   0.0996   |   0.1504   |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   |   0.4896   |   0.4703   |   0.1099   |   0.1609   |
| [uhle2004/ismir2004](#uhle2004ismir2004)           |   0.5597   |   0.5656   |   0.0931   |   0.1496   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.5616   |   0.5462   |   0.0722   |   0.1354   |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   0.6621   |   0.5333   |   0.1348   |   0.1650   |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.7048   |   0.6044   |   0.1391   |   0.1800   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.7130   |   0.5868   |   0.1196   |   0.1743   |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) |   0.7608   |   0.5884   |   0.1702   |   0.1811   |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) |   0.8342   |   0.5431   |   0.0907   |   0.1539   |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) |   0.8944   |   0.5221   |   0.0838   |   0.1517   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) |   1.0447   |   0.7208   |   0.1742   |   0.2195   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.0](#10) ordered by mean.

[CSV](data/ismir2004songs_estimates_1.0_maoe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_maoe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_maoe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_aoe1.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_aoe1.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/ismir2004songs_estimates_1.0_raw_aoe2.csv "Download raw data as CSV") [JSON](data/ismir2004songs_estimates_1.0_raw_aoe2.json "Download raw data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_distribution_aoe1.svg">
</figure>

<a name="figure15"></a>Figure 15: AOE<sub>1</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ismir2004songs_estimates_1.0_distribution_aoe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_distribution_aoe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_distribution_aoe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_distribution_aoe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_distribution_aoe2.svg">
</figure>

<a name="figure16"></a>Figure 16: AOE<sub>2</sub> for estimates compared to version [1.0](#10). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/ismir2004songs_estimates_1.0_distribution_aoe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_distribution_aoe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_distribution_aoe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_distribution_aoe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   | __0.0000__ | __0.0000__ | __0.0003__ |   0.1068   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0016__ |   0.1852   | __0.0004__ | __0.0000__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) | __0.0000__ |   1.0000   |   0.4757   | __0.0093__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0391__ | __0.0035__ | __0.0014__ |   0.3446   | __0.0000__ |   0.7640   | __0.0053__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0069__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0114__ | __0.0007__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0000__ |   0.4757   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.1132   | __0.0037__ | __0.0010__ |   0.6842   | __0.0000__ |   0.2781   |   0.2223   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0058__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0006__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0003__ | __0.0093__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0060__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9344   | __0.0000__ |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.1068   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0881   |   0.7788   | __0.0000__ | __0.0000__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0316__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0316__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0010__ | __0.0028__ | __0.0000__ |   0.3845   | __0.0000__ | __0.0067__ | __0.0006__ |   0.4754   | __0.0000__ |   0.2029   |   0.9811   | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0032__ |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0391__ |   0.1132   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.2595   |   0.1416   |   0.2451   | __0.0001__ | __0.0196__ |   0.5817   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0008__ | __0.0000__ |   0.3025   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0742   |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0000__ | __0.0035__ | __0.0037__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0010__ |   0.2595   |   1.0000   |   0.0988   | __0.0001__ | __0.0002__ | __0.0002__ |   0.1933   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0132__ | __0.0007__ |   0.9467   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3822   |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0014__ | __0.0010__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0028__ |   0.1416   |   0.0988   |   1.0000   | __0.0000__ | __0.0008__ | __0.0000__ |   0.0881   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0344__ | __0.0021__ |   0.5980   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.7014   |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ |   0.3446   |   0.6842   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2451   | __0.0001__ | __0.0000__ |   1.0000   | __0.0000__ |   0.1193   |   0.1328   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0054__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3845   | __0.0001__ | __0.0002__ | __0.0008__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0002__ | __0.0000__ |   0.0504   | __0.0000__ |   0.6405   |   0.4433   | __0.0019__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0067__ |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   | __0.0000__ |   0.7640   |   0.2781   | __0.0060__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0196__ | __0.0002__ | __0.0000__ |   0.1193   | __0.0000__ |   1.0000   | __0.0020__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0000__ | __0.0053__ |   0.2223   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0067__ |   0.5817   |   0.1933   |   0.0881   |   0.1328   | __0.0002__ | __0.0020__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0093__ | __0.0009__ |   0.5538   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2415   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4754   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0504   | __0.0000__ | __0.0000__ | __0.0004__ |   1.0000   | __0.0000__ | __0.0345__ |   0.4690   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2029   | __0.0008__ | __0.0132__ | __0.0344__ | __0.0000__ |   0.6405   | __0.0000__ | __0.0093__ | __0.0000__ | __0.0345__ | __0.0000__ |   1.0000   |   0.1479   | __0.0033__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0703   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.9811   | __0.0000__ | __0.0007__ | __0.0021__ | __0.0000__ |   0.4433   | __0.0000__ | __0.0009__ | __0.0009__ |   0.4690   | __0.0000__ |   0.1479   |   1.0000   | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0042__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0069__ | __0.0058__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0006__ |   0.3025   |   0.9467   |   0.5980   | __0.0054__ | __0.0019__ | __0.0007__ |   0.5538   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0033__ | __0.0003__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4255   |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) | __0.0016__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0881   | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0034__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.1852   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7788   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0034__ |   1.0000   | __0.0000__ | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           | __0.0004__ | __0.0114__ | __0.0002__ |   0.9344   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0125__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0007__ | __0.0006__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0032__ |   0.0742   |   0.3822   |   0.7014   | __0.0000__ | __0.0067__ | __0.0000__ |   0.2415   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0703   | __0.0042__ |   0.4255   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| alonso2004/ismir2004_corr | alonso2004/ismir2004_spec | boeck2015/tempodetector2016_default | davies2009/mirex_qm_tempotracker | dixon2001/ismir2004_indu | dixon2001/ismir2004_trac | dixon2003/ismir2004_auco | echonest/version_3_2_1 | gkiokas2012/default | klapuri2006/ismir2004 | klapuri2006/percival2014 | oliveira2010/ibt | percival2014/stem | scheirer1998/ismir2004 | scheirer1998/percival2014 | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 | tzanetakis2002/ismir2004_hist | tzanetakis2002/ismir2004_mmul | tzanetakis2002/ismir2004_msum | uhle2004/ismir2004 | zplane/auftakt_v3 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [alonso2004/ismir2004_corr](#alonso2004ismir2004_corr) |   1.0000   | __0.0001__ | __0.0000__ | __0.0000__ |   0.1317   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0156__ | __0.0016__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ | __0.0007__ |   0.6557   | __0.0000__ | __0.0000__ |
| [alonso2004/ismir2004_spec](#alonso2004ismir2004_spec) | __0.0001__ |   1.0000   | __0.0000__ | __0.0010__ |   0.0582   |   0.3256   | __0.0352__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0020__ | __0.0000__ |   0.3979   |   0.7233   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   0.4046   | __0.0000__ |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0398__ | __0.0300__ | __0.0184__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0702   |   0.1007   |   0.0772   |   0.7217   |   0.8784   | __0.0268__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0010__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0042__ |   0.1217   |   0.5181   | __0.0000__ | __0.0000__ | __0.0000__ |   0.7276   | __0.0003__ | __0.0000__ | __0.0016__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0085__ |   0.0980   |
| [dixon2001/ismir2004_indu](#dixon2001ismir2004_indu) |   0.1317   |   0.0582   | __0.0000__ | __0.0000__ |   1.0000   | __0.0056__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3403   |   0.0971   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0443__ | __0.0044__ | __0.0000__ |
| [dixon2001/ismir2004_trac](#dixon2001ismir2004_trac) | __0.0000__ |   0.3256   | __0.0000__ | __0.0042__ | __0.0056__ |   1.0000   |   0.0871   | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0185__ | __0.0000__ |   0.0760   |   0.1475   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8015   | __0.0001__ |
| [dixon2003/ismir2004_auco](#dixon2003ismir2004_auco) | __0.0000__ | __0.0352__ | __0.0000__ |   0.1217   | __0.0000__ |   0.0871   |   1.0000   | __0.0368__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2495   | __0.0000__ | __0.0062__ |   0.0890   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.2619   | __0.0021__ |
| [echonest/version_3_2_1](#echonestversion_3_2_1)   | __0.0000__ | __0.0000__ | __0.0000__ |   0.5181   | __0.0000__ | __0.0007__ | __0.0368__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ |   0.2722   | __0.0022__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0013__ |   0.2678   |
| [gkiokas2012/default](#gkiokas2012default)         | __0.0000__ | __0.0000__ | __0.0398__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.5318   |   0.4384   | __0.0000__ | __0.0102__ | __0.0000__ | __0.0000__ |   0.8845   |   0.8023   | __0.0002__ |   0.0707   | __0.0416__ |   0.8486   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/ismir2004](#klapuri2006ismir2004)     | __0.0000__ | __0.0000__ | __0.0300__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.5318   |   1.0000   |   0.8027   | __0.0000__ | __0.0452__ | __0.0000__ | __0.0000__ |   0.4626   |   0.4034   | __0.0000__ | __0.0238__ | __0.0196__ |   0.6729   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [klapuri2006/percival2014](#klapuri2006percival2014) | __0.0000__ | __0.0000__ | __0.0184__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.4384   |   0.8027   |   1.0000   | __0.0000__ |   0.0555   | __0.0000__ | __0.0000__ |   0.3714   |   0.3235   | __0.0000__ | __0.0157__ | __0.0091__ |   0.5708   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [oliveira2010/ibt](#oliveira2010ibt)               | __0.0000__ | __0.0020__ | __0.0000__ |   0.7276   | __0.0000__ | __0.0185__ |   0.2495   |   0.2722   | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0001__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0203__ | __0.0203__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0022__ | __0.0102__ | __0.0452__ |   0.0555   | __0.0001__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0032__ | __0.0020__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0106__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0355__ |
| [scheirer1998/ismir2004](#scheirer1998ismir2004)   | __0.0156__ |   0.3979   | __0.0000__ | __0.0000__ |   0.3403   |   0.0760   | __0.0062__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ |   1.0000   |   0.2380   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0060__ |   0.0736   | __0.0000__ |
| [scheirer1998/percival2014](#scheirer1998percival2014) | __0.0016__ |   0.7233   | __0.0000__ | __0.0016__ |   0.0971   |   0.1475   |   0.0890   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ | __0.0000__ |   0.2380   |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0005__ |   0.2901   | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ |   0.0702   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8845   |   0.4626   |   0.3714   | __0.0000__ | __0.0032__ | __0.0000__ | __0.0000__ |   1.0000   |   0.8608   | __0.0002__ |   0.0997   |   0.0738   |   0.6960   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0000__ | __0.0000__ |   0.1007   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8023   |   0.4034   |   0.3235   | __0.0000__ | __0.0020__ | __0.0000__ | __0.0000__ |   0.8608   |   1.0000   | __0.0001__ |   0.1844   |   0.1311   |   0.6528   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0000__ | __0.0000__ |   0.0772   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ | __0.0001__ |   1.0000   | __0.0110__ | __0.0415__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0000__ | __0.0000__ |   0.7217   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0707   | __0.0238__ | __0.0157__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |   0.0997   |   0.1844   | __0.0110__ |   1.0000   |   0.8181   | __0.0330__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0000__ | __0.0000__ |   0.8784   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0416__ | __0.0196__ | __0.0091__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.0738   |   0.1311   | __0.0415__ |   0.8181   |   1.0000   | __0.0192__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0000__ | __0.0000__ | __0.0268__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.8486   |   0.6729   |   0.5708   | __0.0000__ | __0.0106__ | __0.0000__ | __0.0000__ |   0.6960   |   0.6528   | __0.0001__ | __0.0330__ | __0.0192__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_hist](#tzanetakis2002ismir2004_hist) | __0.0004__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   |   0.6959   | __0.0000__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_mmul](#tzanetakis2002ismir2004_mmul) | __0.0007__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.6959   |   1.0000   | __0.0002__ | __0.0000__ | __0.0000__ |
| [tzanetakis2002/ismir2004_msum](#tzanetakis2002ismir2004_msum) |   0.6557   | __0.0002__ | __0.0000__ | __0.0000__ | __0.0443__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0060__ | __0.0005__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0002__ |   1.0000   | __0.0000__ | __0.0000__ |
| [uhle2004/ismir2004](#uhle2004ismir2004)           | __0.0000__ |   0.4046   | __0.0000__ | __0.0085__ | __0.0044__ |   0.8015   |   0.2619   | __0.0013__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0203__ | __0.0000__ |   0.0736   |   0.2901   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0001__ |
| [zplane/auftakt_v3](#zplaneauftakt_v3)             | __0.0000__ | __0.0000__ | __0.0000__ |   0.0980   | __0.0000__ | __0.0001__ | __0.0021__ |   0.2678   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0203__ | __0.0355__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0001__ |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.0](#10) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/ismir2004songs_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_aoe1.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean AOE<sub>1</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_aoe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_aoe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_aoe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_aoe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.0

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_inter_aoe2.svg">
</figure>

<a name="figure18"></a>Figure 18: Mean AOE<sub>2</sub> for estimates compared to version [1.0](#10) for tempo intervals around T.

[CSV](data/ismir2004songs_estimates_1.0_inter_aoe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_inter_aoe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_inter_aoe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_inter_aoe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_aoe1.svg">
</figure>

<a name="figure19"></a>Figure 19: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.0

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.0](#10).

<figure>
<embed type="image/svg+xml" src="figures/ismir2004songs_estimates_1.0_tempo_gam_aoe2.svg">
</figure>

<a name="figure20"></a>Figure 20: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.0](#10). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/ismir2004songs_estimates_1.0_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/ismir2004songs_estimates_1.0_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/ismir2004songs_estimates_1.0_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/ismir2004songs_estimates_1.0_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/ismir2004songs_estimates_1.0_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.0 on 2020-10-14 08:37. Size L.
