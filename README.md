# Mutations-in-TNBC-

# Project Summary
Triple-negative breast cancer (TNBC) is an aggressive subtype that frequently develops resistance to chemotherapy. An unresolved question is whether resistance is caused by the selection of rare pre-existing clones or alternatively through the acquisition of new genomic aberrations. The aim of this project is to compare variants in tumour samples before and after chemotherapy. In order to identify tissue-specific variants and exclude germline mutations, we attempted to compare blood and tumour samples.


# Files in the project:
1. Project flowchart
2. Commands TNBC (including useful resources used)
3. FASTQ quality report (PreT)
4. FASTQ quality report (PostT)
5. FASTQ quality report of both (multiqc_report 2)
4. Visualization of Pre_sorted_indexed by samtools
5. VCF stats for Pretreatment sample (VCF stats)
6. VCF stats for Posttreatment sample (post_stats)
7. Report TNBC

# URLs used for samples and reference
Project is SRP114962 
https://www.ncbi.nlm.nih.gov/Traces/study/?acc=SRP114962&f=assay_type_s%3An%3Awgs%3Ac&o=sample_name_s%3Aa

Samples were selected from this website https://www.ncbi.nlm.nih.gov/Traces/study/?page=13&acc=SRP114962&f=assay_type_s%3An%3Awgs%3Ac&o=sample_name_s%3Ad&s=SRR5969409
SRR5969410 KTN102 pretreatment #800 Sample KTN102_0_25 (48 spots)
SRR5969460 KTN102 posttreatment #645 Sample KTN102_OP_1 (48spot)

For reference genome Ensembl database was used and chromosome 10 selected
http://www.ensembl.org/info/data/ftp/index.html
ftp://ftp.ensembl.org/pub/release-99/fasta/homo_sapiens/dna/
ftp://ftp.ensembl.org/pub/release-99/fasta/homo_sapiens/dna/Homo_sapiens.GRCh38.dna.chromosome.10.fa.gz 

