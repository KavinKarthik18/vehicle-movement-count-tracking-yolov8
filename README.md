# Vehicle tracking and count monitoring using YOLOV8 ByteTrack and Supervision



### Data Collection and Annotation:
Use Roboflow to collect and annotate a diverse dataset of vehicle images or video frames.

### Data Preprocessing:
Preprocess the dataset using Roboflow to resize images, apply augmentation, and split into training/validation sets.
### Model Training:
Train YOLOv8 to detect vehicles and fine-tune as needed using Roboflow-managed data.
### Object Tracking Initialization:
Use YOLOv8 detections to initialize object tracks with ByteTrack.
### Real-time Tracking:
Apply ByteTrack to track vehicles across frames using both appearance and motion cues.
### Vehicle Counting:
Count vehicles by tracking their trajectories and monitoring predefined regions of interest.
### FINAL PREDICTION:
video is stored in predict directory inside run set directory.
