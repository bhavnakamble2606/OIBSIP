# Wine Quality Prediction using Machine Learning

## Project Overview
This project analyzes the chemical properties of red wine and predicts wine quality using a Random Forest Classifier.

## Dataset
- Dataset file: `winequality-red.csv`
- Total rows: 1,599
- Total columns: 12
- Target column: `quality`
- Missing values: 0

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps
1. Loaded and explored the dataset.
2. Checked missing values and descriptive statistics.
3. Visualized wine quality distribution.
4. Analyzed correlations between chemical properties and quality.
5. Split the dataset into 80% training and 20% testing data.
6. Trained a Random Forest Classifier.
7. Evaluated the model using accuracy and a classification report.
8. Created a confusion matrix.

## Model Results
- Training rows: 1,279
- Testing rows: 320
- Model Accuracy: 67.81%

## Conclusion
The Random Forest Classifier achieved 67.81% accuracy on the test dataset. Alcohol showed a positive correlation with wine quality, while volatile acidity showed a negative correlation. Performance may vary across quality scores because some scores have fewer samples.

## How to Run
1. Install the required Python libraries.
2. Place `winequality-red.csv` in the project folder.
3. Open `wine_quality_prediction.ipynb` in VS Code.
4. Run the notebook cells in order.

## Internship
Oasis Infobyte Data Analytics Internship — Level 2, Task 2
