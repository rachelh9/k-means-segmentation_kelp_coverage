# k-means-segmentation_seattleaquarium_kelp_coverage

## Scientific context
Bull kelp forest are the official marine forest in Washington, with April 16 listed as Bull Kelp Day. However, due to climate-driven ocean warming and increasing grazing pressure, 80-90% of bull kelp forests have disappeared in the Puget Sound. 
Bull kelp forests serves as an important habitat for rockfish, sea otters, herons and are a culture heritage for a lot of Pacific Northwest (PNW) tribes. They also protects coast from erosion during storms as they act as a natural physical buffer that reduces energy of incoming tidal waves. Most importantly, the marine forests acts as a huge carbon sink, absorbing 27-136 metric tons of carbon per day, which is roughly equivalent to 2000-10500 vehicles emissions per year.

To better understand the 


For more background on K-Means segmentation, its use cases, and the code and image processing behind this model, please visit https://oceancv.org/book/ClusterSegmentation_Kmeans.html# created by Katie Bigham and Atticus Carter for the University of Washington's OCEAN 462C course "Computer Vision Across the Marine Sciences".


## Dataset description
### Source imagery 
Original resolution: 4030 × 4606

Total source images: 224 images over a 30m transect back-and-forth (1 frame per 3 seconds)

Raw imagery was taken off the Seattle Aquarium Pier (Elliot Bay) during summer season at peak kelp growth using a GoPro attached to a BlueROV, as provided by Dr Zachary Randall. Pre-processed imagery was not utilised as to determine effectiveness of model without prior processing means.

## Model selection 
K-means segmentation model used for unsupervised learning 
utilised streamlit interface provided by Ada (https://github.com/AI-Ecology-Lab/K-Means-Segmentation)
selected 3-4 clusters based on performance of model on each image analysed.

## Model assessment 

## Model use-case


## Disclaimer
This project uses imagery from the Seattle Aquarium from Dr Zachary Randall. Findings, opinions and conclusions generated from this article is not affiliated and does not reflect views of the Seattle Aquarium. Imagery access can be requested at https://github.com/Seattle-Aquarium/Coastal_Climate_Resilience .
