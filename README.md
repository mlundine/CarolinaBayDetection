# CarolinaBayDetection
Datasets for paper on Carolina Bay Detection

![CarolinaBayDetections](/Images/figure22.png)

# Spreadsheets

In the 'Spreadsheets' directory, you can find csvs containing the following:

Precision and recall data used to construct the PR curves.

Data used for validation on the Delaware datasets (in Spreadsheets/Validation_Delaware)

Filtered Carolina Bay detections joined with morphometry, land-use, and surface hydrologic characteristics (in Full_ACP).

Sedimentological data is available [here](github.com/mlundine/CarolinaBaySedimentology).

Data for the tile size and overlap experiment (in Spreadsheets/Tile_Size_Overlap_Experiment).

# GIS_Files

In the 'GIS_Files' directory, you can find shapefiles of Carolina Bay detections obtained through running the trained Faster R-CNN
model on the Atlantic Coastal Plain DEM tiled at various footprints and then running them through the PAEK smoothing algorithm (in GIS_Files/Final_Detections).

You can also find the unfiltered detections from various tile sizes as shapefiles (in GIS_Files/Multi_Scale_Unfiltered).

You can also find the shapefiles constructed from the tile/overlap experiment (in GIS_Files/Tile_Overlap_Experiment).

# Trained_Models

In the 'Trained_Models' directory, you can find the trained Faster R-CNN (in Trained_Models/frcnn_inference_graph), Mask R-CNN (in Trained_Models/mrcnn_inference_graph), and yolov5 (in Trained_Models/best_carolinaBays) models.

# Atlantic Coastal Plain Digital Elevation Model

![DEM_Area](/Images/figure4.png)

Instructions on how to make the mosaic of the Atlantic Coastal Plain DEM as well as the data needed are available at [here](https://drive.google.com/drive/folders/1Am4y4Bwo28dLGqFbcXSX_iT5JmSGuwLh?usp=sharing)

