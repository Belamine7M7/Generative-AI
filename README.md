# Generative-AI
This code creates an intelligent voice assistant using Google's Gemini API, integrated into a Flask web application. It:

Configures the AI ​​model (Gemini 1.5 Pro) with a Google API key

Manages a contextual conversation while preserving the conversation history

Optimizes responses to be clear and concise (without unnecessary digressions)

Provides a web interface (via Flask) with:

A home page (/)

An API endpoint (/process_voice) to process voice requests and return responses in JSON

Compares text similarities (via difflib) for potential user input analysis

How it works:
The user sends a voice request → The AI ​​generates a targeted response → The conversation history is updated and returned to the interface.

Note: Replace "your api key" with a real Google API key to make it work.

Clic on le lien below:
![image](https://github.com/user-attachments/assets/0530f464-3184-4c26-878b-4b40923a375e)


Then make your prompt :
![image](https://github.com/user-attachments/assets/26f50116-d963-4d23-a5a8-085249e50520)

And ask a question like what s the role of the data scientist ?
![image](https://github.com/user-attachments/assets/aa527312-3d96-45bb-84ff-4d00631fc94e)




