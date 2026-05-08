# SATPdb: A Database of Structurally Annotated Therapeutic Peptides

Welcome to the official repository and documentation overview for **SATPdb**, a comprehensive database of structurally annotated therapeutic peptides. This resource integrates data from 22 public domain peptide databases and datasets to provide a unified platform for researchers working in the field of peptide-based therapeutics.

**Web Server:** [http://crdd.osdd.net/raghava/satpdb/](http://crdd.osdd.net/raghava/satpdb/)

## Citation

Singh, S., Chaudhary, K., Dhanda, S. K., Bhalla, S., Usmani, S. S., Gautam, A., ... & Raghava, G. P. S. (2016). 
**SATPdb: a database of structurally annotated therapeutic peptides.** *Nucleic Acids Research*, 44(D1), D1119-D1126. 
[https://doi.org/10.1093/nar/gkv1114](https://doi.org/10.1093/nar/gkv1114)

This dataset can also be found on Zenodo at https://doi.org/10.5281/zenodo.20078292



## About the Database

SATPdb was developed to fill the gap in existing resources by bringing together therapeutic peptides on a single platform to understand their structure-function relationships. It provides structural annotation for the majority of therapeutic peptides published to date, facilitating rational drug design.

The database integrates data from:
* **Public Databases:** Peptides curated from 22 public domain peptide databases/datasets, including 9 developed in-house.
* **Experimental Validation:** Emphasis is placed on peptides whose therapeutic activities have been experimentally validated.

## Key Features

### Comprehensive Dataset
* **19,192 unique peptides** consisting of experimentally validated sequences with lengths between 2 and 50 amino acids.
* **Diverse Residues:** Covers peptides with natural, non-natural, and modified residues.
* **10 Functional Categories:** Systematically grouped into categories such as antimicrobial (10,585), anticancer (1,099), drug delivery (1,642), and antihypertensive (1,698).

### Structural Annotations
* **PDB-Derived Structures:** 644 peptide structures collected directly from the Protein Data Bank.
* **Predicted Structures:** 13,444 structures predicted using PEPstrMOD and 607 predicted using the I-TASSER suite.
* **Modified Residues:** Structural annotation for 674 peptides having modified residues.

### Built-in Tools
* **Search & Mapping:** Facilities for extensive searching, segment searching, and mapping peptides onto query protein sequences.
* **Similarity Search:** Support for structure and sequence similarity searches using BLAST.
* **Moonlighting Identification:** Tools to search for "moonlighting" peptides that possess multiple therapeutic functions.



## Overview

SATPdb is designed to handle complex relational data with a focus on structural utility:
1.  **Functional Classification:** Peptides are categorized into major functions and further divided into sub-categories (e.g., anticancer divided into antitumor and antiangiogenic).
2.  **Meta-Database Architecture:** Entries are cross-linked with original source databases for easy switching and data verification.
3.  **Responsive Interface:** Built with HTML5 and CSS to be compatible with mobile, tablet, and desktop devices.


## Applications

* **Molecular Discovery:** Identifying moonlighting peptides for drug repositioning to reduce clinical trial costs.
* **Drug Delivery:** Designing peptides capable of crossing the blood-brain barrier or acting as cell-penetrating vehicles.
* **Rational Peptide Design:** Utilizing 3D structural information for molecular simulations, docking, and studying peptide-receptor interactions.

## Contact & Authors

**Prof. G.P.S. Raghava**
raghava@imtech.res.in
Bioinformatics Centre, CSIR-Institute of Microbial Technology, Chandigarh, India.

## License

This is an Open Access article distributed under the terms of the **Creative Commons Attribution License (CC BY 4.0)**.
