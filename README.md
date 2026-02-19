# 🧬 AMR-Watch
**Genomic surveillance of antimicrobial resistance in *Klebsiella pneumoniae***

A full bioinformatics pipeline: raw Illumina reads → QC → assembly → AMR gene detection → phylogenetics → publication figures.

## Pipeline Phases
- Phase 0: Environment setup & GitHub ✅
- Phase 1: Data acquisition from NCBI SRA 🔄
- Phase 2: Quality control & trimming
- Phase 3: De novo genome assembly
- Phase 4: AMR gene detection (CARD/RGI)
- Phase 5: Phylogenetic analysis
- Phase 6: Statistical visualization in R

## Tools
`sra-toolkit` `FastQC` `Trimmomatic` `SPAdes` `RGI` `MAFFT` `RAxML` `BioPython` `ggplot2`
