# rsna_issues
Tasks to do & issues to solve related to the RSNA dataset segmentation process


|Tasks|Status|Comments|
|-----|------|--------|
|Reorder segments in correct order|DONE|The code also checks the geometry of the segments and volume to make sure they are all the same|
|Removing all random voxels and any voxels outside the brain mask|TODO| stratégie de DBSCAN de Emmanuel + s'assurer que tous les voxels avec labels ont des densités appropriée (par exemple pas de l'air)|
|Making sure all images have the same parameters (space, orientation and origin) as SRI24 atlas|TODO|envisager faire une version régistrée sur atlas de Muschelli|
|Making sure all segmentations are present and segmentation masks are in the folder with original NifTI images|TODO|-|
|Plot false positives/false negatives on predictions|TODO|-|
 
