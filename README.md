# Asset Annex Requirements
## Definitions
### Artifact
An artifact is a physical file, such as an executable binary, an archive (e.g. *.zip, *.tar), a document, a source code file, a text or configuration file.

### Component
A component is a group of one or more artifacts. While artifacts are physical files, the component can be regarded as logical aggregate. Licensing information applies on component-level and is consistent within the aggregated artifacts.

### Associated License
An artifact can be obtained under different licenses depending on context or channel in which the artifact is made available or transferred. These licenses are associated with the artifact when downloading or receiving the artifact and are referred to as associated licenses. 

### Effective License
In contrast to the associated licenses, the effective licenses are the licenses under which the artifact is further distributed. The associated and effective licenses of an artifact can differ, but are restricted by the terms of the associated licenses. 
The effective licenses are the licenses relevant for the software distribution:
- An artifact is associated with a dual or multiple licensing option where either one or the other license can be used for distribution. In this case a single effective license needs to be determined.
- An artifact is associated with a license in a specific or later version. In this case a version of the license has to be selected as effective license.
- The associated license of an artifact allows to sublicense the artifact under a different license. In this case the chosen license is the effective license.

### Asset
An asset means software, hardware or the combination of software and hardware. Assets are either used internally or distributed to one or more recipients. Depending on context and individual relationship between the provider and recipient the license terms have to be addressed. 

### Asset Annex
The asset annex contains information to support conformity to legal and regulatory requirements, licenses, and organizational policies. The asset annex aggregates all information required to fulfill the obligations when using, making available or transferring the asset. It covers the following elements:
•	The associated and effective license terms and notices of the individual artifacts and components (inventory; bill of materials).
•	The source code of components if demanded by the effective license.
•	Licenses and notices as demanded by the effective licenses.

## Primary Requirements
1.	The Asset Annex contains a complete list of artifacts and components the asset consists of. Each component is listed - within a bill of materials - with name, version, associated license(s), and its individual artifacts.
2.	The Asset Annex documents the effective licenses of all components included in the asset.
3.	The Asset Annex contains a general description of the license types. In particular, specific aspects concerning warranties and disclaimers for the given license types are detailed.
4.	The Asset Annex documents component classifications with respect to import / export.
5.	The Asset Annex documents component restrictions and implications with respect to patents.
6.	The Asset Annex documents trademarks and trademark restrictions.
7.	The Asset Annex includes notices to support conformity to the obligations resulting from the effective licenses.
8.	The Asset Annex contains the license terms covering the effective licenses. The licenses are preserved (in accordance to the terms of the licenses) as individual files and are organized by license / component. The inclusion of the license files of associated licenses is optional.
9.	The Asset Annex contains notices with respect to known vulnerabilities and exploits. In case a scoring metric is available the scores are documented. If required by regulation, a vulnerability assessment is documented. Vulnerabilities and exploits that have to be addressed by additional measures are documented. Detected vulnerabilities and exploits, which are not applicable for the asset are documentation as such.
10.	The Asset Annex contains additional notice files to support conformity to the license obligations.
11.	The Asset Annex functions as reference. As such, it allows to
    - access a list of all effective licenses
    - access a list of all components with a given effective license
    - access a list of prioritized vulnerabilities and exploits
    - access a list of component classifications with respect to import/export
    - access a list of restrictions with respect to patents
    - access a list of trademark and trademark restrictions
12.	The Asset Annex contains either a written offer (in documentation) or the source code (as archive file) for components with licenses demanding the provisioning of source code.
13.	The Asset Annex contains a glossary with the central terms and definitions.
14.	The Asset Annex contains the Asset Inventory in machine readable form.


## License
Creative Commons Attribute-NoDerivatives 4.0 International
- Copyright (c) 2019 Karsten Klein, metaeffekt GmbH
- Copyright (c) 2019 Thomas Schulte, metaeffekt GmbH
