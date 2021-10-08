# Immune priming alters the microbial composition

The repository provides the scripts used in the analysis for the manuscript "Immune priming alters microbiome composition in the red flour beetle _Tribolium castaneum_."

The project details have been provided in the **Rmarkdown** document. In summary, the _Tribolium castaneum_ larvae were subjected to various routes of immune priming (oral and injection). Experiments were conducted using the two established routes of priming in this system: injection with heat-killed _Bacillus thurigiensis_ (Bt) and oral via ingestion of filtered sterilized bacterial spore supernatants by beetle larvae, with diverse strains of Bt varying in their ability to induce priming. Microbiota composition was assessed after the priming treatment by deep sequencing of the v1-v2 region of the bacterial 16S rRNA gene. 

The initial steps of the analysis including read quality trimming and filtering, ASV discovery and taxonomical assignment, phylogenetic allignment of ASVs , constructing ASVs phylogenetic Tree and removal of contaminant ASVs was performed using the **metagenome.Rmd** script. Following this, further analysis was performed using an online tool called **MicrobioAnalyst**. The inputs for MicrobiomeAnalyst tool is the output of the metagenome.Rmd script and are present in the folder microbiomeanalyst.

The sequencing files have been submitted to NCBI under the Bioproject ID:PRJNA765158 and will be made available post-publication.
