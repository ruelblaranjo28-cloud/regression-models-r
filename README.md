📊 Regression Models Project

👤 Author

Ruel Barredo Laranjo

Aspiring Data Scientist

---

📌 Project Overview

This project analyzes whether transmission type (manual vs automatic) has a significant impact on fuel efficiency (miles per gallon, MPG).

Using the mtcars dataset, linear regression models are applied to:

- Determine if transmission type affects MPG
- Quantify the MPG difference between manual and automatic cars
- Evaluate the influence of other variables such as weight and horsepower

---

❓ Key Question

Does transmission type (manual vs automatic) significantly affect fuel efficiency (MPG)?

---

## 📈 Key Results
- Manual cars tend to have higher MPG than automatic cars
- Weight and horsepower significantly affect fuel efficiency
- The effect of transmission decreases when other variables are considered

---

📊 Data Exploration

The dataset includes variables such as:

- MPG (fuel efficiency)
- Number of cylinders
- Horsepower (hp)
- Weight (wt)
- Transmission type (am)

Initial exploration shows variation in MPG across different car characteristics.

---

📈 Regression Analysis

Model 1: MPG vs Transmission

A simple linear regression model was used to assess the effect of transmission type on MPG.

👉 Result:
Manual cars tend to have higher MPG than automatic cars.

---

Model 2: Adjusted Model (MPG vs Transmission + Weight + Horsepower)

A multiple regression model was used to control for additional variables.

👉 Result:

- Weight and horsepower significantly influence MPG
- The effect of transmission becomes less pronounced after adjustment

---

🔢 Key Results

- Manual cars show higher average MPG than automatic cars
- The regression coefficient for transmission (am) is positive
- After adjusting for weight and horsepower, the transmission effect decreases
- Weight and horsepower are strong predictors of fuel efficiency

---

📉 Model Diagnostics

Residual plots indicate:

- No strong systematic patterns (linearity assumption satisfied)
- Residuals are approximately normally distributed
- No major violations of regression assumptions

---

🧠 Key Insights

- Manual transmission vehicles generally have higher fuel efficiency
- Vehicle weight and horsepower strongly influence MPG
- Including multiple variables improves model accuracy and interpretation

---

💼 Business Insight

The analysis suggests that fuel efficiency is not determined by transmission type alone.
Vehicle characteristics such as weight and horsepower play a significant role.

This insight can help manufacturers and consumers focus on overall vehicle design rather than relying solely on transmission type when evaluating fuel efficiency.

---

✅ Conclusion

This analysis shows that transmission type has an impact on fuel efficiency, with manual vehicles generally achieving higher MPG.

However, the results also highlight that other factors—such as weight and horsepower—play a significant role. When these variables are included, the difference between transmission types becomes smaller.

Overall, this project demonstrates the importance of using multiple variables in regression analysis to obtain more reliable and meaningful insights.

---

📂 Dataset Source

The dataset used in this project is the built-in mtcars dataset in R.
It contains data on fuel consumption and automobile design characteristics for 32 cars from the 1970s.

---

🛠 Tools Used

- R
- R Markdown
- Linear Regression
- Data Visualization

---
