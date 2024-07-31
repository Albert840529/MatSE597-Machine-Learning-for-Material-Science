# MatSE597 (Machine Learning for Material Science) - Final Project

## Semi-Supervised Learning for Understanding Composite Morphology and Mechanical Properties

### 1. Data

In the `Images` folder, you will find all the µ-CT images used for this project. The folder structure is as follows:
- **Subfolders**: Each subfolder contains:
  - 100 images
  - One CSV file with the names and features of each image

- **Subfolder Naming**: Each subfolder name represents the name of the composite and its mechanical properties:
  - Example: `IPP_5%_4_0.44_1.403_0.245`
    - `IPP_5%_4`: Name of the composite
    - `0.44`: UTS (MPa)
    - `1.403`: Young's modulus (GPa)
    - `0.245`: Elongation at break (%)

This naming convention is used in the data preprocessing code: `Final_project_data_preprocess.ipynb`.

### 2. Code

There are two main code files in this repository:

- **`Final_project_data_preprocess.ipynb`**: 
  - Purpose: Loads images and analyzes image features, saving them into a CSV file for use in transfer learning.
  - Instructions: Import your images into the `Images` folder and organize them into subfolders according to the naming rules described above.

- **`Final_project_data_training.ipynb`**: 
  - Purpose: Trains the dataset and evaluates the performance of the model.
  - Instructions: Run this notebook to train your model and assess its performance.

To directly access the trained model, you can download it from the following link:

- **Trained Model Download**: [Download Trained Model](https://drive.google.com/file/d/14Ji493VZq2nxneOxnRn9NWlcDHzA-PB9/view?usp=sharing)

### 3. CT-Images Dataset

The dataset used for this project can be accessed via the following link:

- **CT-Images Dataset**: [Download CT-Images Dataset](https://drive.google.com/drive/folders/1M4rYcE8KqSGjYIP5dHxOa0G2gUy6G3wt?usp=share_link)

## Notes

- Ensure that the folder structure and naming conventions are followed to avoid issues with data preprocessing.
- If you encounter any issues or have questions, please feel free to open an issue in this repository.

