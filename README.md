# EDM Cutting Parameter Prediction

A production-oriented machine learning system for predicting optimal Electrical Discharge Machining (EDM) parameters from historical manufacturing data. This project demonstrates how data science can replace manual trial-and-error with intelligent, data-driven decision-making in industrial environments.

---

## Project Highlights

- Designed a data-driven system to predict EDM cutting parameters using real production data  
- Reduced reliance on operator experience through automated parameter recommendation  
- Built an end-to-end ML pipeline including preprocessing, feature engineering, and model evaluation  
- Applied regression-based models to capture relationships between machining inputs and outputs  
- Demonstrates real-world industrial AI application aligned with smart manufacturing  

---

## Problem Statement

In EDM machining, selecting optimal parameters such as current, voltage, and pulse duration is critical for machining quality and efficiency.  

Traditional approaches depend heavily on operator expertise, leading to:
- Inconsistent results  
- Time-consuming manual tuning  
- Suboptimal machine performance  

This project addresses these challenges by learning patterns from historical data and predicting optimal parameters automatically.

---

## Solution Approach

### Data Pipeline
- Cleaned and processed raw machining data  
- Handled missing values and inconsistencies  
- Performed normalization and feature scaling  

### Feature Engineering
- Extracted meaningful machining features  
- Transformed categorical and numerical inputs  
- Improved model learning through structured input representation  

### Model Development
- Implemented regression-based machine learning models  
- Tuned hyperparameters for improved performance  
- Evaluated models using standard metrics (R², RMSE)  

### Prediction System
- Generates optimal EDM parameter recommendations  
- Supports decision-making for engineers and operators  

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Project Structure

```
EDM-Cutting-Parameter-Prediction/
│
├── MA_Auto_Paramaters_v5.ipynb   # Full ML pipeline implementation
├── README.md                     # Documentation
```

---

## Results & Impact

- Improved prediction accuracy for machining parameters  
- Reduced dependency on manual parameter tuning  
- Increased consistency and repeatability in EDM operations  
- Demonstrates feasibility of AI-driven industrial automation  

*(You can strengthen this by adding actual metrics like R² or RMSE from your notebook.)*

---

## Real-World Relevance

This project reflects practical experience in industrial data science and connects directly to manufacturing environments such as:

- EDM machine optimization  
- Smart factory systems  
- Predictive process control  
- AI-driven production decision systems  

---

## Future Improvements

- Integrate real-time sensor and machine data  
- Deploy as a web-based or API service  
- Apply advanced models (XGBoost, Neural Networks)  
- Build automated model selection (AutoML)  
- Connect with IoT-based smart manufacturing systems  

---

## Author

**Sarah Wai (Wai Phu Paing)**  
Data Science | Machine Learning | AI  

---

## License

This project is licensed under the MIT License.
