# Aigeon AI Realty in US

## Project Overview

Aigeon AI Realty in US is a Python-based server application designed to interact with the Realty in US API, providing users with a comprehensive suite of tools to access and manipulate real estate data. This project leverages the FastMCP framework to create a streamlined interface for querying property information, obtaining property details, and analyzing real estate market trends in the United States.

## Features Overview

This project offers a variety of features that facilitate real estate data retrieval and analysis, including:

- Autocomplete suggestions for locations and properties.
- Comprehensive property listings for sale, rent, and sold properties.
- Detailed property information retrieval.
- Similar homes listing based on property ID.
- Commute time calculations to specific destinations.
- Surroundings data around a property, including optional flood information.

## Main Features and Functionality

1. **Location Autocomplete**: Provides suggestions for states, cities, districts, addresses, and zip codes to assist users in refining their property searches.

2. **Property Listings**: Offers detailed listings of properties available for sale, rent, or that have been sold, with various filters and options to tailor the search results.

3. **Property Details**: Retrieves detailed information about specific properties, including new home value features.

4. **Similar Homes**: Lists properties similar to a specified property, aiding users in exploring comparable real estate options.

5. **Commute Time Calculation**: Computes the time required to travel to a specified destination from a property, with options for different transportation modes and traffic conditions.

6. **Surroundings Information**: Provides data about the surroundings of a property, with an option to include flood information.

## Main Functions Description

### `v2_auto_complete`

- **Description**: Provides autocomplete suggestions for locations and properties.
- **Parameters**:
  - `input` (str): Describes states, cities, districts, addresses, or zip codes.
  - `limit` (int, float, or None): Specifies the number of items per response for paging purposes.

### `locations_auto_complete`

- **Description**: Offers autocomplete suggestions for cities, districts, and places.
- **Parameters**:
  - `input` (str): Name of cities, districts, or places.

### `v3_list`

- **Description**: Lists properties for sale, rent, or sold with various options and filters.
- **Parameters**: None.

### `v3_list_similar_homes`

- **Description**: Lists homes similar to a specified property.
- **Parameters**:
  - `property_id` (str): The property ID to find similar homes.
  - `limit` (int, float, or None): Number of items per response for paging.
  - `status` (str or None): Status of the property (e.g., for_sale, sold).

### `v3_detail`

- **Description**: Retrieves detailed information about a property.
- **Parameters**:
  - `property_id` (str): The property ID to retrieve details.
  - `listing_id` (str or None): The listing ID associated with the property.

### `v3_get_photos`

- **Description**: Retrieves photos of a specified property.
- **Parameters**:
  - `property_id` (str): The property ID to get photos.

### `v3_get_commute_time`

- **Description**: Calculates commute time to a specified destination.
- **Parameters**:
  - `destination_address` (str): The destination address.
  - `property_id` (str): The property ID for the starting point.
  - `transportation_type` (str or None): Mode of transportation (e.g., driving, walking).
  - `with_traffic` (bool or None): Whether to consider traffic conditions.

### `v3_get_surroundings`

- **Description**: Provides data about the surroundings of a property.
- **Parameters**:
  - `property_id` (str): The property ID to get surroundings data.
  - `enable_flood` (bool or None): Option to include flood information.

### `properties_list_sold`

- **Description**: Lists properties that have been sold in a specified city and state.
- **Parameters**:
  - `city` (str): The city name.
  - `state_code` (str): The state code.

This README provides a concise overview of the Aigeon AI Realty in US project, detailing its features and main functions to facilitate user interaction with real estate data in the United States.