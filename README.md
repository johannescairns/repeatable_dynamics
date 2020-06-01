# Repeatable dynamics

This is a companion to the manuscript in preparation (pre-print doi: https://doi.org/10.1101/2020.03.10.985184):

> “Repeatable ecological dynamics govern response of experimental community to antibiotic pulse perturbation“
>
> Johannes Cairns, Roosa Jokela, Lutz Becks, Ville Mustonen, Teppo Hiltunen

To clone the repository:

```sh
git clone https://github.com/johannescairns/repeatable_dynamics.git
```

To run the analyses of our study, we must create a python environment where we can run the code using conda:

```sh
conda env create --file=environment.yaml
```

The `data` directory contains phenotypic (amplicon_data) and whole genome (deep_seq) data for the experiment. The `src` directory has code to reproduce all figures in the paper.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
