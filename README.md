# Artificial Neural Network (ANN) for Handwritten Digit Recognition

This repository contains a Jupyter Notebook (`Ann_project2_AmirHosseinEslami.ipynb`) that implements an Artificial Neural Network (ANN) from scratch. This project was developed as part of an AI Course under Dr. Abdi.

The goal of this project is to build and train an ANN to perform handwritten digit recognition, likely using a widely recognized dataset such as MNIST. The notebook provides a detailed, step-by-step implementation of the ANN, including its architecture, forward propagation, backward propagation, and optimization process.

---

## Project Details

* **Course:** AI Course, Project 2
* **Instructor:** Dr. Abdi
* **Designed by:** Kasra Shariati & Amirhossein Hosseini
* 
---

## Features

* **Custom ANN Implementation:** The notebook provides a ground-up implementation of a feedforward Artificial Neural Network.
* **Forward and Backward Propagation:** Detailed steps for calculating outputs and gradients during training.
* **Weight Update Mechanism:** Includes the logic for updating network weights based on the calculated gradients.
* **Regularization (L2):** The presence of `lmbda * weight` in the backpropagation suggests the inclusion of L2 regularization to prevent overfitting.
* **Handwritten Digit Recognition:** The primary application of this ANN is to classify handwritten digits.

---

## Getting Started

To run this notebook locally, follow these steps:

### Prerequisites

You'll need Python 3 installed on your system.
The project primarily uses `numpy` for numerical operations. Depending on the full scope of the notebook, you might also need other libraries like `matplotlib` for plotting or `scikit-learn` for data preprocessing/evaluation metrics.

You can install the necessary libraries using pip:

```bash
pip install numpy matplotlib scikit-learn # Add other libraries as needed (e.g., tensorflow if used for comparison)
```

### Running the Notebook

1.  **Clone the repository** (or download the `Ann_project2_AmirHosseinEslami.ipynb` file directly):

    ```bash
    git clone https://github.com/AmirHosseinEslami/ANN-Handwritten-Digit-Recognition.git
    cd ANN-Handwritten-Digit-Recognition
    ```
    (Replace `AmirHosseinEslami` and `ANN-Handwritten-Digit-Recognition` with your actual GitHub username and repository name if different.)

2.  **Start Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

3.  **Open the notebook:** Your web browser will open Jupyter's dashboard. Navigate to and open `Ann_project2_AmirHosseinEslami.ipynb`.

4.  **Run the cells:** You can run the cells sequentially to execute the ANN implementation and observe its performance.

---

## Project Structure

* `Ann_project2_AmirHosseinEslami.ipynb`: The main Jupyter Notebook containing the full implementation of the ANN.
* `README.md`: This file.
* `requirements.txt` (Optional): Lists the Python dependencies.

---

## Acknowledgments

This project was completed as part of the AI Course under the guidance of Dr. Abdi.
Special thanks to Kasra Shariati for collaboration on the design.

---
