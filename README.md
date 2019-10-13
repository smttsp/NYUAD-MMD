# NEW YORK UNIVERSITY ABU DHABI - MIXED MEDIA DATASET

The shared dataset contains data collected for two different publications. 

    1. Mixed Media Dataset is collected for "Source Camera Attribution of Multi-Format Devices".
    2. Long stabilized videos: These are additional data which were specifically captured for 
    "Camera Fingerprint Extraction via Spatial Domain Averaged Frames".

## MIXED MEDIA DATASET
The dataset contains images and videos from 108 cameras. Each camera contains images and videos of one or more resolutions.
The structure of each camera is:

    NYU_ID/
        images/
            resolution_i/
                image_j
        videos
            resolution_p/
                video_q

The dataset contains a total of N images, and M videos. However, in "Source Camera Attribution of Multi-Format Devices" paper, 
we have discarded cameras with only a few images, or those without non-stabilized videos etc.
To replicate our dataset and results, we are sharing the code which performs this process.

Since other researchers may use the dataset for other purposes, we don't discard the rest of the data and share them with research community.

## LONG STABILIZED VIDEOS
For "Camera Fingerprint Extraction via Spatial Domain Averaged Frames", we have used long stabilized videos from which we create 
camera fingerprints and try to match them with other fingerprints. 
For this experiment, we have collected stabilized videos from 5 cameras adding up to 260 minutes. 
These cameras are named NYU_112-118.

Please send an email to nyuad.mmd [at] gmail.com for accessing the datasets.
