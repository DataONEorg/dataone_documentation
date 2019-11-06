**Primary Audience**: Researchers who come to DataONE to participate in the DataONE Community by using services/products to: access data from DataONE federation, expose data within DataONE federation, provide computing resources or services like data replication to the DataONE community.

# Top Level Outline 
<!-- Start Document Outline -->
* [1. What is DataONE?](#1-what-is-dataone)
	* [1.1. Background and Goals](#11-background-and-goals)
	* [1.2. Components of DataONE](#12-components-of-dataone)
		* [1.2.1. Cyberinfrastructure](#121-cyberinfrastructure)
			* [Coordinating Nodes](#coordinating-nodes)
			* [Member Nodes](#member-nodes)
			* [Investigator Toolkit](#investigator-toolkit)
	* [1.3. User Scenarios](#13-user-scenarios)
	* [1.4 DataONE Cybersecurity Plan](#14-dataone-cybersecurity-plan)
* [2. What is Data, Metadata, and How Are They Treated in DataONE?](#2-what-is-data-metadata-and-how-are-they-treated-in-dataone)
	* [2.1. Data and Metadata](#21-data-and-metadata)
	* [2.2. Data Packaging](#22-data-packaging)
	* [2.3. User Stories](#23-user-stories)
	* [2.4. DataONE Preservation Strategy](#24-dataone-preservation-strategy)
* [3. How Can You Interact with DataONE?](#3-how-can-you-interact-with-dataone)
	* [3.1. Communicate](#31-communicate)
	* [3.2. Discover](#32-discover)
		* [3.2.1. DataONE Public Website](#321-dataone-public-website)
		* [3.2.2. DataONE Search](#322-dataone-search)
			* [User Guide](#user-guide)
			* [Screencast Tutorials](#screencast-tutorials)
	* [3.3. Participate](#33-participate)
		* [3.3.1. Become a Member Node](#331-become-a-member-node)
			* [Contribute Data](#contribute-data)
			* [Replicate Data](#replicate-data)
			* [Member Node Services](#member-node-services)
			* [Cost of Becoming a Member Node](#cost-of-becoming-a-member-node)
			* [Member Node Resources](#member-node-resources)
* [4. What is the Future of DataONE?](#4-what-is-the-future-of-dataone)
* [1. What is DataONE?](#1-what-is-dataone-1)
	* [1.1. Background and Goals](#11-background-and-goals-1)
	* [1.2. Components of DataONE](#12-components-of-dataone-1)
		* [1. Coordinating Nodes](#1-coordinating-nodes)
		* [2. Member Nodes](#2-member-nodes)
		* [3. Investigator Toolkit](#3-investigator-toolkit)
	* [1.3. User Scenarios](#13-user-scenarios-1)
		* [1.3.1. Core Functionality](#131-core-functionality)
		* [1.3.2. Value Added Services](#132-value-added-services)
		* [1.3.3. System Architecture](#133-system-architecture)
		* [1.3.4. Spread and Impact of Invasive Species](#134-spread-and-impact-of-invasive-species)
	* [1.4. DataONE Cybersecurity Plan](#14-dataone-cybersecurity-plan-1)
* [2. What is Data, Metadata, and How Are They Treated in DataONE?](#2-what-is-data-metadata-and-how-are-they-treated-in-dataone-1)
	* [2.1. Data and Metadata](#21-data-and-metadata-1)
	* [2.2. Data Packaging](#22-data-packaging-1)
	* [2.3. User Stories](#23-user-stories-1)
	* [2.4. DataONE Preservation Strategy](#24-dataone-preservation-strategy-1)
* [3. How Can You Interact with DataONE?](#3-how-can-you-interact-with-dataone-1)
	* [3.1. Communicate](#31-communicate-1)
	* [3.2. Discover](#32-discover-1)
		* [3.2.1. DataONE Public Website](#321-dataone-public-website-)
		* [3.2.2. DataONE Search](#322-dataone-search-1)
	* [3.3. Participate](#33-participate-1)
		* [3.3.1. Become a Member Node](#331-become-a-member-node-1)
	* [4. What's the Future of DataONE? ???](#4-whats-the-future-of-dataone-)

<!-- End Document Outline -->

# 1. What is DataONE?
## 1.1. Background and Goals  
>Data Observation Network for Earth (DataONE) is the foundation of new innovative environmental science through a distributed framework and sustainable cyberinfrastructure that meets the needs of science and society for open, persistent, robust, and secure access to well-described and easily discovered Earth observational data.
>
>Supported by the U.S. National Science Foundation (Phase 1 Grant #ACI-0830944, Phase 2 Grant #ACI-1430508) as one of the initial DataNets, DataONE will ensure the preservation, access, use and reuse of multi-scale, multi-discipline, and multi-national science data via three primary cyberinfrastucture elements and a broad education and outreach program. (from "What is DataONE?": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>)
        
>The major goal of NSF's DataNet program is to catalyze development of a system addressing the vision outlined in Chapter 3 (Data, Data Analysis, and Visualization) of NSF's Cyberinfrastructure Vision for 21st Century Discovery in which “science and engineering digital data are routinely deposited in well-documented form, are regularly and easily consulted and analyzed by specialists and non-specialists alike, are openly accessible while suitably protected, and are reliably preserved.” The DataNet project DataONE (Data Observation Network for Earth) is a federated data network built to improve access to Earth science data, and to support science by:
>
>* engaging the relevant science, data, and policy communities;
>* facilitating easy, secure, and persistent storage of data;
>* disseminating integrated and user-friendly tools for data discovery, analysis, visualization, and decision-making.
>
>![](Research-User%20Documentation%20Overview/ReferenceArchitecture.png)  
>Figure 1. An overview of the major components of the DataONE architecture. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a> )

## 1.2. Components of DataONE
>There are three major components in the DataONE infrastructure: Member Nodes which represent data repositories, Coordinating Nodes which serve data management and discovery services, and the Investigator Toolkit which contains a variety of end user tools for interacting with the infrastructure. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>)
### 1. Coordinating Nodes 
>DataONE currently hosts three Coordinating Nodes that provide network-wide services to enhance interoperability of the Member Nodes and support indexing and replication services. Coordinating Nodes provide a replicated catalog of Member Node holdings and make it easy for scientists to discover data wherever they reside, also enabling data repositories to make their data and services more broadly available to the international community. DataONE Coordinating Nodes are located at the University of New Mexico, the University of California Santa Barbara and at the University of Tennessee (in collaboration with Oak Ridge National Laboratory). (from "Coordinating Nodes": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>)
>
>Coordinating Nodes make critical services available through the APIs that enable identifier resolution, data preservation, data discovery, and supplement the federated identity system. Coordinating Nodes replicate all content between themselves, an in doing so create a small set (3-6 nodes) of geographically and institutionally isolated systems that ensure ongoing operation of the infrastructure should any particular node be inaccessible. Coordinating Nodes maintain complete copies of all science metadata (detailed descriptions of science data objects and collections) and system metadata (low level metadata describing the type, size, ownership, and locations of data and) and index this information to enable data discovery services. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>) 

### 2. Member Nodes  
>DataONE comprises a distributed network of data centers, science networks or organizations. These organizations can expose their data within the DataONE network through the implementation of the DataONE Member Node service interface. In addition to scientific data, Member Nodes can provide computing resources, or services such as data replication, to the DataONE community. (from "Member Nodes": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>).  
>
>Member Nodes are primarily existing data repositories (e.g. the Knowledge Network for Biodiversity, ORNL DAAC, Partnership for Interdisciplinary Studies of Coastal Oceans) that already fill an important role in their respective communities supporting data management, curation, discovery and access functions. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>)

### 3. Investigator Toolkit  
>The DataONE Investigator Toolkit enables access to customized tools that are familiar to scientists and that can support them in all aspects of the data life cycle. (from "Investigator Toolkit": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>)
>
>The Investigator Toolkit is a suite of software libraries, tools, and applications that support interaction with the DataONE infrastructure through the REST service APIs exposed by the Coordinating and Member Nodes. Low level libraries are initially available in Python and Java which assist application developers to take advantage of the core services exposed by DataONE participants. For example, an R plugin has been developed using the Java library. Enabling this plugin within a R script enables discovery, retrieval, and storage of content directly in the DataONE infrastructure. Similar extensions are being developed for workflow tools such as Kepler, VisTrails and Science Pipes to enable interaction with the core DataONE services. (from API Doc-"DataONE Overview": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/overview.html</a>)

## 1.3. User Scenarios
### 1.3.1. Core Functionality
DataONE provides the distributed framework (which is comprised of Member and Coordinating Nodes as illustrated below), sound management, and robust technologies that enable long-term preservation of diverse multi-scale, multi-discipline, and multi-national observational data. DataONE initially emphasizes observational data collected by biological (genome to ecosystem) and environmental (atmospheric, ecological, hydrological, and oceanographic) scientists, research networks, and environmental observatories. DataONE will be domain agnostic, progressively expanding to broader domains and building on infrastructure and interoperability with DataNet partners.

![](proposal_figure_1.png)  
*Figure 2.* DataONE Member Nodes form a robust, distributed network via coordinating services provided by a set of Coordinating Nodes (i.e., Oak Ridge Campus, UC-Santa Barbara, and University of New Mexico) arranged in a high-availability configuration. Scientists and citizens interact with Member Nodes (e.g., South African Environmental Observation Network, California Digital Library, USGS National Biological Information Infrastructure) through software tools that utilize standardized interfaces. This structure supports many different usage scenarios, such as data and metadata management and replication (e.g., using Morpho [black arrows] or the Mercury system [orange arrows]), as well as analysis and modeling (e.g., using commercial software like Matlab [light green arrows] and open-source scientific workflow systems like Kepler [blue arrows]). Coordinating Nodes perform many basic indexing and data replication services to ensure data availability and preservation (e.g., node registration [purple arrow] and monitoring via heartbeat services (red arrow]).

### 1.3.2. Value Added Services
DataONE is not the end, but rather the means to enable scientists and citizens to address and better understand the difficult and complex biological, environmental, social, and technological challenges affecting human, ecosystem, and planetary sustainability. The comprehensive cyber-infrastructure allows novel questions to be asked that require harnessing the enormity of existing data and developing new methods to combine and analyze diverse data resources (see Figure 2 below).

DataONE will accomplish its goals by making scientists, students, librarians, and citizens active participants in the data life cycle, especially the data preservation process. By supporting community derived interoperability standards and incorporating new value-added and innovative technologies (e.g., for semantic and geospatial information, scientific workflows, and advanced visualization) into the scientific process, DataONE will facilitate sophisticated data integration, analysis, interpretation, and understanding. A strong education and outreach program focuses on scientists and students learning to better and more easily manage, preserve, analyze, and visualize Earth observational data. Citizen scientists are actively engaged in data preservation and scientific discovery through their involvement in programs such as the USA National Phenology Network (USA-NPN) and numerous Cornell Laboratory of Ornithology citizen science efforts (e.g., eBird, Project FeederWatch).

![](proposal_figure_2.png)  
*Figure 3.* DataONE value-added services enable scientists to address novel questions through integrating disparate data sources (top), supporting geospatial data processing (lower left), and providing scientific workflow solutions like Kepler (lower middle) and high-level analyses and visualizations like IBM ManyEyes.

### 1.3.3. System Architecture
The DataONE architecture must embrace the highly dispersed and independent nature of data collection activities relevant to the environmental and earth sciences. Data are collected by tens of thousands of scientists around the world who have the expertise to describe and archive these data, as well as curate them. Attempting to centralize this curation function is inherently untenable and will not scale. Thus, DataONE will achieve both scalability and sustainability through a highly distributed system architecture (Figures from “Core Architecture” and below) that utilizes the DataONE Service Interface to access uniform services provided and used by three types of cyber-infrastructure: (1) **Member Nodes** located at institutions distributed throughout academia, libraries, government agencies, and other organizations that provide local data storage, curation, and metadata for a set of data resources that are collected or affiliated with that institution; (2) **Coordinating Nodes** that are geographically-distributed to provide a high-availability, fault-tolerant, and scalable set of coordinating services to the Member Nodes, including a complete metadata index and data replication services for all data in all Member Nodes; and (3) an **Investigator Toolkit** that provides a complete and evolving set of tools for data and metadata management by scientists and curators throughout the entire data life cycle (Figure 3). Initially, there will be three Coordinating Nodes geographically dispersed at ORC, UNM, and UCSB. A small number of additional Coordinating Nodes may be implemented as DataNetONE expands in scope, sustainable funding, and international presence.

(all from API Doc-"User Scenarios": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/userscenarios.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/userscenarios.html</a>)

# 2. What is Data, Metadata, and How Are They Treated in DataONE?
## 2.1. Data and Metadata
>Data, in the context of DataONE, is a discrete unit of digital content that is expected to represent information obtained from some experiment or scientific study. The data is accompanied by science metadata, which is a separate unit of digital content that describes properties of the data. Each unit of science data or science metadata is accompanied by a system metadata document which contains attributes that describe the digital object it accompanies (e.g. hash, time stamps, ownership, relationships).
>
>In the initial version of DataONE, science data are treated as opaque sets of bytes and are stored on Member Nodes (MN). A copy of the science metadata is held by the Coordinating Nodes (CN) and is parsed to extract attributes to assist the discovery process (i.e. users searching for content).
>
>The opaqueness of data in DataONE is likely to change in the future to enable processing of the data with operations such as translation (e.g. for format migration), extraction (e.g. for rendering), and merging (e.g. to combine multiple instances of data that are expressed in different formats). Such operations rely upon a stable, accessible framework supporting reliable data access, and so are targeted after the initial requirements of DataONE are met and the core infrastructure is demonstrably robust.
>
>Data Packaging provides a more complete description of data, science metadata, and system metadata and their relationship to one another.(from API Doc-Overview section of "What is Data (DataONE Perspective)": <a href="https://dataone-architecture-documentation.readthedocs.io/en/latest/design/WhatIsData.html#overview" target="_blank">https://dataone-architecture-documentation.readthedocs.io/en/latest/design/WhatIsData.html#overview</a>)
## 2.2. Data Packaging
>A data package in DataONE is composed of at least one science metadata document describing at least one data object with the relationships between them documented in a resource map document.
>
>Resource maps are RDF documents that conform to the Open Archives Initiative’s Object Reuse and Exchange (OAI-ORE) specification as described in detail below. Resource maps are generated by Member Nodes to define data packages, and have a formatId of http://www.openarchives.org/ore/terms/ (note this is a name space string. The actual ORE terms can be found in the ORE Vocabulary Document). Currently (early 2013), only the RDF/XML form of serialization is supported by the DataONE indexing services, and so Member Nodes are required to provide resource maps in this format in order for DataONE search services to give users the data identifiers associated with the metadata used for searches. 
(from API Doc-Synopsis section of "Data Packaging": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/DataPackage.html#synopsis" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/DataPackage.html#synopsis</a>)
>
>![](Research-User%20Documentation%20Overview/datapackage_class.png)
>Overview class diagram for content model in DataONE. Class attributes refer to the equivalent SOLR index entry
## 2.3. User Stories
>* A user agent can download a description of a data package that provides the DataONE identifiers for all science metadata and data object components associated by the package
>
>* A user agent can download a serialized version of a data package that includes the science metadata and either the data bytes or references to the data bytes via DataONE identifiers directly in the serialized version of the package, and the system metadata for each of these objects.
>
>* The serialized form allows for the relationships between the various components to be properly maintained (e.g., which system metadata documents describe which data and science metadata objects)
>
>* Data packages can be versioned, such that individual components of a package can be replaced with new versions of those objects, new objects can be added, existing objects can be removed, and the whole package is versioned to differentiate it from earlier versions that contained different components.
>
>* A user agent can easily locate and inspect the science metadata associated with any data object
>
>* A user agent can easily locate and access the data objects associated with a science metadata object.
>
>* Data object formats should be well-described in science metadata, ideally to sufficient detail to allow software agents to parse and load the data and science metadata objects for additional processing, querying, and manipulation The data objects supported should minimally include:
>
>   * Data Tables in CSV and other fixed and delimited text formats  
>   * NetCDF files  
>   * Raster images in various formats  
>   * Vector data in specific, community-accepted formats
A scientist can load all of the supported data objects from a data package found in a metadata search without directly knowing the identifiers for individual data objects.
> 
>* A scientist can upload a new data object and associated science metadata in order to create a new data package, or to extend or create a new version of an existing data package.
>
>(all from API Doc-"User Scenarios": <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/DataPackage.html#user-stories" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/DataPackage.html#user-stories</a>)

## 2.4. DataONE Preservation Strategy
DataONE’s preservation goal is to protect the content, meaning, and behavior of data sets registered in its global network of Member Nodes. This is a complex undertaking that warrants a layered, prioritized approach. To get started on a solid footing, our first objective was to build a platform that immediately provides a significant degree of preservation assurance and makes it easy to add more sophisticated preservation function over time. Initially, DataONE’s focus is on preventing loss due to non-malicious causes, such as,
* Technological obsolescence (e.g., loss of support for rendering software and hardware),
* Accidental loss (human error, natural disaster, etc.), and
* Financial instability (loss of funding).

To meet the objective of “easy, secure, and persistent storage of data,” DataONE adopts a simple, three-tiered approach.
1.	**Keep the bits safe.** Retaining the actual bits that comprise the data is paramount, as all other preservation and access questions are moot if the bits are lost. Key sub-strategies for this tier are (a) persistent identification, (b) replication of data and metadata, (c) periodic verification that stored content remains uncorrupted, and (d) reliance on member nodes to adhere to DataONE protocols and guidelines consistent with widely adopted public and private sector standards for IT infrastructure management.
2.	**Protect the form, meaning, and behavior of the bits.** Assuming the bits are kept undamaged, users must also be able to make sense of them into the future, so protecting their form, meaning, and behavior is critical. In this tier we rely on collecting characterization metadata, encouraging use of standardized formats, and securing legal rights appropriate to long-term archival management, all of which supports future access and, as needed to preserve meaning and behavior, format migration and emulation.
3.**	Safeguard the guardians.** If the DataONE federation and its Member Nodes were to disappear, that would be equivalent to 100 percent data loss. The DataONE federation itself provides resiliency against the occasional loss of Member Nodes, and this will be shored up by succession planning, ongoing investigations into preservation cost models, and open-source software tools that can sustained by external developer communities.

Information about preservation metadata related to system metadata is available at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html#requirement-2-perform-preservation-migration" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/SystemMetadataAnalysis.html#requirement-2-perform-preservation-migration</a>

More information about DataONE's Preservation Strategy is at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/PreservationStrategy.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/PreservationStrategy.html</a>.

## 2.5. DataONE Cybersecurity Plan
Cybersecurity for DataONE is part of the initial system planning and design, thereby providing solid integration to all services. The design is based on the fact that DataONE is a collaboration of researchers, data providers, institutions, Coordinating Nodes, Member Nodes, data collections, and other infrastructure components. Therefore, DataONE, as an entity, spans many organizations and administrative domains. The primary goal of DataONE cybersecurity is to protect the data and metadata collections that those organizations and administrative domains contribute, as well as their infrastructure and the DataONE user community.  

DataONE recognizes that your institution must simultaneously meet local requirements and must also integrate into the DataONE cyberinfrastructure. To meet these diverse requirements and needs, DataONE has designed cybersecurity management that is flexible and can support the wide-ranging needs of each Member Node. 

The bottom line is that DataONE security is focused on protecting data in the Member Node at your institution from intentional and non-intentional harm; for example, unauthorized viewing of private data and or alteration or deletion of another user's data. System operations are also protected from malicious activity that often occurs on the Internet. For detailed descriptions of the multiple institutional cybersecurity scenarios in DataONE, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-institutional-components" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-institutional-components</a>. 

Security in DataONE consists of two processes: 
1. **Authentication**, which verifies the identity of users
2. **Authorization**, which applies rules that govern access to system resources (e.g., data). 

Authentication is the process of determining whether or not a user is who they say they are. DataONE relies on both end-users and servers (the Member Nodess and Coordinating Nodes) to use X.509 certificates to authenticate themselves, and relies on CILogon to provide certificates to end-users.

The use of CILogon has two main advantages for your institution. First, you can use existing accounts to obtain certificates, so you don’t need to create and remember another username and password combination. Second, once you have downloaded the certificate, it will secure connections with all DataONE nodes throughout the day, and can be used by multiple DataONE applications. This technique is known as single-sign-on. It also means your institution has full control over who may view or modify your data by defining your own local authorization rules, which will be propagated and enforced by DataONE. More information about authentication can be found at <a href="https://releases.dataone.org/online/api-dhttps://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.htmlocumentation-v2.0.1/design/AuthorizationAndAuthentication.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html</a>.

Authorization is the process for confirming whether a user has privileges to access a resource in DataONE. It provides privacy and access control to user contributed data and metadata, as well as protects DataONE services and resources at both the coordinating and Member Nodes. In order to serve the many administrative domains and political boundaries represented throughout DataONE member and Coordinating Nodes, a “trust” relationship is crucial. Therefore, access control rules that are defined by your institution are honored by other DataONE members. The language that specifies the policy for a given access control rule dictates only whether a user is allowed access to a given resource. This includes the ability to explicitly deny access to a resource overly complicates managing the authorization process, which is seldom used in practice. Rules will consist of the system identity of the user, the type of permission granted (e.g., read, write, and or execute), and the identifier of the resource being requested. DataONE will provide, where reasonable, a conversion of the internal access control rule to a subset of one or more industry standard policy languages to support interoperability between different organizations

For further details about authorization, see <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/Authorization.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/Authorization.html</a>. You can also access a primer outlining the specific differences between authorization and authentication at: <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/AuthorizationAndAuthentication.html</a>.

In conclusion, the cybersecurity posture of DataONE will evolve over time both because of the continuing maturation of DataONE operational strategies and because of an ever-evolving cybersecurity landscape. You can access DataONE's full Cubersecurity Plan at <a href="https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-cybersecurity-plan" target="_blank">https://releases.dataone.org/online/api-documentation-v2.0.1/design/security-plan.html#dataone-cybersecurity-plan</a>.

# 3. How Can You Interact with DataONE?
## 3.1. Communicate 
DataONE offers a variety of different communication outlets. You can chat with someone in real time or through video conferencing, or you can stay in touch through email on one of our discussion lists.
### 3.1.1. In Real Time
DataONE uses Slack for messaging between project participants. Anyone may join the DataONE Slack organization by requesting an invite at: https://slack.dataone.org/

### 3.1.2. Video Conferencing
DatONE uses <a href="https://zoom.us/" target="_blank">Zoom</a> for video conferencing within the project and for webinars.

Project participants needing Zoom for project purposes should contact support *@ dataone.org*.

### 3.1.3. Discussion Lists
DataONE uses Google Groups for email list management. The DataONE.org Google Groups are managed as a *dataone.org* subdomain of *nceas.ucsb.edu* and includes the following lists:

| Address | Description |
|----------|----------|
| administrator@dataone.org | For contacting administrators of the DataONE infrastructure. |
| Column 1 | A voluntary participation mailing list for disseminating information to the community with interest in DataONE. |
| coredev@dataone.org | Internal communications for the DataONE core development team. |
| mnforum@dataone.org| Member Node forum, for discussion related to Member Nodes and disseminating information to DataONE Member Node operators. |
| developers@dataone.org | General development related discussion.|
|DUGcommittee@dataone.org | Private list for the DataONE User Group Committee members.|
| DUGmembers@dataone.org | Open list for the DataONE Users Group. |
| leaders@dataone.org | Private list for members of the DataONE Leadership Team. |
| team@dataone.org | Active project participants.|
| mn-coordinators@dataone.org| Private list for the Member Node coordination team. |
| operations@dataone.org | List for notification to stakeholders of the DataONE infrastructure. Any outages, maintenance, or other perturbations to normal operations should be posted here. |
| support@dataone.org | For requesting support on any aspect of the DataONE project. |
| sysadmin@dataone.org | Project participants with systems administration responsibilities. |

>Contact information for users from DataONE Operations Doc-"Communications" section: <a href="https://dataone-operations.readthedocs.io/en/latest/PROJ/communications.html" target="_blank">https://dataone-operations.readthedocs.io/en/latest/PROJ/communications.html</a>.

## 3.2. Discover   
Using the DataONE Search Interface, you can search, access, and download a wide range of scientific datasets stored in DataONE's federation of repositories.

### 3.2.1. DataONE Public Website
The <a href="https://www.dataone.org" target="_blank">DataONE Public Website </a> offers a multitude of resources for you to find data from DataONE affiliated Member Nodes, to make the most of your own data with supporting tools and services by participating as a DataONE Member Node, and to access materials and resources that promote good data management practices.

### 3.2.2. DataONE Search Interface 
Thousands of datasets are stored in DataONE's federation of repositories, known as <a href="https://www.dataone.org/current-member-nodes#uploads" target="_blank">Member Nodes</a>, providing a broad range of Earth-observation data that can be searched, compared, merged, or used in other ways. Users of the DataONE community &mdash; from scientists, ecosystem managers, and policy makers to students, educators, librarians, and the public &mdash; can search detailed descriptions (metadata) of datasets using the <a href="https://search.dataone.org/data" target="_blank">DataONE Search Interface</a>. Searches in DataONE Search return results based on user-specified criteria, such as desired geographic coverage, taxonomic coverage, and/or keywords included in a dataset's metadata record, such as the dataset’s title, abstract, collection methods, and creator’s name. Users need only click on a search result to open a dataset's metadata record and obtain any data and metadata files available for download.

DataONE offers several resources that help you understand the search interface and provide strategies for conducting dataset searches:
* DataONE Search User Guide  
* <a href="https://www.dataone.org/dataone-search-screencasts" target="_blank">Screencast Tutorials for DataONE Search</a>

## 3.3. Participate  
### 3.3.1. Become a Member Node
You can participate in DataONE's ever-expanding global community that provides open access to a broad range of earth and environmental research data by becoming a DataONE Member Node. Through the implementation of the DataONE Member Node service interface, your institution can expose your data within the DataONE federation. In addition to scientific data, Member Nodes can provide computing resources, or services such as data replication, to the DataONE community. (from "Member Nodes": <a href="https://www.dataone.org/what-dataone" target="_blank">https://www.dataone.org/what-dataone</a>).

DataONE provides your institution with a framework to support open, persistent, robust and secure access to well described and easily discovered data about life on earth and the environment that sustains it. Becoming a Member Node of the DataONE federation supplies your institution with the infrastructure to store and provide access to your institution’s digital scientific holdings and to also make these data available to a much broader community. Your institution can opt to host its own data, or to partner with other data holders or repositories. Your institution also has the freedom to use a variety of standards or formats to describe and store your data.  

As a DataONE Member Node, your institution would report its metadata to a DataONE Coordinating Node, which choreographs services that help users store, discover, and retrieve data. The Coordinating Node provides a host of other services, including facilitating replication and preservation of data objects, authorization and authentication, and data discovery. In essence, DataONE acts a partner in helping to facilitate your institution’s implementation of a data management strategy and showcasing your institution’s intellectual capital.

Additionally, DataONE's Investigator Toolkit provides scientists, researchers, and students with a suite of powerful tools for finding, using and storing data on the DataONE federation. The Investigator Toolkit includes tools for data searching, desktop data file management, data integration and analysis, among many others. You can find the complete, detailed list of tools available in the Investigator Toolkit at <a href="https://www.dataone.org/investigator-toolkit" target="_blank">https://www.dataone.org/investigator-toolkit</a>. 

* Contribute Data
* Replicate Data   
(from API Doc-"Replication Overview" section: <a href="https://dataone-architecture-documentation.readthedocs.io/en/latest/design/ReplicationOverview.html" target="_blank">https://dataone-architecture-documentation.readthedocs.io/en/latest/design/ReplicationOverview.html</a>)

#### Member Node Tiers  
As a DataONE Member Node, you have the option of selecting the level of engagement you want to take within the DataONE federation. You can choose from 4 available tiers. 
(from DataONE Operations Doc-"Select the DataONE Tier": <a href="https://dataone-operations.readthedocs.io/en/latest/MN/deployment/select_tier.html" target="_blank">https://dataone-operations.readthedocs.io/en/latest/MN/deployment/select_tier.html</a>)

#### Member Node Services
Becoming a DataONE Member Node will give you access to a host of services, such as:
##### Metadata Quality Reports
DataONE offers dataset quality assessments to improve curation and preservation via access to metadata quality information. This service includes:
* Comprehensive information on metadata quality and completeness.
* Guidance and support for metadata creators.
* Aggregated time series metrics.
* Customizable quality suites meeting individual repository needs.
* Ability to check metadata against multiple quality suites.
* **FAIR** (Findable Accessible Interoprerable Reusable) quality suite.

##### Data Level Metrics
As a DataONE MEmber Node, you will have access to reliable and comprehensive third-party metrics reporting, which will allow you to track usage of your data. This service features:
* COUNTER compliant download, view, and citation metrics.
* Links to citing publications.
* Time series data showing trends in usage.
* Aggregated reports for individuals, repositories, funders, and others.

##### Custom Data Search
Through the DataONE Search Interface, you can customize data collections with audience and discipline-specific seach capabilities. This service enables you to:
* Show data across multiple repositories simultaneously.
* Search by topic, region, time, and other facets.
* Work with public and private data.
* See a uniform view across metadata standards.
* Add portal-specific search fields and widgets.

##### Member Administration
As a member of the DataONE community, you'll have certain administrative capablities. You can create and manage community access to your data submission and reporting process. Build a community aroud your data using the following administrative features: 
* Define groups to support collaboration.
* Select members who can add data.
* Select members who can view metrics.
* Custom metadata editing for portal members.

##### Learning Support
DataONE offers a host of resources, best practices, and instruction aimed to increase data literaacy through community-led and partnered learning activities. These activities include:
* Skillbuilding Hub for community shared modules, best practices, and resources.
* Webinar series focused on topical data science questions.
* In-person, intensive training workshops.
* Data Help Desk and workshops at domain society meetings.

##### The DataONE Federation
##### Branded Portals
You can customize your data portals and information management for targeted communities. With this service, you can:
* Create a specific domain, organization, or project view of data and associated information.
* Design the look and content to match your target audience.
* Add tabs for additional topical or regional content.
* Use a simple Markdown editorial interface.

Through the Branded Portal service, you'll also receive access to a bundled tool package that includes all of the above-mentioned services:
* Metadata Quaity Reports
* Data Level Metrics
* Custom Search
* Member Administration

#### Cost of Becoming a Member Node?

#### Additional Member Node Resources

(from DataONE Operations Doc-"Member Node Resources Sections": <a href="https://dataone-operations.readthedocs.io/en/latest/MN/index.html#member-nodes-resources" target="_blank">https://dataone-operations.readthedocs.io/en/latest/MN/index.html#member-nodes-resources</a>)

## 4. What's the Future of DataONE?
Over the past decade, DataONE has grown from a nascent project addressing the need for repository interoperability into a robust, interoperable federation of dozens of member repositories spanning the globe and providing unfettered access to earth and environmental research data. DataONE has relied upon, and is grateful for, the participation of hundreds of individuals who have served on working groups, contributed or used data, operated repositories, collaborated on related projects, joined our users group, or served on our advisory board. DataONE was seeded and has grown through the support of an NSF DataNet cooperative agreement. As we approach the end of that award, the leadership of DataONE in conjunction with the DataONE Users Group and other stakeholders, are actively developing sustainability options for 2020 and beyond.

### The New DataONE Community 
To build capacity for enhanced collaboration and partnership, DataONE is making changes to the current user group structure, thereby enabling a more diverse and invested membership and community-driven decision-making. The DataONE Community will serve as our new community-driven governance organization. This organization will replace the DataONE Users Group (DUG), and we welcome everyone with an interest in DataONE to help shape our future.

Since its creation in 2010, the DUG has represented the needs and interests of data authors, users, and other stakeholders and provided guidance to DataONE leadership. As DataONE transitions to a new leadership team, the DataONE Community will be the source of decision-making and guidance at the core of DataONE. We encourage all DataONE users, participating repositories, and others with interests in the Earth and environmental data sciences to contribute to the evolution of the DataONE Community and provide feedback on its Mission, Vision, and Values Statements and forthcoming proposed Governance Model.

### Expanded Repository Participation
We anticipate broadening repository participation in DataONE, welcoming new collaborating researchers and institutions, and transforming organizational governance. DataONE community members will be invited to contribute to the evolution of our model for community-driven repository interoperability as we move forward, and frequent updates and announcements about future changes will be provided at `https://www.dataone.org/future`.

Core DataONE services will continue to operate at UC Santa Barbara and the University of Tennessee Knoxville in 2020 and beyond. All core services, including onboarding of new repositories, data search, infrastructure services such as replication, citation and usage reporting, and education and training activities will continue unabated, and a number of exciting new services are being planned for announcement over the next year.

Stay tuned for news of these changes and new capabilities through the next year and beyond as we evolve DataONE into the future. If you have questions or suggestions, please see our web site or contact us at “info@dataone.org”.

https://www.dataone.org/future (from <a href="https://www.dataone.org/news/dataone-begins-transition-new-leadership" target="_blank">"DataONE Begins Transition to New Leadership"</a>) 