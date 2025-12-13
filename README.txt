README
License: CC BY 4.0
Version 1.0
Date: 2025-12-08

Field:

Cultural Heritage Preservation

Subfield:

GIS Applications and Spatial Data Practices

Contributors:

Rosalia Iriye, UCLA, https://orcid.org/0009-0007-8510-216X
Jack Morrissey, UCLA, https://orcid.org/0009-0007-0377-510X
Catherine Whalen UCLA, https://orcid.org/0009-0005-8820-7878

Project Description:

This is a Data Curation Domain Profile (DCP) for the field of Cultural Heritage Preservation with a subfield of Geographic Information Systems (GIS) Applications and Spatial Data Practices. Our goal was to deliver a dataset of one hundred open access articles published between 2020 and 2025 accompanied by a DCP and to deposit our work in an appropriate repository.

Data Dictionary:

Initial dataset coding template was provided in the Fall 2025 “Data Management and Practice” class at University of California, Los Angeles, then modified for our specific study area.

+--------------------------------------+-----------------------------------------------------------+
| Contributor                          | Last name of contributor who found article and completed  |
|                                      | corresponding data columns.                               |
+--------------------------------------+-----------------------------------------------------------+
| DOI/URL                              | DOI of journal article, formatted using standard prefix   |
|                                      | https://doi.org/ appended with the DOI number or link as  |
|                                      | presented by corresponding online publication.            |
+--------------------------------------+-----------------------------------------------------------+
| Title                                | Title of journal article, formatted as it appeared in     |
|                                      | corresponding online publication.                         |
+--------------------------------------+-----------------------------------------------------------+
| Author                               | Names of author(s) of corresponding journal article,      |
|                                      | formatted as shown in online publication.                 |
+--------------------------------------+-----------------------------------------------------------+
| Journal                              | Title of journal that published corresponding article.    |
+--------------------------------------+-----------------------------------------------------------+
| Publisher                            | Publisher of journal contained in previous column.        |
+--------------------------------------+-----------------------------------------------------------+
| Publication Year                     | Year corresponding journal article was published.         |
+--------------------------------------+-----------------------------------------------------------+
| Data Collected                       | All qualitative and quantitative data types collected in  |
|                                      | corresponding journal article, most often found in        |
|                                      | "Methods" section, but frequently present in multiple     |
|                                      | sections. All data types were appended with the term      |
|                                      | "data" when format was not specified. See "Data Cleaning  |
|                                      | and Standardization" below for additional information.    |
+--------------------------------------+-----------------------------------------------------------+
| Data Deposited (Federer et al.)      | Strict interpretation of Federer et al.'s Data            |
|                                      | Availability Statement (DAS) coding categories, applied   |
|                                      | only to information provided within the DAS (not the      |
|                                      | actual state of data availability throughout the          |
|                                      | article). In the case of articles without Data            |
|                                      | Availability Statements, the category "Other" was listed. |
+--------------------------------------+-----------------------------------------------------------+
| DOI/URL of Data Deposit              | DOI or URL of data deposited (depending on method of      |
|                                      | deposit), as found within article.                        |
+--------------------------------------+-----------------------------------------------------------+
| Data Repository                      | Name of the repository or repositories where article data |
|                                      | was deposited.                                            |
+--------------------------------------+-----------------------------------------------------------+
| DOIs of Data Paper (other citations) | In instances of data paper citation, DOI(s) or full       |
|                                      | hyperlinks to websites contained within article.          |
+--------------------------------------+-----------------------------------------------------------+
| Funding Source                       | Funding source of article, as described in "Funding"      |
|                                      | section. In instances of no noted sponsorship or no       |
|                                      | external sponsorship, “None (not listed)” or “None (no    |
|                                      | external funding)” were listed, respectively.             |
+--------------------------------------+-----------------------------------------------------------+
| Country of Study                     | Country where research contained within the article took  |
|                                      | place. In the case of multi-country studies, the term     |
|                                      | "Global" was listed, and additional context was provided. |
|                                      | Example: "Global; 992 UNESCO World Heritage Sites"        |
+--------------------------------------+-----------------------------------------------------------+
| Province/Municipality                | To provide a more complete picture of GIS applications    |
|                                      | and spatial data use in cultural heritage preservation    |
|                                      | research, specific province/municipality names associated |
|                                      | with research performed in China were listed due to the   |
|                                      | high frequency of studies done in this country. If        |
|                                      | province information was not included in the article      |
|                                      | itself, it was found online by looking up the city, town  |
|                                      | or cultural site contained within the corresponding       |
|                                      | paper.                                                    |
+--------------------------------------+-----------------------------------------------------------+
| Software Used                        | The various forms of software used for geospatial         |
|                                      | analysis in the corresponding article. Version was        |
|                                      | included when provided. For the most prevalent software   |
|                                      | types, ArcGIS and QGIS, the word "version" was written in |
|                                      | between the software type and version number. If no       |
|                                      | version was provided in instances of ArcGIS or QGIS       |
|                                      | software use, "version unspecified" was noted after the   |
|                                      | software type. Examples: "ArcGIS version 10.8;" "QGIS     |
|                                      | version unspecified."                                     |
+--------------------------------------+-----------------------------------------------------------+

