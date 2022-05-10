# Agisoft_Metashape_SfM_Batchfiles
Batchfiles to process large Structure from Motion (SfM) 3D models in Agisoft Metashape.

4 Agisoft Metashape batch files are included. The workflow utilising these batch files is outlined in detail in the following article:
 
      Link pending article publishing
      
A breif summary is offered below:

  - Batch File: Alignment: Add all photos of the entire surveyed region and align for a low density point cloud
  - User Input: Duplicate and subdivide the alignmed images and point cloud into smaller regions (sub-zones)
  - Batch File: Build high Density Point Cloud: Increases the point cloud density for all sub-zones
  - User Input: Filter and delete low confidence point cloud data
  - Batch File: Build Mesh: Meshes dense point clouds
  - User Input: Trim perimeter of the mesh, which will natural warp, to ensure smooth meshing with neighbouring sub-zones
  - Batch File: Close Holes, Decimate and Build Textures: Mesh holes are closed, geometries decimated and textures added.

The end result of this workflow can be found online at V3Geo: 

    https://v3geo.com/model/367
    
Please do contact the author of the article/this github listing should you have any questions:

    m.allison@bham.ac.uk
