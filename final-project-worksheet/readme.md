# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Aug 27th| Project Description | Incomplete
|Sep 5th| Wireframes / Priority Matrix / Functional Components | Incomplete
|Sep 10th| External API(s) Decision / Core Application Structure (HTML, CSS, etc.) | Incomplete
|Sep 17th| Minimal Viable Product | Incomplete
|Sep 26th| Styling / Bug Fixes | Incomplete


## Project Description

For my final project, I will create a site that displays health and safety information for restaurants in New York City. Included will be sanitation grades, violations, and restaurant information. The data will be pulled from [NYC Open Data](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j) and will include several ways to view the information, such as viewing the locations of resturants/grades and sorting the data by type of violations.

## Sample Data

The data will be formatted as json. It includes a restaurant's name, sanitation grade, address, and recent inspection notes. A sample of the data can be seen here:
```
{
	"action": "Violations were cited in the following area(s).",
	"boro": "QUEENS",
	"building": "9014",
	"camis": "50038736",
	"critical_flag": "Critical",
	"cuisine_description": "Mexican",
	"dba": "DON NICO'S",
	"grade": "A",
	"grade_date": "2015-10-19T00:00:00.000",
	"inspection_date": "2015-10-19T00:00:00.000",
	"inspection_type": "Pre-permit (Operational) / Initial Inspection",
	"phone": "7182976426",
	"record_date": "2018-08-30T06:01:26.000",
	"score": "12",
	"street": "161ST ST",
	"violation_code": "05D",
	"violation_description": "Hand washing facility not provided in or near food preparation area and toilet room. Hot and cold running water at adequate pressure to enable cleanliness of employees not provided at facility. Soap and an acceptable hand-drying device not provided.",
	"zipcode": "11432"
}
```

## Wireframes
Main Wireframe
![alt text](https://res.cloudinary.com/patricklm/image/upload/v1536180146/wireframe.png)
This show basic functionality and layout of the site.

## Priority Matrix

Include a full list of features that have been prioritized based on the `Time and Importance` Matix.  

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 

- Find and use external api 
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Add user auth

## Functional Components

Based on the initial logic defined in the previous  phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string of text | 

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
