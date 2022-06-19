# 2D-Virtual-Tryon
Simulate, analyse and compare the recent and most widely used Virtual Tryon algorithms(PFAFN, ACGPN and CP-VTON+)
## Objectives
- To design an algorithm such that given with a pair of human image and a target cloth image produces a human image wearing the target clothes.
- To Perform realistic rendering of clothes.
- To compare algorithms such as PFAFN, CP-VTON+ and ACGPN for different types of images.
## Methodology
![Image text](/Images/1.png)

As shown in Figure the functional block diagram consists of semantic segmentation,matching of cloth and target images geometrically and warping the cloth on image. In semantic segmentation function we will obtain the semantic segmentation of target image and
generate its parsing points. These points are used to align the target cloth in the pose of the
given human body. And using this functionality, we can obtain our Try On result.

## Results
### General results for a target cloth on target image.
![Image text](/Images/8.png)
### Simple Pose-Simple Cloth results.
![Image text](/Images/9.png)
### Simple Pose-Complex Cloth results.
![Image text](/Images/10.png)
### Complex Pose-Simple Cloth results.
![Image text](/Images/11.png)
### Complex Pose-Complex Cloth results.
![Image text](/Images/12.png)
### custom images in controlled environment results.
![Image text](/Images/13.png)
![Image text](/Images/Screenshot(10).png)
### custom images in uncontrolled environment results.
![Image text](/Images/Screenshot(28).png)



