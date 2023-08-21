> Given that Fluffy wakes you up 2/3rds of nights independently: What is the probability that you get at least 2 full nights of sleep over the 5 nights you dogsit for your friend?

131/243

2/3 chance of waking up => 1/3 change of sleeping\
X ~ Bin(5, 1 - (2/3))\
P(>= 2/5 nights sleep) = ? = P(X >= 2)\
= 1 - [ P(X = 0) + P(X = 1) ]\
= 1 - [ (5 choose 0) * (1/3)^0 * (2/3)^5 +  (5 choose 1) * (1/3)^1 * (2/3)^4]\
= 1 - [ 5 * 1/3 * 16/81 + 32/243 ]\
= 1 - [ 80/243 + 32/243 ]\
= 1 - 112/243\
= 131/243

Source: https://www.youtube.com/watch?v=GEPPT8SY6BI&list=PLCiAikFFaMJqKqVO8BZ3rJKRU8K_AFknx&index=3
