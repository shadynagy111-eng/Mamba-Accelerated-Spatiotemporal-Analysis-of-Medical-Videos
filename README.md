# Mamba-Accelerated-Spatiotemporal-Analysis-of-Medical-Videos

![image alt](https://github.com/shadynagy111-eng/Mamba-Accelerated-Spatiotemporal-Analysis-of-Medical-Videos/blob/f9156c2f81cf7eef2eeba54289eb8778a5385002/Dark%20Blue%20and%20Orange%20Simple%20Poster.png)

📌 Overview
---
The analysis of medical videos for tasks such as action recognition, anomaly detection, and disease progression monitoring plays a vital role in improving diagnostic accuracy and treatment planning. Traditional models often struggle with efficiently capturing both spatial and temporal information. This project explores the use of the Mamba architecture for spatiotemporal analysis, leveraging its ability to model long sequences and capture temporal dependencies, providing an efficient and accurate solution for analyzing medical videos.

🏥 **Dataset**
---
- **Paper**: *CardiacNet: Learning to Reconstruct Abnormalities for Cardiac Disease Assessment from Echocardiogram Videos* (ECCV 2024)
  
### **Background**:
- Analyzes cardiac function and diseases using echocardiogram videos.
- Challenges include diagnosing spatial and temporal heart motion patterns.

Link:https://www.kaggle.com/datasets/xiaoweixumedicalai/abnormcardiacechovideos

Sample GIF:
![Image](https://github.com/user-attachments/assets/a77715fb-0998-4cbc-8745-f9ef81419477)

🏗️ Proposed Model Architecture
---
The model combines the Mamba architecture with Convolutional Neural Networks (CNNs) for spatial feature extraction from individual frames and a temporal module to capture the sequence of changes across frames. This hybrid approach efficiently processes both spatial and temporal information, allowing the model to focus on significant events in the video, enabling accurate analysis for tasks like action recognition, anomaly detection, and disease progression.

🔷 Block Diagram :
---
![Image](https://github.com/user-attachments/assets/fdfe52fc-395d-4848-9e3e-3e4d346d2421)

🔬 **Methodology**
---
1. **Dataset Preprocessing**: Extract and preprocess frames from medical videos for spatial and temporal feature extraction.
2. **Model Development**: Combine CNNs for spatial feature extraction with the Mamba architecture for spatiotemporal learning.
3. **Training & Evaluation**: Train the model on medical video tasks and evaluate using accuracy and F1 score.
4. **Optimization**: Fine-tune hyperparameters to improve model performance and efficiency.

⚡ Key Features
---
✔️ Mamba Architecture - Efficiently models long temporal sequences, capturing both spatial and temporal dependencies in medical videos.

✔️ Hybrid CNN-Mamba Fusion - Combines CNNs for spatial feature extraction with the Mamba model for temporal dynamics, enhancing accuracy in video analysis.

✔️ Action & Anomaly Detection - Suitable for a variety of tasks such as action recognition, anomaly detection, and disease progression monitoring in medical videos.

✔️ Computational Efficiency - Optimized for faster processing and reduced computational load, making it viable for real-time medical video analysis.


**🚀 Installation & Setup
---
1. **Clone this repository:**

   ```bash
   git[ clone https://github.com/shadynagy111-eng/Mamba-Accelerated-Spatiotemporal-Analysis-of-Medical-Videos.git
   cd Mamba-Accelerated-Spatiotemporal-Analysis-of-Medical-Videos]


## 📊 Results & Comparisons

| Model               | Accuracy | Computation Time | Power Efficiency |
|---------------------|----------|------------------|------------------|
| CNN                 | ——       | ——               | ——               |
| SNN                 | ——       | ——               | ——               |
| Hybrid CNN-SNN      | ——       | ——               | ——               |

📌 Key Takeaway: _____

📌 Future Work
---
🔹 Expanding the model to handle larger medical video datasets.

🔹 Implementing real-time analysis for live clinical applications.

🔹 Exploring alternative architectures for improved efficiency.

🔹 Enhancing performance on action recognition and anomaly detection tasks.

## 📜Citation

If you use this work in your research, please cite:

```bibtex
@article{mamba2025,
  title={Mamba-Accelerated Spatiotemporal Analysis of Medical Videos},
  author={Youssef Mohamed and Mohammed Abdel-Megeed and Shady Ahmed},
  journal={__},
  year={2025}
}
