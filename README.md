
Subscription Cancellation Analysis with SQL

Case Study: Subscriptions Cancelation Analysis


You’re having a lovely Monday morning getting a slow, quiet start to your day. It’s 8am, and you’re working from home today. You take your first sip of coffee, and it’s heavenly… UNTIL! Your CEO loops you into an email with the leadership team in a panic. She says that churn has been much higher than expected this year which means that many customers have been leaving and canceling their subscriptions instead of renewing. The company is having a retention crisis and needs to figure out how to improve retention before the next board meeting— or the board is not going to be happy! You brainstorm a few quick ideas on how you can make the product stickier and keep customers around longer, but you know you can’t just trust your gut! You have to look into the data first to see what insights you find. 


You reach out to your customer support team first and ask them to pull qualitative data and testimonies from customers who have left. This will be useful to understand on a deeper level why customers are leaving and what their overall tone is when they leave. Then you work with the product manager to understand what the cancelation workflow looks like. Users first have to go to their subscription settings, click cancel, and then enter the cancelation flow. The cancelation flow requires them to select one reason why they are canceling, and then there are 2 additional selections that are optional. Each selection is a dropdown with the same preset values— so you’re already thinking that this categorical data will be much easier to work with than text boxes that allow any text feedback to be typed into them. Qualitative text data can be the wild west due to the inconsistencies and inability to easily summarize insights. 


You know you already want to look into these selections in the cancelations table, but you’re also curious how many users actually select more than just the first required selection. Is it possible that this workflow could be really annoying and frustrating for users and they click random things to get through as quickly as possible? Or do we think users are providing accurate info and we can depend on most of these selections to accurately reflect the user’s reason for canceling? You have a lot to dig into and can’t wait to report your findings back to leadership!


Subscription Cancellation Analysis Summary
Title: Understanding and Reducing Subscription Cancellations
Executive Summary:
This analysis investigates the high churn rate that has been a concern for our company. By identifying the reasons for cancellations and understanding customer behavior, we aim to improve retention and reduce subscription cancellations.

Business Problem:
The company is experiencing a higher-than-expected churn rate, with many customers canceling their subscriptions instead of renewing. This retention crisis needs to be addressed urgently to prevent further revenue loss and satisfy the board's expectations.

Methodology:
Qualitative Data Collection:

Gathered qualitative data and testimonies from customers who canceled their subscriptions through the customer support team to understand their reasons and overall sentiment.

Cancelation Workflow Analysis:

Worked with the product manager to understand the cancellation workflow, which involves selecting a reason for cancellation (one required and two optional selections).

Data Analysis:

Analyzed the cancellation reasons from the cancelations table.

Investigated how many users made additional selections beyond the first required reason.

Evaluated the accuracy and completeness of the data to understand customer behavior and potential frustration points.

Skills:
SQL for data extraction and analysis.

Data visualization for presenting findings.

Customer sentiment analysis.

Problem-solving to identify friction points and propose solutions.

Results:
Completion of Data: Most users provided only the required reason for cancellation, with fewer users opting to provide additional reasons.

<img width="430" alt="image" src="https://github.com/user-attachments/assets/b5d03401-3e37-4f26-958d-967aa9f75178" />


Common Cancellation Reasons: Identified the most frequent reasons for cancellations, including factors like price, lack of value, and poor customer service.

<img width="485" alt="image" src="https://github.com/user-attachments/assets/04f092b3-afcb-4348-aee9-c3f27e17f1d1" />


User Frustration Points: Observed that the cancellation workflow might be frustrating for users, leading them to select random options to complete the process quickly.

<img width="482" alt="image" src="https://github.com/user-attachments/assets/4db19450-f812-4ad1-a5ef-9d42e345397c" />

<img width="472" alt="image" src="https://github.com/user-attachments/assets/f172c933-d0bf-4bc1-9a02-f75a42aa03c4" />



Business Recommendations:
Improve User Experience:

Simplify the cancellation workflow to reduce user frustration.

Provide more intuitive and user-friendly options for selecting cancellation reasons.

Enhance Data Accuracy:

Encourage users to provide additional feedback by making the process easier and more engaging.

Use qualitative data to complement quantitative analysis and gain deeper insights.

Retention Strategies:

Address common cancellation reasons by improving customer service, offering better value, and considering pricing adjustments.

Implement targeted retention campaigns based on the insights gathered from the analysis.

Next Steps:
Implement recommended changes to the cancellation workflow.

Monitor the impact of these changes on the churn rate and customer satisfaction.

Gather continuous feedback from users to further refine the cancellation process and retention strategies.
