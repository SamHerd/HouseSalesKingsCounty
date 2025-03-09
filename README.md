```markdown
# House Sales in King County, USA

This project analyzes house sales data in King County, USA, to explore the factors influencing house prices and develop predictive models to estimate future house prices. The project covers data wrangling, exploratory data analysis, and machine learning model development.

---

## Project Overview
The goal of this project is to identify key factors that influence house prices in King County and build a predictive model to estimate future house prices. The project involves cleaning and preprocessing the data, exploring relationships between features, and developing regression models to make accurate price predictions.

---

## Dataset Overview
The dataset contains information on house sales in King County, USA. Key features include:

- `price` – Sale price of the house  
- `bedrooms` – Number of bedrooms  
- `bathrooms` – Number of bathrooms  
- `sqft_living` – Size of living space (square feet)  
- `sqft_lot` – Lot size (square feet)  
- `floors` – Number of floors  
- `waterfront` – Binary indicator for waterfront property  
- `view` – Quality of the view from the house  
- `condition` – Condition rating  
- `grade` – Overall building grade  
- `sqft_above` – Square footage of house apart from basement  
- `sqft_basement` – Square footage of the basement  
- `yr_built` – Year built  
- `yr_renovated` – Year of renovation  
- `zipcode` – Property location (postal code)  
- `lat` – Latitude coordinate  
- `long` – Longitude coordinate  
- `sqft_living15` – Living room area of the nearest 15 neighbors  
- `sqft_lot15` – Lot size of the nearest 15 neighbors  

---

## Key Insights
- The size of the house (`sqft_living`) is the strongest predictor of price.  
- Houses with a waterfront view have significantly higher prices.  
- Condition and grade of the house also strongly affect the sale price.  
- Higher correlation between square footage and price than other factors.  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## Required Libraries
Make sure the following libraries are installed before running the project:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/SamHerd/house-sales-analysis.git
```
2. Navigate to the project directory:
```bash
cd house-sales-analysis
```
3. Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
4. Open Jupyter Notebook:
```bash
jupyter notebook House_Sales_in_King_Count_USA.ipynb
```

---

## Next Steps
- Explore additional features to improve model accuracy.  
- Test other machine learning models like decision trees and gradient boosting.  
- Automate data cleaning and preprocessing for scalability.  

---

## Connect with Me
If you found this project helpful or have any questions, feel free to reach out:

- **LinkedIn:** [linkedin.com/in/samherd](https://www.linkedin.com/in/samherd)  
- **GitHub:** [github.com/SamHerd](https://github.com/SamHerd)  
```
