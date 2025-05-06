
# ✋ Real-Time Hand Gesture Recognition Using Deep Learning

This project implements real-time hand gesture recognition using a webcam feed. A **LeNet-based Convolutional Neural Network (CNN)** is trained to classify **9 distinct hand gestures**. The application overlays the predicted gesture and its probability on the video stream in real-time.

---

## 🧠 Model Overview

A classic **LeNet architecture** (defined in `lenet.py`) is used for gesture classification. It has been adapted for recognizing hand gestures efficiently.

---

## 📁 Project Structure

    ├── lenet.py # LeNet CNN architecture
    ├── train_network.py # Trains the model and saves it as mask.model
    ├── test_network.py # Tests the trained model on sample images
    ├── main.py # Real-time gesture recognition via webcam
    ├── dataset/ # Training dataset for 9 hand gestures
    ├── images/ # Sample gesture images for testing
    ├── mask.model # Saved trained model


### 🔧 Requirements

- Python 3.x  
- OpenCV  
  ```bash
  pip install opencv-python



▶️ Running Real-Time Gesture Recognition
Make sure your webcam is connected, then run:
    
    python3 main.py

🧪 Training the Model
- To train the CNN from scratch:
    python3 train_network.py
- The trained model will be saved as mask.model.

📷 Testing the Model
- To test the model using sample images in the images/ folder:

        python3 test_network.py

- Ensure that the folder contains valid gesture images.

🛠️ Troubleshooting

    - Ensure correct paths for dataset, images, and model files.
    
    - Use clear, well-lit hand gestures for better recognition.
    
    For low accuracy:
            
            Increase the dataset size
            
            Improve image quality
            
            Tune network hyperparameters or retrain

📚 Citation
If you use this project in your work, please cite:

      Malavika Suresh, Avigyan Sinha, Aneesh R P,
      “Real-Time Hand Gesture Recognition Using Deep Learning”,
      International Journal of Innovations and Implementations in Engineering (ISSN 2454-3489), 2019, Vol. 1.



      @article{malavika2019gesture,
        title={Real-Time Hand Gesture Recognition Using Deep Learning},
        author={Suresh, Malavika and Sinha, Avigyan and R P, Aneesh},
        journal={International Journal of Innovations and Implementations in Engineering},
        volume={1},
        year={2019},
        issn={2454-3489}
      }



