# 🩺 ImageCLEF Medical Caption


This repository hosts a comprehensive Jupyter Notebook that presents a solution for automatically generating captions for radiology images; a multi-label classifiaction task. The notebook implements an image captioning pipeline designed for the [Image CLEF 2019 Concept Detection Challenge](https://www.imageclef.org/2019/medical/caption/) and incorporates data preprocessing, feature extraction, deep learning model training, and evaluation steps.


## Overview

- The project addresses the challenge of generating descriptive multi-label captions tailored to radiology images.
- It leverages deep learning techniques, including a convolutional neural network (CNN) and a pre-trained model.
- The notebook provides a detailed walkthrough—from loading and preprocessing data to training the captioning model and assessing performance using evaluation metrics.


## **🛠️ Installation & Setup**  
1. **Clone the repo**  
   ```bash
   git clone https://github.com/nantoniou/ImageCLEF-Medical-Caption.git
   cd ImageCLEF-Medical-Caption
   ```
2. **Create & activate a virtual environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Launch the Notebook**
   ```bash
   jupyter notebook 4_imageCLEF_medical_caption_task.ipynb
   ```

## 🚀 Future Work

- Experiment with alternative deep learning architectures and advanced preprocessing techniques.
- Incorporate attention mechanisms to further enhance caption quality.
- Introduce additional evaluation strategies and optimize hyperparameters for better performance.
- Explore larger and more diverse datasets to validate and extend the model's capabilities.

## License

This project is licensed under the GNU General Public License v3.0.

