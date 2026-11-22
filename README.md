# Analysis-of-Germline-Variants-for-TP53-and-BRCA1-genes
As a bioinformatician, I was asked to analyze a sample from  wet-lab collaborators, and provide a detailed bioinformatics report on the germline variants in this sample.

## Sample Information
The sample being studied is known as NA12878 (also known as HG001), it is from a Utah female resident with Northern and Western European Ancestry.

Origin: It is derived from a much larger, high-coverage 300x Illumina HiSeq dataset of NA12878. The
"30xdownsample" in the filename indicates that the original high-coverage data (300x) was computationally
reduced (subsampled) to a mean coverage of approximately 30x.


## Process
1) FASTQC Analysis
Basic Statistics, Per base sequence quality, Per sequence quality scores, Per base sequence content, Per sequence GC content and Adapter Content were assessed for QC-checks.

2) Alignment Results
100% of the reads are mapped. Alignment rate was computed using Samtools

3) Exploration and Interpretation of the VCF file
Variant Calling File was analysed to describe the Variants on the TP53 and BRCA1 genes.

4) Biological and Clinical Interpretation for TP53 and BRCA1 using Interactive Genome Viewer
The TP53 gene controls the activation of the transcription factor p53. This transcription factor
plays a key role in defense against cancer development (Joerger et al., 2025). 

The germline variants of BRCA1 are associated with high risk of breast and ovarian carcinomas.
These carcinomas are characterized by homologous recombination deficiency.
