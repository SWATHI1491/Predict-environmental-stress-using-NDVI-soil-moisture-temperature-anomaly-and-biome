# Predict-environmental-stress-using-NDVI-soil-moisture-temperature-anomaly-and-biome



#### NDVI Index: vegetation health, from 0.00 to 1.00
### Soil Moisture %: available water in soil
### Temperature Anomaly C: how much hotter or cooler conditions are than normal
### Biome / Region: shown as a dropdown, though it is currently not used in the calculation

# Run Classification 

# So the model treats these as stress signals:--score increases when
## - lower NDVI = more vegetation stress
## - lower soil moisture = more water stress
## - higher temperature anomaly = more heat stress

# Stress increases when:
- NDVI is low
- soil moisture is low
- temperature anomaly is high
- rainfall is low
- humidity is low
- wind speed is high

# classifies the result:
## - score above 70 = High Water Stress
## - score above 45 = Moderate Stress
## - otherwise = Vegetation Healthy
