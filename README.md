# Calculating the Topographic Wetness Index (TWI)

The Topographic Wetness Index (TWI) can be used within flood risk analysis as described by [Pourali et al (2016)](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/s12061-014-9130-2.pdf&casa_token=556pHuCiUZQAAAAA:WO37dPPHnd7NObyhuElNhxtywKsM0oq7Z9WX6odYtXlU_oGh7VyPl4_blLJZXa4u8ztt05CSVIkqj_O_ku0). 

**Within this group assignment you should to the following exercises:**

#### 1. Answer the following questions:
  1. What is the Topographic Wetness Index? 
  2. What input data and parameters are required?
  3. How are the TWI values related to the flood probability?
  
#### 2. Search for FOSS GIS tools to calculate the TWI. 
Search within the QGIS Processing Toolbox, but also for other FOSS projects (also R or Python based) on github for example.


#### 3. Implement the calculation of the TWI using the QGIS Model Builder. 

The data for this analysis can be downloaded from [here](https://heibox.uni-heidelberg.de/f/d0392835aa3b43a7a676/). It contains a SRTM digital elevation model (DEM) with 1 arc second resolution and a vector file containing the area of interest (AOI), a region on the coast of Slovenia.  

The workflow should contain the following components:
1. Clip the DEM to the study area. 
2. If necessary, preprocess the DEM. 
2. Calculate the TWI. 

**Note:** For a short tutorial on the Model Builder watch this [video](https://www.youtube.com/watch?v=eZb5VLTc9-o&t=449s).

#### 4. Add your model to your forked repository by creating a commit and pushing it to GitHub. 


#### References

Pourali, S. H., Arrowsmith, C., Chrisman, N., Matkan, A. A., & Mitchell, D. (2016). Topography wetness index application in flood-risk-based land use planning. Applied Spatial Analysis and Policy, 9(1), 39-54.
