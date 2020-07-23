# SCHEMA
SCHEMA (Semantic Schema Mapping for Interoperable Data-Exchange) is a project to enable organisations to export and import data in an interoperable manner by using semantic mappings to identify a common schema base for representing the data.


## repo structure

- `schemas`: registry of schemas describing the exported/imported datasets
- `mappings`: mappings between schemas for transforming data
- `matching-alignment`: code for performing ontology matching and alignment on target ontology to identify suitable common or specialised ontology
- `transformers`: code for transforming non-semantic data to semantic data; and to execute mappings
- `data-example`: example datasets