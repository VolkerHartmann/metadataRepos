## Evaluation Matrix

Status: 15.02.2022

| Function              | [AIMS](aims/atAGlance.md) | [Ckan](ckan/atAGlance.md) | [Cordra](cordra/atAGlance.md) | [Coscine](coscine/atAGlance.md) | [DSpace](dspace/atAGlance.md) | [Fedora](fedora/atAGlance.md) | [Gerdi](gerdi/atAGlance.md) |[Invenio](invenio/atAGlance.md) | [MetaStore](metastore/atAGlance.md) | [MyCoRe](mycore/atAGlance.md) | [OSF](openScienceFramework/atAGlance.md) | [Zenodo](zenodo/atAGlance.md) |
| ---------------------:| :-----------------------: | :-----------------------: | :---------------------------: | :-----------------------------: | :---------------------------: | :---------------------------: | :-------------------------: | :----------------------------: | :---------------------------------: | :---------------------------: | :--------------------------------------: | :---------------------------: |
| Register Schema       | +                         | -                         | (+)[^1]                       | +                               |  -                            | -                             | -                           | -                              | +                                   | +                             | -                                        | -                             | 
| Update Schema         | +                         | -                         | (+)[^2]                       | +                               |  -                            | -                             | -                           | -                              | +                                   |                               | -                                        | -                             | 
| Validate Schema       | (+)[^3]                   | -                         |  -                            | (+)[^3]                         |  -                            | -                             | -                           | -                              | +                                   | +                             | -                                        | -                             | 
| Ingest Metadata       | +                         | +                         |  +                            | +                               |  +                            | +                             | +                           | +                              | +                                   | +                             | +                                        | +                             | 
| Update Metadata       |                           | +                         |  +                            | +                               |  +                            | +                             | +                           | +                              | +                                   | +                             | +                                        | +                             | 
| Validate Metadata     | +                         | (+)[^4]                   |  +                            | +                               |  -                            | -                             | +                           | -                              | +                                   |                               | -                                        | -                             | 
| Search by ...         |                           |                           |                               |                                 |                               |                               |                             |                                |                                     |                               |                                          |                               | 
| ... Administrative MD | +                         | +                         |  +                            | +                               |  +                            | +                             | +                           | +                              | +                                   | +                             | +                                        | +                             | 
| ... Content           |                           | (+)[^5]                   |  +                            | (+)[^6]                         |  -                            | +                             | +                           | -                              | (+)[^7]                             | +                             | -                                        | -                             | 
| Persistent Identifier | (+)                       | +                         |  +                            | +                               |  +                            | +                             | +                           | +                              | +[^8]                               | +                             | +                                        | +                             | 

For more detailed information please use the links in the table header.

{{#include featureDescription.md }}

---
**Footnotes**

[^1]: Support for arbitrary (JSON Schema) via configuration only (-> restricted to administrators)

[^2]: Manually by administrators

[^3]: Syntax check

[^4]: Via 'scheming' plugin with a rudimentary schema format

[^5]: Via 'DataStore' plugin (supports SQL queries)

[^6]: Planned

[^7]: Via enhanced service

[^8]: PID via enhanced service


