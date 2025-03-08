💻 Laptop Price Predictor


Welcome to the Laptop Price Predictor! 🎉
This project combines machine learning models with intuitive user interfaces to predict laptop prices based on specifications and features.

📋 Table of Contents
📄 Description
✨ Features
📊 Dataset Details
🤖 Regressor Models
🌟 Selected Models
💵 Price Currency Conversion
🖥️ Running the Application
📈 Metrics
💡 Future Enhancements
🌟 Contribution
📄 Description
The Laptop Price Predictor uses various regression models to predict laptop prices based on their specifications. Designed to support data enthusiasts and tech shoppers, this tool is powered by Python and machine learning libraries.

✨ Features
💻 Predict laptop prices based on features like company, CPU, RAM, GPU, and more.
🔍 Experiment with multiple regression models for optimal results.
🌍 Supports currency conversion from INR to USD.
📈 Evaluate models using key metrics: R² Score and Mean Absolute Error (MAE).
📊 Dataset Details
The dataset includes 1302 laptops with 12 attributes, sourced from Amazon (2017-2018).

Attribute	Description
Company Name	Laptop brand (e.g., Dell, HP, Apple)
Type Name	Form factor (e.g., Ultrabook, Gaming)
Laptop Size	Screen size (in inches)
Screen Resolution	Display resolution (e.g., 1920x1080)
CPU	Processor type
RAM	Memory capacity (GB)
Memory	Storage capacity (HDD/SSD)
GPU	Graphics card details
Operating System	OS type (e.g., Windows, macOS)
Price (INR)	Price in Indian Rupees
🤖 Regressor Models
Model	Description
Multiple Linear Regression	Basic regression model
Ridge Regression	Regularized linear regression
Lasso Regression	Sparse regression
k-Nearest Neighbors (k-NN)	Distance-based prediction
Decision Tree	Tree-based regression model
Support Vector Machine	Kernel-based regression
Random Forest	Ensemble tree model
Extra Trees	Advanced ensemble model
Adaptive Boost (AdaBoost)	Boosting-based ensemble
Gradient Boost	Gradient-based optimization
XGBoost	Highly efficient boosting
Voting Regressor	Combines multiple models
Stacking Regressor	Model stacking for better accuracy
🌟 Selected Models
1. Random Forest Regressor
R² Score: 88.78%
Mean Absolute Error: 15.94%
2. Voting Regressor (Random Forest + Gradient Boost)
R² Score: 89.27%
Mean Absolute Error: 15.37%
💵 Price Currency Conversion
This project supports price conversion from INR to USD.
Default exchange rate: 1 INR = 0.012 USD

python
Copy
Edit
st.title(f"\nPrice: {round(predicted_price * 0.012, 2)} USD")  
The exchange rate can be easily updated as needed.

🖥️ Running the Application
Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt  
Launch the Streamlit application:

bash
Copy
Edit
streamlit run app.py  
📈 Metrics
The performance of each regression model is evaluated using:

R² Score: Measures the variance explained by the model.
Mean Absolute Error (MAE): Captures the average prediction error.
💡 Future Enhancements
Integration with live datasets for real-time predictions.
Incorporating deep learning models for improved accuracy.
Adding support for additional currency conversions and visualization dashboards.
🌟 Contribution
💡 Ideas? Contributions are always welcome! Submit issues, pull requests, or share your feedback to help improve this project.

⭐ If you found this project useful, don't forget to star the repository! 😊

<br />
Made with ❤️ by Soumya Ranjan Nayak for machine learning enthusiasts

Follow for more😁✌🏻