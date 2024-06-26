# Awesome Materials Properties Data Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for data models and ontologies related to materials science and materials properties.

Contributions are very welcome - please follow the [guidelines](CONTRIBUTING.md) and the [Code of Conduct](code_of_conduct.md).

## Schemas | Ontologies | Data Models

### Materials Properties

- [Materials Properties Wikipedia](https://en.wikipedia.org/wiki/List_of_materials_properties): A classification and definitions of materials properties in Wikipedia.

- [Kittel, Charles. Introduction to Solid State Physics. Wiley, 2004](https://www.wiley.com/en-us/Introduction+to+Solid+State+Physics%2C+8th+Edition-p-9780471415268)📖: A standard solid state physics book with chapters dedicated to definitions and derivations for various material properties.

- [KRISS Materials Research Standard Schema](https://github.com/krlee227/MatResData-Standard-Committee/blob/main/dictionary%20ver.%202023%20working%20(230531).json): Standard schema and vocabulary of materials R&D data from the Korean National Center of Materials Research Data and the Korean Research Institute of Standards and Science [(KRISS)](https://www.kriss.re.kr/eng/). ![GitHub Stars](https://img.shields.io/github/stars/krlee227/MatResData-Standard-Committee?style=social)![GitHub last commit](https://img.shields.io/github/last-commit/krlee227/MatResData-Standard-Committee?style=social)

- [Physical information file (PIF)](https://citrineinformatics.github.io/pif-documentation/index.html): Schema for information about physical systems, maintained by Citrine informatics. [![Github Stars](https://img.shields.io/github/stars/CitrineInformatics/pypif?style=social)](https://github.com/CitrineInformatics/pypif) ![GitHub last commit](https://img.shields.io/github/last-commit/CitrineInformatics/pypif?style=social)

- [Graphical Expression of Materials Data (GEMD)](https://citrineinformatics.github.io/gemd-docs/): Open-source format that links together materials, the processes that produced them, and the measurements that characterize them. Initially developed by Citrine Informatics, supersedes PIF.

- [Properties from the NIST Materials Data Vocabulary Ontology (NMRRVOCAB)](https://matportal.org/ontologies/NMRRVOCAB/?p=classes&conceptid=http%3A%2F%2F192.168.1.4%2Fvocab%2F%3Ftema%3D100): Ontology for materials properties from the National Institute of Standards and Technology (NIST).

- [Platform MaterialDigital core ontology (PMDco)](https://material-digital.de/ontologies/): Mid-level ontology for materials science and engineering (processes, experiments, computational workflow).

### Domain-Specific Materials Ontologies

- [Materials Design Ontology](https://github.com/LiUSemWeb/Materials-Design-Ontology) (MDO): "an ontology for materials design field, representing the domain knowledge specifically related to solid-state physics and computational materials science". Applied in practice to Open Databases Integration for Materials Design (OPTIMADE) API and therefore the big computational repos (AFLOW, OQMD, ...). Further material: [registration and graph visualization](https://liusemweb.github.io/mdo/full/1.1/index.html), [PhD thesis](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1651803&dswid=-1784), [slides](https://ontocommons.eu/sites/default/files/2023-06/Huanyu%20Li_Use%20case%20DOME4.0%20and%20OntoCommons-lessons%20learnt%20for%20ontology%20based%20commons.pdf). All links accessed on August 9, 2023.

### Generic Data Models and Top-level Ontologies

- [SciData](https://github.com/stuchalk/scidata): Scientific data model (SDM) and related ontology (SDMO). [![Github Stars](https://img.shields.io/github/stars/stuchalk/scidata?style=social)](https://github.com/stuchalk/scidata) ![GitHub last commit](https://img.shields.io/github/last-commit/stuchalk/scidata?style=social)

- [BFO](https://github.com/BFO-ontology/BFO): The Basic Formal Ontology (BFO) is an upper-level ontology "designed for use in supporting information retrieval, analysis and integration in scientific and other domains", under development since 2002 (last release 2019). [![Github Stars](https://img.shields.io/github/stars/BFO-ontology/BFO?style=social)](https://github.com/BFO-ontology/BFO) ![GitHub last commit](https://img.shields.io/github/last-commit/BFO-ontology/BFO?style=social)

- [European Materials and Modelling Ontology (EMMO)](https://emmc.info/emmo-info/): An ontology designed to represent the "complex multiscale nature of chemicals and materials" with varying analytical philosophical interpretations. Available from the [emmo-repo](https://github.com/emmo-repo/) organization on GitHub. [![Github Stars](https://img.shields.io/github/stars/emmo-repo/EMMO?style=social)](https://github.com/emmo-repo/EMMO) ![GitHub last commit](https://img.shields.io/github/last-commit/emmo-repo/EMMO?style=social)

- [Materials Genome Initiative JSON](https://github.com/usnistgov/mgi-json-schema): JSON schema for materials science and engineering. Directly related is [Material Schema](https://github.com/usnistgov/material-schema) which aims to extend schema.org for materials science. [![Github Stars](https://img.shields.io/github/stars/usnistgov/mgi-json-schema?style=social)](https://github.com/usnistgov/mgi-json-schema) ![GitHub last commit](https://img.shields.io/github/last-commit/usnistgov/mgi-json-schema?style=social)

- [NIST Materials Data Vocabulary Ontology (NMRRVOCAB)](https://matportal.org/ontologies/NMRRVOCAB): Materials data vocabulary ontology from the National Institute of Standards and Technology (NIST) as Simple Knowledge Organization System (SKOS).

- [Chemical Information Ontology](https://github.com/egonw/semanticchemistry/): Aims to establish a standard in representing chemical information. In particular, it aims to produce an ontology to represent chemical structure and to richly describe chemical properties, whether intrinsic or computed." (direct quote from the `README`) [![Github Stars](https://img.shields.io/github/stars/egonw/semanticchemistry?style=social)](https://github.com/egonw/semanticchemistry) ![GitHub last commit](https://img.shields.io/github/last-commit/egonw/semanticchemistry?style=social) [📄](https://doi.org/10.1371/journal.pone.0025513).

- [NFDICORE](https://ise-fizkarlsruhe.github.io/nfdicore/): core ontology that describes all resouces (datasets, data providers, persons, projects and other entities) in the data domain of NFDI. It serves as the basis for further domain specific ontologies, e.g. nfdi4culture ontology, nfdi4matwerk ontology, and contains mappings to numerous external vocabularies and ontologies. See also the [abstract presented at CoRDI 2023](https://www.tib-op.org/ojs/index.php/CoRDI/article/view/371/520) and the related [NFDI4Culture Ontology](https://nfdi4culture.de/ontology)

- [QUDT](https://qudt.org/) Ontology collection about Quantities, Units, Dimensions and Data Types for science and engineering ([catalogue 2.1](https://www.qudt.org/2.1/catalog/qudt-catalog.html)), originally developed for the NASA Exploration Initiatives Ontology Models (NExIOM) project. It includes schemas (e.g. [classes of QUDT](https://www.qudt.org/2.1/catalog/qudt-catalog.html): Quantity, QuantityKind, QuantityKindDimensionVector, Unit) and vocabularies (e.g. individuals of [QuantityKind](https://www.qudt.org/doc/DOC_VOCAB-QUANTITY-KINDS.html), [QuantityKindDimensionVector](https://www.qudt.org/doc/DOC_VOCAB-DIMENSION-VECTORS.html), [Unit](https://www.qudt.org/doc/DOC_VOCAB-UNITS.html)) within various systems of quantity kinds (e.g. ISQ) and units (e.g. SI), including conversion factors for inferred conversion between units.

## Initiatives | Consortia

- [NFDI4Ing](https://www.nfdi4ing.de/): Initiative to build an open and FAIR infrastructure for research data management in engineering.
- [NFDIMatWerk](https://nfdi-matwerk.de/): Initiative to build an open and FAIR infrastructure for research data management in materials science.
- [NFDI4Chem](https://www.nfdi4chem.de/): Initiative to build an open and FAIR infrastructure for research data management in chemistry.

## Related Compilations

- [MatPortal](https://matportal.org/): Collection of ontologies used in materials science.
- [awesome materials informatics](https://github.com/tilde-lab/awesome-materials-informatics/edit/master/README.md): overview of software, data and initiatives in the field of materials informatics.
- [awesome chemical data](https://github.com/neo-chem/awesome-chemical-data): overview of chemical and materials data resources.

## Credits

Some initial collections curated from [awesome-materials-informatics](https://github.com/tilde-lab/awesome-materials-informatics), [awesome-chemical-data](https://github.com/neo-chem/awesome-chemical-data) and [awesome-chemistry-datasets](https://github.com/kjappelbaum/awesome-chemistry-datasets/tree/main).

