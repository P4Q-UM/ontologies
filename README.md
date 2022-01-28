# P4Q Ontologies
This repository contains the ontologies used in the Precise4Q project used for harmonizing data.

## General ontologies
The top-level ontologies contains and restricts general concepts that should be extended by the domain ontologies representing each dataset:

 - [*btl2.owl*](https://biotopontology.github.io/) is the highest level ontology used for harmonization. It is a top-domain ontology that provides definitions for the foundational entities of biomedicine as a basic vocabulary to unambiguously describe facts in this domain. BioTop can be used as top-level model for creating new ontologies for more specific domains or as aid for aligning or improving existing ones.
 - *SCTHRCMJULY18.owl* is a module containing the most general concepts from SNOMED CT, which is the clinical ontology used in this project for representing clinical data.
 - *SCT-BTL2MAPPING.owl* contains the axioms that make SNOMED CT compatible with BTL2 ontology, as SNOMED CT concepts are classified under BTL2 top-level elements.
 - *SemanticDataModel.owl* contains the concepts and the restrictions used for defining the graph structure for representing clinical data.
 - *Precise4Q.owl* contains common concepts used by the concrete ontologies representing each domain, such as "days since injury" or "age at lesion".

## Domain ontologies
The domain ontologies extend the general ontologies in order to represent a more concrete domain:

 - *Barthel.owl* contains the concrete concepts for representing the Barthel index.
 - *Bateria.owl* contains the concrete concepts for representing the Bateria evaluation.
 - *Conditions.owl* contains the concrete concepts for representing diagnosis.
 - *EVSF.owl* contains the concrete concepts for representing the "Escala de Valoración Socio-Familiar" (EVSF).
 - *FIM.owl* contains the concrete concepts for representing the Functional Independence Measure (FIM).
 - *FuglMeyer.owl* contains the concrete concepts for representing the Fugl-Meyer evaluation.
 - *GNPT.owl* contains the concrete concepts for representing the Guttmann Neuro Personal Trainer (GNPT).
 - *RiksStroke.owl* contains the concrete concepts for representing the Swedish register for stroke care.