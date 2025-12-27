## RESTAURANT TIPS ANALYSIS
![](https://github.com/nheesele/restaurant_tips_analysis/blob/main/RESTAURANT.jpg)
> Source: Pinterest

This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. Then examine the relationship between different variables and the tips given. 

The dataset consists of information from 244 restaurant bills, collected in the US in 1987. It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.

## Data Souce:

The dataset is sourced from a sample dataset, which is included for educational and demonstration purposes.
You can import the dataset through `Pandas` as below:

```sql
import pandas as pd
df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```

## Data Structure

The dataset is a Pandas DataFrame. A sample of key variables include:

| id | total_bill | tip | sex    | smoker | day | time   | size |
|----|------------|-----|--------|--------|-----|--------|------|
| 0  | 16.99      | 1.01| Female | No     | Sun | Dinner | 2    |
| 1  | 10.34      | 1.66| Male   | No     | Sun | Dinner | 3    |
| 2  | 21.01      | 3.50| Male   | No     | Sun | Dinner | 3    |
| 3  | 23.68      | 3.31| Male   | No     | Sun | Dinner | 2    |
| 4  | 24.59      | 3.61| Female | No     | Sun | Dinner | 4    |

in which:
- `total_bill`: The total amount of the bill (in USD).
- `tip`: The tip amount left by the customer (in USD).
- `sex`: Gender of the bill payer (Male/Female).
- `smoker`: Whether the customers are smokers or non-smokers (Yes/No).
- `day`: Day of the week.
- `time`: Eating time of day (Lunch/Dinner).
- `size`: Number of people in the party.

## Results

The process to clean and examine the datasets is performed in the link below:
```sql
https://github.com/nheesele/restaurant_tips_analysis/blob/main/Restaurant_tips_analysis.ipynb
```

**Author:** Nhi Le
