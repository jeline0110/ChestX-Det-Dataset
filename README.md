# ChestX-Det-Dataset

ChestX-Det is an improved version of ChestX-Det10 https://github.com/Deepwise-AILab/ChestX-Det10-Dataset. On the basis of ChestX-Det10, we add ***three*** new categoires and 35 new images (from NIH ChestX-14). Besides, the **segmentation** annotations are also provided.

The 13 categories are Atelectasis, Calcification, ***Cardiomegaly***, Consolidation, ***Diffuse Nodule***, Effusion, Emphysema, Fibrosis, Fracture, Mass, Nodule, ***Pleural Thickening***, Pneumothorax.

## Annotation:

The annotation files are ***ChestX_Det_train.json*** and ***ChestX_Det_test.json***. The format in annotation files are: 

{

"file_name": "xxx.png",

"syms": [s1, s2, ...], 

"boxes": [[x1, y1, x2, y2], [x1, y1, x2, y2], …],	

"polygons": [[[x3, y3], [x4, y4], …], [[x3, y3], [x4, y4], …], ...]

}

**syms**: The categories of thoracic abnormalities or diseases.

**boxes**: x1, y1, x2, y2 are left-top, right-bottom coordinates of the bounding box.

**polygons**: x3, y3, x4, y4 are point set coordinates of mask contour.

## Download:

For image downloading, please visit http://resource.deepwise.com/ChestX-Det/train_data.zip and http://resource.deepwise.com/ChestX-Det/test_data.zip.

## Contact

For any question, please contact

```
  lianjie@deepwise.com
```



