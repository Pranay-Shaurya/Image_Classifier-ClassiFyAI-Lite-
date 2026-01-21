# ClassiFyAI Lite

ClassiFyAI Lite is a lightweight image classification app built with a graphical user interface (GUI). It uses a pre-trained deep learning model (Keras/TensorFlow) to identify objects in images from the CIFAR-10 dataset — including airplanes, automobiles, cats, dogs, ships, and more.

<br/>

##  Features

- Simple and responsive GUI built using [Taipy](https://www.taipy.io/)
- Supports image upload and preview
- Integrates with a trained TensorFlow/Keras model
- Classifies images into 10 categories (CIFAR-10)
- Built for ease of use and quick predictions

<br/>

## Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt

Project Structure

ml_gui_app/
├── app.py                  # Main application file
├── model.h5                # Pre-trained Keras model
├── image_utils.py          # Utility functions for image processing
├── assets/                 # Optional folder for logos or icons
├── requirements.txt        # Python dependencies
└── README.md               # Project documented details

Classes Supported (CIFAR-10)
| Class Index | Class Name |
| ----------- | ---------- |
| 0           | Airplane   |
| 1           | Automobile |
| 2           | Bird       |
| 3           | Cat        |
| 4           | Deer       |
| 5           | Dog        |
| 6           | Frog       |
| 7           | Horse      |
| 8           | Ship       |
| 9           | Truck      |

Acknowledgements:

TensorFlow & Keras
Taipy GUI Framework
CIFAR-10 Dataset


