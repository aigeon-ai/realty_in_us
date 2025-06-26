# Aigeon AI Realty in US

## Project Overview

**Aigeon AI Realty in US** is a Python-based server application designed to interact with the Realty in US API, providing a comprehensive set of tools for accessing real estate data in the United States. This application leverages the FastMCP framework to offer a suite of functionalities that facilitate property searches, detailed property information retrieval, and various real estate data analytics.

## Features Overview

This project provides a robust interface to interact with real estate data through the Realty in US API. Key features include:

- Auto-complete suggestions for locations and addresses.
- Comprehensive property listings with filtering options.
- Detailed property information retrieval.
- Similar property suggestions.
- Commute time calculations to specified destinations.
- Surroundings data for properties.
- Access to property photos and other media.

## Main Features and Functionality

1. **Auto-Complete Suggestions**: 
   - Retrieve suggestions for states, cities, districts, addresses, and zip codes to assist in property searches.

2. **Property Listings**:
   - Access lists of properties for sale, rent, or sold, with options to filter results based on various criteria.

3. **Property Details**:
   - Obtain detailed information about specific properties, including new home value features.

4. **Similar Homes**:
   - Find properties similar to a specified property, based on various criteria.

5. **Commute Time Calculation**:
   - Calculate the commute time from a property to a specified destination using different modes of transportation.

6. **Surroundings Data**:
   - Retrieve data about the surroundings of a property, including optional flood information.

7. **Property Photos**:
   - Access and retrieve photos of properties.

## API Endpoints or Main Functions Description

The application provides several key functions, each corresponding to an API endpoint:

- **`v2_auto_complete`**: Provides auto-complete suggestions for locations and addresses.
- **`locations_auto_complete`**: Similar to `v2_auto_complete`, but specifically for location names.
- **`v3_list`**: Lists properties for sale, rent, or sold, with options for filtering.
- **`v3_list_similar_homes`**: Lists homes similar to a specified property.
- **`v3_detail`**: Retrieves detailed information about a property.
- **`v3_get_photos`**: Retrieves photos of a specified property.
- **`v3_get_commute_time`**: Calculates commute time to a specified destination.
- **`v3_get_surroundings`**: Retrieves surroundings data for a property.
- **`properties_list_sold`**: Lists properties that have been sold in a specified city and state.

## Configuration Parameters Explanation

Each function in the application accepts specific parameters that configure the request to the Realty in US API:

- **`input`**: A string input for location or address suggestions.
- **`limit`**: An integer or float specifying the number of items per response for paging purposes.
- **`property_id`**: A unique identifier for a property, used in various functions to specify the target property.
- **`listing_id`**: An optional identifier for a property listing.
- **`destination_address`**: The address used to calculate commute times.
- **`transportation_type`**: Specifies the mode of transportation for commute time calculations.
- **`with_traffic`**: A boolean indicating whether to include traffic conditions in commute time calculations.
- **`enable_flood`**: A boolean indicating whether to include flood information in surroundings data.

This application is designed to provide a seamless interface for accessing and analyzing real estate data, making it an invaluable tool for real estate professionals and enthusiasts alike.