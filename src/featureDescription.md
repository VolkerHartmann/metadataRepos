### Description 
- **Register Schema:**
  - Support for arbitrary schemas of a specific format (e.g. JSON Schema, XSD)
  - The schema should at least be referencable by a unique identifier.
- **Update Schema:**
  - Possibility to 
    - work on different versions of a schema 
    - adapt schemas over time
- **Validate Schema:**
  - Check schema for correct syntax
- **Ingest Metadata:**
  - Store metadata (document) in repository
    - Ideally with previous validation 
- **Update Metadata:** 
  - Possibility to update already ingested metadata (documents).
- **Validate Metadata:**
  - Possibility to validate documents on the basis of registered schemas.
- **Search by Administrative MD:**
  - Search documents by their metadata (e.g. ingest date, ingester, ...)
- **Search by Content:**
  - Search documents by their content
- **Persistent Identifier:**
  - Support for Persistent Identifiers (e.g. DOI, Handle)

