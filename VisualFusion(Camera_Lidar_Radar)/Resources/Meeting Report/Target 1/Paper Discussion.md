# Paper Discussion held on 27th April

## Weekly Current Status
Review papers in groups:
- Group 1: Lidar - Camera
- Group 2: Ridar - Camera
- Group 3: Lidar - Camera - Radar

Find papers on each topic. Share it with the group so there are no conflicts.
Add details to the [sheet](https://docs.google.com/spreadsheets/d/1D0CSpxJMpQfcQ55jQGHQWEsWqWzX3jR_N69Lul2E9UI/edit?usp=sharing).

## Meeting Objective
- Discuss the paper we reviewed this week. 
- Action Item for next week.

## Main Headings
Paper review/discussion.
Different approaches for doing the project.
Discussing project goals.
Action Items for next week.

## Paper review
- Discussed Transformer model on Camera-Lidar-Radar(_Early Fusion_)
	- FUTR3D: A Unified Sensor Fusion Framework for 3D Detection
- Brief explanation on its concepts and fundamentals of transformer model. [Transformer Model Explanation](https://machinelearningmastery.com/the-transformer-model/)
- Discussed CNN model for Camera-Lidar(_Intermediate Fusion_)
	- Clustering lidar data to get Region of Interest(RoI)
	- CNN on the image with RoI
- Discussed how radar data is used on Camera-Radar fusion(_Review Paper_)
	- Denoising Radar noise by having multiple antenna and keeping bypass threshold

### Different approaches for project
- Geometric Approach: Using a traditional approach to fuse the data.
- Transformer Based Approach: Advanced Encoder/Decoder approach for fusion.

### Types of Fusion
- Early Fusion
- Feature Fusion
- Late Fusion

### Advance Project Goals
Object Tracking using **Transformer** Based Approch

## Action Items:
### Group Discussion/Study Session on Wednesday:
- ML Basics/Terminologies by Mayank ([Reference Link](https://medium.com/@himadrisankarchatterjee/a-basic-introduction-to-convolutional-neural-network-8e39019b27c4))
    - _by **Mayank**_
- Object Detection on Image
    - _by **Vishal** and **Gautham**_
    - Topics:
        - CNN 
        - …_etc_

### Group Discussion/Study Session on Saturday:
- Lidar Data Visualization/Processing ([Reference Link](https://learnopencv.com/3d-lidar-visualization/))
    - _by **Mayank** and **Aleena**_
    - Topic:
        - Voxel
        - Clustering 
        - …_etc_
- Lidar Object Detection using open3D
    - _by **Deepali** and **Tarun**_

## Group Task for week:
- Continue to review papers in groups.
- Focus on the models and algorithms.
- Add insights to the sheet
- Practice / Implement basics of the items discussed in the study session.

## Items for Next Weeks:
Group Discussion/Study Session:
- Projecting Lidar Data on camera data
- Projecting Radar Data on camera data

## Links Shared:
- ViT(Visual Transformer) - To learn about transformer for image/object detection [GitHub](https://github.com/FrancescoSaverioZuppichini/ViT?tab=readme-ov-file)
