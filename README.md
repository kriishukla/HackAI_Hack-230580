# Temperature Alert and Weather Forecast Agent

This project involves the creation of two agents, a Temperature Alert Agent, and a Message Printer Agent. The Temperature Alert Agent monitors temperature conditions and sends alerts to the Message Printer Agent when the temperature exceeds defined thresholds. Additionally, the project includes a Weather Forecast feature for a specified location.

## Table of Contents

- [Introduction](#introduction)
- [Agents](#agents)
- [Usage](#usage)
- [Weather Forecast](#weather-forecast)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contact](#contact)

## Introduction

This project consists of two main components:

1. **Temperature Alert Agent**: Monitors the temperature at a specified location using OpenWeatherMap API. It sends alerts to the Message Printer Agent when the temperature exceeds predefined minimum or maximum thresholds.

2. **Message Printer Agent**: Receives and prints messages/alerts sent by the Temperature Alert Agent.

2. **Weather Predictor**: Predict and tells about the weather through intensive Deep learning Algorithms



## Agents

### Temperature Alert Agent

- **Name**: alert_agent
- **Seed**: alert_agent_seed
- **Endpoint**: http://localhost:8000
- **Port**: 8000

### Message Printer Agent

- **Name**: message_printer
- **Endpoint**: http://localhost:8001
- **Port**: 8001

## Usage

To use this project, you only need to follow one simple step:

1. Run the main script `main.py`:


python main.py


### Prerequisites

- Python (>=3.6)
- uagents package
- requests package

You can install the required Python packages using pip:


pip install uagents 
pip install requests
pip install numpy
pip install pandas
pip install matplotlib
pip install tensorflow


## Installation
Clone the repository to your local machine:

git clone https://github.com/kriishukla/HackAI_Hack-230580/edit/master/README.md
cd temperature-alert-forecast-agent
Configure the agents and set up your environment as mentioned in the Configuration section.

Run the agents using Python:

python main.py
### Weather Forecast
The project also provides the option to retrieve weather forecasts for a specified location. To use this feature:

Run the project as mentioned in the Usage section.

When prompted, enter the location for which you want to get the weather forecast.

The weather forecast will be fetched from OpenWeatherMap API and saved to a file named prediction.txt.

## Configuration
Make sure to configure the agents and API keys:

Temperature Alert Agent: Configure the agent with your desired settings such as location, minimum and maximum temperature thresholds, API key, and endpoint.

Message Printer Agent: No configuration is needed for the Message Printer Agent.

OpenWeatherMap API Key: Obtain an API key from OpenWeatherMap and set it in the api_key variable.



Feel free to reach out with any feedback or suggestions.
