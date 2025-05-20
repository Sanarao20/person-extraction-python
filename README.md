# Person Extraction from Photo

This project extracts the person(s) from a given photo using a pretrained DeepLabV3 model in PyTorch. It applies semantic segmentation to isolate people by removing the background.

## Features
- Uses PyTorch DeepLabV3 for accurate person segmentation.
- Outputs the extracted person image with the background removed.
- Works on any input image.

## Requirements

- Python 3.7+
- PyTorch
- torchvision
- OpenCV
- numpy
