## dkNET FAIR Rich Metadata Specification for Datasets (F2.0)
V1.2

Author:  Maryann E. Martone (ORCID: 0000-0002-8406-3871)
Adapted from:  The NIDDK Information Network (dkNET): RRID:SCR_001606
Details provided at:  https://docs.google.com/spreadsheets/d/1UhXDwwIcIKlN4BRO3X_JODP23pNBuGPd_pKqPN0ZL0Y/edit?usp=sharing

## Metadata elements

Title of dataset: 

Author(s):

Author(s) ORCID:

Data contributors + roles:

Contact:

Contact information:

Dataset description:

Data repository:  Name of repository where data was deposited

Data repository RRID

Dataset ID: DOI or database accession number

Full dataset citation: 

Data publication (if any): DOI or PubMed ID

Study publication (if any): DOI or PubMed ID

Data files included

Version

Release date

Consortium or Project collecting the data

Consortium or Project RRID

Grant support

Keywords:


Data license:

Data access:

Dataset parts description:

Dataset part ID’s

Dataset parts repositories

Community standards used:



Study organism

Condition studied

Number of subjects studied

Sex of subjects

Age of subjects (range or categorical, e.g., adult)

Protocol type

Protocol ID

----------------------------------------

Here is additional specifications with some extra information from past workshops conducted by the International Neuroinformatics Coordinating Facility:


TIER 1 - Generic Dataset Metadata

Element Name / Description
Element ID
Requirement Level
Title of dataset:
schema:name
REQUIRED
Dataset description
schema:description
REQUIRED
Version
schema:version
REQUIRED
Dataset contributors
Name [Required]
identifier - ORCID [Recommended]
email - [Recommended]
Affiliation - [Recommended]
Address - [Optional]
Webpage - [Optional]

schema:author,
schema:contributor,
schema:director,
schema:creator,



REQUIRED
Contact:
schema:contactPoint
REQUIRED
Dataset DOI or other primary URI
schema:sameAs
REQUIRED
Data repository: Name of repository where data was deposited
schema:publisher
OPTIONAL
Dataset ID: database accession number and other alternated identifiers
* This handles additional identifiers (e.g. accession numbers) and is handled by identifier propertyTypes
schema:identifier
OPTIONAL
Distributions
URL - DataDownload.contentURL [REQUIRED]
Name - DataDownload.name
Size - DataDownload.contentSize
Date Published - DataDownload.datePublished
Data Modified - DataDownload.dateModified
Measurement Type [OPTIONAL]

schema:DataDownload
RECOMMENDED
Associated Publications
DOI/ISBN - schema:sameAs [REQUIRED]
Publication Type: schema:role [REQUIRED]
Identifiers (e.g. PubMed) schema:identifier [OPTIONAL]
Basic publication info [OPTIONAL]

schema:CreativeWork
RECOMMENDED, if available
Funding Acknowledgement
Sponsor -> Organization / Person
Name [Required]
Identifier [Recommended]
Email [Optional]
Address [Optional]
Identifier [Recommended]
Name [Optional]

schema:grant
RECOMMENDED
Data license
Name (schema:name) [REQUIRED]
Text (schema:text) [ RECOMMENDED]
URL (schema:sameAs) [REQUIRED]

schema:license
REQUIRED
Data access restrictions




keywords
schema:keywords
OPTIONAL
URL
schema:url
REQUIRED
























TIER 2 - Generic Neuroscience Metadata




Element Name / Description
Element ID
Requirement Level
Community standards used




Variables Measured / Dimensions
schema:variableMeasured
[OPTIONAL]
Assay (i.e. type of experiment performed)










Minimal Information for Neuroscience Data Standard (MINDS)
http://incf.github.io/minds-schema/


age range




sex




species




strain




disease




brain regions




Protocol










Minimum Information about a Neuroscience Investigation (MINI): Electrophysiology
http://precedings.nature.com/documents/1720/version/1/files/npre20081720-1.pdf


Cell type / line




Equipment




Development Stage




Task / Paradigm










ARRIVE guidelines
https://www.nc3rs.org.uk/arrive-guidelines


Ethical Review




Subject Weight Range




Subject Genetic Modification Status (e.g. knock-out or transgenic)




Subject Genotype




Experimental Groups




Sample Sizes










Minimal Information for Neural ElectroMagnetic Ontologies
http://nemo.nic.uoregon.edu/wiki/NEMO


Native Language










Minimum Information About a Spinal Cord Injury experiment
http://www.regenbase.org/miasci-online.html


Surgery / Procedure




Common Metadata Elements for Cataloging Biomedical Datasets
https://figshare.com/articles/Common_Metadata_Elements_for_Cataloging_Biomedical_Datasets/1496573


Data Location (i.e. host)




Organ / Tissue










Data Tag Suite
https://datatagsuite.github.io/docs/html/


Spatial Coverage




Refinement




Availability




Aggregation




Privacy




Molecule




Biological Entity




Material




Selection Criteria






















TIER 3 - Domain Specific Metadata




Element Name / Description
Element ID
Requirement Level
Metadata standard/Data model




URI




key:value
















UN-REVIEWED SUGGESTIONS




Element Name / Description
Element ID


Suggested Items
Not Reviewed


Cost
schema:isAccessibleForFree


Has Part
ID
Description

schema:hasPart


Is part of
schema:isPartOf


Thumbnail image
schema:thumbnailUrl


Images
schema:imageObject


Schema Version
schema:schemaVersion


Additional Type
schema:additionalType




























