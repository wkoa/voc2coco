# voc2coco
A useful script for converting voc format annotations(generated by LabelImg or LabelImg) to coco format annotations
# Requirements
* python2.7
* opencv
* numpy
# Example
*1 converter = voc2coco('/path/to/VOCdevkit','year')
*2 converter.voc_to_coco_converter()
## Default output dir
/path/to/VOCdevkit/VOCyear/cocoformatJson
