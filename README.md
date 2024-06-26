# Weather Forecast Web Scraping Project

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Sample Output](#sample-output)
- [Contributing](#contributing)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Overview
The **Weather Forecast Web Scraping Project** is a Python-based application designed to scrape and extract weather forecast data from a weather forecast website for the top 100 cities globally. For demonstration purposes, this project showcases data for 10 cities. The extracted data includes city names, short weather reports, and detailed forecasts for different time periods. The final output is a `.csv` file that organizes this data for easy analysis and use.

## Features
- **Real-Time Data**: Extracts up-to-date weather forecast data for the top 100 cities (demo shows 10 cities).
- **Detailed Forecasts**: Includes weather forecasts for the next 1-3 days, 4-7 days, 7-10 days, and the upcoming week.
- **Data Export**: Exports data to a `.csv` file for easy access and analysis.
- **Extensive Use of Python Libraries**: Utilizes BeautifulSoup for web scraping, Numpy for data manipulation, and Pandas for data handling and export.

## Requirements
- Python 3.x
- BeautifulSoup
- Numpy
- Pandas
- Requests

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/weather-forecast-webscraping.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd weather-forecast-webscraping
    ```
3. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```
4. **Activate the virtual environment:**
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```
5. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Run the web scraping script:**
    ```bash
    python scrape_weather.py
    ```
2. **Check the output file:**
    The script will fetch weather data for the top 10 cities and save it as a `.csv` file named `report.csv`. Open this file to view the extracted weather data.

## Data Structure
The extracted data is organized into the following columns:

- **City Name**: The name of the city.
- **Short Report**: A brief summary of the current weather.
- **1-3 Days Forecast**: Weather forecast for the next 1-3 days.
- **4-7 Days Forecast**: Weather forecast for the next 4-7 days.
- **7-10 Days Forecast**: Weather forecast for the next 7-10 days.
- **Next Week Forecast**: Weather forecast for the upcoming week.

## Sample Output
Here is an example of the first few rows of the `weather_forecast.csv` file:

| City Name | Short Report | 1-3 Days Forecast | 4-7 Days Forecast | 7-10 Days Forecast | Next Week Forecast |
|-----------|--------------|-------------------|-------------------|--------------------|--------------------|
| City A    | Detailed Data| Detailed Data     | Detailed Data     | Detailed Data      | Detailed Data      |
| City B    | Detailed Data| Detailed Data     | Detailed Data     | Detailed Data      | Detailed Data      |
| City C    | Detailed Data| Detailed Data     | Detailed Data     | Detailed Data      | Detailed Data      |
| City D    | Detailed Data| Detailed Data     | Detailed Data     | Detailed Data      | Detailed Data      |

## Contributing
Contributions to this project are welcome. Here’s how you can contribute:

1. **Fork the repository.**
2. **Create a new branch for your feature or bug fix:**
    ```bash
    git checkout -b feature/amazing-feature
    ```
3. **Make your changes.**
4. **Commit your changes:**
    ```bash
    git commit -m 'Add some amazing feature'
    ```
5. **Push to the branch:**
    ```bash
    git push origin feature/amazing-feature
    ```
6. **Open a pull request.**

## Contact
For questions or support, please contact:

- **Your Name**: [shivanshpal31@gmail.com](mailto:shivanshpal31@gmail.com)
- **GitHub**: [https://github.com/shivanshpal31](https://github.com/shivanshpal31)

## Acknowledgments
- **BeautifulSoup**: For making web scraping easier.
- **Inspired by**: Various weather forecast projects and web scraping tutorials.

Feel free to modify the content to better suit your project specifics and personal details. This README provides a detailed and organized introduction to your weather scraping project, making it easy for others to understand, use, and contribute.
