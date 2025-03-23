# Road_flood_banglore_maps
# Flood Prediction and Visualization on Google Maps

## Overview
This project predicts flood-prone locations based on weather conditions (rainfall intensity, temperature, humidity, and atmospheric pressure) and visualizes the results on Google Maps. The web application allows users to input weather parameters, and the backend processes the data to determine potential flood locations. The predicted locations are then marked on a Google Map displayed on the frontend.

## Features
- User inputs weather parameters (rainfall, temperature, humidity, pressure)
- A trained machine learning model predicts potential flood locations
- The predicted flood locations are displayed as markers on Google Maps
- Interactive UI for users to enter weather data and visualize results

## Tech Stack
- **Frontend:** HTML, JavaScript, Google Maps API
- **Machine Learning:** Pre-trained flood prediction model
- **Data Handling:** NumPy, Pandas

## Setup Instructions

### Prerequisites
- Python 3.x installed
- Google Maps API key (enable Maps JavaScript API)


## How It Works
1. The user inputs values for rainfall intensity, temperature, humidity, and pressure.
2. The frontend sends these values to the Flask backend via a POST request.
3. The backend runs the trained flood prediction model and determines flood-prone locations.
4. The locations are sent back to the frontend as JSON.
5. The frontend uses Google Maps API to place markers at the predicted flood locations.

## Example Input
```
Rainfall: 10.5 mm
Temperature: 30°C
Humidity: 85%
Pressure: 1015 hPa
```

## Expected Output
- The predicted flood locations appear as red markers on Google Maps.
- If no flood is predicted, no markers are displayed.

## Future Enhancements
- Improve prediction accuracy with a more advanced ML model.
- Deploy the application to a cloud server for public access.
- Add historical data visualization for better insights.

