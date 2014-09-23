---
layout: page
order: 3
title: Transcriptome
permalink: /transcriptome/
subproject: true
teaser: /assets/images/transcription.png
abstract: The transcriptome is the readout of the genome. Identifying common features in it across distant species can reveal fundamental principles. To this end, the ENCODE and modENCODE consortia have generated large amounts of matched RNA-sequencing data for human, worm and fly. Uniform processing and comprehensive annotation of these data allow comparison across metazoan phyla, extending beyond earlier within-phylum transcriptome comparisons and revealing ancient, conserved features. Specifically, we discovered co-expression modules shared across animals, many of which are enriched in developmental genes. We used expression patterns to align the stages in worm and fly development, finding a novel pairing between worm embryo and fly pupae, in addition to the expected embryo-to-embryo and larvae-to-larvae pairings. Furthermore, we found that the extent of non-canonical, non-coding transcription is similar in each organism, per base-pair. Finally, we found in all three organisms the gene-expression levels, both coding and noncoding, can be quantitatively predicted from chromatin features at the promoter using a “universal model," based on a single set of organism-independent parameters.

paper:
  title: Comparative analysis of the transcriptome across distant species

  authors: Gerstein MB, Rozowsky J, Yan K, Wang D, Cheng C, Brown JB, Davis CA, Hillier L, Sisu C, Li JJ, Pei B, Harmanci AO, Duff MO, Djebali S, Alexander RP, Alver BH, Auerbach RK, Bell K, Bickel PJ, Boeck ME, Boley NP, Booth BW, Cherbas L, Cherbas P, Di C, Dobin A, Drenkow J, Ewing B, Fang G, Fastuca M, Feingold EA, Frankish A, Gao G, Good PJ, Green P, Guigó R, Hammonds A, Harrow J, Hoskins RA, Howald C, Hu L, Huang H, Hubbard TJP, Huynh C, Jha S, Kasper D, Kato M, Kaufman TC, Kitchen RR, Ladewig E, Lagarde J, Lai E, Leng J, Lu Z, MacCoss M, May G, McWhirter R, Merrihew G, Miller DM, Mortazavi A, Murad R, Oliver B, Olson S, Park PJ, Pazin MJ, Perrimon N, Pervouchine D, Reinke V, Reymond A, Robinson G, Samsonova A, Saunders GI, Schlesinger F, Sethi A, Slack FJ, Spencer WC, Stoiber MH, Strasbourger P, Tanzer A, Thompson OA, Wan KH, Wang G, Wang H, Watkins KL, Wen J, Wen K, Xue C, Yang L, Yip K, Zaleski C, Zhang Y, Zheng H, Brenner SE, Graveley BR, Celniker SE, Gingeras TR, and Waterston R 

  authors_short: Gerstein et al.

  meta: Nature 512:445–448, 2014

  url: http://www.nature.com/nature/journal/v512/n7515/full/nature13424.html
---
    
