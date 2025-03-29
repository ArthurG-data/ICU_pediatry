# **Evaluating Pediatric ICU Accessibility in Queensland**

## **Project Overview**
This project investigates disparities in pediatric emergency healthcare performance across Queensland. By leveraging **unsupervised machine learning**, we aim to identify meaningful hospital groupings, analyze performance differences, and evaluate the effectiveness of resource allocation in emergency care settings.

## **Research Questions**
1. **Meaningful Groupings**: Identify and categorize hospitals based on patient load, treatment times, and accessibility.
2. **Performance Analysis**: Compare key healthcare metrics among these groups.
3. **Significance Testing**: Examine how treatment prioritization affects critically ill patients.

## **Key Findings**
- **Hospital Clusters**: 95 hospitals grouped into three clusters:
  - **Large hospitals (10 total)**: High admission rates (20.8%) and effective resource management.
  - **Mid-sized hospitals (20 total)**: Longer waiting times (23.4 min median) and higher patient dropout rates (5.7%).
  - **Small/remote hospitals (65 total)**: Short waiting times (3.2 min median) and high treatment efficiency (97.4% treated within time).
- **Treatment of Life-Threatening Cases**:
  - Remote hospitals excelled in treating emergency cases within the recommended timeframe.
  - Major city hospitals faced challenges managing patient demand.
- **Resource Allocation Insights**:
  - Large hospitals effectively managed demand due to adequate staffing and infrastructure.
  - Mid-sized hospitals showed signs of strain, suggesting a need for targeted resource allocation.

## **Methodology**
- **Data Clustering**: Unsupervised ML techniques (K-Means, Hierarchical Clustering) for hospital grouping.
- **Statistical Analysis**: Correlation testing between patient volume, treatment time, and resource allocation.
- **Visualization & Reporting**: Data-driven insights presented through Power BI dashboards and statistical reports.

## **Technologies Used**
- **Machine Learning**: Scikit-learn (Clustering, PCA)
- **Data Processing**: Pandas, NumPy
- **Visualization**: Power BI, Matplotlib, Seaborn

## **Conclusion**
The study suggests that **resource allocation across Queensland is largely effective**, with hospitals at both ends of the patient volume spectrum performing well. However, **mid-sized hospitals in major cities** showed signs of operational strain, potentially requiring additional support. By refining hospital classification methods and improving resource distribution, healthcare services can be optimized for all Queenslanders.


---
### **Authors**
- **Arthur Guillaume** – Data Science & Machine Learning Specialist

