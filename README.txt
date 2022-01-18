SCTLD Intervention Methods Comparison
Erin Shilling, eshilling15@gmail.com
version: January 18, 2022

This repository contains scripts and data associated with the publication:
Shilling EN, Combs IR, Voss JD. 2021. Assessing the effectiveness of two intervention methods for stony coral tissue loss disease on Montastraea cavernosa. Scientific Reports 11, 856 doi.org/10.1038/s41598-021-86926-4
Stony coral tissue loss disease (SCTLD) was first observed in Florida in 2014 and has since spread to multiple coral reefs across the wider Caribbean. The northern section of Florida’s Coral Reef has been heavily impacted by this outbreak, with some reefs experiencing as much as a 60% loss of living coral tissue area. We experimentally assessed the effectiveness of two intervention treatments on SCTLD-affected Montastraea cavernosa colonies in situ. Colonies were tagged and divided into three treatment groups: (1) chlorinated epoxy, (2) amoxicillin combined with CoreRx/Ocean Alchemists Base 2B, and (3) untreated controls. The experimental colonies were monitored periodically over 11 months to assess treatment effectiveness by tracking lesion development and overall disease status. The Base 2B plus amoxicillin treatment had a 95% success rate at healing individual disease lesions but did not necessarily prevent treated colonies from developing new lesions over time. Chlorinated epoxy treatments were not significantly different from untreated control colonies, suggesting that chlorinated epoxy treatments are an ineffective intervention technique for SCTLD. The results of this experiment expand management options during coral disease outbreaks and contribute to overall knowledge regarding coral health and disease. 

3D model protocol adapted from Young et al. 2017.

Protocols and walkthroughs accompanying this manuscript:
1. Protocol for intervention treatment methods and 3D model generation and analysis
2. Statistical analysis of SCTLD intervention experiment outcomes

Repository contents:
* figures/
o Fig1.eps -- Diagramatic representation of sampling depths (.eps)
o Fig1.png -- Diagramatic representation of sampling depths (.png)
o Fig2.eps -- Map of sampling sites (.eps)
o Fig2.png -- Map of sampling sites (.png)
o Fig3.eps -- Barplot of ITS2 sequences
o Fig4.eps -- Barplot of ITS2 type profiles
o Fig5.eps -- nMDS plots of ITS2 sequences and ITS2 type profiles
* lab_protocol/
o barcodeMM.csv -- Barcoding PCR mastermix recipe
o bcPCR.csv -- Barcoding PCR profile
o bcPrimers.csv -- Barcoding PCR primer sequence example
o ctab.csv -- CTAB extraction buffer recipe
o etbrGel.csv -- Ethidium bromide gel recipe
o index.html -- Symbiodiniaceae lab prorocol webpage
o its2MM.csv -- Symbiodiniaceae ITS2 mastermix recipe
o its2PCR.csv -- Symbiodiniaceae ITS2 PCR profile
o its2Primers.csv -- Symbiodiniaceae specific ITS2 primer sequences
o reagents.csv -- Reagent stock recipes
o supplies.csv -- Supplies for CTAB extraction
o sybrGel.csv -- SYBR gel recipe
* scripts/
o sampleRename.py -- rename files based on a .csv table
* stats/
o 62_20190310_DBV_2019-03-11_01-11-25.167036.profiles.absolute.clean.txt -- SymPortal ITS2 type profile absolute abundance output file cleaned for importing into R
o 62_20190310_DBV_2019-03-11_01-11-25.167036.profiles.absolute.txt -- SymPortal ITS2 type profile absolute abundance output file
o 62_20190310_DBV_2019-03-11_01-11-25.167036.profiles.relative.txt -- SymPortal ITS2 type profile relative abundance output file
o 62_20190310_DBV_2019-03-11_01-11-25.167036.seqs.absolute.clean.txt -- SymPortal ITS2 sequence absolute abundance output file cleaned for importing into R
o 62_20190310_DBV_2019-03-11_01-11-25.167036.seqs.absolute.txt -- SymPortal ITS2 sequence absolute abundance output file
o 62_20190310_DBV_2019-03-11_01-11-25.167036.seqs.relative.txt -- SymPortal ITS2 sequence relative abundance output file
o CBC_MCAV_sampling_metadata.txt -- M. cavernosa sample metadata
o Symbiodiniaceae_ITS2_statistical_analyses.Rmd -- Symbiodiniaceae statistical analysis Rmarkdown document
o index.html -- Symbiodiniaceae statistical analysis webpage
o its2Primer.pwk -- PRIMER7 workbook
o stats.Rproj -- R project file
* .gitignore -- .gitignore file
* CBC_MCAV_Symbiodiniaceae_ITS2_metadata.xlsx -- M. cavernosa sample and library prep metadata
* README.md -- Repository readme document
* Symbiodiniaceae_ITS2_primers_PCR.xlsx -- Symbiodiniaceae ITS2 and barcoding primer sequences and PCR profiles

