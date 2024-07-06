
# UAV-based Image Segmentation of Crop Lands into weed And crops using UNET with RESNET-50 backbone.

This project leverages UAV imagery to perform precise segmentation of weeds and crops using a U-Net architecture integrated with a ResNet-50 backbone. The model is designed to enhance agricultural management by accurately distinguishing between crops and weeds, thereby facilitating targeted weed control and optimizing crop yield.



## Crop Lands
| Crop Field | Segmented Image |
|------------|------------------|
| ![Crop Field](https://drive.google.com/file/d/1BXcB3ZsfLJlEmIWrXfp2uxNPdK4E9Pcc/view?usp=drive_link) | ![Segmented Image](https://drive.google.com/file/d/1PzTYxaDgxWA9ni5h9bZRLs0LUnm1PzPJ/view?usp=drive_link) |

## Model Architecture
The model architecture employs a U-Net framework with a ResNet-50 backbone. U-Net is a convolutional neural network designed for image segmentation tasks, characterized by its U-shaped structure with a contracting path to capture context and a symmetric expanding path for precise localization. The ResNet-50 backbone, integrated into the U-Net encoder, leverages residual learning to facilitate training of deeper networks, enhancing feature extraction and improving segmentation accuracy. This combination ensures effective segmentation of UAV images for distinguishing between crops and weeds.

## DATASET
The dataset used in this work is derived from the research conducted by I. Sa, M. Popovic, R. Khanna, Z. Chen, P. Lottes, F. Liebisch, J. Nieto, C. Stachniss, A. Walter, and R. Siegwart. Their paper, titled "WeedMap: A large-scale semantic weed mapping framework using aerial multispectral imaging and deep neural network for precision farming," was published in 2018 by MDPI, Remote Sensing.