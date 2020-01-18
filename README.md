# NEW YORK UNIVERSITY ABU DHABI - MIXED MEDIA DATASET

This dataset contains data collected for two different publications. 

    1. Mixed Media Dataset is collected for "Source Camera Attribution of Multi-Format Devices".
    2. Long stabilized videos: These are additional data which were specifically captured for 
    "Camera Fingerprint Extraction via Spatial Domain Averaged Frames".

## MIXED MEDIA DATASET
is a visual media dataset that is mainly compiled for source camera attribution (verification or identification) in mixed media setting. It has two main properties that separates itself from existing datasets: 

    1. Images and videos of multiple resolutions and/or aspect ratios for many cameras
    2. Data from variety of brands/models which may allow researchers to see differences of models & brands. 

Moreover, even though we have only used cameras with images and non-stabilized videos, we are sharing those without images or without non-stabilized videos so that researchers with other needs can utilize the dataset.

This dataset contains images and videos from 108 cameras. Each camera contains images and videos of one or more resolutions.
The file tree of each camera is as follows:

    NYU_ID/
        images/
            resolution_i/
                image_j
        videos
            resolution_p/
                video_q

The dataset contains a total of N images, and M videos. However, in our experiments, we have only used cameras with only non-stabilized videos and at least 6 matching images from a single resolution. 

In this repository we are sharing the code to replicate the used dataset and results.

## LONG STABILIZED VIDEOS
For "Camera Fingerprint Extraction via Spatial Domain Averaged Frames", along with mixed media dataset, we have collected long stabilized videos from 5 cameras adding up to 260 minutes. 

Please send an email to `nyuad.mmd [at] gmail.com` for accessing the datasets.
