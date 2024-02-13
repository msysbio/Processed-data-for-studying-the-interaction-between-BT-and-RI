# Processed data for "Starvation response strategies impact the interaction dynamics of human gut bacteria: a study of Bacteroides thetaiotaomicron and Roseburia intestinalis"

Here we deposit the processed RNA-seq, flow cytometry and fermentation data of exploring the impact of nutrient scarcity on the interaction dynamics of two common human gut bacteria, Bacteroides thetaiotaomicron (BT) and Roseburia intestinalis (RI).

For the processed RNA-seq data, we included a total of 69 samples representing the different growth phases of BTt/RI in three biological replicates for RNA sequencing, which were selected from the following six independent experiments: monoculture BT in WC medium (4 h, 12 h and 36 h), monoculture RI in WC (4 h, 12 h and 48 h), coculture BT and RI in WC (12 h , 24 h and 36 h), monoculture BT in WC plus mucin beads (4 h, 12 h, 24 h, 48 h and 120 h), monoculture RI in WC plus mucin beads (16 h, 28 h, 40 h and 48 h), and coculture BT and RI in WC plus mucin beads (6 h, 12 h, 24 h, 48 h and 120 h). Total RNA was extracted and purified from RNAprotect-treated (Qiagen, Hilden, Germany) frozen samples using the phenol-free RNeasy Plus Mini Kit (Qiagen) according to the instructions of the manufacturer. All samples were prepared using the NEBNext Ultra II Directional RNA Library Prep Kit for Illumina (New England BioLabs, #E7760L). The libraries were sequenced on a NovaSeq 6000 (Illumina, San Diego, CA, USA) on a v1.5 S4_300 kit in XP mode. 

The analysis of the raw sequencing reads was performed as follows: low quality reads and adapters were trimmed with fastp. High quality RNA reads were mapped to their respective reference transcripts with Salmon run in a selective alignment mode and with a decoy-aware index constructed from each organism’s genome. The latest reference genomes and transcripts for BT and RI were downloaded from the ensemble bacteria and BV-BRC databases, respectively: GCA_000011065.ASM1106v1.dna.toplevel.fa (B.thetaiotaomicron VPI-5482), GCA_000011065.ASM1106v1.cds.all.fa (B. thetaiotaomicron VPI-5482), GCA_900537995.1_Roseburia_intestinalis_strain_L1-82_genomic.fna (R. intestinalis L1-82), GCA_900537995.1_Roseburia_intestinalis_strain_L1-82_cds_from_genomic.fna (R. intestinalis L1-82). Raw transcript counts were extracted from salmon’s output and used for differential gene expression analysis. COG categories, COG numbers and KO numbers were extracted from NCBI COG and KEGG database for BT. To obtain annotations for RI, we mapped the respective transcripts to the eggnog database v.5 with the eggnog mapper 2.1.9.

Fermentation data were obtained from 120ml serum bottles and microtiter plates, as described in details in the manuscript (preprint): https://www.biorxiv.org/content/10.1101/2023.02.02.526806v1

Now published in ISME: https://www.nature.com/articles/s41396-023-01501-1
