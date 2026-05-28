# NASA API Data Explorer

This project demonstrates how to access and utilize various public APIs provided by NASA to retrieve and manipulate space-related data.

## Project Overview

The goal of this notebook is to:
- Obtain and manage a NASA API key.
- Make API requests to different NASA endpoints.
- Process the retrieved JSON data into a structured pandas DataFrame.
- Export the processed data to a CSV file for further analysis or sharing.

## Features

- **Astronomy Picture of the Day (APOD)**: Fetches and displays the daily astronomy picture along with its title and explanation.
- **Near-Earth Object Web Service (NEOWS)**: Retrieves data about Near-Earth Objects (asteroids) based on a specified date range, processes it, and saves it into a CSV file.

## Setup

To run this project, you will need:

1.  **NASA API Key**: 
    - Go to the [NASA API website](https://api.nasa.gov/) and request a free API key. 
    - Once you have your API key, replace the placeholder `"A8aLr93b18zjr9HlwwGzgRhnOGfV5bTPmcswq07m"` with your actual key in the `api_key` variable within the notebook.

2.  **Python Environment**: Ensure you have Python installed.

3.  **Required Libraries**: Install the necessary Python libraries using pip:
    ```bash
    pip install requests pandas IPython
    ```

## Usage

1.  **Clone the Repository (if applicable)**:
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```
2.  **Open the Jupyter/Colab Notebook**: Open the `.ipynb` file in Jupyter Notebook or Google Colab.
3.  **Run Cells**: Execute the cells sequentially.
    - The first few cells will fetch the APOD.
    - Subsequent cells will fetch and process NEO data, displaying the first few rows of the DataFrame and exporting the full dataset to `neo_asteroids.csv`.

## Technologies Used

- Python
- `requests` library for making HTTP requests
- `pandas` library for data manipulation and analysis
- `IPython.display` for displaying images in the notebook

```
