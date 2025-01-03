# Geospatial Data Visualization of Tanzania’s Administrative Boundaries Using Python


---

## Project Description

This project focuses on visualizing the administrative boundaries of Tanzania, including wards, districts, and regions, using geospatial data and Python. The visualization provides insights into Tanzania’s spatial structure, enabling better understanding and decision-making for research, policy, and governance. The project also integrates spatial data processing and analysis to explore demographic, economic, or environmental patterns.

The tools used in this project include Geopandas, Matplotlib, Shapely, and Folium, providing static and interactive visualizations.


---

## Project Objectives

1. To visualize Tanzania’s administrative boundaries, including regions, districts, and wards.


2. To explore, process, and analyze geospatial data using Python.


3. To create aesthetically appealing and informative maps for data-driven decision-making.




---

## Technologies Used

Programming Language: Python

Libraries:

`Geopandas:` For geospatial data manipulation and visualization.

`Matplotlib:` For creating static maps and plots.

`Shapely:` For geometric operations.

`Folium:` For interactive web-based mapping.

`Pandas:` For handling attribute data.




---

## Data Sources

The shapefiles and other geospatial datasets for Tanzania were sourced from:

1. Tanzania National Bureau of Statistics (NBS).

2. OpenStreetMap and other open geospatial repositories.

3. Custom data collected and aligned with administrative boundaries.



---





---

## Key Features

1. Static Map Visualizations:

Visualize Tanzania’s regions, districts, and wards with customized colors, labels, and boundaries.

Add thematic layers such as population density or infrastructure.



2. Interactive Mapping:

Create interactive maps using Folium with zoom and pan capabilities.

Add popups and tooltips to display additional information.



3. Geospatial Analysis:

Perform spatial operations such as buffering, clipping, and area calculations.

Merge attribute data to create thematic maps.



4. Export Maps:

Save visualizations as static images or export them as interactive HTML files.





---

### Examples

Visualizing Administrative Boundaries

Static visualization of Tanzania’s regions:

geo_data.plot(figsize=(10, 10), color="lightblue", edgecolor="black")
plt.title("Regions of Tanzania")
plt.show()

Interactive Mapping

Interactive visualization using Folium:

import folium

# Initialize map
tanzania_map = folium.Map(location=[-6.369028, 34.888822], zoom_start=6)

# Add ward boundaries
folium.GeoJson("data/wards.geojson", name="Ward Boundaries").add_to(tanzania_map)

# Save and display
tanzania_map.save("outputs/tanzania_map.html")


---

Project Outputs

1. Static maps for regions, districts, and wards.


2. Interactive maps embedded with demographic or environmental data.


3. Analytical insights on spatial patterns, clustering, and attributes.




---

Future Work

Integrate real-time geospatial data for dynamic visualizations.

Incorporate predictive modeling using spatial machine learning.

Expand the project to other countries or regions.



---

Contact

For inquiries or contributions, contact:
Name: Jabulente
Email: jabulente@hotmail.com
GitHub: Jabulente 
