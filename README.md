# Finding Places Nearby Tool

This tool uses the Google Maps API to explore amazing places nearby. When you're short on time and new to a place, it can be challenging to discover all the hidden gems a location has to offer. The current Google Maps interface often shows only a limited number of options nearby, causing many of the best places to go unnoticed.

Additionally, the Google Maps API restricts the number of items displayed in each call to a maximum of 20. This limitation means that not all nearby places are listed, and many remain undiscovered. Some websites provide lists of the "top 50 attractions in your city," or use the Google API, but their sorting doesn't always fulfill the purpose of ensuring you don't miss out on great places.

This tool addresses these challenges by leveraging the Google Maps API to partition a selected area into smaller grids. By doing this, we ensure that all places within each grid area are listed. While grid sizes could be smaller for better precision, this would result in a significantly larger number of API calls, making it less favorable due to limitations on the number of calls allowed.

## Getting Started

To use this tool, provide an address and radius like this:

```python
find_places_nearby('SpitalFields Market, London', 500)
```

The tool will list all the amazing places nearby, using a ranking method that takes into account both the number of ratings and overall ratings on Google Maps. This makes it a valuable resource for quickly discovering hundreds of amazing places in your vicinity, including tourist attractions, markets, museums, and much more, ensuring you are never short on time when exploring a new city.

# Usage
To get started, follow these steps:

- Provide an address and a radius in meters.
- Run the find_places_nearby function.
- Explore the list of amazing places nearby.

# Dependencies
This tool depends on the Google Maps API and the Python programming language. Make sure you have the necessary libraries and credentials set up to use this tool effectively.

