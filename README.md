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

![Image text](/Images/14.png)
### custom images in uncontrolled environment results.
![Image text](/Images/15.png)

## Conclusion
- Distortions like fine finger details can be overcome by improving the loss function.
- From all the figures seen above of the comparison between all the three algorithms PFAFN generates better results than CPVTON, CP-VTON+ and ACGPN.
-  CP-VTON+ also generates good results but has challenges for complex clothes and poses.
- From the results we can conclude that images should be taken in a proper controlled environment with good lighting conditions.
-  Virtual Try-On can be used instead of tedious offline shopping or clueless selection of products.

## Future scope
This concept of virtual try-on can be used by online stores and help their customers know how they would look in that attire. Collecting the appropriate data of both target cloth and image is necessary towards which we are working. Also this project is useful for online shopping enthusiasts to reduce their time and number of returns. This Virtual Try-On can be extended to 3D and real-time also. When we talk about shopping for clothes, it is one of the most enjoyable experiences for a customer, but at the same time can become cumbersome and tiring. The usual hassles involved in traditional in-store shopping experiences like standing in long queues or having to dress-undress again and again can make the whole experience a little dull. With
virtual try-on, all these hassles are done away with.With virtual try-on, a customer can try different clothing items without having to go through
any of the above-mentioned hassles, right from the comfort of their homes.





