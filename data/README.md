# Data documentation

## Source dataset

This project uses processed microarray gene-expression data and sample metadata from the NCBI Gene Expression Omnibus.

- GEO Series accession: GSE6740
- GEO DataSet record: GDS2649
- Platform: GPL96, Affymetrix Human Genome U133A Array
- Organism: Homo sapiens
- Study type: Expression profiling by microarray

## Study design

The study contains 40 expression profiles from purified CD4+ and CD8+ T cells collected from 20 male participants.

Participant groups:

- Acute HIV infection: 5 participants
- Chronic progressive HIV infection: 5 participants
- HIV non-progressors with low or undetectable viral load: 5 participants
- HIV-uninfected controls: 5 participants

Each participant contributed a paired CD4+ and CD8+ T-cell sample. HIV-positive participants were untreated before study entry.

## Data access

Download the processed series-matrix file from GEO:

`GSE6740_series_matrix.txt.gz`

The compressed file may be read directly in Python. If it is decompressed locally, the filename is:

`GSE6740_series_matrix.txt`

This repository does not include the original expression matrix. Users should obtain it directly from GEO using accession GSE6740.

## First analysis subset

The first analysis uses CD4+ T-cell samples only.

- Progressive HIV group: acute HIV infection plus chronic progressive HIV infection
- Reference group: HIV non-progressors plus HIV-uninfected controls

This grouping is exploratory and is intended to examine broad host transcriptional differences associated with progressive untreated HIV infection.

## Privacy and responsible use

This repository contains no private, unpublished, restricted-access, or participant-identifiable data. All source data used in this project are publicly available through GEO.

## Citation

Hyrcza MD, et al. Distinct transcriptional profiles in ex vivo CD4+ and CD8+ T cells from HIV-infected individuals at different clinical stages and rates of disease progression. *Journal of Virology*. 2007.

GEO accession: GSE6740  
Dataset record: GDS2649
