# Fusobacterium
Material for research on virulence Fusobacterium necrophorum

In this repo you can find the definition files of the wgMLST scheme created for the genus Fusobacterium. The file wgmlst_adb_AM_fusobacterium_v2_confirmed.fasta.gz contains all reference alleles and can be used to build a blast database to detect the loci in Fusobacterium genomes.
The folder AcceptedAlleles contains files with all the accepted alleles, containing start and stop codon, no internal stop, and no further than 75% from reference allele.
The folder Vir_Fuso contains a fasta with structure headers with all virulence genes extracted based on the annotation from the public assemblies of Fusobacterium genomes. The complete folder can be used as knowledgebase in the custom genotyping plugin of BioNumerics.
