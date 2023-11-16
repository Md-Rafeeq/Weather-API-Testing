# OpenWeatherMap API Testing with Postman

## Overview

This repository contains a collection of Postman requests for testing the OpenWeatherMap API. The collection includes basic tests with assertions for latitude, longitude, city name, wind speed, and temperature range.

## Prerequisites

- [Postman](https://www.postman.com/) installed on your machine.

## Getting Started

1. Clone the repository:

    bash
    git clone https://github.com/yourusername/OpenWeatherMap-Postman-Tests.git
    

2. Import the collection into Postman:
   - Open Postman.
   - Click on *Import*.
   - Choose *Collection* and upload the JSON file (`OpenWeatherMap-Tests.postman_collection.json`).

3. Run the collection:
   - Select the imported collection in Postman.
   - Click on *Run*.
   - Review the test results for each request.

## Test Cases

1. *Latitude and Longitude Check:*
   - Validates that the latitude is 51.51 and the longitude is -0.13.

2. *City Name Check:*
   - Verifies that the response contains the expected city name ("London" in this case).

3. *Wind Speed Check:*
   - Ensures that the wind speed is a positive value.

4. *Temperature Range Check:*
   - Validates that the temperature falls within a reasonable range (adjustable in the script).

## Customization

Feel free to customize the tests based on your specific requirements. Adjust assertions, add more test cases, or modify the collection to suit your testing needs.

## Author

- Mohammed Rafeeq
- rafeeqahmed.180@gmail.com