Article Collection:

An initial sampling of articles was collected by surveying JSTOR, ResearchGate, Semantic Scholar and UC Libraries for relevant journals, using combinations of the search terms "GIS," "Cultural Heritage" and "Preservation" and filtering results to only include open source articles published within the 2020-2025 date range. This initial sampling allowed contributors to identify more prevalent open access journals with histories of publishing research covering the intersection of GIS applications/spatial data practices and cultural heritage preservation. All contributors selected three journals and attempted to pull an even number of articles from each, randomly selecting entries that matched the agreed upon search criteria. Two of the selected journals did not offer enough published articles to meet our requirements. In these instances, our searches were expanded to facilitate the project goal. In total, one hundred articles were sourced from nine open access journals.

Data Entry:

Our overarching guideline for selecting and extracting data from articles was to include all available data, even when superfluous data was available. For example, contributors included full names of all authors as they appeared in articles rather than abbreviating or using the primary author's last name and et al. In the instance of multiple terms per cell, terms were separated with semicolons and unnecessary spaces after entries were removed. This was done in an effort to make the data machine readable once our dataset was complete. In the interest of user readability, all first words of entries within cells and after semicolons were capitalized. For links to deposited data, full hyperlinks to corresponding repositories or web pages were included, making them directly accessible via the dataset itself.

Data Cleaning and Standardization:

Our data cleaning efforts were primarily aimed at streamlining variabilities in repeat instances of spatial data types. Data types were initially entered as they appeared in articles, resulting in many different terms referencing the same concepts. Contributors used Exploratory Data Analysis and a glossary of common GIS data types to consolidate overlapping terminology. The term "historical" was used to replace the word "historic" wherever it appeared, as "historical" was favored by the vast majority of researchers. The term "institutional" was initially incorporated as an antecedent to data from overly specific public and private sources. Where possible, data of this nature was ultimately replaced with more useful descriptive terminology. Addressing additional inconsistencies in instances of certain spatial data types, the following terms were used to standardize nomenclature and abbreviations: Close Range Photogrammetry (CRP) photogrammetric data; Computer-Aided Design (CAD) data; Digital Elevation Model (DEM) data; Digital Surface Model (DSM) data; Digital Terrain Model (DTM) data; Electrical Resistivity Tomography (ERT) data; Ground Penetrating Radar (GPR) data; Light Detection and Ranging (LiDAR) data; Synthetic Aperture Radar (SAR) data; Terrestrial Laser Scanner (TLS) data; Uncrewed Aerial System (UAS) photogrammetric data; Unmanned Aerial Vehicle (UAV) photogrammetric data. Further, the terms "photos" and "orthophotos" were replaced with "photography" and "orthophotography," respectively. After discovering minimal overlap in research sponsorship, contributors did not pursue data cleaning in “Funding Source” column beyond standardizing instances of “None (not listed)” or “None (no external funding).” Finally, instances of the most prevalent software, ArcGIS and QGIS, that provided version numbers were clearly delineated using the term "version" before the version number, and those without versions were appended with "version unspecified."

User Guidance:

We hope that our dataset will prove useful to researchers who are interested in exploring how GIS applications and spatial data practices can be used in the field of cultural heritage preservation.
