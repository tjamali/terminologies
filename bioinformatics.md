# Bioinformatics Methods Terms

## **COMPUTING FUNDAMENTALS**

### **Algorithm**
A set of step-by-step instructions or rules designed to solve a specific problem or perform a computation. In bioinformatics, algorithms are used for sequence alignment, phylogenetic reconstruction, gene prediction, and many other analytical tasks.

### **Database**
A structured collection of data that is organized and stored electronically for efficient retrieval and analysis. Bioinformatics databases store biological information such as DNA/protein sequences, gene annotations, pathway information, and experimental data.

### **Command line interface**
A text-based method of interacting with computers by typing commands rather than using graphical user interfaces. Essential for bioinformatics as most analysis tools are command-line based and it enables automation and scripting.

### **High-performance computing (HPC)**
Computing systems with significantly higher processing power, memory, and storage than standard computers, often using parallel processing across multiple processors or computers. Required for computationally intensive bioinformatics tasks like genome assembly and large-scale data analysis.

## **DATA FORMATS AND STANDARDS**

### **File formats**
Standardized ways of encoding and storing biological data. Common bioinformatics formats include:
- **FASTA**: Sequence data (DNA, RNA, protein)
- **FASTQ**: Sequencing reads with quality scores  
- **BED**: Genomic intervals and features
- **VCF**: Variant call format for genetic variants
- **SAM/BAM**: Sequence alignment data
- **GTF/GFF**: Gene annotations

### **Genome annotation**
The process of identifying and labeling functional elements in a genome sequence, including genes, regulatory elements, repetitive sequences, and other features. Provides the biological context necessary for interpreting genomic data.

## **BIOLOGICAL KNOWLEDGE BASES**

### **Gene Ontology (GO)**
A standardized vocabulary (controlled ontology) that describes gene and protein functions across three domains: molecular function, biological process, and cellular component. Enables consistent annotation and comparison of gene functions across species and studies.

### **Pathway databases**
Curated collections of biological pathways that describe sequences of molecular interactions and reactions. Major databases include KEGG (metabolic pathways), Reactome (signaling pathways), and BioCyc. Used for functional interpretation of gene lists and systems-level analysis.

### **Sequence databases**
Repositories containing biological sequence information. Examples include GenBank (nucleotide sequences), UniProt (protein sequences), and RefSeq (reference sequences). Provide the foundational data for sequence analysis and annotation.

### **Functional annotation**
The process of assigning biological meaning to genes, proteins, or other molecular features by predicting their functions, pathways, and relationships. Often involves comparing sequences to databases and using computational prediction tools.

### **Sequence alignment**
The process of arranging DNA, RNA, or protein sequences to identify regions of similarity, which may indicate functional, structural, or evolutionary relationships. Can be pairwise (comparing two sequences) or multiple sequence alignment (comparing many sequences simultaneously).

### **BLAST (Basic Local Alignment Search Tool)**
A widely-used algorithm and database search tool that finds local similarities between sequences. BLAST compares query sequences against sequence databases to identify homologous sequences, predict function, and infer evolutionary relationships.

## **STATISTICAL FOUNDATIONS**

### **Statistical testing**
Methods for making inferences about populations based on sample data, typically involving hypothesis testing to determine if observed differences are statistically significant. Fundamental to interpreting experimental results and identifying meaningful patterns.

### **P-value**
The probability of obtaining results at least as extreme as those observed, assuming the null hypothesis is true. Lower p-values indicate stronger evidence against the null hypothesis, but must be interpreted carefully considering multiple testing.

### **Multiple testing correction**
Statistical methods that adjust significance thresholds when performing many statistical tests simultaneously to control the overall false positive rate. Common methods include Bonferroni correction and False Discovery Rate control.

### **False discovery rate (FDR)**
The expected proportion of false positives among all significant results. FDR control methods (like Benjamini-Hochberg) are widely used in genomics to balance discovery of true positives while limiting false discoveries.

### **Log transformation**
A mathematical transformation that applies the logarithm function to data values. Commonly used in bioinformatics to normalize skewed data distributions (like gene expression values) and make them more suitable for statistical analysis.

## **DATA PREPROCESSING**

### **Quality control (QC)**
Systematic procedures to assess and ensure data quality before analysis. In sequencing data, QC includes evaluating read quality scores, adapter contamination, sequence duplication, and other technical artifacts that could affect downstream analysis.

### **Data normalization**
Statistical procedures to adjust data values to account for systematic biases or technical variation, making samples comparable. Essential in genomics to correct for library size differences, batch effects, and other technical factors.

