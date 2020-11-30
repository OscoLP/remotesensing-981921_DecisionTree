## A Machine Learning Approach for Mapping Forest Vegetation in Riparian Zonesin an Atlantic Biome Environment Using Sentinel-2 Imagery

Journal: Remote Sensing (www.mdpi.com/journal/remotesensing)
Special Issue: AI Remote Sensing

Garcia Furuya et. al (2020)

Abstract: Riparian  zones  consist  of important  environmental  regions,  specifically  to  maintain  the quality of water resources. Accurately mapping forest vegetation in riparian zones is an important issue, since it may provide information about numerous surface processes that occur in these areas. Recently, machine learning algorithms have gained attention as an innovative approach to extract information  from  remote  sensing  imagery,  including  to  support  the  mapping  task  of  vegetation areas.Nonetheless, studies related to machine learning application for forest vegetation mapping in the riparian zones exclusively is still limited.Therefore, this paper presents a framework for forestvegetation mapping in riparian zones based on machine learning models using orbital multispectral images.  A  total  of  14  Sentinel-2  images  registered  throughout  the  year,  covering  a  large  riparian zone of a portion of a wide river in the Pontal do Paranapanema region, São Paulo state, Brazil, was adopted as the dataset. This area is mainlycomposed of the Atlantic Biome vegetation, and it is near to  the  last  primary  fragment  of  its  biome,  being  an  important  region  from  the  environmental planning  point  of  view.We  compared  the  performance  of  multiple  machine  learning  algorithms like k-Nearest Neighbors (kNN), Decision Tree (DT), Random Forest (RF), Support Vector Machine (SVM), and Normal Bayes (NB). We  evaluated different dates and locations with all models. Our results  demonstrated  that  the  DT  learner  has,  overall,  the  highest  accuracy  in  this  task.  The  DT algorithm also showed high accuracy when applied on different dates and in the riparian zone of another  river.  We  conclude  that  the  proposed  approach  is  appropriated  to  accurately  map forestvegetation in riparian zones, including temporalcontext.

## Repository Explanation

Here, to help ascertain the relationship between the spectral bands and the predictions, we present our decision tree models’ structure in text form. This structure can be accessed via this GitHub link, with additional information regarding it. The model was constructed with training samples from different dates, collected at the riparian zone of the Parana river. The presented structure is from the pruned tree model, with a total of 394 leaves and 787 nodes.

## Tree Structure

https://github.com/OscoLP/remotesensing-981921_DecisionTree/blob/main/Structure
