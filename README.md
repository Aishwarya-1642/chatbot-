
# to place order for pizza
# Description:
This project builds a serverless chatbot that allows users to order pizza through a conversational interface. The bot collects user inputs such as pizza type, toppings, crust,apetizer and delivery details, confirms the order, and stores it securely. The system is designed using AWS services to ensure scalability, low maintenance, and high availability
# Key AWS Services Used:

Amazon Lex – to build and manage the conversational bot (understands user input and responds).

AWS Lambda – to process logic like saving the order, validating choices, and sending confirmations.

Amazon DynamoDB – to store order details in a fast, scalable NoSQL database.

Amazon SNS (optional) – to send text message updates when the order is confirmed.

API Gateway (optional) – to expose order processing as an API if needed.

CloudWatch – for monitoring logs and bot activity.
# steps and preview in free tier account 
# choose service amazon lex
![Screenshot (16)](https://github.com/user-attachments/assets/f75cfa05-5293-4166-9994-c3cdcc0fa8a1)

# choose create bot
![Screenshot (14)](https://github.com/user-attachments/assets/b82e3490-75b6-46eb-9f18-d13e70917203)
![Screenshot (28)](https://github.com/user-attachments/assets/84691d5c-1782-4e6e-b6a2-0c03a1e90d37)
![Screenshot (29)](https://github.com/user-attachments/assets/ff0db6b2-81c6-49cc-9854-726c6b146e6b)
![Screenshot (30)](https://github.com/user-attachments/assets/ca92950e-dabe-48a4-86e4-a5464204930f)
![Screenshot (31)](https://github.com/user-attachments/assets/3986ebab-92e8-49ab-81e5-1838e9f61646)
![Screenshot (32)](https://github.com/user-attachments/assets/fc956e3e-37a7-43c3-8ab5-5046f42ad92a)
# add slot type
![Screenshot (37)](https://github.com/user-attachments/assets/8c4a5065-7629-4f6b-a2e9-22c8a7733eee)
# save intent
![Screenshot (39)](https://github.com/user-attachments/assets/deff6afd-6635-4b17-9fe6-5f9fcc665c7e)
#  give prompt, select slot, save intents 
![Screenshot (40)](https://github.com/user-attachments/assets/8b87a5dd-3182-4bd5-b257-b33786897a0f)
# for advance feature we can use buttons.
![Screenshot (43)](https://github.com/user-attachments/assets/6f1fe90b-8013-4f4d-a93e-c7383657b875)
# we can test  the bot 
![Screenshot (50)](https://github.com/user-attachments/assets/fe17d161-d781-416b-8bdb-cddb26508eb5)
![Screenshot (51)](https://github.com/user-attachments/assets/2715dacf-4561-4f00-8706-0a22d8911eda)
![Screenshot (52)](https://github.com/user-attachments/assets/fb42a7d8-0857-45c0-a529-518a61cdd8dc)
![Screenshot (53)](https://github.com/user-attachments/assets/1bbbd12d-e84d-4742-86dc-b02e75f321ce)
# How it Works:

User interacts with the Lex chatbot, selecting pizza type, crust, toppings, and delivery options.

Lex triggers a Lambda function to validate and process the order.

Lambda saves the order details in DynamoDB.

(Optional) After confirmation, an SMS notification is sent to the customer using SNS.

Goals:

Learn how to integrate multiple AWS services together.

Understand serverless architecture for building real-world applications.

Build a scalable chatbot that can handle multiple users.
















