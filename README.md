# **Assessing Trends in Fishing Effort Inside and Outside Peru's EEZ Using AIS Data from Global Fishing Watch.** 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EDS220-Fall2022-org/homework-2-mangrove-team.git/HEAD?labpath=peruvian-fisheries-effort.ipynb)

## **Authors:**

- Jessica French - jfrench@bren.ucsb.edu
- Pol Carbó Mestre - pcarbomestre@bren.ucsb.edu
- Javier Patrón - jpatron@bren.ucsb.edu

## **Description:**

The purpose of this notebook is to explore Global Fishing Watch's dataset on daily fishing effort, as inferred from fishing hours per day. In this notebook (peruvian-fisheries-effort.ipynb), we will demonstrate how to read and visualize the data, and provide an overview of how the selected data can be used to explore differences in fishing effort within and outside Peru's Exclusive Economic Zone, and whether fishing effort is impacted by El Niño Southern Oscillation (ENSO) events.

#### **Visuals**
Here is an interesting video from the Global Fishing Watch that describes their tool and potential uses:

https://twitter.com/i/status/1466607715350769665

<p align="center">
<img width="560" alt="Screenshot 2022-11-28 at 20 12 08" src="https://user-images.githubusercontent.com/110002614/204437845-87b9ac57-6944-45d7-ae79-b035ee656554.png">
</p>

## Contents:
- _peruvian-fisheries-effort.ipynb_: Jupyter notebook contains all information and description of the project including GEE Access, Data visualization, Metadata description, and our case example.
- _environment.yml_: This is our conda environment file used to create our Binder environment. Click on the file to see the list of dependencies and channels we prioritize for the project.

#### **Installation of GEE**
If you are unsure of how to use Google Earth Engine, or you are having problems initiating the `ee.Authenticate()`, and `ee.Initialize()`, please follow the steps under the webpage of Google Earth Devlopers to help you set the first steps.

https://developers.google.com/earth-engine/guides/getstarted

## **Datasets**
<p align="center">
<img width="655" alt="Screenshot 2022-11-28 at 20 13 33" src="https://user-images.githubusercontent.com/110002614/204438134-ea688841-9f4b-473d-b72e-386b5c343024.png">
</p>

 
The Global Fishing Watch (GFW) provides an open platform to access Automatic Identification System (AIS) data from commercial fishing activities. In this project we are using their API to explore the data and use it for our case example. For more information and details check our .ipynb notebook.
 
Global Fishing watch - https://developers.google.com/earth-engine/datasets/catalog/GFW_GFF_V1_fishing_hours


## **References**
1. Christensen, V., de la Puente, S., Sueiro, J. C., Steenbeek, J., & Majluf, P. (2014). Valuing seafood: The Peruvian fisheries sector. Marine Policy, 44, 302–311. https://doi.org/10.1016/j.marpol.2013.09.022
2. El Niño | National Geographic Society. (n.d.). Retrieved November 29, 2022, from https://education.nationalgeographic.org/resource/el-nino
3. FAO. Fishery and Aquaculture Statistics. Global capture production 1950-2020 (FishStatJ). 2022. In: FAO Fisheries and Aquaculture Division [online]. Rome. Updated 2022.
4. GFW (global fishing watch) daily fishing hours | Earth Engine Data catalog | google developers (no date) Google. Google. Available at: https://developers.google.com/earth-engine/datasets/catalog/GFW_GFF_V1_fishing_hours (Accessed: November 30, 2022).
5. Global Fishing Watch Application Programming Interfaces (API) Documentation (https://globalfishingwatch.org/our-apis/documentation#introduction)
6. Kroodsma, David A., Juan Mayorga, Timothy Hochberg, Nathan A. Miller, Kristina Boerder, Francesco Ferretti, Alex Wilson et al. "Tracking the global footprint of fisheries." Science 359, no. 6378 (2018): 904-908. DOI:10.1126/science.aao5646.

## **Roadmap and Contribuation**
There is a potential second stage of this project, were we could use the dataset that contains all of the vessel tracks from the Global Fishing Watch Daily Vessel Hours, and potentially find a niche regarding security coast guard for specific regions or even MPAs. 

The contributions for this repo is open and we would like to encourage our public people to wranggle and explore this dataset.

## **Support**
If you have any questions reading this Repo please do not hesitate on sending us an email with your questions. Additionally there is an awesome support area from google earth engine and github that can help you or guide you.
https://github.com/google/earthengine-api
