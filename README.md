# Medieval Manuscript Data Integration Ontology (MMDIO)

This repository contains all the resources related to the Medieval Manuscript Data Integration Ontology (MMDIO), developed using the MeLOn methodology.

## Repository Structure

- **data/**: Contains the MMDIO schema and RDF database.
- **diagrams/**: Contains the ontology diagram.
- **docs/**: Contains the HTML LODE published file.
- **sparql/**: Contains the competency questions for each use case and general questions and queries.

## Description

### Data Folder

The `data` folder includes:
- **mmdio_schema.owl**: The schema for the Medieval Manuscript Data Integration Ontology.
- **rdf_database.rdf**: The RDF database containing the extracted data according to the MMDIO schema.

### Diagrams Folder

The `diagrams` folder includes:
- **ontology_diagram.png**: The visual representation of the MMDIO, created using Graffoo.

### Docs Folder

The `docs` folder includes:
- **lode_published.html**: The HTML file published with LODE, documenting the ontology.

### SPARQL Folder

The `sparql` folder includes:
- **competency_questions_use_cases.sparql**: SPARQL queries addressing competency questions for each use case.
- **general_questions.sparql**: SPARQL queries addressing general questions.

## Usage

1. **Ontology Visualization**:
   - The ontology was visualized using Graffoo and modeled in Protégé.
   
2. **Data Integration**:
   - Data was extracted according to the MMDIO schema, converted into RDF triples, and tested in GraphDB.

3. **Publication**:
   - The ontology was documented and published with LODE.

## Enhancements

This process has enhanced data integration for the Mosaico and Irnerio platforms by providing a structured and comprehensive ontology for medieval manuscript data.

## Contact

For any questions or issues, please contact [faria.ferooz2@unibo.it](mailto:faria.ferooz2@unibo.it).
