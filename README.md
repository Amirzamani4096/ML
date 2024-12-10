# Lung Cancer Detection in CT Images Using Region Proposal Network with Integrated Feature Maps from VGG16 
Lung cancer stands as one of the deadliest known diseases worldwide, comprising nearly two-thirds of all existing cancers [1]. The mortality rate of this type of cancer among all recognized tumours is 18% . Studies indicate that early detection of lung cancer can improve treatment outcomes and increase patients' survival rates. Among the available imaging modalities, computed tomography (CT) imaging is important in lung cancer detection and diagnosis. With increased access to CT equipment, physicians review a substantial volume of CT images daily. However, due to the prolonged time required for physicians to examine each CT scan, errors in cancer detection may occur due to fatigue or external factors, posing significant risks to patients. Therefore, to reduce individual errors, computer-aided detection (CAD) systems have been developed to assist physicians in rapidly and accurately identifying tumours.
Lung nodule detection systems typically identify nodules in two stages. The first stage involves extracting candidate nodules to increase the system's sensitivity. Traditional methods for extracting remaining nodules used threshold-based or region-based algorithms, which perform poorly in extracting nodules with lower contrast than the surrounding tissue. The second stage involves removing false-positive candidate nodules to increase the system's precision. However, lung nodule detection approaches need more efficiency, such as lengthy processes, lack of end-to-end detectability, and challenges with larger datasets.

Our method utilizes pretrained VGG16 with 5-group convolution as the main feature extraction network. After a series of convolutions and pooling in VGG16, the size of the feature map of the last layer is reduced, which leads to limited performance in the ROIs detection of nodules. It has been observed that the utilization of small feature maps does not provide sufficient resolution to represent the features of nodules accurately. We can create a feature map that demonstrates the feature resolution of various sizes of nodules in the proposed method by combining the last three layers of VGG16. 
The proposed feature map enters a region proposal network (RPN) and obtains a set of rectangular-shaped nodule proposals, each of which has a score in the output. The proposed network of the region consists of a fully convolutional network. In the false-positive reduction stage, the selected proposed regions are input into a 2D deep convolutional neural network (2D DCNN) is designed to reduce false-positive nodules. 

## ML
### ML
#### ML

machine learning codes   
itis mmy repository

[saba](https://github.com/sabadaftari?tab=repositories)
