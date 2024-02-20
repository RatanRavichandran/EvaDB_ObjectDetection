# EvaDB_ObjectDetection
automating a system using YOLO for real-time video object detection and annotation.

# About the Project

Video/object detection is a widely used application of computer vision. Through thsi project, I try to automate annotation processes, which when done manually can be very time consuming and labor intensive. This would need efficient object detection across various applications such as surveillance and autonomous vehicles. By harnessing YOLO's capabilities, we can provide accurate and timely annotations, enhancing decision-making and analysis tasks.

# Datasets
The dataset used is a YouTube video containing two cars in an intersection. Feel free to replace the dataset with one of your own when implementing the notebook!

# Methodology

1.  **Data Collection and Preprocessing:**
    
    -   Collect a diverse dataset of videos covering various scenarios and object types.
    -   Preprocess the videos to ensure compatibility with the object detection algorithm.
2.  **Model Development:**
    
    -   Implement the YOLO (You Only Look Once) object detection algorithm using a deep learning framework such as TensorFlow or PyTorch.
    -   Train the model on the collected dataset to learn to detect objects accurately and efficiently.
3.  **Integration with Database:**
    
    -   Develop a database system to store video data and associated annotations.
    -   Implement functionalities to load videos into the database and execute object detection queries on the stored videos.
4.  **Video Processing Pipeline:**
    -   Build a video processing pipeline that reads input videos, processes them frame by frame, and feeds frames to the object detection model.
    -   Integrate the object detection model output with the annotation algorithm to generate bounding boxes and labels for detected objects.
5.  **Annotation and Visualization:**
    
    -   Annotate detected objects with bounding boxes and labels on video frames.

## Running Tests

<a href="https://ibb.co/tpGZkXm"><img src="https://i.ibb.co/1Ggsh6v/Screenshot-2024-02-20-093913.png" alt="Screenshot-2024-02-20-093913" border="0"></a>

Figure 1: Original Image

<a href="https://ibb.co/vX5YvWG"><img src="https://i.ibb.co/FHvVq1M/Screenshot-2024-02-20-093929.png" alt="Screenshot-2024-02-20-093929" border="0"></a>

Figure 2: Objects detected and annotated.

# Conclusion
Ther YOLO-based system has proven effective in automating video object detection and annotation, easing labor-intensive processes. Future improvements may involve refining object boundaries through advanced post-processing techniques and integrating cloud-based services for scalable processing.

# Contributions
If you have ideas for improvement or wish to contribute, please open an issue or submit a pull request. Collaboration is highly encouraged!
