[[Poolman_et+al_MetabolicTradeoffsBetweenBiomassSynthesis_2014]]

# [Metabolic trade-offs between biomass synthesis and photosynthate export at different light intensities in a genomeâ€“scale metabolic model of rice](https://dx.doi.org/10.3389/fpls.2014.00656)

## [[Mark G. Poolman]]; [[Sudip Kundu]]; [[Rahul Shaw]] et al.

### 2014

## Abstract
Previously we have used a genome scale model of rice metabolism to describe how metabolism reconfigures at different light intensities in an expanding leaf of rice. Although this established that the metabolism of the leaf was adequately represented, in the model, the scenario was not that of the typical function of the leaf—to provide material for the rest of the plant. Here we extend our analysis to explore the transition to a source leaf as export of photosynthate increases at the expense of making leaf biomass precursors, again as a function of light intensity. ==In particular we investigate whether, when the leaf is making a smaller range of compounds for export to the phloem, the same changes occur in the interactions between mitochondrial and chloroplast metabolism as seen in biomass synthesis for growth when light intensity increases==. ==Our results show that the same changes occur qualitatively, though there are slight quantitative differences reflecting differences in the energy and redox requirements for the different metabolic outputs==.

## Key concepts
#claim/metabolism; #claim/rice; #claim/synthesis; #flux_balance_analysis; #result/metabolic_network; #photosynthesis; #arabidopsis; #scale_model; #objective_function

## Quote
> Our results have shown that the occurrence of transitions in the flux solutions for our rice leaf cell metabolism model at different light intensities are not peculiar to the production of a specific metabolic output, but are relatively insensitive to the nature of the output


## Key points
- Genome–scale metabolic modeling (GSM) is a technique for investigating the feasible metabolic states of an organism, taking account of the possibilities and constraints imposed by the structure of the metabolic network
- The principal constraint is that of mass balance, dictated by the stoichiometries of the reactions in the network, coupled with the assumption of a metabolic steady state where the production and consumption of all internal metabolites of the network is balanced so that their concentrations remain constant. This defines a space containing all feasible states of the metabolism, from which more specific solutions are extracted with a combination of additional constraints, such as experimentally-observed values of nutrient uptake and growth rates, with an objective function that is intended to define an optimal state of the metabolism
- Our results have shown that the occurrence of transitions in the flux solutions for our rice leaf cell metabolism model at different light intensities are not peculiar to the production of a specific metabolic output, but are relatively insensitive to the nature of the output
- Part of that difference comes from the known difference in redox state between the two mixtures, reflected in the Assimilatory Quotient values. Another component is in the amount of ATP required for synthesis, and we do not know this value with any certainty
- The small difference in the minimum light input required in the two cases is of no significance compared to the light needed to satisfy the cell’s maintenance ATP needs, which itself is a very uncertain figure, though the value we have used results in a minimum www.frontiersin.org quantum demand figure that is in the range of experimental measurements

## Synopsis

### Introduction
Genome–scale metabolic modeling (GSM) is a technique for investigating the feasible metabolic states of an organism, taking account of the possibilities and constraints imposed by the structure of the metabolic network.
The principal constraint is that of mass balance, dictated by the stoichiometries of the reactions in the network, coupled with the assumption of a metabolic steady state where the production and consumption of all internal metabolites of the network is balanced so that their concentrations remain constant.
This defines a space containing all feasible states of the metabolism, from which more specific solutions are extracted with a combination of additional constraints, such as experimentally-observed values of nutrient uptake and growth rates, with an objective function that is intended to define an optimal state of the metabolism.
The models are solved using linear programming, and associated techniques that are part of the methodology known as Flux Balance Analysis (FBA), to give a predicted distribution of fluxes in the metabolic network

### Methods
The model of rice metabolism of a rice mesophyll cell used in this study is that the authors reported previously ([^Poolman_et+al_2013_a]) and is available in the supplementary data to that paper.
It was based on the genome annotation recorded in the“RiceCyc” database, version 2.01, downloaded from http://www.gramene.
All computation was achieved using the software package ScrumPy–metabolic modeling in Python Poolman (2006).
This includes facilities for performing linear programming using the Gnu Linear Programming Kit–

