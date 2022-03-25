# MUAAD: Manipal UAV Anomaly Activity Dataset


UAV based surveillance is gaining much interest worldwide due to its extensive applications in monitoring wildlife, urban planning, disaster management, providing security, etc. The UAV videos can be analyzed for strange/odd/anomalous patterns which are essential aspects of surveillance. But manual analysis of these videos is tedious and laborious. The development of computer-aided systems for the analysis of UAV based surveillance videos is crucial. Despite this interest, in literature, several computer aided systems are developed focusing on CCTV based surveillance videos. These methods are designed for single scene scenarios and lack contextual knowledge which is required for multi-scene scenarios. Furthermore, the lack of standard UAV based anomaly detection datasets limits the development of these systems. We proposes a new Anomaly Activity Detection dataset from UAV Aerial Videos. 




UAV based surveillance is gaining much interest worldwide due to its extensive applications in monitoring wildlife, urban planning, disaster management, providing security, etc. These videos are analyzed for strange/odd/anomalous patterns which are essential aspects of surveillance. But manual analysis of these videos is tedious and laborious. The development of computer-aided systems for the analysis of UAV based surveillance videos is crucial. Despite this interest, in literature, several computer aided systems are developed focusing on CCTV based surveillance videos. These methods are designed for single scene scenarios and lack contextual knowledge which is required for multi-scene scenarios. Furthermore, the lack of standard UAV based anomaly detection datasets limits the development of these systems.


## Dataset Details

The videos are acquired from the camera on-board a UAV (DJI Phantom 3 drone) at the campus of Manipal Institute of Technology, Manipal, India. These videos are acquired at 29 fps and are of resolution 1024x720 pixels. The videos are collected during different time of the day at which maximum vehicular traffic is expected (morning 9am, afternoon 12 noon and evening 4pm). In total, the dataset contains 60 videos collected from nine different locations within the campus. The training set consists of 8 videos while the test set consists of 52 videos. Frame level annotations are provided where 1 indicates the frames are anomalous and 0 indicates the frames are normal. The training and testing videos are stores in two separate folders. The comparison of the devel-oped dataset with respect to other datasets are shown in Table 1. Table 2 describes the details of the developed dataset. Figure 1 shows the distribution of the normal and anomalous samples in the dataset. Figure 2 shows few sample scenes from the MUAAD dataset.

Table 1: Comparison of MUAAD dataset with other Anomaly detection datasets
![alt text](https://github.com/uverma/MUAAD/blob/main/Comparison.png)


Table 2: Details of the MUAAD dataset


![alt text](https://github.com/uverma/MUAAD/blob/main/Table.png)


Figure 1: Distribution of Normal and anomalous samples in MUAAD dataset


![alt text](https://github.com/uverma/MUAAD/blob/main/NormalVsAnomalous.png)
 
