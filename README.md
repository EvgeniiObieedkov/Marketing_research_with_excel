## Marketing_research_with_excel  

#### Introduction in the case  
May 2022. A mobile network operator is planning to expand into a new region.  
You are participating in a marketing research project to determine which mobile tariff would be most popular among the target audience — subscribers aged 18–25.

🎯 #### Project Goals  
Assess tariff suitability:  
In neighboring regions with similar socio-economic conditions, the operator offers the "Online" tariff to the same target audience.  
→ Analyze whether it can be promoted under the same conditions in the new region.

Design a promotion package:  
The operator wants to offer a promotion for new subscribers: a bundle of 2 additional services free for the first two months after activation.  
→ Identify which two services would be most attractive to the target audience.  

Step 1 – Usage  
Avg. monthly minutes & GB (use DATEDIF)  
Filter: age 18–25  
Add subscription fee  

Step 2 – Survey Cleanup  
Remove duplicates, blanks, non-target ages  

Step 3 – Dissatisfied Users  
Pivot: minutes + GB (for dissatisfied)  
Chart results  

Step 4 – Weekly Segments  
Convert usage to weekly  
Filter age 18–25  
Repeat Step 3  

Step 5 – Willingness to Pay  
Pie charts: fee & willingness  
Count those fitting “Online” usage  
Of them, who’d pay 28–38 USD  

Step 6 – Service Pairing  
Matrix of additional service pairs  
Find most frequent combo  
