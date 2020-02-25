# Coursera_Capstone
Understand neighborhoods using Data Science

### Problem description
Let's say for instance that you're willing to open a store (i.e. franchise) in a city you barely know. Besides from the obvious answer: "_Go to the city center!_", what else you can do to find the sweetest spot in town? There's a chance that analyzing neighborhoods will give you some more '_hidden_' information to better solve the main question: '_Where should I open the store?_', or at least is a starting point to your endeavour.

### Data description
That's a more obvious question: '_What kind of data do I need to help solve the main question?_'. Short answer: '_Well, that's store and neighborhood information_'. And the other question: '_Where do I get all that information?_', let's find out:
- Venue information: information provided by [Foursquare API](https://developer.foursquare.com/docs/api/venues/search) and [REST API](https://en.wikipedia.org/wiki/Representational_state_transfer) methods to retrieve all sort of details regarding venues.
- Neighborhood information: to get a better understanding of '_How's this neighborhood?_'.
  - Shape: that solves the question of '_How big or small a neighborhood is_', thankfully this information is provided as a [GIS](https://en.wikipedia.org/wiki/GIS_file_formats) file from the [Open Data Portal of Toronto](https://open.toronto.ca/dataset/neighbourhoods/). This file provides information from each neighborhood of Toronto, such as: area code, name, latitude and longitude of neighborhood's centroid, area shape and length.
  - Demographics: responds to '_Who lives there?_', also from the [Open Data Portal of Toronto](https://open.toronto.ca/dataset/neighbourhood-profiles/), we'll get information reagarding age, population, dwells and much more for each neighborhood.
