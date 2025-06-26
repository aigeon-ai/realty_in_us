# Aigeon AI Realty in US

## Project Overview

Aigeon AI Realty in US is a Python-based server application designed to interact with the Realty in US API. This application provides a suite of tools to facilitate real estate data retrieval, including property listings, auto-complete suggestions for locations, detailed property information, and more. It is built using the FastMCP framework, which simplifies the creation and management of API tools.

## Features Overview

This server application offers a comprehensive set of features for accessing and managing real estate data in the United States. Key functionalities include:

- Auto-complete suggestions for locations such as states, cities, districts, and addresses.
- Retrieval of property listings for sale, rent, or sold properties.
- Access to detailed property information, including photos and surroundings.
- Calculation of commute times to specific locations.
- Listing of similar homes based on a given property.

## Main Features and Functionality

1. **Auto-Complete Suggestions**: 
   - Provides suggestions for locations based on partial inputs, helping users find cities, districts, and specific addresses efficiently.

2. **Property Listings**: 
   - Lists properties available for sale, rent, or that have been sold, with options for filtering and pagination.

3. **Property Details**: 
   - Retrieves detailed information about specific properties, including new home value features and associated photos.

4. **Commute Time Calculation**: 
   - Calculates the estimated commute time to a destination, considering different modes of transportation and traffic conditions.

5. **Surroundings Information**: 
   - Provides data about the surroundings of a property, including optional flood information.

## Main Functions Description

- **v2_auto_complete**: 
  - Fetches auto-complete suggestions for locations based on user input. It supports optional pagination through a limit parameter.

- **locations_auto_complete**: 
  - Similar to `v2_auto_complete`, this function provides location suggestions but is tailored for different endpoints.

- **v3_list**: 
  - Lists properties for sale, rent, or sold. It allows users to apply various filters to refine their search.

- **v3_list_similar_homes**: 
  - Returns a list of homes similar to a specified property, with options to filter by status and limit the number of results.

- **v3_detail**: 
  - Retrieves detailed information about a specific property, including optional listing details.

- **v3_get_photos**: 
  - Obtains photos associated with a particular property, enhancing the visual understanding of the property.

- **v3_get_commute_time**: 
  - Calculates the commute time to a specified address, considering different transportation types and traffic conditions.

- **v3_get_surroundings**: 
  - Provides information about the surroundings of a property, with an option to include flood data.

- **properties_list_sold**: 
  - Lists properties that have been sold in a specified city or state, allowing users to analyze past real estate transactions.

This application leverages the capabilities of the Realty in US API to deliver a robust toolset for real estate data management, making it an invaluable resource for developers and businesses in the real estate sector.