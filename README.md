# SoccerVission AI

AI-powered football match analysis using computer vision and machine learning for deeper performance insights

----------------------------------------------------------------------------------------------------------- 
<img src="https://github.com/user-attachments/assets/aebb6b5f-476c-4cc2-a854-2790ce536359" width="47%" height="205px" /> 
<img src="https://github.com/user-attachments/assets/44ad6a74-b0b3-4a7b-bb35-a4c8ec8e88b8" width="47%" height="220px" />

-----------------------------------------------------------------------------------------------------------

## Features
- Real-Time Object Detection: Detects players, referees, and the soccer ball
- Multi-Object Tracking: Tracks entities across frames to maintain consistent player identities.
- Team Classification via Jersey Colors: K-Means clustering to assign players to teams based on shirt color.
- Ball Possession Analytics: Computes team possession percentages using spatial proximity to the ball.
- Camera Motion Compensation: Applies optical flow to account for camera movement and stabilize tracking.
- Player Motion Analysis: Measures player displacement, speed, and movement trajectories over time.
- Real-World Distance: Perspective transformation to convert pixel coordinates into real-world distances.
- Advanced Metrics: Extracts performance insights, including total distance covered per player, etc.
  
-----------------------------------------------------------------------------------------------------------

## Model Performance

- Model: Custom-trained YOLOv8 (PyTorch)
- Detection Accuracy: 96.2% for players, referees, and soccer ball
- Team Classification Accuracy: 93.5% using K-Means clustering
- Inference: Real-time gameplay scenarios

-----------------------------------------------------------------------------------------------------------
## Training & Evaluation Results

#### Training Batches
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/2d7e54c5-5150-4a48-8b7e-ed0a8f980e17" width="48%" height="350px"/>
  <img src="https://github.com/user-attachments/assets/77743c9a-8379-4638-b456-1df598be3300" width="48%" height="350px"/>
</div>

#### Validation (Ground Truth vs Predictions)
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/cf1fc764-c012-4387-8876-ed2243d9ea87" width="48%" height="350px"/>
  <img src="https://github.com/user-attachments/assets/5338699a-b2b9-4f41-a89f-1e925a31effe" width="48%" height="350px"/>
</div>

#### Model Performance Metrics
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/525d23d6-b918-4157-85e3-a2a1a27c7f46" width="29%" height="320px"/>
  <img src="https://github.com/user-attachments/assets/37d25e4c-a322-4000-b3d1-14338d4b82da" width="22%" height="300px"/>
  <img src="https://github.com/user-attachments/assets/93747d0f-085b-4dd7-9eb8-1dc2c91e3857" width="22%" height="123px"/>
  <img src="https://github.com/user-attachments/assets/3cc1c8bf-a944-4b91-be2a-421e092d3a47" width="22%" height="123px"/>
</div>

#### Precision, Recall & Label Analysis
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/6d5035bb-3b85-463f-a95d-ddca23a4417a" width="25%" height="170px"/>
  <img src="https://github.com/user-attachments/assets/1ec4563b-1c26-4ba7-a6d5-d897ad86acb5" width="25%" height="170px"/>
  <img src="https://github.com/user-attachments/assets/d42c442e-2882-45f5-a7fa-4141a4ebe200" width="22.5%" height="142px"/>
  <img src="https://github.com/user-attachments/assets/e6bf8f07-4d71-43ab-ba71-75538ed95476" width="22.5%" height="142px"/>
</div>


-----------------------------------------------------------------------------------------------------------

## Tech Stack
- Python
- Ultralytics YOLO
- PyTorch
- OpenCV
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
  
-----------------------------------------------------------------------------------------------------------
🔗 [View Project Details](https://kchua220.github.io/Portfolio-Website/project/soccervision-ai)
