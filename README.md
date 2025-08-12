# 🚗 Car Price Prediction

This project focuses on predicting the selling price of used cars based on various features. It utilizes Linear Regression and Lasso Regression models to perform the predictions, along with data preprocessing and visualization techniques.

## 📊 Dataset

The dataset used is car data.csv, which contains information about various cars including their name, year of purchase, selling price, present price, kilometers driven, fuel type, seller type, transmission, and number of owners.

## ✨ Features

Data Loading and Inspection: Loads the dataset into a pandas DataFrame and provides initial insights using head(), shape, and info().

Missing Value Check: Verifies and confirms no missing values in the dataset.

Categorical Data Distribution: Analyzes the distribution of categorical features like Fuel_Type, Seller_Type, and Transmission.

Categorical to Numerical Conversion: Encodes categorical features into numerical representations for model compatibility.

Fuel_Type: Petrol (0), Diesel (1), CNG (2)

Seller_Type: Dealer (0), Individual (1)

Transmission: Manual (0), Automatic (1)

Feature and Target Separation: Splits the dataset into features (X) and target (Y), where 'Selling_Price' is the target variable.

Data Splitting: Divides the data into training and testing sets (90% training, 10% testing) for model evaluation.

Linear Regression Model:

Trains a Linear Regression model on the training data.

Evaluates the model's performance using the R-squared error on both training and test data.

Visualizes actual vs. predicted prices using scatter plots for both training and test datasets.

Lasso Regression Model:

Trains a Lasso Regression model on the training data.

Evaluates the model's performance using the R-squared error on both training and test data.

Visualizes actual vs. predicted prices using scatter plots for both training and test datasets.

## 🛠️ Technologies Used

Python

pandas: For data loading and manipulation.

matplotlib.pyplot: For creating static, interactive, and animated visualizations.

seaborn: For statistical data visualization.

scikit-learn: For machine learning tasks, including:

train_test_split: For splitting data into training and testing sets.

LinearRegression: For implementing the Linear Regression model.

Lasso: For implementing the Lasso Regression model.

metrics: For evaluating model performance (e.g., R-squared error).

## 📦 Requirements

To run this project, you will need the following Python libraries:

pandas

matplotlib

seaborn

scikit-learn

## 🚀 Getting Started

To get a copy of this project up and running on your local machine, follow these steps.

### Installation

Clone the repository (if applicable):

```
git clone <repository_url>
cd <repository_name>
```

Install the required Python packages:

```
pip install pandas matplotlib seaborn scikit-learn
```

### Usage

Place the dataset: Ensure the car data.csv file is located in the same directory as the Jupyter notebook (Car_Price_Prediction.ipynb).

Run the Jupyter Notebook: Open and execute the cells in the Car_Price_Prediction.ipynb notebook in a Jupyter environment (e.g., Jupyter Lab, Jupyter Notebook, Google Colab).

The notebook will:

Load and preprocess the car data.

Train both Linear Regression and Lasso Regression models.

Output the R-squared error for both models on training and test datasets.

Display scatter plots comparing actual vs. predicted prices.

## 📈 Results

The notebook provides R-squared error scores for both Linear Regression and Lasso Regression models, indicating how well the models fit the data. It also includes scatter plots to visually assess the prediction accuracy.

Linear Regression R-squared (Training Data): Approximately 0.8799

Linear Regression R-squared (Test Data): Approximately 0.8366

Lasso Regression R-squared (Training Data): Approximately 0.8428

Lasso Regression R-squared (Test Data): Approximately 0.8709

These results suggest that both models perform reasonably well, with Lasso Regression showing slightly better performance on the test data in this specific run.

## 🧑‍💻 Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature-name).

Make your changes.

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature/your-feature-name).

Open a Pull Request.

## 📄 License

This project is open-source and available under the MIT License.
