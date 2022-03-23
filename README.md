# Artificial-neural-network-for-star-tracker-centroid-computation



We propose a unique dataset with star images, their centroids and a new centroid algorithm based on machine learning, that significantly improves star image centroid performance. It can be used by scientists to refine various techniques and algorithms related to photogrammetry, astrometry, and photometry. 

Our script "Dataset_GAIAmp" allows to save equatorial coordinates of stars, their magnitudes, proper motions, etc. as labels. In addition, you can build your dataset based on different sky surveys and catalogs available in the Astroquery library. The user can also select image resolution, limiting magnitudes, crop sizes, etc.

The script "ANN_star_centroids" involves loading a dataset, creating a DataLoader, creating a Neural Network Model, training and testing it.

