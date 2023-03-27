# Wine-quality-level-detection-system-ML

This is a project for detecting the quality level of wine using machine learning algorithms. The dataset used in this project is the Wine Quality dataset from the UCI Machine Learning Repository.

## Project Overview

The project uses logistic regression to classify wine into three quality levels: low, high. The dataset is preprocessed to remove any missing or incomplete data and to normalize the feature values. Many models are trained on the preprocessed dataset and evaluated using accuracy score and confusion matrix.


# Description of Qualities

1. Alcohol: the amount of alcohol in wine
2. Volatile acidity: acetic acid content which leading to an unpleasant vinegar taste
3. Sulphates: a wine additive that contributes to SO2 levels and acts as an antimicrobial and antioxidant
4. Citric Acid: acts as a preservative to increase acidity (small quantities add freshness and flavor to wines)
5. Total Sulfur Dioxide: is the amount of SO2
6. Density: sweeter wines have a higher density
7. Chlorides: the amount of salt 
8. Fixed acidity: are non-volatile acids that do not evaporate easily
9. pH: the level of acidity
10. Free Sulfur Dioxide: it prevents microbial growth and the oxidation of wine
11. Residual sugar: is the amount of sugar remaining after fermentation stops.  (Wines > 45g/ltrs are sweet)

## Usage

### Dataset

The Wine Quality dataset used in this project is available on the UCI Machine Learning Repository. The dataset contains 11 input features and a target variable indicating the quality level of the wine. 

### Software Setup

To run this project, you will need to install the following Python packages:

- pandas
- numpy
- scikit-learn

You can install these packages using pip:

    pip install pandas numpy scikit-learn

### Usage

Once you have installed the required packages, you can run the `Red_wine.ipynb` and `White_wine.ipynb` script to train and evaluate the logistic regression model on the Wine Quality dataset. 

To do this, navigate to the project directory and run the following command:

    jupyter nbconvert --execute <notebook>


You can find the data set right here --> https://archive.ics.uci.edu/ml/datasets/wine+quality

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
