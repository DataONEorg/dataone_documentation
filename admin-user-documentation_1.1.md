>Suzie created the bulk of this document back in 2011. She sent it to me on 23 July 2019, and I thought that it was a good place to start for this documentation. She originally created it in a Word file. I have edited it for clarity and ease of reading, updated some of the information and all the links, included images, and rendered it into Markdown. I've also included my own notes about gaps in documentation, suggested ideas based on my own experiences and on my conversation with Amy Schuler from the Cary Institute/Figshare repo, and requests for clarification.

**Purpose:** to provide data administrators and/or potential Member Nodes with a quick overview of DataONE, including the benefits, responsibilities, costs, technical specifications, and architecture involved with participating as a MN in DataONE.

**Audience:** administratively-focused people at institutions such as libraries, research centers, data repositories, government and non-profit organizations. These individuals may or may not be technically literate, but likely have access to people with technical proficiency, such as advisors, supervisors, and IT support.

# Top Level Outline

<!-- Start Document Outline -->

* [1. Participating in DataONE: A General Overview](#1-participating-in-dataone-a-general-overview-1)
	* [1.1. What is DataONE and How Can You Participate?](#11-what-is-dataone-and-how-can-you-participate-1)
	* [1.2. What would DataONE Mean for Your Institution?](#12-what-would-dataone-mean-for-your-institution-1)
	* [1.3. What are the Potential Benefits for Your Institution?](#13-what-are-the-potential-benefits-for-your-institution-1)
	* [1.4. What are the Roles, Responsibilities, and Requirements for Your Institution?](#14-what-are-the-roles-responsibilities-and-requirements-for-your-institution-1)
	* [1.5. What are the Costs Involved for Your Institution?](#15-what-are-the-costs-involved-for-your-institution-1)
	* [1.6. What are the Services Available for Your Institution?](#16-what-are-the-services-available-for-your-institution)
	* [1.7. What are the Technical Requirements for Your Institution?](#17-what-are-the-technical-requirements-for-your-institution)
		* [Bandwidth](#bandwidth-1)
		* [Storage Capacity](#storage-capacity-1)
		* [Connectivity](#connectivity-1)
		* [Status Checks](#status-checks-1)
	* [1.8. Who Needs to Be Involved?](#18-who-needs-to-be-involved)
* [2. Participating In DataONE: A Detailed Report](#2-participating-in-dataone-a-detailed-report-1)
	* [Data and Metadata](#data-and-metadata-1)
	* [System Metadata](#system-metadata-1)
	* [Identifiers](#identifiers-1)
	* [DataONE Preservation Strategy](#dataone-preservation-strategy-1)
	* [DataONE Cybersecurity](#dataone-cybersecurity-1)
	* [Content Discovery](#content-discovery-1)
	* [Event Logging and Reporting](#event-logging-and-reporting-1)
	* [Implementation](#implementation-1)
	* [DataONE Application Programming Interfaces (APIs)](#dataone-application-programming-interfaces-apis-1)
	* [Time and Bandwidth Constraints](#time-and-bandwidth-constraints-1)
	* [Investigator Toolkit](#investigator-toolkit-1)
	* [License and Copyright Policy](#license-and-copyright-policy-1)
* [3. User Scenarios by Institution](#3-user-scenarios-by-institution)
	* [Libraries](#libraries-1)
	* [Research Centers](#research-centers-1)
	* [Data Repositories](#data-repositories-1)
	* [Government Organizations](#government-organizations-1)
	* [Non-Profits](#non-profits-1)
* [Glossary](#glossary-1)

<!-- End Document Outline -->

# 1. Participating in DataONE: A General Overview

## 1.1. What is DataONE and How Can You Participate?
<a href="https://www.dataone.org/" target="_blank">Data Observation Network for Earth (DataONE)</a> is a federation of repositories for environmental and ecological science data and metadata (descriptions of data) that helps meet the needs of science and society for open, persistent, robust, and secure access to well-described and easily discovered Earth observational data. Supported by the U.S. National Science Foundation (Phase 1 Grant <a href="https://nsf.gov/awardsearch/showAward?AWD_ID=0830944" target="_blank">#ACI-0830944</a>, Phase 2 Grant <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1430508" target="_blank">#ACI-1430508</a>), DataONE's goal is the preservation, access, use, and reuse of multi-scale, multi-discipline, and multi-national scientific data through a distributed framework, sustainable cyberinfrastructure, and education and outreach programs. 

There are three major components in the DataONE cyberinfrastructure: Member Nodes which represent data repositories, Coordinating Nodes which serve data management and discovery services, and the Investigator Toolkit which contains a variety of end user tools for interacting with the infrastructure. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>)

![](Research-User%20Documentation%20Overview/ReferenceArchitecture.png)  
*Figure 1.* An overview of the major components of DataONE architecture.

Your institution can participate in DataONE by becoming a DataONE Member Node. Through the implementation of the DataONE Member Node service interface, your institution can expose your data within the DataONE federation. In addition to scientific data, Member Nodes can provide computing resources, or services such as data replication, to the DataONE community. (from "Member Nodes": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>).

## 1.2. What would DataONE Mean for Your Institution?
DataONE provides your institution with a framework to support open, persistent, robust and secure access to well described and easily discovered data about life on earth and the environment that sustains it. ~~This includes biological data from genome to ecosystem, as well as data from atmospheric, ecological, hydrological and other earth sciences.~~ Becoming a Member Node of the DataONE federation supplies your institution with the infrastructure to store and provide access to your institution’s digital scientific holdings and to also make these data available to a much broader community. Your institution can opt to host its own data, or to partner with other data holders or repositories. Your institution also has the freedom to use a variety of standards or formats to describe and store your data.  

As a DataONE Member Node, your institution would report its metadata to a DataONE Coordinating Node, which choreographs services that help users store, discover, and retrieve data. The Coordinating Node provides a host of other services, including facilitating replication and preservation of data objects, authorization and authentication, and data discovery. In essence, DataONE acts a partner in helping to facilitate your institution’s implementation of a data management strategy and showcasing your institution’s intellectual capital.

Additionally, DataONE's Investigator Toolkit provides scientists, researchers, and students with a suite of powerful tools for finding, using and storing data on the DataONE federation. The Investigator Toolkit includes tools for data searching, desktop data file management, data integration and analysis, among many others. You can find the complete, detailed list of tools available in the Investigator Toolkit at <a href="https://www.dataone.org/investigator-toolkit" target="_blank">https://www.dataone.org/investigator-toolkit</a>.  

## 1.3. What are the Potential Benefits for Your Institution?
* Improved methods of access to your data, as well as wider access to and exposure of those data.  
* Cost-effective preservation of your data and metadata.
* Access to a larger community with expertise and best practices in data life cycle management.
* A toolkit for analysis, visualization and modeling your data.
* A response to increasing demands by funding agencies for long-term data management planning.
* Visibility as a community leader in supporting open and rapid access to scientific data.
* Recognition and credit for data and services provided through data citations in published literature.
* Opportunities for collaborative research.
* Potential funding opportunities resulting from data discovery.
* Showcase for your institution’s intellectual capital.

## 1.4. What are the Roles, Responsibilities, and Requirements for Your Institution?
* Provide access to actively managed data.
* Allow replication of data for preservation and increased access.
* Provide descriptive metadata to Coordinating Nodes to facilitate data discovery, access and usability.
* Ensure availability and reliability of physical data access.
* Engage with the larger DataONE community to advance DataONE services, support emerging Member Nodes, and promote best practices in data management.
* Utilize a unique identifier for each dataset by participating in DataONE user identity federation.
* Deploy an implementation of DataONE APIs (Application Programming Interfaces).
* Have an identifier system to uniquely identify data items within the Member Node.

## 1.5. What are the Costs Involved for Your Institution?
This section should outline the estimated costs involved in becoming a DataONE MN, as well as the long-term costs for maintaining a MN with DataONE.

## 1.6. What are the Services Available for Your Institution?
This section should outline the various services offered to DataONE Member Nodes, such as issue tracking and tech support. If DataONE decides to begin charging fees for various services, this section should be combined with the above section (1.5.) on costs and include the various price points for each service. 

>*NOTE 1:* The following information comes from the Overview section in the API documentation: <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>. I thought it could be included here, but I wasn't sure.
>
>As a DataONE Member Node, your institution would have access to several fundamental services upon which additional infrastructure, services, applications and communities may be built. These core, community building services include:
> 
> * Promotion of data preservation through automated replication of data and metadata.
> * Support for arbitrary globally unique identifiers with guaranteed resolution and dereferencing.
> * Extensible search and discovery services.
> * Federated management of user identities and access control.

>*NOTE 2:* Here's information on proposed value added services from the User Scenarios section in the API documentation: <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/userscenarios.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/userscenarios.html</a>. Some of this could be included as well.
>
>DataONE is not the end, but rather the means to enable scientists and citizens to address and better understand the difficult and complex biological, environmental, social, and technological challenges affecting human, ecosystem, and planetary sustainability. The comprehensive cyber-infrastructure allows novel questions to be asked that require harnessing the enormity of existing data and developing new methods to combine and analyze diverse data resources (see Figure 2 below).
>
>DataONE will accomplish its goals by making scientists, students, librarians, and citizens active participants in the data life cycle, especially the data preservation process. By supporting community derived interoperability standards and incorporating new value-added and innovative technologies (e.g., for semantic and geospatial information, scientific workflows, and advanced visualization) into the scientific process, DataONE will facilitate sophisticated data integration, analysis, interpretation, and understanding. A strong education and outreach program focuses on scientists and students learning to better and more easily manage, preserve, analyze, and visualize Earth observational data. Citizen scientists are actively engaged in data preservation and scientific discovery through their involvement in programs such as the USA National Phenology Network (USA-NPN) and numerous Cornell Laboratory of Ornithology citizen science efforts (e.g., eBird, Project FeederWatch).
>
>![](Research-User%20Documentation%20Overview/proposal_figure_2.png)  
>*Figure 2.* DataONE value-added services enable scientists to address novel questions through integrating disparate data sources (top), supporting geospatial data processing (lower left), and providing scientific workflow solutions like Kepler (lower middle) and high-level analyses and visualizations like IBM ManyEyes.

## 1.7. What are the Technical Requirements for Your Institution?
### Bandwidth
Your institution’s bandwidth level should be at least on a local 10base-T connection (10 Mbps) to a local backbone operating at T1 or higher rates (about 1.5 Mbps). This level of bandwidth should allow a gigabyte file to be transferred in approximately 2-4 minutes. DataONE recognizes that network capabilities around the world vary (e.g., Internet backbone bandwidth and network reliability vary between countries), and these expectations serve as guidelines rather than as fixed requirements.

### Storage Capacity
Ideally, your institution will participate in the cooperative replication scheme supported by DataONE, which means you will store copies of data from other Member Nodes. A good rule of thumb is that your institution should expect to provide additional storage capacity equivalent to the capacity dictated by replication expectation for your own data. For example, if you bring 100GB of data to the DataONE federation, and its replication policy requires that two copies of each dataset be stored somewhere in the DataONE federation, your institution's Member Node should in all fairness expect to provide 200GB of storage capacity over and above the original 100GB. DataONE recognizes that some institutions may have extreme resource limitations, so this expectation of additional storage capacity is not an absolute requirement for participation in DataONE. 

### Connectivity
Reliable, high-capacity connectivity contributes to good performance, and DataONE expects that your institution will be available via the network 99.9% of the time. This level of availability provides for about 8.5 hours of unscheduled downtime per year.

### Status Checks
One of the core services of DataONE operations is a testing service that runs tests to check conformance with API specifications, as well as stress tests to gauge performance. The service generates a report detailing overall functionality. These tests will be performed on a regular basis to ensure that your institution’s Member Node is operating as expected. This service performs routine status checks to detect if your node becomes inaccessible, and automatically updates routing information to avoid directing clients to attempt connecting to your institution’s node when it may not be accessible.

## 1.8. Who Needs to Be Involved?
Institutions need to be aware of the people they will need to have in place to help them implement and maintain a DataONE MN. This section should note who the institution needs to involve, and could offer different user scenarios based on the type of institution. 

> NOTE: Amy's draft of MN Deployment Process starts to outline the required expertise for implementation: <a href="https://docs.google.com/document/d/16_gWL-0GnrDf1nOdRrmscJ5Rv3wTjH72NDqeb4NuWLA/edit#heading=h.gjdgxs" target="_blank">https://docs.google.com/document/d/16_gWL-0GnrDf1nOdRrmscJ5Rv3wTjH72NDqeb4NuWLA/edit#heading=h.gjdgxs</a>

## 1.9. How Much Time is Involved in Becoming a Member Node?
It's important for people to have a sense of the time investment that it may take to become a MN. Therefore, this section should offer estimated time frames for how long it will take an institution to become a Member Node. This could offer different user scenarios, based on the different implementation routes.

# 2. Participating In DataONE: A Comprehensive Overview
DataONE has a core infrastructure that supports content replication, identifier resolution, content discovery and retrieval, and a federated identity infrastructure. The Investigator Toolkit also contains several components widely used by the community. This report offers a high-level overview of the DataONE architecture to inform those who are making the decision to implement a DataONE Member Node at their institution. Full documentation of the services and tools is available at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/index.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/index.html</a>. 

>Note: There are multiple versions of the Architecture documentation in multiple locations. When you select the final destination for the most recent version, update the link above.

## Data and Metadata
DataONE defines **data** as a discrete unit of digital content that represents information obtained from an experiment or scientific study. The data is accompanied by **science metadata**, which is a separate unit of digital content that describes properties of the data. Each unit of science data or science metadata is also accompanied by a **system metadata** document that contains attributes that describe the digital object it accompanies (e.g. hash, time stamps, ownership, relationships). (from <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/WhatIsData.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/WhatIsData.html</a>)

Science metadata may be written in a variety formats, which are outlined in detail at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/WhatIsData.html#metadata-types" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/WhatIsData.html#metadata-types</a>.

Operationally, science data and metadata are stored on a Member Node and a copy of the science metadata is held by the Coordinating Node in order to facilitate the discovery process as people search for content. The data package contains the science data, science metadata, and system metadata, which is described in detail in the next section.

![](Research-User%20Documentation%20Overview/datapackage_class.png)  
*Figure 3.* Components of a data package.

## System Metadata
System metadata is used by DataONE to track and manage objects across the distributed network of Coordinating and Member Nodes. It is considered operational information and is needed to run DataONE. It is critical to ensuring that science data, science metadata, and other digital objects stored in DataONE are discoverable, accessible, auditable, verifiable, and are associated with meaningful related digital objects. Digital objects in DataONE must also be viable for the long term - for many decades - and so the system metadata must also include provenance information.

System metadata describes managed objects such as science data, science metadata, and resource map objects by identifying low level elements (e.g. size, type, owner, access control rules) and the relationships between objects (e.g. describes and describedBy). System metadata have some elements that are provided by the client software  including the low level elements. Other elements are generated by DataONE during the course of managing objects and include information about provenance and replication. System metadata is maintained by the Coordinating Nodes and reflects the current state of an object in the system. Full documentation about system metadata is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadata.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadata.html</a>. Details about the generation of system metadata associated with a data object and its associated science metadata is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SysmetaLifecycle.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SysmetaLifecycle.html</a>.

System metadata is indexed to support access control rules for search results, support efficient discovery of objects by their properties, and augment the science metadata indexes. Three indexes support this: the permission index, system index and discovery index. Complete information about the indexing process can be found at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SearchMetadata.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SearchMetadata.html</a>

>NOTE: This was the original link Suzie included in her document: http://mule1.dataone.org/ArchitectureDocs-current/design/indexing_systemmetadata.html. I could not locate it, so I replaced it with the above link to the Content Discovery section in the API doc. Not sure if this is right, though.  

More details about preservation metadata related to system metadata is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html</a>.  

## Identifiers
Identifiers are handles utilized as a mechanism to specifically identify the individual objects (documents, data sets, data records) that they manage. Identifiers refer to objects in DataONE. Initially data and science metadata documents describing data have identifiers. The definition of an individual data object may be a single record within some larger collection, or may refer to an entire set of records contained within some package. Full documentation on identifiers is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/PIDs.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/PIDs.html</a>.

Uniqueness of identifiers in DataONE is largely under the control of the Member Nodes, with the requirement that an existing identifier cannot be reused. DataONE treats the original identifier (i.e. the first assignment of the identifier to an object that becomes known to DataONE) as the authoritative identifier for an object. 

Identifiers utilized by Member Nodes can take many different forms, from automatically generated sequential or random character strings to strings that conform to schemes such as the LSID and DOI specifications. DataONE does not directly utilize implied functionality and services that might be available for some of the identifier schemes. DataONE's infrastructure and services operate independently of such external services, with no functional dependency. An identifier that has been registered by DataONE will always refer to the same set of bytes in the case of data and metadata objects. Generation of other representations of the objects may be supported by services (e.g. an image may be transformed from TIFF to JPEG), but the identifier will always refer to the original form.

A fundamental goal of DataONE is to ensure that any identifier utilized in the system is resolvable. That is, DataONE provides a method that will enable retrieval of the bytes associated with the object (the actual object bytes or metadata associated with the object). Resolution is handled by the Coordinating Nodes through the `CNCore.resolve()` method, which returns a list of nodes from which the object may be retrieved. A guarantee of identifier resolvability is an important, core function of the DataONE infrastructure upon which many other services may be constructed, both within DataONE and by third party systems. 

## DataONE Preservation Strategy
DataONE’s preservation goal is to protect the content, meaning, and behavior of data sets registered in its global network of Member Nodes. This is a complex undertaking that warrants a layered, prioritized approach. To get started on a solid footing, our first objective was to build a platform that immediately provides a significant degree of preservation assurance and makes it easy to add more sophisticated preservation function over time. Initially, DataONE’s focus is on preventing loss due to non-malicious causes, such as,
* Technological obsolescence (e.g., loss of support for rendering software and hardware),
* Accidental loss (human error, natural disaster, etc.), and
* Financial instability (loss of funding).

To meet the objective of “easy, secure, and persistent storage of data,” DataONE adopts a simple, three-tiered approach.
1.	**Keep the bits safe.** Retaining the actual bits that comprise the data is paramount, as all other preservation and access questions are moot if the bits are lost. Key sub-strategies for this tier are (a) persistent identification, (b) replication of data and metadata, (c) periodic verification that stored content remains uncorrupted, and (d) reliance on member nodes to adhere to DataONE protocols and guidelines consistent with widely adopted public and private sector standards for IT infrastructure management.
2.	**Protect the form, meaning, and behavior of the bits.** Assuming the bits are kept undamaged, users must also be able to make sense of them into the future, so protecting their form, meaning, and behavior is critical. In this tier we rely on collecting characterization metadata, encouraging use of standardized formats, and securing legal rights appropriate to long-term archival management, all of which supports future access and, as needed to preserve meaning and behavior, format migration and emulation.
3.**	Safeguard the guardians.** If the DataONE federation and its Member Nodes were to disappear, that would be equivalent to 100 percent data loss. The DataONE federation itself provides resiliency against the occasional loss of Member Nodes, and this will be shored up by succession planning, ongoing investigations into preservation cost models, and open-source software tools that can sustained by external developer communities.

Information about preservation metadata related to system metadata is available at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html#requirement-2-perform-preservation-migration" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html#requirement-2-perform-preservation-migration</a>

More information about DataONE's Preservation Strategy is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/PreservationStrategy.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/PreservationStrategy.html</a> 

## DataONE Cybersecurity
Cybersecurity for DataONE is part of the initial system planning and design, thereby providing solid integration to all services. The design is based on the fact that DataONE is a collaboration of researchers, data providers, institutions, Coordinating Nodes, Member Nodes, data collections, and other infrastructure components. Therefore, DataONE, as an entity, spans many organizations and administrative domains. The primary goal of DataONE cybersecurity is to protect the data and metadata collections that those organizations and administrative domains contribute, as well as their infrastructure and the DataONE user community.  

DataONE recognizes that your institution must simultaneously meet local requirements and must also integrate into the DataONE cyberinfrastructure. To meet these diverse requirements and needs, DataONE has designed cybersecurity management that is flexible and can support the wide-ranging needs of each Member Node. 

The bottom line is that DataONE security is focused on protecting data in the Member Node at your institution from intentional and non-intentional harm; for example, unauthorized viewing of private data and or alteration or deletion of another user's data. System operations are also protected from malicious activity that often occurs on the Internet. For detailed descriptions of the multiple institutional cybersecurity scenarios in DataONE, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-institutional-components" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-institutional-components</a>.

Security in DataONE consists of two processes: 
1. **Authentication**, which verifies the identity of users
2. **Authorization**, which applies rules that govern access to system resources (e.g., data). 

Authentication is the process of determining whether or not a user is who they say they are. DataONE relies on both end-users and servers (the Member Nodess and Coordinating Nodes) to use X.509 certificates to authenticate themselves, and relies on CILogon to provide certificates to end-users.

The use of CILogon has two main advantages for your institution. First, you can use existing accounts to obtain certificates, so you don’t need to create and remember another username and password combination. Second, once you have downloaded the certificate, it will secure connections with all DataONE nodes throughout the day, and can be used by multiple DataONE applications. This technique is known as single-sign-on. It also means your institution has full control over who may view or modify your data by defining your own local authorization rules, which will be propagated and enforced by DataONE. More information about authentication can be found at <a href="https://releases.dataone.org/online/api-dhttps://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.htmlocumentation-v2.0.1/design/AuthorizationAndAuthentication.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html</a>.

Authorization is the process for confirming whether a user has privileges to access a resource in DataONE. It provides privacy and access control to user contributed data and metadata, as well as protects DataONE services and resources at both the coordinating and Member Nodes. In order to serve the many administrative domains and political boundaries represented throughout DataONE member and Coordinating Nodes, a “trust” relationship is crucial. Therefore, access control rules that are defined by your institution are honored by other DataONE members. The language that specifies the policy for a given access control rule dictates only whether a user is allowed access to a given resource. This includes the ability to explicitly deny access to a resource overly complicates managing the authorization process, which is seldom used in practice. Rules will consist of the system identity of the user, the type of permission granted (e.g., read, write, and or execute), and the identifier of the resource being requested. DataONE will provide, where reasonable, a conversion of the internal access control rule to a subset of one or more industry standard policy languages to support interoperability between different organizations

Further details about authorization, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/Authorization.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/Authorization.html</a>. You can also access a primer outlining the specific differences between authorization and authentication at: <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html</a>.

In conclusion, the cybersecurity posture of DataONE will evolve over time both because of the continuing maturation of DataONE operational strategies and because of an ever-evolving cybersecurity landscape. You can access DataONE's full Cubersecurity Plan at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-cybersecurity-plan" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-cybersecurity-plan</a>.

## Content Discovery
Searching for content is primarily the responsibility of DataONE Coordinating Nodes. Content searches are accomplished using a web browser interface that utilizes a SOLR index to support search operations. The SOLR index content includes system metadata, science metadata and resource maps. The basic model is that each index entry represents information about a single identifier (PID). For PIDs that refer to a science data object, the index entry will be constructed from system metadata and resource maps that reference the object. If the PID refers to a science metadata object, the index entry will have fields populated with content extracted from the science metadata document. There is also a requirement that search results only contain information that the user has permission to read. This means that access permissions for each item in the search is examined. 

Your institution specifically benefits from this system because the content in the SOLR index can be used to created data citations that follow established best practices. This provides a means for your institution to get credit for providing access to the data. 

A full description of the SOLR index, how it is populated, and how it can be used to support programmatic search of the DataONE holders can be found at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SearchMetadata.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SearchMetadata.html</a>.

>*NOTE:* We might consider providing a brief explanation about how metadata standards affect searchability of content and appearance of metadata records in DataONE Search here. This could link to a new section in the API documentation that addresses this in more detail and could provide examples of MNs that have implemented diffrent MD standards. Or some kind of guide that walks people through different versions of MD: "If you want your MD to look like this, use these standards."

## Event Logging and Reporting
The DataONE logs various interactions and operations in the system to provide operational status information about the entire system, to report on specific node operations, and to inform DataONE participants (users, contributors, administrators) about their specific domain of interest in the system. For example, your institution might like to monitor use of your data and where it is being replicated to. You can find more informaiton about event logging at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/logging.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/logging.html</a>.

## Implementation
Your institution can participate in DataONE as a Member Node through three different strategies:
1. **Native service support**: Implement the DataONE Member Node service APIs as part of the existing data repository application interfaces. Native Member Node implementations currently exist for Metacat, with Dryad close to completion, and support for Fedora Commons in the works.
2. **Proxy service**: Utilize a proxy service that offers a translation layer between the DataONE service interfaces and existing service interfaces exposed by a repository. A proxy service (the "Generic Member Node" or GMN) written in Python and based on the Django web framework is also available with implementation examples for Dryad and ORNL DAAC.
3. **Standalone service**: Deploy a standalone Member Node software stack and perform custom synchronization of content between the Member Node data store and the existing data repository. The GMN can also operate as a flexible standalone Member Node service.

DataONE has implementation examples of each that can be used directly or as examples to assist with new implementations. DataONE has a liberal open source policy, so all source code can be re-purposed as necessary to assist with new deployments.

In general there should be little to no impact on your existing operations. Existing data repositories can continue to operate in parallel with the Member Node services. Aspects that may see some impact include restriction on identifiers being used (to ensure global uniqueness), how the repository works with content that may be replicated to it from another Member Node, and there will be some additional connectivity demand to support the necessary network communications.

If your institution should choose to no longer be part of the DataONE federation, decommissioning is technically as simple as turning the node off. However, a more controlled approach is desirable and would ensure that the data remains in a stable state. At least a week before the shutdown, your institution’s Member Node administrator should inform DataONE of the impending change. The Coordinating Nodes will perform the synchronization and ensure that data objects are replicated as necessary. All content that was replicated up to this point will continue to be available through the Coordinating Node and other Member Nodes. 

>*NOTE:* Suzie got this information from this resource: https://docs.dataone.org/member-area/planning-for-dug/dug-general-documents/member-node-documents-final-versions/MNTechnicalDoc2010Dec03.docx/view. I cannot access this document because I need a DataONE user account to do so. Therefore, I'm currently unable to check for currency of the points presented in this section. I'll check with her to see if she can get me a copy of the doc.

>*NOTE 2:* Information about the implementation process is available in the DataONE Operations documentation, but it's currently incomplete: <a href="https://dataone-operations.readthedocs.io/en/latest/MN/deployment/implementation_planning.html" target="_blank">https://dataone-operations.readthedocs.io/en/latest/MN/deployment/implementation_planning.html</a>. Specific info on existing MN implementations is listed as "TODO." 

## DataONE Application Programming Interfaces (APIs)
DataONE has application programming interfaces (APIs) available that support interaction between Member Node and Coordinating Node, and support development of applications that interact with the DataONE infrastructure, such as elements of the Investigator Toolkit. All services in DataONE are implemented using a RESTful approach with HTTPS (or HTTP) as the transport protocol and XML for encoding messages.

As a Member Node, your institution can choose from four different tiers, each with varying levels of content exposure to the DataONE community. The tiers and Member Node APIs necessary to support are summarized in the table below. Also indicated are the corresponding Coordinating Node APIs that are necessary for the functions expressed for each tier.

|Tier |Description |MN APIs |CN APIs |
|----------|----------|----------|----------|
| 1 | Public read, no authentication or access control of content. No content can be created through the DataONE service interfaces. The node cannot act as a replication target. | MNCore, MNRead | CNCore, CNRead |
| 2 |Read and resolve with access control support. | Tier 1 + MNAuthorization | 	CNAuthorization, CNRegister, CNIdentity |
| 3 | Write (create, update, delete), possibly limited support for data types. | Tier 2 + MNStorage | Column 2 |
| 4 | Replication target. The types of content supported by the node may be limited to a subset of object formats.| Tier 3 + MNReplication| CNReplication |

Member Node APIs provide mechanisms to report the level of service compliance and to specify replication policies. There are also APIs to monitor the current state of the DataONE infrastructure and to track the current operation state of associated Member Nodes. Member Node APIs include the core API, Read API, Authorization API, Storage API, and Replication API.  Complete information is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/apis/MN_APIs.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/apis/MN_APIs.html</a>.

Coordinating Node APIs include the the core API, Read API, Authorization API, Storage API, and Replication API.  Complete information is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/apis/CN_APIs.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/apis/CN_APIs.html</a>.

Investigator Toolkit APIs [No specific description available] Complete information is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/apis/ITK_APIs.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/apis/ITK_APIs.html</a>.

## Time and Bandwidth Constraints
Because the DataONE architecture relies on the performance of the Coordinating Nodes, the transfer rate between Coordinating Nodes was tested to establish the rates of data acquisition, the size of data objects, and the number of simultaneous users supported.   

This means your institution’s Member Node should have individual data objects that are small enough to be easily transferred across the network to other nodes. Data objects on the order of Megabytes or (low) Gigabytes are reasonable, while data objects on the order of Terabytes will not work well.

Additionally, your institutions’s bandwidth should be at least a local 10base-T connection (10 Mbps) to a local backbone operating at T1 or higher rates (about 1.5 Mbps). This level of bandwidth should allow a gigabyte file to be transferred in approximately 2-4 minutes.

Full documentation regarding these constraints can be found at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/notes/time_bandwidth_constraints.html?highlight=bandwidth" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/notes/time_bandwidth_constraints.html?highlight=bandwidth</a>.

## Investigator Toolkit
The Investigator Toolkit provides a suite of software tools that are useful for DataONE users. The tools categories are (1) web portals and tools, (2) metadata and data management tools, (3) analysis and modeling tools, and (4) DataONE libraries. Documentation about the investigator toolkit is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-overview.html</a>.

**Web portals and tools:** The Investigator Toolkit provides a suite of software tools that are useful for the various audiences that DataONE serves. Current tools available are the DataONE Search Portal and the DataONE System Monitoring Portal. For more information, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-web.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-web.html</a>.

>*NOTE:* Need to provide descriptions for both portals.

**Metadata and data management tools:** 

>*NOTE:* Nee to provide overview of these <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-metadata.html#metadata-and-data-management-tools" target="_blank">tools</a> and a description of the <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-metadata.html#metacat-web-registry" target="_blank">Metacat web registry</a>. 

**Analysis and modeling tools:** Quantitiative analysis is at the center of all science, and represents the main point where scientists utilize data and produce derived data products. Thus, the analysis and modeling tools in the Investigator Toolkit will represent the most important suite of tools for accessing data from DataONE and contributing results to the DataONE Member Nodes. For a complete list of analysis and modeling tools, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-analysis.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-analysis.html</a>

>*NOTE:* Need to provide descriptions of <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-matlab.html" target="_blank">Matlab</a>, <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-vistrails.html" target="_blank">VisTrails</a>, and <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-kepler.html" target="_blank">Kepler</a>. 

**DataONE libraries:** The Investigator Toolkit provides a set of libraries that can be used for making custom software that interacts with the DataONE infrastructure.

.*NOTE:* Need to provide descriptions of <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-java-lib.html" target="_blank">Java</a> and <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/itk-python-lib.html" target="_blank">Python</a> Libraries.

## License and Copyright Policy
DataONE is developing software and distributing software that originates from multiple institutions that each have their own policies governing copyright and licensing of software. As a project, we are committed both philosophically and through our cooperative agreement with NSF to distribute our work as open source software. However, we must do so within the guidelines provided by each of our institutions. 

DataONE software products have been and will continue to be jointly designed and created by individuals spread across the DataONE participating institutions. No one individual or institution claims creative ownership of any of the DataONE software products. Therefore, the general policy is that each DataONE software product contains a copyright statement that indicates that all of the participating organizations hold joint copyright in the work.

DataONE is committed to open science and open source principles, so all software developed will be licensed under an approved open source license. Because different open source licenses can have implications for the re-use and distribution of that software, we do have a general policy that guides choice of licenses. However, we also recognize that existing software that we may wish to use may already contain existing open source licenses that can not be changed easily or at all, and we do not want as a matter of policy to exclude the use of these open source products. We recognize the benefits of various open source licenses, but as a general policy DataONE will use the Apache 2.0 open source license for all newly developed code: http://www.opensource.org/licenses/apache2.0.php.

Each DataONE product includes a copyright and license statement in a file at the root of the source and binary distributions and in each source code file that reads:
> This work was created by participants **in** the DataONE project, **and is** jointly copyrighted by participating institutions in DataONE. For more information on DataONE, see our web site at http://dataone.org.  
>
>   Copyright 2010  
>
>Licensed under the Apache License, Version 2.0 (the "License"); you **may not** use this file **except in** compliance **with** the License. You may obtain a copy of the License at  

>http://www.apache.org/licenses/LICENSE-2.0  
>
>Unless required by applicable law **or** agreed to **in** writing, software distributed under the License **is** distributed on an **"AS IS"** BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express **or** implied. See the License **for** the specific language governing permissions **and** limitations under the License.

Each DataONE product also includes a copy of the Apache 2.0 license at the root of its source code tree in order to make the license easily accessible to people that receive the product.

Complete information regarding license and copyright policy is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/license_and_copyright_policy.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/license_and_copyright_policy.html</a>.

# 3. User Scenarios by Institution
We might consider offering user scenarios for the different institutions. These could include stories delineating differences among who needs to be involved, how much time is involved, benefits, implementation routes, etc.
### Libraries
### Research Centers
### Data Repositories
### Government Organizations
### Non-Profits

# Glossary
DataONE developers have created a glossary of all terms used in the architecture documentation. This glossary also points to relevant use cases. The glossary is available at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/glossary.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/glossary.html</a>
