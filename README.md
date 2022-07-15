# metabarcoding
Includes:
- A primer tag set suitable for plant (p6-loop) and animal (16S P007) metabarcoding 
- The sequences for six synthetic standards compatible with plant p6-loop metabarcoding experiments
- A blacklist of human and human-like sequences derived from multiple animal (16S P007) metabarcoding experiments

Notes:
- The p6-loop is a short locus in the chloroplast genome of plants, and, for vascular plants, is amplified by the trnL gh primers (Taberlet et al. 2007: https://doi.org/10.1093/nar/gkl938)
- '16S P007' is a short locus in the mitochonidral genome of animals that is amplified by the 16S P007 primers (Giguet-Covex et al. 2014: https://doi.org/10.1038/ncomms4211)

**Tromsø_p6-loop_primer_tags.txt**:
A list of 384 eight or nine base pair tags suitable for p6-loop and 16S P007 metabarcoding. The same tag is added to the 5' end of the forward and reverse primers to allow for unique dual tagging of amplicons. These tags are modified from those presented by Taberlet et al. (2018: https://doi.org/10.1093/oso/9780198767220.001.0001, p217; also listed here: https://www.oxfordscholarship.com/view/10.1093/oso/9780198767220.001.0001/oso-9780198767220-appendix-2)

**Human_16S_sequences_PDH_v2.1_20220708.tsv**:
A list of human and human-like 16S P007 sequences that can be used in a blacklist setup. First column is the sequence, second column is identity to sequences in EMBL r143, and remaining columns are taxonomic information derived from ObiTools.
