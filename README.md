# CRIME-ANALYSIS
![image](https://github.com/user-attachments/assets/64d25060-af72-4e35-a957-9cf6571e5ec5)

Crime Scene: Do Not Cross - Investigation in Progress

**Interact with the final Dashboard**

[Crime Dashboard](https://drive.google.com/file/d/1cZ6pqL4zPwWXyi1h2hB_2hUV7MolBV7z/view?usp=sharing)

[Google Drive Download Link](https://drive.google.com/drive/folders/12Ik4VTO7yKkQhYNqDUFgmQMgVa95xYPW)

**Understanding Crime Trends and Patterns for Effective Resource Allocation and Crime Prevention**

**Problem Statement:**

The crime dataset, containing records such as Offence Group, Offence Subgroup, Number of Offences, Offence Description, Force Name, and Financial Year/Quarter, provides a comprehensive view of criminal activities over time. However, law enforcement agencies face challenges in identifying trends and predicting future crime occurrences due to the large volume of historical data.
This issue is further complicated by the need to understand how crime patterns evolve across different offence groups and subgroups, and how offences fluctuate throughout the financial years and quarters. Without clear insights into these trends, resource allocation may be inefficient, leading to under-policing in high-crime areas and missed opportunities for crime prevention. Additionally, seasonal fluctuations and specific crime patterns are often overlooked, making it difficult to develop effective crime prevention strategies.

[Data Source](https://github.com/Datafyde/Power-BI-Guided-Project-Data-Titans.git)

**Key Challenges:**
Identifying Crime Trends: Detecting patterns in crime over time (e.g., quarterly or yearly trends) to understand when offences spike and which offence groups contribute the most.
Resource Allocation: Determining where to focus law enforcement efforts based on historical crime data, particularly during high-crime periods.
Offence Group Analysis: Analyzing how different offence groups and subgroups contribute to total crime and whether certain categories consistently dominate the statistics.
Predictive Crime Analytics: Leveraging historical data to predict potential future trends and help law enforcement agencies proactively mitigate crime.

**Research Objective:**
This project aims to:
Analyze crime patterns by year and quarter to identify seasonal or recurring trends.
Examine offence groups and subgroups to determine which crimes are most frequent and how they evolve over time.
Provide insights for law enforcement agencies to better allocate resources, focusing on high-frequency offence periods.
Support data-driven decision-making for proactive crime prevention by identifying high-risk offence periods and potential future trends.

**Research Questions :**
1. What is the seasonal crime pattern, and how do offences vary across financial quarters?
2. Is there a noticeable pattern in crime rates based on seasonal or quarterly trends?
3. How do different offence groups distribute across financial quarters?
4. What is the overall distribution of offences across the four financial quarters?
5. How does the number of offences change from year to year?
6. What are the most common offence groups?
7. What are the most common specific offence subgroups?
8. How do total offences change across both financial years and quarters?


**Data preprocessing was performed using Python, involving:**

1. Data deduplication
2. Inconsistency resolution
3. Removal of non-positive values (zero and negative)
4. Data transformation for analysis and visualization compatibility

   **Dataset before transformation:**
   ![image](https://github.com/user-attachments/assets/7ba8b978-e299-40e6-ae2f-709147437aca)

   **DataSet after Transformation:**
   ![image](https://github.com/user-attachments/assets/f294801e-eaa9-48dd-b7eb-9531c04ac84e)

   **Data Transformation using Python:**
   [Python Code](https://drive.google.com/file/d/1I5eaacBOfT8QaQ5QdTBccpryryLVqZCO/view?usp=sharing)

   **Visualization Uing PowerBi:**
   ![image](https://github.com/user-attachments/assets/27cae137-63db-49e7-979b-d54f09fbb537)

   **Issues and Solutions in Big Data Analytics:**
1. Data Privacy & Security: Sensitive crime data is vulnerable to breaches and unauthorized access.
Solution: Implement encryption, anonymization techniques, and stringent access controls to protect sensitive information.
2. Data Quality & Accuracy: Inconsistent or incomplete crime records can lead to inaccurate insights and unreliable decisions.
Solution: Use data cleaning tools and validation processes to ensure high-quality, consistent data.
3. Real-Time Analysis: Processing real-time crime data for immediate insights can be technically challenging.
Solution: Employ real-time data streaming platforms such as Apache Kafka for efficient real-time data analysis.
4. Scalability: Managing and analyzing large and growing crime datasets becomes increasingly difficult as data volume grows.
Solution: Utilize distributed computing frameworks like Apache Hadoop or Apache Spark to efficiently scale data processing.
5. Data Integration: Combining crime data from multiple sources (e.g., police reports, social media, surveillance) can be complex and prone to errors.
Solution: Leverage advanced data integration tools to seamlessly combine data from diverse sources for holistic crime analysis.

**Effective Solutions Using Big Data:**
1. Predictive Policing: Machine learning algorithms can predict potential crime hotspots, enabling law enforcement to allocate resources proactively and prevent crime before it happens.
2. Social Media Analysis: By applying Natural Language Processing (NLP), big data systems can scan social media platforms for signs of potential criminal activity, providing early warnings for law enforcement.
3.  Geospatial Analysis: Geographical Information Systems (GIS) can be integrated with big data to map crime hotspots and visualize crime patterns, helping in strategic planning and crime prevention.
4. Real-Time Surveillance: With the integration of IoT devices and video analytics, big data can be used to monitor high-risk areas in real time, improving surveillance and immediate response to criminal activities.
5. Crime Pattern Detection: Big data tools such as Apache Spark can process large volumes of crime data to detect hidden patterns, helping law enforcement identify trends and make informed decisions for crime prevention.

Link:[Issues and Solution using Big Data Analytics](https://docs.google.com/document/d/1782-df_uDY8mHoK5mXRkLeC_YQDVU_pYKLBqjZHgsWo/edit?usp=sharing)

**Crime Data Summary and Recommendations:**

Total Offences by Quarter:
Q1 had the highest offences at 16,003,859.
Q2 had the highest average offences at 1,339,987.82, with Q1 closely following.

Recommendation:
Prioritize resource allocation in Q1 and Q2 due to consistently high crime rates.
Use predictive models to plan for Q1 and Q2 spikes in crime.

High-Frequency Offence Groups:
Miscellaneous crimes against society led with 31,625 offences (320.83% higher than public order offences).

Recommendation:
Focus on targeted enforcement for high-frequency crimes like miscellaneous crimes.
Monitor lower frequency offences like public order for potential surges.

Yearly Crime Distribution:
Offences ranged from 4,638 to 17,909 across 12 Financial Years.
Recommendation:
Investigate factors behind annual spikes and adjust long-term crime prevention strategies.


**General Recommendations:**

Seasonal Policing: Focus on Q1 and Q2, where crime peaks.
Predictive Analytics: Use data to anticipate trends and adjust enforcement strategies.
Targeted Crime Prevention: Prioritize high-frequency crimes (e.g., miscellaneous crimes) while monitoring lower-frequency offences.




   

