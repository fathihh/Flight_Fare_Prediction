✈️ Flight Fare Prediction

The Flight Fare Prediction project uses machine learning to analyze and predict flight ticket prices based on key factors such as airline, route, journey time, duration, and number of stops. Accurate flight fare prediction helps both airlines and passengers — airlines can optimize pricing strategies, and travelers can make better booking decisions.

📘 Project Overview

In the highly competitive airline industry, understanding and predicting flight prices is essential. Flight pricing depends on various features such as:

Airline

Source and Destination

Date of Journey

Departure and Arrival Time

Duration

Total Stops

Additional Information

Price (Target variable)

The project explores these variables using exploratory data analysis (EDA) and machine learning models to identify the most influential factors and build an accurate fare prediction model.

📊 Dataset Information

Dataset Name: Flight_Fare.xlsx
Total Records: 10,683

Key Features:

Airline – Name of the airline operating the flight

Date_of_Journey – Date when the flight is scheduled

Source – Departure city

Destination – Arrival city

Route – Route taken by the flight (including layovers)

Dep_Time – Flight departure time

Arrival_Time – Flight arrival time

Duration – Total journey time

Total_Stops – Number of stops in the journey

Price – Target variable (fare price)

⚙️ Workflow

Data Loading and Cleaning – Load dataset and handle missing values

Feature Engineering – Convert date/time features and extract relevant patterns

Encoding Categorical Variables – Convert text to numerical format

Exploratory Data Analysis (EDA) – Visualize flight patterns and price trends

Model Building – Train regression models like Linear Regression, Decision Tree, and Random Forest

Model Evaluation – Evaluate model performance using metrics such as R² score, MAE, and RMSE

Prediction – Predict flight prices based on new input features

🤖 Machine Learning Models Used

Linear Regression

Decision Tree Regressor

Random Forest Regressor (Best performing model)

The Random Forest model achieved the highest accuracy, demonstrating strong performance in capturing non-linear relationships and handling categorical features effectively.

📈 Results & Insights

Random Forest achieved high predictive accuracy.

Flight fares are most influenced by Airline, Total Stops, and Duration.

Evening flights tend to be costlier than early morning ones.

Non-stop flights show the highest price range.

🚀 Future Enhancements

Integrate real-time flight data using APIs

Deploy the model as a web app (e.g., Flask or Streamlit)

Experiment with advanced models like XGBoost and CatBoost

Incorporate features like seasonality or demand trends

🧠 Tech Stack

Python

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook
