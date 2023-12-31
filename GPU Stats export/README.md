﻿
# Export GPU statistics to a database for longer retention

## What is this?

This utility fetches the statistics of my Nvidia graphics card,
processes it and then stores it in a Json file which is then auto
imported to my Database server at regular intervals.

## 

## How it works?

-   The script was built to be used with Nvidia's MSI Afterburner server
    utility which publishes data on a local webserver.

-   This utility accesses the URL and fetches the data from the server.
    It processes and converts the required data to Json format.

-   The Json data is then fed to the database server to generate
    metrics.

<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/1460f5f8ec8e26c394384791ea4fd61d226afa4c.png">
</p>

<p align="Center"><i> process script </i></p>

<br/>
<br/>

**Historical data from Influx database server.**


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/d029788812498d708e0bb771f09476bb9109c3c9.png">
</p>

<br/>


<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/1c2fab97c267e2876561ec75331e7563def1ef4f.png">
</p>

<br/>
