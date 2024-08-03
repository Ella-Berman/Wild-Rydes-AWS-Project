# Wild-Rydes-AWS-Project
Due to costs, resources were terminated. Presentation outlines the deployment process, states cost predictions, and provides a video
demonstration of website functionality:
https://docs.google.com/presentation/d/1hlTBQ2d4xrSgHzb_mslsUNpwUEU_ERYlI74oH-ypkYU/edit?usp=sharing

Used AWS services to deploy a dynamic serverless web application that allows users to request an account, 
confirm their account via email, sign in to the website, and request rides on an interactive map. 
I used S3 to host a static web app, Cognito to authenticate and manage users, Lambda, IAM, and DynamoDB 
to build a serverless backend, and API Gateway to deploy a RESTful API. 

I gathered data from CloudWatch to analyze metrics such as the amount of data stored/transferred and the number of get requests, token requests, and API requests made. I utilized this data to make cost predictions for running the platform with millions of monthly users.
