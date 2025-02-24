---
cssclasses:
  - cards
---
### Facilities
```dataview
TABLE
	"> " + Note
FROM #Location/Facility 
WHERE contains(location, link("USS Nightingale"))
```
### Shuttles
The Nightingale is equipped with dozens of shuttles. Some notable ones are listed below!
```dataview
TABLE
	"> " + Note
FROM #Location/Ship/Shuttle
WHERE contains(location, link("USS Nightingale"))
```