### **Normalization methods**
Specific techniques for data normalization, such as:
- **TPM/FPKM**: For RNA-seq expression data
- **Quantile normalization**: Making distributions identical across samples  
- **Z-score normalization**: Centering and scaling data
- **Batch correction**: Removing systematic technical variation

### **Batch effects**
Systematic technical variation between samples processed at different times, locations, or by different personnel/equipment, which can confound biological differences of interest. A major concern requiring careful experimental design and statistical correction methods.

## **WORKFLOW MANAGEMENT**

### **Bioinformatics pipelines**
Automated workflows that chain together multiple computational tools and analysis steps to process biological data from raw input to final results. Pipelines ensure reproducibility, handle complex dependencies, and enable efficient processing of large datasets.

### **Workflow management**
Systems and practices for organizing, executing, and monitoring complex computational workflows. Tools like Nextflow, Snakemake, and CWL help manage dependencies, resource allocation, and error handling in bioinformatics pipelines.

### **Version control**
Systems for tracking changes to code, data, and analysis scripts over time, enabling collaboration and maintaining historical records. Git is the most common version control system, essential for reproducible research.

### **Reproducibility**
The ability to obtain consistent results when an analysis is repeated using the same data and methods. Critical in computational biology and requires careful documentation of software versions, parameters, and computational environments.

## **DATA ANALYSIS METHODS**

### **Clustering**
Unsupervised machine learning methods that group similar data points together based on their characteristics. In bioinformatics, used for grouping genes with similar expression patterns, classifying cell types, or organizing samples by similarity.

### **Dimensionality reduction**
Techniques that reduce the number of variables in high-dimensional data while preserving important patterns. Common methods include Principal Component Analysis (PCA) and t-SNE, used for visualization and noise reduction in genomic data.

### **Data visualization**
The creation of graphical representations of data to facilitate understanding and interpretation. Includes heatmaps, scatter plots, volcano plots, and specialized genomic visualizations. Essential for exploratory analysis and communicating results.

### **Genome assembly**
The computational process of reconstructing a complete genome sequence from shorter sequencing reads by identifying overlapping regions and determining the correct order and orientation of sequences. Produces contigs and scaffolds that represent the genome structure.

### **Motif analysis**
Computational methods for identifying short, conserved sequence patterns (motifs) that often represent functional elements like transcription factor binding sites or regulatory sequences. Includes both motif discovery (finding unknown patterns) and motif scanning (searching for known patterns).

## **SYSTEMS-LEVEL ANALYSIS**

### **Systems biology**
An interdisciplinary approach that studies complex biological systems by analyzing interactions between system components (genes, proteins, metabolites) rather than individual components in isolation. Integrates computational modeling with experimental data.

### **Network analysis**
Computational methods for studying biological networks where nodes represent biological entities (genes, proteins, metabolites) and edges represent interactions or relationships. Used to identify functional modules, key regulatory hubs, and pathway connectivity.

### **Pathway analysis**
Computational approaches that interpret gene lists in the context of known biological pathways to identify which pathways are enriched or perturbed in experimental conditions. Helps translate gene-level changes into biological mechanisms.

### **Gene set enrichment analysis (GSEA)**
A computational method that determines whether predefined sets of genes show statistically significant enrichment in ranked gene lists (e.g., ranked by differential expression). More powerful than simple overlap tests as it considers the entire gene ranking.

### **Cell-type-specific enrichment analysis**
Computational methods that determine whether gene sets are preferentially expressed in specific cell types. Used to interpret bulk tissue data, validate single-cell analyses, and understand tissue composition and cellular functions.

## **ADVANCED ANALYTICAL CONCEPTS**

### **Ontology enrichment**
Statistical analysis to determine if specific biological categories (from controlled vocabularies like Gene Ontology) are over-represented in gene sets of interest. Provides functional interpretation of experimental results.

### **Interactome**
The complete set of molecular interactions in cells or organisms, including protein-protein, protein-DNA, and metabolic interactions. Computational analysis of interactomes reveals functional relationships and regulatory mechanisms.

### **Comparative genomics**
The study of genome structure and function through comparison between different species or individuals. Identifies conserved elements, evolutionary relationships, and functional predictions based on sequence similarity and synteny.

### **Phylogenetics**
The study of evolutionary relationships between organisms or sequences through computational construction and analysis of evolutionary trees (phylogenies). Uses sequence similarity, molecular evolution models, and statistical methods to infer common ancestry and divergence times.
