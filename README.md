# Mask Region based Convolutional Neural Network
- is  a best approach to Instance Segmentation
- Instance Segmentation =

Object Detection
<br>![](https://cdn-images-1.medium.com/max/1600/1*0T9gJQre00Mol0B1ATaHdA.gif) 
<br>+ Semantic Segmentation
<br>![](https://deeplearninganalytics.org/x/cdn/?https://storage.googleapis.com/wzukusers/user-32883313/images/5c140bcc570211goPAxe/semantic.gif)
<br>=
<br>![](http://thoth.inrialpes.fr/people/pluc/eccv883images/long/inst/frankfurt_000000_015676/nT11.gif)

# Region Proposal Network [Paper](https://arxiv.org/abs/1311.2524)
![](https://cdn-images-1.medium.com/max/800/1*REPHY47zAyzgbNKC6zlvBQ.png)
- approach for bounding box object detection
- uses proposed regions aka 'Regions of Interest(ROI)'


# Fast Region Proposal Network [Paper](https://arxiv.org/abs/1504.08083)
- proposes a Region Proposal Network to select the ROIs.
- uses ROI pooling to classify each ROI.

# Mask-RCNN [Paper](https://arxiv.org/abs/1703.06870)
- Mask RCNN used parallel heads for class, mask and box regression.
- ROI Allign is used to tackle the problem of data loss and miss allignment during ROI pooling.
- Fully Convolutional Network is used to regress the mask.
- 
