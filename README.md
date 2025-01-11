# Predictive Maintenance System

This project is done as a part of my industry orinted internship in _**Cothon Solutions**_, this project demonstrates the use of machine learning and deep learning techniques to predict equipment failures using sensor data. The goal is to develop a predictive maintenance system that forecasts when a piece of equipment is likely to fail, reducing downtime and maintenance costs.

## **Technologies Used**
- **Programming Language**: Python
- **Machine Learning Libraries**: 
  - `Scikit-learn` (Random Forest, XGBoost)
  - `XGBoost` (Gradient Boosting)
- **Deep Learning Framework**: 
  - `TensorFlow`/`Keras` (LSTM for time-series data)
- **Data Handling & Processing**: 
  - `Pandas` for data manipulation
  - `NumPy` for numerical operations
- **Visualization**: 
  - `Matplotlib` for plotting sensor data and model results
- **Environment**: 
  - Google Colab (for running code on cloud-based resources with GPU support)


## **Project Workflow**
1. **Data Preprocessing**:
   - Load the dataset.
   - Handle missing or corrupted data.
   - Encode categorical variables and scale numerical features.
   
2. **Feature Engineering**:
   - Extract meaningful features from sensor data (e.g., rolling averages, trend analysis).
   
3. **Model Building**:
   - Train machine learning models (Random Forest, XGBoost) for classification.
   - Train an LSTM model to handle sequential sensor data and predict failure.

4. **Evaluation**:
   - Evaluate model performance using accuracy and feature importance metrics.
   - Visualize trends and model predictions using `Matplotlib`.

5. **Deployment Potential**:
   - Integrate this system into real-time predictive maintenance applications for industries like manufacturing, aviation, and energy.


##  **Dependencies**
**Python 3.x**

**Pandas**

**numpy**

**scikit-learn**

**xgboost**

**tensorflow**

**keras**

**matplotlib**

**plotly (for advanced visualization)**

## **Results**
- The models predict equipment failures based on sensor data, reducing downtime and enhancing operational efficiency.
- **Accuracy**: The performance of the models is evaluated using accuracy scores.
- **Feature Importance**: Identifying which sensor readings most significantly impact predictions.

## **Contributing**
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Contact**
- **Author**: Santhosh S
- **Email**: santhoshs25042006@gmail.com
