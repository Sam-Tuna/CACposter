# Things that didn't fit in the poster:

## N. gardneri sequencing and assembly
### Illumina data
Sequencing was performed by Macrogen (South Korea).
Read QC was done using TrimGalore v.0.6.1 (https://github.com/FelixKrueger/TrimGalore)

### Nanopore data
Library preparation was done with the Ligation Sequencing kit (https://store.nanoporetech.com/ligation-sequencing-kit-v14.html). Sequencing was performed on an R10.4 flow cell, and dorado was used for basecalling, with the sup v.5.0.0 model.

Read QC was done using Chopper v.0.10 (De Coster and Rademakers, 2023, https://github.com/wdecoster/chopper). 

### Hybrid assembly

Hybrid assembly was done with MaSuRCA v.4.1.4 (Zimin et al., 2013, https://github.com/alekseyzimin/masurca).

#### Annotation software

RepeatModeler v.2.0.7 (https://github.com/Dfam-consortium/RepeatModeler)

RepeatMasker v.4.1.5 (https://github.com/Dfam-consortium/RepeatMasker)

Genemar-ES v.73_lic (https://gatech-genemark.github.io/GeneMark-E-Docs/#/)

EggNOG-mapper v.4.1.15, with the eggNOG database v.5.0 (https://github.com/eggnogdb/eggnog-mapper), 

## Public assemblies used

A. mexicana: https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_052426525.1/

M. crocata: https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_029281795.1/


## References

Aleksey V. Zimin, Guillaume Marçais, Daniela Puiu, Michael Roberts, Steven L. Salzberg, James A. Yorke, The MaSuRCA genome assembler, Bioinformatics, Volume 29, Issue 21, November 2013, Pages 2669–2677, https://doi.org/10.1093/bioinformatics/btt476

Wouter De Coster, Rosa Rademakers, NanoPack2: population-scale evaluation of long-read sequencing data, Bioinformatics, Volume 39, Issue 5, May 2023, btad311, https://doi.org/10.1093/bioinformatics/btad311

Elías-Román, R. D., Medel-Ortiz, R., Alvarado-Rosales, D., Hanna, J. W., Ross-Davis, A. L., Kim, M. S., & Klopfenstein, N. B. (2018). Armillaria mexicana, a newly described species from Mexico. Mycologia, 110(2), 347–360. https://doi.org/10.1080/00275514.2017.1419031

Igor V. Grigoriev, Roman Nikitin, Sajeet Haridas, Alan Kuo, Robin Ohm, Robert Otillar, Robert Riley, Asaf Salamov, Xueling Zhao, Frank Korzeniewski, Tatyana Smirnova, Henrik Nordberg, Inna Dubchak, Igor Shabalov, MycoCosm portal: gearing up for 1000 fungal genomes, Nucleic Acids Research, Volume 42, Issue D1, 1 January 2014, Pages D699–D704, https://doi.org/10.1093/nar/gkt1183

Jane E Stewart, Mee-Sook Kim, Jorge R Ibarra Caballero, Patrick I Bennett, John W Hanna, Rubén D Elías-Román, Ned B Klopfenstein, High-Quality Draft Genome for Armillaria mexicana, a Recently Described Species in North America, Genome Biology and Evolution, Volume 17, Issue 10, October 2025, evaf185, https://doi.org/10.1093/gbe/evaf185

Renate Heinzelmann, Heidy Baggenstos, Andreas Rudolf, Is the bioluminescence in many Mycena species overlooked? ― A case study from M. crocata in Switzerland, Mycoscience, 2024, 65 巻, 4 号, p. 173-179, 公開日 2024/07/20, [早期公開] 公開日 2024/05/13, Online ISSN 1618-2545, Print ISSN 1340-3540, https://doi.org/10.47371/mycosci.2024.03.001, https://www.jstage.jst.go.jp/article/mycosci/65/4/65_MYC633/_article/-char/ja, 
