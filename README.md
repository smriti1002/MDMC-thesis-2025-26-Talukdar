# MDMC-thesis-2025-26-Talukdar
This repository consists the work related to the partial fulfillment of the completion fo the course of MDMC 2025-26

# Thesis Repository — FAIR-by-design data modeling for Hydrogen Research Infrastructures

## Overview

This repository contains the research outputs produced in the context of the 
thesis titled *"FAIR-by-design data modeling for hydrogen research infrastructures"*
developed at Area Science Park
that includes
the Data Management Plan (DMP) 
drafted for the hydrogen laboratory under development, as well as the HydLab
ontology — a hierarchical domain-specific OWL ontology for the semantic modelling 
of hydrogen research infrastructures.

Both outputs were developed following a FAIR by design approach, ensuring that 
all research data and metadata are Findable, Accessible, Interoperable, and 
Reusable from the earliest stages of the research infrastructure's development.

---

## Repository Structure

| Path | Description |
|------|-------------|
| `dmp/` | Data Management Plan document and associated resources |
| `ontology/hydlab.ttl` | HYDLAB ontology — canonical Turtle source |
| `ontology/hydlab.owl` | OWL/RDF XML serialisation — auto-generated |
| `ontology/hydlab.jsonld` | JSON-LD serialisation — auto-generated |
| `scripts/` | Python scripts for ontology conversion and documentation generation |
| `docs/index.html` | Human-readable HTML documentation of the ontology |

---

## HYDLAB Ontology

**Namespace:** `https://purl.org/hydlab/ns#`  
**Prefix:** `hydlab:`  
**Version:** `v1.0.0`  
**Persistent Identifier:** [Zenodo DOI — to be added upon publication]

HYDLAB is a domain-specific layered OWL ontology developed for the semantic 
modelling of hydrogen research infrastructures. It was derived from the Piping 
and Instrumentation Diagram (P&ID) of the hydrogen laboratory under development 
at the institution, and aligns with the following external ontologies:

| Prefix | Ontology | Used for |
|--------|----------|----------|
| `schema:` | Schema.org | Organization, ResearchOrganization |
| `sosa:` | W3C SOSA | Sensor, observes, madeSampling |
| `ssn-system:` | W3C SSN Systems | Frequency |
| `emmo:` | EMMO | Device (Electrolyzer, ElectrochemicalDevice) |
| `oeo:` | Open Energy Ontology | HydrogenPowerPlant |
| `qudt:` | QUDT | ElectricPotentialDifference |
| `om:` | Ontology of Units of Measure | hasUnit |
| `dcterms:` | Dublin Core | isPartOf, metadata annotation |
| `skos:` | SKOS | broadMatch, concept |

---

## Data Management Plan

The DMP was drafted following the CERN DMP template and developed through 
a consultative process involving the review of official institutional documentation, 
engagement with the laboratory's engineering consultants, and direct involvement 
with senior laboratory management. It follows the FAIR by design structure and 
is intended to serve as a living document, to be updated as the hydrogen 
laboratory evolves.

---

## License

All contents of this repository are released under the 
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

You are free to share and adapt the material for any purpose, provided 
appropriate credit is given, a link to the license is provided, and any 
changes made are indicated.

---

## Citation

If you use or build upon the contents of this repository, please cite:

[Your Name]. (2026). *FAIR by Design data modeling for
Hydrogen Research 

Infrastructures*. Area Science Park
DOI: [Zenodo DOI — to be added upon publication]

---

## Contact

Smritirekha Talukdar
Area Science Park
smritirekha.talukdar@areasciencepark.it
