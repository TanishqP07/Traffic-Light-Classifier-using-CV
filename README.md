# 🚦 Traffic Light Classifier

A machine learning project designed to classify traffic lights into **Red**, **Yellow**, or **Green** categories using computer vision techniques. This project processes traffic light images, extracts relevant features, and classifies the state of the light for applications in autonomous driving.

---

## 🌟 Features
- **Traffic Light Classification**: Classifies traffic light states as red, yellow, or green.
- **Dataset Handling**: Utilizes traffic light image datasets for training and testing.
- **Error Prevention**: Ensures no red light is classified as green.
- **Extensible**: Modular code that supports future enhancements.

---

## 🛠️ Technologies Used
- **Programming Language**: Python 3.7+
- **Libraries**:
  - [OpenCV](https://opencv.org/) for image processing.
  - [NumPy](https://numpy.org/) for numerical computations.
  - [Matplotlib](https://matplotlib.org/) for visualization.
  - [Jupyter Notebook](https://jupyter.org/) for interactive coding and analysis.

---

## 📦 Installation

### Prerequisites
- Python 3.7 or later.
- Traffic light image dataset.

---

### Steps
- Clone the repository:
   ```bash
   git clone https://github.com/TanishqP07/Traffic-Light-Classifier-using-CV.git
   cd Traffic-Light-Classifier-using-CV

- Install dependencies:
   ```bash
   pip install -r requirements.txt

---

# 📋 Usage

### Run the Notebook:
- Open `Traffic_Light_Classifier.ipynb` in Jupyter Notebook.
- Execute the cells step-by-step to:
  - Load data.
  - Preprocess images.
  - Extract features.
  - Classify traffic lights.

---

### Validate Functions:
- Use `test_functions.py` to validate critical functions like `one_hot_encode`.

---

### Dataset:
- Place your dataset in the `traffic_light_images` directory.
- Ensure the structure includes subdirectories for:
  - `red`
  - `yellow`
  - `green`

---

# 🚀 Future Enhancements

- Improve classification accuracy with larger datasets and advanced techniques.
- Implement object detection to handle multiple traffic lights in an image.
- Add real-time video classification using live webcam input.

---

# 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

# 📫 Contact

For any questions or collaboration, feel free to reach out:
- **Email**: [tanishq.m.pawar@gmail.com](mailto:tanishq.m.pawar@gmail.com)
- **GitHub**: [TanishqP07](https://github.com/TanishqP07)

---

# 📂 Dataset Information

The dataset used in this project consists of traffic light images categorized into:
- **Red Traffic Lights**
- **Yellow Traffic Lights**
- **Green Traffic Lights**

*The dataset used for this project is included in the repository under the `traffic_light_images` folder.*

---

# 🧪 Tests

The `test_functions.py` file contains unit tests to ensure the accuracy of critical components. To run the tests:
1. Open the file in a Python environment.
2. Execute the functions using:
   ```bash
   python test_functions.py


