# Age Classification with Naive Bayes Classifier

This project uses a Naive Bayes Classifier to classify facial images into two age groups: "young adult" and "adult." The classifier is based on statistical features calculated from training images and operates in the LAB color space for more robust color representation.

## Project Structure

- Training and Testing Data: Organized into directories for "young adult" and "adult" images.
- Model Building: Image preprocessing, mean and variance calculations for each class, and implementation of the Naive Bayes algorithm.
- Evaluation: Accuracy measurement and visualizations to assess model performance.
- Presentation Enhancements: Visualization of the mean and variance in images, interactive graphs, and a potential Streamlit web application for interactive classification.

## Approach

1. Image Preprocessing
    - Images are converted from BGR to LAB color space, as it helps with lighting and color consistency in images.
    - Images are flattened into vectors for easier statistical calculation.
2. Training
    - **Mean and Variance Calculation**: For each class, the pixel-wise mean and variance are calculated. These values help to model the probability distributions used in classification.
3. Testing
    - **Naive Bayes Classification**: For each test image, the probability of it belonging to each class is calculated. The class with the highest probability is chosen as the predicted class.
4. Visualization
    - The means and standard deviations of pixel values for each class are displayed to show the distinct characteristics of each class.
>>>>>>> b005112 (first commit)
