# Shellfish-OpenImages > 416x416
https://public.roboflow.ai/object-detection/shellfish-openimages

Provided by [Jacob Solawetz](https://roboflow.ai)
License: CC BY 4.0

![Image example](https://i.imgur.com/4LoSPQh.png)

# Overview 

This dataset contains 581 images of various shellfish classes for object detection. These images are derived from the [Open Images](https://arxiv.org/pdf/1811.00982.pdf) open source computer vision datasets.

This dataset only scratches the surface of the Open Images dataset for shellfish!

![Image example](https://i.imgur.com/oMK91v6.png)

# Use Cases

* Train object detector to differentiate between a lobster, shrimp, and crab.
* Train object dector to differentiate between shellfish
* Object detection dataset across different sub-species
* Object detection among related species
* Test object detector on highly related objects
* Train shellfish detector
* Explore the quality and range of Open Image dataset

# Tools Used to Derive Dataset

![Image example](https://i.imgur.com/1U0M573.png)

These images were gathered via the [OIDv4 Toolkit](https://github.com/EscVM/OIDv4_ToolKit) This toolkit allows you to pick an object class and retrieve a set number of images from that class **with bound box lables**. 

We provide this dataset as an example of the ability to query the OID for a given subdomain. This dataset can easily be scaled up - please reach out to us if that interests you. 