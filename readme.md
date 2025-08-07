# Transcriptomic Subtyping of Patient-Derived Ovarian Cancer Models Using NMF-Based Clustering and Downstream Functional Characterisation
## Overview
This repository contains the analysis code and supporting files for the transcriptomic classification of patient-derived ovarian cancer models (OCMs) using RNA-seq data. The primary aim is to define tumour-intrinsic molecular subtypes through non-negative matrix factorisation (NMF)–based clustering, followed by differential expression, pathway enrichment, and transcription factor activity analysis. These subtypes are then compared with established subtype frameworks from bulk tumour studies.

Additional analyses explore how ovarian cancer cell lines (from the Cancer Cell Line Encyclopedia, CCLE) relate to the identified subtypes, offering a reference point for selecting relevant models.

The repository is structured to enable full reproducibility of the analysis, including preprocessing, clustering, and downstream biological interpretation.

This project provides a resource for researchers studying HGSOC biology, with an emphasis on tumour-intrinsic transcriptomic diversity.

## Background
High-grade serous ovarian cancer (HGSOC) is the most common and lethal subtype of ovarian cancer, marked by high genetic complexity and clinical heterogeneity. Transcriptomic profiling of bulk tumours has identified distinct molecular subtypes, but these are often confounded by stromal and immune cell signals that mask tumour-cell-specific biology.

To overcome this, we generated a living biobank of patient-derived ovarian cancer models (OCMs), representing purified epithelial tumour cells from HGSOC patients. This system allows for the interrogation of transcriptional programs that are intrinsic to the cancer cells themselves.

