# Spatial Analysis for Solar Site Suitability

The deployment of solar power plants is a key strategy for achieving net-zero emissions and mitigating the effects of climate change (IPCC, 2023).
The success of a solar power project depends significantly on site selection, which requires the careful integration of multiple geospatial and environmental factors. Geographic Information Systems (GIS) and spatial analysis tools, such as ArcGIS Pro, enable the evaluation of critical factors, including solar irradiance, slope, terrain aspect, proximity to infrastructure, environmental constraints, and legal considerations (Ayompe et al., 2021).

# Goals
Identify suitable locations for a solar plant in Seine-et-Marne (Department 77) using GIS analysis\
Verify that the selected land(s) meets specific criteria\
Ensure compliance with environmental, legal and infrastructure constraints


# Specifications
For this project, 18 criteria were considered. These criteria are divided into three broad categories based on their stage in the value chain. 
Site Assessment (Feasibility study) \
Environmental and legal compliance \
Infrastructure and Connectivity

These criteria are further explained below:

# Site Assessment
The site assessment stage identifies land areas that meet the necessary technical conditions for solar production. In this stage, we evaluate the terrain of the land and the solar potential to determine if the land is physically suitable for a solar farm

# Site Physical Assessment
**Solar Irradiance**: Areas with solar irradiance greater than 1,000 kWh.m-2 per year\
**Slope**: Slope value within the range of 5 and 15° degrees was selected\
**Aspect**: Aspect between 110–200° (southeast, south, partly southwest)\
**Temperature** (Average temperature in July): 15–40°C


# Environmental and Legal Compliance
**Land Use/Land Cover**: Areas free of forests, mountains and wetlands. Preferably low and medium vegetation\
**National parks and areas of cultural heritage**: Exclude areas\
**Zones Naturelles d’Intérêt Ecologique, Faunistique et Floristique (ZNIEFF) I et II**: Exclude areas\
**Zones Importantes pour la Conservation des Oiseaux (ZICO)**: Exclude areas\
**Zones Natura 2000 selon les directives Oiseaux et Habitats**: Exclude areas


# Infrastructure and Connectivity
**Distance to Roads**: <500m\
**Distance to populated areas**: <2500m\
**Distance to enterprises**: <3500m\
**Distance to electrical lines**: <8000m\
**Proximity to multi-storey houses**: Exclude areas within 100m of 16-storey buildings


# Optional Criteria
**Parking**: Parking with areas greater than 5000m-2\
**Polluted area**: Polluted areas greater than 5000m-2


All datasets were referenced against WGS84 to ensure spatial consistency and accuracy.

# Tools
ArcGIS Pro\
ArcGIS Online\
ArcGIS Storymap








