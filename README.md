# Project-4

# Homo sapiens/Malate dehydrogenase, mitochondrial (MDH2)
# P40926
# D173N


## Description of the protein and variation site

Malate dehydrogenase or MDH2 is an enzyme that catalyzes the reversible conversion of (S)-malate to oxaloacetate while reducing NAD+ to NADH (de Lorenzo et al., 2024). MDH2 is a homodimer with one active site at each subunit. Each monomer is built from two regions, an N-terminus that binds the NAD+ and NADH cofactor and a C-terminus that binds the substrate.

The catalytic mechanism utilizes histidine and aspartate to move along a proton and in this case a hydrogen atom. In my numbering, His176 acts as the base that pulls a proton off of malate and Asp159 helps to stabilize the protonated form so histidine can do its job. Three arginines hold the substrate in place (Arg80, Arg86, and Arg152) by forming salt bridges with the carboxylate groups of malate (Eo et al., 2022). 

Loss of human MDH2 activity causes a recessive mitochondrial disease. Patients are typically infants who present with seizures, low muscle tone, developmental delay, and excretion of malate into their urine (Ait-El Mkadem et al., 2017). The variant I was assigned, D173N, was first described by Priestley et al. (2022) in a patient who carried it together with a second MDH2 variant on another allele. In this variant there is a change found at amino acid position 149 and it changes from D (Aspartate) which is negatively charged into N (Asparagine) which is neutrally charged. The same paper added this variant to a list of pathogenic MDH2 mutations and confirmed loss of function in this gene which was enough to cause early onset epileptic encephalopathy in humans. 
The D173N variant changes a single amino acid at position 173 (Uniprot position, 149 in Mol*) from aspartate to asparagine. Aspartate and asparagine are nearly the same size and shape, but aspartate is negatively charged at biological pH whereas asparagine is neutrally charged. This is an isosteric change but not an isoelectric one, so we should expect the structure to look almost identical while the chemistry of the active site will be altered. 

1. image of the unmodified site
![](images/Site.png) Unmodified active site region within MDH2

2. image of modification site
![](images/Asparagine_Model.png) This model shows the almost unchanged structure of the variant, yet chemically this difference affects the active site (His176). 


## Effect of the sequence variant on MDH dynamics

Compare the data on the variant to the project 2 data


1. Image of aligned PDB files (no solvent)
 (images/Superimposed_Variant.png)
Superimposed structure of MDH2 D173N variant in MolStar. The superimposed image shows regions of poor overlap. This is evident by the gaps and spaces between the outputs and overall thickness of the protein.The residue is highlighted and labeled. The location of the variant is demonstrated to be found in a Beta sheet within MDH2.

2. Image of the site with the aligned PDB files (no solvent)
(images/Superimposed_Variant_Close_Up.png)
Close up image of the site of variation within MDH2 for variant D173N

3. Annotated RMSF plot showing differences between the simulations
![alt text](images/RMSF_of_wildtype.png)
(images/RMSF_of_Variant.png)


4. Annotated plots of pKa for the key amino acids
(images/pKa.png)
Predicted pKa Values of Key Catalytic and Binding-Site Residues. Results highlight the pKa values of residues most critical to enzymatic function and ligand interaction. Value differences between the wild-type and variant can be observed. Together, these residues define the electrostatic environment of the active site and are therefore the most relevant for pKa analysis. pKa values between the wild-type and variant don’t differ significantly. The environment of these residues aren’t impacted remarkably for ligand binding specificity. The graph visualizes scatterplot data for the wild-type and variant pKa values across residues. 

5. If needed, show ligand bound images and how modification affects substrate binding
(images/Variant_Malate.png)
(images/Variant_NAD+.png)
MDH2 reactants malate and NAD+ are shown in the figures above. NAD+ is on the right highlighted in pink and malate is on the left and circled. Poor alignment is demonstrated by gaps between the protein structures. Comparing to wildtype, The D173N substitution removes a negative charge, which likely disrupts the electrostatic network that normally positions NAD⁺ and the substrate correctly which is consistent with reduced catalytic efficiency typically seen in these types of variants.




## Conclusions and key takeaways

