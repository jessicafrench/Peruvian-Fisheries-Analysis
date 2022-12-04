# **The Fishing Team** 

####### **Click This Link to Launch the Notebook in Your Browser**
launch with myBinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EDS220-Fall2022-org/homework-2-mac/HEAD)

## **Authors:**

- Jessica French - jfrench@ucsb.edu
- Pol Carbo Mestre - pcarbomestre@ucsb.edu
- Javier Patrón - jpatron@ucsb.edu

## **Description:**

The purpose of this notebook is to explore Global Fishing Watch's dataset showing daily fishing effort as inferred fishing hours daily. This notebook will show how to read in the dataset, visualize the data using google earth engine, and give an overview of how the data can be used to explore differences in fishing effort within and outside Peru's EEZ and how fishing effort is impacted by El Niño Southern Oscillation (ENSO) events.

#### **Visuals**
Here is an interesting video from the global fishing watch company describing their tool and potential usages. 
https://twitter.com/i/status/1466607715350769665

<img width="560" alt="Screenshot 2022-11-28 at 20 12 08" src="https://user-images.githubusercontent.com/110002614/204437845-87b9ac57-6944-45d7-ae79-b035ee656554.png">

## Contents:
- peruvian-fisheries-effort.ipynb: Jupyter notebook contains all information and description of the project including GEE Access, Data visualization, Metadata description, and our case example.
- environment.yml: This is our conda environment file used to create our Binder environment. Click on the file to see the list of dependencies and channels we prioritize for the project.

#### **Installation of GEE**

If you are unsure of how to use Google Earth Engine, or you are having problems initiating the `ee.Authenticate()`, and `ee.Initialize()`, please follow the steps under the webpage of Google Earth Devlopers to help you set the first steps.

https://developers.google.com/earth-engine/guides/getstarted

## **Datasets**
 <img width="655" alt="Screenshot 2022-11-28 at 20 13 33" src="https://user-images.githubusercontent.com/110002614/204438134-ea688841-9f4b-473d-b72e-386b5c343024.png">
 
 
The Global Fishing Watch (GFW) provides an open platform to access Automatic Identification System (AIS) data from commercial fishing activities. In this project we are using their API to explore the data and use it for our case example.
 
Global Fishing watch - https://developers.google.com/earth-engine/datasets/catalog/GFW_GFF_V1_fishing_hours


## **Roadmap and Contribuation**
There is a potential second stage of this project, were we could use the dataset that contains all of the vessel tracks from the Global Fishing Watch Daily Vessel Hours, and potentially find a niche regarding security coast guard for specific regions or even MPAs. 

The contributions for this repo is open and we would like to encourage our public people to wranggle and explore this dataset.

## **Support**
If you have any questions reading this Repo please do not hesitate on sending us an email with your questions. Additionally there is an awesome support area from google earth engine and github that can help you or guide you.
https://github.com/google/earthengine-api
