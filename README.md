# **Improved and Extended Multilocus Sequence Typing (MLST) Scheme for the *Streptomyces* reveals Complex Taxonomic Structure** 
**Angelika Kiepas, Prof Paul A Hoskisson, Dr Leighton Pritchard**

Strathclyde Insitute of Pharmacy and Biomedical Sciences, University of Strathclyde, 161 Cathedral Street, Glasgow G4 0RE, Scotland, UK
***


## **Overview**
Welecome to MLST_MicroSoc_2022 repository and thank you for expressing your interest in our reserach! :wave: :microscope: :woman_technologist: :man_technologist: :dna: :microscope: 


This is the repository where you can find supplementary data for poster presented at the Microbiology Society Annual Conference 2022. 

***
## **Interactive representations of minimum spanning trees**
All interactive graphs represent minimum spanning tree with 852 sequence types and 292 connected components describing all sequences *Streptomyces* genomes, and all sequence types from the pubMLST database. Each node represents a unique sequence type, and each edge corresponds to traversing from one sequence type to other by making up to five marker changes. This divison of *Streptomyces* into 292 components that share no marker alleles with each other implies a set of natural divisions between groups of isolates. 


- #### **pubMLST vs new *Streptomyces* sequence types**
The current canonical *Streptomyces* Multilocus Sequence Typing Scheme provided by [pubMLST](https://pubmlst.org) comprises six markers (16S rRNA, atpD, gyrB, recA, rpoB and trpB) and 236 sequence types. We extended the current scheme to include all avaliable **Streptomyces** genomes, identifying over 600 novel sequence types. To view how they map onto minimum spanning tree simply click [here](docs/MLSTIG_00003.html)!

- #### **Streptomyces** sequence type representation in GenBank
Despite 2276 genomes named as *Streptomyces* were downloaded from [NCBI](https://www.ncbi.nlm.nih.gov), 150 pubMLST sequences types were without a representative genome. You can check out how they are represented throughout our minimum spanning tree [here](docs/MLSTIG_00002.html)!

- #### **Unique genera according to pyANI analysis within each connected component**
Using [pyani](https://github.com/widdowquinn/pyani) we can determine whether genomes belong to the same candidate species or genus(%ID >≈95%, %coverage >≈50%), and examine their distributions on the minimum spanning tree that you can view [here](docs/MLSTIG_00005.html). Here we present that organisms assigned the same species name in [NCBI](https://www.ncbi.nlm.nih.gov):

1. May share <95% genome identity suggesting that the should be distinct species. 
2. Some genomes identified as the same species (>≈95% genome identity) with pyani](https://github.com/widdowquinn/pyani) are found in diconnected minimum spanning tree components. 
(pyANI [genome identity plot](docs/matrix_identity_rimosus.pdf) and [aligment coverage](docs/matrix_coverage_rimosus.pdf))
3. A single connected component unites two sets of genomes that belong to a distinct candidate genera as less than 50% of their genomes are homologous, by alignment length. 
(pyANI [genome identity plot](docs/matrix_identity_15_1.pdf) and [aligment coverage](docs/matrix_coverage_15_1.pdf))


***
If you have any questions please do not hesitate to contact me at <angelika.kiepas@strath.ac.uk>:envelope_with_arrow: :woman_technologist:. 
