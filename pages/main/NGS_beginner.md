---
title: NGS beginner
tags:
keywords: "features, capabilities, scalability, multichannel output, dita, hats, comparison, benefits"
last_updated: "August 22, 2017"
published: true
sidebar: site_sidebar
permalink: NGS_beginner.html
wide: true
---

## Summary
This manual introduces the basics of next generation sequence (NGS) data to researchers who would like to get started with sequencing their data.To explore and visualize the resulting read pileups along with genome annotation features, this tutorial also introduces the very easy-to-use IGV genome browser from the Broad Institute. No special computer knowledge is required to work through this manual. Its content should be useful for both complete beginners in the NGS analysis area and intermediate users who are mainly interested in visualizing their NGS results.

### File Formats for Sequences, Alignments and Annotations
A basic knowledge of the most common sequence, alignment and annotation formats is often useful to understand the inputs/outputs and contents of many analysis tools used in the NGS field. The table below lists some of the most commonly used data formats. More detailed information can be found at the [UCSC Genome Browser](http://genome.ucsc.edu/FAQ/FAQformat) and the [IGV](http://software.broadinstitute.org/software/igv/FileFormats) sites.

Source Data | Recommended File Formats
----------- | ------------------------
Sequence and base call quality data | FASTQ and FASTA formats
Sequence alignment data | SAM and BAM formats
Genome annotations	| GTF, GFF and BED format
Dense continuous data (e.g. %GC) | WIG and bigWig

## Command-line tools
[NGSUtils](http://ngsutils.org/) is made up of programs in Python. They are separated into modules based on the type of file that is to be analyzed. There are four modules:

*bamutils (BAM/SAM files)
*bedutils (BED files)
*fastqutils (FASTQ files, base- and color-space)
*gtfutils (GTF gene models)

## Galaxy for NGS Analysis
[Main Galaxy website](https://galaxyproject.org/)

[Use Galaxy](https://usegalaxy.org/)
### Tutorials on Galaxy
[Galaxy tutorials](https://galaxyproject.org/learn/)

## Visualization

IGV (Integrated Genome Viewer)

### Genome Browsers
UCSC Genome Browser



