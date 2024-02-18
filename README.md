# Breast Cancer Diagnosis Prediction

This project is centered on the task of classifying breast masses as either malignant or benign, which is vital in the early detection and treatment of breast cancer. The data used for this prediction is sourced from digitized images of a fine needle aspirate (FNA) of a breast mass. The dataset includes features that capture various attributes of the cell nuclei present in the image.

Each instance in the dataset includes:

- **ID number**: A unique identifier for each sample.
- **Diagnosis**: The diagnosis outcome, where 'M' stands for malignant and 'B' stands for benign.

The dataset computes ten real-valued features for each cell nucleus, which include:

- **Radius**: The average distance from the center to points on the perimeter of the nucleus.
- **Texture**: The standard deviation of gray-scale values within the nucleus.
- **Perimeter**: The total distance around the nucleus.
- **Area**: The total area covered by the nucleus.
- **Smoothness**: A measure of variations in radius lengths.
- **Compactness**: Calculated as the square of the perimeter divided by the area minus 1.0.
- **Concavity**: A measure of the severity of concave portions of the nucleus contour.
- **Concave points**: The count of concave portions of the nucleus contour.
- **Symmetry**: A measure of the nucleus' symmetry.
- **Fractal dimension**: An approximation of the nucleus' "coastline" using fractal geometry principles.

These features offer a quantitative analysis of cell nuclei characteristics, which can help differentiate between malignant and benign breast masses. By training a machine learning model on this dataset, we aim to create a predictive model that can contribute to the early detection and diagnosis of breast cancer.
