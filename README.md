
# Object Detection Using Sliding Window with SVM Classifier

## Description
This project implements an object detection method using a Support Vector Machine (SVM) classifier, incorporating the sliding window technique to localize and identify vehicles within images. The project leverages computer vision techniques to explore spatial, color, and gradient features for effective vehicle detection.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Data Paths](#data-paths)
- [Methodology](#methodology)
- [Objectives](#objectives)
- [How to Use the Notebook](#how-to-use-the-notebook)
- [Contributions](#contributions)
- [License](#license)

## Technologies Used
- Python
- Libraries:
  - OpenCV
  - Scikit-learn
  - NumPy
  - Matplotlib

## Data Paths
- **Vehicles dataset**:
  ```python
  vehicles_path = '/content/drive/MyDrive/CompVis/Data_Zip/Data_Zip/vehicles'
  ```
- **Non-vehicles dataset**:
  ```python
  non_vehicles_path = '/content/drive/MyDrive/CompVis/Data_Zip/Data_Zip/non-vehicles'
  ```

## Methodology
In this project, we utilize techniques from computer vision to detect vehicles in images by exploring spatial, color, and gradient features. The SVM classifier is employed to classify these features effectively.

## Objectives
- Perform feature extraction using Histogram of Oriented Gradients (HOG) on a labeled training dataset and train a linear SVM classifier.
- Explore color spaces, color histograms, and spatial clustering as features for the classifier.
- Investigate HOG as a potentially useful feature extraction technique.
- Evaluate different classifiers in combination with feature selections to balance high test accuracy, low false positives, and short execution time.
- Train the selected classifier with chosen features on a labeled training image set, focusing on feature normalization and random selection for training and testing.
- Implement a sliding window technique and utilize the trained classifier to search for vehicles in images.
- Create a heatmap of recurring detections frame by frame to filter out outliers and track detected vehicles, estimating bounding boxes for identified vehicles.

## How to Use the Notebook
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Ensure that the dataset paths are correctly set.
3. Execute each cell to perform the object detection process.

## Contributions
Contributions are welcome! If you would like to contribute to this project, please feel free to submit suggestions or modifications.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
```

