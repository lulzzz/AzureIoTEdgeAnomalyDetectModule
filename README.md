# AzureIoTEdgeAnomalyDetectModule
Azure IoT Edge module for detection anomalies in DHT data

## Supported inputs and outputs  
The module supports one input "input1" for receiving DHT data.
Data is scored within the module and scored output data is provided via "output1".

## Supported desired properties  
TemperatureMeanValue -> the determined mean value for temperature
TemperatureStdDeviation -> the determined standard deviation for temperature
HumidityMeanValue -> the determined mean value for humidity
HumidityStdDeviation -> the determined standard deviation for humidity
