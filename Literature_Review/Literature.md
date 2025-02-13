# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:



## Summary of Each Work:

- **Source 1**:  **<ins>Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks</ins>**

  - **[Link](https://doi.org/10.48550/arXiv.1506.01497)**
  - **Objectives**:  
    The paper introduces Faster R-CNN, an improved object detection framework that builds upon previous R-CNN models by incorporating a Region Proposal Network (RPN) to enable near real-time object detection. The goal is to reduce computational complexity and improve detection accuracy by integrating region proposal generation within the neural network.
  - **Methods**:  
    The authors propose an end-to-end, fully convolutional neural network that jointly trains a region proposal network and a Fast R-CNN detector. The RPN shares convolutional layers with the object detection network, generating high-quality region proposals while maintaining computational efficiency. The network is trained using a multi-task loss function that simultaneously optimizes for object classification and bounding box regression.
  - **Outcomes**:  
    Faster R-CNN significantly improves object detection speed and accuracy compared to its predecessors, R-CNN and Fast R-CNN. The introduction of the RPN eliminates the need for external proposal mechanisms, leading to a more efficient and scalable detection framework. The results demonstrate state-of-the-art performance on benchmark datasets such as PASCAL VOC and MS COCO.
  - **Relation to the Project**:  
    This paper provides a foundation for modern object detection frameworks and is crucial for projects involving real-time image analysis, autonomous vehicles, and surveillance systems. The approach of integrating proposal generation into the deep learning model has influenced subsequent advancements in object detection, including single-shot detectors like YOLO and SSD.


- **Source 2**:  **<ins>Mask R-CNN</ins>**

  - **[Link](https://doi.org/10.48550/arXiv.1703.06870)**
  - **Objectives**:  
    The paper introduces Mask R-CNN, an extension of Faster R-CNN that enables pixel-level instance segmentation in addition to object detection. The goal is to provide an efficient and scalable framework for object detection and segmentation by adding a branch for predicting object masks in parallel with existing bounding box and classification predictions.
  - **Methods**:  
    The authors propose a simple yet effective modification to Faster R-CNN by incorporating a fully convolutional network (FCN) branch that predicts segmentation masks for each detected object. The model utilizes **RoIAlign**, a refinement over RoIPool, to preserve spatial information and improve mask prediction accuracy. The framework is trained end-to-end using a multi-task loss function that optimizes classification, bounding box regression, and mask prediction simultaneously.
  - **Outcomes**:  
    Mask R-CNN achieves state-of-the-art performance on instance segmentation tasks, significantly outperforming previous methods on datasets such as MS COCO. The framework is highly flexible and can be extended to keypoint detection and other structured prediction tasks. The introduction of RoIAlign leads to improved localization accuracy compared to previous pooling methods.
  - **Relation to the Project**:  
    This paper is fundamental for projects involving advanced image analysis, particularly in medical imaging, autonomous vehicles, and robotics. Mask R-CNN’s ability to perform instance segmentation alongside object detection makes it a powerful tool for tasks requiring fine-grained image understanding, such as scene parsing and object manipulation in robotics.


- **Source 3**:  **<ins>Faster R-CNN Explained for Object Detection Tasks</ins>**

  - **[Link](https://www.digitalocean.com/community/tutorials/faster-r-cnn-explained-object-detection)**
  - **Objectives**:  
    This tutorial aims to provide a comprehensive understanding of the Faster R-CNN model, detailing its evolution from earlier models like R-CNN and Fast R-CNN. It seeks to elucidate the architecture, components, and improvements that make Faster R-CNN a state-of-the-art object detection framework.
  - **Methods**:  
    The authors systematically dissect the Faster R-CNN architecture, beginning with an overview of traditional object detection pipelines. They then delve into the limitations of R-CNN and Fast R-CNN, leading to the introduction of the Region Proposal Network (RPN) in Faster R-CNN. The tutorial explains key concepts such as anchor boxes, feature sharing, and the training methodologies employed in Faster R-CNN.
  - **Outcomes**:  
    Readers gain a thorough understanding of how Faster R-CNN integrates region proposal generation and object detection into a unified network. The tutorial highlights the efficiency and accuracy improvements over its predecessors, emphasizing the significance of the RPN and shared convolutional features in achieving real-time object detection.
  - **Relation to the Project**:  
    This tutorial serves as an accessible resource for understanding the advancements in object detection models, particularly the transition to real-time detection with Faster R-CNN. It provides foundational knowledge beneficial for projects involving object detection tasks, offering insights into the architectural innovations that enhance detection performance.

