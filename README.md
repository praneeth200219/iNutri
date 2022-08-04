# iNutri
This is the official implementation of our paper titled: **iNutri: An Automated Nutrition Level Monitoring System in Smart Malnutrition-care** submitted to review at Springer's Journal of Medical Systems

## Authors
Ashish Marisetty, Prathistith Raj Medi, Praneeth Nemani, Venkanna U, Debanjan Das

## Abstract
Malnutrition is caused by a lack of sufficient nutrients in the diet, affecting the body's vital organs and functioning. 
Periodic examination and mass screening employ both traditional and non-invasive techniques. However, major drawbacks include the need for additional equipment, the lack of holistic feature representation, the absence of appropriate health indicators, and the unavailability of cloud-based smartphone implementation for estimating the Body Fat Percentage (BFP), Basal Metabolic Rate (BMR), and Body Mass Index (BMI) accurately for smart-malnutrition monitoring. To resolve these limitations, this study proposes a novel, scalable \& robust cloud-based smart malnutrition-monitoring system that uses a single full-body image of a person to estimate height, weight, and other intuitive health parameters in a multi-modal learning framework. 

## Contributions
- A holistic feature fusion of facial, body \& 3D embeddings, including the correlation between them, optimal feature combination and individual importance in estimating the weight is insightfully discussed.
- This paper is the first to incorporate the fine-grain local 3D representation in combination using 3D classification network backbones as feature extractors.

## Conceptual Overview
<img src="Images/CO-crop (1)_page-0001.jpg" width="1000"/>

## Conclusion
Given the pervasiveness and ever-increasing incidence of smartphone usage worldwide, the proposed framework allows users to periodically monitor their health using their smartphones. This research investigated a novel method for predicting height and weight and inferring other health indicators, including BMI, BMR and BFP from a single-shot full-body image using holistic feature representation in a multi-modal learning paradigm. The solution is meticulously validated and tested with real-world images by also simulating various lighting conditions artificially and systematically studying the importance of 2D and 3D features. In the following aspects of this solution, we can investigate more rigorous methods of training and converging the multi-modal architecture, as well as better methods of extracting the FFs, DFs, and BFs embeddings. To improve weight and height prediction performance, we can further explore sub-embedding representations fusion methods and try to design a method to predict height without scale information or constraints. Furthermore, future app development efforts may include the formation of communities as well as the investigation of security issues relating to the Machine Learning model and databases.

