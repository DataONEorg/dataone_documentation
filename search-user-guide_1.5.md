# DataONE Search User Guide


<a href="https://www.dataone.org/" target="_blank">Data Observation Network for Earth (DataONE)</a> is a federation of repositories for environmental and ecological science data and metadata (descriptions of data) that helps meet the needs of science and society for open, persistent, robust, and secure access to well-described and easily discovered Earth observational data. Supported by the U.S. National Science Foundation (Phase 1 Grant <a href="https://nsf.gov/awardsearch/showAward?AWD_ID=0830944" target="_blank">#ACI-0830944</a>, Phase 2 Grant <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1430508" target="_blank">#ACI-1430508</a>), DataONE's goal is the preservation, access, use, and reuse of multi-scale, multi-discipline, and multi-national scientific data through a distributed framework, sustainable cyberinfrastructure, and education and outreach programs. You can learn more about the cyberinfrastructure elements and education and outreach programs by visiting <a href="https://www.dataone.org/what-dataone" target="_blank">"What is DataONE?"</a> or by exploring the <a href="https://www.dataone.org" target="_blank">DataONE public website</a>.


Thousands of datasets are stored in DataONE's federation of repositories, known as <a href="https://www.dataone.org/current-member-nodes#uploads" target="_blank">Member Nodes</a>, providing a broad range of Earth-observation data that can be searched, compared, merged, or used in other ways. Users of the DataONE community &mdash; from scientists, ecosystem managers, and policy makers to students, educators, librarians, and the public &mdash; can search detailed descriptions (metadata) of datasets using the <a href="https://search.dataone.org/data" target="_blank">DataONE Search Interface</a>. Searches in DataONE Search return results based on user-specified criteria, such as desired geographic coverage, taxonomic coverage, and/or keywords included in a dataset's metadata record, such as the dataset’s title, abstract, collection methods, and creator’s name. Users need only click on a search result to open a dataset's metadata record and obtain any data and metadata files available for download. 


This user guide is comprised of three sections, each containing information for using and understanding the various features and capabilities of DataONE Search. Section 1 begins with a brief overview of the DataONE Search interface. Section 2 lists the different ways you can conduct searches and explains how DataONE Search looks for datasets. Sections 2.1 thru 2.3.9 provide in-depth explanations and examples of the  search approaches mentioned in Section 2: the basic search feature; the geographic search feature; and the filtered search feature. Lastly, Section 3 offers a Search Legend that explains the meanings of the various icons that appear in DataONE Search.


# Table of Contents


<!-- Start Document Outline -->


* [DataONE Search User Guide](#dataone-search-user-guide)
	* [1. DataONE Search Overview](#1-dataone-search-overview)
	* [2. Using and Understanding DataONE Search](#2-using-and-understanding-dataone-search)
		* [2.1. Searching for Datasets using the Basic Search Feature](#21-searching-for-datasets-using-the-basic-search-feature)
		* [2.2. Searching for Datasets using a Geographic Search with DataONE Map](#22-searching-for-datasets-using-a-geographic-search-with-dataone-map)
		* [2.3. Searching for Datasets using DataONE Filters](#23-searching-for-datasets-using-dataone-filters)
			* [2.3.1.  Data Attribute](#231--data-attribute)
			* [2.3.2.  Data Files](#232--data-files)
			* [2.3.3.  Member Node](#233--member-node)
			* [2.3.4.  Creator](#234--creator)
			* [2.3.5.  Year](#235--year)
			* [2.3.6.  Identifier](#236--identifier)
			* [2.3.7.  Taxon](#237--taxon)
			* [2.3.9.  Location](#239--location)
	* [3. DataONE Search Legend](#3-dataone-search-legend)


<!-- End Document Outline -->


## 1. [DataONE Search Overview](#1-dataone-search-overview)
DataONE Search is a web-based search interface for accessing data in the DataONE federation. You can access it from the <a href="https://www.dataone.org/" target="_blank">DataONE homepage</a>, or you can type `search.dataone.org` into your browser directly. In addition to this user guide, you can also view a series of <a href="https://www.dataone.org/dataone-search-screencasts" target="_blank">screencast tutorials about using DataONE Search</a>.


On the DataONE Search landing page, you'll see three columns: the left column includes a basic search textbox (more information provided in [2.1. Searching for Datasets using the Basic Search Feature](#21-searching-for-datasets-using-the-basic-search-feature) and a set of parameters that can be used to filter data (more information provided in [2.3. Searching for Datasets using DataONE Filters](#23-searching-for-datasets-using-dataone-filters); the center column includes a list of datasets (sorted by most recently added to the DataONE federation); and the right column includes a searchable map (more information provided in [2.2. Searching for Datasets using a Geographic Search with DataONE Map](#22-searching-for-datasets-using-a-geographic-search-with-dataone-map). 


![DataONE Search Interface](DataONE%20Search%20Landing%20Page.PNG)


From the Data Catalog menu bar, you can view a summary of all datasets in the DataONE federation by clicking "Summary." This will display the total metadata and data files uploaded over time; the format these files are in; and the time period covered by the datasets. 


![DataONE Summary](DataONE%20Summary.PNG)


You can also view dataset summaries for individual Member Nodes in the DataONE federation by clicking on a Member Node logo displayed in the search results listings. See Section [2.3.3.  Member Node](#233--member-node) below for more details about how to do this.


## 2. [Using and Understanding DataONE Search](#2-using-and-understanding-dataone-search)
You can search for datasets using DataONE Search in three primary ways: 1) You can conduct a basic search using the basic search textbox; 2) You can conduct a geographic search using the map; and 3) You can conduct a more refined search using the available filters.


You can also combine a basic search with a filtered search. In this scenario, DataONE Search will return results that contain both the basic search terms and the filtered search terms. Keep in mind that DataONE Search treats each filter as an AND search command, so selecting too many filters could make your search too precise and affect your results. 


You can always remove search terms and filters by clicking "x" next to any search terms or by clicking "clear all filters." In the example below, a basic search was conducted for the terms `Louisiana`, `vegetation`, and `ozone`. Any of the three search terms can be removed individually by clicking the "x" next to a term or all terms can be removed at the same time by clicking "clear all filters."


![Clearing DataONE Search Filters](Clearing%20DataONE%20Search%20Terms.PNG)


All filters in DataONE Search, including the basic search feature, are looking for matches in the science metadata for each dataset. Any text or metadata contained in the data files (e.g. .csv table; .zip folder) will not be searched. 


To view the full metadata record for a dataset, click on its row in the search results listing. You'll be taken to the metadata records page where you can learn more about the dataset and explore data and metadata files available for download. The figure below shows the metadata record that appears after clicking on the first search result listed in the previous figure. 


![Metadata Record View](Metadata%20Record%20Display.PNG)


### 2.1. [Searching for Datasets using the Basic Search Feature](#21-searching-for-datasets-using-the-basic-search-feature)
* Basic searches completed with DataONE Search will match your search terms to the full text associated with datasets, including title, abstract, keywords, contributors, data variables, geographic regions, and any other metadata available.
* Because science metadata standards vary across Member Node repositories, the order of words in a search phrase can sometimes be a factor in obtaining results. For example, if searching for datasets on heat and gas emissions from Yellowstone geysers, searching `heat and gas emissions` generates 0 search results, while searching `gas and heat emissions` generates the desired result. So, if you find your search is not yielding optimal results, try rearranging the order of your search terms. 




| `heat and gas emissions` Results | `gas and heat emissions` Results |
|----------|----------|
|![](Heat%20and%20Gas%20Emissions%20Search.PNG)|![Gas and heat](Gas%20and%20Heat%20Emissions%20Search.PNG)|




* Searching for multiple terms at the same time will look for matches with that exact phrase - e.g., `small mammals` - `small` and `mammals` will return results that mention both of the independent words `small` and `mammals`. 
* The basic search feature functions more like a filter, and by default, will return results that contain all search terms. So, entering terms individually will often generate better results than entering longer strings of words. For example, searching `soil and small mammals` will return 0 results, while searching `soil` and `small mammals` as two separate search terms will return 686 results.


| `soil and small mammals` Results | `soil` and `small mammals` Results |
|----------|----------|
|![](Search%20for%20soilANDsmallmammals.PNG)|![](Search%20for%20soil%20and%20small%20mammals.PNG)|




### 2.2. [Searching for Datasets using a Geographic Search with DataONE Map](#22-searching-for-datasets-using-a-geographic-search-with-dataone-map)
* A geographic search is helpful if you want to explore the kinds of research being conducted in specific regions or locations. Using the DataONE map, you can identify datasets by geographic area. Each tile on the map represents the number of geographic regions, not the number of datasets, located within that tile. Geographic regions are extracted from the science metadata in each dataset. As noted above in [Section 2.1.](#21-searching-for-datasets-using-the-basic-search-feature), science metadata standards vary across Member Node repositories. Each science metadata standard stores geographic regions somewhat differently, and it is up to the scientists to define exactly what they consider to be a geographic region for their datasets.   


![Tiles and Geographic Regions](DataONE%20Map%20Tiles.PNG)


* The number of geographic regions visible on your screen may vary and can be affected by your computer's current resolution, Operating System (OS), or web browser.
* You can zoom into a particular area on the map by clicking a tile. This selection adjusts the map scale to display a more precise geographic area on the map. All the datasets available within that targeted region will appear in the search results listing. For example, clicking on the tile with 304 regions that was featured in the above image will zoom closer into that area and display the region's 2,457 datasets in the search results listing. 


![Map Tile 304 Zoom](Map%20Tile%20304%20Zoom.PNG)


* To pinpoint a dataset's location on the map, hover over the location icon &mdash; ![](Map%20Icon%20small.PNG) &mdash; in the search results listing. It will highlight the dataset's location on the map.


![](DataONE%20Map%20Location%20View.png)


* To see the full metadata record of a dataset, click on its row in the list of search results.
* By default, the map feature is enabled and will adjust its scaling to fit your search terms and filters. You can disable the map feature by clicking "Hide Map."


![](Hide%20Map%20Feature.PNG)


* The figure below shows a view of your screen when the map is hidden. You can enable the map feature again by clicking "Show Map."


![](Map%20Hidden.PNG)


### 2.3. [Searching for Datasets using DataONE Filters](#23-searching-for-datasets-using-dataone-filters)
You can use the additional nine (9) filters described below to conduct a more targeted search or to refine your basic search results. As mentioned in Section 2. "Using and Understanding DataONE Search," you can always remove filters by clicking "x" next to any filters or clicking "clear all filters." 


#### 2.3.1. ![](Data%20Attribute%20Icon.PNG) [Data Attribute](#231--data-attribute)  
  A data attribute is a unit of information inside a dataset. Data attributes are essentially the measurable properties and variables of a dataset, such as density, length, temperature, height, weight, and species. You can use this filter to search for specific attributes in datasets. 
##### Examples: `soil temperature`, `salinity`


#### 2.3.2. ![](data-table.png) [Data Files](#232--data-files) 
  If this filter is selected, only search results that include data files will be returned. If it is not selected, some search results may be metadata files only. When you click on a search result, you'll be taken to the dataset's metadata record. There, you can see the file types available for download in the dataset. If you download a metadata file, you'll need to open it using a text editor (e.g., Notepad, Wordpad, Atom, Brackets, etc.) in order to view its contents.
  
#### 2.3.3. ![](Member%20Node%20Icon.PNG) [Member Node](#233--member-node)
  DataONE Member Nodes (MNs) are data repositories that provide Earth science data to the DataONE federation. From the list (which expands to show all current Member Nodes), you can select one or more Member Nodes to restrict your search to include only data from those Member Nodes. Each search result originates from only selected Member Nodes, and the Member Node's logo will be displayed in the search result listing. For example, selecting the Arctic Data Center from the Member Node list prompts DataONE Search to display all datasets originating from only the Arctic Data Center in the search result listing.
  
![Member Node Filter](Member%20Node%20Filter.PNG)
  
  Click on the Member Node logo displayed in the search result listing to view more information about the Member Node and see its dataset summary, download history, latest updates, and file formats. The figure below shows the summary page that appears after clicking on the Arctic Data Center's logo. 
  
![Member Node Summary](Artic%20Data%20Center%20MN%20Summary.PNG)
  
#### 2.3.4. ![](Creator%20Icon.PNG) [Creator](#234--creator)  
  You can use this filter to search for the person name(s) or entity (organization, group, etc.) that are listed as creators of a dataset. The username of the user who uploaded a dataset is not taken into account (use the basic search filter instead).
##### Examples: `Smith`, `John Smith`


#### 2.3.5. ![](Year%20Icon.PNG) [Year](#235--year)  
  Use the slider or type in a year number and limit your search to data that was collected and/or published between that year range. You can filter results by year in two ways:  
  1. **Year(s) of data coverage**: Year that data was collected. By default, the results returned will contain data collected within the data coverage range. 
  2. **Year of publication**: Year that data was published. If the creator did not provide a publish date, then the year the data was uploaded is used instead.  


#### 2.3.6. ![](Identifier%20Icon.PNG) [Identifier](#236--identifier)  
  An advanced filter to use when searching for a specific dataset by part or all of its ID or DOI (Digital Object Identifier). [What is a DOI?](https://www.dataone.org/citing-dataone)
##### Examples: `lter`, `doi:10.5063/F1HH6HOR`


#### 2.3.7. ![](Taxon%20Icon.PNG) [Taxon](#237--taxon) 
  This filter searches all taxonomic ranks (class, family, species, etc.) that were provided by the dataset creator for a full or partial match.
##### Examples: `Dreissena polymorhpa`, `Mollusca`


#### 2.3.9. ![](Location%20Icon.PNG) [Location](#239--location)  
  The location filter searches for a dataset's geographic site or study area description. The location may be a place name or a detailed description of the study site.
##### Examples: `Davis Pond`, `freshwater`


## 3. [DataONE Search Legend](#3-dataone-search-legend)
The following legend describes the icons you will see in the search results listing and in a dataset's metadata records, which you can view after clicking on a search result. Each icon offers brief hover-over information when you place your cursor over the icon. Not all search results will contain each icon described below.


| Icon | Description |
|---::---|:------------|
|![](Data%20Abstract%20Icon.PNG)| This icon appears in the search results listing and provides a snapshot of a dataset's abstract.|
|![Data File Icon](data-table.png)| This icon appears in the search results listing and indicates the number of data files included in the dataset.|
|![](Data%20File-MD%20Records.PNG)| This icon appears in the metadata records and indicates which of the dataset's files are data files.|
|![](Metadata%20File.PNG)| This icon appears in the metadata records and indicates which of the dataset's files are metadata files.|
|![](Map%20Icon.PNG)| This icon appears in the search results listing and indicates the number of a dataset's geographical locations on the map. Each dataset may correspond to more than one geographic area. Hovering over the icon will highlight any of the dataset's localities that are visible on the map.|
|![](Provenance%20Icon.PNG)| This icon appears in the search results listing and indicates that a dataset contains provenance, an important form of metadata that captures the lineage and processing history of data and knowledge artifacts. Provenance plays a crucial role in increasing the transparency, reproducibility, and reuse of science data.|
|![](Dataset%20Download%20Icon.PNG)| This icon appears in both the search results listing and the metadata records and indicates the number of times that all or part of a dataset has been downloaded. In the metadata records, the icon also indicates that a metadata and/or data file is available for download.|
|![](Dataset%20View%20Icon.PNG)| This icon appears in both the search results listing and the metadata records and indicates the number of times that all or part of a dataset has been viewed.|
|![](Citation%20Icon.PNG)| This icon appears in the metadata records and indicates the number of times that all or part of the dataset has been cited.|

 



 


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU3Njc2MDg0NF19
-->