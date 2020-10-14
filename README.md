# Nextflow test datasets for CI

This repo contains small viral sequencing datasets for different sequencing platforms (Illumina, Ion Torrent, Nanopore).


Workflows using test datasets will specify the URL to a test dataset as input and Nextflow will figure out how to get the data to execute the workflow on it, e.g. in a `test` profile specified in a `test.config`


```
params.input = https://github.com/peterk87/nf-test-datasets/raw/iontorrent/ampliseq/a.bam
```
