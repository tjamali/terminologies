# RNA Biology & Sequencing Terms 

## **FUNDAMENTAL RNA BIOLOGY**

### **Transcription**
The process by which genetic information in DNA is copied into RNA by RNA polymerase enzymes. This is the first step in gene expression, where a specific DNA sequence (gene) serves as a template to produce a complementary RNA molecule.

### **Gene expression**
The process by which information from a gene is used to synthesize functional gene products, typically proteins or functional RNAs. Gene expression involves transcription (DNA to RNA) and translation (RNA to protein), and can be regulated at multiple levels.

### **Transcriptome**
The complete set of RNA transcripts produced by a genome under specific conditions. Unlike the static genome, the transcriptome is dynamic and varies between cell types, developmental stages, and environmental conditions.

### **mRNA (messenger RNA)**
A type of RNA that carries genetic information from DNA to ribosomes for protein synthesis. mRNA is transcribed from protein-coding genes and serves as the template for translation. It undergoes processing including 5' capping, 3' polyadenylation, and splicing in eukaryotes.

### **rRNA (ribosomal RNA)**
A type of RNA that is a structural and catalytic component of ribosomes, the cellular machinery responsible for protein synthesis. rRNA makes up the majority of total cellular RNA and is highly conserved across species.

### **tRNA (transfer RNA)**
Small RNA molecules that serve as adapters during translation, bringing specific amino acids to the ribosome based on the mRNA codon sequence. Each tRNA has an anticodon that pairs with mRNA codons and carries the corresponding amino acid.

### **Translation**
The process by which the genetic code in mRNA is decoded to synthesize proteins. Ribosomes read mRNA codons and coordinate the assembly of amino acids brought by tRNAs to form polypeptide chains.

## **RNA PROCESSING AND REGULATION**

### **Splicing**
The process by which introns (non-coding sequences) are removed from pre-mRNA and exons (coding sequences) are joined together to form mature mRNA. Occurs in the nucleus and is carried out by the spliceosome complex.

### **Alternative splicing**
A process where different combinations of exons from the same gene are joined together during mRNA processing, allowing one gene to produce multiple protein isoforms with different functions. A major source of protein diversity.

### **Isoforms**
Different versions of RNA transcripts or proteins produced from the same gene through processes like alternative splicing, alternative polyadenylation, or alternative transcription start sites. Isoforms can have distinct functions, expression patterns, or regulatory properties.

### **UTRs (Untranslated regions)**
Sequences in mRNA that are not translated into protein, located at the 5' end (5' UTR) and 3' end (3' UTR) of the coding sequence. UTRs contain important regulatory elements that control mRNA stability, localization, and translation efficiency.

### **Polyadenylation**
The addition of a poly(A) tail (string of adenine nucleotides) to the 3' end of mRNA molecules. This modification enhances mRNA stability, facilitates nuclear export, and improves translation efficiency.

### **mRNA stability**
The resistance of mRNA molecules to degradation by cellular nucleases. mRNA stability is regulated by various factors including sequence motifs, RNA-binding proteins, microRNAs, and cellular conditions. Stable mRNAs have longer half-lives and produce more protein.

### **Processing bodies**
Cytoplasmic ribonucleoprotein granules where mRNA degradation, storage, and translational repression occur. Also called P-bodies, they contain mRNAs that are not being actively translated and various RNA-processing enzymes.

## **SPECIALIZED RNA TYPES**

### **Circular RNAs (circRNAs)**
Covalently closed circular RNA molecules formed by back-splicing, where a downstream exon is joined to an upstream exon. CircRNAs are generally more stable than linear RNAs, can act as microRNA sponges, and may regulate gene expression. They are abundant in the brain and associated with various diseases.

### **Extrachromosomal circular DNA (eccDNA)**
Circular DNA molecules that exist independently of chromosomes in the nucleus. They can contain genes and regulatory elements, potentially affecting gene expression and contributing to genetic diversity and disease, including cancer.

## **SEQUENCING FUNDAMENTALS**

### **cDNA (complementary DNA)**
DNA synthesized from mRNA using reverse transcriptase enzyme. Since mature mRNA lacks introns, cDNA represents only the coding sequences of genes. Used in many molecular biology applications including gene cloning and RNA sequencing.

### **Reverse transcription**
The process of synthesizing DNA from an RNA template using reverse transcriptase enzyme. Essential step in RNA sequencing protocols to convert RNA into stable cDNA that can be amplified and sequenced.

