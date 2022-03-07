# TensorRT
New samples might be added in the future. All standard samples could be found in /usr/src/tensorrt/samples. As for now, you can calibrate your model with int8 precision using added option --calib-imgs with trtexec app.
## Calibration
Download images for calibration from coco val2017
```
wget http://images.cocodataset.org/zips/val2017.zip
unzip val2017.zip
rm val2017.zip
```
### Choose 1k images from dataset 
```
for jpg in $(ls -1 val2017/*.jpg | sort -R | head -1000); do \
    cp ${jpg} calibration/; \
done
```
### Create the calibration.txt file with all selected images
```
realpath calibration/*jpg > calibration.txt
```

