# UFO-Sightings

## Project Overview
A dataset containing UFO sightings have been provided, and an HTML webpage was then created to filter through sighting parameters to help users find specific data using Javascript.

## Webpage Preview
![image](https://user-images.githubusercontent.com/79720695/125224290-94846180-e28a-11eb-9fae-05b5fa671802.png)

## Dataset Columns
Each UFO Sighting event contains the following data:
- Date*
- City*
- State*
- Country*
- Shape*
- Duration
- Comments

<i>* Represents paramters able to be filtered</i>

## Searching the data
- Once the text field is typed, the filter will be applied as soon as the user clicks outside of the textbox
- Multiple criteria can be searched at the same time
- The filter will work for partial string matches as well

### Example
- Entering "se" in City and "u" in country will find any country containing the letter "u" and city containing the string "se"
![image](https://user-images.githubusercontent.com/79720695/125225199-1b860980-e28c-11eb-9360-34f7ce010169.png)

## Future Opportunities
The current webpage meets all of the client's requirement and scope. If the client wishes to expand the scope of the project, a few drawbacks and possibilities for improvement include:
- Lack of wildcard and dynamic expressions. REGEX search capabilities can be added to fix this.
- The data is static and can become dated quickly. This can be addressed by adding webscraping functions to other popular UFO sighting websites to ensure there is always a healthy flow of new data for visitors.