### **PCR amplification**
Polymerase Chain Reaction - a technique that amplifies specific DNA sequences through repeated cycles of denaturation, primer annealing, and DNA synthesis. Used in sequencing library preparation to increase the amount of material for sequencing.

### **Fragmentation**
The process of breaking DNA or RNA into smaller pieces of defined size ranges, typically required for next-generation sequencing. Can be achieved through enzymatic, physical (sonication), or chemical methods.

### **Sequencing library**
A collection of DNA fragments with adapter sequences attached that are prepared for sequencing. Libraries contain the template molecules that will be sequenced, with adapters providing binding sites for primers and flow cell surfaces.

### **Reads**
Individual DNA or RNA sequences generated by sequencing instruments. Each read represents the sequence of one DNA/RNA fragment in the library. Read length varies by sequencing technology (typically 75-300 bp for short reads, >1000 bp for long reads).

### **Read depth/Coverage**
The number of sequencing reads that align to a specific genomic position or feature. Higher coverage provides more accurate quantification and better detection of variants. Also called sequencing depth.

### **Quality scores**
Numerical values (typically Phred scores) that indicate the confidence in each sequenced nucleotide. Higher scores indicate greater confidence in the base call. Quality scores are used for filtering and quality control.

### **Reference genome/transcriptome**
A representative DNA sequence (genome) or collection of RNA sequences (transcriptome) for a species, used as a standard for comparison and alignment of sequencing reads. Provides coordinate system for mapping and annotation.

### **Alignment/Mapping**
The process of determining where sequencing reads originate in a reference genome or transcriptome. Alignment algorithms identify the best matching position for each read, accounting for mismatches and gaps.

## **SEQUENCING TECHNOLOGIES**

### **Short-read sequencing**
Sequencing technologies that generate relatively short reads (typically 75-300 base pairs), such as Illumina platforms. Offers high throughput, low error rates, and cost-effectiveness, making it the most widely used approach for RNA-seq.

### **Long-read sequencing**
Sequencing technologies that generate long reads (>1000 base pairs), such as PacBio and Oxford Nanopore platforms. Advantages include better resolution of repetitive regions, structural variants, and splice isoforms, though typically with higher error rates than short-read sequencing.

## **BULK SEQUENCING APPROACHES**

### **Single-cell vs bulk**
**Bulk sequencing** measures the average signal from all cells in a sample, masking cell-to-cell heterogeneity. **Single-cell sequencing** profiles individual cells separately, revealing cellular diversity, rare cell types, and developmental trajectories, but with higher technical noise and cost.

### **RNA-seq (RNA sequencing)**
A high-throughput method for profiling gene expression by sequencing all RNA molecules in a sample. Provides quantitative measurement of transcript abundance, can detect novel transcripts and splice variants, and enables genome-wide expression analysis.

### **Total RNA sequencing**
An RNA-seq approach that sequences all RNA species in a sample (mRNA, rRNA, tRNA, non-coding RNAs) without prior selection or enrichment. Provides comprehensive view of the transcriptome but requires deeper sequencing due to high rRNA content.

### **Transcriptomics**
The comprehensive study of all RNA transcripts produced by a genome under specific conditions. Includes analysis of gene expression levels, splice variants, non-coding RNAs, and their regulation. RNA-seq is the primary experimental approach for transcriptomics.

## **SINGLE-CELL APPROACHES**

### **scRNA-seq (Single-cell RNA sequencing)**
A technique that profiles gene expression in individual cells by isolating single cells and sequencing their RNA content. Enables identification of cell types, developmental trajectories, and rare cell populations that are masked in bulk RNA-seq.

### **snRNA-seq (Single-nucleus RNA sequencing)**
A variant of single-cell RNA sequencing where nuclei are isolated instead of whole cells. Particularly useful for tissues that are difficult to dissociate (like frozen or fibrous tissues) or where cell isolation might alter gene expression.

### **Ribosome profiling (Ribo-seq)**
A specialized sequencing technique that captures RNA fragments protected by ribosomes during translation, providing a genome-wide snapshot of actively translated mRNAs. Complements RNA-seq by showing which transcripts are actually being translated into proteins.

## **ANALYTICAL CONCEPTS**

### **Differential gene expression**
The comparison of gene expression levels between different conditions, treatments, or cell types to identify genes that are significantly up- or down-regulated. Statistical methods account for biological variability and multiple testing to identify truly differentially expressed genes.

### **Batch effects**
Systematic technical variation between samples processed at different times, locations, or by different personnel/equipment, which can confound biological differences of interest. Batch effects are a major concern in RNA-seq studies and require careful experimental design and statistical correction methods.
