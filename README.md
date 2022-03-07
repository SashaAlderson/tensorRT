# TensorRT
New samples might be added in the future. All standard samples could be found after TensorRT installation in /usr/src/tensorrt/samples. As for now, you can calibrate your model with int8 precision using added option `--calib-imgs` on custom `trtexec app`. You can read [readme](https://github.com/SashaAlderson/tensorRT/blob/main/trtexec/README.md) for more information about `trtexec`.
# Create trtexec sample
```
git clone git@github.com:SashaAlderson/tensorRT.git samples
cd samples/trtexec
make
```
You can find generated `trtexec` file in bin folder.