_Additional details on data generation and analysis can be found in the [paper supplement](http://cmptxn.gersteinlab.org/rawdata/submit/Gerstein_CmpTxn_Supplement.pdf)._

# 1. Protein-Coding Gene Annotation

## Description

The human, worm and fly protein-coding gene annotation are from GENCODE 10, extensions of WormBase WS220 and FlyBase 5.45, respectively.

## Data Source

*   Human protein-coding gene annotation, in gtf format, from GENCODE v10: [gen10_CDS+exons_only_protein-coding_only.gtf.gz](http://cmptxn.gersteinlab.org/Comparative_Datasets.xlsx)
*   Worm protein-coding gene annotation, in gtf format, from modENCODE June 2012 freeze: [AG1201.integrated_transcripts_strictly_coding.ws220.gtf.gz](http://cmptxn.gersteinlab.org/AG1201.integrated_transcripts_strictly_coding.ws220.gtf.gz)
*   Fly protein-coding gene annotation, in gtf format, from modENCODE June 2012 freeze: [coding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz](http://cmptxn.gersteinlab.org/coding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz)

# 2. Fly Strict Non-coding Gene

## Description

The fly non-coding gene annotation is developed beyond FlyBase 5.45.

## Data Source

*   Fly strict non-coding annotation, in gtf format, from modENCODE June 2012 freeze: [strict_noncoding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz](http://cmptxn.gersteinlab.org/strict_noncoding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz)

# 3. Comparable and Non-comparable Non-coding RNA Annotations

## Description

The compressed GTF files for non-coding RNA gene annotations. For each species, there is one compressed file that contains the comparable (miRNA, tRNA, snoRNA, snRNA, pri-miRNA) and one of non-comparable (between organism) ncRNA annotations. The comparable annotations are further separated into the biotypes.

## Data Source

*   Human comparable ncRNA, in gtf format: [human_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/human_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Human non-comparable ncRNA, in gtf format: [human_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/human_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Worm comparable ncRNA, in gtf format: [worm_consensus_ncRNAs_03_23_2013.gtf.tar.bz2 ](http://cmptxn.gersteinlab.org/worm_consensus_ncRNAs_03_23_2013.gtf.tar.bz2 )
*   Worm non-comparable ncRNA, in gtf format: [worm_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/worm_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Fly comparable ncRNA, in gtf format: [fly_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/fly_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Fly non-comparable ncRNA, in gtf format: [fly_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/fly_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)

# 4. Human-Worm-Fly Ortholog Lists

## Description

We have compiled a complete list of ~28k triplets of orthologous genes among human, worm and fly (6353 unique genes in human, 5083 unique genes in worm, 4839 unique genes in fly). The list was merged from the MIT list and Ensembl. It contains all one to one, one to many and many to many orthologous relationships.

## Data Source

*   MIT Human-Worm-Fly Orthologs: [Modencode.merged.orth20120611_wfh_comm_all.csv](http://cmptxn.gersteinlab.org/Modencode.merged.orth20120611_wfh_comm_all.csv)

# 5. Table Summarizing Processed Expression Values for all Annotated Genes

## Description

These tables provide a summary of all annotations with processed expression values associated to protein coding genes in human, worm, and fly. These tables also include TF prediction power, orthology etc. Details of the values and features are provided in the excel sheet headers.

## Data Source

*   Human coding gene details, in Excel format: [human_gene.xlsx](http://cmptxn.gersteinlab.org/human_gene.xlsx)
*   Worm coding gene details, in Excel format: [worm_gene.xlsx](http://cmptxn.gersteinlab.org/worm_gene.xlsx)
*   Fly coding gene details, in Excel format: [fly_gene.xlsx](http://cmptxn.gersteinlab.org/fly_gene.xlsx)

# 6. Transcriptionally Active Regions (TARs)

## Description

TARs refer to the non-canonical transcription in the regions excluding protein-coding exons, annotated ncRNAs and pseudogenes. Listed below are all the TARs locations with 90% and 98% exon discovery rate thresholds in the genome of each species, using the chromosome, start and stop. Details of TAR calling are in supplement.

## Data Source

*   TARs in human at 90% threshold, in bed format: [human_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/human_exon_disc_90_tars.bed)
*   TARs in human at 98% threshold, in bed format: [human_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/human_exon_disc_98_tars.bed)
*   TARs in worm  at 90% threshold, in bed format: [worm_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/worm_exon_disc_90_tars.bed)
*   TARs in worm at 98% threshold, in bed format: [worm_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/worm_exon_disc_98_tars.bed)
*   TARs in fly at 90% threshold, in bed format: [fly_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/fly_exon_disc_90_tars.bed)
*   TARs in fly at 98% threshold, in bed format: [fly_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/fly_exon_disc_98_tars.bed)

# 7. Enhancers

## Description

Human enhancers are from Yip et al. "Classification of genomic regions based on experimentally-determined binding sites of more than 100 transcription-related factors in the whole human genome". Genome Biol 13: R48.  Worm and fly enhancers are identified using enhancer specific histone marks, see Ho et al. 2014.

## Data Source

*   Human enhancers used for TAR analysis: [Enhancers](http://encodenets.gersteinlab.org/metatracks/)
*   Worm and fly enhancers used for TAR analysis: [Enhancers](http://encodedcc.sdsc.edu/ftp/users/akundaje/enhancers/)
*   Alternative human enhancers: [Enhancers](http://encodedcc.sdsc.edu/ftp/users/akundaje/enhancers/)

# 8. Clustering of ncRNAs and TARs with Co-expression Modules

## Description

For each species, we mapped the ncRNAs and TARs to modules based on co-expression correlations, and found those highly mapped ncRNAs may have related functions with modular genes so that we can annotate them based on modular functions.

## Data Source

*   incRNAs and TARs associated with the 16 modules in three species, tarball of txt files: [16_module_ncRNA.tar.gz](http://cmptxn.gersteinlab.org/16_module_ncRNA.tar.gz)

# 9. Supervised ncRNA predictions (novel ncRNA fragments)

## Description

We applied the machine learning method, incRNA (Lu et al. "Prediction and characterization of noncoding RNAs in C. elegans by integrating conservation, secondary structure, and high-throughput sequencing and array data". Genome Res. 21:245-54) to predict ncRNAs in the genomes of human, worm and fly.

## Data Source

*   Human supervised ncRNA predictions Feb 6 , 2013, in bed format: [hg_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/hg_incRNA_tar98_intersection_50_6Feb13.bed)
*   Worm supervised ncRNA predictions Feb 6 , 2013, in bed format: [ce_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/ce_incRNA_tar98_intersection_50_6Feb13.bed)
*   Fly supervised ncRNA predictions Feb 6 , 2013, in bed format: [dm_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/dm_incRNA_tar98_intersection_50_6Feb13.bed)

# 10. Gene Co-expression Modules

## Description

We built co-expression modules by combining across-species orthology and within-species co-expression relationships between protein coding genes. In the resulting multilayer network we searched for dense subgraphs, using simulated annealing. We used the Orthoclust methodology, see Yan et al. Genome Biol. (2014) 15:R100. To focus on the cross-species conserved functions, we restricted the clustering to orthologs, arriving at 16 conserved modules, which are enriched in a variety of functions, ranging from morphogenesis to chromatin remodeling.

## Data source

*   16 human, worm and fly co-expressed and co-evolved modules showing highly coordinated expression patterns only during phylotypic stage, tarball of csv files: [16_module.tar.gz](http://cmptxn.gersteinlab.org/16_module.tar.gz)
*   Gene names in 16 conserved modules: [genelist_16modules.xlsx](http://cmptxn.gersteinlab.org/genelist_16modules.xlsx)
*   Enriched Gene Ontology terms on biological process in 16 conserved modules: [GO_16modules_biological_process.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_biological_process.xlsx)
*   Enriched Gene Ontology terms on cellular component in 16 conserved modules: [GO_16modules_cellular_component.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_cellular_component.xlsx)
*   Enriched Gene Ontology terms on molecular function in 16 conserved modules: [GO_16modules_molecular_function.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_molecular_function.xlsx)

# 11. Developmental Stage Mapping between Worm and Fly

## Description

We used expression patterns to align the stages in the worm and fly development, finding a novel pairing between the worm embryo and fly pupa stages, in addition to the expected embryo-to-embryo and larvae-to-larvae pairings.  See Li et al., Genome Res. (2014) 24:1086-101. for more details.

## Data Source

*   Embryonic specific worm genes aligned with fly genes in both embryo stage and pupae stage: [wf_dual_mapping.xls](http://cmptxn.gersteinlab.org/wf_dual_mapping.xls)

# 12. Raw Data for the "Comparative Analysis of the Transcriptome across Distant Species"

## Description

Description of all datasets in different formats, and links to raw data (reads).

## Data Source

*   Descriptions of all raw datasets are available in a [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1IcgCLVUuXPzkTxUXLU0c2hB4qevQResFcs1TER_yGjw/edit?usp=sharing), or can be [downloaded here](http://cmptxn.gersteinlab.org/rawdata/Comparative_Datasets_with_Links.xlsx) as an Excel spreadsheet.
*   The raw data links alone can also be accessed by  [clicking here](http://cmptxn.gersteinlab.org/rawdata/comparative_tables.html).
