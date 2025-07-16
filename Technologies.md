<img src="https://github.com/NIH-NCPI/.github/blob/main/profile/ncpi-logo-close-crop.png" width="40" alt="NCPI Logo"/> [Home](https://github.com/NIH-NCPI)/[Resources](README.md)/Technologies

<h1> Technologies </h1>

> NCPI members are exploring or implementing the following technologies in support of cloud platform interoperability.

<h2> Researcher Auth Service (RAS) </h2>

Researcher Auth Service (RAS) is an effort by the NIH's Center for Information Technology (CIT) to provide a common mechanism by which researchers can establish their identity and access data they are authorized to use across the systems outlined above. The RAS Application Programming Interface (API) allows seamless access to researchers for integrated data repositories.

Using RAS, a researcher accessing NIH data resources can log in with their eRA Commons credentials and then access any integrated repository without having to log in again. Existing rules for authorization will be enforced so a user can only access data they are authorized to view.

RAS uses open standards and protocols and provides integrating systems with many standards-based options for integration. RAS is part of the NIH CIT IAM General Support System (GSS), a Federal Information Security Management Act (FISMA) High system. As such, RAS adheres to NIST 800-53 and 800-57 guidelines pertaining to configuration management, least privilege, and cryptographic key establishment & management.

* For more information about RAS across NIH, see [Researcher Auth Service Initiative](https://datascience.nih.gov/researcher-auth-service-initiative). 
* For detailed documentation of the RAS API see [Researcher Auth Service (RAS) Project Service Offerings](https://auth.nih.gov/docs/RAS/serviceofferings.html).

<h2> Data Repository Service (GA4GH DRS) </h2>

The Global Alliance for Genomics and Health (GA4GH) Data Repository Service (DRS) provides a generic interface to data repositories so data consumers—including workflow systems—can access data objects in a single, standard way regardless of where they are stored and how they are managed.

The primary functionality of DRS is to map a logical ID to a means for physically retrieving the data represented by that ID. There are two styles of DRS URIs—Hostname-based and Compact Identifier-based—both using the `drs://` URI scheme. The API defines the characteristics of those IDs, the types of data supported, how they can be pointed to using URIs, and how clients can use these URIs to ultimately make successful DRS API requests.

* For more information on the most recent version of this API (1.4), see the [Data Repository Service 1.4 Documentation](https://ga4gh.github.io/data-repository-service-schemas/preview/release/drs-1.4.0/docs/).

<h2> Fast Healthcare Interoperability Resources (FHIR) </h2>

Fast Healthcare Interoperability Resources (FHIR) is a standard describing data formats and elements (known as “resources”) and an API for exchanging electronic health records (EHR). As patients move around the healthcare ecosystem, their electronic health records must be available, discoverable, and understandable across systems. Further, to support automated clinical decision support and other machine-based processing, the data must also be structured and standardized.

The FHIR standard was created by HL7 using a modern web-based suite of API technologies, including an HTTP-based RESTful protocol, HTML/CSS for user interface integration, a choice of JSON, XML, or RDF for data representation, and Atom for results.

One of its goals is to facilitate interoperation between legacy health care systems; to make it easy to provide health care information on a wide variety of devices (from computers to tablets to cell phones); and to allow third-party application developers to provide medical applications that integrate into existing systems.

* For more information and a definition of the FHIR standard, see [HL7 FHIR Release 5](https://www.hl7.org/fhir/overview.html).
* For more information on NCPI FHIR Resources, see [FHIR Resources](FHIR-Resources.md)

<h2> Portable Format for Bioinformatics (PFB) </h2>

The Portable Format for Bioinformatics (PFB) is an [Avro](https://avro.apache.org/docs/current/)-based file format that bundles schema, data, ontologies/controlled vocabularies, and pointers to data files in a single, serializable package. It can be sent easily across systems and has the flexibility for different data models.

PFBs are used to bring search results from hosted datasets into workspace environments that users can leverage for computational analysis.

* [pyPFB](https://github.com/uc-cdis/pypfb/#readme) is a Python library and CLI to create, view, and edit PFB files.
* For more information on the PFB format and schema, see the [pyPFB documentation](https://github.com/uc-cdis/pypfb/blob/master/docs/detailed_pfb_doc.md).

<h2> Workflow Execution Service (WES) </h2>

Reproducibility of research is key to open science. Developed by the GA4GH Cloud Work Stream, the Workflow Execution Service (WES) API describes a standard protocol for running the same genomic data analysis in different environments and obtaining the same results. Rather than transferring data across national and institutional bounds—a process that is cumbersome, resource-intensive, and limited by regulatory constraints—the WES API is part of a larger framework to bring algorithms to genomic data.

* For more information on this service, see the [Workflow Execution Service (WES) documentation](https://www.ga4gh.org/product/workflow-execution-service-wes/).
