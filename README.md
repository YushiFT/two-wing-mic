<img src="https://user-images.githubusercontent.com/46493113/186980876-c0f19069-589f-4f51-bdfb-12014ca3ff0b.png" width="100%"></img>

Reference Information and Reproducible Analysis
=====================

Provenance for this README
--------------------------

* File name: README.md
* Author: Yushi Tang
* Other contributors: Donghui Wen
* Date created: 2022-08-15
* Date modified: 2022-08-25

Roproducible Analysis
---------------------

* Source: <https://github.com/YushiFT/two-wing-mic/tree/main/docs/two_wing_reproducible_analysis.Rmd>
* Output: <https://github.com/YushiFT/two-wing-mic/tree/main/docs/two_wing_reproducible_analysis.pdf>


Dataset Version and Release History
-----------------------------------

* Current Version:
  * Number: 1.0
  * Date: 2022-08-15
  * Persistent identifier: [manuscript under review]

Dataset Attribution and Usage
-----------------------------

* Dataset Title: Two-Wing-Structure Dataset

* Persistent Identifier: [manuscript under review]

* Dataset Contributors:

  * Creators: Yushi Tang and Donghui Wen

* Date of Issue: 2022-08-15

* Publisher: Peking University

* License:
  * Title: Creative Commons Attribution 4.0 International (CC BY 4.0)
  * Specification: <https://creativecommons.org/licenses/by/4.0/>

* Suggested Citations:

  * Dataset citation:
    > Tang, Y., Chen, W., Su, Z., Wei, J., Zheng, Y., Xiong, F., Chen, L., Wen, D. The *Two-Wing* admixed structure of environmental microbial communities. (2022) (under review)

Contact Information
-------------------

* Primary Contact:
  * Name: Yushi Tang
  * Affiliation: Princeton University
  * ORCID ID: 0000-0002-3809-2129
  * Email: yushi.tang@princeton.edu

* Primary Contact:
  * Name: Donghui Wen
  * Affiliation: Peking University
  * ORCID ID: 0000-0002-1301-989X
  * Email: dhwen@pku.edu.cn

* Contributor ORCID IDs (see above)

- - -

Methodological Information
==========================

* Methods of data collection: The data were collected following the procedures developed by Wen Lab at Peking University, as detailed in Tang Y. et al. (2022) (under review).

* Methods of data processing: Raw measurements were compiled into one CSV with minimal processing, as detailed in "two_wing_structure_cookbook.pdf".

* Software-specific information: The dataset and codebook do not require any specific software to read and reuse, but the data package follows the Frictionless Data framework, which has libraries for multiple languages: <https://frictionlessdata.io/tooling/libraries/#data-package>.

- - -

Additional Dataset Metadata
===========================

Acknowledgements
----------------

* Funding source: General Project Nos. 51678003 and 51678334 of Natural Science Foundation

Relations to Other Datasets and/or Publications
-----------------------------------------------

* References for replication code for the dataset and related analyses:
  * Tang, Y., Chen, W., Su, Z., Wei, J., Zheng, Y., Xiong, F., Chen, L., Wen, D. The *Two-Wing* admixed structure of environmental microbial communities. (2022) (under review)

 
Dates and Locations
-------------------

* Dates of data collection: start=2015-04-01; end=2015-04-30

* Geographic locations of data collection: Hangzhou Bay, Zhejiang, PRC 

- - -

Data and File Overview
======================

Summary Metrics
---------------

* File count: 5
* Total file size: 4.8 MB
* Range of individual file sizes: 9 KB - 3.2 MB
* File formats: TXT, CSV, JSON, PDF

Naming Conventions
------------------

* File naming scheme: Each file name has three fields, delimimited by underscores (followed by the file extension):
    1. Project shorthand: "TMEN" in all cases
    2. Content type: "RawData"; "README"; "DataPackageDescriptor"; or "Codebook"
    3. Date of latest revision to the file by the creators

Table of Contents
-----------------

