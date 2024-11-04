# COR-OD
### Usage 
We run the code with torch version: 1.7.0, python version: 3.7.16
* Train MSO-FPC
```
# python train.py --workers 8 --device 0 --batch 24 --data data/coco.yaml --img 640 --cfg models/detect/gelan-c.yaml --weights '' --name gelan-c --hyp hyp.scratch-high.yaml --min-items 0 --epochs 500 --close-mosaic 15
```
The code repository for "Cross-scene Object Relationship-driven Object Detection for Flexible Printed Circuit Production"If you use any content of this repo for your work, please cite the following bib entry:

    title={Cross-scene Object Relationship-driven Object Detection for Flexible Printed Circuit Production},
    author={Jiu Dai, Guangzhu Chen, Xiaojuan Liao, Haichuan Ma, Linmao Xu},
    year={2024}
    }
