## License
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# ChatGPT++
ChatGPT is a web application that allows you to chat with OpenAI's GPT-3.5 Turbo AI model. The application can speak out loud response messages, learn new things, and save your conversations to your local machine. You can also use the same model with ChatGPT Plus for a very low cost. You can also share with your friends, and the OpenAI account offers $18 free to use as ChatGPT Plus for 3-6 months or more.

## Features
ChatGPT++ has the following features:
- Speakable response: The AI's response can be spoken aloud by your browser.
- Teachable AI: You can easy to teach the AI new things by providing it with examples of how to respond to certain inputs.
- Local data storage: Your conversations with the AI are stored locally on your machine using the browser's local storage API. No login is required to use this app.
- Responsive design : You can use both PC or Mobile. I will update for tablet after.

## Usage
To use ChatGPT:
1. Visit the live website [here](https://github.com/linjaboss/ChatGPT-ReactJS-OpenAI). You can use yourself openai api key. (On Right Bar)
2. Enter your message in the text box and press "Send" to send it to the AI.
3. The AI's response will be displayed below your message.
4. To teach the AI a new response, click the "New Teach" button at the left bar next to the AI's response. Then, enter one or more examples of inputs that should trigger this response.

## Installation On Node Environment
1. Clone this repository to your local machine:
```bash
git clone https://github.com/linjaboss/ChatGPT-ReactJS-OpenAI
```
OPTIONS: If you want to set up a freetoken, you need to create a `.env` file on the same level as `package.json`. The content should be in this format:
Content will this format : 
```
  REACT_APP_GPT_TOKENS=sk-*******,sk-******,sk-****
```
You can set up only one, but when you set up an array, every time a user sends a message, the application will automatically pick a token to add to the request header.

2. Install the required dependencies using Yarn or NPM:
```bash
  npm install
```

3. Start the development server:
```bash
  npm start
```
## Security
This application only serves to help you connect to OpenAI. If you want to secure your application, you will need a backend for that purpose.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
You can use for any purpose. If you can, please give me a feed back.
