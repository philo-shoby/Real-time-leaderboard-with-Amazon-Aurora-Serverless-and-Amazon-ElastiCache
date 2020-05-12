# Real-time-leaderboard-with-Amazon-Aurora-Serverless-and-Amazon-ElastiCache

This is a project to create real time leaderboard using AWS services.
The web application is built using Express.js, a popular Node.js web application framework.

# Services used:
-	Amazon Aurora Serverless and the Data API for fast, elastic, fully-managed data storage
-	Amazon ElastiCache for fast lookups on your global leaderboard
-	Amazon Cognito for user authentication
-	AWS Lambda for compute
- Amazon API Gateway

Steps:
-	First, you start with a Registration endpoint, where a new user signs up and creates their account.
-	Second, you use a Login endpoint where a user can use a client (such as a web application or a mobile app) to authenticate and receive an ID token.
-	Third, you use a AddUserScore endpoint to record a score for a user.
-	Fourth, you use the FetchUserScores endpoint to retrieve the top scores for a particular user.
-	Finally, you use the FetchTopScores endpoint to retrieve the global top scores for the current day and month as well as the top scores of all time.

> snapshots.pdf contains the snapshots of each steps.

> scripts.txt contains commands to run in Amazon Cloud9
