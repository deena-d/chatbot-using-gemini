# Google Generative AI Chat Server

This project sets up a chat server using Google Generative AI, allowing users to interact with a generative model through a web interface.

## Installation

1. Clone the repository to your local machine:

```bash
git clone <repository_url>
Install dependencies:
bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root directory of the project.
Add your Google Generative AI API key to the .env file:
plaintext
Copy code
API_KEY=your_api_key_here
Usage
Start the server:
bash
Copy code
npm start
Open a web browser and navigate to http://localhost:3000 to access the chat interface.

Interact with the chat interface by sending messages and receiving responses from the generative model.

Configuration
MODEL_NAME: Specify the name of the generative model to use.
API_KEY: Set your Google Generative AI API key.
Endpoint
/chat: POST request to this endpoint with a JSON body containing the user input to start a chat session with the generative model.
Safety Settings
You can configure safety settings for the chat sessions by adjusting the safetySettings array in the runChat function. These settings help filter out harmful content based on predefined categories and thresholds.

Contributing
Contributions are welcome! Feel free to open issues or pull requests to suggest improvements or report bugs.

License
This project is licensed under the MIT License.

csharp
Copy code

You can add this README file to your project repository to provide information about setting up and using the chat server with Google Generative AI.

## Demo video



https://github.com/deena-d/chatbot-using-gemini/assets/107647091/6158c40f-1ea4-46a6-afdc-848a360b17c7




