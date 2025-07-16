<img src="https://github.com/NIH-NCPI/.github/blob/main/profile/ncpi-logo-close-crop.png" width="40" alt="NCPI Logo"/> [Home](https://github.com/NIH-NCPI)/[Resources](README.md)/Introduction to FHIR

<h1> Introduction to FHIR </h1>


<img src="https://github.com/NIH-NCPI/Resources/blob/main/Images/FHIR-logo.png"
     align="right"
     alt="HL7 FHIR Logo"
     width="415"
     height="100" />

<br> Fast Healthcare Interoperability Resources (FHIR) is a standard for exchanging electronic healthcare information developed by Health Level Seven International (HL7).

FHIR defines data elements called **Resources**—such as `Patient`, `Observation`, or `Specimen`—and outlines their structure and sharing via web technologies like RESTful APIs, JSON, and XML. Its modular design supports interoperability across diverse health information systems.

<h2> NCPI and FHIR </h2>

NCPI uses FHIR as a common standard for research data exchange, supporting the NCPI's goal of FAIR data principles (Findable, Accessible, Interoperable, and Re-usable). The work of the NCPI FHIR Working Group also focuses on defining an NCPI FHIR Implementation Guide to provide a common data model for describing NCPI data sets. This standardization simplifies the integration and analysis of data from varied research studies.

<h2> NCPI FHIR Resources </h2>

- [**NCPI FHIR Implementation Guide (IG)**](https://github.com/NIH-NCPI/ncpi-fhir-ig-2?tab=readme-ov-file)  
  The *NCPI FHIR Implementation Guide v2* (NCPI FHIR IG v2) provides specifications, building blocks, interaction models, and use cases for FHIR within NCPI. It details study data structuring with specific FHIR Resource Types to ensure compliance and interoperability across NCPI platforms. A contributors guide is also available.

- [**NCPI FHIR Aggregator**](https://fhir-aggregator.readthedocs.io/en/latest/)
  The NCPI FHIR Aggregator is a centralized catalog for FHIR data from various biomedical resources, such as clinical data, research study information, and OMICS data tied to specimens. Researchers can use it to search for patient phenotypes and associated data across these diverse sources. Learn more about the [FHIR Aggregator].

- [**fhir-query tool**](https://github.com/FHIR-Aggregator/fhir-aggregator-client)  
  The `fhir-query` (or `fq`) command-line tool, a companion to the aggregator, simplifies interactions with FHIR servers. It assists in retrieving server vocabularies and executing queries to filter and pull FHIR resources.

<h2> Learn More </h2>

To learn more about FHIR and its research applications:

- [Introduction to FHIR for Research](https://datascience.nih.gov/fhir-initiatives/introduction-to-fhir-for-research)
- [FHIR for Researchers Training](https://datascience.nih.gov/fhir-initiatives/researchers-training)
