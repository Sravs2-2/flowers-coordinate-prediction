# Flowers Dataset Single Pixel Coordinate Prediction

## Introduction
This project aims to build and train a model to predict the single pixel coordinate of flowers in images from the Flowers Dataset. The minimum input image size for the model is set to 256x256.

## Table of Contents
- [Dependencies](#dependencies)
- [How to Run Locally](#how-to-run-locally)
- [How to Run in a Containerized Environment](#how-to-run-in-a-containerized-environment)
- [Code Style](#code-style)

## Dependencies
Make sure you have the following dependencies installed:
- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- scikit-learn

You can install the dependencies using the following command:
```bash
pip install -r requirements.txt
```

### Local Environment
1. Clone the repository:
 ```bash
  git clone https://github.com/Sravs2-2/sravani_ML.git
  cd sravani_ML
 ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. train the training script:
   ```bash
    python train.py
   ```

### Containerized Environment (Docker)
Ensure you have Docker installed on your machine.

1. Build the Docker image:
    ```bash
    docker build -t sravani-ml 
    ```

2. Run the Docker container:
    ```bash
    docker run -it sravani-ml
    ```

## Code Style (PEP 8 Compliance)

The code follows the PEP 8 style guidelines. To check for compliance, you can use tools like `flake8`:

```bash
flake8
```











