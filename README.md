# cnn-robustness-test
Testing robustness of Convolutional Neural Networks.

In this repo I used Pikachu to test whether or not OpenCLIP-resnet50-CC12M will fail following the introduction of changes.

The changes introduced: 

1) Rotation of Pikachu's picture;
2) Resizing of the picture;
3) Switching colour channels.

Results: The model did not fail, though some changes did decrease it's certainty.

Note: This is/was homework on my neural networks minor.
