# Object_annotation_labelme
conda create --name=labelme python=3
conda activate labelme
pip install labelme

# or install standalone executable/app from:
# https://github.com/labelmeai/labelme/releases

# or install from source
pip3 install git+https://github.com/labelmeai/labelme

type labelme

UI window will open
1. Upload image
2. select polygon
3. start selecting the points in the image you want to segment


other option is using Segment Anything model (SAM)

where
1. login to your roboflow account
2. create Instance Segmentation
3. Upload images you want to segment
4. use manual labelling
5. start annotating
6. use smart polygon for selection can use both standard or Enhanced 
7. save the work
8. create a version
9. want to perform preprocessing or agumentation you can
10. create image and export in the framework you want to use.