# Image Classification using TensorFlow and Teachable Machine

This project demonstrates an image classification model trained using Teachable Machine. The model is used to classify images into two categories: `Dress` and `T-shirt`.

## Project Overview

- The model was trained using Teachable Machine.
- Exported in TensorFlow format.
- A Jupyter Notebook (`predict.ipynb`) is provided to load the model, preprocess images, and make predictions.

## Files in the Repository

- `saved_model/`: Contains the TensorFlow exported model files.
  - `saved_model.pb`: The main model file.
  - `variables/`: Directory containing model weights.
- `labels.txt`: A text file containing the class labels.
- `predict.ipynb`: The Jupyter Notebook for loading the model and running predictions.

## Requirements

To run this project, ensure you have the following installed:

- Python 3.7+
- TensorFlow 2.11.0
- NumPy
- Pillow (PIL)

Install the dependencies using pip:

```bash
pip install tensorflow==2.11.0 numpy pillow
```

## How to Use

1. **Run the Jupyter Notebook**:
   Open `predict.ipynb` in Jupyter Notebook or Google Colab :
   - Load the model.
   - Preprocess an image.
   - Make predictions.

2. **Output**:
   The notebook will output the predicted class and the confidence score. Example:

   ```
   Predicted Class: Dress, Confidence: 0.95
   ```

## Project Structure

```
├── saved_model/
│   ├── saved_model.pb
│   └── variables/
│       ├── variables.data-00000-of-00001
│       └── variables.index
├── labels.txt
├── predict.ipynb
└── README.md
```