Based on the data retrieved from the simulations revealing information regarding chemical and structural analysis of the protein structure between the wildtype and D173N variant, this modification impacts the protein's chemistry more than its structure. Aspartate and asparagine are nearly isosteric, and as demonstrated in Figures 2 and 3, the overall fold of the enzyme is preserved with no structural differences detected between the wild-type and variant models. The RMSF plots shown in Figures 9 and 10 support this, as the variant alters very little of the protein's dynamics relative to the wild-type. However, at the local level, the loss of the negative charge at position 173 disrupts the electrostatic environment of the active site, particularly the interaction with His176 that is critical for proton transfer during catalysis. Ligand alignment shown in Figures 7 and 8 demonstrates poor superimposition of malate and NAD+ between the wild-type and variant, suggesting substrate and cofactor positioning is compromised. pKa values presented in Table 1 are not dramatically different between the two, which is consistent with the structural integrity being largely maintained. The AlphaMissense pathogenicity score of 0.319 shown in Figure 11 reflects this mixed picture. The variant is predicted to be damaging enough to cause disease, as confirmed in the literature by Priestley et al. (2022), yet the mechanism of dysfunction is chemical rather than structural, primarily manifesting as reduced catalytic efficiency through the disruption of His176 positioning rather than through misfolding or loss of dimerization.

## Authors

Thomas Field

## Deposition Date
6 May 2026

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

*Ait-El-Mkadem, Samira, et al. “Mutations in MDH2, Encoding a Krebs Cycle Enzyme, Cause Early-Onset Severe Encephalopathy.” The American Journal of Human Genetics, vol. 100, no. 1, Jan. 2017, pp. 151–59. DOI.org (Crossref), doi.org/10.1016/j.ajhg.2016.11.014.

*Broeks, Melissa H., et al. “Inborn Disorders of the Malate Aspartate Shuttle.” Journal of Inherited Metabolic Disease, vol. 44, no. 4, July 2021, pp. 792–808. PubMed, doi.org/10.1002/jimd.12402. 

*De Lorenzo, Laura, et al. “Catalytic Mechanism and Kinetics of Malate Dehydrogenase.” Essays in Biochemistry, edited by Joseph Provost et al., vol. 68, no. 2, Oct. 2024, pp. 73–82. doi.org (Crossref), doi.org/10.1042/EBC20230086.

*Eo, Yumi, et al. “Structural Comparison of hMDH2 Complexed with Natural Substrates and Cofactors: The Importance of Phosphate Binding for Active Conformation and Catalysis.” Biomolecules, vol. 12, no. 9, Aug. 2022, p. 1175. DOI.org (Crossref), doi.org/10.3390/biom12091175

*Laemmle, Alexander, et al. “Triheptanoin - Novel Therapeutic Approach for the Ultra-Rare Disease Mitochondrial Malate Dehydrogenase Deficiency.” Molecular Genetics and Metabolism Reports, vol. 29, Dec. 2021, p. 100814. PubMed, doi.org/10.1016/j.ymgmr.2021.100814. 

*Laemmle A, et al. “Induced Pluripotent Stem Cell-Derived Hepatocytes Reveal TCA Cycle Disruption and the Potential Basis for Triheptanoin Treatment for Malate Dehydrogenase 2 Deficiency.” Molecular Genetics and Metabolism Reports, vol. 39, June 2024, p. 101066. PubMed, doi.org/10.1016/j.ymgmr.2024.101066. 

*Qiao, L., Yan, H., Liu, G., Guo, G., & Sun, S. (2026). Intellifold-2: Surpassing alphafold 3 via architectural refinement and structural consistency. https://doi.org/10.64898/2026.02.09.704787

*Roe, Charles R., and Fanny Mochel. “Anaplerotic Diet Therapy in Inherited Metabolic Disease: Therapeutic Potential.” Journal of Inherited Metabolic Disease, vol. 29, nos. 2–3, 2006, pp. 332–40. PubMed, doi.org/10.1007/s10545-006-0290-3.

*Sen, K. “Malate Dehydrogenase 2 Deficiency Is an Emerging Cause of Pediatric Epileptic Encephalopathy with a Recognizable Biochemical Signature.” Science Direct, Dec. 202 AD, doi.org/https://doi.org/10.1016/j.ymgmr.2022.100931.

*Yang HC, et al. “The Malate-Aspartate Shuttle Is Important for de Novo Serine Biosynthesis.” Cell Reports, vol. 42, no. 9, Sept. 2023, p. 113043. PubMed, doi.org/10.1016/j.celrep.2023.113043. 
