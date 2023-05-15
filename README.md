# Ecomm-linear-regrssion

# ****Problem Statement -****

> **Let's imagine - I have just landed a contract with an ecommerce company based in New York City that sells clothing online, but also offers in-store style and clothing advice sessions. Customers come to the store for sessions with a personal stylist, and can then order the clothes they want using a mobile app or website from the comfort of their own home.**
> 

---

## ****Stakeholder - Senior Product Manager****

# ****Get the Data****

> I will be working with the Ecommerce Customers Excel file from the company. The file contains customer information such as email, address, and their color avatar. It also includes several numerical value columns:
> 
> - **Avg. Session Length: The average duration of in-store style advice sessions**
> - **Time on App: The average time spent on the app in minutes**
> - **Time on Website: The average time spent on the website in minutes**
> - **Length of Membership: The number of years the customer has been a member**

---

# Steps -

- ****Import libraries****
- ****Read in the Ecommerce Customers excel file as a Data Frame called data.****
- ****Check the head of data, and check out its info() and describe() methods.****
- ****Exploratory Data Analysis****
- ****Training and Testing Data****
- ****Training the Model****
- ****Predicting Test Data****
- ****Calculating metrics of linear regression****
- **Comparing** ****Residuals****

---

# Important Insights - 
****

- The length of membership appears to be highly correlated with the yearly amount spent.
- There is a strong linear relationship between the length of membership and yearly amount spent.
- The X variable contains columns for 'Avg. Session Length', 'Time on App', 'Time on Website', and 'Length of Membership'.
- The y variable contains 'Yearly Amount Spent'.
- A good model was developed with a good fit, and the distribution of data was checked and found to be uniform.
- The coefficients of each variable were interpreted to determine whether the company should focus on mobile app or website development.

|  | Coefficient |
| --- | --- |
| Avg. Session Length | 25.981550 |
| Time on App | 38.590159 |
| Time on Website | 0.190405 |
| Length of Membership | 61.279097 |

## **The greater the value, the more related it is to the target variable, which in this case is Yearly Amount Spent.**

**These numbers indicate that holding all other features constant, a 1 unit increase in Avg. Session Length results in a $25.981550 increase in Yearly Amount Spent, and the same applies to the other features.**

**Since Time on App is a much more significant factor than Time on Website, the company has a choice: they could either focus all their attention on the App, which is bringing in most of the money, or they could concentrate on improving the Website, which is underperforming.**

# ****The company should focus on the mobile app!****

# Visualizations -

Seaborn joint plot - 

![download.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/739ebfd8-f6a9-4eec-8c08-ee90387bd106/download.png)

Seaborn hex joint plot - 

![download.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b9d122a3-36dd-4016-bdb6-9eb54464cf91/download.png)

Seaborn heatmap - 

![download.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10bad1df-0895-46f5-a319-81839155af5a/download.png)

Seaborn linear model plot - 

![download.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3277f8b4-3138-46f7-99a6-4ccd213d61d7/download.png)

Seaborn residual distribution plot - 

![download.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/922559bf-5963-483e-a0d8-8933f881c4ff/download.png)

Comparison of all features of the dataset
