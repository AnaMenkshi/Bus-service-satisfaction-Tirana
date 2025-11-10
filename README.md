# 🚌 Assessment of Customer Satisfaction of Bus Services in Tirana

This project explores and models factors that influence **customer satisfaction** with **urban bus services in Tirana, Albania**.  
It uses survey data collected from passengers to understand perceptions about cleanliness, safety, bus conditions, waiting times, and more.

---

##  Objectives
- Analyze survey responses about public transport satisfaction  
- Identify key variables affecting satisfaction  
- Build and evaluate a **linear regression model** to predict overall satisfaction  
- Visualize correlations and trends between service factors and satisfaction  

---

##  Key Variables

| Category | Example Variables |
|-----------|-------------------|
| **Demographics** | Gender, Age Group |
| **Bus Stops** | Cleanliness, Information, Safety |
| **Bus Interior** | Temperature, Crowdedness, Cleanliness |
| **Service** | Waiting Time, Travel Time, Driver Helpfulness |
| **Satisfaction** | General satisfaction rating (0–10) |

---

##  Tools and Libraries

- **Python 3.9+**
- **Pandas** – data handling  
- **NumPy** – numerical operations  
- **Matplotlib / Seaborn** – visualizations  
- **Scikit-learn** – regression modeling and evaluation  

---

##  Project Structure

```
BUS.ipynb              → Data analysis and regression modeling notebook
css.csv                → Dataset with customer survey responses
results/               → Visual outputs and model results

⚠️ Note: The file css.csv contains confidential survey data collected for research purposes and is not publicly available.
For demonstration, only code and analysis structure are provided.
```

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/bus-service-satisfaction-tirana.git
   cd bus-service-satisfaction-tirana
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook BUS.ipynb
   ```

---

##  Results Summary

- The regression model predicts **general satisfaction** based on cleanliness, waiting time, and bus condition.  
- **Most influential factors:** bus cleanliness, travel time, and driver helpfulness.  
- The project provides visual insights into which aspects passengers value most.

---



##  Future Improvements

- Add more advanced models (Random Forest, XGBoost)  
- Include geospatial analysis of bus stations  
- Automate data collection for real-time satisfaction tracking  

---

##  Author

**Ana Menkshi**  

---

## License

MIT License