* TMEN_README_2021-03-15.txt, 9 KB
* TMEN_RawData_Bacteria_Species_2021-03-15.csv, 152 KB
* TMEN_RawData_Archaea_Species_2021-03-15.csv, 22 KB
* TMEN_DataPackageDescriptor_2021-03-15.json, 1.5 MB
* TMEN_Codebook_2021-03-15.pdf, 3.2 MB

- - -

File Details
============

Details for: README_2021-03-15.txt
----------------------------------------------

* Description: This is the README file you are reading right now--the introduction to the dataset and accompanying documentation files.

* Format:
  * Extension: .txt
  * Media type: text/plain
  * Encoding: UTF-8

* Size: 9 KB

Details for: TMEN_RawData_Bacteria_Species_2021-03-15.csv
-----------------------------------------------

* Description: This file represents the dataset itself; all other files are documentation for the dataset.

* Format:
  * Extension: .csv
  * Media type: text/csv
  * Encoding: UTF-8
  * Standard: RFC 4180 (<https://tools.ietf.org/html/rfc4180>)

* Size: 152 KB

* Dimensions: 1406 rows; 36 columns

* Variables:
  * The first line contains variable names as column headers.
  * The full details on all variables, including naming schemes, descriptions and value types, are contained in the data package and the codebook.

* Missing data codes: Missing values are left blank in all cases.

* Other encoding details:
  * A comma is used as the record separator and CRLF as the line break (per RFC 4180).
  * All string values are enclosed in double quotes (some contain punctuation, but none contain quotation marks)
  * Timestamps follow the ISO 8601 standard (<https://www.iso.org/standard/70907.html>; see also <https://en.wikipedia.org/wiki/ISO_8601>).

Details for: TMEN_RawData_Archaea_Species_2021-03-15.csv
-----------------------------------------------

* Description: This file represents the dataset itself; all other files are documentation for the dataset.

* Format:
  * Extension: .csv
  * Media type: text/csv
  * Encoding: UTF-8
  * Standard: RFC 4180 (<https://tools.ietf.org/html/rfc4180>)

* Size: 22 KB

* Dimensions: 168 rows; 36 columns

* Variables:
  * The first line contains variable names as column headers.
  * The full details on all variables, including naming schemes, descriptions and value types, are contained in the data package and the codebook.

* Missing data codes: Missing values are left blank in all cases.

* Other encoding details:
  * A comma is used as the record separator and CRLF as the line break (per RFC 4180).
  * All string values are enclosed in double quotes (some contain punctuation, but none contain quotation marks)
  * Timestamps follow the ISO 8601 standard (<https://www.iso.org/standard/70907.html>; see also <https://en.wikipedia.org/wiki/ISO_8601>).


Details for: TMEN_DataPackageDescriptor_2021-03-15.json
--------------------------------------------------------------

* Description: Following the Frictionless Data Specs (<https://frictionlessdata.io/specs/>), this JSON file serves as a "descriptor" to allow one to work with the dataset as a "data package" (<https://specs.frictionlessdata.io/data-package/>). It contains much the same information as in this README and the accompanying codebook--i.e., thorough metadata, variable details, and comprehensive information on value types--but in a machine-readable format.

* Format:
  * Extension: .json
  * Media type: application/json
  * Encoding: UTF-8
  * Standard: STD 90 (<https://tools.ietf.org/html/std90>)

* Size: 1.5 MB

* Other encoding details:
  * Generated using the Data Package Creator browser tool (<https://create.frictionlessdata.io/>), with "Profile" set to "Data Package."

Details for: TMEN_Codebook_2021-03-15.pdf
------------------------------------------------

* Description: This codebook provides comphrensive documentation for the all of the variables and values in the dataset in a human-readable form. This includes variable naming schemes, labels and descriptions for all variables (including some descriptive statistics), as well as details on all value types and units of measurement.

* Format(s):
  * Extension: .pdf
  * Media type: application/pdf
  * Standard: ISO 32000 (<https://www.iso.org/standard/51502.html>; see also <https://www.loc.gov/preservation/digital/formats/fdd/fdd000277.shtml>)

* Size: 3.2 MB

* Pages: 72

- - -
END OF README
