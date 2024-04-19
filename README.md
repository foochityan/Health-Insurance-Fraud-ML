# Health-Insurance-Fraud-ML

# Know the context
You are a data scientist in a major health insurance provider in the US. They are looking to build a claims fraud detection model in a bid to make claims processing faster, more accurate, and automated.

# Business problem
Existing manual methods of reviewing claims for fraud is tedious, unscalable, and lacks accuracy
Rule-based fraud detection methods are rigid and less readily adaptable to drifts in fraud patterns
Project objectives and description
Explore the implementation of several common statistical tests (using scipy.stats) as part of the insurer's preliminary investigation into reports of potential fraudulent healthcare claims.

# Part 1 - Individual Provider
There have been rumours that a specific provider with the ID "bb49afa2-3d8a-306c-a06e-a1715dd71af8" is overbilling treatments for patients, resulting in allegedly excessive claim costs. In particular, the provider has been accused of having an average total claim cost that is significantly higher than other providers of the same specialty i.e., General Practice.
Our task is to identify the provider based on his/her details, and verify whether this accusation is true.

# Part 2 - Two organizations
There are two organizations with similar profiles (types of patients seen, location etc.) for which we want to test whether the total claim costs between them are indeed similar as well. The IDs of the two organizations are "226098a2-6a40-3588-b5bb-db56c3a30a04" and "108ccece-277a-396f-8bf2-1527f74458eb"

# Part 3 - More than two organizations
The insurer is now keen to review the average total claim costs of PCPs (private clinical practices) within a particular set of cities, and to see if one or more of them has a significantly different (higher or lower) average dollar cost from the rest. The set of cities include AVON and WATERTOWN.

# Part 4 - Proportions across two providers
To account for differences in total claim costs across two doctors (i.e., providers), the insurer is looking to test if there is any significant differences in the proportion of encounter classes (e.g., outpatient, inpatient etc.) that they each have to handle.
The providers to be evaluated are as follows:
ID of Provider 1: b0c5743a-4f9a-33b3-bab4-6a474fcf9ffd
ID of Provider 2: fc897c25-b2ee-30c5-a945-d0eb13a1f96e
