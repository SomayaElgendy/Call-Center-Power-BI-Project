
# Call Center-Dashboard

![Snap_1](<https://github.com/user-attachments/assets/d7d17120-0120-42c8-8307-9ec43278a207/>
)

## Problem Statement

This dashboard is designed to help call centers analyze their performance trends and improve service delivery. It provides insights into customer satisfaction, agent performance, call resolution rates, and average response times. By identifying areas of improvement, such as high call abandonment rates or low agent satisfaction scores, the dashboard enables management to make data-driven decisions.

Additionally, metrics like the number of calls handled, average wait time, and agent availability trends allow for better resource allocation and process optimization.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Two pie charts are added. One to represent the perecntage of answered and not answered calls, and one to represent the perecntage of resolved issues and not resolved issues.
- Step 4 : A stacked column chart is used to show how many calls are answered by each agent and how many issues are solved of these answered calls. to make this chart, two measures are created: the sum of answered calls and the sum of resolved calls.
- Step 5 : Visual filters (Slicers) were added for different topic types named "Admin Support", "Contract Related", "Payment Related", "Streaming", "Technical Support".
- Step 6 : Two card visuals were added to the canvas, one representing average speed of answer in seconds & other representing average satisfaction.
- Step 7 : A bar chart was also added to the report design area representing the number of calls per month.
        
Results for different topic types:

![Snap_Admin](https://github.com/user-attachments/assets/2892fd12-caf9-429d-9b4d-383c00713b6e)

![Snap_Contract](https://github.com/user-attachments/assets/9215f864-91b2-4e81-a371-42c38fb8f179)

![Snap_Payment](https://github.com/user-attachments/assets/8703792d-7066-4027-b8aa-d5f29adf62f6)

![Snap_Streaming](https://github.com/user-attachments/assets/964bf177-fe44-4191-88f1-bd440761ba96)

![Snap_Technical](https://github.com/user-attachments/assets/41351214-331b-44ea-b4e9-5b774d328bb8)

# Insights

A single page report was created on Power BI Desktop.
Following inferences can be drawn from the dashboard;

### [1] Answered Calls vs. Unanswered Calls
- Answered Calls: 81.08% of the total calls are answered, indicating good performance in handling customer queries.
- Unanswered Calls: 18.92% remain unanswered, which can be improved by optimizing agent availability during peak times.
           
### [2] Resolved Calls vs. Unresolved Calls
- Resolved Calls: 72.92% of the answered calls are successfully resolved, showcasing decent issue resolution.
- Unresolved Calls: 27.08% remain unresolved, highlighting a need for enhanced agent training or better resource allocation.
  
### [3] Average Speed of Answer
- The average speed of answer is 67.52 seconds, which is moderate but can be further reduced to improve customer satisfaction. Long wait times may contribute to higher customer dissatisfaction.

 ### [4] Call Volume per Month
- January: Highest number of calls with 1.8K.
- February and March: Call volumes decrease slightly to 1.6K each. This trend suggests seasonal variations or reduced demand during these months.

 ### [5] Agent Statistics
- Top Performers:
  - Jim: Leads with 536 answered calls and 485 resolved calls.
  - Dan and Becky: Follow closely with good performance metrics.
- Improvement Areas:
  - Stewart: Lowest performer with 477 answered calls and 424 resolved calls. Consider providing additional support or training.
- The small gaps between answered and resolved calls across agents reflect efficiency but still leave room for reducing unresolved issues.

 ### [6] Customer Satisfaction
- Average Satisfaction Score: 3.40 out of 5. While this is acceptable, there is significant room for improvement. High unresolved rates and longer answer times might be contributing factors.

# Recommendations for Improvement

    1. Reduce Unanswered Calls:

    - Optimize shift schedules based on call volume trends.
    - Introduce an overflow system or callback options during peak times.

    2. Improve Call Resolution Rates:

    - Conduct targeted training sessions for agents with lower resolution rates.
    - Provide agents with better tools or access to FAQs to resolve issues more efficiently.
    
    3. Enhance Speed of Answer:

    - Add more agents during peak call hours.
    - Introduce automated responses or IVR systems for basic queries to reduce agent load.

    4. Focus on Agent Support:

    - Recognize and reward top performers like Jim to motivate other agents.
    - Offer personalized training for agents like Stewart who underperform.
    5. Increase Customer Satisfaction:

    - Survey customers to identify specific dissatisfaction causes.
    - Address factors like long wait times and unresolved calls to improve the overall experience.
