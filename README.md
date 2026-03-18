# GIMs
GIM coverage and abundances in bacterial genomes and metagenomics datasets were derived from UniRef90 gene abundance (copy number) using customized script adapted from HUMAnN. Specifically, “humann_ regroup_table -c GIM3_reaction.tsv” were used to calculate reaction abundance from UniRef90 gene abundance (copy number), and then “humann --pathways-database GIM3_pathways.tsv” were used to calculate pathway abundance and coverage from reaction abundance.

if you have any problem related to this framework, please contact gaojie: 994856235@qq.com
