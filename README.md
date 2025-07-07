# digit-recognition-cnn
This is a digit recognition service built using Convolutional Neural Networks (CNN) in TensorFlow and OpenCV for image preprocessing. It can train on the MNIST dataset and predict handwritten digits from PNG images.

---
1. Content
## 🗂️ Project Structure
digit-recognition-cnn/
├── src/
│ ├── main.py # Train the CNN model and save it as handwritten.h5
│ ├── predict.py # Load model and predict digits from images
│ ├── handwritten.h5 # Trained CNN model
│ ├── input/ # Folder with PNG images to predict
├── venv/ (or myenv/) # Virtual environment (should NOT be pushed to GitHub)
├── .gitignore
├── requirements.txt
├── README.md

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sammykhan214/digit-recognition-cnn.git
cd digit-recognition-cnn

2. Set Up a Virtual Environment
python -m venv myenv
source myenv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Train the Model
To train the model using the MNIST dataset and save it as handwritten.h5:
python src/main.py

5. Predict Digits
To predict digits from all PNG images in the src/input/ folder:
python src/predict.py

6. Dependencies
Python 3.x
TensorFlow
OpenCV (opencv-python)
NumPy

7. .gitignore Recommendations
# Ignore virtual environments
venv/
myenv/

# Ignore model weights
*.h5

# Ignore cache and temp files
__pycache__/
*.pyc
.DS_Store


8. Author
Mohammed Samme
Digit Recognition using CNN and OpenCV