# UFO-sightings

## Project Overview 
The goal of this project was to design a webpage that could summarize the incidences of UFO sightings while allowing users to filter sightings based on criteria such as location, UFO shape, and date of observance. This was achieved by utilizing a dynamic table with Javascript.

## Results
Conducting a search using this table is a straight-forward process as there are only a few steps to follow which are outlined below:

For the search itself, one only needs to fill out the filter criteria in the manner shown below (Figure 1), this includes date of observation(dd/mm/yyyy), city, state, country, and shape of object observed. In Figure 1, only the city criteria was filled in but any (or none) of the fields can be filled out to determine the resulting specificity of the table.

![willow](https://user-images.githubusercontent.com/93050931/150694074-acdc4cc1-d4ab-4b25-86ac-0c25ff5c25e6.png)

(Figure 1)

After filling out the desired criteria, press enter and a table should load which shows the documented UFO sightings that match the provided search filters (Figure 2).

![willow1](https://user-images.githubusercontent.com/93050931/150694474-c8a10288-6fb7-4512-99b1-159c8d45493d.png)

(Figure 2)

This process can be repeated for any criteria that matches entries in the database. 

## Summary
One drawback of the webpage is that the search criteria can be a bit ambiguous. It is not obvious to somebody who is not familiar with the United States what the codes for each state would be. For example, if somebody were trying to search for UFO sightings in Alaska, they may input "al" as that would be a common guess based on intuition. However, this would actually show results for Alabama. If somebody were relying on this webpage for an important project, this could seriously impair their analysis. A better solution would be a drop down menu to select a state's full name instead of inputting a two-letter code.

### Potential Improvements
- Add a drop down menu for states and cities. What would be even more helpful is to filter by state first, then use that filter to narrow the drop down menu for cities to only show cities within the selected state. Furthermore, the United States and Canada appear to be the only countries represented in the data. This same idea can be applied to selecting states and provinces as well. Lastly, since Canada has provinces not states, the search filter should say "State/Province". A user would have no idea that Canada is represented in this data because Canada has no states.

-When search criteria is entered that matches no entries in the dataset, a message should appear along the lines of 'No data matching search criteria'. In the current webpage, nothing appears at all to indicate that the search criteria is invalid. This may lead a user to beleive the website has frozen or simply does not work. There should be an output for every possible input.




