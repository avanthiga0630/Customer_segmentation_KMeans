# Customer Segmentation Using K-Means Clustering

## 1. Project Overview
This project uses Machine Learning to group mall customers
based on their annual income and spending score.

The K-Means clustering algorithm identifies different
customer groups to help businesses understand customer
behaviour and improve marketing strategies.

## 2. Problem Statement
Businesses need to understand customer spending patterns
to develop effective marketing strategies.

This project segments customers based on their annual
income and spending score.

## 3. Dataset
- Dataset: Mall Customers Dataset
- Number of records: 200
- Features used:
  - Annual Income (k$)
  - Spending Score (1-100)

## 4. Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- Machine Learning

## 5. Methodology
1. Loaded and explored the dataset.
2. Checked for missing values and duplicate records.
3. Selected annual income and spending score.
4. Visualized customer data using a scatter plot.
5. Used the Elbow Method to select the number of clusters.
6. Applied K-Means clustering.
7. Visualized the customer segments.
8. Analysed the number of customers in each cluster.
9. Exported the results to a CSV file.
    
## 6. Results and Business Insights

  The K-Means clustering algorithm segmented 200 mall customers into four groups based on annual income and spending score.

### Customer Segment Distribution

  | Customer Segment            | Number of Customers | Percentage |
  | --------------------------- | ------------------: | ---------: |
  | Low Income - High Spending  |                  52 |        26% |
  | High Income - Low Spending  |                  50 |        25% |
  | High Income - High Spending |                  50 |        25% |
  | Low Income - Low Spending   |                  48 |        24% |

### Key Business Insights

  1. **Low Income - High Spending:** Consider testing affordable loyalty rewards and personalized offers.
  2. **High Income - Low Spending:** Investigate potential barriers to spending and test targeted promotions.
  3. **High Income - High Spending:** Consider premium product recommendations and personalized customer experiences.
  4. **Low Income - Low Spending:** Explore budget-friendly products and value-based promotions.

### Conclusion

  The segmentation results show four customer groups with relatively balanced sizes. These segments can help businesses design targeted marketing strategies. The proposed strategies should   be tested against actual purchasing data before implementation.


## 7. Project Files
- Customer_Segmentation.ipynb: Jupyter Notebook containing
  the project code and analysis.
- Customer_Segmentation_Results.csv: Dataset containing
  the customer segmentation results.

## 8. How to Run
1. Download the project notebook.
2. Open Google Colab.
3. Upload the notebook and dataset.
4. Run the notebook cells sequentially.

## 9. Conclusion
This project demonstrates how K-Means clustering can
be used to segment mall customers and understand
their spending behaviour.
