# IMPACT-OF-GENERATIVE-AI-USAGE-ON-STUDENT-ACADEMIC-PERFORMANCE-AND-WELL-BEING

![Ai_ima](Ai_imag.jpg)

## TABLE OF CONTENT

- [INTRODUCTION](#Introduction)

- [DATA SOURCE](#Data-Source)

- [PROBLEM STATEMENT](#Problem-Statement)

- [DATA COLLECTION AND PREPARATION](#Data-Collection-and-Preparation)

- [Skills demonstrated](#Skills-demonstrated)

- [Visualizations](#Visualizations)

- [Insight from analysis](#Insight-from-analysis)

- [Conclusion](#Conclusion)

- [RECOMMENDATION](#RECOMMENDATION)

## Introduction

Generative Artificial Intelligence (GenAI) has become an important technology in education, transforming how students learn, conduct research, complete assignments, and solve academic problems. Tools such as ChatGPT, Google Gemini, Microsoft Copilot, and Claude provide instant access to information, personalized learning support, and assistance with writing, programming, and problem-solving. As a result, the use of GenAI among students has increased significantly in recent years.
The growing adoption of Generative AI offers several potential benefits, including improved learning efficiency, better academic performance, reduced study time, and increased access to educational resources. However, concerns have also been raised about students becoming overly dependent on AI, reduced critical thinking, academic dishonesty, and the possible effects on mental well-being, such as anxiety and burnout.
Given these potential benefits and challenges, it is important to examine how Generative AI influences both students' academic performance and well-being. This study investigates the relationship between Generative AI usage and outcomes such as GPA improvement, skill retention, anxiety levels, and burnout risk. The findings will contribute to a better understanding of how AI can be used responsibly to enhance learning while supporting students' academic success and overall well-being.

## Data-Source
The dataset used in this study was obtained from an online educational resource and was created for learning and research purposes. It contains student-related information on Generative Artificial Intelligence (GenAI) usage, academic performance, and well-being. The dataset includes variables such as students' major category, year of study, pre- and post-semester GPA, weekly GenAI usage hours, primary use case of AI, prompt engineering skill, AI tool diversity, traditional study hours, perceived AI dependency, institutional AI policy, anxiety level during examinations, skill retention score, burnout risk level, and GPA improvement. The dataset was used to examine the relationship between Generative AI usage, students' academic performance, and well-being through data analysis and visualization using Power BI.

## Problem-Statement
This dataset examines how university students across different disciplines utilize Generative AI tools and how usage patterns relate to academic outcomes, skill retention, anxiety levels, and burnout risk. It combines demographic, behavioral, institutional, and performance-related variables to evaluate the educational impact of AI-assisted learning. The analysis seeks to answer the following questions:
- Does increased GenAI usage improve academic performance?
- How does AI dependency affect skill retention?
- Is there a relationship between AI usage and burnout risk?
- Do institutional AI policies influence student outcomes?
- Which AI use cases are associated with the highest GPA improvement?


## Data-Collection-and-Preparation 
#### Raw data:
The dataset on IMPACT-OF-GENERATIVE-AI-USAGE-ON-STUDENT-ACADEMIC-PERFORMANCE was obtained from Kaggle.
[Download IMPACT OF GENERATIVE AI USAGE ON STUDENT ACADEMIC PERFORMANCE ](Impact.csv)

### Tools used: 
        - MICROSOFT Excel - Data Cleaning and Transformation
        - Powerbi - Data visualization and dashboard development.
        - DAX - Creation of calculated measures and KPIs. 
        
## SKILLS DEMONSTRATED:
 - Excel:
    - Checked and removed duplicates to ensure data quality and accuracy.
    - Created a new column named GPA_IMPROVEMENT by calculating the difference between the Post-Semester GPA and the Pre-Semester GPA (Post_Semester_GPA Pre_Semester_GPA). This derived variable was used to measure changes in students' academic performance after a semester of Generative AI usage.
    - convert it as a Table

 - Powerbi:
     - importing the dataset from the excel
     - creating the measures using DAX (Data Analysis Expressions) to perform dynamic calculations. These measures included Total_number_of _student,average_weekly_ai_hours, average_skill_retention, average_gpa_improvement
  
  ## Data Analysis:
 - Perceived_AI_Dependency by Average_Skill_Retention
 - Institutional_Policy by Average_GPA_Improvement
 - Primary_Use_Case by Average_GPA_Improvement
 - sum of Weekly_GenAI_Hours by Sum of GPA Improvement
 - Burnout_Risk_Level by sum of Perceived_AI_Dependency

## Visualizations:
 - ![Ai_image](Ai_image.png)

## Insight from analysis
- Students who used Generative AI more frequently generally showed greater GPA improvement, suggesting that appropriate use of AI tools may positively support academic performance.
- Students with higher perceived AI dependency tended to have lower skill retention scores, indicating that excessive reliance on AI may reduce long-term knowledge retention.
- Burnout risk varied across students with different levels of AI usage, indicating that the amount of time spent using AI may be associated with students' academic stress and well-being.
- Student outcomes differed across institutional AI policy categories, suggesting that university policies on AI use may influence academic performance and learning experiences.
- The analysis indicates that Generative AI can enhance academic performance when used as a learning support tool. However, excessive dependence on AI may reduce skill retention, highlighting the importance of responsible AI use. Institutional policies and the way students use AI also appear to influence academic outcomes and student well-being.

## Conclusion
- The analysis of customer spending patterns provides clear insights into behavior across cities, time periods, and expense categories. Greater Mumbai recorded the highest total spending, followed by Ahmedabad and Bengaluru, indicating stronger customer activity in these locations.
Monthly trends show fluctuations in spending over time, with January 2015, August 2014, and December 2013 recording the highest spending amounts in their respective years. This suggests that customer spending varies significantly across different periods.
In terms of expense types, Food recorded the highest spending amount, showing that customers allocate a large portion of their spending to this category. Additionally, female customers accounted for a higher proportion of transactions after data cleaning and standardization.
Overall, these insights highlight important patterns in customer behavior that can support better decision-making in marketing, customer targeting, and business strategy.

# RECOMMENDATION
- Businesses should focus more on high-performing locations such as Greater Mumbai, Ahmedabad, and Bengaluru by implementing targeted marketing strategies to further increase customer engagement and revenue.
- Since Food recorded the highest spending amount, companies should prioritize expanding food-related products and services to meet customer demand and maximize profit opportunities.
- Seasonal spending patterns should be leveraged by planning promotional campaigns during peak months such as January, August, and December to boost sales.
- Customer segmentation strategies should be developed based on spending behavior, particularly focusing on gender and location to improve personalized marketing.
- Further analysis can be conducted to explore the factors influencing spending behavior across different card types and expense categories for more business insights.


