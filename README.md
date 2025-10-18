# Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning-

## Background 
A company can experience significant growth when it understands the behavior and personality of its customers. This understanding enables the company to provide better services and greater value to potential loyal customers. By processing historical marketing campaign data, the company can enhance its performance and effectively target the right customers to increase transactions on its platform. Based on these data insights, the focus of this project is to develop a predictive clustering model that helps the company make more informed and strategic business decisions.

This project was conducted as part of a mini project at Rakamin Academy, aiming to apply data analysis and machine learning techniques to real business scenarios.

## Goals
The goal of this project is to utilize customer and campaign data to develop insights that strengthen business strategies. More specifically, the aim is to build a predictive clustering model that enables the company to identify, segment, and engage customers more effectively.

## Objectives
- Analyze historical marketing campaign data to uncover key customer patterns.
- Identify and group customers with high potential for loyalty and engagement.
- Develop a predictive clustering model to improve customer targeting.
- Provide data-driven insights that support strategic decision-making and boost company performance.

## Workflow Project
<img width="428" height="709" alt="image" src="https://github.com/user-attachments/assets/58a0b153-74ce-4a55-8306-cc1985fa2460" />

## Exploratory Data Analysis
<img width="721" height="396" alt="image" src="https://github.com/user-attachments/assets/0c09213a-ae80-443c-80c6-63db241c329c" />

- Customers with an income of 80–120 million IDR show the highest conversion rate (around 18–19%), significantly outperforming lower-income groups (<20 million IDR with ~10%). This suggests that upper-middle-income customers are more likely to convert compared to lower or higher extremes.

<img width="704" height="426" alt="image" src="https://github.com/user-attachments/assets/dffdd558-9d69-4daa-afc2-55f61f4cc9df" />

- Conversion rate strongly increases with spending categories. Customers in the “Very High” spending group (Q4) have a conversion rate of over 12%, which is far higher than the lower spending groups (<3%). This indicates that high-spending customers are the most valuable segment for driving conversions.

<img width="719" height="422" alt="image" src="https://github.com/user-attachments/assets/91b7ab99-dbdd-4943-b8fd-ed897cb9f591" />

- The 30–50 years group shows the highest conversion rate (5.2%), making it the most promising segment.
- The >70 years group also performs strongly (5%), indicating a significant opportunity in the senior segment.
- The 50–70 years group has the lowest rate (3.6%), which may require tailored marketing approaches to boost conversions.
- The <30 years group is moderate (4%), showing potential but not as high as older groups.

<img width="646" height="424" alt="image" src="https://github.com/user-attachments/assets/f79760b3-5b4e-416b-8056-b0b1142792e8" />

- Single and “Other” categories record the highest conversion rates (~19–20%), far above engaged (~10.5%) and married (~11%). This may indicate that single individuals or those outside traditional marital categories are more receptive to conversions compared to people in stable family commitments.

## Data Modeling
### Elbow Method
<img width="697" height="425" alt="image" src="https://github.com/user-attachments/assets/889654da-9e80-4be8-b7e0-b369763e52b6" />

- A sharp drop occurs between K=1 to K=3, meaning adding clusters at this stage significantly improves clustering quality.
- Between K=4 to K=6, the curve still decreases but at a slower rate.
- From K=7 onward, the curve flattens, showing diminishing returns when adding more clusters.
- The “elbow point” appears around K=4

### Silouette Analysis
<img width="703" height="540" alt="image" src="https://github.com/user-attachments/assets/fb37e664-98f3-4dc8-9bd2-40a02fe5a11c" />

- Good clustering quality – The average silhouette score of 0.576 indicates that the clusters are moderately strong, well-separated, and meaningful.
- Cluster consistency – Most clusters (blue, green, yellow) show consistently high silhouette values, while Cluster 0 (black) has some lower values, suggesting a few borderline points.
- K=4 is reasonable – The results suggest that using 4 clusters provides a solid structure, though testing nearby values of K (e.g., 3 or 5) could further confirm the optimal number.

### Cluster Graph 2D
<img width="659" height="470" alt="image" src="https://github.com/user-attachments/assets/e8b5c373-dcb5-41cb-ac6b-f75eae3fa9c9" />

- Clear separation of clusters – The four clusters (brown, red, gray, purple) are well-separated along the first principal component (x-axis), suggesting that the data is effectively partitioned into distinct groups.
- Balanced distribution – Each cluster has a relatively similar size and density, indicating that K=4 provides a balanced segmentation without one cluster dominating the others.
- Centroids as representative points – The yellow X marks show the centroids of each cluster, which are positioned centrally within their groups. This means the centroids are good representatives of each cluster’s characteristics.

## EDA After Clustering

<img width="1445" height="282" alt="image" src="https://github.com/user-attachments/assets/735b1dcb-5973-4245-9ba3-7aadea2957a3" />

<img width="1436" height="395" alt="image" src="https://github.com/user-attachments/assets/2bbd1a53-8e3d-4286-a7a0-8a88d856981d" />

<img width="1445" height="300" alt="image" src="https://github.com/user-attachments/assets/25ee3624-5c25-40d1-85ad-e64282ce6072" />

## Business Recommendations
<img width="1528" height="694" alt="image" src="https://github.com/user-attachments/assets/fd843bcf-ef49-4b62-9d9a-5d7046cb45fe" />








