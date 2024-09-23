# Chatbot-with-Amazon-Lex
Build a Chatbot with Amazon Lex

Amazon Lex is a fully managed service from AWS that allows developers to build conversational interfaces using voice and text. It powers Alexa and uses the same deep learning technologies for automatic speech recognition (ASR) and natural language understanding (NLU). Lex helps you design and build chatbots, virtual agents, or any interactive conversational system.

 🔐Why do we need Amazon Lex permissions?
Amazon Lex needs the permission to call other AWS services on your behalf, later in this project series you'll be integrating Lex with another service called Lambda!

 🔐 What does Idle session timeout mean?
Amazon Lex will only maintain a session for a set length of time.

 🔐 What is intent classification confidence score threshold?
When you're using Amazon Lex to build a chatbot, this threshold is like a minimum score for your chatbot to confidently understand what the user is trying to say.

Setting this to 0.4 means that your chatbot needs to be at least 40% confident that it understands what the user is asking to be able to give a response.
So if a user's input is ambiguous and your chatbot's confidence score is below 0.4, it'll throw an error message.
 
  🔐  What are intents?
An intent is what the user is trying to achieve in their conversation with the chatbot. For example, checking a bank account balance; booking a flight; ordering food.
In Amazon Lex, you build your chatbot by defining and categorising different intents. If you set up different intents, one single chatbot can manage a bunch of requests that are usually related to each other.
