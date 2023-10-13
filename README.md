# Credit-Decision-Analytics
<img width="593" alt="METRIC" src="https://github.com/harpalsinhjhala13/Credit-Decision-Analytics/assets/141703984/6da4c4b1-e067-4cf6-8daa-0ba4964fd874">



****Metrics Definition:********

**1. Loans Repaid Duration:**
   - Why Chosen: This metric provides insights into the average duration in months, customers take to repay their loans. Maximum number of Loans are being repaid in duration of 14, 8, 11 or 7 months. It’s crucial for understanding customer behavior and planning repayment schedules, also increase profitability of Business. I have further suggested a key Business insight that might help KIVA increase its revenue based on this metric on the next page.
   - Pros: Helps in predicting repayment method and also gives us understanding of customer standpoint of view. Also allows for better resource allocation, and aids in customer segmentation. Provides a clear understanding of customer commitment.
   - Cons: Might not capture outliers (very short or long-term loans), needs to be analyzed alongside other metrics for comprehensive insights.

**2. Method of Repayment (Months, irregular, bullet):**
   - Why Chosen: Method of repayments can indicate financial instability or financial behavior of customers. Also to indicate that significant amount of loans are either monthly or irregular repayment method based, which can further used to derive to the conclusion, I have suggested on next page. Also additionally, monitoring the percentage of irregular repayments helps in risk assessment and understanding the customer's financial health.
   - Pros: Identifies high-risk customers, provides insights into payment behavior, and helps in personalized customer engagement.
   - Cons: Doesn’t provide reasons for irregular payments, might need additional qualitative data for a complete understanding.

**3. Gender-based Loan Division:**
   - Why Chosen: Understanding if there’s a correlation between gender and loan repayment methods. It uncover potential biases or differences in financial behavior, that is females are more frequent loan borrowers as well as the repayment method widely chosen by female is either irregular or monthly.
   - Pros: Helps in identifying gender-specific financial challenges, informs targeted financial education programs, and ensures fair lending practices, gives key Business insights.
   - Cons: Doesn’t account for other demographic factors, might be influenced by societal norms and cultural factors, and needs to be handled sensitively
 
**Short Analysis:**
The loan count visualization, revealing popular repayment durations of 14, 8, 7, and 11 months, highlights distinct customer preferences. I propose a strategic model for KIVA, encouraging 12-15 months’ repayment periods. This extended timeframe reduces default risks and supports consistent monthly payments due to lower installments. It aligns KIVA's offerings with customer choices, enhancing profitability and building a sustainable lending ecosystem. Ethical practices, consistent monitoring, and a customer-centric approach remain pivotal. This approach fosters trust, ensures lender satisfaction, and empowers borrowers effectively.

**1. Mitigating Default and Irregular Payments:** Longer repayment periods, such as 12-15 months, provide customers with ample time to manage their finances, reducing the risk of default and irregular payments. Lower monthly installment amounts make it easier for borrowers to meet their obligations consistently.

**2. Enhancing Customer Engagement:** Extending repayment periods caters to customer preferences, fostering trust and loyalty. Lenders favor longer durations for higher returns, enriching KIVA’s ecosystem, enabling more loans, and empowering borrowers.

**3. Boosting KIVA's Revenue:** A longer loan duration enables KIVA to charge a slightly higher interest rate due to the extended timeframe. Additionally, the cumulative interest earned on loans over a more extended period increases KIVA’s revenue stream. Assuming KIVA earns a commission from both lenders and borrowers, this model enhances profitability.


**Challenges and Considerations:**
**1. Customer Education: **Educate customers about the benefits of extended repayment periods, clarifying misconceptions and addressing concerns. Transparent communication is vital for customer understanding and acceptance.

**2. Monitoring and Adaptation:** Implement a robust monitoring system to assess the effectiveness of the extended repayment model. Regularly analyze data to adapt strategies based on customer response and market dynamics.


**Recommendation for Tracking and Reporting Defined Metrics:**  

**1. Gender-Specific Metric Tracking:** Utilize Power BI’s or Tableau's capabilities to create gender-specific dashboards. This segregation will provide detailed insights into the financial behaviors of men and women, enabling tailored strategies.
   - Implement interactive charts and graphs to visualize gender-based trends, enabling KIVA to make informed decisions related to customer engagement and product offerings.

**2. Data Cleaning and Maintenance:** Establish a robust data cleaning protocol to address discrepancies. Regularly audit and clean the dataset to maintain accuracy and consistency.
   - Utilize Python for advanced data cleaning algorithms, ensuring data integrity. Python’s libraries, like Pandas, offer powerful tools for handling complex data discrepancies.

**3. Utilize Python for Advanced Analysis:** Python, with libraries such as NumPy and SciPy, can be employed for in-depth statistical analysis. These tools can validate assumptions, ensuring that insights drawn are accurate and reliable.

**4. Regulatory Compliance and Ethical Considerations:** Monitor regional regulations and update the reporting tools accordingly to comply with legal requirements. Regularly validate the tools against the latest legal standards to avoid discrepancies.

**5. Regular Monitoring and Adaptation:**  Implement a real-time monitoring system through Power BI or Tableau, allowing constant vigilance of the defined metrics.
   - Conduct periodic reviews to assess the effectiveness of extended loan durations. Adapt strategies based on the monitored data, ensuring that customer preferences and market dynamics are always considered.

**Challenges and Mitigations:**
**1. Data Quality Management:**
   - Challenge: Data discrepancies can lead to erroneous outcomes.
   - Mitigation: Implement automated data validation scripts and conduct regular data audits. Employ data quality management tools to identify and rectify discrepancies promptly.

**2. Regulatory Compliance and Ethical Practices:**
  - Challenge: Balancing profit motives with ethical lending practices.
   - Mitigation: Collaborate with legal experts to stay updated on regulations. Ethical considerations should be integral to product design. Transparent communication with borrowers builds trust.
 
– Harpalsinh Jhala
