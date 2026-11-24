# umash_personal_bioaerosol_microbiome
Code repository for the paper "The personal bioaerosol microbiome in swine farms: Particle-size-resolved characterization and comparison of two wearable sampling devices"
# General Information
1. Project: The influence of on-farm exposures and biosecurity practices on the skin and nasal microbiomes of U.S. swine workers (part of UMASH)
2. Grant: CDC NAT'L INST FOR OCCUP SAFETY & HEALTH (Sponsor Award: 5 U54OH010170-12-00; Award Title: Upper Midwest Agricultural Safety and Health Center)
3. Samples: Personal bioaerosol particles (breathing area)
4. Sequencing method: full length (V1-V9) 16S rRNA gene sequencing (ONT, r10.4.1 flowcell, SQK-16S114.24 kit)
5. Date: 2024 - 2026
6. Author: Gerardo R. Diaz (diazo005@umn.edu)
7. Description: This dry lab bitacora contains the code and processes followed during the bionformatic analysis, data processing, statistical analysis and data visualization of the paper "The personal bioaerosol microbiome in swine farms: Particle-size-resolved characterization and comparison of two wearable sampling devices". Do not hesitate to contact the first author (diazo005@umn.edu) or corresponding author (nnoyes@umn.edu) with further questions, issues or suggestions about this repository.
# Contains
1. AC_vs_NIOSH_16S_ONT_bioinformatics.txt: txt file with the steps for the bioinformatic analysis of the full-length 16S ONT reads. It contains genus-level taxonomic classification (Epi2me wf-16S), sup-model basecalling (dorado), QC plot and reports (Nanoplot & MultiQC), quality- and length-based filtering (Chopper), and species-level taxonomic classification (emu).
2. AC_vs_NIOSH_Ranalysis.md: Markdown file used for the microbiome and statistical analysis, and plot generation in R. Remember to change file extension "md" to "Rmd" before using it in R.
# WARNING
Check software versions, paths and dependencies because they constantly change. Keep in mind that this code was adapted for my particular needs. If you need help with it please email me diazo005@umn.edu. Welcome!
