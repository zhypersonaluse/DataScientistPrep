# Summerize By HZ for personal interview usage
# Step 1 Clarify and Deconstruct the Problem
- Don't assume anything. Ask clarifying questions. 
There are multiple types of product sense questions
- Type 1: Diagnose a problem or root cause analysis: When you saw a metric dropped X%, how would you investigate?
    -
     **Example Answer**
    - S1. What is the usage of this metric? Is this metric drop suddenly or is there a decreasing trend in this metric?
    - S2. I would like to investigate this problem through the following processes:
        1. I would like to double check the data collection progress, to ensure there is no data error during ETL
        2. After the data collection process is clear, I would like to check the horizontal metrics and upstream metrics to ensure there is no big shift in that process. If we see a similar change or opposite change in these metrics, we could use it to explain the decrease initially.
        3. Then we could analyze the metrics deeply by investigating the metrics by different user groups, regions, language, platforms, incoming channels etc.
        During this process,I would like to analyze the root cause in two aspects:
        - Internal Factor, Is there any seasonality in the data itself? Could is there any internal strategy change, is there any model change, is there any marketing campaign during this process. If that is the case, we could analyze whether the change leads to this decrease.
        - External Factor, Could competitor marketing campaign affect the upsteam metrics? Could abnormal environment affect the upstream rate? 
    - S3. Summerization
        Once the root cause is determined, we could evaluate how this metrics will affect the long term goal. If this change impact the long term goal, we could contact the counterparties for either a rollback or another round of strategy change.

- Type 2: Measure the success:When there is a product or feature, how would you evaluate Whether this product or feature performs its jobs?
    -
    **Example Answer**
    - S1. What is the detailed functions of this new product? and what are the primary goals for this new product and which group is this new function target for? For example, is this new product to provide some new functions to help improve user engagement? to reduce the learning path of a customer? Or just a brand new function to attract more users?
    - S2. For this problem, I would like to provide two success metrics and one guardrail metric related to the goals. 
        - **Example 1, if the product or feature is used to enhance the user engagement**    
        - success metrics:
        - 1). I would like to use the usage rate, since this product or feature is introduced to improve the user engagement, we need to know the precentage of users who start to use this product, if the usage is high, we could continue the analysis, if the usage is low, we might need to perform further analysis. 
        - 2). I would like to use effective average time spending on the product or the new feature, because this metric could help us understand whether the users will start to use this new feature. The reason I use effective time is the new product or feature may take the user some time to figure out and get used, this time should not be counted. 
        - guardrail metric:
        - I would like to use the retention rate as the guardrail metric, because it's a new product or feature, which always introduce complexity for users to use the products. If the users found the new product is complicated to use or hard to learn, they would like to shift to a simpler product so that we would loss users. Therefore, for a new feture, I would like to use this metric as a guardrail metric.
        - **Eample 2, if the product or feature is used to enhance the profit**
        - To Be Continue

- Type 3: launch a new product or not: When there is a new product, what should be done to determine whether the proposed product should be launched or not?

- Ask Assumptions:
    - What are the goals of this new feature?
    - What are the target users of this new feature?