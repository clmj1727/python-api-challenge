<h1  align="center">Python API Challenge</h1>
<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->

## About The Project

### Background

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

### Instructions

This activity is broken down into two deliverables, WeatherPy and VacationPy.

### Part 1: WeatherPy

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature

- Latitude vs. Humidity

- Latitude vs. Cloudiness

- Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression for Each Relationship
You should create the following plots:

- Northern Hemisphere: Temperature vs. Latitude

- Southern Hemisphere: Temperature vs. Latitude

- Northern Hemisphere: Humidity vs. Latitude

- Southern Hemisphere: Humidity vs. Latitude

- Northern Hemisphere: Cloudiness vs. Latitude

- Southern Hemisphere: Cloudiness vs. Latitude

- Northern Hemisphere: Wind Speed vs. Latitude

- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

### Part 2: VacationPy

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
   

<p align="center">
  <img src="https://github.com/clmj1727/python-api-challenge/blob/73e26ed8c64b597a5cb4d7ae0f5ca7600cfa2bf3/Images/python-api.Vacationpy1.png" alt="python-api VacationPy Output 1" width="700">
</p>


  
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

- A max temperature lower than 27 degrees but higher than 21

- Wind speed less than 4.5 m/s

- Zero cloudiness

<p align="center">
  <img src="https://github.com/clmj1727/python-api-challenge/blob/73e26ed8c64b597a5cb4d7ae0f5ca7600cfa2bf3/Images/python-api.Vacationpy2.png" alt="python-api VacationPy Output 2" width="700">
</p>
  
  
<!-- BUILT-WITH-PYTHON-AND-JUPYTER-FRAMEWORK -->
## Built with Python and Jupyter Notebook Framework 

Geoapify, OpenWeatherMapAPI, and Juypter Notebook platform was the framework used for this project.

<p  align="right">(<a  href="#readme-top">back to top</a>)</p>

  

