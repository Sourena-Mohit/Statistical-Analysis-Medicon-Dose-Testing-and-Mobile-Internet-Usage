# Statistical Analysis: Medicon Dose Testing & Mobile Internet Usage

This repository contains two case studies focused on statistical analysis using inferential statistics and hypothesis testing. Each case study presents a unique business problem, with corresponding questions that require analysis to derive actionable insights.

---

## Case Study 1: Medicon Dose Testing

### Context

Medicon, a pharmaceutical company, has produced a sixth batch of 40,000 COVID-19 vaccine doses. Previous clinical trials have been successful, with 200,000 doses administered across five batches. The company now seeks to evaluate the **quality and effectiveness** of the sixth batch by testing a sample of the doses on volunteers.

This analysis focuses on understanding:
- The probability of unsatisfactory doses.
- The time taken for the vaccine to take full effect.

### Objective

To assess the quality and effectiveness of the sixth batch of doses and provide insights for planning future batches.

### Key Questions

1. **Probability of Unsatisfactory Doses (100 Volunteers Sample)**
   - What is the probability distribution for unsatisfactory doses?
   - What is the probability that exactly 3 doses will not be satisfactory?
   - What is the probability that at most 3 doses will not be satisfactory out of 100?

2. **NYC Doses Request (200 Doses Sample)**
   - What is the probability that at least 30 doses will not be satisfactory out of 200 doses?

3. **Time of Effect (50 Volunteers Sample)**
   - What is the probability that the time of effect is less than 11.5 hours?
   - What is the 90th percentile of the time of effect?
   - Estimate the range that will contain the population mean time of effect with 95% confidence.

### Data

- The dataset used for the analysis includes details about the **time of effect** for 50 doses, provided in the `doses.csv` file.
- Key variables in the dataset:
  - `pickup_dt`: Date and time of the pickup.
  - `borough`: NYC's borough (e.g., Manhattan, Brooklyn, etc.).
  - `pickups`: Number of pickups for the period.
  - `spd`: Wind speed (miles/hour).
  - `vsb`: Visibility (miles).
  - `temp`: Temperature (Fahrenheit).
  - `dewp`: Dew point temperature (Fahrenheit).
  - `slp`: Sea level pressure.
  - `pcp01`: 1-hour liquid precipitation.
  - `pcp06`: 6-hour liquid precipitation.
  - `pcp24`: 24-hour liquid precipitation.
  - `sd`: Snow depth (inches).
  - `hday`: Is it a holiday (Y/N)?

---

## Case Study 2: Mobile Internet Usage Analysis

### Context

**ExperienceMyServices** reported that the average American spends **144 minutes** per day accessing the Internet via a mobile device, with a standard deviation of **110 minutes**. You have collected data from 30 samples to validate this claim.

### Objective

To determine if there is enough statistical evidence to conclude that the population mean time spent on mobile Internet is **different** from 144 minutes.

### Key Question

**Is there enough statistical evidence to conclude that the population mean time spent per day accessing the Internet via mobile devices differs from 144 minutes?**

- **Hypothesis Test**: Use the p-value approach with a significance level of 0.05.

### Data

- The dataset `InternetMobileTime.csv` contains the time (in minutes) that 30 people spent accessing the Internet via mobile devices.

### Statistical Approach

- **Null Hypothesis (H₀)**: The population mean time spent per day accessing the Internet via a mobile device is 144 minutes.
- **Alternative Hypothesis (H₁)**: The population mean time spent per day accessing the Internet via a mobile device is different from 144 minutes.

---

## Project Workflow

1. **Data Exploration**: 
   - Perform **univariate** and **bivariate** analysis to explore the variables and their relationships.
   - Use **visualizations** (e.g., histograms, box plots, scatter plots) to understand data distributions and relationships.

2. **Statistical Analysis**:
   - For Case Study 1, calculate probabilities using binomial distributions and confidence intervals.
   - For Case Study 2, conduct hypothesis testing using the p-value approach.

3. **Results and Interpretation**:
   - Summarize findings for each case study, highlighting key insights that can help Medicon and guide mobile Internet usage assumptions.
   - Provide recommendations for actionable business decisions based on the statistical analysis.

---

## Files in This Repository

- `doses.csv`: Dataset for the **Medicon Dose Testing** case study, containing time-of-effect data.
- `InternetMobileTime.csv`: Dataset for the **Mobile Internet Usage Analysis** case study, containing sample data on mobile Internet usage times.
- `README.md`: Project documentation (this file).

---

## Conclusion

This repository showcases the use of statistical methods, including **inferential statistics** and **hypothesis testing**, to solve real-world business problems. By analyzing the quality and effectiveness of Medicon's vaccine doses and evaluating mobile Internet usage, we derive actionable insights to inform decision-making.

---

## Author

Sourena Mohit Tabatabaie , 
from MIT applied Data Science program   

---

## License

This project is licensed under the [MIT License](LICENSE).

---

### How to Use This Repository

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sourena-Mohit/Statistical-Analysis-Medicon-Dose-Testing-and-Mobile-Internet-Usage
