# Enigmatic AI Chatbot
This project is an interactive chatbot that aims to tease and tantalize users with hints about an upcoming breakthrough in cutting-edge AI integration. The chatbot is designed to be enigmatic, providing concise and coy responses to user inquiries.

![Screenshot of chatbot closed](/screenshots/chatbot_with_intents-closed)
![Screenshot of chatbot open](/screenshots/chatbot_with_intents-open)

## Features
1. **Chatbot Interface**: The chatbot is displayed as a floating icon on the bottom right of the web page. Users can click the icon to expand the chatbot interface and interact with it.
2. **Hint and Clue System**: The chatbot is programmed to respond to specific keywords, such as "hint" or "clue," by providing vague and intriguing responses. These responses are designed to pique the user's curiosity and encourage them to sign up for updates.
3. **Sign-up Promotion**: The chatbot encourages users to sign up for updates to be among the first to know about the upcoming breakthrough.
4. **Local LLM Integration**: The `chatbot_with_intents-local` version of the project uses a local large language model (LLM) to generate the chatbot's responses. This allows for more consistent and accurate responses, even with a quantized 7B model running locally.
5. **GCP Cloud Function Integration**: The `chatbot_with_intents` version of the project uses a GCP Cloud Function to make API calls to OpenAI's GPT-3.5-Turbo model, providing a more robust and scalable solution.

## Experimentation with System Prompt
The development of this chatbot involved extensive experimentation with the system prompt. The goal was to create a chatbot that would provide consistent and accurate responses, even when using a smaller, quantized model running locally.
Through this experimentation, I was able to refine the system prompt to achieve the desired level of enigmatic and concise responses from the chatbot. The prompt sets the tone for the chatbot's personality and guides the language model in generating appropriate responses.

## Deployment
The two versions of the chatbot can be deployed in different ways:
1. **chatbot_with_intents-local**: This version can be deployed as a standalone web application, with the LLM running locally on the user's device.
2. **chatbot_with_intents**: This version requires the deployment of a GCP Cloud Function to handle the API calls to OpenAI's GPT-3.5-Turbo model. The web application can then interact with the Cloud Function to generate the chatbot's responses.
