# k-means-segmentation_seattleaquarium_kelp_coverage

## Scientific context
Bull kelp forests are the official marine forest in Washington, with April 16 listed as Bull Kelp Day. However, due to climate-driven ocean warming and increasing grazing pressure, 80-90% of bull kelp forests have disappeared in the Puget Sound. Bull kelp forests serve as an important habitat for rockfish, sea otters, and herons, and are a cultural heritage for many Pacific Northwest (PNW) tribes. They also protect the coast from erosion during storms, acting as a natural physical buffer that reduces the energy of incoming tidal waves. Most importantly, the marine forests act as a huge carbon sink, absorbing 27-136 metric tons of carbon per day, which is roughly equivalent to the emissions from 2000-10500 vehicles per year.

Elliot Bay is located off the Seattle Aquarium Pier, which supports a huge kelp colony that is most actively growing in the summer. Kelp surveys are done by the Seattle Aquarium under the Urban Kelp Research Project, utilising remotely operated vehicles (ROVs) such as ROV Nereo and ROV Lutris. 


## Dataset description
### Source imagery 
Original resolution: 4030 × 4606

Total source images: 224 images over a 30m transect back-and-forth (1 frame per 3 seconds)

Raw imagery was taken off the Seattle Aquarium Pier (Elliot Bay) during the summer season at peak kelp growth using a GoPro attached to a BlueROV, as provided by Dr Zachary Randall. Pre-processed imagery was not utilised to determine the model's effectiveness without prior processing.

## Model selection 
K-means segmentation model used for unsupervised learning of 4 selected kelp images. The streamlit interface for the k-means image segmentation was provided by Ada Carter (https://github.com/AI-Ecology-Lab/K-Means-Segmentation). 3-4 clusters were selected and merged based on the model's performance for each analysed image.

For more background on K-Means segmentation and its use cases, please visit https://oceancv.org/book/ClusterSegmentation_Kmeans.html#, created by Dr Katie Bigham and Ada Carter for the University of Washington's OCEAN 462C course "Computer Vision Across the Marine Sciences".

## Model assessment 


## Model use-case
This model works well for calculating percent area covered by kelp within a local surveying region. Assuming a larger area of kelp coverage could support more biodiversity, the k-means model could be useful in synthesising multiple datasets to help map kelp canopies in Washington, specifically for the Washington Floating Kelp Statewide Linear Extent published by the Washington State Department of Natural Resources. Learning about kelp growth patterns could also help bull kelp restoration throughout Elliot Bay and the broader Puget Sound area. However, it is to note that k-means is more accurate for colour-based clusters instead of species-based clusters.

## Disclaimer
This project uses imagery from the Seattle Aquarium from Dr Zachary Randall. Findings, opinions and conclusions generated from this article is not affiliated and does not reflect views of the Seattle Aquarium. Imagery access can be requested at https://github.com/Seattle-Aquarium/Coastal_Climate_Resilience .
