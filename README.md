**#Customer Segmentation using Unsupervised Learning**


![Segmentatie](https://github.com/user-attachments/assets/db19c3ee-3c1f-4ec0-8358-552c95e84791)

☀️ Objective
This project utilizes unsupervised learning techniques to segment customers based on their purchasing behavior. By grouping customers with similar characteristics together, businesses can tailor their marketing strategies and offerings to specific customer segments, thereby maximizing customer satisfaction and profitability.


☀️What is Customer Segmentation?

Customer segmentation is the practice of categorizing customers into distinct groups based on shared characteristics, enabling companies to target and tailor their marketing strategies to each group effectively. Customers are typically segmented based on their similarities in behavior, preferences, and purchasing habits.

☀️Introduction:

The main task of Clustering is to identify natural groups within an unlabeled dataset. This means that clustering is an Unsupervised Machine Learning task, which is important in many scientific, engineering, and business domains. Some well-known applications of clustering include:

Customer segmentation for efficient marketing

Image segmentation for computer vision

Document clustering for information retrieval


☀️Feature Description

RFM is one of the most widely used methods to perform customer segmentation due to its simplicity and availability. On top of that, the report takes other behavrioul data into consideration to better identify customer groups.

Recency:The count of days since the individual’s last transaction. The feature was generated from “purchase_date” of the dataset. The count of the days between the last purchase date and the snapshot date.

Frequency: The count of times an individual has purchased from the brand in the six months.

Monetary: Ths sum of an individual's transaction amount.

Length: The duration between one's first and last transaction date. It provides further information on the stage of customer journey. eg. new comers may have lower length but it's worth observing its monetary and frequency values.

Average spend per shop: The average amount of one's spend per transaction.

Count of unique product id: The count of unique product an individual has bought.

![233505817-18d55dee-2a30-43b7-aa69-b1c3fa59a329](https://github.com/user-attachments/assets/e61be053-b5e5-4708-8ade-715482084822)



☀️Dependencies

Python (>= 3.6)

scikit-learn

pandas

numpy

matplotlib (optional for visualization)


