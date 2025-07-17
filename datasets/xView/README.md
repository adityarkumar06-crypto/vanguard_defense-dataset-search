1129 (847 with labels) images, 800645 objects total across 60 classes.

Remote aerial images with annotation


Download and trainig:
Dataset can be obtained from https://challenge.xviewdataset.org/download-links   

xView/      
├── file.geojson    
├── train_images/           
├── val_images/            
└── (conversion)
    ├── images/
    │   ├── train/         
    │   └── val/            
    └── labels/
        ├── train/          
        └── val/  

Training and validation images can be downloaded, but only training images offer labels. Files must be converted as seen above into a YOLO trainable format with an appropriate data.yaml.