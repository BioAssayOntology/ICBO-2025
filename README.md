# ICBO-2025
BioAssay Ontology (BAO) files for 16th International Conference on Biological and Biomedical Ontology (ICBO):
This repository contains the BioAssay Ontology (BAO) files prepared for the 16th International Conference on Biological and Biomedical Ontology (ICBO-2025). The files in this branch include updates, new terms, and additional axioms introduced to support pharmacokinetics/pharmacodynamics (PK/PD)–related use cases and reasoning-based classification of permeability and efflux assays.

Overview and Purpose:
This repository serves as the development and demonstration branch accompanying the ICBO-2025 use case publication. It provides ontology files that can be explored in Protégé to reproduce the reasoning examples presented in the manuscript.

Repository Contents:
The repository includes a modularized release of BAO, organized as follows:
- bao_complete.owl – Main ontology file that imports all BAO modules and external ontologies.
- bao_core.owl – Core BAO module with foundational classes and relations.
- bao_module_*.owl – Thematic modules for biology, properties, vocabularies, etc.
- bao_vocabulary_*.owl – Domain-specific vocabularies (e.g., assay, detection, computational methods, instruments, materials, organizations, people, units).
- bao_external.owl – Imports of external ontologies (ChEBI, CLO, DOID, EFO, GO, UBERON, etc.) for cross-domain alignment.
- BAO_*_import.owl – Individual import files for referenced external ontologies.

Together, these files provide a complete, interoperable ontology package for use in semantic annotation, reasoning, and ontology-driven data integration.

How to Use
1. Download the repository (clone or zip download) to your local machine.
2. Place all ontology files in the same folder to preserve import resolution.
3. Open bao_complete.owl in Protégé
4. Activate a reasoner (HermiT) to reproduce inference-based classifications of assays as described in the ICBO-2025 use case.

The reasoning examples (Figures 6–7 in the paper) will be reproduced by the ontology axioms provided here, demonstrating automated grouping of passive permeability assays and active efflux transporter assays.
