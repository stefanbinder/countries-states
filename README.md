# Full Country and State list of our planet

The repository contains a JSON file with a __complete list of the 250 countries__ of the world. Included with all states of every single country.
The format of the full list is following:

[
	{
		"code2": "AT",
	    "code3": "AUT",
	    "name": "Austria",
	    "capital": "Vienna",
	    "region": "Europe",
	    "subregion": "Western Europe",
	    "states": [
		    {
		        "code": "B",
		        "name": "Burgenland",
		        ubdivisio
		    },
		    ...
		]
	},
	...
]

A country-element consists of:

* code2 - Country code out of 2 letters
* code3 - Country code out of 2 letters
* name - the name of the country
* capital - the name of the capital
* region - the region/continent of the country, possible values: 
⋅⋅* Asia
⋅⋅* Europe
⋅⋅* Africa
⋅⋅* Oceania
⋅⋅* Americas
⋅⋅* Polar 
* subregion - the subregion of the country inside the region, possible values: 
⋅⋅* Southern Asia
⋅⋅* Northern Europe
⋅⋅* Southern Europe
⋅⋅* Northern Africa
⋅⋅* Polynesia
⋅⋅* Middle Africa
⋅⋅* Caribbean
⋅⋅* South America
⋅⋅* Western Asia
⋅⋅* Australia and New Zealand
⋅⋅* Western Europe
⋅⋅* Eastern Europe
⋅⋅* Central America
⋅⋅* Western Africa
⋅⋅* Northern America
⋅⋅* Southern Africa
⋅⋅* Eastern Africa
⋅⋅* South-Eastern Asia
⋅⋅* Eastern Asia
⋅⋅* Melanesia
⋅⋅* Micronesia
⋅⋅* Central Asia
* states

A state-element consists of:

* code
* name
* subdivision (can be e.g. 'London borough', 'council area', 'country', ...)
