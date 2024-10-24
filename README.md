AI Chat Application
This project is a simple AI chat application where users can input text, and the application fetches a response from a generative AI model using an API.

Features
User Chat Interface: Users can input text in a chat-like interface.
AI Response: The app fetches responses from a generative AI model based on the user's input.
Loading Indicator: A loading animation is shown while the AI response is being fetched.
Clean UI: The chat interface supports both user and AI message boxes.
Technologies Used
HTML
CSS
JavaScript
Fetch API for making asynchronous API requests
Google Gemini API for generating AI responses
Getting Started
Prerequisites
Before running this application, make sure you have the following:

A valid Google API key for accessing the Gemini language model.
Basic knowledge of HTML, CSS, and JavaScript.
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ai-chat-app.git
cd ai-chat-app
Update API Key:

Replace the placeholder "EnterYourAPIKeyHere" in the JavaScript code with your actual API key.

javascript
Copy code
let Api_url = "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent?key=YourApiKey";
Open the app:

Open the index.html file in your browser to run the chat application.

How It Works
User Input: The user enters a message in the chat prompt.
API Call: When the user submits the message, the app sends a request to the Gemini API to generate a response based on the user's message.
AI Response: The AI's response is displayed in a chat bubble below the user's message.
Loading Indicator: While the response is being generated, a loading GIF is displayed.
Code Overview
index.html: The main HTML structure of the chat application.
styles.css: The CSS file containing styles for the chat interface.
app.js: The JavaScript file where the core logic for handling user input, making API requests, and displaying responses is implemented.
Example

Future Enhancements
Add support for rich text responses.
Implement error handling for failed API requests.
Add more customization options for users.
