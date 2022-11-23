# d3_fers
A walkthrough of NSW Functional Economic Regions (FERs) with some simple ABS population data, using D3 and scrollama. 

Maps are tricky to work with in static visualisations, especially in a state like NSW where Sydney is extremely dense but also extremely small relative to the size of the rest of the state, so the map's just a sea of white with a deep blue on the coast for the Metro LGAs. 

I wanted to use scrollama and D3 to explore other ways to represent geographic data, in particular using the zoom and filtering functionality of D3.

Index file is a modified version of the scrollama <a href="https://russellsamora.github.io/scrollama/sticky-side/">sticky side example</a>.
The two geojson files are modified versions of the ABS's 2022 Australian LGAs shapefile, filtered to FERs and LGAs. The files have been simplified for page functionality purposes, as their original size (around 50MB) was too big for the page to comfortably load and manipulate the data.
