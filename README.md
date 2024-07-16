# Self-supervised-segmentation-on-partially-labeled-data
Self-supervised segmentation on partially labeled data using SAM and DINO v2

The problem is to use self supervised learning to segment  partially labeled objects in remote sensing images. To address such a problem I thought about using some vision models that are made of  vision transformers and masked auto encoders (SSL technique).

As they are one of the pioneers of SSL technique, I thought of using one of the vision models released by Meta AI, which is [DINO v2](https://github.com/facebookresearch/dinov2/tree/main) fine tuned on small labeled dataset..

 Or another method of using segment anything ([SAM](https://github.com/facebookresearch/segment-anything/tree/main) by Meta AI) and use the few existing labels = annotated pixels as input prompts to the model 

The second methods sounds more promising and adequate to the challenging limited annotation.

The used images are gathered from the satellite sentinel and was initially made for competition Tick Tick Bloom: Harmful Algal Bloom Detection Challenge on [DrivenData](https://www.drivendata.org/competitions/143/tick-tick-bloom/) and are publically available.
