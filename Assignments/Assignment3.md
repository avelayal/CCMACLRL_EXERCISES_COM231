# Assignment 3: 

## Predicting Customer Purchase using Logistic Regression 
An online store wants to predict whether a visitor will **purchase a product $(y = 1)$** or **leave without buying $(y = 0)$**.  


We collect two features about each customer:

- $x_1$ = Time spent browsing the website (minutes)
- $x_2$ = Number of product pages viewed
- $y$ = Purchase outcome (1 = purchase, 0 = no purchase)

We need to use **logistic regression** to model the probability of purchase:

$$
\hat{y} = \sigma(w_1 x_1 + w_2 x_2 + b)
$$

where 

$$
\sigma(z) = \frac{1}{1+e^{-z}}
$$

---

## Dataset

| Customer | Time on site (x₁) | Pages viewed (x₂) | Purchase (y) |
|----------|-------------------:|------------------:|-------------:|
| A        | 1                  | 4                 | 0            |
| B        | 2                  | 3                 | 0            |
| C        | 3                  | 7                 | 1            |
| D        | 5                  | 2                 | 1            |
| E        | 6                  | 6                 | 1            |

Initial model parameters:
- $m_1 = 0.8$
- $m_2 = 0.4$  
- $b = -4.0$

---

## Tasks

### 1. Compute Probabilities (5 points)
![1](https://github.com/user-attachments/assets/c520e524-6a8e-48c9-ba40-4454a62bf5c1)

### 2. Compute Average Loss (6 points)
![2](https://github.com/user-attachments/assets/6001a5c6-5eb9-491c-b010-f4bfb9aa7431)

###3. Update the slope and intercept using Gradient Descent (6 points)
![3](https://github.com/user-attachments/assets/ee7fe80a-331e-496f-b91c-525c1af2f861)

### 4. Compute new probabilities using the new slopes and intercept (5 points)
![4](https://github.com/user-attachments/assets/6337ca2c-ad35-46d6-ab46-671331e47347)

### 5. Compute new Average Loss (6 points)
![5](https://github.com/user-attachments/assets/41cceb30-6f45-4d6a-ba88-44c7fa644c80)


