# UFOs


## Project Overview
To enhance the ability to analyze data on UFO sightings, this short project improves a data filter on data stored in a JavaScript array and includes updates to a simple webpage for inputing criteria used to filter the data. The existing webpage initially included a date filter criteria and the enhanced webpage includes filters for city, state, country, and generalized shape of UFO observed. 

## Resources
- JavaScript
- Bootstrap
- HTML + CSS

## Results
Our final result is the webpage found in figure 1. The webpage includes a large image created by NASA and is titled "The Truth is Out There". It also includes a brief sub-header and webpage description, all of which was provided prior to the start of this project. 

![Image of "The Truth is Out There" webpage](https://github.com/ozloty06/UFOs/blob/main/static/images/webpage.png)
##### Fig. 1 - "The Truth is Out There" webpage screen capture.



Enhancements to the webpage center on the filter search criteria section. For comparison, Figure 2 provides a view of the prior search criteria before the webpage was enhanced for additional search filters (left) and the enhanced filtered search criteria (right).

![Image of original search filter](https://github.com/ozloty06/UFOs/blob/main/static/images/criteria.png)
##### Fig. 2 - Original Search Filter (left) and Enhanced Search Filter (right).



In order to conduct a search of the existing data, the user may choose to enter search criteria for any one of the input fields provided, all of them, or any combination of criteria. When no criteria is entered in a field, the table produces all the available data for that particular column heading. See Figure 3 for an example filtered search of observations in the USA that described a circle shaped object.

Search criteria allows the user to filter by:
- Date of UFO observation
- City where UFO observation took place
- State where UFO observation took place
- Country where UFO observation took place
- Shape of UFO observation described (i.e. circle, triangle, light, unknown, etc.)

![Image of a filtered search](https://github.com/ozloty06/UFOs/blob/main/static/images/filtering.png)
##### Fig. 3 - Conducting a Filtered Search.



## Summary

The enhanced webpage allows for more indepth review of the UFO observation data than was previously possible filtering by date alone. One drawback of this new design is that the filters are case sensitive and many of data entries are entirely lowercase. For example, while a search for "atlanta" produces a single result, filtering by "Atlanta" produces an empty table. 

One recommendation would be remove the case sensitivity to the filters and possibly use autocomplete text to help users more quickly identify potential filter criteria based on the existing table while compensating for spelling errors and typos. A second recommendation would be to provide the list of countries included in the data set as checkboxes to help users less familiar with country abrieviations (i.e. someone may be unsure if "Canada" is listed under "ca", "cn", or even "cd"). Lastly, adding buttons to clear the filter and submit the filter would give users an alternative means to complete those tasks than refreshing the page or manually clearing fields. 
