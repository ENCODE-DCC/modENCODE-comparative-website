---
layout: page
order: 2
title: Regulation
permalink: /regulation/
subproject: true
teaser: /assets/images/regulation.png
abstract: Despite the extremely large evolutionary distances separating metazoan species, they show remarkable commonalities, which has helped establish fly and worm as model organisms for human biology. Although studies of individual elements and factors have explored similarities in gene regulation, a large scale comparative analysis of basic principles of transcriptional regulatory features is lacking. To address this lack we mapped the genome-wide binding locations of 165 human, 93 worm, and 52 fly transcription-regulatory factors (RFs) generating a total of 1,019 data sets from a variety of cell-types, developmental stages, or conditions in the three species, of which 498 are presented here for the first time. We find that structural properties of regulatory networks are remarkably conserved, including clustering of RFs in high-occupancy target (HOT) regions, differential chromatin signatures associated with context specific vs. constitutive HOT regions, and the relative frequency of network motifs. Moreover, orthologous RF families recognize similar binding motifs in vivo and show some similar co-associations, despite dramatic divergence in their specific regulatory targets. Our results suggest that gene-regulatory properties previously observed for individual factors are in fact general principles of metazoan regulation that are remarkably well-preserved despite extensive functional divergence of individual network connections. The comparative maps of regulatory circuitry provided here will be crucial in understanding the regulatory underpinnings of model organism biology and how these relate to human biology, development, and disease.

paper:
  title: Comparative analysis of regulatory information and circuits across distant species

  authors: Boyle AP, Araya CL, Brdlik C, Cayting P, Cheng C, Cheng Y, Gardner K, Hillier L, Janette J, Jiang L, Kasper D, Kawli T, Kheradpour P, Kundaje A, Li JJ, Ma L, Niu W, Rehm EJ, Rozowsky J, Slattery M, Spokony R, Terrell R, Vafeados D, Wang D, Weisdepp P, Wu Y, Xie D, Yan K, Feingold EA, Good PJ, Pazin MJ, Huang H, Bickel PJ, Brenner SE, Reinke V, Waterston RH, Gerstein M, White KP, Kellis M, and Snyder M

  authors_short: Boyle et al.

  meta: Nature 512:453–456, 2014

  url: http://www.nature.com/nature/journal/v512/n7515/full/nature13668.html  
---

The data below provide data from all stages of the uniformly processed ENCODE and  modENCODE data for human,  worm (_C. elegans_) and fly (_D. melanogaster_) until the July 2012 Freeze that is being used in the joint modENCODE/ENCODE analysis papers.

#  Available data

