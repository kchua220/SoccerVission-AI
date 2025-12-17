# SoccerVission AI

In this project, I worked on building an AI-powered system to analyze football matches more effectively. The system uses YOLO, an advanced object detection model, to detect and track players, referees, and the ball in video footage. To assign players to teams, K-means clustering was applied based on t-shirt colors, allowing for the calculation of ball possession percentages. Optical flow techniques were used to track player motion while accounting for camera movement, ensuring accuracy. Additionally, perspective transformation converted pixel data into real-world distances, enabling measurements like player speed and the total distance covered during a match. This project combines AI, computer vision, and sports analytics to uncover more sophisticated performance metrics in soccer.

-----------------------------------------------------------------------------------------------------------
### Input

<img width="1434" alt="Screenshot 2024-12-24 at 2 23 26 PM" src="https://github.com/user-attachments/assets/aebb6b5f-476c-4cc2-a854-2790ce536359" />


### Output
<img width="1481" alt="Screenshot 2024-12-24 at 2 13 08 PM" src="https://github.com/user-attachments/assets/44ad6a74-b0b3-4a7b-bb35-a4c8ec8e88b8" />

-----------------------------------------------------------------------------------------------------------
### Model Training

The project utilized a custom-trained YOLOv8 model, fine-tuned with PyTorch, to achieve an impressive 96.2% detection accuracy for players, referees, and soccer balls in real-time gameplay scenarios. Additionally, KMeans clustering was implemented to classify players into teams based on jersey colors, achieving a 93.5% accuracy in team assignment. 

[TRAINED MODEL](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=drive_link)

[RESULTS FILE](https://github.com/user-attachments/files/18236735/results.csv)

![train_batch3511](https://github.com/user-attachments/assets/2d7e54c5-5150-4a48-8b7e-ed0a8f980e17)

![train_batch3512](https://github.com/user-attachments/assets/77743c9a-8379-4638-b456-1df598be3300)

![val_batch0_labels](https://github.com/user-attachments/assets/cf1fc764-c012-4387-8876-ed2243d9ea87)

![val_batch0_pred](https://github.com/user-attachments/assets/5338699a-b2b9-4f41-a89f-1e925a31effe)

![results](https://github.com/user-attachments/assets/525d23d6-b918-4157-85e3-a2a1a27c7f46)

![labels](https://github.com/user-attachments/assets/d42c442e-2882-45f5-a7fa-4141a4ebe200)

![labels_correlogram](https://github.com/user-attachments/assets/e6bf8f07-4d71-43ab-ba71-75538ed95476)

![F1_curve](https://github.com/user-attachments/assets/37d25e4c-a322-4000-b3d1-14338d4b82da)

![PR_curve](https://github.com/user-attachments/assets/93747d0f-085b-4dd7-9eb8-1dc2c91e3857)

![P_curve](https://github.com/user-attachments/assets/6d5035bb-3b85-463f-a95d-ddca23a4417a)

![R_curve](https://github.com/user-attachments/assets/1ec4563b-1c26-4ba7-a6d5-d897ad86acb5)

![confusion_matrix](https://github.com/user-attachments/assets/3cc1c8bf-a944-4b91-be2a-421e092d3a47)


-----------------------------------------------------------------------------------------------------------

### Languages, Libraries & Framworks
- Python
- Ultralytics YOLO
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Scikit-Learn

-----------------------------------------------------------------------------------------------------------
Thank you for taking the time to explore this project! ! Feel free to reach out if you have suggestions or feedback!
