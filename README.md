# Image Segmentation
Image Segmentation:
comparing, analysing and using different methods based on NN to segment three classes namely sky, ground and objects.

### Using model:
python test.py --model_path model --dataset dataset --image --out_path image

##### Example:
python3.6 test.py --model_path model/citys/segnet_cityscapes_1_99.pkl --img_path cities/berlin_000009_000019_leftImg8bit.png --out_path cities/berlin_000009_000019_leftImg8bit_ctl_99.png


<p align="center">
  <img src="https://github.com/Thesis-Dominique/ImageSegmentation/blob/master/cities/rberlin_000010_000019_leftImg8bit.png" width="420" title="Input image" />
  <img src="https://github.com/Thesis-Dominique/ImageSegmentation/blob/master/cities/berlin_000010_000019_leftImg8bit_ctl_99.png" width="420" title="Output image"/>
</p>

![Performance](https://github.com/Thesis-Dominique/ImageSegmentation/blob/master/cities/comb001.jpg)
