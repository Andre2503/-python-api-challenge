# # Weather and Vacation Analysis

## Overview

This challnege comprises two main deliverables: WeatherPy and VacationPy. The objective is to analyze weather data across cities worldwide and use the information to plan future vacations.

---

## Part 1: WeatherPy

### Description

The `WeatherPy` notebook visualizes the weather of 598 cities randomly selected and located at varying distances from the equator. This part uses Python, the citipy Python library, and the OpenWeatherMap API to create a model of weather across these cities.

### Requirements Fulfilled

- **Requirement 1:** Created scatter plots showcasing the relationship between weather variables and latitude.

- **Requirement 2:** Computed linear regressions for each relationship and separated the plots into Northern Hemisphere and Southern Hemisphere.

### Findings

After each pair of plots, an explanation of what the linear regression is modelling is provided, along with any noticeable relationships or findings.

---

## Part 2: VacationPy

### Description

The `VacationPy` notebook employs Python, the geoViews Python library, and the Geoapify API to visualize ideal vacation spots based on weather conditions.

### Requirements Fulfilled

- Created a map displaying a point for every city in the `city_data_df` DataFrame.
- Filtered the DataFrame based on ideal weather conditions.
- Created a new DataFrame, `hotel_df`, storing the city, country, coordinates, and humidity.
- Used the Geoapify API to locate the first hotel within 10,000 meters of the coordinates for each city.
- Added hotel names and countries in the hover message for each city in the map.

For any further questions or clarifications, feel free to reach out.

Thank you!
