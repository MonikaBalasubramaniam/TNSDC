# House Prices Prediction Using Deep Learning (PyTorch) and XGBoost

## Description
This machine learning project aims to predict house prices using deep learning techniques implemented in PyTorch and the XGBoost algorithm. The goal is to build models that accurately predict the median house value based on various features.

## Overview
1. Built an MLP regressor using PyTorch to predict median house value.
2. Utilized evaluation indices such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE) to assess model performance.
3. Constructed an MLP model with 4 layers and applied the sigmoid activation function.
4. Compared the performance of the MLP model with the XGBoost algorithm.
5. Observed that the MSE/MAE/MAPE of the MLP model were 0.019, 0.098, and 0.28, respectively, while for XGBoost, they were 22928, 32029, and 0.178. This indicates that the MLP model outperforms XGBoost.
6. Calculated the accuracy of the MLP model to be 0.042, and for XGBoost, it was 33383. Thus, the accuracy of the MLP model is superior to that of XGBoost.

## Installation
To run this project, ensure you have Python installed. Then, install the required libraries using the following command:

pip install torch numpy pandas matplotlib scikit-learn xgboost

## Usage
1. Clone the repository: git clone <repository-url>
2. Navigate to the project directory: cd project-directory
3.  Run the Python script to execute the models: python house_prices_prediction.py


## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request

## License
This project is licensed under the [MIT License](LICENSE).

Feel free to modify this template to better suit your project's specific needs and requirements.





