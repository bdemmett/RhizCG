RhizCG
======

This repo contains the bioinformatics pipeline and scripts for data analysis and figure generation presented in the manuscript Emmett *et al*. 2017. 'Plant phylogeny and life history shape rhizosphere microbiome' *submitted*


Sequence analysis pipeline
-------

From raw reads to OTU table and phylogenetic tree see ipnyb/MiSeqRuns_2015

1. Read merge individual runs with PEAR
2. De-multiplex individual runs
3. Quality control and filtering
4. Merge individual fastaQC files
5. Cluster OTUs
6. Generate tree with Fastree
* bootstrap tree generation for use in consenTrait.R


Data analysis
------
7. Create phyloseq objects from OTU table and tree
* filter extremely low abundance OTUs and rarify

Scripts are located in the 
