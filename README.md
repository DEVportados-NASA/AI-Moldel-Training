# AI-Model-Training

## Overview

This project demonstrates training a **Random Forest Regressor** for weather prediction using historical weather data. The model predicts key weather parameters such as temperature, humidity, wind speed, precipitation, solar radiation, and cloud cover for a given city and date.

The trained model, along with the city label encoder, is exported as a `.pkl` file for easy use in other applications, including Python scripts or web backends.

---

## Features

- Predicts:
  - Maximum temperature
  - Minimum temperature
  - Average temperature
  - Precipitation
  - Cloud cover
- Handles multiple cities
- Accepts date input and encodes it into features for the model
- Easy integration via a `.pkl` file

---

## Libraries

The following Python libraries are required:

```text
pandas
numpy
scikit-learn
joblib
