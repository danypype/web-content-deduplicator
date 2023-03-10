# web-content-deduplicator
A set of Python services to deduplicate web content based on images

# Services

## 1. Image SIFT extractor

Input an `Image` object. Get an `Image` object back with `n` [SIFT](https://en.wikipedia.org/wiki/Scale-invariant_feature_transform) descriptors

## 2. Image-pair SIFT + Ransac matcher

Input a pair of `Image` objects with SIFT descriptors. Obtain a probability (between 0 and 1) of the two images resembling the same object/space

## 3. Image sets intersector

Input `n` sets of `Image`s. Retrieve the intersection of the given sets, based on a specified probability threshold `P`

## 4. ...

# Development environment set-up guide

1. Install OpenCV: https://docs.opencv.org/4.x/d0/db2/tutorial_macos_install.html
2. ...
