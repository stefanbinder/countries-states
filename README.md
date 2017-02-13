# Full Country and State list of our planet

The repository contains a JSON file with a __complete list of the 250 countries__ of the world. Included with all states of every single country.
The format of the full list is following:

```
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
```

A country-element consists of:

* code2 - Country code out of 2 letters
* code3 - Country code out of 2 letters
* name - the name of the country
* capital - the name of the capital
* region - the region/continent of the country, possible values: 
1. Asia
1. Europe
1. Africa
1. Oceania
1. Americas
1. Polar 
* subregion - the subregion of the country inside the region, possible values: 
1. Southern Asia
1. Northern Europe
1. Southern Europe
1. Northern Africa
1. Polynesia
1. Middle Africa
1. Caribbean
1. South America
1. Western Asia
1. Australia and New Zealand
1. Western Europe
1. Eastern Europe
1. Central America
1. Western Africa
1. Northern America
1. Southern Africa
1. Eastern Africa
1. South-Eastern Asia
1. Eastern Asia
1. Melanesia
1. Micronesia
1. Central Asia
* states

A state-element consists of:

* code
* name
* subdivision (can be e.g. 'London borough', 'council area', 'country', ...)