* [Human](#Human)
      0. [Dataset reference](#Humanset0)
      1. [Genome Assembly](#Humanset1)
      2. [Raw Alignments ](#Humanset2)
      3. [Unique Alignments ](#Humanset3)
      4. [MetaData and Data Quality Metrics](#Humanset4)
      5. [Blacklist regions ](#Humanset5)
      6. [IDR Uniform Peak Calls ](#Humanset6)
      7. [Blacklist Filtered Peak Calls (for primary data analysis)](#Humanset7)
      8. [Unthresholded Peak Calls](#Humanset8)
      9. [Signal Tracks (input normalized)](#Humanset9)
      10. [Unique Mappability track](#Humanset10)
      11. [TF Target Predictions](#Humanset11)
      12. [HOT Regions](#Humanset12)

* [Worm](#Worm)
      0. [Dataset reference](#Wormset0)
      1. [Genome Assembly](#Wormset1)
      2. [Raw Alignments ](#Wormset2)
      3. [Unique Alignments ](#Wormset3)
      4. [MetaData and Data Quality Metrics](#Wormset4)
      5. [Blacklist regions ](#Wormset5)
      6. [IDR Uniform Peak Calls ](#Wormset6)
      7. [Blacklist Filtered Peak Calls (for primary data analysis)](#Wormset7)
      8. [Unthresholded Peak Calls](#Wormset8)
      9. [Signal Tracks (input normalized)](#Wormset9)
      10. [Unique Mappability track](#Wormset10)
      11. [TF Target Predictions](#Wormset11)
      12. [HOT Regions](#Wormset12)
  
* [Fly](#Fly)
      0. [Dataset reference](#Flyset0)
      1. [Genome Assembly](#Flyset1)
      2. [Raw Alignments ](#Flyset2)
      3. [Unique Alignments ](#Flyset3)
      4. [MetaData and Data Quality Metrics](#Flyset4)
      5. [Blacklist regions ](#Flyset5)
      6. [IDR Uniform Peak Calls ](#Flyset6)
      7. [Blacklist Filtered Peak Calls (for primary data analysis)](#Flyset7)
      8. [Unthresholded Peak Calls](#Flyset8)
      9. [Signal Tracks (input normalized)](#Flyset9)
      10. [Unique Mappability track](#Flyset10)
      11. [TF Target Predictions](#Flyset11)
      12. [HOT Regions](#Flyset12)


<a name="Human"></a>

# Human

<a name="Humanset0"></a>

# 0. Dataset Reference

## Description

All human datasets were processed uniformly for the steps below. Here we provide a reference file to map all datasets to their originating ENCODE Accession ID as well as appropriate metadata. Downloadable files in the sections below map to either a File Prefix, a UCSC Accession ID or an EncodeDCC Accession ID.

## Data Source

<!--
<iframe width='800px' height='300px' scrolling=no frameborder='0' src="https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/pubhtml/sheet?headers=false&gid=1301528230"></iframe>
-->

[View](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo) on Google Docs or [(Download)](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/export)

## Data Format

EXCEL/TSV/GoogleDoc

[Top](#)


<a name="Humanset1"></a>

# 1. Genome Assembly (hg19)

## Description

Per chromosome FASTA file (Random contigs are not used for mapping or computing unique mappability)

## Data Source

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/referenceSequences/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/referenceSequences/)

## Data Format

FASTA


<a name="Humanset2"></a>

# 2. Raw Alignments

## Description

FASTQ and BAM files can be downloaded from the URL. Different labs used different mappers and mapping strategies. Hence, these files should be filtered to standardize them.

## Data Source

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeHaibTfbs/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeHaibTfbs/)

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/)

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeOpenChromChip/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeOpenChromChip/)

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeSydhTfbs/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeSydhTfbs/)

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeUchicagoTfbs/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeUchicagoTfbs/)

[http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeUwTfbs/](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeUwTfbs/)

## Data Format

BAM

[Top](#)


<a name="Humanset3"></a>

# 3. Unique Alignments

## Description

BAM files above are filtered to only keep unique mapping reads (tagAlign/ directory). Then duplicate reads were removed (only one read per position). These can be obtained in the distinctTagAlign/ directory"

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/alignments/distinctTagAlign/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/alignments/distinctTagAlign/)

## Data Format

TAGALIGN

[Top](#)


<a name="Humanset4"></a>

# 4. MetaData and Data Quality Metrics

## Description

Measures of enrichment, signal-to-noise ratios, library complexity and peak calling statistics.

## Data Source

[https://docs.google.com/spreadsheet/ccc?key=0Am6FxqAtrFDwdHdRcHNQUy03SjBoSVMxdUNyZV9Rdnc#gid=9](https://docs.google.com/spreadsheet/ccc?key=0Am6FxqAtrFDwdHdRcHNQUy03SjBoSVMxdUNyZV9Rdnc#gid=9)

## Data Format

EXCEL/TSV/GoogleDoc

[Top](#)


<a name="Humanset5"></a>

# 5. Blacklist Regions

## Description

The Blacklisted Regions aim to identify a comprehensive set of regions in the Fly genome that have anomalous, unstructured, high signal/read counts in next gen sequencing experiments independent of cell line and type of experiment. These regions tend to have a very high ratio of multi-mapping to unique mapping reads and high variance in mappability. Some of these regions overlap pathological repeat elements such as satellite, centromeric and telomeric repeats. However, simple mappability based filters do not account for most of these regions. Hence, it is recommended to use this blacklist alongside mappability filters. 

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/blacklist/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/blacklist/)

## Data Format

BED

[Top](#)


<a name="Humanset6"></a>

# 6. IDR Uniform Peak Calls

## Description

The SPP peak caller was used along with the IDR framework for calling peaks and thresholding based on reproducibility. IDR threshold of 0.02 was used. See https://sites.google.com/site/anshulkundaje/projects/idr for details"

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/uniformPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/uniformPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Humanset7"></a>

# 7. Blacklist Filtered Peak Calls

## Description

IDR Peak calls are filtered against blacklists. THESE ARE THE HUMAN PEAK CALLS FOR PRIMARY ANALYSIS.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/finalPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/finalPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Humanset8"></a>

# 8. Unthresholded Peak Calls

## Description

These are a large set of unthresholded peak calls (up to 300K peaks) from SPP. Useful for analyses that want to analyze low signal peaks.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/unthresholdPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/peakCalls/unthresholdPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Humanset9"></a>

# 9. Signal Tracks

## Description

Signal tracks are generated for each dataset using MACSv2's signal processing module. Signal tracks represent ChIP signal compared to input control signal.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/signal/foldChange/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/signal/foldChange/) 

## Data Format

BIGWIG

[Top](#)


<a name="Humanset10"></a>

# 10. Unique Mappability track

## Description

A position 'i' on a particular genomic strand 's' is considered uniquely mappable for a read-length 'k' if the k-mer starting at 'i' on strand 's' maps uniquely i.e. only to position 'i' on strand 's' (no mismatches allowed). There are other ways to define mappability e.g. allowing for mismatches but this is basically an ""optimistic"" idealized mappability mask not accounting for mismatches.

A whole genome index (except for the human female mask for which chrY was excluded from the index) is created and the Bowtie mapper was used to try to map each k-mer against both strands of the genome.

Each globalmap_k20tok54.tgz file contains binary files representing uniqueness maps for each chromosome for all read-lengths ranging from 20 to 54 (encoded in a single file for each chromosome)

(a) The files are in uint8 (unsigned 8 bit integers) binary formats (saves disk space)

(b) Each file is basically a vector of unsigned 8bit integers that is the length of the chromosome. The elements of the vector are >= 0 (taking values 0 or 20 to 54)

(c) A value of 'x' at a position means that position is PERFECTLY unique in the genome for all k-mers of length >= x starting at that position on the + strand

(d) A value of 0 at a position means that position is not unique for any of the k-mer lengths (k=20 to 54)

(e) In order to obtain the uniqueness map for a particular read-length 'k', simply perform the following operation on each element of the vector (vector > 0) & (vector <= k)

(f) In order to obtain the uniquness map for the - strand, you simply need to right-shift the vector by <k-1>. i.e. if position 1 is UNIQUE on the + strand for read-length <k=3> then it implies position 3 is UNIQUE on the - strand

How to read the files in a programming language such as matlab/octave

<pre>
%First gunzip and untar the globalmap_k20tok54.tgz file
%You will see one file for each chromosome e.g. chr1.uint8.unique
% Read the files as a contiguous binary vector of unsigned 8 bit integers

tmp_uMap = fopen('chr1.uint8.unique','r');
uMapdata = fread(tmp_uMap,'*uint8');
fclose(tmp_uMap);

% You can similarly read the files in any other programming language as a vector of unsigned 8bit 
integers. Convert to doubles if you like (although this is a waste of memory) 
or write it out as a text file if you prefer"
</pre>

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/mappability/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/mappability/)

## Data Format

BINARY

[Top](#)


<a name="Humanset11"></a>

# 11. TF Target Predictions

## Description

TIP algorithm for predicting TF target genes was applied to the input-normalized ChIP-seq tracks; these are the output files of that method.  Note that TIP was run on all CHIP-seq datasets, including those with score -1.  For most applications you should ignore those results, and treat the score=0 results cautiously.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/TFtargets/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/TFtargets/)

## Data Format

TIP

[Top](#)


<a name="Humanset12"></a>

# 12. HOT Regions

## Description

High-occupancy target (HOT) regions and extreme-occupancy target (XOT) regions from human (hs). HOT and XOT regions are called using the regulator-only peak sets (no polymerase datasets) for each organism, and using only datasets from the species contexts. HOT and XOT regions have higher density of binding than would be expected at a 5% significance threshold (HOT) or 1% significance threshold (XOT) based on 1000x simulations of clustered binding. Please note that the HOT regions include the XOT regions. Concordantly, ubiquitously HOT and ubiquitously XOT regions in each organism are defined as the regions that are HOT or XOT across all of the main contexts, respectively. 

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/hotRegions/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Human/hotRegions/)

## Data Format

BED

[Top](#)




<a name="Worm"></a>

# Worm

<a name="Wormset0"></a>

# 0. Dataset Reference

## Description

All Worm datasets were processed uniformly for the steps below. Here we provide a reference file to map all datasets to their
originating ENCODE Accession ID as well as appropriate metadata. 

Downloadable files in the sections below map to either a File Prefix or a modEncodeDCC Accession ID.

## Data Source

<!--
<iframe width='800px' height='300px' scrolling=no frameborder='0' src="https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/pubhtml/sheet?headers=false&gid=1833857626"></a></iframe>
-->

[View](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/pubhtml/sheet?headers=false&gid=1833857626) on Google Docs or [Download](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/export)

## Data Format

EXCEL/TSV/Google Docs

[Top](#)


<a name="Wormset1"></a>

# 1. Genome Assembly (ce10)

## Description

Per chromosome FASTA file (Random contigs are not used for mapping or computing unique mappability)

## Data Source

[http://hgdownload.cse.ucsc.edu/goldenPath/ce10/chromosomes/](http://hgdownload.cse.ucsc.edu/goldenPath/ce10/chromosomes/)

## Data Format

FASTA


<a name="Wormset2"></a>

# 2. Raw Alignments

## Description

FASTQ and BAM files can be downloaded from the URL. Different labs used different mappers and mapping strategies. Hence, these files should be filtered to standardize them.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/alignments/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/alignments/)

## Data Format

BAM

[Top](#)


<a name="Wormset3"></a>

# 3. Unique Alignments

## Description

BAM files above are filtered to only keep unique mapping reads (tagAlign/ directory). Then duplicate reads were removed (only one read per position). These can be obtained in the distinctTagAlign/ directory"

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/alignments/distinctTagAlign/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/alignments/distinctTagAlign/)

## Data Format

TAGALIGN

[Top](#)


<a name="Wormset4"></a>

# 4. MetaData and Data Quality Metrics

## Description

Measures of enrichment, signal-to-noise ratios, library complexity and peak calling statistics.

## Data Source

[https://docs.google.com/spreadsheet/ccc?key=0Algk3BSZDYzgdDlYNU00d2p3azJyZWlrZ09OQXNXTGc#gid=0](https://docs.google.com/spreadsheet/ccc?key=0Algk3BSZDYzgdDlYNU00d2p3azJyZWlrZ09OQXNXTGc#gid=0)

## Data Format

EXCEL/TSV/GoogleDoc

[Top](#)


<a name="Wormset5"></a>

# 5. Blacklist Regions

## Description

The Blacklisted Regions aim to identify a comprehensive set of regions in the Fly genome that have anomalous, unstructured, high signal/read counts in next gen sequencing experiments independent of cell line and type of experiment. These regions tend to have a very high ratio of multi-mapping to unique mapping reads and high variance in mappability. Some of these regions overlap pathological repeat elements such as satellite, centromeric and telomeric repeats. However, simple mappability based filters do not account for most of these regions. Hence, it is recommended to use this blacklist alongside mappability filters. 

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/blacklist/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/blacklist/)

## Data Format

BED

[Top](#)


<a name="Wormset6"></a>

# 6. IDR Uniform Peak Calls

## Description

The SPP peak caller was used along with the IDR framework for calling peaks and thresholding based on reproducibility. IDR threshold of 0.05 was used. chrM peaks were removed as these were unreliable in most cases. See https://sites.google.com/site/anshulkundaje/projects/idr for details

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/uniformPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/uniformPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Wormset7"></a>

# 7. Blacklist Filtered Peak Calls

## Description

IDR Peak calls are filtered against blacklists. THESE ARE THE WORM PEAK CALLS FOR PRIMARY ANALYSIS.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/finalPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/finalPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Wormset8"></a>

# 8. Unthresholded Peak Calls

## Description

These are a large set of unthresholded peak calls (up to 300K peaks) from SPP. Useful for analyses that want to analyze low signal peaks.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/unthresholdPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/peakCalls/unthresholdPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Wormset9"></a>

# 9. Signal Tracks

## Description

Signal tracks are generated for each dataset using MACSv2's signal processing module. Signal tracks represent ChIP signal compared to input control signal.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/signal/foldChange/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/signal/foldChange/) 

## Data Format

BIGWIG/BEDGRAPH

[Top](#)


<a name="Wormset10"></a>

# 10. Unique Mappability track

## Description

A position 'i' on a particular genomic strand 's' is considered uniquely mappable for a read-length 'k' if the k-mer starting at 'i' on strand 's' maps uniquely i.e. only to position 'i' on strand 's' (no mismatches allowed). There are other ways to define mappability e.g. allowing for mismatches but this is basically an ""optimistic"" idealized mappability mask not accounting for mismatches.

A whole genome index is created and the Bowtie mapper was used to try to map each k-mer against both strands of the genome.

Each globalmap_k20tok54.tgz file contains binary files representing uniqueness maps for each chromosome for all read-lengths ranging from 20 to 54 (encoded in a single file for each chromosome)

(a) The files are in uint8 (unsigned 8 bit integers) binary formats (saves disk space)

(b) Each file is basically a vector of unsigned 8bit integers that is the length of the chromosome. The elements of the vector are >= 0 (taking values 0 or 20 to 54)

(c) A value of 'x' at a position means that position is PERFECTLY unique in the genome for all k-mers of length >= x starting at that position on the + strand

(d) A value of 0 at a position means that position is not unique for any of the k-mer lengths (k=20 to 54)

(e) In order to obtain the uniqueness map for a particular read-length 'k', simply perform the following operation on each element of the vector (vector > 0) & (vector <= k)

(f) In order to obtain the uniquness map for the - strand, you simply need to right-shift the vector by <k-1>. i.e. if position 1 is UNIQUE on the + strand for read-length <k=3> then it implies position 3 is UNIQUE on the - strand

How to read the files in a programming language such as matlab/octave

<pre>
%First gunzip and untar the globalmap_k20tok54.tgz file
%You will see one file for each chromosome e.g. chr1.uint8.unique
% Read the files as a contiguous binary vector of unsigned 8 bit integers

tmp_uMap = fopen('chr1.uint8.unique','r');
uMapdata = fread(tmp_uMap,'*uint8');
fclose(tmp_uMap);

% You can similarly read the files in any other programming language as a vector of unsigned 8bit 
integers. Convert to doubles if you like (although this is a waste of memory) 
or write it out as a text file if you prefer"
</pre>

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/mappability/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/mappability/)

## Data Format

BINARY

[Top](#)


<a name="Wormset11"></a>

# 11. TF Target Predictions

## Description

TIP algorithm for predicting TF target genes was applied to the input-normalized ChIP-seq tracks; these are the output files of that method.  Note that TIP was run on all CHIP-seq datasets, including those with score -1.  For most applications you should ignore those results, and treat the score=0 results cautiously.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/TFtargets/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/TFtargets/)

## Data Format

TIP

[Top](#)


<a name="Wormset12"></a>

# 12. HOT Regions

## Description

High-occupancy target (HOT) regions and extreme-occupancy target (XOT) regions from worm (ce). HOT and XOT regions are called using the regulator-only peak sets (no polymerase datasets) for each organism, and using only datasets from the species contexts. HOT and XOT regions have higher density of binding than would be expected at a 5% significance threshold (HOT) or 1% significance threshold (XOT) based on 1000x simulations of clustered binding. Please note that the HOT regions include the XOT regions. Concordantly, ubiquitously HOT and ubiquitously XOT regions in each organism are defined as the regions that are HOT or XOT across all of the main contexts, respectively. 

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/hotRegions/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Worm/hotRegions/)

## Data Format

BED

[Top](#)




<a name="Fly"></a>

# Fly

<a name="Flyset0"></a>

# 0. Dataset Reference

## Description

All fly datasets were processed uniformly for the steps below. Here we provide a reference file to map all datasets to their
originating ENCODE Accession ID as well as appropriate metadata. 

Downloadable files in the sections below map to either a File Prefix or a modEncodeDCC Accession ID.

## Data Source

<!--
<iframe width='800px' height='300px' scrolling=no frameborder='0' src="https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/pubhtml/sheet?headers=false&gid=1581524421"></a></iframe>
-->

[View](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/pubhtml/sheet?headers=false&gid=1581524421) on Google Docs or [(Download)](https://docs.google.com/spreadsheets/d/1CLvyljx02arfj5CmWFwGuPwrXmlUCC2Us0ZV5rpVhjo/export)

## Data Format

EXCEL/TSV/GoogleDoc

[Top](#)


<a name="Flyset1"></a>

# 1. Genome Assembly (dm3)

## Description

Per chromosome FASTA file (Random contigs are not used for mapping or computing unique mappability)

## Data Source

[http://hgdownload.cse.ucsc.edu/goldenPath/dm3/chromosomes/](http://hgdownload.cse.ucsc.edu/goldenPath/dm3/chromosomes/)

## Data Format

FASTA


<a name="Flyset2"></a>

# 2. Raw Alignments

## Description

FASTQ and BAM files can be downloaded from the URL. Different labs used different mappers and mapping strategies. Hence, these files should be filtered to standardize them.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/alignments/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/alignments/)

## Data Format

BAM

[Top](#)


<a name="Flyset3"></a>

# 3. Unique Alignments

## Description

BAM files above are filtered to only keep unique mapping reads (tagAlign/ directory). Then duplicate reads were removed (only one read per position). These can be obtained in the distinctTagAlign/ directory"

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/alignments/distinctTagAlign/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/alignments/distinctTagAlign/)

## Data Format

TAGALIGN

[Top](#)


<a name="Flyset4"></a>

# 4. MetaData and Data Quality Metrics

## Description

Measures of enrichment, signal-to-noise ratios, library complexity and peak calling statistics.

## Data Source

[https://docs.google.com/spreadsheet/ccc?key=0Algk3BSZDYzgdDU3cXVVMHdQeHRTUWtnYk1aSG13NEE&pli=1#gid=6](https://docs.google.com/spreadsheet/ccc?key=0Algk3BSZDYzgdDU3cXVVMHdQeHRTUWtnYk1aSG13NEE&pli=1#gid=6)

## Data Format

EXCEL/TSV/GoogleDoc

[Top](#)


<a name="Flyset5"></a>

# 5. Blacklist Regions

## Description

The Blacklisted Regions aim to identify a comprehensive set of regions in the Fly genome that have anomalous, unstructured, high signal/read counts in next gen sequencing experiments independent of cell line and type of experiment. These regions tend to have a very high ratio of multi-mapping to unique mapping reads and high variance in mappability. Some of these regions overlap pathological repeat elements such as satellite, centromeric and telomeric repeats. However, simple mappability based filters do not account for most of these regions. Hence, it is recommended to use this blacklist alongside mappability filters. 

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/blacklist/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/blacklist/)

## Data Format

BED

[Top](#)


<a name="Flyset6"></a>

# 6. IDR Uniform Peak Calls

## Description

The MACSv2 peak caller was used along with the IDR framework for calling peaks and thresholding based on reproducibility. IDR threshold of 0.05 was used.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/uniformPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/uniformPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Flyset7"></a>

# 7. Blacklist Filtered Peak Calls

## Description

IDR Peak calls are filtered against blacklists. THESE ARE THE Fly PEAK CALLS FOR PRIMARY ANALYSIS.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/finalPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/finalPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Flyset8"></a>

# 8. Unthresholded Peak Calls

## Description

These are a large set of unthresholded peak calls using MACSv2. Useful for analyses that want to analyze low signal peaks.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/unthresholdPk/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/peakCalls/unthresholdPk/)

## Data Format

NARROWPEAK

[Top](#)


<a name="Flyset9"></a>

# 9. Signal Tracks

## Description

Signal tracks are generated for each dataset using MACSv2's signal processing module. Signal tracks represent ChIP signal compared to input control signal.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/signal/foldChange/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/signal/foldChange/) 

## Data Format

BIGWIG

[Top](#)


<a name="Flyset10"></a>

# 10. Unique Mappability track

## Description

A position 'i' on a particular genomic strand 's' is considered uniquely mappable for a read-length 'k' if the k-mer starting at 'i' on strand 's' maps uniquely i.e. only to position 'i' on strand 's' (no mismatches allowed). There are other ways to define mappability e.g. allowing for mismatches but this is basically an ""optimistic"" idealized mappability mask not accounting for mismatches.

A whole genome index is created and the Bowtie mapper was used to try to map each k-mer against both strands of the genome.

Each globalmap_k20tok54.tgz file contains binary files representing uniqueness maps for each chromosome for all read-lengths ranging from 20 to 54 (encoded in a single file for each chromosome)

(a) The files are in uint8 (unsigned 8 bit integers) binary formats (saves disk space)

(b) Each file is basically a vector of unsigned 8bit integers that is the length of the chromosome. The elements of the vector are >= 0 (taking values 0 or 20 to 54)

(c) A value of 'x' at a position means that position is PERFECTLY unique in the genome for all k-mers of length >= x starting at that position on the + strand

(d) A value of 0 at a position means that position is not unique for any of the k-mer lengths (k=20 to 54)

(e) In order to obtain the uniqueness map for a particular read-length 'k', simply perform the following operation on each element of the vector (vector > 0) & (vector <= k)

(f) In order to obtain the uniquness map for the - strand, you simply need to right-shift the vector by <k-1>. i.e. if position 1 is UNIQUE on the + strand for read-length <k=3> then it implies position 3 is UNIQUE on the - strand

How to read the files in a programming language such as matlab/octave

{% highlight matlab %}
%First gunzip and untar the globalmap_k20tok54.tgz file
%You will see one file for each chromosome e.g. chr1.uint8.unique
% Read the files as a contiguous binary vector of unsigned 8 bit integers

tmp_uMap = fopen('chr1.uint8.unique','r');
uMapdata = fread(tmp_uMap,'*uint8');
fclose(tmp_uMap);

% You can similarly read the files in any other programming language as a vector of unsigned 8bit 
integers. Convert to doubles if you like (although this is a waste of memory) 
or write it out as a text file if you prefer"
{% endhighlight %}

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/mappability/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/mappability/)

## Data Format

BINARY

[Top](#)


<a name="Flyset11"></a>

# 11. TF Target Predictions

## Description

TIP algorithm for predicting TF target genes was applied to the input-normalized ChIP-seq tracks; these are the output files of that method.  Note that TIP was run on all CHIP-seq datasets, including those with score -1.  For most applications you should ignore those results, and treat the score=0 results cautiously.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/TFtargets/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/TFtargets/)

## Data Format

TIP

[Top](#)


<a name="Flyset12"></a>

# 12. HOT Regions

## Description

High-occupancy target (HOT) regions and extreme-occupancy target (XOT) regions from Fly (dm). HOT and XOT regions are called using the regulator-only peak sets (no polymerase datasets) for each organism, and using only datasets from the species contexts. HOT and XOT regions have higher density of binding than would be expected at a 5% significance threshold (HOT) or 1% significance threshold (XOT) based on 1000x simulations of clustered binding. Please note that the HOT regions include the XOT regions. Concordantly, ubiquitously HOT and ubiquitously XOT regions in each organism are defined as the regions that are HOT or XOT across all of the main contexts, respectively.

## Data Source

[http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/hotRegions/](http://encodedcc.stanford.edu/ftp/modENCODE_VS_ENCODE/Regulation/Fly/hotRegions/)

## Data Format

BED

[Top](#)


