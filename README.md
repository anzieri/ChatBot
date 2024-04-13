# AI ChatBot 

Think ChatGPT but better. This AI Chatbot is called "Cloud AI" and is a simple web application that uses HTML, CSS and Javascript only. It integrates the uses of Google's Gemini 1.0 pro API which unlike OpenAI's ChatGPT has an unlimited number of tokens. 

## How it Works

If you understand what promises and async functions are then this is going to be a breeeze. Otherwise for those that don't, the async keyword transforms a regular JavaScript function into an asynchronous function, causing it to return a Promise. The await keyword is used inside an async function to pause its execution and wait for a Promise to resolve before continuing. A promise is a debt. Basically the webapp sends in a request to an API and waits for the response from that API in form of a promise. 

Integration of the Gemini AI API can be found on their main site link https://ai.google.dev/docs. This link contains integrations for beyond JavaScript as well. This means if you have an interest in using it on your Python, Flutter, Swift, Node and others, you can with ease. 

A prompt is input into the textfield which is then sent to the API. The response is processed and a reply is received from the AI model in Markdown format. The text then has to be formatted appropriately to create a readable more user friendly look.

Link to a hosted version of this link https://chatbot2-qmj5.onrender.com/
