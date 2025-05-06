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

bash
Copy
Edit
python3 main.py
🧪 Training the Model
To train the CNN from scratch:

bash
Copy
Edit
python3 train_network.py
The trained model will be saved as mask.model.

📷 Testing the Model
To test the model using sample images in the images/ folder:

bash
Copy
Edit
python3 test_network.py
Ensure that the folder contains valid gesture images.

🛠️ Troubleshooting
Ensure correct paths for dataset, images, and model files.

Use clear, well-lit hand gestures for better recognition.

For low accuracy:

Increase the dataset size

Improve image quality

Tune network hyperparameters or retrain

📚 Citation
If you use this project in your work, please cite:

Malavika Suresh, Avigyan Sinha, Aneesh R P,
“Real-Time Hand Gesture Recognition Using Deep Learning”,
International Journal of Innovations and Implementations in Engineering (ISSN 2454-3489), 2019, Vol. 1.

bibtex
Copy
Edit
@article{malavika2019gesture,
  title={Real-Time Hand Gesture Recognition Using Deep Learning},
  author={Suresh, Malavika and Sinha, Avigyan and R P, Aneesh},
  journal={International Journal of Innovations and Implementations in Engineering},
  volume={1},
  year={2019},
  issn={2454-3489}
}
📄 License
This project is licensed under the MIT License.

vbnet
Copy
Edit
MIT License

Copyright (c) 2019 Malavika Suresh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
