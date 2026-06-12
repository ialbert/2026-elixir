# Ebolavirus genome

NCBI Link:

https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000848505.1/

ACCESSION: GCF_000848505.1

```
# The URL to the genome.
FASTA_URL=https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/848/505/GCF_000848505.1_ViralProj14703/GCF_000848505.1_ViralProj14703_genomic.fna.gz

# The URL to the annotation.
GFF_URL=https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/848/505/GCF_000848505.1_ViralProj14703/GCF_000848505.1_ViralProj14703_genomic.gff.gz

```


szures, mRNA tipusra

awk -F'\t' '$3 == "mRNA"' ebola-mayinga-annotation.gff > mrna-only.gff

Meresek

SRR1972976

https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Get&RID=2GRG19SR016