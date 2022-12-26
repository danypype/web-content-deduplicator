# web-content-deduplicator
A set of Python services to deduplicate web content based on images

# Services

## 1. Image SIFT extractor

Input an `Image` object. Get an `Image` object back with `n` [SIFT](https://en.wikipedia.org/wiki/Scale-invariant_feature_transform) descriptors

## 2. Image-pair SIFT + Ransac matcher

Input a pair of `Image` objects with SIFT descriptors. Obtain a probability (between 0 and 1) of the two images resembling the same object/space

## 3. ...
