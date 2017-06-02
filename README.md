# POS Tagging Experiments

This repository contains experiments in Vietnamese POS Tagging problems. It is a part of [underthesea](https://github.com/magizbox/underthesea) project.

## Corpus Summary 

Corpus is in [UniversalDependencies format](https://github.com/UniversalDependencies/UD_Vietnamese).

```
Sentences    : 16281
Unique words : 19742
Top words    : ,, ., của, ", là, và, một, có, được, người, không, đã, cho, những, :, -, “, ..., ”, ở
Pos Tags     : 29
List tags    : A, Ab, B, C, CH, Cb, Cc, E, Eb, I, L, M, Mb, N, Nb, Nc, Np, Nu, Ny, P, Pb, R, T, V, Vb, Vy, X, Y, Z
```
## Reports

![](https://img.shields.io/badge/accuracy-92.3%25-red.svg)

* Detail Reports, [link](https://docs.google.com/spreadsheets/d/12bqhU5NS9rxM9kY2pBjRSB6Av_XsoOonHEqiv-lDKZw/edit?usp=sharing)
* Vietnamese POS Tagging publications, [link](https://docs.google.com/spreadsheets/d/12bqhU5NS9rxM9kY2pBjRSB6Av_XsoOonHEqiv-lDKZw/edit#gid=26250307)

## How to usage

```
# clone project
$ git clone git@github.com:magizbox/underthesea.chunking.git
$ cd underthesea.chunking

# create environment
$ conda env create -f environment.yml
$ source activate underthesea.pos_tag
```
Last update: June 2017