### Results
The number of reactions active in the metabolic network when producing phloem sap is between 173 and 180, depending on light intensity, which is, not surprisingly, lower than the 270–277 needed to make the major biomass components.
When varying the light intensity for a mature, non-growing source leaf, the authors observed five distinct regions in the flux responses in mitochondria and chloroplasts (Figure 1) that appeared qualitatively similar to the pattern of responses the authors reported previously for a growing, non-exporting leaf ([^Poolman_et+al_2013_a]).
At these transitions there are changes in the set of reactions constituting the optimal solution for the flux distribution.
Region B is characterized by complete oxidation of pyruvate by the conventional operation of the citric acid cycle and the mitochondrial electron transport chain with www.frontiersin.org and the specific destination of the fixed carbon has only a minor influence

### Conclusion
The authors' results have shown that the occurrence of transitions in the flux solutions for the rice leaf cell metabolism model at different light intensities are not peculiar to the production of a specific metabolic output, but are relatively insensitive to the nature of the output.
Part of that difference comes from the known difference in redox state between the two mixtures, reflected in the Assimilatory Quotient values.
Another component is in the amount of ATP required for synthesis, and the authors do not know this value with any certainty.
In both cases, there will be a non-growth associated maintenance energy value, which might be assumed to be more or less constant.
The small difference in the minimum light input required in the two cases is of no significance compared to the light needed to satisfy the cell’s maintenance ATP needs, which itself is a very uncertain figure, though the value the authors have used results in a minimum www.frontiersin.org quantum demand figure that is in the range of experimental measurements

##  Confirmation of earlier findings
- The number of reactions active in the metabolic network when producing phloem sap is between 173 and 180, depending on light intensity, which is, not surprisingly, lower than the 270–277 needed to make the major biomass components. When varying the light intensity for a mature, non-growing source leaf, ==we observed five distinct regions in the flux responses in mitochondria and chloroplasts== (Figure 1) that appeared qualitatively similar to the pattern of responses we reported previously for a growing, non-exporting leaf ([^Poolman_et+al_2013_a])
- In any case, the small difference in the minimum light input required in the two cases is of no significance compared to the light needed to satisfy the cell’s maintenance ATP needs, which itself is a very uncertain figure, though the value we have used results in a minimum www.frontiersin.org quantum demand figure that is in the range of experimental measurements. ==Our AQ values for an expanding leaf are comparable to those measured experimentally==, as is the magnitude of the difference between using NH3 and NO3 as N source ([^Searles_2003_a])

## Counterpoint to earlier claims
- As stated above, this implies that if photorespiratory CO2 is recovered, O2 consumption, and evolution are balanced for the complete cycle. Though ==we cannot claim on the basis of this evidence that this will always be the case in all feasible metabolic states==, nevertheless the fact that there are situations where it can occur undermines the use of AQ as an indicator of the degree of photorespiration (e.g., [^Skillman_2008_a])

