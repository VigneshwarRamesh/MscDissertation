📊 Predictive Analytics for Real Estate Market Trends Using Machine Learning
🏡 Project Overview
This project develops a machine learning-driven recommendation system for the UK real estate market. It predicts property prices and classifies regions into investment and rental markets, helping investors and tenants make data-driven decisions.

🔑 Key Features
📈 Property Price Prediction: Uses Random Forest, XGBoost, and Linear Regression.
🏡 Investment Market Classification: Utilizes Neural Networks.
🏠 Rental Market Segmentation: Implements K-Means Clustering.
🌍 Data Integration: Integrates PropertyData API, Bank of England data, and UK geospatial data.
📊 Interactive Dashboard: Uses AWS QuickSight for real-time visualization.

🔗 View QuickSight Dashboard

📂 Repository Structure
|── data/                         # Raw and processed datasets
|── notebooks/                     # Jupyter Notebooks for analysis & model training
|   |── dissertation_python_script.ipynb
|   |── model_future_average_price_finished.ipynb
|   |── model_investment_finished.ipynb
|   |── rental_model_finished.ipynb
|── reports/                       # Research & presentation materials
|   |── Dissertation_Report.pdf
|   |── Dissertation_Presentation.pptx
|── scripts/                       # Python scripts for ETL & deployment
|── README.md                      # Project documentation (this file)

⚙️ Technologies Used
Category	Tools & Technologies
Programming	Python (Pandas, NumPy, Scikit-Learn, TensorFlow, Matplotlib)
Machine Learning	Random Forest, XGBoost, Linear Regression, Neural Networks, K-Means Clustering
Data Sources	PropertyData API, Bank of England, UK Geospatial Data
Visualization	AWS QuickSight
Infrastructure	Databricks, AWS RDS

🚀 Installation & Setup
Prerequisites
Ensure you have the following installed:

Python 3.8+
Jupyter Notebook
Required Python packages:
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn requests

Running the Notebooks
Clone the repository:
git clone https://github.com/your-username/real-estate-prediction.git
cd real-estate-prediction

Open Jupyter Notebook:
jupyter notebook

Navigate to the notebooks/ directory and execute the scripts.

📊 Results & Insights
✔ Random Forest model achieved MSE of 3.92, making it the most accurate model for property price prediction.
✔ Neural Network classifier achieved 81% accuracy in classifying investment markets.
✔ K-Means Clustering model provided clear rental market segmentation (homogeneity score of 0.82).
✔ AWS QuickSight Dashboard provides interactive real estate insights.

🔮 Future Enhancements
🚀 Expand model coverage to postcode-level predictions.
📡 Integrate real-time data feeds for dynamic market analysis.
📱 Develop a mobile-friendly version of the dashboard.
🔄 Improve model adaptability for evolving market conditions.

🤝 Contributing
We welcome contributions!
To contribute:

Fork the repository.
Create a new branch (feature-branch).
Commit your changes and push them.
Open a Pull Request.

📝 License
This project is open-source under the MIT License.




