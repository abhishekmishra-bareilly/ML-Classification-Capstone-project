# ML-Classification-Capstone-project
ML Classification Capstone project
## **EDA Conclusion**
* We found there are **95919** values are listed as **0**. Using some **google search** we found that **0**  meaning the **payment wasn't due**, which makes sense that most customers were using the revolving credit.
* Also we found **24415** values as **-2** which means **No consumption**.

* There are no **duplicate** IDs or rows.

* **30%** male have **default** payment while **26%** female have **defaul** payment, the difference is not significant.

* Also we can see **Female** have more **count** than **male**
* **'EDUCATION'** column: notice **5** and **6** are both recorded as **'unknown'** and there is 0 which isn't explained in the dataset description. 

* Since the amounts are so small, let's combine **0,4,5,6** to **0** which means**"other**'.

* **'MARRIAGE'** column: what does **0** mean in **'MARRIAGE'**? Since there are only  54 observations of 0, 

* we will combine **0** and **3** in one value as **'others'**.
* There was a huge jump from **May 2005**  to **July 2005** 

* when delayed payment increased significantly, then it peaked at **August 2005**.

* Things started to get better in **September, 2005** .

* Unsurprisingly, customers who had **higher credit** limits had **lower delayed** payment rates.
