# Phewas
# Pipeline for Phenome Wide Association Studies

# Prerequistes tools to be installed
nextflow
docker
R package

# Installation
git clone https://github.com/gkatagi/Phewas.git  && cd Phewas


# Example command to run the pipeline:
```bash
nextflow run main.nf --vcf_file testdata/vcf_samples.csv --pheno SMOKER --pheno_file testdata/all.doid.count.csv
```
