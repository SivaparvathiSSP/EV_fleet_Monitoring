# EV_fleet_Monitoring
## Project Overview
The Real-Time EV Fleet Monitoring and Predictive Analytics Solution is designed to help fleet managers efficiently monitor and manage their electric vehicles (EVs). The system provides real-time insights into vehicle performance, battery health, charging status, and driver behavior. Additionally, it offers route optimization, vehicle maintenance alerts, cost analysis based on energy consumption, and customizable report generation.

## Features
- **User Authentication and Registration**: Secure login with email verification and role-based access control for fleet managers and drivers.
- **EV Registration and Monitoring**: Register vehicles with details like make, model, battery capacity, and service history. Track real-time data including location, speed, battery status, and charging status.
- **Route Optimization**: Suggest optimal routes based on battery levels and available charging stations.
- **Battery Health Monitoring**: Monitor battery status and alert when charging or maintenance is required.
- **Driver Behavior Analysis**: Evaluate driver habits like speed, braking, and acceleration to assess energy consumption.
- **Cost and Energy Consumption Analysis**: Calculate operational costs and energy usage with detailed interfaces.
- **Customizable Reports**: Generate and export reports based on fleet data and analytics.
- **Predictive Analytics**: Utilize a machine learning model for battery health prediction and other insights.

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: Scikit-learn (Battery Health Prediction Model)
- **Data Storage**: CSV files, SQLite
- **Visualization**: JavaScript charting libraries

## Project Structure

```
EV_Fleet_Monitoring/
├── app.py                         # Main Flask application
├── route_model.py                 # Route optimization model
├── route_optimizer.py             # Route optimization logic
├── train_model.py                 # ML model training script
├── static/                        # Static assets (CSS, JS, images)
├── templates/                     # HTML templates
├── Dataset.csv                    # Training dataset
├── battery_health_model.pkl       # Trained ML model
├── charging_stations_india.csv    # Charging station data
└── requirements.txt               # Project dependencies
```
## Usage

1. Access the web interface at `http://localhost:5000`
2. Use the dashboard to:
   - Monitor fleet status
   - Check battery health predictions
   - Plan optimized routes
   - Generate performance reports
   - View maintenance alerts

## Data Sources

- Battery health data: Custom dataset for ML model training
- Charging station data: Curated dataset of charging stations in India
- Route information: Real-time fleet tracking data


## Licence
MIT licence