## Data and code
- supplementary data to that paper (http://dx.doi.org/10.1104/pp.113.216762
- Supplementary Material for this article can be found online at: http://www.frontiersin.org/journal/10.3389/fpls.2014.00656/abstract


## References
[^Boyle_2009_a]: Boyle, N. R., and Morgan, J. A. (2009). Flux balance analysis of primary metabolism in Chlamydomonas reinhardtii. BMC Syst. Biol. 3:4. doi: 10.1186/1752-0509-3-4 [[Boyle_FluxBalanceAnalysisPrimaryMetabolism_2009]] [OA](https://doi.org/10.1186/1752-0509-3-4)  [Scite](https://scite.ai/reports/10.1186/1752-0509-3-4)

[^Chang_et+al_2011_a]: Chang, R. L., Ghamsari, L., Manichaikul, A., Hom, E. F. Y., Balaji, S., Fu, W., et al. (2011). Metabolic network reconstruction of Chlamydomonas offers insight into light—driven algal metabolism. Mol. Syst. Biol. 7:518. doi: 10.1038/msb.2011.52 [[Chang_et+al_MetabolicNetworkReconstructionChlamydomonasOffers_2011]] [OA](https://doi.org/10.1038/msb.2011.52)  [Scite](https://scite.ai/reports/10.1038/msb.2011.52)

[^Cheung_et+al_2014_a]: Cheung, C. Y. M., Poolman, M. G., Fell, D. A., Ratcliffe, R. G., and Sweetlove, L. J. (2014). A diel flux balance model captures interactions between light and dark metabolism during day-night cycles in C3 and crassulacean acid metabolism leaves. Plant Physiol. 165, 917–929. doi: 10.1104/pp.113.234468 [[Cheung_et+al_DielFluxBalanceModelCaptures_2014]] [OA](https://doi.org/10.1104/pp.113.234468)  [Scite](https://scite.ai/reports/10.1104/pp.113.234468)

[^Cheung_et+al_2013_a]: Cheung, C. Y. M., Williams, T. C. R., Poolman, M. G., Fell, D. A., Ratcliffe, R. G., and Sweetlove, L. J. (2013). A method for accounting for maintenance costs in flux balance analysis improves the prediction of plant cell metabolic phenotypes under stress conditions. Plant J. 75, 1050–1061. doi: 10.1111/tpj.12252 [[Cheung_et+al_MethodAccountingMaintenanceCostsFlux_2013]] [OA](https://doi.org/10.1111/tpj.12252)  [Scite](https://scite.ai/reports/10.1111/tpj.12252)

[^Chindelevitch_et+al_2014_a]: Chindelevitch, L., Trigg, J., Regev, A., and Berger, B. (2014). An exact arithmetic toolbox for a consistent and reproducible structural analysis of metabolic network models. Nat. Commun. 5:4893. doi: 10.1038/ncomms5893 [[Chindelevitch_et+al_ExactArithmeticToolboxConsistentReproducible_2014]] [OA](https://doi.org/10.1038/ncomms5893)  [Scite](https://scite.ai/reports/10.1038/ncomms5893)

[^de_Oliveira_et+al_2010_a]: de Oliveira Dal’Molin, C. G., Quek, L.-E., Palfreyman, R. W., Brumbley, S. M., and Nielsen, L. K. (2010). C4GEM, a genome-scale metabolic model to study C4 plant metabolism. Plant Physiol. 154, 1871–1885. doi: 10.1104/pp.110.166488 [[de_Oliveira_et+al_C4gemGenomescaleMetabolicModelStudy_2010]] [OA](https://doi.org/10.1104/pp.110.166488)  [Scite](https://scite.ai/reports/10.1104/pp.110.166488)

[^Grafahrend-Belau_et+al_2009_a]: Grafahrend-Belau, E., Schreiber, F., Koschützki, D., and Junker, B. H. (2009). Flux balance analysis of barley seeds: a computational approach to study systemic properties of central metabolism. Plant Physiol. 149, 585–598. doi: 10.1104/pp.108.129635 [[Grafahrend-Belau_et+al_FluxBalanceAnalysisBarleySeeds_2009]] [OA](https://doi.org/10.1104/pp.108.129635)  [Scite](https://scite.ai/reports/10.1104/pp.108.129635)

[^Hayashi_1990_a]: Hayashi, H., and Chino, M. (1990). Chemical composition of phloem sap from the uppermost internode of the rice plant. Plant Cell Physiol. 319, 247–251. [[Hayashi_ChemicalCompositionPhloemFromUppermost_1990]] [OA](https://api.scholarcy.com/oa_version?query=Hayashi%2C%20H.%20Chino%2C%20M.%20Chemical%20composition%20of%20phloem%20sap%20from%20the%20uppermost%20internode%20of%20the%20rice%20plant%201990) [GScholar](https://scholar.google.co.uk/scholar?q=Hayashi%2C%20H.%20Chino%2C%20M.%20Chemical%20composition%20of%20phloem%20sap%20from%20the%20uppermost%20internode%20of%20the%20rice%20plant%201990) [Scite](https://api.scholarcy.com/scite_url?query=Hayashi%2C%20H.%20Chino%2C%20M.%20Chemical%20composition%20of%20phloem%20sap%20from%20the%20uppermost%20internode%20of%20the%20rice%20plant%201990)

[^Holzhuetter_2004_a]: Holzhütter, H.-G. (2004). The principle of flux minimization and its application to estimate stationary fluxes in metabolic networks. Eur. J. Biochem. 271, 2905–2922. doi: 10.1111/j.1432-1033.2004.04213.x [[Holzhuetter_PrincipleFluxMinimizationApplicationEstimate_2004]] [OA](https://doi.org/10.1111/j.1432-1033.2004.04213.x)  [Scite](https://scite.ai/reports/10.1111/j.1432-1033.2004.04213.x)

[^International_2005_a]: International Rice Genome Sequencing Project (2005). The map–based sequence of the rice genome. Nature 436, 793–800. doi: 10.1038/nature03895 [[International_InternationalRiceGenomeSequencingProject_2005]] [OA](https://doi.org/10.1038/nature03895)  [Scite](https://scite.ai/reports/10.1038/nature03895)

[^Juliano_1986_a]: Juliano, B. O. (1986). Rice: Chemistry and Technology, 2nd Edn., Chapter 19. St. Paul, MN: American Association of Cereal Chemists Inc. [[Juliano_RiceChemistryTechnologynChapter19_1986]] [OA](https://scholar.google.co.uk/scholar?q=Juliano%2C%20B.O.%20Rice%3A%20Chemistry%20and%20Technologyn.%2C%20Chapter%2019%201986) [GScholar](https://scholar.google.co.uk/scholar?q=Juliano%2C%20B.O.%20Rice%3A%20Chemistry%20and%20Technologyn.%2C%20Chapter%2019%201986) 

[^Kwon_1985_a]: Kwon, Y. W., and Soh, C. H. (1985). Characteristics of nuclear DNA in rice roots of japonica and indica x japonica varieties. Agric. Res. Seoul Natl. Univ. 10, 63–68. [[Kwon_CharacteristicsNuclearDnaRiceRoots_1985]] [OA](https://api.scholarcy.com/oa_version?query=Kwon%2C%20Y.W.%20Soh%2C%20C.H.%20Characteristics%20of%20nuclear%20DNA%20in%20rice%20roots%20of%20japonica%20and%20indica%20x%20japonica%20varieties%201985) [GScholar](https://scholar.google.co.uk/scholar?q=Kwon%2C%20Y.W.%20Soh%2C%20C.H.%20Characteristics%20of%20nuclear%20DNA%20in%20rice%20roots%20of%20japonica%20and%20indica%20x%20japonica%20varieties%201985) [Scite](https://api.scholarcy.com/scite_url?query=Kwon%2C%20Y.W.%20Soh%2C%20C.H.%20Characteristics%20of%20nuclear%20DNA%20in%20rice%20roots%20of%20japonica%20and%20indica%20x%20japonica%20varieties%201985)

[^Mintz-Oron_et+al_2012_a]: Mintz-Oron, S., Meir, S., Malitsky, S., Ruppin, E., Aharoni, A., and Shlomi, T. (2012). Reconstruction of Arabidopsis metabolic network models accounting for subcellular compartmentalization and tissue–specificity. Proc. Natl. Acad. Sci. U.S.A. 109, 339–344. doi: 10.1073/pnas.1100358109 [[Mintz-Oron_et+al_ReconstructionArabidopsisMetabolicNetworkModels_2012]] [OA](https://doi.org/10.1073/pnas.1100358109)  [Scite](https://scite.ai/reports/10.1073/pnas.1100358109)

[^Padmasree_et+al_2002_a]: Padmasree, K., Padmavathi, L., and Raghavendra, A. S. (2002). Essentiality of mitochondrial oxidative metabolism for photosynthesis: optimization of carbon assimilation and protection against photoinhibition. Crit. Rev. Biochem. Mol. Biol. 37, 71–119. doi: 10.1080/10409230290771465 [[Padmasree_et+al_EssentialityMitochondrialOxidativeMetabolismPhotosynthesis_2002]] [OA](https://doi.org/10.1080/10409230290771465)  [Scite](https://scite.ai/reports/10.1080/10409230290771465)

[^Poolman_2006_a]: Poolman, M. G. (2006). ScrumPy - metabolic modelling with Python. Syst. Biol. (Stevenage). 153, 375–378. doi: 10.1049/ip-syb:20060010 [[Poolman_ScrumpyMetabolicModellingWith_2006]] [OA](https://doi.org/10.1049/ip-syb:20060010)  [Scite](https://scite.ai/reports/10.1049/ip-syb:20060010)

[^Poolman_et+al_2013_a]: Poolman, M. G., Kundu, S., Shaw, R., and Fell, D. A. (2013). Responses to light intensity in a genome-scale model of rice metabolism. Plant Physiol. 162, 1060–1072. doi: 10.1104/pp.113.216762 [[Poolman_et+al_ResponsesLightIntensityGenomescaleModel_2013]] [OA](https://doi.org/10.1104/pp.113.216762)  [Scite](https://scite.ai/reports/10.1104/pp.113.216762)

[^Poolman_et+al_2009_a]: Poolman, M. G., Miguet, L., Sweetlove, L. J., and Fell, D. A. (2009). A genome–scale metabolic model of Arabidopsis and some of its properties. Plant Physiol. 151, 1570–1581. doi: 10.1104/pp.109.141267 [[Poolman_et+al_GenomescaleMetabolicModelArabidopsisSome_2009]] [OA](https://doi.org/10.1104/pp.109.141267)  [Scite](https://scite.ai/reports/10.1104/pp.109.141267)

[^Schuster_et+al_2008_a]: Schuster, S., Pfeiffer, T., and Fell, D. A. (2008). Is maximization of molar yield in metabolic networks favoured by evolution? J. Theor. Biol. 252, 497–504. doi: 10.1016/j.jtbi.2007.12.008 [[Schuster_et+al_MaximizationMolarYieldMetabolicNetworks_2008]] [OA](https://doi.org/10.1016/j.jtbi.2007.12.008)  [Scite](https://scite.ai/reports/10.1016/j.jtbi.2007.12.008)

[^Searles_2003_a]: Searles, P. S., and Bloom, A. J. (2003). Nitrate photo–assimilation in tomato leaves under short–term exposure to elevated carbon dioxide and low oxygen. Plant Cell Environ. 26, 1247–1255. doi: 10.1046/j.1365-3040.2003. 01047.x [[Searles_NitratePhotoassimilationTomatoLeavesUnder_2003]] [OA](https://doi.org/10.1046/j.1365-3040.2003.01047.x)  [Scite](https://scite.ai/reports/10.1046/j.1365-3040.2003.01047.x)

[^Skillman_2008_a]: Skillman, J. B. (2008). Quantum yield variation across the three pathways of photosynthesis: not yet out of the dark. J. Exp. Bot. 59, 1647–1661. doi: 10.1093/jxb/ern029 [[Skillman_QuantumYieldVariationAcrossThree_2008]] [OA](https://doi.org/10.1093/jxb/ern029)  [Scite](https://scite.ai/reports/10.1093/jxb/ern029)

[^Williams_et+al_2010_a]: Williams, T. C. R., Poolman, M. G., Howden, A. J. M., Schwarzlander, M., Fell, D. A., Ratcliffe, R. G., et al. (2010). A genome–scale metabolic model accurately predicts fluxes in central carbon metabolism under stress conditions. Plant Physiol. 154, 311–323. doi: 10.1104/pp.110. 158535 [[Williams_et+al_GenomescaleMetabolicModelAccuratelyPredicts_2010]] [OA](https://doi.org/10.1104/pp.110.158535)  [Scite](https://scite.ai/reports/10.1104/pp.110.158535)

[^Youens-Clark_et+al_2011_a]: Youens-Clark, K., Buckler, E., Casstevens, T., Chen, C., Declerck, G., Derwent, P., et al. (2011). Gramene database in 2010: updates and extensions. Nucleic Acids Res. 39, D1085–D1094. doi: 10.1093/nar/gkq1148 [[Youens-Clark_et+al_GrameneDatabase2010UpdatesExtensions_2011]] [OA](https://doi.org/10.1093/nar/gkq1148)  [Scite](https://scite.ai/reports/10.1093/nar/gkq1148)

[^_0000_a]: www.frontiersin.org [[__0000]] [OA](http://www.frontiersin.org)  

