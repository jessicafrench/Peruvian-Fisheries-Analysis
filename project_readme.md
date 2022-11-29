



# ** The Fishing Team ** 

##**Description:**
For this first stage of the project we will select and interesting dataset, and create some coding lines to visualize and understand the metadata. In this case we are choosing a dataset from Earth Engine to called “GFW (Global Fishing Watch) Daily Fishing Hours”. The values are displayed per band for each finishing activity depending of each gear type. The units are hours. 

We will use this data set to explore the effect of natural global effects like “El Niño 2015” in the finishing industry. We will define a specific location and compare the values of finishing hours from a normal year to a really hot year like the scenario in 2015. 

Here is the link to our data:
(https://developers.google.com/earth-engine/datasets/catalog/GFW_GFF_V1_fishing_hours)

##**Visuals**
Here is an interesting video from the global fishing watch company describing their tool and potential usages. 
https://twitter.com/i/status/1466607715350769665

<img width="560" alt="Screenshot 2022-11-28 at 20 12 08" src="https://user-images.githubusercontent.com/110002614/204437845-87b9ac57-6944-45d7-ae79-b035ee656554.png">

##**Installation**

For this project we will use our normal python 3 environment, and we have selected the following packages for our project:
ee (Earth Engine)
geemap (Google Earth Engine)
Pandas (Basic python package)
Matplotlib.pyplot (Basic python package)
Numpy (Basic python package)

If you are unsure of how to use Google Earth Engine, or you are having problems initiating the `ee.Authenticate()`, and `ee.Initialize()`, please follow the steps under the webpage of Google Earth Devlopers to help you set the first steps.

https://developers.google.com/earth-engine/guides/getstarted

##**Metadata Display and Basic Visualization**
 
 <img width="655" alt="Screenshot 2022-11-28 at 20 13 33" src="https://user-images.githubusercontent.com/110002614/204438134-ea688841-9f4b-473d-b72e-386b5c343024.png">
 
Under the Metadata Display and Basic Visualization seccions we have provided some example commands to take a quick look at what is in your dataset, and how you can access it or index it.
For this purpose we created a function named `get_image_ids`, which shows the ids per image. Later on the code we will use this name bands to present the data and values.
drifting_longlines
fixed_gear
other_fishing
purse_seines
squid_jigger
trawlers
For the “Basic Visualization” we are showing what the data looks. Furthermore,  we have specified in our region of interest which is the Peruvian coas. In this case we are creating a map to show quickly what the value of each pixel represents in the map. 

##**Roadmap**
There is a potential second stage of this project, were we could use the dataset that contains all of the vessel tracks from the Global Fishing Watch Daily Vessel Hours, and potentially find a niche regarding security coast guard for specific regions or even MPAs.


##**Contributing**
The contributions for this repo is open and we would me happy to discuss further steps we can take.

##**Support**

If you have any questions reading this Repo please do not hesitate on sending us an email with your questions. Additionally there is an awesome support area from google earth engine and github that can help you or guide you.
https://github.com/google/earthengine-api

