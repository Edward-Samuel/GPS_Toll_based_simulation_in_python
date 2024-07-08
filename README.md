# GPS_Toll_based_simulation_in_python
A Python-based simulation of a GPS-based toll collection system using SimPy, Geopandas, Shapely, and Geopy for vehicle movement, toll zone detection, toll calculation, and payment processing.
## Overview

This project is a simple user authentication and car management system built with Flask. It allows users to register, log in, and reset their password using security questions. Additionally, it supports managing car data and viewing car details with a map visualization using Folium.

## Features

- User registration with username, password, security question, and security answer.
- User login.
- Password reset functionality with security question verification.
- Car data management including viewing car details and visualizing GPS data on a map.
- Geofence parameters for calculating toll based on distance traveled within a specified area.

## Project Structure

- `app.py`: Main Flask application file.
- `users.csv`: CSV file for storing user information.
- `templates/`: Directory containing HTML templates.
  - `login.html`: Login page template.
  - `register.html`: Registration page template.
  - `forgot_password.html`: Password reset page template.
  - `reset_password.html`: New password setup page template.
  - `index.html`: Car management and viewing page template.
  - `car_detail.html`: Car detail and map visualization page template.

## Requirements

- Python 3.x
- Flask
- mysql-connector-python
- geopy
- folium
