# Genomics & Genetics Terms 

## **FOUNDATIONAL MOLECULAR BIOLOGY**

### **Nucleotide**
The basic building block of DNA and RNA, consisting of a phosphate group, a sugar (ribose in RNA, deoxyribose in DNA), and one of four nitrogenous bases (A, T, G, C in DNA; A, U, G, C in RNA).

### **Base pairs**
Complementary nucleotides that pair together in double-stranded DNA (A with T, G with C) or RNA-DNA hybrids. The human genome contains approximately 3.2 billion base pairs.

### **DNA (Deoxyribonucleic acid)**
The hereditary material containing genetic instructions for all living organisms, composed of four nucleotides arranged in a double helix structure.

### **RNA (Ribonucleic acid)**
**RNA (Ribonucleic acid)** is a versatile nucleic acid that differs from DNA in several key ways: it contains ribose sugar (with a 2'-OH group) instead of deoxyribose, uses uracil instead of thymine, and is typically single-stranded, allowing it to fold into complex 3D structures. This structural flexibility enables RNA to perform diverse functions beyond simple information storage, including catalysis (ribozymes), regulation, and protein synthesis. The presence of the 2'-OH group makes RNA less stable than DNA but allows for the formation of intricate secondary structures that are essential for its various biological roles.

The major types of RNA include **mRNA (messenger RNA)**, which carries genetic information from DNA to ribosomes for protein synthesis; **tRNA (transfer RNA)**, which brings amino acids to the ribosome during translation; **rRNA (ribosomal RNA)**, the structural and catalytic component of ribosomes; and various **regulatory RNAs** such as microRNAs (miRNAs) that control gene expression, long non-coding RNAs (lncRNAs) that regulate chromatin and transcription, and small nuclear RNAs (snRNAs) that process other RNAs. Additionally, newer discoveries include circular RNAs (circRNAs) and enhancer RNAs (eRNAs), highlighting the expanding complexity of the RNA world and its central role in gene regulation and cellular function.

### **Gene**
A functional unit of heredity consisting of a DNA sequence that codes for a specific protein or RNA molecule. Genes contain the instructions for making the molecules that control cellular functions.

### **Chromosome**
A structure containing DNA and associated proteins found in the nucleus of cells. Humans have 23 pairs of chromosomes (46 total), with each chromosome containing hundreds to thousands of genes.

### **Genome**
The complete set of DNA in an organism, including all of its genes and non-coding sequences. The human genome contains approximately 3.2 billion base pairs and ~20,000-25,000 protein-coding genes.

## **BASIC GENETICS CONCEPTS**

### **Allele**
Alternative versions of a gene or genetic variant at a specific chromosomal location. For example, a SNP position might have a "C" allele and a "T" allele in different individuals.

### **Genotype**
An individual's genetic makeup at specific loci, typically described as the combination of alleles present (e.g., CC, CT, or TT for a SNP).

### **Phenotype**
Observable characteristics or traits of an individual, which result from the interaction between genotype and environmental factors (e.g., height, disease status, gene expression levels).

### **Diploid**
Having two complete sets of chromosomes, one from each parent. Humans are diploid organisms with two copies of each chromosome (except sex chromosomes in males).

### **Homozygous**
Having identical alleles at a specific genetic locus (e.g., AA or BB).

### **Heterozygous**
Having different alleles at a specific genetic locus (e.g., AB).

### **Maternal/Paternal**
Referring to genetic material inherited from the mother (maternal) or father (paternal). In diploid organisms, one copy of each chromosome comes from each parent.

## **GENETIC VARIATION CONCEPTS**

### **SNPs (Single nucleotide polymorphisms)**
The most common type of genetic variation among humans, occurring when a single DNA nucleotide (A, T, G, or C) differs between individuals at the same genomic position. SNPs occur approximately once every 300 base pairs throughout the genome. They serve as genetic markers in GWAS and can be functional (affecting protein structure, gene expression) or neutral. Most human genetic diversity is captured by SNPs.

### **Minor allele frequency (MAF)**
The frequency of the less common allele at a genetic variant in a given population. Typically expressed as a proportion or percentage. MAF is crucial for statistical power calculations in association studies—rare variants (low MAF) require larger sample sizes to detect associations. Most GWAS focus on common variants (MAF > 5%) due to power considerations, though rare variant analyses are increasingly important.

### **Genetic loci**
Specific positions or regions on chromosomes where genes or genetic variants are located. A locus (plural: loci) can refer to a single nucleotide position, a gene, or a broader chromosomal region. In GWAS context, it often refers to genomically defined regions containing one or more associated variants that likely represent the same association signal.

## **POPULATION GENETICS CONCEPTS**

### **Population stratification**
Systematic differences in allele frequencies between subgroups within a study population, often due to ancestry or demographic factors. If not properly controlled, it can lead to false positive associations in GWAS because both genetic variants and phenotypes may differ systematically between population subgroups. Corrected using methods like principal component analysis or mixed linear models.

### **Ancestry**
The genetic heritage or lineage of an individual, reflecting the geographic and ethnic origins of their ancestors. Ancestry affects allele frequencies and linkage disequilibrium patterns, making it important to consider in genetic studies.

### **Hardy-Weinberg equilibrium**
A principle stating that allele and genotype frequencies remain constant in a population across generations under certain conditions (no mutation, selection, migration, or non-random mating). Deviations from HWE can indicate technical problems (genotyping errors, population stratification) or biological factors (inbreeding, selection). HWE testing is a standard quality control step in genetic studies.

### **Inbreeding**
Mating between genetically related individuals, which increases the probability of offspring being homozygous for recessive alleles. Can cause deviations from Hardy-Weinberg equilibrium.

### **Selection**
Evolutionary pressure that affects the survival and reproduction of individuals with certain genotypes, potentially altering allele frequencies over time.

## **GENETIC PROCESSES**

### **Recombination**
The process during meiosis where chromosomes exchange genetic material, creating new combinations of alleles. Recombination frequency depends on the physical distance between loci—closer loci recombine less frequently.

### **Linkage disequilibrium**
The non-random association between alleles at different genetic loci. When two variants are in linkage disequilibrium, they are inherited together more often than would be expected by chance. This occurs because loci close together on the same chromosome are less likely to be separated by recombination. LD patterns vary by ancestry and are crucial for GWAS design, as a significant SNP may be tagging the true causal variant rather than being causal itself.

### **Haplotype**
A group of alleles at different loci on the same chromosome that are inherited together as a unit due to linkage disequilibrium. Haplotypes represent the combination of variants along a chromosomal segment and are important for understanding inheritance patterns, population history, and fine-mapping disease associations.

### **Imprinting**
An epigenetic phenomenon where gene expression depends on the parent of origin. Some genes are only expressed from the maternal copy, others only from the paternal copy.

### **Nonsense-mediated decay**
A cellular quality control mechanism that degrades mRNA molecules containing premature stop codons, preventing translation of truncated proteins.

## **REGULATORY CONCEPTS**

### **Cis-regulatory**
Genetic elements or variants that affect the expression of genes on the same chromosome, typically nearby (within ~1Mb). Examples include promoters, enhancers, and cis-eQTLs.

### **Trans-regulatory**
Genetic elements or variants that affect the expression of genes on different chromosomes or distant genes on the same chromosome, typically through diffusible factors like transcription factors.

### **Functional variant**
A genetic variant that has a biological effect, such as changing protein structure, altering gene expression, or affecting regulatory elements.

### **Causal variant**
The actual genetic variant that is biologically responsible for an observed association, as opposed to variants that are associated due to linkage disequilibrium with the causal variant.

### **Risk alleles**
Alleles that increase the probability of developing a disease or trait. In polygenic risk scores, multiple risk alleles are combined to estimate overall genetic risk.

## **STATISTICAL CONCEPTS**

### **Statistical power**
The probability that a study will detect an association if one truly exists. Power depends on effect size, sample size, allele frequency, and significance threshold. Higher power reduces the chance of false negatives.

### **Effect size**
A quantitative measure of the magnitude of a phenomenon, such as how much a genetic variant increases disease risk (odds ratio) or affects a quantitative trait (beta coefficient).

### **Association**
A statistical relationship between two variables, such as between a genetic variant and a phenotype. Association does not necessarily imply causation.

### **Confounding**
A situation where a third variable is associated with both the exposure and outcome, potentially creating a spurious association or masking a true association.

### **Reverse causation**
A situation where the outcome influences the exposure, rather than the exposure causing the outcome. For example, disease status affecting lifestyle factors rather than lifestyle causing disease.

### **Instrumental variables**
Variables that are associated with the exposure but only affect the outcome through their effect on the exposure. Used in Mendelian randomization to infer causal relationships.

### **Principal component analysis (PCA)**
A statistical technique that reduces the dimensionality of data by identifying the main axes of variation. In genetics, used to capture population structure and control for ancestry in association studies.

### **Mixed linear models**
Statistical models that can account for both fixed effects (like covariates) and random effects (like population structure or family relatedness). Commonly used in GWAS to control for confounding.

## **COMPLEX INHERITANCE CONCEPTS**

### **Heritability**
The proportion of phenotypic variation in a population that is attributable to genetic factors. **Narrow-sense heritability (h²)** refers to additive genetic effects only, while **broad-sense heritability (H²)** includes all genetic effects. **SNP heritability** estimates the proportion of trait variation explained by common SNPs captured on genotyping arrays. Heritability is population- and environment-specific.

### **Allelic imbalance**
The unequal expression or representation of two alleles at a heterozygous locus. In diploid organisms, both maternal and paternal alleles should theoretically be expressed equally, but various factors can cause imbalance: cis-regulatory variants, imprinting, nonsense-mediated decay, or technical artifacts. Allelic imbalance analysis in RNA-seq data can identify functional variants affecting gene expression.

## **ADVANCED ANALYTICAL METHODS**

### **GWAS (Genome-wide association studies)**
A research approach that examines genetic variations (typically SNPs) across the entire genome to identify associations with diseases, traits, or phenotypes. GWAS compares the frequency of genetic variants between cases (people with a disease/trait) and controls (people without). It's an unbiased, hypothesis-free method that can discover novel genetic factors. Requires large sample sizes (thousands to millions of individuals) to detect statistically significant associations and account for multiple testing burden.

### **Meta-analysis**
A statistical method that combines results from multiple independent studies to increase statistical power and obtain more precise estimates of genetic effects. In genomics, it pools GWAS data from different cohorts to identify additional genetic loci and improve effect size estimates.

### **Meta-regression**
An extension of meta-analysis that investigates how study-level characteristics (like ancestry, age, sex composition) influence the observed genetic associations. It can identify sources of heterogeneity between studies and explore how genetic effects vary across different populations or conditions.

### **eQTL (Expression quantitative trait loci)**
Genetic variants (usually SNPs) that influence gene expression levels. eQTLs link genetic variation to functional consequences by showing how DNA sequence differences affect RNA expression. **Cis-eQTLs** affect nearby genes (typically within 1Mb), while **trans-eQTLs** affect distant genes or genes on different chromosomes. eQTL analysis helps interpret GWAS findings by identifying the genes and molecular mechanisms underlying genetic associations.

### **Polygenic risk scores (PRS)**
A numerical score that estimates an individual's genetic predisposition to a disease or trait based on their genotype across many genetic variants. PRS is calculated by summing the effects of risk alleles weighted by their effect sizes (typically from GWAS). It represents the cumulative genetic burden and can be used for risk prediction, patient stratification, and understanding genetic architecture of complex traits.

### **Mendelian randomization**
A method that uses genetic variants as instrumental variables to infer causal relationships between exposures and outcomes. It leverages the principle that genetic variants are randomly distributed in the population (like random assignment in experiments), helping to overcome confounding and reverse causation issues in observational studies. For example, using genetic variants that affect smoking behavior to determine if smoking causally influences disease risk.
