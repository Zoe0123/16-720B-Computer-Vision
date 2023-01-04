# 16-720B-Computer-Vision
Individual Assginments for [CMU 16-720B - Computer Vision (https://kriskitani.github.io/courses/16720B/2022_Fall/Computer_Vision_16_720B_Syllabus_Fall_2022.pdf)

## Assignment 1 Hough Transform

Implemented the convolution with vectorization, Edge Detection with Non-Maximal Suppression, applied the Hough Transform to an edge magnitude image and conducted the Non-Maximal Suppression for the Hough Accumulator

## Assignment 2 Bag of Visual Words

Built a dictionary of visual words from training data: Used Harris corner detector to pick interest points, extracted visual words from interest points on images, formed a visual dictionary, and represented each image as a vector of visual words.

Built and evaluated a recognition system: used the visual word dictionary and Spatial Pyramid Matching to extract visual features from images. Implemented Deep Learning approaches (VGG16; ViT) and compared results with the BoW.

## Assignment 3 Neural Networks
Extracted text from images, implemented different Neural Network architectures for recognition, and compared results.

Implemented image compression with Autoencoders and experimeted with data augmentation.

## Assignment 4 Homography
Found corresponding point pairs between two images by implementing Harris detector in concert with the BRIEF descriptor.

Estimated the planar homography from a set of matched point pairs, implemented the RANSAC algorithm on noisy data and automated homography estimation/warping for Augmented Reality.

Generated panoramas: computed keypoints and descriptors, found putative feature correspondences by matching keypoint descriptors, estimated a homography using RANSAC and warped one of the images with the homography and overlayed them.

## Assignment 5 3D Reconstruction

Estimated the fundamental matrix from the corresponding points in a pair images by using the Eight Point and Seven Point Algorithm.

Metric Reconstruction: computed the camera matrices and triangulate the 2D points to obtain the 3D scene structure.

Implemented Bundle Adjustment.

## Assignment 6 Object Tracking in Videos
Implemented two variants of the Lucas-Kanade Tracking algorithm: The warp being translation only and the warp being the full affine transformation.

Implemented the Matthew-Bakers Inverse Compositional Alignment with affine matrix.

Implemented the Multi-object tracking (MOT) by Detection: computed the intersection-over-union (IoU) metric, and matched with the Hungarian Algorithm.


