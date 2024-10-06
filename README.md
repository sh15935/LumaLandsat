# LumaLandsat
LumaLandsat: is a satellite-based platform designed to help farmers monitor and manage their crops more efficiently using real-time data. By leveraging Landsat 8 and 9 satellite imagery, the platform delivers critical insights on crop health, land use, and environmental conditions, enabling farmers to optimize resource usage, predict yields, and manage their fields with greater precision.

# How It Works:
•⁠  ⁠LumaLandsat. collects data from Landsat satellites, focusing on specific areas defined by the user (target pixels). 
•⁠  ⁠It provides a 3x3 grid centered on the user’s location, offering detailed data on crop health and other key indicators like the NDVI (Normalized Difference Vegetation Index).
•⁠  ⁠Users can customize the notification lead time for satellite overpasses and select the method of notification.
•⁠  ⁠The platform allows users to filter data based on cloud cover and choose specific timeframes for satellite acquisitions.
•⁠  ⁠Through an intuitive interface, farmers can visualize data on maps, download reports in CSV format, and view spectral signatures, which reflect crop health over time.

# Design 
•⁠  ⁠https://www.figma.com/design/RkfQppmoFUsTmZASesbu8n/Untitled?node-id=39-5723&node-type=frame&t=HSgvIoHZdnIATtdr-0
  
# Benefits:
•⁠  ⁠Precision Agriculture: Farmers receive detailed, real-time information, allowing them to make data-driven decisions.
•⁠  ⁠Resource Management: Optimizing irrigation, predicting yields, and tracking soil moisture helps reduce resource waste.
•⁠  ⁠Increased Productivity: By providing timely insights, the platform enhances crop health management and boosts overall productivity.
•⁠  ⁠Sustainability: Promotes sustainable farming practices by optimizing resource use and improving land management.
  
# Goals:
We aim to revolutionize agriculture by making satellite data accessible to farmers at all scales, enhancing efficiency, sustainability, and productivity. We hope to create lasting solutions that benefit not only farmers but also contribute to food security and environmental sustainability.

# Front-End
HTML/CSS: The core languages for structuring and styling web pages, providing the layout and appearance for users.
JavaScript: Adds interactivity and dynamic features to the website.
React: A JavaScript library for building fast, interactive user interfaces with reusable components.
Google Maps API: Allows embedding interactive maps on websites for users to select locations.
Chart.js: A library used to create various types of data visualizations, like graphs and charts.
Back-End
Node.js: A runtime environment for executing JavaScript server-side, enabling fast and scalable backend applications.
Express.js: A minimal web framework for Node.js to create APIs and handle server requests.
Langages de Requête
SQL: Used for querying and managing relational databases.
NoSQL: Used for non-relational databases like MongoDB, handling more flexible and scalable data structures.
Data Sources
Google Earth Engine: A cloud-based platform for planetary-scale environmental data analysis, used to retrieve satellite imagery and geospatial data.
USGS EarthExplorer API: Provides access to remote sensing data, including Landsat images and other satellite data.
NDVI (Normalized Difference Vegetation Index)
A key metric used in remote sensing to assess vegetation health by comparing near-infrared and visible light from satellite images, commonly used in environmental monitoring.
