# Exploratory-Analysis-of-FMCG-Daily-Sales-Data-2022-2024-
Exploratory data analysis and machine learning on a Kaggle dataset. 
Includes visualizations to answer research questions about sales and profitability trends, as well as applications of Decision Tree and Random Forest models. 
Kaggle Dataset Link: https://www.kaggle.com/datasets/beatafaron/fmcg-daily-sales-data-to-2022-2024


### Research Questions

* How are products distributed across channels?
* Which region generates the most profit?
* To what extent do promotions affect sales volume?
* What is the market share or revenue of different SKUs and segments (over time)?
* How does revenue of different segments change over time?
* How does sales volume change over time?
* How do product prices change over time?
* How does the demand–supply balance change over time?

---

### Questions and Answers

1. **How are products distributed across channels?**
   From the pie chart, it can be seen that products are sold almost equally across all three channels (E-commerce, Retail, and Discount).

2. **Which region generates the most profit?**
   The chart shows that profits across the regions are approximately equal.

3. **To what extent do promotions affect sales volume?**
   The graph clearly shows that promotions more than double the sales volume.

4. **What is the market share or revenue of different SKUs and segments (over time)?**
   Products from the yogurt segment hold about 41% of the market share. The most profitable product is **YO-029** (4.6%), while the least profitable product is **MI-008** (2.1%).

5. **How does revenue of different segments change over time?**
   The graph shows a significant increase in revenue during summer months for products such as *Juice-Seg3, Milk-Seg1,* and *Milk-Seg2*, while *Yogurt-Seg3* shows only a slight increase.

6. **How does sales volume change over time?**
   Since there are many products, the graph is somewhat cluttered. However, it can be observed that beverage sales increase in the summer, while ready meal sales decrease.

7. **How do product prices change over time?**
   Product prices tend to fluctuate in a sinusoidal pattern over time. This may be due to periodic discount campaigns.

8. **How does the demand–supply balance change over time?**
   It can be said that the demand–supply balance has been maintained. As seen in the previous graph, the overall demand–supply ratio increases slightly in the summer. In general, the changes and fluctuations are not strong, and the balance is largely preserved.

---

### ML Approach

I approached the data using supervised learning models to predict **Promotion Flag** and **Units Sold**.

* From feature importance analysis, the main factor affecting **Units Sold** is *stock availability*, followed by *promotion flag*.
* Promotion flag, as expected, depends on stock availability.
* For the **Promotion Flag Classifier**, the **F1 score** is approximately **0.71**.
* For the **Units Sold regression**, the **R² score** is **0.77**.
* These values could be further improved by hyperparameter tuning.

Depending on the problem setup, other analyses could also be carried out, and unsupervised learning approaches may be applicable as well.



Do you also want me to polish this into a **formal report-style narrative** (instead of Q\&A), so it reads like a research/analysis summary?
