# StyleTransfer
image style transfer!

## Model

Model TrainSet URL:[http://msvocds.blob.core.windows.net/coco2014/train2014.zip](http://msvocds.blob.core.windows.net/coco2014/train2014.zip "http://msvocds.blob.core.windows.net/coco2014/train2014.zip")

VGG trained Model:[http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat](http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat "http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat")

## Test
Test yourmodel:
```bash
python evaluate.py --checkpoint ./model/la_muse.ckpt --in-path ./examples/content/settingsun.jpeg --out-path ./
```
