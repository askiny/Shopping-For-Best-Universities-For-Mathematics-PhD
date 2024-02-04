# Shopping-For-Best-Universities-For-Mathematics-PhD

In this project; I examined the relationships of universities, countries and advisors at the Mathematics PhD level with dynamic network maps. I evaluated the best countries and good universities to do a PhD in mathematics.

# Dataset Information

This question is about Math Genealogy and I am going to use the data that was already scraped by Jeremy Kun. Data consists of historical data on PhD dissertation. A sample entry would look like as follows:

{
  "id": 13325,
  "name": "Daniel Gray Quillen",
  "thesis": "Formal Properties of Over-Determined Systems of Linear Partial Differential Equations",
  "school": "Harvard University",
  "country": "UnitedStates",
  "year": 1964,
  "subject": "19—K-theory",
  "advisors": [
    7583
  ],
  "students": [
    62762,
    67441,
    30219,
    62770,
    62764,
    62771
  ]
},

The name of the person who wrote the thesis is Daniel Gray Quillen, and his unique id is 13325. His thesis title is "Formal Properties of Over-Determined Systems of Linear Partial Differential Equations". He got his PhD degree from Harvard in 1964. His advisor's id is 7583 (Raul Bott). The advisors field is an array since a student might have more than 1 advisor. The student field indicates Quillen had 6 PhD students with those specific id's.

# Libraries Used
Pandas, Json, Requests, Networkx, Gravis
