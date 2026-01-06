# Descriptive Statistics

### Mean (Average)

Mean kya hota hai?
    - Sab values ka sum / total number of values

Data Science use:
    - Mean outliers se bahut zyada affect hota hai


### Median (Middle Value)

Median kya hota hai?
    - Sorted data ka beech ka value

Rules:
    - Odd count → middle value
    - Even count → middle ke do values ka average

Data Science use:
    - Median outliers se affect nahi hota

### Mode (Most Frequent Value)


Mode kya hota hai?
    - Jo value sabse zyada baar repeat hoti hai

Data Science use:
    - Categorical data ke liye best


| Measure | Outlier Effect | Best Use Case       |
| ------- | -------------- | ------------------- |
| Mean    | High           | Normal distribution |
| Median  | Low            | Skewed data         |
| Mode    | None           | Categorical data    |

### Variance

Variance kya hota hai?
    - Har value mean se kitni door hai, uska average squared distance

Problem with Variance:
    - Unit square ho jata hai
    - Data rupees mein ho to variance rupees²
    - Isliye directly interpret karna mushkil


### Standard Deviation (STD)

Standard Deviation kya hota hai?
    - Variance ka square root

Intuition (Bahut Important)

Low Standard Deviation:
    - Data points mean ke paas
    - Example: exam marks 48, 49, 50, 51

High Standard Deviation:
    - Data zyada spread
    - Example: marks 10, 30, 70, 95


Real-Life Data Science Examples
Salary Data:
    - Mean salary = 50k
    - STD = 2k → sab log almost same earn kar rahe
    - STD = 40k → huge inequality

Population vs Sample (Interview Favorite)
Population:
    - np.var(data)
    - np.std(data)

Sample (zyada common in DS):
    - np.var(data, ddof=1)
    - np.std(data, ddof=1)

