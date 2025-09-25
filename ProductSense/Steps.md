# Summerize By HZ for personal interview usage
# Step 1 Clarify and Deconstruct the Problem
- Don't assume anything. Ask clarifying questions. 
There are multiple types of product sense questions
- Type 1: Diagnose a problem or root cause analysis: When you saw a metric dropped X%, how would you investigate?
    Example Answer:
    S1. What is the usage of this metric? Is this metric drop suddenly or is there a decreasing trend in this metric?
    S2. I would like to investigate this problem through the following processes:
        1. I would like to double check the data collection progress, to ensure there is no data error during ETL
        2. After the data collection process is clear, I would like to check the horizontal metrics and upstream metrics to ensure there is no big shift in that process. If we see a similar change or opposite change in these metrics, we could use it to explain the decrease initially.
        3. Then we could analyze the metrics deeply by investigating the metrics by different user groups, regions, language, platforms, incoming channels etc.
        During this process,I would like to analyze the root cause in two aspects:
        - Internal Factor, Is there any seasonality in the data itself? Could is there any internal strategy change, is there any model change, is there any marketing campaign during this process. If that is the case, we could analyze whether the change leads to this decrease.
        - External Factor, Could competitor marketing campaign affect the upsteam metrics? Could abnormal environment affect the upstream rate? 
    S3. Summerization
        Once the root cause is determined, we could evaluate how this metrics will affect the long term goal. If this change impact the long term goal, we could contact the counterparties for either a rollback or another round of strategy change.


- Ask Assumptions:
    - What are the goals of this new feature?
    - What are the target users of this new feature?