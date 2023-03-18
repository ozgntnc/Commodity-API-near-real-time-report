# Commodities-API

I have created it after my graudation from Istanbul Data Science Academy- Big Data&Data Engineering Bootcamp.
It aims to visualize current value of Cocoa, Coffee and Sugar commodities at stock market in near real time using Google Cloud Products.
Commodities-API started out as a simple, lightweight Open-Source API for current and historical commodities rates published by the banks and the stock market.
You may see general flow below.

![flow](https://user-images.githubusercontent.com/106034214/226112509-557beb1c-4675-4b7d-9d95-cef24037c66b.PNG)

Project starts retrieving data from Commodities API for Cocoa, Coffee, Sugar commodities. Related processors were inserted and data transforme on Nifi.
Raw data has been reshaped considering requested JSON format then data published to Kafka.

Nifi flow

![image](https://user-images.githubusercontent.com/106034214/226112864-280a5a12-efdf-4082-a49d-5bd502c20f67.png)

