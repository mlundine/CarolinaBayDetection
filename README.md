# CarolinaBayDetection
Datasets for paper on Carolina Bay Detection

![CarolinaBayDetections](/ReadMe_Images/figure22.png)

# Spreadsheets

Link to directory [here](https://drive.google.com/drive/folders/1Z5i-MXIT-I_Dpbo_hm9YnG0Umodl_rqO?usp=sharing).

In the 'Spreadsheets' directory, you can find csvs containing the following:

Precision and recall data used to construct the PR curves.

Data used for validation on the Delaware datasets (in Spreadsheets/Validation_Delaware)

Filtered Carolina Bay detections joined with morphometry, land-use, and surface hydrologic characteristics (in Spreadsheets/Full_ACP).

Sedimentological data is available at [github.com/mlundine/CarolinaBaySedimentology](https://github.com/mlundine/CarolinaBaySedimentology).

Data for the tile size and overlap experiment (in Spreadsheets/Tile_Size_Overlap_Experiment).

Data for the principal component analysis on topo metrics.

# GIS_Files

Link to directory [here](https://drive.google.com/drive/folders/1fLN-rl-nvsm_Jy2etdGSgARrRAcllA_w?usp=sharing).

In the 'GIS_Files' directory, you can find shapefiles of Carolina Bay detections obtained through running the trained Faster R-CNN
model on the Atlantic Coastal Plain DEM tiled at various footprints and then running them through the PAEK smoothing algorithm (in GIS_Files/Final_Detections).
![detect_multi_scale](/ReadMe_Images/figure21.png)

You can also find the unfiltered detections from various tile sizes as shapefiles (in GIS_Files/Multi_Scale_Unfiltered).

You can also find the shapefiles constructed from the tile/overlap experiment (in GIS_Files/Tile_Overlap_Experiment).

# Trained_Models

Link to directory [here](https://drive.google.com/drive/folders/1j1Mmnv3WCN0-yapzcIpyhOv7JkxKwF6n?usp=sharing).

In the 'Trained_Models' directory, you can find the trained Faster R-CNN (in Trained_Models/frcnn_inference_graph), Mask R-CNN (in Trained_Models/mrcnn_inference_graph), and yolov5 (in Trained_Models/best_carolinaBays) models.
This repo has a GUI that you can use to run the models: [github.com/mlundine/tensorflow_app](https://github.com/mlundine/tensorflow_app)

# Atlantic Coastal Plain Digital Elevation Model

![DEM_Area](/ReadMe_Images/figure4.png)

Instructions on how to make the mosaic of the Atlantic Coastal Plain DEM as well as the data needed are available [here](https://drive.google.com/drive/folders/1Am4y4Bwo28dLGqFbcXSX_iT5JmSGuwLh?usp=sharing).

